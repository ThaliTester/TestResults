#### Test 80807573a8c39da_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
08-17 19:50:37.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
08-17 19:50:37.613  6751  6751 D AndroidRuntime: 
08-17 19:50:37.613  6751  6751 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 19:50:37.613  6751  6751 D AndroidRuntime: CheckJNI is OFF
08-17 19:50:37.613  6751  6751 D AndroidRuntime: readGMSProperty: start
08-17 19:50:37.613  6751  6751 D AndroidRuntime: readGMSProperty: already setted!!
08-17 19:50:37.613  6751  6751 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 19:50:37.623  6751  6751 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 19:50:37.623  6751  6751 D AndroidRuntime: readGMSProperty: end
08-17 19:50:37.623  6751  6751 D AndroidRuntime: addProductProperty: start
08-17 19:50:37.723   287   287 E SMD     : DCD OFF
08-17 19:50:37.753  6751  6751 E AffinityControl: AffinityControl: registerfunction enter
08-17 19:50:37.783  6751  6751 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 19:50:37.793  1014  4019 E PersonaManagerService: inState():  stateMachine is null !!
08-17 19:50:37.793  1014  4019 I PersonaManagerService: PersonaId don't exist
08-17 19:50:37.793  1014  4019 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 19:50:37.793  1014  4019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-17 19:50:37.813  1014  4019 W ActivityManager: mDVFSHelper.acquire()
08-17 19:50:37.813  1014  4019 D FocusedStackFrame: Set to : 0
08-17 19:50:37.823  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 19:50:37.823  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:37.823  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 19:50:37.823  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:37.823  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:37.823  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:37.833  6762  6762 E Zygote  : MountEmulatedStorage()
08-17 19:50:37.833  6762  6762 E Zygote  : v2
08-17 19:50:37.833  6762  6762 I libpersona: KNOX_SDCARD checking this for 10171
08-17 19:50:37.833  6762  6762 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:37.833  1014  4019 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6762 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 19:50:37.833  1014  4019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-17 19:50:37.833  1014  4019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:50:37.833  1014  4019 D InputDispatcher: Focused application set to: xxxx
08-17 19:50:37.833  1014  4019 D InputDispatcher: Focus left window: 1478
08-17 19:50:37.833  6751  6751 D AndroidRuntime: Shutting down VM
08-17 19:50:37.833  6762  6762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:50:37.833  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:50:37.833  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 19:50:37.843   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-17 19:50:37.843  6762  6762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:37.843  6762  6762 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 19:50:37.863  6762  6762 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:37.863  6762  6762 D ActivityThread: Added TimaKeyStore provider
08-17 19:50:37.863  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:50:37.863  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:50:37.863  1014  1477 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-17 19:50:37.863  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 19:50:37.883  1014  1477 D PersonaManager: isKioskContainerExistOnDevice
08-17 19:50:37.933   257   451 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-17 19:50:37.933   257  1101 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-17 19:50:37.933  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{3f12b9e7 token=android.os.BinderProxy@3031a1dc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-17 19:50:37.933  1478  1478 D Launcher: onTrimMemory. Level: 20
08-17 19:50:38.023  6762  6762 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-17 19:50:38.043  6751  6751 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 19:50:38.063  6762  6762 I cr.library_loader: Time to load native libraries: 6 ms (timestamps 9397-9403)
08-17 19:50:38.063  6762  6762 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 19:50:38.083  6762  6762 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ec62c96}
08-17 19:50:38.083  6762  6762 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 19:50:38.093  6762  6762 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 19:50:38.123  6762  6762 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-17 19:50:38.123  6762  6762 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:50:38.133  6762  6762 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 19:50:38.163  6762  6762 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:50:38.163  6762  6762 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:50:38.163  6762  6762 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:50:38.163  6762  6762 I Adreno-EGL: Local Branch: 
08-17 19:50:38.163  6762  6762 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:50:38.163  6762  6762 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:50:38.163  6762  6762 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 19:50:38.243  6762  6762 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:50:38.253  6762  6762 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-17 19:50:38.253  6762  6762 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-17 19:50:38.263  6762  6762 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-17 19:50:38.263  6762  6762 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-17 19:50:38.353   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
08-17 19:50:38.373  6762  6762 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:50:38.383  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{2edfa8c5 u0 com.test.thalitest/.MainActivity t3}
08-17 19:50:38.393  6762  6762 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 19:50:38.403  6762  6762 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 19:50:38.403  6762  6762 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-17 19:50:38.413  6762  6762 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-17 19:50:38.413  6762  6762 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:50:38.413  6762  6762 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:50:38.543  6762  6803 D OpenGLRenderer: Render dirty regions requested: true
08-17 19:50:38.543  1014  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 19:50:38.543  1014  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:50:38.553  1014  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 19:50:38.553  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:50:38.553  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 19:50:38.553  6762  6790 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-17 19:50:38.563  6762  6762 V ActivityThread: updateVisibility : ActivityRecord{2677adf6 token=android.os.BinderProxy@3420831b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-17 19:50:38.563  6762  6762 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:50:38.563  6762  6762 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 19:50:38.573   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-17 19:50:38.583  1014  1476 D InputDispatcher: Focus entered window: 6762
08-17 19:50:38.593  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:50:38.593  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:50:38.593  6762  6762 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-17 19:50:38.593  6762  6803 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 19:50:38.593  6762  6803 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-17 19:50:38.603  6762  6803 D OpenGLRenderer: Enabling debug mode 0
08-17 19:50:38.623  1014  1472 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-17 19:50:38.633  1177  1177 I StatusBar: Icon Only
08-17 19:50:38.633  1177  1177 D PanelView: There is/are notification(s) 
08-17 19:50:38.633  1014  6808 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-17 19:50:38.643  1014  1045 I ActivityManager: Displayed Component not be shown by security: +756ms (total +5s823ms)
08-17 19:50:38.643  1014  1045 W ActivityManager: mDVFSHelper.release()
08-17 19:50:38.643  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2edfa8c5 u0 com.test.thalitest/.MainActivity t3} time:119984
08-17 19:50:38.653  6762  6762 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-17 19:50:38.653  6762  6762 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3420831b time:119991
08-17 19:50:38.653   257  1101 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-17 19:50:38.653   257   454 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-17 19:50:38.653  1861  1861 I SamsungIME: getCurrentCandidateView
08-17 19:50:38.663  1014  1093 V AlarmManager: waitForAlarm result :4
08-17 19:50:38.673  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
08-17 19:50:38.683  2035  2035 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
08-17 19:50:38.683  6762  6762 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6762
08-17 19:50:38.723  1014  4020 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:50:38.723  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
08-17 19:50:38.723  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:38.723  1014  4020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:38.723  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:50:38.793  1861  1861 D SamsungIME: Dismiss ExpandCandiate
08-17 19:50:38.793  4728  4728 D ConnectivityManager: CallingUid : 10011, CallingPid : 4728
08-17 19:50:38.803  1014  1026 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:50:38.803  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-17 19:50:38.803  1014  1127 D ConnectivityService: apparently satisfied.  currentScore=60
08-17 19:50:38.803  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-17 19:50:38.803  4728  6815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:50:38.853  4728  6816 W DriveInitializer: Background init thread started
,08-17 19:50:38.883   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-17 19:50:38.883   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:50:38.883  4728  6816 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-17 19:50:38.923  2035  2035 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-17 19:50:38.963  4728  6816 W DriveInitializer: Background init thread ended
,08-17 19:50:38.983  6762  6762 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 19:50:38.983  1861  1861 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:50:38.983  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:50:38.983  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-17 19:50:38.983  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:38.983  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:38.983  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.013  1014  1026 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-17 19:50:39.023  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-17 19:50:39.033  1014  4019 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:50:39.033  1014  4019 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-17 19:50:39.033  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:39.033  1014  4019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.033  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.043  1861  1861 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:50:39.063  1861  1861 I SamsungIME: KeybaordView init() : load resources
,08-17 19:50:39.063  4728  6826 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-17 19:50:39.063  4728  6826 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-17 19:50:39.063  6762  6807 D jxcore_app_log: JniHelper::setJavaVM(0xb85fa2b0), pthread_self() = -1195878272
,08-17 19:50:39.083  6762  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 19:50:39.083  6762  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 19:50:39.083  6762  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 19:50:39.083  6762  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 19:50:39.083  6762  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 19:50:39.083  6762  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19aee3fc added. We now have 1 listener(s)
,08-17 19:50:39.093  1861  1861 I SamsungIME: getCurrentKeyboard
08-17 19:50:39.093  1861  1861 I SamsungIME: getTextKeyboard
,08-17 19:50:39.093  6762  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-17 19:50:39.093  6762  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:50:39.093  6762  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:50:39.093  6762  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 19:50:39.103  6762  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1124690b added. We now have 1 listener(s)
,08-17 19:50:39.103  6762  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:39.113  6762  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:50:39.113  6762  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 19:50:39.113  6762  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 19:50:39.113  6762  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 19:50:39.113  6762  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 19:50:39.113  6762  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:39.113  6762  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-17 19:50:39.123  6762  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-17 19:50:39.123  1861  1861 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:39.123  6762  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:50:39.123  6762  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 19:50:39.123  6762  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:50:39.123  6762  6807 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 19:50:39.133  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:39.133  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:39.143  2035  2035 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:50:39.173  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:39.173  6762  6762 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 19:50:39.173  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.173  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.293  1014  1333 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:50:39.303  1014  1333 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-17 19:50:39.303  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:39.303  1014  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:50:39.303  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.333  1014  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:50:39.333  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-17 19:50:39.333  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:39.333  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.333  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.393  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:39.393  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:39.393  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.393  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.403  1014  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:39.403  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:39.403  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.403  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.453  1014  1213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:39.453  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:39.453  1014  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.453  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.453  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:39.453  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:39.453  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:39.453  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:39.473  6833  6833 E Zygote  : MountEmulatedStorage(),
08-17 19:50:39.473  6833  6833 E Zygote  : v2
08-17 19:50:39.473  6833  6833 I libpersona: KNOX_SDCARD checking this for 10011
08-17 19:50:39.473  6833  6833 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:39.473  6833  6833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:50:39.473  1014  1213 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6833 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-17 19:50:39.473  6833  6833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:39.473  6833  6833 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:50:39.503  6833  6833 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:39.503  6833  6833 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:39.503  2035  6830 I art     : Explicit concurrent mark sweep GC freed 73123(4MB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 10MB/17MB, paused 4.553ms total 117.790ms
,08-17 19:50:39.533  6833  6833 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 19:50:39.533  6833  6833 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 19:50:39.573  6833  6833 I MultiDex: VM with version 2.1.0 has multidex support
08-17 19:50:39.573  6833  6833 I MultiDex: install
08-17 19:50:39.573  6833  6833 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 19:50:39.603  6833  6833 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-17 19:50:39.663  6833  6833 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-17 19:50:39.663  6833  6833 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ab90132: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-17 19:50:39.663  6833  6833 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-17 19:50:39.693  6833  6833 D ChimeraCfgMgr: Reading stored module config
,08-17 19:50:39.763  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-17 19:50:39.773  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:39.773  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:39.773  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.773  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.783  1014  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:39.783  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:39.793  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:50:39.793  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.793  6833  6850 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-17 19:50:39.813  6833  6833 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-17 19:50:39.813  6833  6833 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-17 19:50:39.833  2035  2035 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=69f7c9e2-61f4-4b62-8fb6-2cddf30cd1fb
,08-17 19:50:39.843  1014  4020 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 19:50:39.843  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-17 19:50:39.853  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:39.853  1014  4020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.853  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:50:39.853  2035  2035 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:50:39.863  2035  2035 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:50:39.903  4231  4329 I art     : Explicit concurrent mark sweep GC freed 2137(81KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 665us total 28.730ms
,08-17 19:50:39.943  1014  4020 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:39.943  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:39.953  1014  4020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:39.953  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:39.953   282   672 D WVCdm   : Instantiating CDM.
,08-17 19:50:39.953   282   282 I WVCdm   : CdmEngine::OpenSession
,08-17 19:50:39.953   282   282 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-17 19:50:39.973   282   282 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-17 19:50:39.993   282   282 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-17 19:50:40.053   282   282 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-17 19:50:40.053   282   670 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-17 19:50:40.063   282   670 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,08-17 19:50:40.063   282   670 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-17 19:50:40.063   282   670 D WVCdm   : PrepareKeyRequest: nonce=3105449655
,08-17 19:50:40.073  6762  6828 W jxcore-log: Initializing JXcore engine
08-17 19:50:40.073  6762  6828 W jxcore-log: JXcore engine is ready
,08-17 19:50:40.113  6833  6846 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-17 19:50:40.113  6833  6846 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:40.113  6833  6846 I System.out: (HTTPLog)-Static: isShipBuild true
08-17 19:50:40.113  6833  6846 I System.out: (HTTPLog)-Thread-1235-924449751: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-17 19:50:40.113  2035  2201 W GCoreFlp: No location to return for getLastLocation()
,08-17 19:50:40.113  6833  6846 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:40.123   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:50:40.123   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 19:50:40.143  1994  1994 E audit   : type=1400 msg=audit(1471456240.143:205): avc:  denied  { ioctl } for  pid=6828 comm="Thread-1256" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 19:50:40.143  1994  1994 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:40.143  1994  1994 E audit   : type=1300 msg=audit(1471456240.143:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9de028f8 items=0 ppid=309 ppcomm=main pid=6828 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1256" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 19:50:40.143  1994  1994 E audit   : type=1320 msg=audit(1471456240.143:205): 
,08-17 19:50:40.153  6762  6828 W jxcore-log: Starting JXcore engine
08-17 19:50:40.153  1014  1465 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:40.153  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:40.163  1014  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:40.163  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:40.163  6833  6846 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:50:40.163  1014  4019 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:40.163  6833  6846 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6833, getuid(): 10011
,08-17 19:50:40.173  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:40.173  1014  4019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:40.173  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:40.173  1014  1333 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:40.173  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:40.173  1014  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:50:40.173  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:40.193  4728  6829 D UdcContextInitService: registered all accounts: true
,08-17 19:50:40.203  2035  2204 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 19:50:40.223  2035  2219 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-17 19:50:40.283  6762  6828 W jxcore-log: Platform android
08-17 19:50:40.283  6762  6828 W jxcore-log: 
08-17 19:50:40.283  6762  6828 W jxcore-log: Process ARCH arm
08-17 19:50:40.283  6762  6828 W jxcore-log: 
,08-17 19:50:40.433  6833  6846 I qtaguid : Untagging socket 30
,08-17 19:50:40.543  1014  3350 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:50:40.543  1014  1213 I art     : Explicit concurrent mark sweep GC freed 28395(1498KB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 2.284ms total 156.248ms
,08-17 19:50:40.583  6762  6828 I jxcore-log: JXcore Cordova bridge is ready!
08-17 19:50:40.583  6762  6828 I jxcore-log: 
,08-17 19:50:40.583  6762  6828 W jxcore-log: JXcore engine is started
,08-17 19:50:40.583  6762  6807 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 19:50:40.583  6762  6762 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 19:50:40.663  1014  1472 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 19:50:40.663  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-17 19:50:40.663  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:40.663  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:40.663  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:40.723   287   287 E SMD     : DCD OFF
,08-17 19:50:41.163  6861  6861 I dex2oat : ----------------------------------------------------
08-17 19:50:41.163  6861  6861 I dex2oat : <SS>: S T A R T I N G . . .
08-17 19:50:41.163  6861  6861 I dex2oat : <SS>: Zip is absent. Canceled.
,08-17 19:50:41.163  6861  6861 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-17 19:50:41.223  6861  6861 I dex2oat : dex2oat took 61.627ms (threads: 4)
,08-17 19:50:41.233  6833  6846 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:50:41.233  6833  6846 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:50:41.233  6833  6846 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:50:41.233  6833  6846 I Adreno-EGL: Local Branch: 
08-17 19:50:41.233  6833  6846 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:50:41.233  6833  6846 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:50:41.233  6833  6846 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:50:41.313  6833  6846 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:50:41.313  6833  6846 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:50:41.313  6833  6846 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:50:41.313  6833  6846 I Adreno-EGL: Local Branch: 
08-17 19:50:41.313  6833  6846 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:50:41.313  6833  6846 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:50:41.313  6833  6846 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:50:41.353  6833  6846 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:50:41.353  6833  6846 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:50:41.353  6833  6846 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:50:41.353  6833  6846 I Adreno-EGL: Local Branch: 
08-17 19:50:41.353  6833  6846 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:50:41.353  6833  6846 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:50:41.353  6833  6846 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:50:41.463  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 19:50:41.463  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-17 19:50:41.463  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:41.463  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:41.463  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:41.503  2035  6831 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-17 19:50:41.503  2035  6831 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:50:41.503  2035  6831 I System.out: (HTTPLog)-Static: isShipBuild true
08-17 19:50:41.503  2035  6831 I System.out: (HTTPLog)-Thread-272-379053157: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-17 19:50:41.503  2035  6831 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:41.503   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:50:41.503   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 19:50:41.503  2035  6831 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:50:41.503  2035  6831 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2035, getuid(): 10011
,08-17 19:50:41.553  2035  6831 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2035, getuid(): 10011
,08-17 19:50:41.683   282   672 I WVCdm   : CdmEngine::CloseSession
,08-17 19:50:41.693   282   672 I WVCdm   : L3 Terminate.
,08-17 19:50:41.743  1014  3326 D SSRM:n  : SIOP:: AP = 330
,08-17 19:50:41.763  2035  2219 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 19:50:41.763  2035  2219 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-17 19:50:41.763  2035  2219 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-17 19:50:40.341+0200, stopTime=2016-08-17 19:50:41.773+0200, duration=1432ms
,08-17 19:50:41.783  2035  6875 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:41.783   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:50:41.783   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 19:50:41.783  2035  6875 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:50:41.793  2035  6875 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2035, getuid(): 10011
,08-17 19:50:41.833  2035  6875 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2035, getuid(): 10011
,08-17 19:50:41.843  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 19:50:42.083  2035  6875 I qtaguid : Untagging socket 65
,08-17 19:50:42.113  1014  1323 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:50:42.113  1014  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-17 19:50:42.113  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.113  1014  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:42.113  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.143  2035  2219 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-17 19:50:42.203  1014  1323 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:42.203  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.203  1014  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:42.203  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.293  2035  6878 I art     : Explicit concurrent mark sweep GC freed 54827(2MB) AllocSpace objects, 10(468KB) LOS objects, 40% free, 11MB/19MB, paused 1.387ms total 71.648ms
,08-17 19:50:42.303  1014  4020 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:42.313  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.313  1014  4020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:50:42.313  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.363  1014  4019 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:42.363  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.363  1014  4019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:42.363  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.363  2035  6880 E CommitToConfigurationOperation: Malformed snapshot token (size): ,
,08-17 19:50:42.363  2035  6878 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:50:42.363  1014  4020 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:42.363  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.363  1014  4020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:42.363  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.393  1014  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:42.393  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.393  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:42.393  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.393  2035  6880 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 19:50:42.393  2035  6878 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:50:42.393  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:42.393  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.393  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:50:42.393  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.423  1014  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:42.423  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:42.423  1014  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:42.423  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:42.433  2035  6880 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 19:50:42.433  2035  6878 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:50:42.433  2035  6878 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-17 19:50:42.433  2035  6878 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 19:50:42.483  1014  1323 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:50:42.523  2035  6878 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
08-17 19:50:42.523   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:50:42.523   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 19:50:42.533  2035  6878 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
08-17 19:50:42.533  2035  6878 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2035, getuid(): 10011
,08-17 19:50:42.573  2035  6878 I qtaguid : Tagging socket 80 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2035, getuid(): 10011,
,08-17 19:50:42.813  1014  1477 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:50:42.823  2035  6878 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:42.823  2035  6878 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2035, getuid(): 10011
,08-17 19:50:42.963  1014  4020 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:50:42.963  2035  6878 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:42.963  2035  6878 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2035, getuid(): 10011
,08-17 19:50:43.103  1014  1026 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:50:43.113  2035  6878 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:43.113  2035  6878 I qtaguid : Tagging socket 77 with tag 1106541400000000{285627412,0} for uid -1, pid: 2035, getuid(): 10011
,08-17 19:50:43.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:50:43.723   287   287 E SMD     : DCD OFF,
,08-17 19:50:43.913  2035  6873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:50:43.913  2035  6873 I qtaguid : Tagging socket 65 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2035, getuid(): 10011
,08-17 19:50:44.193  2035  6873 I qtaguid : Untagging socket 65
,08-17 19:50:44.203  2035  2219 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-17 19:50:44.233  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 19:50:44.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:50:44.933  1014  1465 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-17 19:50:44.933  1014  1465 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:50:44.933  1014  1465 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-17 19:50:44.933  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:50:44.943  1014  1014 I MotionRecognitionService: Plugged
08-17 19:50:44.943  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-17 19:50:44.943  1014  1465 D BatteryService: stay LED for fully charged
,08-17 19:50:44.943  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:50:44.943  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:50:44.943  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:50:44.943  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:50:44.963  3153  3153 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:50:44.963  3153  3253 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:50:44.973  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:50:44.973  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:50:44.973  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:50:45.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:50:46.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:50:46.443  1014  1486 I ActivityManager: Killing 6390:com.sec.pcw.device/1000 (adj 15): empty #21
,08-17 19:50:46.723   287   287 E SMD     : DCD OFF
,08-17 19:50:47.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:50:47.873  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-17 19:50:48.363   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-17 19:50:49.723   287   287 E SMD     : DCD OFF
,08-17 19:50:51.793  1014  3326 D SSRM:n  : SIOP:: AP = 340,
,08-17 19:50:52.733   287   287 E SMD     : DCD OFF
,08-17 19:50:53.713  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 19:50:53.713  6762  6828 I jxcore-log: 
,08-17 19:50:53.713  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 19:50:53.713  6762  6828 I jxcore-log: 
,08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:53.723  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:53.723  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:53.723  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 19:50:53.723  6762  6828 I jxcore-log: 
,08-17 19:50:53.723  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 19:50:53.723  6762  6828 I jxcore-log: 
,08-17 19:50:54.173  6762  6828 D ExecuteNativeTests: Running unit tests
,08-17 19:50:54.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:50:54.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a added. We now have 2 listener(s)
,08-17 19:50:54.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:50:54.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:50:54.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:50:54.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:50:54.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb added. We now have 2 listener(s)
08-17 19:50:54.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:54.263  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:50:54.263  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:54.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:54.263  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:54.263  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:50:54.273  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:50:54.273  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:54.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:50:54.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:50:54.273  6762  6828 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 19:50:54.273  6762  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:50:54.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:50:54.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:50:54.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 19:50:54.273  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:54.273  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.273  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.273  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.273  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:50:54.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:50:54.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a removed from the list
08-17 19:50:54.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb removed from the list
08-17 19:50:54.273  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.273  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.273  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.273  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.283  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.283  6762  6828 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 19:50:54.283  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:54.283  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.283  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.283  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.283  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.283  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.283  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.283  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.283  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.283  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.283  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.283  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.283  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:50:54.293  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.293  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.293  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.293  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.293  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.293  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.293  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.293  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.293  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.293  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.293  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.293  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.293  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.293  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.293  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.293  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.293  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.293  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.293  6762  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:50:54.293  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:54.303  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:50:54.303  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.303  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:50:54.303  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:50:54.303  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:50:54.303  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:50:54.303  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:54.303  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:50:54.303  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:50:54.303  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:54.313  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:54.313  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:50:54.323  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:50:54.323  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 19:50:54.333  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 19:50:54.333  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:50:54.333  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:50:54.333  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:50:54.343  3153  3254 D BtGatt.GattService: registerClient() - UUID=ebeef19a-e928-43cc-9c29-2b9cb1b56997
,08-17 19:50:54.393  3153  3246 D BtGatt.GattService: onClientRegistered() - UUID=ebeef19a-e928-43cc-9c29-2b9cb1b56997, clientIf=6
,08-17 19:50:54.393  6762  6777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:50:54.393  3153  3161 D BtGatt.GattService: start scan with filters
,08-17 19:50:54.403  3153  3252 D BtGatt.ScanManager: handling starting scan
,08-17 19:50:54.403  3153  3252 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:50:54.413  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:50:54.413  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:50:54.413  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:50:54.413  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:50:54.413  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:54.413  3153  3246 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:50:54.413  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.413  3153  3252 D BtGatt.ScanManager: allow scan with filters
,08-17 19:50:54.413  3153  3252 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:50:54.423  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:50:54.423  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:50:54.423  3153  3252 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 19:50:54.423  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:50:54.423  3153  3246 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:50:54.423  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.433  3153  3252 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:50:54.433  3153  3252 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:50:54.433  6762  6828 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:50:54.433  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:54.433  6762  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:50:54.433  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.433  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:50:54.433  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.433  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:50:54.433  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:50:54.433  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:50:54.433  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:50:54.433  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:50:54.433  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:50:54.433  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:50:54.433  3153  3162 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:50:54.443  3153  3254 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:50:54.443  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:50:54.443  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:50:54.443  3153  3246 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:50:54.443  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:50:54.443  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:50:54.443  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:50:54.443  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:50:54.443  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:54.443  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.443  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.443  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:50:54.443  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.443  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.453  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.453  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.453  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.453  6762  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:50:54.453  3153  3246 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:50:54.453  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.453  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:54.453  3153  3252 D BtGatt.ScanManager: filter size is 1
,08-17 19:50:54.453  3153  3252 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 19:50:54.463  3153  3246 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:50:54.463  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:50:54.463  3153  3252 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:54.463  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:54.463  3153  3246 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:50:54.463  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.463  3153  3252 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:50:54.463  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:54.463  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:50:54.463  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.463  3153  3246 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:50:54.463  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:50:54.463  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:50:54.463  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:50:54.463  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:50:54.463  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:54.473  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:50:54.473  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.473  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:50:54.473  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:50:54.483  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:50:54.483  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:50:54.483  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:50:54.483  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:50:54.483  3153  3162 D BtGatt.GattService: registerClient() - UUID=ab11d911-6be5-42e3-acfa-7c2d8fd07cf1
,08-17 19:50:54.523  3153  3246 D BtGatt.GattService: onClientRegistered() - UUID=ab11d911-6be5-42e3-acfa-7c2d8fd07cf1, clientIf=6
,08-17 19:50:54.533  6762  6776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:50:54.533  3153  3161 D BtGatt.GattService: start scan with filters
,08-17 19:50:54.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:50:54.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:50:54.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:50:54.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:50:54.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:54.533  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:54.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:50:54.543  3153  3252 D BtGatt.ScanManager: handling starting scan
,08-17 19:50:54.543  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:50:54.543  6762  6828 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:50:54.543  3153  3246 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:50:54.543  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.543  3153  3252 D BtGatt.ScanManager: allow scan with filters
,08-17 19:50:54.543  3153  3252 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:50:54.553  3153  3252 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 19:50:54.553  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:54.553  6762  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:50:54.553  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:54.553  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:50:54.553  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:50:54.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 19:50:54.553  3153  3246 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:50:54.553  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:50:54.553  3153  3252 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:50:54.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:50:54.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:50:54.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:50:54.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:50:54.553  3153  3252 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 19:50:54.563  3153  3254 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:50:54.563  3153  3162 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:50:54.563  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:50:54.563  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:50:54.563  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:50:54.563  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.563  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-17 19:50:54.563  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list,
08-17 19:50:54.563  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:54.563  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.563  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.563  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:54.563  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:50:54.563  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:54.563  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.563  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.573  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.573  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:54.573  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.573  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.573  6762  6828 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:50:54.573  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:54.573  3153  3246 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-17 19:50:54.573  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:54.583  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:54.583  3153  3246 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:50:54.583  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.583  3153  3252 D BtGatt.ScanManager: filter size is 1
08-17 19:50:54.583  3153  3252 D BtGatt.ScanManager: delete FilterIndex - 4
,08-17 19:50:54.583  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.583  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:50:54.583  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:50:54.583  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:50:54.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:50:54.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:54.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:50:54.593  3153  3246 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:50:54.593  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:50:54.593  3153  3252 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:50:54.593  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.593  3153  3246 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:50:54.593  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:50:54.593  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:50:54.593  3153  3252 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:50:54.603  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.603  3153  3246 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:50:54.603  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.603  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:50:54.603  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:50:54.613  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:50:54.613  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:50:54.613  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:50:54.613  3153  3254 D BtGatt.GattService: registerClient() - UUID=1b756c00-8093-4a0a-9730-5f802dd7926e
,08-17 19:50:54.653  3153  3246 D BtGatt.GattService: onClientRegistered() - UUID=1b756c00-8093-4a0a-9730-5f802dd7926e, clientIf=6,
,08-17 19:50:54.653  6762  6776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:50:54.663  3153  3161 D BtGatt.GattService: start scan with filters
,08-17 19:50:54.663  3153  3252 D BtGatt.ScanManager: handling starting scan
,08-17 19:50:54.663  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:50:54.663  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:50:54.663  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:50:54.663  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:50:54.663  3153  3246 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:50:54.663  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.673  3153  3252 D BtGatt.ScanManager: allow scan with filters
,08-17 19:50:54.673  3153  3252 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:50:54.673  3153  3252 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-17 19:50:54.673  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:50:54.673  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:50:54.673  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:54.673  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:50:54.673  3153  3246 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:50:54.673  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.683  3153  3252 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:50:54.683  3153  3252 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:50:54.683  6762  6828 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:50:54.683  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.683  6762  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:50:54.683  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.683  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:50:54.683  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.683  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:50:54.683  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:50:54.683  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:50:54.683  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:50:54.683  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:50:54.683  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:50:54.683  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:50:54.683  3153  3162 D BtGatt.GattService: stopScan() - queue size =1,
,08-17 19:50:54.683  3153  3254 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:50:54.683  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-17 19:50:54.683  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:50:54.683  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:50:54.683  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 19:50:54.683  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:50:54.683  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:50:54.693  3153  3246 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:50:54.693  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.693  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:50:54.693  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:50:54.693  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:50:54.693  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:50:54.693  3153  3246 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:50:54.693  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.693  3153  3252 D BtGatt.ScanManager: filter size is 1
,08-17 19:50:54.693  3153  3252 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 19:50:54.703  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.703  6762  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:50:54.703  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.703  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.703  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.703  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:50:54.703  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.703  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.703  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.703  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.703  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:54.703  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:54.703  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:54.703  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.703  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.703  3153  3246 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 19:50:54.703  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.703  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.703  6762  6828 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 19:50:54.703  3153  3252 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:50:54.703  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.703  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.703  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.703  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.703  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.703  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.703  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.703  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.703  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.703  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.703  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.703  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:54.703  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:54.703  3153  3246 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:50:54.713  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.713  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.713  3153  3252 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:50:54.713  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:50:54.713  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.713  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.713  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.713  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.713  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.713  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.713  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.713  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.713  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.713  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.713  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.713  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.713  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.713  6762  6828 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 19:50:54.713  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.713  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.713  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.713  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.713  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.713  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.713  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.713  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.713  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.713  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.713  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.713  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:54.713  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.713  6762  6828 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-17 19:50:54.713  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.713  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.713  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:50:54.713  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.723  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.723  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.723  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.723  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.723  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.723  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.723  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.723  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.723  3153  3246 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:50:54.723  3153  3246 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.723  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:50:54.723  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:50:54.723  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:50:54.723  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:50:54.723  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.723  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.723  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.723  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.723  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.723  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.723  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.723  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.723  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.723  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.723  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.723  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.723  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.723  6762  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:54.723  6762  6828 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,08-17 19:50:54.723  6762  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:54.723  6762  6828 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:50:54.723  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:50:54.733  6762  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 19:50:54.733  6762  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:50:54.733  6762  6828 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 19:50:54.733  6762  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:54.733  6762  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 19:50:54.733  6762  6828 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 19:50:54.733  6762  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:54.733  6762  6828 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:50:54.733  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 19:50:54.733  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-17 19:50:54.733  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 19:50:54.733  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 19:50:54.733  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 19:50:54.733  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 19:50:54.733  6762  6828 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 19:50:54.733  6762  6828 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:54.733  6762  6828 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-17 19:50:54.733  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.733  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.733  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.733  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.733  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:54.733  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.733  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 19:50:54.733  6762  6891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1320)
08-17 19:50:54.733  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.733  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.733  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.733  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.733  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.733  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.733  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.733  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.743  6762  6828 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 19:50:54.743  6762  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1320
,08-17 19:50:54.743  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.743  6762  6828 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 19:50:54.743  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 19:50:54.743  6762  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:50:54.743  6762  6828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:50:54.743  6762  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:50:54.743  6762  6828 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:50:54.743  6762  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:50:54.743  6762  6828 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 19:50:54.743  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
,08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.743  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.743  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.743  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.743  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Li,stener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.743  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.743  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.743  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.753  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:54.753  6762  6891 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.753  6762  6891 D BluetoothSocket: connect(): myUserId = 0
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 19:50:54.753  6762  6762 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 19:50:54.753  6762  6891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 19:50:54.753  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.753  6762  6762 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:50:54.753  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.753  6762  6893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 19:50:54.753  6762  6893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:54.753  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.753  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.753  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.753  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.753  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.753  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.753  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.753  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.753  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.753  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.753  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.753  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.753  3153  3161 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:50:54.763  6762  6891 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.763  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.763  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:54.763  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:54.763  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:54.763  6762  6762 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-17 19:50:54.763  6762  6828 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 19:50:54.763  6762  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:50:54.763  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:50:54.763  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.763  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.763  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.763  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.763  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.763  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.763  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.763  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.763  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.763  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.763  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.763  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.763  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.763  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.763  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.763  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.763  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.763  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.763  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
08-17 19:50:54.763  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.763  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.763  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.763  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.763  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.763  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.763  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.773  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.773  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:54.773  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:54.773  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:54.773  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.773  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.773  6762  6828 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da2ee9a not in the list
,08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.773  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:54.773  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.773  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:54.773  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:54.773  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:54.773  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:54.773  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@182eb3cb not in the list
,08-17 19:50:54.773  6762  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:50:54.773  6762  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:50:54.773  6762  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-17 19:50:54.773  6762  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:50:54.773  6762  6828 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
08-17 19:50:54.773  6762  6828 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 19:50:54.773  6762  6828 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 19:50:54.773  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:50:54.773  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da36bb5 added. We now have 2 listener(s)
08-17 19:50:54.773  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-17 19:50:54.773  6762  6828 D BluetoothAdapter: enable()
,08-17 19:50:54.783  6762  6828 D BluetoothAdapter: enable(): BT is already enabled..!
,08-17 19:50:54.793  1014  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:50:54.793  1014  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:50:54.793  1014  1495 D SecContentProvider2: mCursor = null
08-17 19:50:54.793  1014  1495 D WifiService: setWifiEnabled: true pid=6762, uid=10171
,08-17 19:50:54.793  1014  1495 W ActivityManager: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-17 19:50:54.803  1014  1495 W WifiService: Failed getting userId using ActivityManagerNative,
08-17 19:50:54.803  1014  1495 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:50:54.803  1014  1495 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:50:54.803  1014  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:50:54.803  1014  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:50:54.803  1014  1495 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:50:54.803  1014  1495 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:50:54.803  1014  1495 D SettingsProvider: name = wifi_on,
08-17 19:50:54.803  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:50:54.803  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c64324a added. We now have 3 listener(s)
08-17 19:50:54.803  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:54.803  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:50:54.803  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d3825bb added. We now have 4 listener(s)
,08-17 19:50:54.803  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:54.813  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:50:54.813  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26093ad8 added. We now have 5 listener(s)
08-17 19:50:54.813  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:54.813  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:50:54.813  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-17 19:50:54.813  1014  1027 D SecContentProvider2: mCursor = null
,08-17 19:50:54.813  1014  1027 D WifiService: setWifiEnabled: false pid=6762, uid=10171
,08-17 19:50:54.813  1014  1027 D SettingsProvider: name = wifi_on
,08-17 19:50:54.823  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 19:50:54.823  1375  1375 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:50:54.823  1375  1375 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-17 19:50:54.823  1375  1375 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:50:54.823  1375  1375 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 19:50:54.823  6762  6828 D BluetoothAdapter: disable()
,08-17 19:50:54.833  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:50:54.843  1014  1333 D SettingsProvider: name = bluetooth_on,
,08-17 19:50:54.843  3153  3242 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-17 19:50:54.843  3153  3242 D BluetoothAdapterProperties: Setting state to 13
08-17 19:50:54.843  3153  3242 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 19:50:54.843  3153  3242 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:50:54.843  3153  3242 D BluetoothAdapterService: updateAdapterState state is 13
08-17 19:50:54.843  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:50:54.843  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:50:54.853  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:54.853  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:54.853  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:50:54.853  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:54.853  3153  3153 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-17 19:50:54.853  3153  3153 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bc47718, channel: 19, state: LISTENING
08-17 19:50:54.853  3153  3153 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1bc47718, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a19a800, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23803571mSocket: android.net.LocalSocket@34455f56 impl:android.net.LocalSocketImpl@3719fbd7 fd:FileDescriptor[74]
08-17 19:50:54.853  3153  3153 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@34455f56 impl:android.net.LocalSocketImpl@3719fbd7 fd:FileDescriptor[74]
08-17 19:50:54.853  1014  1125 E WifiNative-wlan0: do suspend true
,08-17 19:50:54.853  3153  3242 D BluetoothAdapterService: Autoconnection is available 
08-17 19:50:54.853  3153  3242 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 19:50:54.853  3153  3242 D BluetoothAdapterService: terminating service from this receiver
,08-17 19:50:54.853  1305  1305 D BluetoothPbap: Proxy object disconnected
08-17 19:50:54.853  1305  1305 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:50:54.853  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:50:54.853  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:50:54.863  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:54.863  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:54.863  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:54.863  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:54.863  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:50:54.863  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.863  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.863  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:50:54.863  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:50:54.873  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:50:54.873  1177  1177 D BluetoothTile:  getBluetoothState : 13
08-17 19:50:54.873  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:50:54.873  1861  1861 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:50:54.873  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:50:54.873  1014  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:50:54.873  1014  1323 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:50:54.873  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:50:54.873  3153  3153 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b11b7ad, channel: 5, state: LISTENING
08-17 19:50:54.873  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 19:50:54.873  3153  3153 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b11b7ad, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e1cb839, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29501ae2mSocket: android.net.LocalSocket@2c187e73 impl:android.net.LocalSocketImpl@3ce71130 fd:FileDescriptor[76]
,08-17 19:50:54.873  3153  3153 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c187e73 impl:android.net.LocalSocketImpl@3ce71130 fd:FileDescriptor[76]
,08-17 19:50:54.873  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:50:54.873  3153  3153 I BtOppRfcommListener: stopping Accept Thread
08-17 19:50:54.873  3153  3153 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10bf21a9, channel: 12, state: LISTENING
08-17 19:50:54.873  3153  3153 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10bf21a9, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aa5aafb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f59032emSocket: android.net.LocalSocket@b728ecf impl:android.net.LocalSocketImpl@a64105c fd:FileDescriptor[79]
08-17 19:50:54.873  3153  3153 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b728ecf impl:android.net.LocalSocketImpl@a64105c fd:FileDescriptor[79]
,08-17 19:50:54.883  3153  5076 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 19:50:54.883  3153  5076 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 19:50:54.883  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:54.883  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:54.883  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 19:50:54.883  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:54.883  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:54.883  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:50:54.883  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:54.883  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:54.883  3153  3242 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 19:50:54.883  3153  3242 D BluetoothAdapterProperties: mDiscovering is false
,08-17 19:50:54.883  1014  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:50:54.893  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:50:54.893  1014  1465 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:50:54.893  3153  3242 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:50:54.893  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.893  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:54.893  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:54.893  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:54.903  3153  3246 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-17 19:50:54.903  3153  3246 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:50:54.913  3153  3153 V BluetoothOppManager: cleanUp...
,08-17 19:50:54.913  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.913  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:54.923  3153  3242 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 19:50:54.923  3153  3242 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 19:50:54.923  3153  3242 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 19:50:54.923  3153  3242 E bt-btif : cmd socket is not created
08-17 19:50:54.923  1305  1305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:50:54.923  1014  1323 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:50:54.923  1014  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:50:54.923  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:54.923  1014  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:54.923  3153  3265 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 19:50:54.923  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-17 19:50:54.923  3153  3265 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 19:50:54.923  3153  3242 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 19:50:54.923  6762  6891 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@27bb2916, channel: -1, state: INIT
,08-17 19:50:54.923  6762  6891 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@27bb2916, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e396297, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22432c84mSocket: android.net.LocalSocket@425c6d impl:android.net.LocalSocketImpl@3db8c0a2 fd:FileDescriptor[105]
08-17 19:50:54.933  6762  6891 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@425c6d impl:android.net.LocalSocketImpl@3db8c0a2 fd:FileDescriptor[105]
08-17 19:50:54.933  6762  6891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1320)
08-17 19:50:54.933  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:50:54.933  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:50:54.933  3153  3265 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:50:54.943  1305  1305 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:50:54.953  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:50:54.953  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:50:54.953  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 19:50:54.953  1014  1472 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 19:50:54.963  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:54.963  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:54.963  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:54.963  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:54.973  6900  6900 E Zygote  : MountEmulatedStorage()
08-17 19:50:54.973  6900  6900 I libpersona: KNOX_SDCARD checking this for 10055
08-17 19:50:54.973  6900  6900 E Zygote  : v2
08-17 19:50:54.973  6900  6900 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:54.973  1014  1472 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6900 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-17 19:50:54.973  6900  6900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:50:54.983  6900  6900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:54.983  6900  6900 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:54.993  1014  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:50:54.993  1014  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 19:50:54.993  1014  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:50:54.993  1014  1495 D BatteryService: stay LED for fully charged
08-17 19:50:54.993  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:50:55.003  1014  1014 I MotionRecognitionService: Plugged,
08-17 19:50:55.003  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:50:55.003  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:50:55.003  1375  1375 I wpa_supplicant: nl80211: Received scan results (9 BSSes)
,08-17 19:50:55.003  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:50:55.003  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:50:55.003  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-17 19:50:55.003  1014  1124 D WifiP2pService: InactiveState{ what=147461 }
08-17 19:50:55.003  1014  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
08-17 19:50:55.003  1014  1124 D WifiP2pService: DefaultState{ what=147461 }
,08-17 19:50:55.013  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:50:55.013  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:50:55.013  3153  3153 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:50:55.023  3153  3253 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:50:55.023   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:50:55.023  2035  3011 V NativeCrypto: Read error: ssl=0xb8aeff28: I/O error during system call, Connection timed out,
08-17 19:50:55.033  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:50:55.033  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:50:55.033  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-17 19:50:55.033  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:50:55.033  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
08-17 19:50:55.033  2035  3011 V NativeCrypto: SSL shutdown failed: ssl=0xb8aeff28: I/O error during system call, Broken pipe
08-17 19:50:55.033  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 19:50:55.033  2035  3011 E GCM     : Wifi connection closed with errorCode 20
08-17 19:50:55.033  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:50:55.033  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:50:55.033  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:50:55.033  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:50:55.033  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:50:55.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.033  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:50:55.043  6900  6900 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:55.043  6900  6900 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:55.043  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 19:50:55.053  1014  1027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-17 19:50:55.063  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:50:55.063  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:50:55.063  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,08-17 19:50:55.063  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:50:55.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.063  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-17 19:50:55.063  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:50:55.063  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 19:50:55.073  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-24ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:50:55.083  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-25ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
08-17 19:50:55.083  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:50:55.083  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 19:50:55.083  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:50:55.083  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:50:55.083  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:50:55.083  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-17 19:50:55.083  1014  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:50:55.083  1014  1748 I qtaguid : Tagging socket 380 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1014, getuid(): 1000
08-17 19:50:55.083  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer,
,08-17 19:50:55.083  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-17 19:50:55.083  1014  1124 D WifiP2pService: P2pDisablingState
08-17 19:50:55.093  1014  1748 I qtaguid : Untagging socket 380
08-17 19:50:55.093  1014  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:50:55.093  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 19:50:55.093  1014  1124 D WifiP2pService: p2p socket connection lost
,08-17 19:50:55.093  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:50:55.093  1014  1124 D WifiP2pService: P2pDisabledState
,08-17 19:50:55.093  1014  1125 E WifiNative-wlan0: do suspend true
08-17 19:50:55.093  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 19:50:55.093  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:50:55.093  1014  1045 D WifiDisplayController: disconnect
08-17 19:50:55.093  1014  1045 D WifiDisplayController: updateConnection
08-17 19:50:55.093  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:50:55.093  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:50:55.103  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 19:50:55.103  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:50:55.103  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:50:55.103  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:50:55.113  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:50:55.113  6900  6900 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 19:50:55.113  1014  1495 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:50:55.113  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:50:55.123  3153  3265 W bt-btif : ag scb idx 1 not allocated
08-17 19:50:55.123  3153  3265 W bt-btif : ag scb idx 2 not allocated
08-17 19:50:55.123  3153  3265 E bt-btif : BTA AG is already disabled, ignoring ...
,08-17 19:50:55.123  3153  3317 I bt_userial_mct: exiting userial_read_thread
08-17 19:50:55.123  3153  3317 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 19:50:55.133  3153  3246 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 19:50:55.133  3153  3267 I bt_vendor: hw_epilog_process
08-17 19:50:55.133  3153  3246 D bt_userial_mct: userial_close
08-17 19:50:55.133  3153  3246 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 19:50:55.143  6900  6900 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-17 19:50:55.153  6900  6900 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
08-17 19:50:55.153  6900  6900 D UserAnalysis: Create SecureDbHelper
,08-17 19:50:55.153  6900  6900 D IntelligenceServiceApplication: onCreate()
,08-17 19:50:55.153  1014  1465 I ActivityManager: Killing 6417:com.wsomacp/u0a23 (adj 15): empty #21
,08-17 19:50:55.163  6900  6900 D IntelligenceServiceApplication: no applications having user consent for prediction
08-17 19:50:55.163  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-17 19:50:55.163  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.163  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.163  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.163  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:55.173  6923  6923 E Zygote  : MountEmulatedStorage()
08-17 19:50:55.173  6923  6923 E Zygote  : v2
08-17 19:50:55.173  6923  6923 I libpersona: KNOX_SDCARD checking this for 10105
08-17 19:50:55.173  6923  6923 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:55.173  6923  6923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:55.183  6923  6923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:55.183  6923  6923 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-17 19:50:55.183  1014  1026 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6923 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-17 19:50:55.183  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-17 19:50:55.183  6900  6900 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 19:50:55.193  6900  6900 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 19:50:55.203  6923  6923 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-17 19:50:55.203  6923  6923 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:55.223  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 },
08-17 19:50:55.223  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-17 19:50:55.223  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:50:55.223  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:50:55.223  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.223  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.223  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.223  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.223   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:50:55.223   277  1009 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-17 19:50:55.233   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:50:55.233  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 19:50:55.233  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.233  1014  1127 V NetworkStats: updateIfacesLocked()
08-17 19:50:55.233  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:50:55.233  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:50:55.233  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-17 19:50:55.233  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-17 19:50:55.233  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:50:55.233  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:50:55.243  1375  1375 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:50:55.243  1014  1127 V NetworkStats: performPollLocked() took 12ms
08-17 19:50:55.243  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:55.243  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:50:55.243  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:50:55.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.253  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:50:55.253  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:50:55.253  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:50:55.253  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 19:50:55.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.253  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.263  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:55.263  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-17 19:50:55.263  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:55.263  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:55.263  1177  1177 D HotspotTile: onReceive : 0, 0
,08-17 19:50:55.263  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:50:55.263  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:55.263  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:55.263  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:50:55.263  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:50:55.273  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-17 19:50:55.273  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:50:55.273  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.273  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
08-17 19:50:55.273  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:50:55.273  1177  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
,08-17 19:50:55.273  1014  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
,08-17 19:50:55.273  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-17 19:50:55.273  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:50:55.273  1014  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:50:55.273  4728  6815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 19:50:55.273  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-17 19:50:55.273  6762  6762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 19:50:55.273  1014  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-17 19:50:55.273  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:50:55.283  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 19:50:55.273  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:50:55.283  1449  1449 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 19:50:55.283  1449  1449 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 19:50:55.283  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-17 19:50:55.283  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:50:55.283  1014  1122 V NetworkStats: updateIfacesLocked()
08-17 19:50:55.283  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:50:55.283  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:50:55.283  1014  1122 V NetworkStats: performPollLocked() took 4ms
08-17 19:50:55.283  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:50:55.283  1014  1129 D Tethering: MasterInitialState.processMessage what=3
08-17 19:50:55.283  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:55.293  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:50:55.293  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:50:55.293  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:50:55.293  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:50:55.293  1014  1127 E ConnectivityService: updateNetworkInfo()
,08-17 19:50:55.293  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 19:50:55.293  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-17 19:50:55.293  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:50:55.293  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:50:55.293  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-17 19:50:55.293  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:50:55.293  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 19:50:55.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:55.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.293  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-17 19:50:55.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:50:55.303  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.333  1375  1375 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:50:55.343  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.353  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.353  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.353  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.353  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.353  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.363  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.363  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.363  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.363  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.363  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.363  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.363  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:50:55.363   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:50:55.363   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:50:55.363  6923  6943 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-17 19:50:55.363  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:50:55.373  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.373  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.373  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.373  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.373  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.373  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.373  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.383  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.383  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.383   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:50:55.383   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:50:55.383  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:50:55.383  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-17 19:50:55.383  6923  6943 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:50:55.383  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.383  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.393  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.393  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:50:55.393  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:50:55.403  3153  3246 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:50:55.403  3153  3246 I bt_vendor: bluetooth satus is on
08-17 19:50:55.403  3153  3246 I bt_vendor: bt-vendor : resetting BT status
08-17 19:50:55.403  3153  3246 I bt_vendor: Starting hciattach daemon
08-17 19:50:55.403  3153  3246 I bt_vendor: try to set false
08-17 19:50:55.403  1375  1375 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 19:50:55.403  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:50:55.403  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:50:55.403  3153  3246 I bt_vendor: Starting hciattach daemon
08-17 19:50:55.403  3153  3246 I bt_vendor: try to set false
08-17 19:50:55.403  3153  3246 I bt_vendor: cleanup
,08-17 19:50:55.403  3153  3265 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-17 19:50:55.403  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:50:55.403  3153  3246 I GKI_LINUX: GKI_exit_task 0 done
08-17 19:50:55.403  3153  3246 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 19:50:55.403  3153  3242 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-17 19:50:55.403  3153  3242 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:50:55.403  3153  3242 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 19:50:55.403  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:50:55.403  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
08-17 19:50:55.413  3153  3242 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 19:50:55.413  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:50:55.413  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 19:50:55.413  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.413  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.413  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:50:55.413  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:50:55.413  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:50:55.413  3153  3153 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:50:55.413  3153  3153 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:50:55.413  3153  3153 D BtGatt.GattService: stop()
08-17 19:50:55.413  3153  3153 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 19:50:55.413  3153  3242 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-17 19:50:55.413  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:50:55.413  1014  4019 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:50:55.413  1014  4019 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 19:50:55.413  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.413  1014  4019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.413  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:50:55.413  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-17 19:50:55.423  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:50:55.423  3153  3242 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:50:55.423  1014  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:50:55.423  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:50:55.423  1014  1477 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:50:55.423  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:50:55.423  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:50:55.423  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 19:50:55.423  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:50:55.423  3153  3242 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:50:55.423  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.423  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:50:55.423  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.423  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-17 19:50:55.423  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:50:55.433  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:50:55.433  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:50:55.433  1375  1375 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 19:50:55.433  1375  1375 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 19:50:55.433  1375  1375 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 19:50:55.433  1375  1375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 19:50:55.433  1375  1375 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:50:55.433  3153  3242 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:50:55.433  1014  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:50:55.433  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:50:55.433  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:50:55.433  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:50:55.433  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.433  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.433  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:50:55.433  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:50:55.433  1014  1129 D Tethering: InitialState.processMessage what=4
,08-17 19:50:55.433  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-17 19:50:55.433  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:50:55.433  3153  3242 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:50:55.443  1014  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:50:55.443  1014  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:50:55.443  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.443  1014  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.443  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:50:55.443  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:50:55.443  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:50:55.443  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:50:55.443  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:50:55.443  3153  3242 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:50:55.443  1014  4020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:50:55.443  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:50:55.443  1014  1129 E Tethering: No numeric data
,08-17 19:50:55.453  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:55.453  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.453  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:50:55.453  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:50:55.453  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:50:55.453  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:50:55.453  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:50:55.453  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:50:55.453  3153  3242 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:50:55.453  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:50:55.453  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:50:55.453  1014  1129 D Tethering: clearTetheredNotification()
,08-17 19:50:55.453  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.453  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:50:55.453  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:50:55.453  1177  1177 D HotspotTile: updateTetherState():false, false
08-17 19:50:55.453  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:50:55.453  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:50:55.453  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:50:55.453  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:50:55.463  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.463  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.463  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:50:55.463  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:50:55.463  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:50:55.463  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:50:55.463  3153  3242 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:50:55.463  3153  3242 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:50:55.463  3153  3242 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 19:50:55.463  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-17 19:50:55.463  1014  1122 V NetworkStats: performPollLocked() took 7ms
08-17 19:50:55.463  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:55.463  3153  3153 D HeadsetService: Received stop request...Stopping profile...
,08-17 19:50:55.463  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:50:55.463  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 19:50:55.463  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:55.463  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:55.473  1305  1305 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:50:55.473  3153  3153 D A2dpService: Received stop request...Stopping profile...
08-17 19:50:55.473  3153  3258 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:50:55.473  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:50:55.473  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-17 19:50:55.473  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 19:50:55.473  1305  1305 D BluetoothA2dp: Proxy object disconnected
08-17 19:50:55.473  1305  1305 D A2dpProfile: Bluetooth service disconnected
,08-17 19:50:55.473  3153  3153 D HidService: Received stop request...Stopping profile...
08-17 19:50:55.473  3153  3153 D HidService: Stopping Bluetooth HidService
08-17 19:50:55.473  3153  3153 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:50:55.473  3153  3153 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:50:55.473  3153  3153 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:50:55.473  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:50:55.473  3153  3153 D HealthService: Received stop request...Stopping profile...
,08-17 19:50:55.473  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:50:55.473  1305  1305 D BluetoothInputDevice: Proxy object disconnected
08-17 19:50:55.473  1305  1305 D HidProfile: Bluetooth service disconnected
,08-17 19:50:55.473  3153  3153 D PanService: Received stop request...Stopping profile...
08-17 19:50:55.473  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:50:55.483  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:50:55.483  1305  1305 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:50:55.483  1305  1305 D PanProfile: Bluetooth service disconnected
08-17 19:50:55.483  3153  3153 D BluetoothMapService: Received stop request...Stopping profile...
08-17 19:50:55.483  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:50:55.483  1305  1305 D BluetoothMap: Proxy object disconnected
08-17 19:50:55.483  1305  1305 D MapProfile: Bluetooth service disconnected
,08-17 19:50:55.483   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8dd97c8
08-17 19:50:55.483   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-17 19:50:55.483   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-17 19:50:55.483   272   331 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1193437896)
08-17 19:50:55.483  3153  3153 D SapService: Received stop request...Stopping profile...
08-17 19:50:55.483  3153  3153 D SapService: Stopping Bluetooth SapService
08-17 19:50:55.483  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:50:55.493  1305  1305 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 19:50:55.493  1305  1305 D SapProfile: Bluetooth service disconnected
,08-17 19:50:55.493  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:50:55.493  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:50:55.493  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:50:55.493  3153  3153 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 19:50:55.493  3153  3153 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 19:50:55.493  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 19:50:55.493  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:50:55.493  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 19:50:55.493  3153  3153 D BluetoothA2dp: Proxy object disconnected
08-17 19:50:55.493  3153  3153 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 19:50:55.493  3153  3259 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 19:50:55.493  3153  3153 I GKI_LINUX: GKI_exit_task 2 done
08-17 19:50:55.493  3153  3153 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-17 19:50:55.493  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 19:50:55.493  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:50:55.493  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:50:55.493  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:50:55.493  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:50:55.493  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:50:55.493  3153  3153 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:50:55.493  3153  3153 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:50:55.493  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:50:55.493  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:50:55.493  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:50:55.493  3153  3153 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:50:55.493  3153  3153 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 19:50:55.493  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 19:50:55.493  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:50:55.493  3153  3153 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 19:50:55.493  3153  3153 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-17 19:50:55.503  3153  3153 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:50:55.503  3153  3153 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:50:55.503  3153  3242 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-17 19:50:55.503  3153  3242 D BluetoothAdapterProperties: Setting state to 10
08-17 19:50:55.503  3153  3242 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 19:50:55.503  3153  3242 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:50:55.503  3153  3242 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 19:50:55.503  3153  3242 D BluetoothAdapterService: Autoconnection is available 
08-17 19:50:55.503  3153  3242 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 19:50:55.503  3153  3242 I BluetoothAdapterState: Entering OffState
,08-17 19:50:55.503  1305  1313 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:50:55.503  1177  2367 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:50:55.503  1177  2367 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.513  2035  3012 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:50:55.513  2035  3012 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.513  1305  1316 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:50:55.513  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:50:55.513  1305  1313 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:50:55.513  3153  3161 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:50:55.513  3153  3161 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:50:55.513  1449  5203 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:50:55.513  1449  5203 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.513  1305  1316 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:50:55.513  1305  1313 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:50:55.513  1305  1313 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.513  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:50:55.513  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.523  6762  6770 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:50:55.523  6762  6770 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.523  6762  6770 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 19:50:55.523  6762  6770 D BluetoothLeAdvertiser: Exit stop advertising
08-17 19:50:55.523  6762  6770 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-17 19:50:55.523  6762  6770 D BluetoothLeScanner: Exiting stopAllScan
,08-17 19:50:55.523  3153  3162 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:50:55.523  1305  1316 D Bluetoothsap: onBluetoothStateChange: up=false
,08-17 19:50:55.523  1305  1316 D Bluetoothsap: Unbinding service...
,08-17 19:50:55.523  1432  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:50:55.523  1432  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.523  1417  1431 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:50:55.523  1417  1431 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:50:55.523  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 19:50:55.523  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:50:55.543   272   331 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-17 19:50:55.543   272   331 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-17 19:50:55.543   272   331 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1193437896) wakelock released: 1, error no: 0
08-17 19:50:55.543   272   331 I rmt_storage: 
,08-17 19:50:55.543   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8dd97c8
,08-17 19:50:55.553  1375  1375 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:50:55.553  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:50:55.553  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-17 19:50:55.553  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:50:55.563  1177  1177 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
08-17 19:50:55.563  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:50:55.563  1177  1747 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
,08-17 19:50:55.563  3153  3246 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 19:50:55.563  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:50:55.563  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-17 19:50:55.563  1177  1747 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
,08-17 19:50:55.563  1177  1177 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
08-17 19:50:55.563  1014  4019 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 19:50:55.563  1177  1177 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
08-17 19:50:55.563  1014  1486 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:50:55.563  2035  2216 D BluetoothAdapter: 683006723: getState() :  mService = null. Returning STATE_OFF
08-17 19:50:55.563  2035  2216 D BluetoothAdapter: 683006723: getState() :  mService = null. Returning STATE_OFF
08-17 19:50:55.563  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:50:55.563  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:50:55.563  1861  1861 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:50:55.573  1014  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:50:55.573  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:50:55.573  3153  3153 I GKI_LINUX: GKI_exit_task 1 done
08-17 19:50:55.573  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.573  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:55.573  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:50:55.573  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:50:55.573  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:55.573  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:50:55.573  3153  3153 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 19:50:55.573  3153  3153 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 19:50:55.583  3153  3153 I art     : System.exit called, status: 0
08-17 19:50:55.583  3153  3153 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=236 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923, D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=233 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=230 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.j,ava:63)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  1014  1472 I ActivityManager: Killing 6406:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.andro,id.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=200 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  6923  6923 D StrictMode: StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:50:55.613  6923  6923 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:50:55.613  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 19:50:55.623  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:50:55.623  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:50:55.623  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:50:55.623  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 19:50:55.623  1375  1375 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 19:50:55.623  1014  4020 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:50:55.633  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:50:55.633  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.633  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:55.633  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:50:55.633  1631  1631 I Hs20UtilService: Starting #8
08-17 19:50:55.633  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:50:55.633  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:50:55.633  1631  1717 I Hs20UtilService: Message received 5007
08-17 19:50:55.633  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:50:55.633  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:50:55.633  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:50:55.633  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:50:55.633  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:50:55.653  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 19:50:55.653  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:50:55.653  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:50:55.653  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:50:55.653  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:50:55.653  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:50:55.653  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:50:55.653  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-17 19:50:55.653  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.653  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.653  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.653  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.663  6977  6977 E Zygote  : MountEmulatedStorage()
08-17 19:50:55.663  6977  6977 E Zygote  : v2
08-17 19:50:55.663  6977  6977 I libpersona: KNOX_SDCARD checking this for 10064
08-17 19:50:55.663  6977  6977 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:55.663  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:50:55.673  1014  1477 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6977 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:50:55.673  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:55.673  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:50:55.673  6923  6971 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-17 19:50:55.683  1014  1476 I ActivityManager: Process com.android.bluetooth (pid 3153)(adj 0) has died(26,722)
,08-17 19:50:55.693  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:55.693  6977  6977 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:55.703  1014  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:55.703  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:55.703  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:55.703  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 19:50:55.713  6977  6977 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:50:55.723  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:50:55.723  6977  6977 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:50:55.723  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-17 19:50:55.733  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:50:55.733   287   287 E SMD     : DCD OFF
,08-17 19:50:55.733  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:50:55.733  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:50:55.733  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.733  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.733  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:55.733  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:55.733  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:55.733  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 19:50:55.743  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:55.743  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:50:55.743  2035  2216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:50:55.743  1177  1177 D HotspotTile: onReceive : 1, 0
,08-17 19:50:55.743  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:55.743  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:55.753  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:55.753  6977  6977 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:50:55.763  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 19:50:55.763  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:55.763  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.763  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:55.763  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:55.773  6994  6994 E Zygote  : MountEmulatedStorage()
,08-17 19:50:55.773  1014  1495 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6994 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:50:55.773  6994  6994 E Zygote  : v2
08-17 19:50:55.773  6994  6994 I libpersona: KNOX_SDCARD checking this for 10065
08-17 19:50:55.773  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:50:55.773  6994  6994 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:55.773  1014  1495 I ActivityManager: Killing 6456:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21,
,08-17 19:50:55.773  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:55.783  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:55.783  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:50:55.783  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-17 19:50:55.803  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:55.803  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:55.803  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:55.803  6994  6994 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:55.823  6994  6994 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:50:55.833  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:55.833  1014  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:55.833  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-17 19:50:55.833  1014  1465 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-17 19:50:55.833  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:55.833  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:55.833  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:55.833  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:55.843  7009  7009 E Zygote  : MountEmulatedStorage()
08-17 19:50:55.843  7009  7009 I libpersona: KNOX_SDCARD checking this for 10102
08-17 19:50:55.843  7009  7009 E Zygote  : v2
08-17 19:50:55.843  7009  7009 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:55.843  1014  1465 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7009 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 19:50:55.853  1014  1465 I ActivityManager: Killing 6439:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21,
,08-17 19:50:55.853  7009  7009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:55.853  7009  7009 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:55.853  7009  7009 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:50:55.863  7009  7009 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:55.873  7009  7009 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:55.883  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:50:55.883  7009  7009 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 19:50:56.073  7009  7030 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-17 19:50:56.073  7009  7030 I Babel_SMS: MmsConfig.loadMmsSettings
,08-17 19:50:56.073  7009  7030 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-17 19:50:56.073  7009  7030 I Babel_SMS: MmsConfig.loadFromDatabase
,08-17 19:50:56.123  7009  7030 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-17 19:50:56.123  7009  7030 I Babel_SMS: MmsConfig.loadFromResources
,08-17 19:50:56.123  7009  7030 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-17 19:50:56.123  7009  7030 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-17 19:50:56.153  1014  1486 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-17 19:50:56.153  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-17 19:50:56.153  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.153  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:56.153  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:50:56.173  7009  7009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:50:56.183  7009  7009 I Babel_Crash: startup - clean
,08-17 19:50:56.243  1014  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:50:56.243  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:50:56.243  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.243  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.243  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:50:56.253  1631  1631 I Hs20UtilService: Starting #9
,08-17 19:50:56.253  1631  1717 I Hs20UtilService: Message received 5007
,08-17 19:50:56.253  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:50:56.253  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:50:56.253  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:50:56.253  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:50:56.253  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:50:56.253  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:50:56.263  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:50:56.273  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:50:56.273  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:50:56.273  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.273  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.273  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:50:56.273  1631  1631 I Hs20UtilService: Starting #10
,08-17 19:50:56.273  1631  1717 I Hs20UtilService: Message received 5011
,08-17 19:50:56.273  1014  4019 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-17 19:50:56.273  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.273  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.273  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.273  1014  4019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.293  1014  4019 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7033 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-17 19:50:56.293  7009  7009 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-17 19:50:56.293  7033  7033 E Zygote  : MountEmulatedStorage(),
08-17 19:50:56.293  7033  7033 E Zygote  : v2
08-17 19:50:56.293  7033  7033 I libpersona: KNOX_SDCARD checking this for 1000,
08-17 19:50:56.293  7009  7009 W AudioCapabilities: Unsupported mime audio/evrc
08-17 19:50:56.293  7033  7033 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.293  7033  7033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 19:50:56.293  7009  7009 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 19:50:56.303  1014  1042 D Tethering: interfaceRemoved wlan0
,08-17 19:50:56.303  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:50:56.303  7033  7033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:56.303  7009  7009 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-17 19:50:56.303  7033  7033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:50:56.303  7009  7009 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-17 19:50:56.313  7009  7009 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-17 19:50:56.313  7009  7009 W AudioCapabilities: Unsupported mime audio/x-ima
,08-17 19:50:56.313  7009  7009 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 19:50:56.323  7009  7009 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 19:50:56.323  7033  7033 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:56.323  7033  7033 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:56.333  7009  7009 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:50:56.343  7009  7009 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:50:56.343  7009  7009 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-17 19:50:56.353  7009  7009 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:50:56.353  7009  7009 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:50:56.353  7009  7009 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-17 19:50:56.353  7009  7009 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-17 19:50:56.353  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:50:56.353  7009  7009 W VideoCapabilities: Unsupported mime video/mp43
,08-17 19:50:56.363  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 19:50:56.363  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:50:56.363  7009  7009 W VideoCapabilities: Unsupported mime video/sorenson
,08-17 19:50:56.363  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:50:56.363  1014  1472 I ActivityManager: Killing 6471:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-17 19:50:56.373  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.373  1014  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.373  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.373  7009  7009 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 19:50:56.383  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.383  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.383  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.383  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.383  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.383  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.383  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.383  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:50:56.383  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.393  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.393  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:50:56.393  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.393  7009  7009 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 19:50:56.393  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.393  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:50:56.393  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-17 19:50:56.393  1014  1047 I PowerManagerService: [PWL] Off : 75s ago
,08-17 19:50:56.393  1014  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-17 19:50:56.393  1014  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-17 19:50:56.393  1014  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=1106)
,08-17 19:50:56.403  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.403  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:50:56.403  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.403  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.403  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.403  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.413  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.413  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:50:56.413  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.413  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.413  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.413  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.423  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.423  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.423  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.423  7009  7009 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:50:56.423  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.423  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.433  7009  7009 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:50:56.433  1014  1042 D Tethering: interfaceRemoved p2p0
08-17 19:50:56.433  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:50:56.433  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.433  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.433  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:50:56.433  7009  7009 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:50:56.443  1305  1305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:50:56.443  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:50:56.443  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-17 19:50:56.443  7009  7009 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:50:56.443  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.443  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.443  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:50:56.443  1014  4020 I ActivityManager: Killing 6505:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-17 19:50:56.443  7009  7009 I vclib   : onServiceConnected
,08-17 19:50:56.453  1305  1305 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:50:56.453  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:50:56.453  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:50:56.453  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:50:56.463  1014  4020 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 19:50:56.463  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.463  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.463  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.463  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.473  7050  7050 E Zygote  : MountEmulatedStorage(),
08-17 19:50:56.483  7050  7050 E Zygote  : v2
,08-17 19:50:56.483  7050  7050 I libpersona: KNOX_SDCARD checking this for 1002
,08-17 19:50:56.483  7050  7050 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.483  7050  7050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:56.483  1014  4020 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7050 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-17 19:50:56.483  7050  7050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:56.483  7050  7050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:56.503   309   309 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 21.346ms
,08-17 19:50:56.513  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:56.513  7050  7050 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:56.523   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 17.205ms
,08-17 19:50:56.533  7050  7050 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 19:50:56.533  7050  7050 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:50:56.543   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.082ms
,08-17 19:50:56.563  7050  7050 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:50:56.603  7050  7050 D BtSettings.ProfileConfig: Adding GattService
,08-17 19:50:56.603  7050  7050 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 19:50:56.603  7050  7050 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding HidService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding HealthService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding PanService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding SapService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding SapClientService
,08-17 19:50:56.613  7050  7050 D BtSettings.ProfileConfig: Adding HidDevService
,08-17 19:50:56.613  7050  7050 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:50:56.613  1014  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 19:50:56.613  1014  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.613  1014  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:50:56.613  1014  1476 D SettingsProvider: selectionArgs: false
08-17 19:50:56.613  1014  1476 D SettingsProvider: selectionArgs: 1002
,08-17 19:50:56.613  1014  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1476 D SettingsProvider: ret = -1
,08-17 19:50:56.623  1014  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-17 19:50:56.623  1014  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1495 D SettingsProvider: selectionArgs: false
,08-17 19:50:56.623  1014  1495 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1495 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 19:50:56.623  1014  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:50:56.623  1014  1486 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1486 D SettingsProvider: selectionArgs: 1002,
08-17 19:50:56.623  1014  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1486 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  4019 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 19:50:56.623  1014  4019 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:50:56.623  1014  4019 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  4019 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  4019 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  4019 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  4019 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 19:50:56.623  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1026 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1026 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1026 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  4020 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 19:50:56.623  1014  4020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  4020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  4020 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  4020 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  4020 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:50:56.623  1014  4020 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 19:50:56.623  1014  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1472 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1472 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1472 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1323 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 19:50:56.623  1014  1323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1323 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1323 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1323 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:50:56.623  1014  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1477 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1477 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1477 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:50:56.623  1014  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1213 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1213 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1213 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 19:50:56.623  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1027 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1027 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1027 D SettingsProvider: ret = -1
08-17 19:50:56.623  1014  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 19:50:56.623  1014  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:50:56.623  1014  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:50:56.623  1014  1465 D SettingsProvider: selectionArgs: false
08-17 19:50:56.623  1014  1465 D SettingsProvider: selectionArgs: 1002
08-17 19:50:56.623  1014  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:50:56.623  1014  1465 D SettingsProvider: ret = -1
,08-17 19:50:56.633  1014  1476 I ActivityManager: Killing 6490:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-17 19:50:56.643  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:50:56.643  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.643  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:50:56.643  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-17 19:50:56.643  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-17 19:50:56.643  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:56.653  2035  7066 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:50:56.653  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:50:56.653  1014  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:50:56.653  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:50:56.663  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.663  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:56.663  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:50:56.663  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:56.663  1631  1631 I Hs20UtilService: Starting #11
,08-17 19:50:56.663  1631  1717 I Hs20UtilService: Message received 5011
,08-17 19:50:56.663  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:56.663  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:56.663  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:56.673  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:50:56.673  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:50:56.673  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:50:56.673  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:50:56.683  1014  1304 E Watchdog: !@Sync 4
,08-17 19:50:56.683  1014  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:56.693  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:50:56.693  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:56.693  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:56.693  1014  1323 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 19:50:56.693  1014  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.693  1014  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.693  1014  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.693  1014  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.703  2035  7066 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 19:50:56.713  7067  7067 E Zygote  : MountEmulatedStorage()
08-17 19:50:56.713  7067  7067 E Zygote  : v2
08-17 19:50:56.713  7067  7067 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:50:56.713  7067  7067 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:56.713  7067  7067 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:50:56.713  1014  1323 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:50:56.713  7067  7067 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:56.713  7067  7067 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:56.723  7067  7067 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:56.723  7067  7067 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:56.753  7067  7067 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-17 19:50:56.753  7067  7067 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 19:50:56.753  7067  7067 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 19:50:56.763  7067  7067 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-17 19:50:56.763  7067  7067 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-17 19:50:56.763  7067  7067 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 19:50:56.763  7067  7067 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:50:56.773  1014  1027 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-17 19:50:56.773  1014  1027 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-17 19:50:56.783  7067  7082 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-17 19:50:56.783  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-17 19:50:56.783  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 19:50:56.783  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.783  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-17 19:50:56.783  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.793  7084  7084 E Zygote  : MountEmulatedStorage(),
08-17 19:50:56.793  7084  7084 E Zygote  : v2
08-17 19:50:56.793  7084  7084 I libpersona: KNOX_SDCARD checking this for 10031,
08-17 19:50:56.793  1014  1027 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7084 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-17 19:50:56.793  7084  7084 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.793  7084  7084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:56.803  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast,
08-17 19:50:56.803  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 19:50:56.803  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.803  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.803  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-17 19:50:56.803  7084  7084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:56.803  7084  7084 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 19:50:56.823  7099  7099 E Zygote  : MountEmulatedStorage()
08-17 19:50:56.823  7099  7099 E Zygote  : v2
08-17 19:50:56.823  7099  7099 I libpersona: KNOX_SDCARD checking this for 10001
08-17 19:50:56.823  7099  7099 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.823  7099  7099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:56.823  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7099 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:50:56.823  7099  7099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:50:56.823  7099  7099 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:50:56.823  7084  7084 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:56.823  7084  7084 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:56.833  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-17 19:50:56.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.833  1772  1772 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-17 19:50:56.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.843  7113  7113 E Zygote  : MountEmulatedStorage(),
08-17 19:50:56.843  7113  7113 E Zygote  : v2
08-17 19:50:56.843  7113  7113 I libpersona: KNOX_SDCARD checking this for 10121
08-17 19:50:56.843  7113  7113 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.843  7113  7113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:50:56.843  1014  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7113 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 19:50:56.853  7113  7113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:56.853  7113  7113 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:56.853  7099  7099 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:56.853  7099  7099 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:56.863  2593  2607 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-17 19:50:56.863  1772  1772 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-17 19:50:56.863  1772  1772 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-17 19:50:56.863  1772  1772 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-17 19:50:56.863  1772  1772 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 19:50:56.873  1772  1772 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 19:50:56.873  1772  1772 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-17 19:50:56.873  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-17 19:50:56.873  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.873  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.873  7113  7113 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:56.873  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.873  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.883  7113  7113 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:56.893  7129  7129 E Zygote  : MountEmulatedStorage(),
08-17 19:50:56.893  7129  7129 E Zygote  : v2
08-17 19:50:56.893  7129  7129 I libpersona: KNOX_SDCARD checking this for 10077
08-17 19:50:56.893  7129  7129 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.893  1014  1027 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7129 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:50:56.893  7129  7129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:50:56.893  7129  7129 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:56.893  7129  7129 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-17 19:50:56.903  7084  7084 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-17 19:50:56.913  1014  1477 I ActivityManager: Killing 6524:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-17 19:50:56.913  7113  7113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:50:56.913  7113  7113 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:50:56.913  7113  7113 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:50:56.933  1014  1465 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 19:50:56.933  7129  7129 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:56.933  7129  7129 D ActivityThread: Added TimaKeyStore provider
08-17 19:50:56.933  7113  7113 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:50:56.933  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.933  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.933  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.933  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.933  2747  7144 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-17 19:50:56.933  2747  7144 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-17 19:50:56.943  2747  7144 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-17 19:50:56.943  2747  7144 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-17 19:50:56.953  2747  7144 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-17 19:50:56.953  7147  7147 E Zygote  : MountEmulatedStorage()
08-17 19:50:56.953  7147  7147 E Zygote  : v2
08-17 19:50:56.953  7147  7147 I libpersona: KNOX_SDCARD checking this for 10032
08-17 19:50:56.953  7147  7147 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.953  1014  1465 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7147 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:50:56.953  7147  7147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:56.953  7113  7113 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-17 19:50:56.953  7147  7147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:56.953  7147  7147 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 19:50:56.953  7113  7113 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-17 19:50:56.963  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-17 19:50:56.963  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.963  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.963  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:56.963  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:56.973  7161  7161 E Zygote  : MountEmulatedStorage()
08-17 19:50:56.973  7161  7161 E Zygote  : v2
08-17 19:50:56.973  7161  7161 I libpersona: KNOX_SDCARD checking this for 10141
08-17 19:50:56.973  7161  7161 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:56.973  7161  7161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:56.973  1014  1477 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7161 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-17 19:50:56.983  1014  1477 I ActivityManager: Killing 6598:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-17 19:50:56.983  7161  7161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:56.983  7161  7161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:56.993  7147  7147 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:56.993  7147  7147 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:56.993  1014  1333 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast,
,08-17 19:50:57.003  1014  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.003  1014  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.003  1014  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.003  1014  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.003  7161  7161 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:57.003  7161  7161 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:57.013  7177  7177 E Zygote  : MountEmulatedStorage()
,08-17 19:50:57.013  7177  7177 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:50:57.013  7177  7177 E Zygote  : v2
08-17 19:50:57.013  7177  7177 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:57.013  7177  7177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:50:57.013  1014  1333 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7177 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:50:57.023  1014  1333 I ActivityManager: Killing 6616:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21,
,08-17 19:50:57.023  7177  7177 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:57.023  7177  7177 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:57.043  7177  7177 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:57.043  7177  7177 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:57.053  7161  7161 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-17 19:50:57.053  7161  7161 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:50:57.053  7161  7161 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:50:57.053  7161  7161 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:50:57.083  7147  7192 E SPPClientService: ============PushLog. commonIsShipBuild. stop!,
08-17 19:50:57.083  7147  7192 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-17 19:50:57.093  7147  7192 D SPPClientService: PushLog.txt file is not deleted.
,08-17 19:50:57.093  7147  7192 D SPPClientService: PushLog.txt file is not deleted.
08-17 19:50:57.093  7177  7177 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 19:50:57.093  7147  7192 D SPPClientService: ============PushLog. stop!
,08-17 19:50:57.113  1014  1472 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:50:57.113  7147  7147 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true,
,08-17 19:50:57.113  1014  1213 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-17 19:50:57.113  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.113  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.113  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.113  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.143  7194  7194 E Zygote  : MountEmulatedStorage()
,08-17 19:50:57.143  7194  7194 E Zygote  : v2
08-17 19:50:57.143  7194  7194 I libpersona: KNOX_SDCARD checking this for 10036
08-17 19:50:57.143  7194  7194 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:57.143  1014  1213 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7194 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:50:57.143  7194  7194 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:57.143  1014  1213 I ActivityManager: Killing 6633:com.samsung.helphub/1000 (adj 15): empty #21,
,08-17 19:50:57.143  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
08-17 19:50:57.143  1014  4019 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-17 19:50:57.143  1014  4019 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-17 19:50:57.153  7194  7194 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:50:57.153  7194  7194 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-17 19:50:57.153  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:57.153  1014  4019 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-17 19:50:57.153  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-17 19:50:57.153  1014  1486 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:50:57.183  7194  7194 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:57.183  7194  7194 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:57.223  1014  1472 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:50:57.233  7194  7194 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@365363be
,08-17 19:50:57.243  7194  7194 I SA      : [SSP] onCreated
,08-17 19:50:57.253  7194  7194 I SA      : [TPM] There is no property file
,08-17 19:50:57.253  7194  7194 I SA      : [SCU] isHaveSA() - false
,08-17 19:50:57.263  1014  1477 D RCPManagerService: exchangeData() failure , invalid userId
08-17 19:50:57.263  7194  7194 I SA      : [TPM] getModelProperty : null
08-17 19:50:57.263  7194  7194 I SA      : [TPM] getCSCProperty : null
08-17 19:50:57.263  7194  7194 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-17 19:50:57.263  7194  7194 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-17 19:50:57.263  7194  7194 I SA      : [DM] TFT FEATURE: false
,08-17 19:50:57.263  7194  7194 I SA      : [DM] init START
,08-17 19:50:57.273  7194  7194 I SA      : [DM] This device is not a Vodafone
,08-17 19:50:57.273  7177  7177 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-17 19:50:57.273  7147  7203 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-17 19:50:57.283  7177  7177 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-17 19:50:57.283  7177  7177 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-17 19:50:57.283  7194  7194 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-17 19:50:57.293  7177  7177 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 19:50:57.293  7177  7177 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-17 19:50:57.293  7177  7177 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-17 19:50:57.293  1014  4020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-17 19:50:57.293  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.293  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-17 19:50:57.293  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.293  1014  4020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-17 19:50:57.293  7194  7194 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-17 19:50:57.303  7194  7194 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-17 19:50:57.303  7194  7194 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-17 19:50:57.303  7194  7194 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-17 19:50:57.303  7194  7194 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-17 19:50:57.303  7194  7194 I SA      : [SCU] isHaveSA() - false,
08-17 19:50:57.303  7222  7222 I libpersona: KNOX_SDCARD checking this for 10008
08-17 19:50:57.303  7194  7194 I SA      : support phone number id : false
,08-17 19:50:57.303  7222  7222 I libpersona: KNOX_SDCARD not a persona
08-17 19:50:57.303  7194  7194 I SA      : [DM] Supports Ref Jpn : true
08-17 19:50:57.303  7194  7194 I SA      : [DM] init END
08-17 19:50:57.303  7194  7194 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-17 19:50:57.303  7194  7194 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-17 19:50:57.303  7194  7194 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-17 19:50:57.303  7222  7222 E Zygote  : MountEmulatedStorage()
08-17 19:50:57.303  7222  7222 E Zygote  : v2
08-17 19:50:57.313  7222  7222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:57.313  7222  7222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:57.313  7222  7222 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-17 19:50:57.313  1014  4020 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7222 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 19:50:57.323  1014  1465 I ActivityManager: Killing 6666:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-17 19:50:57.343  1014  1486 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
08-17 19:50:57.343  7194  7194 I SA      : [SLFUCHKMGR] constructor called
,08-17 19:50:57.343  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.343  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.343  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.343  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.353  7222  7222 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:57.353  7222  7222 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:57.363  1014  1323 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:50:57.363  7194  7194 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
08-17 19:50:57.363  7194  7194 I SA      : [OR] == isSIMCardReady false ==
,08-17 19:50:57.363  7240  7240 E Zygote  : MountEmulatedStorage()
08-17 19:50:57.363  7240  7240 I libpersona: KNOX_SDCARD checking this for 10068
08-17 19:50:57.363  7240  7240 E Zygote  : v2
08-17 19:50:57.363  7240  7240 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:57.363  7240  7240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:57.373  7194  7194 I SA      : [SCU] == networkStateCheck == false
08-17 19:50:57.373  7194  7194 I SA      : [OR] onReceive END
,08-17 19:50:57.373  7240  7240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:50:57.373  1014  4020 D RCPManagerService: exchangeData() failure , invalid userId,
08-17 19:50:57.373  7240  7240 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:50:57.373  1014  1486 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7240 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-17 19:50:57.393   309   309 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 627us total 25.196ms
,08-17 19:50:57.403  1014  1476 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-17 19:50:57.403  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-17 19:50:57.403  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:57.403  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:57.403  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:50:57.403  1014  1477 I ActivityManager: Killing 6690:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-17 19:50:57.413  1014  1465 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-17 19:50:57.413  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.413  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.413  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.413  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.413  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:50:57.423  7240  7240 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:57.423  7240  7240 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:57.423  1014  1333 D RCPManagerService: exchangeData() failure , invalid userId
08-17 19:50:57.423   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 24.746ms
,08-17 19:50:57.433  1014  4020 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:50:57.443   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.418ms
,08-17 19:50:57.453  7257  7257 E Zygote  : MountEmulatedStorage(),
08-17 19:50:57.453  7257  7257 E Zygote  : v2
08-17 19:50:57.453  7257  7257 I libpersona: KNOX_SDCARD checking this for 10110
08-17 19:50:57.453  7257  7257 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:57.453  7257  7257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:57.453  7257  7257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:50:57.453  1014  1465 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7257 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:50:57.453  7257  7257 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:50:57.463  1014  1465 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-17 19:50:57.463  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.463  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.463  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:57.463  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:57.483  7268  7268 E Zygote  : MountEmulatedStorage()
08-17 19:50:57.483  7268  7268 I libpersona: KNOX_SDCARD checking this for 10009,
08-17 19:50:57.483  7268  7268 E Zygote  : v2
08-17 19:50:57.483  7268  7268 I libpersona: KNOX_SDCARD not a persona,
08-17 19:50:57.483  7268  7268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:57.483  7268  7268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:50:57.493  7268  7268 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 19:50:57.503  1014  1465 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7268 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
08-17 19:50:57.503  1014  1465 I ActivityManager: Killing 6176:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-17 19:50:57.503  1014  1465 I ActivityManager: Killing 6706:com.android.calendar/u0a131 (adj 15): empty #22
,08-17 19:50:57.503  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:57.513  1014  1495 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-17 19:50:57.513  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-17 19:50:57.513  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:57.513  1014  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:57.513  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:50:57.513  7009  7254 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 19:50:57.523  7257  7257 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:57.523  7240  7240 D BadgeProvider: onCreate
,08-17 19:50:57.533  7240  7240 D BadgeProvider: DatabaseHelper
,08-17 19:50:57.543  7268  7268 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:50:57.543  7268  7268 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:57.553  1014  4020 I ActivityManager: Killing 6000:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-17 19:50:57.693  1014  1495 I art     : Explicit concurrent mark sweep GC freed 57716(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/35MB, paused 2.307ms total 164.038ms
,08-17 19:50:57.703  1014  4020 I ActivityManager: Killing 5784:com.android.vending/u0a26 (adj 15): empty #21
,08-17 19:50:57.713  2862  2862 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 19:50:57 GMT+02:00 2016
,08-17 19:50:57.713  1014  1495 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 19:50:57.713  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 19:50:57.713  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:57.713  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:57.713  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 19:50:57.723  7240  7251 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-17 19:50:57.733  2862  2862 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 19:50:57.743  7240  7251 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-17 19:50:57.743  7240  7251 D BadgeProvider: sendNotify, [notify] : null
08-17 19:50:57.743  7240  7251 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-17 19:50:57.743  7240  7251 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 19:50:57.743  7240  7251 D BadgeProvider: update, [UpdateCount] : 1
,08-17 19:50:57.743  1478  1478 D Launcher.Model: reloadBadges entered.
,08-17 19:50:57.743  2862  2862 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 19:50:57.743  2862  2862 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 19:50:57.753  2862  2862 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 19:50:57.763  2862  7291 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 19:50:57.763  2862  7291 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-17 19:50:57.773  2862  7291 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-17 19:50:57.783  1014  4019 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-17 19:50:57.783  1014  4019 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-17 19:50:57.783  2862  7291 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-17 19:50:57.783  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-17 19:50:57.783  2862  2862 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-17 19:50:57.793  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-17 19:50:57.863  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:50:57.863  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-17 19:50:57.863  1014  1026 D SecContentProvider2: mCursor = null
,08-17 19:50:57.863  1014  1026 D WifiService: setWifiEnabled: true pid=6762, uid=10171
,08-17 19:50:57.863  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:50:57.863  1014  1026 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:50:57.863  1014  1026 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:50:57.863  1014  1026 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:50:57.863  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:50:57.863  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:50:57.863  1014  1026 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:50:57.863  1014  1026 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:50:57.863  1014  1026 D SettingsProvider: name = wifi_on
,08-17 19:50:57.873  1014  4019 I ActivityManager: Killing 6833:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-17 19:50:57.873  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 19:50:57.873  1014  1323 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:50:57.883  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:50:57.883  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-17 19:50:57.883  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:57.883  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:57.883  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:50:57.893  4728  7294 I iu.SyncManager: SYNC; picasa accounts
,08-17 19:50:57.903  4728  4728 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-17 19:50:57.993   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 19:50:57.993   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:50:58.003  7257  7298 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:50:58.003   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:50:58.003   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:50:58.003  7257  7298 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:50:58.013   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 19:50:58.013   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:50:58.013  7257  7299 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:50:58.013   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:50:58.013   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:50:58.023  7257  7299 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:50:58.043  7257  7257 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 19:50:58.043  7257  7257 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 19:50:58.043  7257  7257 I GAv4    :   adb logcat -s GAv4
,08-17 19:50:58.063  7257  7257 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:50:58.063  1014  1333 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:50:58.073  7257  7257 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:50:58.083  7257  7301 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:50:58.263  1014  1042 D Tethering: interfaceAdded wlan0
,08-17 19:50:58.273  1014  1129 E Tethering: No numeric data
,08-17 19:50:58.273  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:50:58.273  1014  1129 D Tethering: clearTetheredNotification()
08-17 19:50:58.273  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:50:58.273  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:58.273  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:50:58.273  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:50:58.273  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:50:58.273  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:50:58.273  1014  1129 D Tethering: InitialState.processMessage what=4,
08-17 19:50:58.273  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:50:58.273  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:50:58.283  1177  1177 D HotspotTile: updateTetherState():false, false
,08-17 19:50:58.283  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:58.283  1014  1122 V NetworkStats: performPollLocked() took 6ms
08-17 19:50:58.283  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:50:58.283  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:50:58.283  1014  1129 E Tethering: No numeric data
,08-17 19:50:58.283  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:50:58.283  1014  1129 D Tethering: clearTetheredNotification()
08-17 19:50:58.283  1014  1042 D Tethering: interfaceAdded p2p0
,08-17 19:50:58.283  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 19:50:58.283   277  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-17 19:50:58.283  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:50:58.293  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:58.293   277  1013 D SoftapController: Softap fwReload - Ok
08-17 19:50:58.293  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:50:58.293  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:50:58.293  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 19:50:58.293  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:50:58.293  1177  1177 D HotspotTile: updateTetherState():false, false
,08-17 19:50:58.293  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:50:58.293  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:50:58.293   277  1013 D CommandListener: Setting iface cfg
08-17 19:50:58.293   277  1013 D CommandListener: Trying to bring down wlan0
,08-17 19:50:58.293   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:50:58.293  1014  1122 V NetworkStats: performPollLocked() took 7ms
,08-17 19:50:58.293  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:58.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:58.293  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:50:58.303  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 19:50:58.303  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 19:50:58.303  1014  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-17 19:50:58.313  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:50:58.313  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:50:58.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:58.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:58.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:58.313  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:50:58.313  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:50:58.313  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-17 19:50:58.313  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:50:58.313  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:58.313  1177  1177 D HotspotTile: onReceive : 2, 0
,08-17 19:50:58.313  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:58.313  1014  4019 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:50:58.323  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:58.323  7257  7257 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-17 19:50:58.333  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:58.333  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:58.333  1014  4019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:50:58.333  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 19:50:58.343  7257  7257 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 9684-9687)
,08-17 19:50:58.343  7257  7257 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 19:50:58.363  7257  7257 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23803571}
,08-17 19:50:58.363  7257  7257 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 19:50:58.363  7257  7257 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 19:50:58.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:50:58.383  7257  7257 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-17 19:50:58.383  7257  7257 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:50:58.383  7323  7323 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-17 19:50:58.383  7257  7257 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 19:50:58.383  7323  7323 I wpa_supplicant: Successfully initialized wpa_supplicant
08-17 19:50:58.383  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:50:58.403  7257  7257 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:50:58.403  7257  7257 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:50:58.403  7257  7257 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:50:58.403  7257  7257 I Adreno-EGL: Local Branch: 
08-17 19:50:58.403  7257  7257 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:50:58.403  7257  7257 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:50:58.403  7257  7257 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:50:58.403  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-17 19:50:58.413   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7323,
08-17 19:50:58.413   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-17 19:50:58.413  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:50:58.413  7323  7323 I wpa_supplicant: ssSupport state is = 1
08-17 19:50:58.413  7323  7323 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 19:50:58.413  7323  7323 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-17 19:50:58.413   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7323
08-17 19:50:58.413   379   379 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-17 19:50:58.463  7257  7338 W cr.media: Requires BLUETOOTH permission
,08-17 19:50:58.483  7257  7257 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 19:50:58.493  7257  7257 I NSApplication: Starting up...
,08-17 19:50:58.493  1014  1323 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,08-17 19:50:58.503  1014  1213 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:50:58.503  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-17 19:50:58.513  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 19:50:58.513  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:58.513  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:58.513  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-17 19:50:58.523  7343  7343 E Zygote  : MountEmulatedStorage()
,08-17 19:50:58.523  7343  7343 E Zygote  : v2
08-17 19:50:58.523  7343  7343 I libpersona: KNOX_SDCARD checking this for 10117
08-17 19:50:58.523  7343  7343 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:58.523  1014  1495 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7343 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 19:50:58.533  1014  1495 I ActivityManager: Killing 6977:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-17 19:50:58.533  7343  7343 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:58.533  7343  7343 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:58.543  7343  7343 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-17 19:50:58.563  7343  7343 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:58.563  7343  7343 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:58.573  7343  7343 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:50:58.603   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
08-17 19:50:58.603  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-17 19:50:58.663  7323  7323 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-17 19:50:58.663  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:50:58.673  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-17 19:50:58.673   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7323
08-17 19:50:58.673   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:50:58.673  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 19:50:58.673  7323  7323 I wpa_supplicant: ssSupport state is = 1
,08-17 19:50:58.673  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 19:50:58.673  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:50:58.673  7323  7323 E wpa_supplicant: SIM READ ERROR
08-17 19:50:58.673  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 19:50:58.673  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:50:58.673  7323  7323 E wpa_supplicant: SIM READ ERROR
08-17 19:50:58.673  7323  7323 I wpa_supplicant: Blacklist: Clear (all) 
08-17 19:50:58.673  7323  7323 I wpa_supplicant: wpa_default_ap_write_once
,08-17 19:50:58.673  7323  7323 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:50:58.673  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:50:58.673  7323  7323 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 19:50:58.673  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:50:58.673  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-17 19:50:58.673  7323  7323 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 19:50:58.683  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:50:58.683  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:50:58.683  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:50:58.733  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 19:50:58.733   287   287 E SMD     : DCD OFF,
,08-17 19:50:58.893  7323  7323 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 19:50:58.893  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-17 19:50:58.913  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-17 19:50:58.913   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7323
08-17 19:50:58.913   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:50:58.913  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 19:50:58.913  7323  7323 I wpa_supplicant: ssSupport state is = 1
,08-17 19:50:58.913  7323  7323 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:50:58.913  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:50:58.933  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-17 19:50:58.933   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7323
08-17 19:50:58.933   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-17 19:50:58.933  7323  7323 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-17 19:50:58.933  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-17 19:50:58.933  7323  7323 I wpa_supplicant: ssSupport state is = 1
08-17 19:50:58.933  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:50:58.933  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:50:58.933  7323  7323 E wpa_supplicant: SIM READ ERROR,
08-17 19:50:58.933  7323  7323 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:50:58.933  7323  7323 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:50:58.933  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:50:58.933  7323  7323 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 19:50:58.933  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:50:58.933  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:50:58.933  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:50:58.933  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:50:58.943  1014  1486 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-17 19:50:58.943  1014  1486 I ActivityManager: Killing 6994:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-17 19:50:58.953  1014  1333 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:50:58.953  1014  1333 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:50:58.953  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:50:58.953  1014  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:50:58.953  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:50:58.953  1631  1631 I Hs20UtilService: Starting #12
,08-17 19:50:58.953  1631  1717 I Hs20UtilService: Message received 5011
,08-17 19:50:58.963  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:50:58.963  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:50:58.963  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:50:58.963  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:50:58.973  7323  7323 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-17 19:50:58.973  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:50:59.053  7323  7323 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,08-17 19:50:59.053  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-17 19:50:59.053  7323  7323 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:50:59.273  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:50:59.273  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:50:59.273  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:50:59.303  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-17 19:50:59.313  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:50:59.313  7323  7323 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-17 19:50:59.313  7323  7323 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:50:59.313  7323  7323 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:50:59.313  7323  7323 E wpa_supplicant: SIM READ ERROR,
,08-17 19:50:59.313  7323  7323 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:50:59.323  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 19:50:59.343  7323  7323 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-17 19:50:59.343  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
08-17 19:50:59.343  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:50:59.343  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:50:59.353  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:50:59.343  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:50:59.353  1177  1177 D HotspotTile: onReceive : 3, 0
08-17 19:50:59.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:59.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:59.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:59.343  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:50:59.343  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:50:59.343  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-17 19:50:59.353  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:50:59.353  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:50:59.353  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:59.353  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:50:59.353  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
,08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:59.353  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:50:59.353  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:59.353  1014  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 19:50:59.353  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-17 19:50:59.353  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:50:59.353  1014  1125 E WifiConfigStore: Not a HS20
08-17 19:50:59.353  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
08-17 19:50:59.353  1014  1477 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:50:59.353  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:50:59.353  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:50:59.363  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
08-17 19:50:59.363  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:50:59.363  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 19:50:59.363  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:50:59.363  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-17 19:50:59.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:50:59.363  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 19:50:59.363  7323  7323 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:50:59.363  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:50:59.363  7323  7323 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:50:59.363  7323  7323 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:50:59.363  7323  7323 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-17 19:50:59.363  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:50:59.363  7323  7323 I wpa_supplicant: First Scan Start
08-17 19:50:59.363  7323  7323 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 19:50:59.363  1631  1631 I Hs20UtilService: Starting #13
08-17 19:50:59.363  1631  1717 I Hs20UtilService: Message received 5011,
,08-17 19:50:59.373  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-17 19:50:59.373  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
,08-17 19:50:59.373  1014  1125 I WifiNative-HAL: startHal
08-17 19:50:59.373  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d6f888c
08-17 19:50:59.373  1014  1125 I WifiNative-HAL: Could not start hal
,08-17 19:50:59.373  7009  7009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:50:59.383  1014  1125 E WifiNative-wlan0: do suspend true
,08-17 19:50:59.383  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
08-17 19:50:59.383  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 19:50:59.383  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 19:50:59.383  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:50:59.383  1014  1148 I WifiNative-HAL: startHal
08-17 19:50:59.383  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ecb49bc
08-17 19:50:59.383  1014  1148 I WifiNative-HAL: Could not start hal
08-17 19:50:59.383  1014  1148 E WifiScanningService: could not start HAL
,08-17 19:50:59.383  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-17 19:50:59.383  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:50:59.383   277  1013 D CommandListener: Setting iface cfg
08-17 19:50:59.383   277  1013 D CommandListener: Trying to bring up p2p0
,08-17 19:50:59.383  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 19:50:59.383  1014  1124 D WifiP2pService: P2pEnablingState
08-17 19:50:59.383  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:50:59.383  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 19:50:59.383  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:50:59.383  1014  1124 D WifiP2pService: P2p socket connection successful
08-17 19:50:59.383  1014  1125 E WifiNative-wlan0: invaild command id : 215
08-17 19:50:59.383  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:50:59.383  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:50:59.383  1014  1125 E WifiNative-wlan0: invaild command id : 215
08-17 19:50:59.393  1014  1124 D WifiP2pService: P2pEnabledState
,08-17 19:50:59.393  7323  7323 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:50:59.393  7323  7323 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:50:59.393  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-17 19:50:59.393  7323  7323 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-17 19:50:59.393  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:50:59.393  1014  1125 E WifiStateMachine: Failed to set frequency band 0
08-17 19:50:59.393  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:50:59.393  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:50:59.393  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 19:50:59.393  1014  1125 D SecContentProvider2: mCursor = null
08-17 19:50:59.393  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:50:59.393  1014  1045 D WifiDisplayController: disconnect,
08-17 19:50:59.393  1014  1045 D WifiDisplayController: updateConnection
08-17 19:50:59.393  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:50:59.393  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:50:59.393  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:50:59.393  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:50:59.393  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:50:59.393  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:50:59.393  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:50:59.393  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:50:59.403  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 19:50:59.403  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-17 19:50:59.403  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:50:59.403  1014  1465 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:50:59.403  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:50:59.403  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:50:59.403  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  secondary type: null
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  wps: 0
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  grpcapab: 0
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  devcapab: 0
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  status: 3
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  wfdInfo: null
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-17 19:50:59.403  1014  1045 D WifiDisplayController:  SConnectInfo : null
08-17 19:50:59.403  1014  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-17 19:50:59.403  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:50:59.413  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:50:59.413  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:50:59.413  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 19:50:59.413  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:50:59.413  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:50:59.413  1014  1472 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 19:50:59.413  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:59.413  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:59.413  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:59.413  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:59.423  7373  7373 E Zygote  : MountEmulatedStorage()
,08-17 19:50:59.433  7373  7373 E Zygote  : v2
,08-17 19:50:59.433  7373  7373 I libpersona: KNOX_SDCARD checking this for 10064
08-17 19:50:59.433  7373  7373 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:59.433  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 19:50:59.433  7373  7373 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:50:59.433  7373  7373 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:50:59.433  1014  1472 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7373 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:50:59.433  7373  7373 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:50:59.433  1014  1124 D WifiP2pService: InactiveState
08-17 19:50:59.433  7323  7323 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 19:50:59.433  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:50:59.433  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
08-17 19:50:59.433  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:50:59.443  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:50:59.453  7373  7373 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:59.453  7373  7373 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:59.463  7373  7373 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:50:59.483  7373  7373 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:50:59.483  7373  7373 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:50:59.503  7373  7373 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:50:59.513  1014  1213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 19:50:59.513  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:59.513  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:59.513  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:50:59.513  1014  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:50:59.523  7388  7388 E Zygote  : MountEmulatedStorage()
,08-17 19:50:59.523  7388  7388 E Zygote  : v2
08-17 19:50:59.523  7388  7388 I libpersona: KNOX_SDCARD checking this for 10065
08-17 19:50:59.523  7388  7388 I libpersona: KNOX_SDCARD not a persona
,08-17 19:50:59.523  7388  7388 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:50:59.523  1014  1213 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7388 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:50:59.523  1014  1213 I ActivityManager: Killing 6900:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-17 19:50:59.523  7388  7388 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:50:59.533  7388  7388 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:50:59.553  7388  7388 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:50:59.553  7388  7388 D ActivityThread: Added TimaKeyStore provider
,08-17 19:50:59.573  7388  7388 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:50:59.583  1014  4019 I ActivityManager: Killing 7050:com.android.bluetooth/1002 (adj 15): empty #21
,08-17 19:50:59.993  1014  1093 V AlarmManager: waitForAlarm result :8
,08-17 19:51:00.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:51:00.543  1014  3350 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:51:00.553  7323  7323 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
08-17 19:51:00.553  7323  7323 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 19:51:00.563  7323  7323 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-17 19:51:00.563  7323  7323 I wpa_supplicant: Trying to associate with  'G700'
,08-17 19:51:00.563  7323  7323 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-17 19:51:00.563  1014  7369 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 19:51:00.563  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-17 19:51:00.573  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 19:51:00.573  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:00.683  7323  7323 E wpa_supplicant: Cmd 35605 not handled
,08-17 19:51:00.683  7323  7323 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:51:00.683  7323  7323 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-17 19:51:00.683  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:00.683  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:51:00.683  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:00.683  7323  7323 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 19:51:00.683  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:51:00.683  7323  7323 I wpa_supplicant: Associated with F4.99.3E
08-17 19:51:00.683  7323  7323 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:51:00.683  7323  7323 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 19:51:00.683  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:51:00.693  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:51:00.693  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:00.693  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:51:00.693  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 19:51:00.693  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:00.693  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:51:00.693  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:51:00.693  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:51:00.693  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:51:00.693  1014  1129 E Tethering: No numeric data
,08-17 19:51:00.693  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:51:00.693  1014  1129 D Tethering: clearTetheredNotification()
,08-17 19:51:00.693  7323  7323 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:51:00.693  7323  7323 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-17 19:51:00.703  7323  7323 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 19:51:00.703  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-17 19:51:00.703  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:00.703  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:00.703  7323  7323 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:51:00.703  7323  7323 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-17 19:51:00.703  7323  7323 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-17 19:51:00.703  7323  7323 I wpa_supplicant: Blacklist: Clear (temp) 
,08-17 19:51:00.703  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:51:00.703  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:00.703  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 19:51:00.703  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:51:00.703  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:51:00.703  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:51:00.703  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:00.703  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:51:00.713  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:51:00.713  1177  1177 D HotspotTile: updateTetherState():false, false
,08-17 19:51:00.713  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:00.713  1014  1125 D SecContentProvider2: mCursor = null
08-17 19:51:00.713  1014  1122 V NetworkStats: performPollLocked() took 10ms
08-17 19:51:00.713  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:00.713  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:00.713  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:00.723  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 19:51:00.723  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:00.723  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:00.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:00.733  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.733  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.733  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:51:00.733  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:51:00.733  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
08-17 19:51:00.733  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-17 19:51:00.733  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:51:00.733  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-17 19:51:00.733  1014  1127 E ConnectivityService: updateNetworkInfo()
,08-17 19:51:00.743  1014  4020 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:51:00.743  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-17 19:51:00.743  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:00.743  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:00.743  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:51:00.743  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:51:00.743  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:51:00.753  1631  1631 I Hs20UtilService: Starting #14
,08-17 19:51:00.753  1631  1717 I Hs20UtilService: Message received 5007
08-17 19:51:00.753  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:00.753  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:51:00.753  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:51:00.753  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:51:00.753  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:51:00.753  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:51:00.763   277  1013 D CommandListener: Setting iface cfg
,08-17 19:51:00.763  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-17 19:51:00.773  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:51:00.773  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:00.783  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:51:00.783  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:51:00.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:00.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:00.783  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:00.783  1014  1125 E WifiNative-wlan0: do suspend false
,08-17 19:51:00.793  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:51:00.793  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:51:00.793  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:00.793  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:00.873  1014  1465 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:51:00.873  1014  1465 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:51:00.873  1014  1465 D SecContentProvider2: mCursor = null
,08-17 19:51:00.873  1014  1465 D WifiService: setWifiEnabled: false pid=6762, uid=10171
,08-17 19:51:00.883  1014  1465 D SettingsProvider: name = wifi_on
,08-17 19:51:00.893  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:00.913  1014  1125 E WifiNative-wlan0: do suspend true
,08-17 19:51:00.933  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:51:00.933  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:51:00.943   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:51:00.943  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:00.943  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:00.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.943  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.943  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
08-17 19:51:00.943  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 19:51:00.943  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:51:00.943  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:51:00.943  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:51:00.943  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-17 19:51:00.943  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 19:51:00.943   277  1013 E Netd    : no such netId 503
,08-17 19:51:00.953  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:51:00.953  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 19:51:00.953  1014  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-17 19:51:00.953  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 19:51:00.953  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:00.953  1014  1127 V NetworkStats: updateIfacesLocked()
08-17 19:51:00.953  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:51:00.953  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:00.953  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:51:00.963  1014  1127 V NetworkStats: performPollLocked() took 6ms
,08-17 19:51:00.963  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:00.963  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:00.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:00.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:00.963  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 19:51:00.963  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:51:00.963  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:00.963  1014  1014 D RttService: SCAN_AVAILABLE : 1
,08-17 19:51:00.963  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:51:00.973  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:51:00.973  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 19:51:00.973  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:51:00.973  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-17 19:51:00.973  1014  7404 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:51:00.973  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 19:51:00.973  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:51:00.973  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:51:00.973  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:51:00.973  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:51:00.973  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:51:00.973  1014  1127 E ConnectivityService: updateNetworkInfo()
,08-17 19:51:00.973  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:00.973  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:00.973  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 19:51:00.973  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-17 19:51:00.973  1014  1045 D WifiDisplayController: disconnect
08-17 19:51:00.973  1014  4020 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:51:00.973  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:51:00.973  1014  1124 D WifiP2pService: P2pDisablingState
08-17 19:51:00.973  1014  1045 D WifiDisplayController: updateConnection
08-17 19:51:00.973  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-17 19:51:00.973  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:51:00.973  1014  1124 D WifiP2pService: p2p socket connection lost
08-17 19:51:00.973  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:51:00.973  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:00.973  1014  1124 D WifiP2pService: P2pDisabledState
08-17 19:51:00.973  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:00.973  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:51:00.973  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 19:51:00.973  1014  7404 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 19:51:00.983  1014  1125 E WifiNative-wlan0: do suspend true
,08-17 19:51:00.983  1631  1631 I Hs20UtilService: Starting #15
,08-17 19:51:00.983  1631  1717 I Hs20UtilService: Message received 5007
08-17 19:51:00.983  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-17 19:51:00.983  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:51:00.983  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:51:00.983  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:51:00.983  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:51:00.983  1014  1486 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:51:00.983  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:51:00.993  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:51:00.993  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:51:00.993  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:51:00.993  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:51:00.993  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:51:00.993  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:51:00.993  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:51:01.003  7407  7407 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
08-17 19:51:01.013  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 19:51:01.013  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 },
08-17 19:51:01.013  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:51:01.013  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
08-17 19:51:01.013  7407  7407 I dhcpcd  : version 5.5.6 starting
08-17 19:51:01.013   277  1013 D CommandListener: Clearing all IP addresses on wlan0
08-17 19:51:01.013  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:51:01.013  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:01.013  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:01.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:01.013  7407  7407 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-17 19:51:01.013  7323  7323 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-17 19:51:01.013  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:51:01.023  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:51:01.023  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:01.023  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:01.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.023  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.023  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:51:01.023  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:51:01.023  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:51:01.023  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:01.023  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:01.033  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:01.033  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:51:01.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:51:01.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.033  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:51:01.033  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:01.033  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:01.033  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 19:51:01.033  1177  1177 D HotspotTile: onReceive : 0, 0
,08-17 19:51:01.033  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-17 19:51:01.033  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:01.033  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:01.043  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:01.043  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:01.043  7373  7373 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-17 19:51:01.043  7373  7373 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-17 19:51:01.043  7373  7373 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:51:01.043  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:01.043  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:01.043  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:01.043  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:01.043  7388  7388 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:51:01.053  1014  1323 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 19:51:01.053  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:01.053  1014  1323 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:51:01.053  1014  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:01.053  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:51:01.053  1631  1631 I Hs20UtilService: Starting #16
08-17 19:51:01.053  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:51:01.053  1631  1717 I Hs20UtilService: Message received 5007
08-17 19:51:01.063  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:51:01.063  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:51:01.063  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,08-17 19:51:01.073  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 19:51:01.073  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:51:01.073  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:51:01.083  1014  4019 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 19:51:01.083  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:01.083  1014  4019 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:51:01.083  1014  4019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:01.083  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:51:01.083  1631  1631 I Hs20UtilService: Starting #17
,08-17 19:51:01.083  1631  1717 I Hs20UtilService: Message received 5011
08-17 19:51:01.083  7407  7407 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-17 19:51:01.083  7407  7407 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 19:51:01.083  7407  7407 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-17 19:51:01.083  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:51:01.083  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:51:01.083  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:51:01.083  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-17 19:51:01.083  7407  7407 I dhcpcd  : bssid match
,08-17 19:51:01.093  7407  7407 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-17 19:51:01.163  1014  2075 V SAMP_SPCM_test: CSC File load.. 
,08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-17 19:51:01.173  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
,08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-17 19:51:01.183  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-17 19:51:01.193  7323  7323 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 19:51:01.193  7407  7407 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-17 19:51:01.213  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-17 19:51:01.213  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-17 19:51:01.213  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 19:51:01.223  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbc,agent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 19:51:01.233  1014  2075 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-17 19:51:01.243  7407  7407 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
08-17 19:51:01.243  7323  7323 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 19:51:01.243  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:51:01.243  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:51:01.243  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:51:01.243  1014  2075 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,08-17 19:51:01.243  1014  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 19:51:01.243  1014  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:01.243  1014  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:01.243  1014  2075 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:01.253  7414  7414 E Zygote  : MountEmulatedStorage(),
,08-17 19:51:01.263  7414  7414 E Zygote  : v2,
08-17 19:51:01.263  7414  7414 I libpersona: KNOX_SDCARD checking this for 1000
,08-17 19:51:01.263  7414  7414 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:01.263  1014  2075 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7414 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-17 19:51:01.263  7414  7414 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:01.263  7323  7323 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 19:51:01.263  7323  7323 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-17 19:51:01.263  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:01.263  7323  7323 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 19:51:01.263  7323  7323 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 19:51:01.263  7323  7323 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-17 19:51:01.263  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:51:01.263  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:01.263  1014  1129 D Tethering: InitialState.processMessage what=4
08-17 19:51:01.273  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:51:01.273  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:51:01.273  1014  1129 E Tethering: No numeric data
,08-17 19:51:01.273  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:01.273  7414  7414 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:51:01.273  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:01.273  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:51:01.273  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:01.273  7414  7414 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:51:01.273  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:51:01.273  1014  1129 D Tethering: clearTetheredNotification()
,08-17 19:51:01.273  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:51:01.273  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:51:01.283  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:01.283  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:51:01.283  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:51:01.283  1177  1177 D HotspotTile: updateTetherState():false, false
,08-17 19:51:01.283  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:01.283  1014  1122 V NetworkStats: performPollLocked() took 4ms
,08-17 19:51:01.283  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:01.283  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:01.333  7414  7414 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:51:01.343  7414  7414 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:01.363  7414  7414 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
08-17 19:51:01.363   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:51:01.413  1014  2075 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-17 19:51:01.413  1014  1014 I ActivityManager: Killing 6923:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-17 19:51:01.463  7323  7323 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:51:01.603  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:51:01.603  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:51:01.603  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:51:01.603  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:51:01.603  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:51:01.613  7323  7323 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 19:51:01.613  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:51:01.713  1014  1213 I ActivityManager: Killing 7067:com.sec.pcw.device/1000 (adj 15): empty #21,
,08-17 19:51:01.713  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-17 19:51:01.713  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:51:01.723  7009  7009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:51:01.723  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:51:01.723  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:51:01.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:01.723  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:01.733  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:01.733  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 19:51:01.733  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-17 19:51:01.733  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:01.733  1177  1177 D HotspotTile: onReceive : 1, 0
,08-17 19:51:01.733   287   287 E SMD     : DCD OFF
,08-17 19:51:01.733  2035  2216 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:51:01.733  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:01.733  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:51:01.743  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:01.743  1014  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:51:01.743  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:51:01.743  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:01.743  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:01.743  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:51:01.753  1631  1631 I Hs20UtilService: Starting #18
,08-17 19:51:01.753  1631  1717 I Hs20UtilService: Message received 5011
,08-17 19:51:01.753  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:51:01.753  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:51:01.753  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:51:01.753  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:51:01.803  1014  3326 D SSRM:n  : SIOP:: AP = 350,
,08-17 19:51:02.373   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:51:02.443   277  1007 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR,
,08-17 19:51:02.443  1014  1042 D Tethering: interfaceRemoved wlan0
,08-17 19:51:02.443  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:51:02.653  1014  1042 D Tethering: interfaceRemoved p2p0
,08-17 19:51:02.653  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:51:03.363   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-17 19:51:03.393  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 19:51:03.893  6762  6828 D BluetoothAdapter: enable()
,08-17 19:51:03.893  1014  1323 W ActivityManager: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-17 19:51:03.893  1014  1323 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-17 19:51:03.893  1014  1323 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
08-17 19:51:03.893  1014  1323 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:51:03.893  1014  1323 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256),
08-17 19:51:03.893  1014  1323 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
,08-17 19:51:03.893  1014  1323 W BluetoothManagerService: ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 19:51:03.893  1014  1323 W BluetoothManagerService: ,	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:51:03.893  1014  1323 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:03.893  1014  1323 D SettingsProvider: name = bluetooth_on,
08-17 19:51:03.893  1014  1323 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:03.903  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:03.903  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-17 19:51:03.903  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-17 19:51:03.903  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
08-17 19:51:03.903  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:03.903  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:03.903  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:03.903  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:03.923  7452  7452 E Zygote  : MountEmulatedStorage()
,08-17 19:51:03.923  7452  7452 E Zygote  : v2
,08-17 19:51:03.923  7452  7452 I libpersona: KNOX_SDCARD checking this for 1002
08-17 19:51:03.923  7452  7452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:51:03.923  7452  7452 I libpersona: KNOX_SDCARD not a persona
08-17 19:51:03.923  7452  7452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:51:03.923  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7452 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 19:51:03.933  7452  7452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:51:03.963  7452  7452 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-17 19:51:03.963  7452  7452 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:03.983  7452  7452 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 19:51:03.983  7452  7452 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:51:04.013  7452  7452 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding GattService
,08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding A2dpService
08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding HidService
08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding HealthService
,08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding PanService
08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding SapService
08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding SapClientService
,08-17 19:51:04.053  7452  7452 D BtSettings.ProfileConfig: Adding HidDevService
08-17 19:51:04.053  7452  7452 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:51:04.053  1014  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 19:51:04.053  1014  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.053  1014  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.053  1014  1213 D SettingsProvider: selectionArgs: false
08-17 19:51:04.053  1014  1213 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.053  1014  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.053  1014  1213 D SettingsProvider: ret = -1
,08-17 19:51:04.063  1014  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 19:51:04.063  1014  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.063  1014  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  1477 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  1477 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  1477 D SettingsProvider: ret = -1
,08-17 19:51:04.063  1014  1333 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-17 19:51:04.063  1014  1333 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.063  1014  1333 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  1333 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  1333 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  1333 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  1333 D SettingsProvider: ret = -1
08-17 19:51:04.063  1014  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-17 19:51:04.063  1014  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:51:04.063  1014  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  1465 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  1465 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  1465 D SettingsProvider: ret = -1
,08-17 19:51:04.063  1014  4019 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-17 19:51:04.063  1014  4019 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.063  1014  4019 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  4019 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  4019 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  4019 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  4019 D SettingsProvider: ret = -1
,08-17 19:51:04.063  1014  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-17 19:51:04.063  1014  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.063  1014  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  1472 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  1472 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  1472 D SettingsProvider: ret = -1
,08-17 19:51:04.063  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 19:51:04.063  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.063  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  1026 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  1026 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  1026 D SettingsProvider: ret = -1
08-17 19:51:04.063  1014  1495 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-17 19:51:04.063  1014  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.063  1014  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  1495 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  1495 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  1495 D SettingsProvider: ret = -1
,08-17 19:51:04.063  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:04.063  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.063  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.063  1014  1027 D SettingsProvider: selectionArgs: false
08-17 19:51:04.063  1014  1027 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.063  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.063  1014  1027 D SettingsProvider: ret = -1
,08-17 19:51:04.073  1014  1323 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService,
,08-17 19:51:04.073  1014  1323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.073  1014  1323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.073  1014  1323 D SettingsProvider: selectionArgs: false
08-17 19:51:04.073  1014  1323 D SettingsProvider: selectionArgs: 1002
,08-17 19:51:04.073  1014  1323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.073  1014  1323 D SettingsProvider: ret = -1
08-17 19:51:04.073  1014  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 19:51:04.073  1014  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.073  1014  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.073  1014  1486 D SettingsProvider: selectionArgs: false,
08-17 19:51:04.073  1014  1486 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.073  1014  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.073  1014  1486 D SettingsProvider: ret = -1
,08-17 19:51:04.073  1014  4020 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 19:51:04.073  1014  4020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.073  1014  4020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.073  1014  4020 D SettingsProvider: selectionArgs: false
08-17 19:51:04.073  1014  4020 D SettingsProvider: selectionArgs: 1002,
08-17 19:51:04.073  1014  4020 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.073  1014  4020 D SettingsProvider: ret = -1
,08-17 19:51:04.093  7452  7452 D BluetoothAdapterState: make
,08-17 19:51:04.093  7452  7452 I bluedroid: init
,08-17 19:51:04.103  7452  7467 I BluetoothAdapterState: Entering OffState
,08-17 19:51:04.103  7452  7452 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,08-17 19:51:04.103  7452  7452 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 19:51:04.103  7452  7452 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:51:04.103  7452  7452 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 19:51:04.103  7452  7452 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-17 19:51:04.103  7452  7452 I bluedroid: get_profile_interface socket
08-17 19:51:04.103  7452  7452 I bluedroid: get_profile_interface map_client
08-17 19:51:04.103  7452  7470 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 19:51:04.103  7452  7452 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 19:51:04.113  7452  7452 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,08-17 19:51:04.113  7452  7470 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-17 19:51:04.113  7452  7470 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:51:04.113  7452  7470 I bluedroid: getModelRssiValues
08-17 19:51:04.113  7452  7470 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:51:04.113  7452  7470 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:51:04.113  1014  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:51:04.113  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.113  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:04.113  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.123  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:04.123  1014  1014 D SettingsProvider: name = bluetooth_name
,08-17 19:51:04.123  7452  7470 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:51:04.123  7452  7460 I bluedroid: config_hci_snoop_log
,08-17 19:51:04.123  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-17 19:51:04.123  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-17 19:51:04.123  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 19:51:04.133  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 19:51:04.133  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:51:04.133  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:04.133  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:04.133  7452  7452 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 19:51:04.133  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 19:51:04.143  7452  7467 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 19:51:04.143  7452  7467 D BluetoothAdapterProperties: Setting state to 11
,08-17 19:51:04.143  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:51:04.143  7452  7467 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 19:51:04.143  7452  7467 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 19:51:04.143  7452  7467 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 19:51:04.143  7452  7467 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:51:04.143  7452  7467 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 19:51:04.153  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:04.153  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-17 19:51:04.163  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:51:04.163  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:04.163  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-17 19:51:04.163  7452  7467 D BluetoothSecureManager: getInstant: null
,08-17 19:51:04.163  7452  7467 D BluetoothSecureManager: calling getMethod for getService
08-17 19:51:04.163  7452  7467 D BluetoothSecureManager: calling getService
,08-17 19:51:04.163  7452  7467 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@83bb0f
,08-17 19:51:04.163  1861  1861 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:51:04.163  1014  1495 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 19:51:04.163  1014  1495 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-17 19:51:04.163  7452  7467 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:51:04.163  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:51:04.163  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:04.163  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 19:51:04.163  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:51:04.163  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:51:04.163  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:51:04.173  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 19:51:04.173  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:51:04.173  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 19:51:04.173  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:51:04.173  1014  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:04.173  1014  1333 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 19:51:04.173  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 19:51:04.173  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:51:04.173  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:51:04.173  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.173  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 19:51:04.173  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:51:04.173  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:51:04.183  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:04.183  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:04.183  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:04.183  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:04.183  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:04.183  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-17 19:51:04.183  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:04.183  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 19:51:04.183  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:51:04.183  7452  7467 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 19:51:04.183  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:51:04.183  7452  7467 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:04.183  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:04.183  7452  7467 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:04.183  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:51:04.193  7452  7467 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:51:04.193  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:51:04.193  7452  7467 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 19:51:04.193  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:51:04.203  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:04.203  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:51:04.203  7452  7467 D BluetoothBondStateMachine: make
08-17 19:51:04.203  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 19:51:04.203  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:04.203  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:04.203  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:04.203  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:04.203  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:51:04.203  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:51:04.203  7452  7472 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 19:51:04.203  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:51:04.213  7473  7473 E Zygote  : MountEmulatedStorage()
,08-17 19:51:04.213  7473  7473 E Zygote  : v2
08-17 19:51:04.213  7473  7473 I libpersona: KNOX_SDCARD checking this for 10055
08-17 19:51:04.213  7473  7473 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:04.213  7473  7473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:04.213  7473  7473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:51:04.213  1014  1477 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7473 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-17 19:51:04.223  1014  4020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.223  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.223  1014  4020 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:51:04.223  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.223  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.223  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:51:04.223  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 19:51:04.223  7473  7473 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:51:04.223  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:51:04.223  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:51:04.223  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 19:51:04.223  7452  7452 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:51:04.223  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.223  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.223  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:51:04.223  7452  7452 D BtGatt.GattService: Received start request. Starting profile...
08-17 19:51:04.223  7452  7452 D BtGatt.GattService: start()
08-17 19:51:04.223  7452  7452 D BtGatt.GattService: start()
08-17 19:51:04.223  7452  7452 I bluedroid: get_profile_interface gatt
08-17 19:51:04.223  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:51:04.223  7452  7452 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:51:04.223  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:51:04.223  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:51:04.223  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 19:51:04.223  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.223  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.223  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.223  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.223  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:04.233  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 19:51:04.233  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:51:04.233  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:51:04.233  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.233  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.233  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.233  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.233  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:04.243  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:51:04.243  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:51:04.243  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:51:04.243  7452  7452 D BtGatt.GattService: mStartError = false
08-17 19:51:04.243  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:51:04.243  1014  1333 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.243  1014  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.243  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:04.243  1014  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.243  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:04.243  7452  7452 D HeadsetService: Received start request. Starting profile...
08-17 19:51:04.243  7452  7452 D HeadsetService: start()
,08-17 19:51:04.243  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:51:04.243  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:51:04.243  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:51:04.243  7452  7452 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 19:51:04.243  1014  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.243  7452  7452 D HeadsetStateMachine: make
08-17 19:51:04.243  1014  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 19:51:04.243  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.243  1014  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.243  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:51:04.253  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:51:04.253  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 19:51:04.253  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.253  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.253  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.253  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:51:04.253  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:51:04.253  7452  7452 E HeadsetStateMachine: # of Max HF connection is 2,
08-17 19:51:04.253  1014  4020 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:04.253  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.253  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.253  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.253  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:04.253  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:04.253  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:51:04.253  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:51:04.253  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:51:04.253  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:51:04.253  7452  7467 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:51:04.263  1014  1213 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 19:51:04.263  1014  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.263  1014  1213 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.263  1014  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:51:04.263  1014  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:51:04.263  7473  7473 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:51:04.263  7473  7473 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:04.263  1014  1477 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 19:51:04.263  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 19:51:04.263  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.263  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:04.263  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:51:04.263  7452  7452 I bluedroid: get_profile_interface handsfree
,08-17 19:51:04.283  7452  7452 I DualScoManager: Instantiating Dual Sco Manager
08-17 19:51:04.283  7452  7452 I DualScoManager: Set HeadsetServiceHelper
,08-17 19:51:04.283  7452  7452 D BluetoothAtMessage: createCMTIContentObservers
,08-17 19:51:04.293  1014  1486 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 19:51:04.293  1014  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:04.293  1014  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:04.293  1014  1486 D SettingsProvider: selectionArgs: false
08-17 19:51:04.293  1014  1486 D SettingsProvider: selectionArgs: 1002
08-17 19:51:04.293  1014  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:04.293  1014  1486 D SettingsProvider: ret = -1
,08-17 19:51:04.293  7452  7492 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 19:51:04.293  7452  7492 D HeadsetStateMachine: Clear mHeadsetBrsf
08-17 19:51:04.293  7452  7492 D HeadsetStateMachine: map size, before remove : 0
08-17 19:51:04.293  7452  7492 D HeadsetStateMachine: map size, after remove: 0
,08-17 19:51:04.293  7452  7452 D HeadsetService: mStartError = false
,08-17 19:51:04.293  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:04.293  7452  7452 D A2dpService: Received start request. Starting profile...
08-17 19:51:04.293  7452  7452 D A2dpService: start()
,08-17 19:51:04.293  7452  7452 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:51:04.303  7452  7452 I bluedroid: get_profile_interface avrcp
,08-17 19:51:04.303  7473  7473 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 19:51:04.303  7452  7452 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:51:04.303  7452  7452 D Avrcp   : Initialize Media Controller
,08-17 19:51:04.303  7452  7452 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 19:51:04.313  7452  7452 E Avrcp   : getActiveSessions
,08-17 19:51:04.313  7452  7452 D Avrcp   : pick active media Controller
08-17 19:51:04.313  7452  7452 D Avrcp   : Get the active Media Controller 
,08-17 19:51:04.323  7452  7452 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:51:04.323  7452  7495 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 19:51:04.323  7452  7452 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:51:04.323  7452  7452 D A2dpStateMachine: make
,08-17 19:51:04.333  7452  7452 I bluedroid: get_profile_interface a2dp
,08-17 19:51:04.333  7452  7497 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 19:51:04.333  7452  7452 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 19:51:04.333  7452  7452 D A2dpService: mStartError = false
08-17 19:51:04.333  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:04.333  7452  7452 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:51:04.333  7452  7496 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:51:04.333  7473  7473 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-17 19:51:04.333  7473  7473 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 19:51:04.333  7473  7473 D UserAnalysis: Create SecureDbHelper
,08-17 19:51:04.343  7452  7495 D BluetoothMediaBrowser: no now playing list
08-17 19:51:04.343  7452  7495 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 19:51:04.343  7452  7452 D HidService: Received start request. Starting profile...
08-17 19:51:04.343  7452  7452 D HidService: start()
08-17 19:51:04.343  7452  7452 I bluedroid: get_profile_interface hidhost
08-17 19:51:04.343  7452  7452 D HidService: setHidService(): set to: null
08-17 19:51:04.343  7452  7452 D HidService: mStartError = false
08-17 19:51:04.343  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:51:04.343  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-17 19:51:04.343  7452  7452 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 19:51:04.343  7473  7473 D IntelligenceServiceApplication: onCreate()
,08-17 19:51:04.343  7452  7452 D HealthService: Received start request. Starting profile...
08-17 19:51:04.343  7452  7452 D HealthService: start()
,08-17 19:51:04.343  1014  1465 I ActivityManager: Killing 7084:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-17 19:51:04.353  7452  7452 I bluedroid: get_profile_interface health
,08-17 19:51:04.353  7452  7452 D HealthService: mStartError = false
08-17 19:51:04.353  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:04.353  7452  7452 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:51:04.353  7452  7452 D PanService: Received start request. Starting profile...
,08-17 19:51:04.353  7452  7452 D PanService: start()
08-17 19:51:04.353  7452  7452 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:51:04.353  7452  7452 I bluedroid: get_profile_interface pan
,08-17 19:51:04.353  7452  7452 D PanService: mStartError = false
08-17 19:51:04.353  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:04.353  7473  7473 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-17 19:51:04.353  7452  7452 D BluetoothMapService: Received start request. Starting profile...
08-17 19:51:04.353  7452  7452 D BluetoothMapService: start()
,08-17 19:51:04.363  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-17 19:51:04.363  7452  7452 D BluetoothMapService: mStartError = false
08-17 19:51:04.363  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:04.363  7473  7473 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-17 19:51:04.363  7452  7452 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 19:51:04.363  7452  7452 D SapService: Received start request. Starting profile...
08-17 19:51:04.363  7452  7452 D SapService: start()
08-17 19:51:04.363  7452  7452 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:51:04.363  7452  7452 I bluedroid: get_profile_interface sap
08-17 19:51:04.363  7452  7452 D SapService: mStartError = false
08-17 19:51:04.363  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:04.363  7452  7452 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 19:51:04.363  1417  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:51:04.363  1417  1417 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-17 19:51:04.363  1417  1417 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:51:04.363  1417  1446 I Telecom : BluetoothPhoneService: Result of Message : true
08-17 19:51:04.363  7452  7452 D HeadsetStateMachine: Proxy object connected
,08-17 19:51:04.363  7452  7452 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-17 19:51:04.363  7473  7473 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 19:51:04.363  7452  7492 D HeadsetStateMachine: Disconnected process message: 11
08-17 19:51:04.363  7452  7452 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:51:04.363  7452  7452 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 19:51:04.363  7452  7452 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:51:04.363  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-17 19:51:04.363  7452  7452 D BluetoothA2dp: Proxy object connected
08-17 19:51:04.373  7452  7452 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 19:51:04.373  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:51:04.373  7452  7492 D HeadsetStateMachine: Disconnected process message: 18
,08-17 19:51:04.373  7452  7492 D HeadsetStateMachine: Disconnected process message: 10
08-17 19:51:04.373  7452  7492 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:51:04.373  7452  7492 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:51:04.373  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-17 19:51:04.373  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-17 19:51:04.373  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:51:04.373  1014  1477 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 19:51:04.373  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:04.383  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:04.383  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:04.383  1014  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:04.393  7502  7502 E Zygote  : MountEmulatedStorage(),
08-17 19:51:04.393  7502  7502 E Zygote  : v2
08-17 19:51:04.393  7502  7502 I libpersona: KNOX_SDCARD checking this for 10105
08-17 19:51:04.393  7502  7502 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:04.393  7502  7502 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:04.393  1014  1477 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7502 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-17 19:51:04.393  7502  7502 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:51:04.393  7502  7502 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:51:04.413  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 19:51:04.413  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:51:04.423  7452  7467 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-17 19:51:04.423  7452  7467 I bluedroid: enable
,08-17 19:51:04.423  7452  7515 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 19:51:04.423  7452  7467 I bt_hci_bdroid: init
,08-17 19:51:04.433  7452  7467 I bt_vendor: bt-vendor : init
,08-17 19:51:04.433  7452  7467 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 19:51:04.433  7452  7467 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 19:51:04.433  7452  7467 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-17 19:51:04.433  7452  7467 D bt_userial_mct: userial_init
,08-17 19:51:04.433  7452  7467 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:51:04.433  7452  7467 I bt_vendor: Starting hciattach daemon
08-17 19:51:04.433  7452  7467 I bt_vendor: try to set false
,08-17 19:51:04.433  7452  7467 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 19:51:04.433  7452  7467 I bt_vendor: Starting hciattach daemon
08-17 19:51:04.433  7452  7467 I bt_vendor: try to set true
,08-17 19:51:04.433  7502  7502 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-17 19:51:04.433  7502  7502 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:04.453  7521  7521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 19:51:04.503  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 19:51:04.513  7528  7528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:51:04.533  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:51:04.543  7532  7532 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 19:51:04.553  7534  7534 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 19:51:04.553  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 19:51:04.593   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:51:04.593   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:51:04.593  7502  7540 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:51:04.603   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:51:04.603   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:51:04.603  7502  7540 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:51:04.733   287   287 E SMD     : DCD OFF
,08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.743  7502  7502 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:04.743  7502  7502 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:04.753  1014  1027 I ActivityManager: Killing 7099:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-17 19:51:04.753  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 19:51:04.763  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:51:04.833  7502  7545 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 19:51:04.853  7551  7551 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-17 19:51:04.853  1014  1465 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:51:04.853  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:04.853  1014  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:04.853  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 19:51:04.863  7552  7552 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 19:51:04.893  7452  7467 I bt_vendor: bluetooth satus is on
,08-17 19:51:04.893  7452  7519 D bt_userial_mct: userial_open(port:0)
08-17 19:51:04.893  7452  7519 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 19:51:04.893  7452  7519 I bt_vendor: Done intiailizing UART
,08-17 19:51:04.903  7452  7519 I bt_vendor: Done intiailizing UART
,08-17 19:51:04.903  7452  7519 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-17 19:51:04.903  7452  7519 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-17 19:51:04.903  7452  7556 D bt_userial_mct: Entering userial_read_thread()
,08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_A2D
,08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 19:51:04.903  7452  7515 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 19:51:04.913  7452  7515 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:51:04.913  7452  7515 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 19:51:04.913  7452  7515 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 19:51:05.003  7452  7515 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 19:51:05.013  7452  7515 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41e2ed1 
08-17 19:51:05.013  7452  7515 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41e2ed1 
,08-17 19:51:05.023  7452  7470 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 19:51:05.023  7452  7470 E bt-btif : Calling BTA_HhEnable
,08-17 19:51:05.033  7452  7470 E bt-btif : btif_storage_get_adapter_property service_ma, proto_id 0
,08-17 19:51:05.033  7452  7470 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-17 19:51:05.033  7452  7470 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:51:05.033  7452  7470 I bluedroid: getModelRssiValues
08-17 19:51:05.033  7452  7470 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:51:05.033  7452  7470 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:51:05.033  7452  7470 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:51:05.033  1014  1014 D SettingsProvider: name = bluetooth_name
,08-17 19:51:05.033  7452  7470 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:51:05.033  7452  7470 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:51:05.043  7452  7470 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:51:05.043  7452  7470 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-17 19:51:05.043  7452  7470 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-17 19:51:05.043  7452  7470 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 19:51:05.043  7452  7470 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 19:51:05.043  7452  7470 E bt-btif : btif_sock_init: !vhci_init
08-17 19:51:05.043  7452  7470 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 19:51:05.043  7452  7470 D IOP_DB_BT: db_open: db_open : handle 3026276368l, read 13894 bytes onto local cache
,08-17 19:51:05.043  7452  7470 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-17 19:51:05.043  7452  7470 D IOP_DB_BT: db_query: result 1
08-17 19:51:05.043  7452  7470 I         : iop_db_open: iop_db_open status 0
,08-17 19:51:05.043  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 19:51:05.043  7452  7470 D bte_conf: Device ID record 1 : primary
08-17 19:51:05.043  7452  7470 D bte_conf:   vendorId            = 0075
08-17 19:51:05.043  7452  7470 D bte_conf:   vendorIdSource      = 0001
,08-17 19:51:05.043  7452  7470 D bte_conf:   product             = 0100
08-17 19:51:05.043  7452  7470 D bte_conf:   version             = 0200
08-17 19:51:05.043  7452  7470 D bte_conf:   clientExecutableURL = 
08-17 19:51:05.043  7452  7470 D bte_conf:   serviceDescription  = ,
08-17 19:51:05.043  7452  7470 D bte_conf:   documentationURL    = 
08-17 19:51:05.043  7452  7470 D bte_conf: bte_load_did_conf no section named DID2.
08-17 19:51:05.043  7452  7470 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:51:05.053  7452  7467 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 19:51:05.053  7452  7467 D BluetoothAdapterProperties: ScanMode =  20
08-17 19:51:05.053  7452  7467 D BluetoothAdapterProperties: State =  11
,08-17 19:51:05.053  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:05.053  1014  1333 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-17 19:51:05.053  7452  7467 D BluetoothAdapterProperties: Setting state to 12
08-17 19:51:05.053  7452  7467 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:51:05.053  7452  7556 E bt_mct  : hci lib postload completed
,08-17 19:51:05.053  7452  7470 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:51:05.053  7452  7470 D BluetoothAdapterProperties: Scan Mode:21
,08-17 19:51:05.063  1014  1323 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-17 19:51:05.063  1014  1323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:05.063  1014  1323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:05.063  1014  1323 D SettingsProvider: selectionArgs: false
08-17 19:51:05.063  1014  1323 D SettingsProvider: selectionArgs: 1002
08-17 19:51:05.063  1014  1323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:05.063  1014  1323 D SettingsProvider: ret = -1
,08-17 19:51:05.063  7452  7467 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:51:05.063  7452  7467 D BluetoothAdapterService: updateAdapterState state is 12
08-17 19:51:05.063  7452  7470 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:51:05.063  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:05.063  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.063  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.063  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.063  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.063  1305  1313 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:51:05.073  7452  7467 D BluetoothAdapterService: Autoconnection is available 
08-17 19:51:05.073  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:05.073  7452  7467 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 19:51:05.073  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 19:51:05.073  7452  7467 D BluetoothAdapterService: starting service from this receiver
08-17 19:51:05.073  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.073  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.073  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:51:05.073  7452  7467 I BluetoothAdapterState: Entering On State from state = 11
,08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:05.083  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:05.083  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 19:51:05.083  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.083  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.083  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.083  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.083  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:51:05.083  1014  1323 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:51:05.093  1014  1323 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-17 19:51:05.093  1014  1323 D BatteryService: stay LED for fully charged
08-17 19:51:05.093  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:51:05.093  1177  4941 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:05.093  1177  4941 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:51:05.093  7452  7464 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:05.093  7452  7464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:05.093  2035  3012 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:05.093  2035  3012 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:05.093  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:05.093  7452  7452 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 19:51:05.103  1014  1014 I MotionRecognitionService: Plugged
08-17 19:51:05.103  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:51:05.103  1449  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:05.103  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:05.113  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:05.113  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:51:05.113  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:51:05.113  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:51:05.113  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:51:05.133  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:51:05.133  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:05.133  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.133  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.133  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.133  1449  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:05.143  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:51:05.143  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:51:05.143  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:51:05.143  1305  1305 D BluetoothInputDevice: Proxy object connected
08-17 19:51:05.143  7452  7452 I BluetoothPbapService: Handler(): got msg=1
08-17 19:51:05.143  1305  1305 D HidProfile: Bluetooth service connected
,08-17 19:51:05.143  1417  6968 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:05.143  1014  1477 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:51:05.143  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:51:05.143  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:05.143  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.143  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.143  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.143  1417  6968 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:05.153  7452  7480 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:05.153  1305  1313 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:51:05.153  7452  7452 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:51:05.153  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 19:51:05.153  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.153  7452  7560 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 19:51:05.153  7452  7492 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:51:05.153  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.153  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.153  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.153  7502  7517 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:05.153  7502  7517 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:05.163  1305  1305 D BluetoothMap: Proxy object connected
,08-17 19:51:05.163  1305  1305 D MapProfile: Bluetooth service connected
08-17 19:51:05.163  1305  1305 D BluetoothMap: getConnectedDevices()
08-17 19:51:05.163  1305  7290 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:05.163  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:51:05.163  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:05.163  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.163  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.163  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.163  7452  7560 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:51:05.163  7452  7560 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:05.163  1305  7290 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:05.163  1305  1316 D BluetoothPan: Binding service...
,08-17 19:51:05.163  7452  7560 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-17 19:51:05.163  7452  7560 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:51:05.163  7452  7560 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:51:05.163  7452  7560 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dceee83
,08-17 19:51:05.163  7452  7560 D BluetoothSocket: channel: 19
08-17 19:51:05.163  7452  7560 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 19:51:05.163  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:51:05.163  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.173  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.173  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:51:05.173  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.173  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true,
08-17 19:51:05.173  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-17 19:51:05.173  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:51:05.173  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.173  1014  1014 D BluetoothA2dp: Proxy object connected
,08-17 19:51:05.173  1305  1305 D HeadsetProfile: Bluetooth service connected
08-17 19:51:05.173  1305  1313 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 19:51:05.173  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-17 19:51:05.173  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.173  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.173  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.173  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.183  1449  1650 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:05.183  1449  1650 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:05.183  1305  7290 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:05.183  1305  7290 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:05.183  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:51:05.183  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.183  1305  1305 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:51:05.183  1305  1305 D PanProfile: Bluetooth service connected
08-17 19:51:05.183  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.183  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.183  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.183  1305  1313 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:05.183  1305  1313 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:05.183  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:05.183  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:51:05.183  1014  1044 D BluetoothPan: Binding service...
,08-17 19:51:05.183  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:51:05.183  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.183  6762  6776 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:05.193  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:51:05.193  6762  6776 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:05.193  1417  1431 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:05.193  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:51:05.193  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:05.193  1305  1305 D BluetoothPbap: Proxy object connected
08-17 19:51:05.193  1305  1305 D PbapServerProfile: Bluetooth service connected
08-17 19:51:05.193  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.193  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.193  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 19:51:05.193  1305  1305 D BluetoothA2dp: Proxy object connected
,08-17 19:51:05.193  1305  1305 D A2dpProfile: Bluetooth service connected
08-17 19:51:05.193  1417  1431 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:05.193  1417  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:05.193  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:51:05.193  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:05.193  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.193  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.193  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.193  1417  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:05.203  1305  1316 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 19:51:05.203  1305  1316 D Bluetoothsap: Binding service...
,08-17 19:51:05.203  1305  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 19:51:05.203  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-17 19:51:05.203  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.203  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.203  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.203  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.203  1305  1305 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-17 19:51:05.203  1305  1316 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-17 19:51:05.203  1305  1305 D SapProfile: Bluetooth service connected
,08-17 19:51:05.213  1432  1448 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:05.213  1432  1448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:51:05.213  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-17 19:51:05.213  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:51:05.213  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:51:05.213  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:51:05.213  1305  1305 D Bluetoothsap: getConnectedDevices()
,08-17 19:51:05.213  1417  1431 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:05.213  1417  1431 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:05.213  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 19:51:05.213  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:51:05.213  1417  1417 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@32dbecef, true,
08-17 19:51:05.223  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:51:05.223  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:51:05.223  1861  1861 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:51:05.223  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:05.223  1177  1177 D BluetoothTile:  getBluetoothState : 12
08-17 19:51:05.223  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:05.223  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:05.223  1417  1417 D BluetoothHeadset: registerMessageListener
,08-17 19:51:05.223  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:05.233  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:51:05.233  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.233  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.233  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:05.233  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:05.233  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:05.233  1305  1305 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-17 19:51:05.233  1305  1305 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 19:51:05.233  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:05.233  1305  1305 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:51:05.233  1305  1305 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 19:51:05.233  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:05.233  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,08-17 19:51:05.233  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:51:05.233  7452  7480 D HeadsetService: registerMessageListener
,08-17 19:51:05.233  1014  1472 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:05.233  1014  1486 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-17 19:51:05.233  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:05.243  7452  7480 D HeadsetService: registerMessageListener
,08-17 19:51:05.243  7452  7492 D HeadsetStateMachine: Disconnected process message: 70
08-17 19:51:05.243  7452  7492 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2a19a800
08-17 19:51:05.243  1417  1417 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 19:51:05.243  1417  1417 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:51:05.243  7452  7564 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 19:51:05.243  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:05.243  1417  1417 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 19:51:05.243  1417  1417 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 19:51:05.243  1417  1417 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 19:51:05.243  1305  1305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:51:05.243  1014  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:51:05.243  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.243  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.253  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.253  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:51:05.253  7452  7564 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:51:05.253  7452  7564 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:05.253  7452  7492 D HeadsetStateMachine: Disconnected process message: 9
08-17 19:51:05.253  7452  7492 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 19:51:05.253  7452  7564 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-17 19:51:05.253  7452  7564 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:51:05.253  7452  7564 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:51:05.253  7452  7564 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e1cb839
,08-17 19:51:05.263  7452  7564 D BluetoothSocket: channel: 5
,08-17 19:51:05.263  1305  1305 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:51:05.263  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:51:05.263   282   671 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-17 19:51:05.263   282   671 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 19:51:05.263   282   671 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:51:05.263   282   671 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:51:05.263   282   671 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 19:51:05.263   282   671 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 19:51:05.263   282   671 V audio_hw_primary: adev_set_parameters: exit
08-17 19:51:05.263  7452  7492 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 19:51:05.273  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:05.273  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:51:05.273  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
08-17 19:51:05.273  7452  7452 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:51:05.273  1014  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:05.283  1014  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.283  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.283  1014  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:05.283  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:05.293  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:05.293  1014  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:51:05.293  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:51:05.303  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:05.303  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:05.303  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:05.313  1014  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:51:05.313  2035  7571 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-17 19:51:05.313  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:51:05.313  7452  7574 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 19:51:05.313  7452  7574 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:05.323  7452  7574 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-17 19:51:05.323  7452  7574 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:51:05.323  7452  7574 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:51:05.323  7452  7574 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aa5aafb
08-17 19:51:05.323  7452  7574 D BluetoothSocket: channel: 12
08-17 19:51:05.323  7452  7574 I BtOppRfcommListener: Accept thread started.
,08-17 19:51:05.463  1014  1026 I art     : Explicit concurrent mark sweep GC freed 72310(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 2.314ms total 150.180ms
,08-17 19:51:05.463  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:51:05.473  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.473  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:05.473  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:05.483  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:51:05.483  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:05.483  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:05.483  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:05.493  2035  7571 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 19:51:06.903  6762  6828 D BluetoothAdapter: disable(),
08-17 19:51:06.903  1014  1027 D SettingsProvider: name = bluetooth_on
,08-17 19:51:06.923  7452  7467 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 19:51:06.923  7452  7467 D BluetoothAdapterProperties: Setting state to 13
08-17 19:51:06.923  7452  7467 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:51:06.923  7452  7467 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:51:06.923  7452  7467 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 19:51:06.923  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:06.923  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
08-17 19:51:06.923  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:06.923  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:06.923  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:06.923  7452  7452 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-17 19:51:06.923  7452  7467 D BluetoothAdapterService: Autoconnection is available 
08-17 19:51:06.923  7452  7467 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 19:51:06.923  7452  7467 D BluetoothAdapterService: terminating service from this receiver
08-17 19:51:06.923  7452  7452 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bc47718, channel: 19, state: LISTENING
08-17 19:51:06.923  7452  7452 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1bc47718, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@dceee83, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23803571mSocket: android.net.LocalSocket@34455f56 impl:android.net.LocalSocketImpl@3719fbd7 fd:FileDescriptor[74]
08-17 19:51:06.923  7452  7452 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@34455f56 impl:android.net.LocalSocketImpl@3719fbd7 fd:FileDescriptor[74]
,08-17 19:51:06.933  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:06.933  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:51:06.933  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:51:06.943  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:51:06.943  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:06.943  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-17 19:51:06.943  1861  1861 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:51:06.943  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:06.943  1014  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-17 19:51:06.943  1014  4020 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:51:06.953  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:06.953  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:06.953  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:51:06.953  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:06.953  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:06.953  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:51:06.953  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:06.953  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:51:06.953  1014  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 19:51:06.953  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:06.953  1014  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:06.953  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:06.963  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:06.963  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:06.963  1305  1305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:51:06.963  7452  7467 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 19:51:06.963  7452  7467 D BluetoothAdapterProperties: mDiscovering is false
,08-17 19:51:06.963  6762  6762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:06.963  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:06.963  1014  1472 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 19:51:06.963  7452  7467 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:51:06.963  1014  1465 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:51:06.963  1014  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:51:06.963  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:06.963  1014  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:06.963  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:06.973  1014  1333 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:51:06.973  1014  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:51:06.973  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:06.973  1014  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:06.973  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:51:06.983  7452  7470 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:51:06.983  7452  7470 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:51:06.983  7452  7467 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-17 19:51:06.993  7452  7467 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-17 19:51:06.993  7452  7467 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 19:51:06.993  7452  7467 E bt-btif : BTA got event 0x1a1c
,08-17 19:51:06.993  7452  7467 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 19:51:06.993  7452  7515 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 19:51:06.993  7452  7515 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 19:51:06.993  7452  7574 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 19:51:06.993  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:51:06.993  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:51:06.993  7452  7515 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:51:06.993  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:06.993  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:06.993  7452  7452 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15ecc4, channel: 5, state: LISTENING
08-17 19:51:06.993  7452  7452 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15ecc4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e1cb839, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b11b7admSocket: android.net.LocalSocket@29501ae2 impl:android.net.LocalSocketImpl@2c187e73 fd:FileDescriptor[76]
08-17 19:51:06.993  7452  7452 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29501ae2 impl:android.net.LocalSocketImpl@2c187e73 fd:FileDescriptor[76]
,08-17 19:51:06.993  7452  7452 I BtOppRfcommListener: stopping Accept Thread
08-17 19:51:06.993  7452  7452 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ce71130, channel: 12, state: LISTENING
08-17 19:51:06.993  7452  7452 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ce71130, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aa5aafb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@10bf21a9mSocket: android.net.LocalSocket@f59032e impl:android.net.LocalSocketImpl@b728ecf fd:FileDescriptor[80]
08-17 19:51:06.993  7452  7452 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f59032e impl:android.net.LocalSocketImpl@b728ecf fd:FileDescriptor[80]
,08-17 19:51:06.993  7452  7574 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 19:51:06.993  1305  1305 D BluetoothPbap: Proxy object disconnected
08-17 19:51:06.993  1305  1305 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:51:07.003  1305  1305 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:51:07.003  7452  7452 V BluetoothOppManager: cleanUp...
,08-17 19:51:07.003  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:51:07.013  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:07.013  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 19:51:07.033  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:07.033  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:51:07.193  7452  7515 W bt-btif : ag scb idx 1 not allocated
08-17 19:51:07.193  7452  7515 W bt-btif : ag scb idx 2 not allocated
08-17 19:51:07.193  7452  7515 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 19:51:07.193  7452  7556 I bt_userial_mct: exiting userial_read_thread
08-17 19:51:07.193  7452  7556 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 19:51:07.193  7452  7470 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 19:51:07.193  7452  7519 I bt_vendor: hw_epilog_process
08-17 19:51:07.193  7452  7470 D bt_userial_mct: userial_close
08-17 19:51:07.193  7452  7470 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 19:51:07.733   287   287 E SMD     : DCD OFF
,08-17 19:51:08.373  7452  7470 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 19:51:08.373  7452  7470 I bt_vendor: bluetooth satus is on
08-17 19:51:08.373  7452  7470 I bt_vendor: bt-vendor : resetting BT status
08-17 19:51:08.373  7452  7470 I bt_vendor: Starting hciattach daemon
08-17 19:51:08.373  7452  7470 I bt_vendor: try to set false
,08-17 19:51:08.373  7452  7470 I bt_vendor: Starting hciattach daemon
08-17 19:51:08.373  7452  7470 I bt_vendor: try to set false
,08-17 19:51:08.373  7452  7470 I bt_vendor: cleanup
08-17 19:51:08.373  7452  7515 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-17 19:51:08.373  7452  7470 I GKI_LINUX: GKI_exit_task 0 done
08-17 19:51:08.373  7452  7470 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 19:51:08.373  7452  7467 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 19:51:08.373  7452  7467 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:51:08.373  7452  7467 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-17 19:51:08.373  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:51:08.373  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:51:08.373  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:51:08.373  1014  4019 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-17 19:51:08.373  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:08.373  1014  4019 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.373  1014  4019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.373  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:51:08.373  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:51:08.373  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:51:08.373  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 19:51:08.383  7452  7452 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:51:08.383  1014  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:08.383  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.383  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:08.383  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.383  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:08.383  7452  7452 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:51:08.383  7452  7452 D BtGatt.GattService: stop()
08-17 19:51:08.383  7452  7452 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 19:51:08.383  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:51:08.383  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:51:08.383  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:51:08.383  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1,
08-17 19:51:08.383  1014  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:08.383  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.383  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:08.383  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.383  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:08.383  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 19:51:08.393  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-17 19:51:08.393  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:51:08.393  7452  7452 D HeadsetService: Received stop request...Stopping profile...
08-17 19:51:08.393  1014  1465 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:08.393  1014  1465 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.393  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:08.393  1014  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.393  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:08.393  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:51:08.393  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:51:08.393  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:51:08.393  1014  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:08.393  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.393  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:08.393  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.393  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:08.393  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:08.403  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 19:51:08.403  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:51:08.403  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:51:08.403  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:51:08.403  1305  1305 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:51:08.403  1014  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:08.403  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.403  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:08.403  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.403  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:08.403  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:08.403  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:51:08.403  7452  7467 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:08.403  1014  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:08.403  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.403  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:08.403  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.403  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:08.403  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:51:08.403  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:51:08.403  7452  7467 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:51:08.403  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:08.403  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.403  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:08.403  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.403  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:08.413  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:08.413  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:51:08.413  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:51:08.413  7452  7467 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:51:08.413  7452  7467 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:51:08.413  7452  7467 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 19:51:08.413  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-17 19:51:08.413  7452  7452 D A2dpService: Received stop request...Stopping profile...
,08-17 19:51:08.413  7452  7496 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:51:08.413  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:08.413  1305  1305 D BluetoothA2dp: Proxy object disconnected
,08-17 19:51:08.413  1305  1305 D A2dpProfile: Bluetooth service disconnected
08-17 19:51:08.413  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-17 19:51:08.413  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 19:51:08.413  7452  7452 D HidService: Received stop request...Stopping profile...
08-17 19:51:08.413  7452  7452 D HidService: Stopping Bluetooth HidService
08-17 19:51:08.413  7452  7452 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-17 19:51:08.413  7452  7452 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:51:08.413  7452  7452 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:51:08.413  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:08.413  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:51:08.413  7452  7452 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:51:08.413  7452  7452 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:51:08.423  1305  1305 D BluetoothInputDevice: Proxy object disconnected
08-17 19:51:08.423  1305  1305 D HidProfile: Bluetooth service disconnected
,08-17 19:51:08.423  7452  7452 D HealthService: Received stop request...Stopping profile...
,08-17 19:51:08.423  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:08.423  7452  7452 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 19:51:08.423  7452  7452 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 19:51:08.423  7452  7452 D PanService: Received stop request...Stopping profile...
08-17 19:51:08.423  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:08.423  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 19:51:08.423  7452  7452 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:51:08.423  1305  1305 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:51:08.423  1305  1305 D PanProfile: Bluetooth service disconnected
,08-17 19:51:08.433  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:08.433  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-17 19:51:08.433  7452  7452 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:51:08.433  7452  7452 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:51:08.433  7452  7452 D BluetoothA2dp: Proxy object disconnected
08-17 19:51:08.433  7452  7452 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-17 19:51:08.433  7452  7452 D SapService: Received stop request...Stopping profile...
08-17 19:51:08.433  7452  7452 D SapService: Stopping Bluetooth SapService
08-17 19:51:08.433  7452  7452 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7faefb1
,08-17 19:51:08.433  7452  7497 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-17 19:51:08.433  7452  7452 I GKI_LINUX: GKI_exit_task 2 done
,08-17 19:51:08.433  7452  7452 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 19:51:08.433  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 19:51:08.433  7452  7452 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:51:08.433  7452  7452 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:08.433  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:51:08.433  7452  7452 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:51:08.433  7452  7452 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:51:08.433  7452  7452 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:51:08.443  7452  7452 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:51:08.443  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:51:08.443  7452  7452 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:51:08.443  7452  7452 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:51:08.443  7452  7452 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:51:08.443  7452  7452 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 19:51:08.443  1305  1305 D BluetoothMap: Proxy object disconnected
08-17 19:51:08.443  1305  1305 D MapProfile: Bluetooth service disconnected
08-17 19:51:08.443  1305  1305 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 19:51:08.443  1305  1305 D SapProfile: Bluetooth service disconnected
,08-17 19:51:08.443  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 19:51:08.443  7452  7452 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:51:08.443  7452  7452 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-17 19:51:08.443  7452  7452 E BluetoothAdapterService(133885873): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-17 19:51:08.443  7452  7452 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:51:08.443  7452  7452 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:51:08.443  7452  7467 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-17 19:51:08.443  7452  7467 D BluetoothAdapterProperties: Setting state to 10
08-17 19:51:08.443  7452  7467 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-17 19:51:08.443  7452  7467 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:51:08.443  7452  7467 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 19:51:08.443  7452  7467 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:51:08.443  7452  7467 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 19:51:08.443  7452  7467 I BluetoothAdapterState: Entering OffState
,08-17 19:51:08.443  1305  1316 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:51:08.443  1177  4941 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:51:08.443  1177  4941 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.453  7452  7464 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:51:08.453  7452  7464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.453  2035  2054 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:51:08.453  2035  2054 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.453  7452  7480 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:51:08.453  1305  1313 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:51:08.453  7502  7518 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:51:08.453  7502  7518 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.453  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:51:08.453  1305  1316 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:51:08.463  1449  1485 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:51:08.463  1449  1485 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.463  1305  1313 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:51:08.463  1305  7561 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:51:08.463  1305  7561 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:51:08.463  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:51:08.463  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.463  6762  6777 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:51:08.463  6762  6777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.463  6762  6777 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 19:51:08.463  6762  6777 D BluetoothLeAdvertiser: Exit stop advertising
08-17 19:51:08.463  6762  6777 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-17 19:51:08.463  6762  6777 D BluetoothLeScanner: Exiting stopAllScan
,08-17 19:51:08.463  1305  7290 D Bluetoothsap: onBluetoothStateChange: up=false
,08-17 19:51:08.463  1305  7290 D Bluetoothsap: Unbinding service...
,08-17 19:51:08.463  1432  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:51:08.463  1432  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.473  1417  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:51:08.473  1417  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:51:08.473  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 19:51:08.473  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:51:08.483  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:08.483  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-17 19:51:08.483  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:51:08.483  1177  1177 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
,08-17 19:51:08.483  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:51:08.483  1177  1747 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
,08-17 19:51:08.483  7452  7470 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 19:51:08.483  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:08.483  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-17 19:51:08.483  1177  1747 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
08-17 19:51:08.483  7452  7452 I GKI_LINUX: GKI_exit_task 1 done
08-17 19:51:08.483  7452  7452 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-17 19:51:08.493  7452  7452 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 19:51:08.493  1177  1177 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
,08-17 19:51:08.493  1177  1177 D BluetoothAdapter: 860545745: getState() :  mService = null. Returning STATE_OFF
,08-17 19:51:08.493  1014  4020 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:08.493  7452  7452 I art     : System.exit called, status: 0
,08-17 19:51:08.493  7452  7452 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 19:51:08.493  1014  1465 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:51:08.493  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:08.493  1861  1861 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 19:51:08.493  2035  2216 D BluetoothAdapter: 683006723: getState() :  mService = null. Returning STATE_OFF
08-17 19:51:08.493  2035  2216 D BluetoothAdapter: 683006723: getState() :  mService = null. Returning STATE_OFF
08-17 19:51:08.493  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:08.493  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:08.503  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:08.503  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:51:08.503  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 19:51:08.503  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:08.503  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:08.503  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:08.503  1305  1305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:51:08.503  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:51:08.503  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.513  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:08.513  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:08.513  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:51:08.513  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:51:08.523  1305  1305 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:51:08.523  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:51:08.533  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:08.533  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:51:08.533  1014  1027 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 19:51:08.543  1014  1027 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 19:51:08.543  1014  1027 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-17 19:51:08.543  1014  1027 W BroadcastQueue: android.os.TransactionTooLargeException
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-17 19:51:08.543  1014  1027 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:51:08.543  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 19:51:08.553  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:08.553  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:08.553  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:08.553  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:08.563  7591  7591 E Zygote  : MountEmulatedStorage()
,08-17 19:51:08.563  7591  7591 E Zygote  : v2
08-17 19:51:08.563  7591  7591 I libpersona: KNOX_SDCARD checking this for 1002
08-17 19:51:08.563  7591  7591 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:08.563  7591  7591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:08.563  1014  1027 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7591 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-17 19:51:08.563  7591  7591 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:51:08.563  7591  7591 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:51:08.593  7591  7591 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:51:08.593  7591  7591 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:08.603  7591  7591 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 19:51:08.603  7591  7591 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:51:08.623  7591  7591 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding GattService
,08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding HeadsetService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding A2dpService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding HidService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding HealthService
,08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding PanService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding SapService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding HeadsetClientService,
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding SapClientService
08-17 19:51:08.653  7591  7591 D BtSettings.ProfileConfig: Adding HidDevService
08-17 19:51:08.653  7591  7591 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:51:08.663  1014  4019 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 19:51:08.663  1014  4019 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.663  1014  4019 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.663  1014  4019 D SettingsProvider: selectionArgs: false
,08-17 19:51:08.663  1014  4019 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.663  1014  4019 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:51:08.663  1014  4019 D SettingsProvider: ret = -1
,08-17 19:51:08.663  1014  4020 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 19:51:08.663  1014  4020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.663  1014  4020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.663  1014  4020 D SettingsProvider: selectionArgs: false
,08-17 19:51:08.663  1014  4020 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.663  1014  4020 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.663  1014  4020 D SettingsProvider: ret = -1
,08-17 19:51:08.663  1014  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-17 19:51:08.663  1014  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.663  1014  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.663  1014  1495 D SettingsProvider: selectionArgs: false
08-17 19:51:08.663  1014  1495 D SettingsProvider: selectionArgs: 1002
,08-17 19:51:08.663  1014  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.663  1014  1495 D SettingsProvider: ret = -1
,08-17 19:51:08.663  1014  1323 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 19:51:08.663  1014  1323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.663  1014  1323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.663  1014  1323 D SettingsProvider: selectionArgs: false
08-17 19:51:08.663  1014  1323 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.663  1014  1323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.663  1014  1323 D SettingsProvider: ret = -1
,08-17 19:51:08.663  1014  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 19:51:08.663  1014  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.663  1014  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.663  1014  1472 D SettingsProvider: selectionArgs: false
08-17 19:51:08.663  1014  1472 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.663  1014  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.663  1014  1472 D SettingsProvider: ret = -1
,08-17 19:51:08.663  1014  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 19:51:08.663  1014  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.663  1014  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:51:08.663  1014  1477 D SettingsProvider: selectionArgs: false
08-17 19:51:08.663  1014  1477 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.663  1014  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.663  1014  1477 D SettingsProvider: ret = -1
,08-17 19:51:08.673  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:08.673  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.673  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.673  1014  1026 D SettingsProvider: selectionArgs: false
08-17 19:51:08.673  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-17 19:51:08.673  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.673  1014  1026 D SettingsProvider: ret = -1
,08-17 19:51:08.673  1014  1333 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 19:51:08.673  1014  1333 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.673  1014  1333 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.673  1014  1333 D SettingsProvider: selectionArgs: false
08-17 19:51:08.673  1014  1333 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.673  1014  1333 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.673  1014  1333 D SettingsProvider: ret = -1
,08-17 19:51:08.673  1014  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:08.673  1014  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.673  1014  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.673  1014  1465 D SettingsProvider: selectionArgs: false
08-17 19:51:08.673  1014  1465 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.673  1014  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.673  1014  1465 D SettingsProvider: ret = -1
,08-17 19:51:08.673  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:08.673  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.673  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.673  1014  1027 D SettingsProvider: selectionArgs: false
08-17 19:51:08.673  1014  1027 D SettingsProvider: selectionArgs: 1002
,08-17 19:51:08.673  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.673  1014  1027 D SettingsProvider: ret = -1
,08-17 19:51:08.673  1014  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 19:51:08.673  1014  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:08.673  1014  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:51:08.673  1014  1476 D SettingsProvider: selectionArgs: false
08-17 19:51:08.673  1014  1476 D SettingsProvider: selectionArgs: 1002
08-17 19:51:08.673  1014  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.673  1014  1476 D SettingsProvider: ret = -1
,08-17 19:51:08.673  1014  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 19:51:08.673  1014  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:51:08.673  1014  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:08.673  1014  1486 D SettingsProvider: selectionArgs: false
08-17 19:51:08.673  1014  1486 D SettingsProvider: selectionArgs: 1002
,08-17 19:51:08.673  1014  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:08.673  1014  1486 D SettingsProvider: ret = -1
,08-17 19:51:08.693  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:08.693  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:51:08.693  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:51:08.693  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:08.693  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:08.693  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:08.703  2035  7607 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:51:08.703  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
,08-17 19:51:08.703  1014  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:51:08.713  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:08.713  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:08.713  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:08.723  2035  7607 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 19:51:09.933  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:51:09.933  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:10.733   287   287 E SMD     : DCD OFF,
,08-17 19:51:11.853  1014  3326 D SSRM:n  : SIOP:: AP = 330,
,08-17 19:51:12.933  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:12.933  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31a79133 added. We now have 6 listener(s)
08-17 19:51:12.933  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:12.933  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:12.933  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33088cf0 added. We now have 7 listener(s)
08-17 19:51:12.933  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:12.933  6762  6828 I System.out: IsBluetoothEnabled
,08-17 19:51:12.933  6762  6828 D BluetoothAdapter: disable()
,08-17 19:51:12.943  1014  1486 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-17 19:51:12.943  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:12.943  6762  6828 D BluetoothAdapter: enable()
,08-17 19:51:12.943  1014  1465 W ActivityManager: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:51:12.943  1014  1465 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 19:51:12.943  1014  1465 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:51:12.943  1014  1465 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:51:12.943  1014  1465 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 19:51:12.943  1014  1465 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 19:51:12.943  1014  1465 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 19:51:12.943  1014  1465 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:51:12.943  1014  1465 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:51:12.943  1014  1465 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:12.953  1014  1465 D SettingsProvider: name = bluetooth_on
,08-17 19:51:12.953  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:51:12.953  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:12.953  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-17 19:51:12.963  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 19:51:12.983  7591  7591 D BluetoothAdapterState: make
,08-17 19:51:12.983  7591  7591 I bluedroid: init
,08-17 19:51:12.983  7591  7613 I BluetoothAdapterState: Entering OffState
,08-17 19:51:12.993  7591  7591 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 19:51:12.993  7591  7591 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 19:51:12.993  7591  7591 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:51:12.993  7591  7591 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:51:12.993  7591  7591 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-17 19:51:12.993  7591  7591 I bluedroid: get_profile_interface socket
08-17 19:51:12.993  7591  7591 I bluedroid: get_profile_interface map_client
08-17 19:51:12.993  7591  7616 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 19:51:12.993  7591  7591 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 19:51:12.993  7591  7616 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 19:51:12.993  7591  7616 E BluetoothServiceJni: populateRssiValuesNative
,08-17 19:51:12.993  7591  7591 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.003  7591  7616 I bluedroid: getModelRssiValues
08-17 19:51:13.003  7591  7616 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:51:13.003  7591  7616 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:51:13.003  1014  1495 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 19:51:13.003  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.003  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.003  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.003  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.003  7591  7616 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:51:13.003  1014  1014 D SettingsProvider: name = bluetooth_name
,08-17 19:51:13.003  7591  7605 I bluedroid: config_hci_snoop_log
,08-17 19:51:13.003  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 19:51:13.013  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-17 19:51:13.013  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 19:51:13.013  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 19:51:13.013  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:51:13.013  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:13.013  7591  7591 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-17 19:51:13.013  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:51:13.013  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 19:51:13.023  7591  7613 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 19:51:13.023  7591  7613 D BluetoothAdapterProperties: Setting state to 11
08-17 19:51:13.023  7591  7613 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 19:51:13.023  7591  7613 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:51:13.023  7591  7613 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 19:51:13.023  7591  7613 D BluetoothAdapterService: Autoconnection is available 
08-17 19:51:13.023  7591  7613 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 19:51:13.023  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:13.023  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-17 19:51:13.033  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:51:13.033  7591  7613 D BluetoothSecureManager: getInstant: null
08-17 19:51:13.033  7591  7613 D BluetoothSecureManager: calling getMethod for getService
08-17 19:51:13.033  7591  7613 D BluetoothSecureManager: calling getService
,08-17 19:51:13.033  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:13.033  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-17 19:51:13.033  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:13.033  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:51:13.033  1014  4019 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:13.043  7591  7613 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@5e8d5a5
08-17 19:51:13.043  1014  1465 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:51:13.043  1861  1861 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 19:51:13.043  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:51:13.043  1014  1477 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 19:51:13.043  1014  1477 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-17 19:51:13.043  7591  7613 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:51:13.043  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:13.043  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:51:13.043  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:51:13.043  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:51:13.043  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:51:13.043  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:51:13.043  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:13.043  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 19:51:13.043  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:51:13.053  7591  7613 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 19:51:13.053  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:51:13.053  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:13.053  7591  7613 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:13.053  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 19:51:13.053  7591  7613 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:13.053  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 19:51:13.053  7591  7613 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:51:13.053  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:51:13.053  1014  4020 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:51:13.053  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 19:51:13.053  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:51:13.053  7591  7613 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 19:51:13.053  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.053  7591  7613 D BluetoothBondStateMachine: make
,08-17 19:51:13.053  1014  4020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:13.053  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:13.053  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:51:13.053  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:51:13.053  7591  7613 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:51:13.063  7591  7617 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:51:13.063  1014  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:13.063  1014  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.063  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
08-17 19:51:13.063  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.063  1014  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.063  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.063  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:51:13.063  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:51:13.063  7591  7613 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:51:13.063  7591  7591 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:51:13.073  7591  7591 D BtGatt.GattService: Received start request. Starting profile...
08-17 19:51:13.073  7591  7591 D BtGatt.GattService: start()
08-17 19:51:13.073  7591  7591 D BtGatt.GattService: start()
08-17 19:51:13.073  7591  7591 I bluedroid: get_profile_interface gatt
,08-17 19:51:13.073  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
08-17 19:51:13.073  7591  7591 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:51:13.073  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:13.073  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:51:13.083  1014  1333 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:13.083  1014  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.083  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.083  1014  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.083  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.083  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:51:13.083  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:51:13.083  7591  7613 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:51:13.083  1014  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:13.083  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.083  7591  7591 D BtGatt.GattService: mStartError = false
08-17 19:51:13.083  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
,08-17 19:51:13.093  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.093  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.093  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.093  7591  7591 D HeadsetService: Received start request. Starting profile...
,08-17 19:51:13.093  7591  7591 D HeadsetService: start()
,08-17 19:51:13.093  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 19:51:13.093  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:51:13.093  7591  7613 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 19:51:13.093  7591  7591 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 19:51:13.093  7591  7591 D HeadsetStateMachine: make
08-17 19:51:13.093  1014  4019 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:13.093  1014  4019 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.093  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.093  1014  4019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:51:13.093  7591  7591 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 19:51:13.093  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-17 19:51:13.103  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:51:13.103  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:51:13.103  7591  7613 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:51:13.103  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:13.103  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.103  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.103  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.103  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.103  1014  1476 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-17 19:51:13.103  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:51:13.103  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:51:13.103  7591  7613 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-17 19:51:13.103  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.113  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.113  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.113  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:51:13.113  1014  1333 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:13.113  1014  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.113  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.113  1014  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.113  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.113  1014  4020 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 19:51:13.113  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.113  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.123  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.123  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:51:13.123  7591  7591 I bluedroid: get_profile_interface handsfree
08-17 19:51:13.123  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:13.123  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:13.123  7591  7613 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:51:13.123  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:13.123  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.123  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.123  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.123  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.133  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:51:13.133  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:51:13.133  7591  7613 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:51:13.133  1014  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:51:13.133  1014  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.133  1014  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.133  1014  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.133  1014  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.133  7591  7591 I DualScoManager: Instantiating Dual Sco Manager
,08-17 19:51:13.133  7591  7591 I DualScoManager: Set HeadsetServiceHelper
,08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:13.143  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:13.143  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:13.143  7591  7591 D BluetoothAtMessage: createCMTIContentObservers
,08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:51:13.143  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:51:13.143  7591  7613 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:51:13.143  7591  7613 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:51:13.143  7591  7613 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:51:13.143  1014  1465 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 19:51:13.143  1014  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:13.143  1014  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:13.143  1014  1465 D SettingsProvider: selectionArgs: false
08-17 19:51:13.143  1014  1465 D SettingsProvider: selectionArgs: 1002
,08-17 19:51:13.143  1014  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:13.143  1014  1465 D SettingsProvider: ret = -1
,08-17 19:51:13.143  7591  7621 D HeadsetStateMachine: Enter Disconnected: -2
08-17 19:51:13.143  7591  7591 D HeadsetService: mStartError = false
08-17 19:51:13.143  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
,08-17 19:51:13.143  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 19:51:13.143  7591  7591 D A2dpService: Received start request. Starting profile...
08-17 19:51:13.143  7591  7591 D A2dpService: start()
,08-17 19:51:13.143  7591  7621 D HeadsetStateMachine: Clear mHeadsetBrsf
08-17 19:51:13.143  7591  7621 D HeadsetStateMachine: map size, before remove : 0
,08-17 19:51:13.153  7591  7591 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:51:13.153  7591  7621 D HeadsetStateMachine: map size, after remove: 0
,08-17 19:51:13.153  7591  7591 I bluedroid: get_profile_interface avrcp
,08-17 19:51:13.153  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:13.153  7591  7591 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:51:13.153  7591  7591 D Avrcp   : Initialize Media Controller
08-17 19:51:13.163  7591  7591 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 19:51:13.163  7591  7591 E Avrcp   : getActiveSessions
08-17 19:51:13.163  7591  7591 D Avrcp   : pick active media Controller
08-17 19:51:13.163  7591  7591 D Avrcp   : Get the active Media Controller 
,08-17 19:51:13.163  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:51:13.173  7591  7591 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:51:13.173  7591  7625 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
08-17 19:51:13.173  7591  7591 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:51:13.173  7591  7591 D A2dpStateMachine: make
,08-17 19:51:13.183  7591  7591 I bluedroid: get_profile_interface a2dp
08-17 19:51:13.183  7591  7627 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 19:51:13.183  7591  7591 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 19:51:13.183  7591  7591 D A2dpService: mStartError = false
08-17 19:51:13.183  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
,08-17 19:51:13.183  7591  7591 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:51:13.183  7591  7625 D BluetoothMediaBrowser: no now playing list
08-17 19:51:13.183  7591  7625 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 19:51:13.193  7591  7626 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:51:13.193  7591  7591 D HidService: Received start request. Starting profile...
,08-17 19:51:13.193  7591  7591 D HidService: start()
08-17 19:51:13.193  7591  7591 I bluedroid: get_profile_interface hidhost
08-17 19:51:13.193  7591  7591 D HidService: setHidService(): set to: null
,08-17 19:51:13.193  7591  7591 D HidService: mStartError = false
08-17 19:51:13.193  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
,08-17 19:51:13.193  7591  7591 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 19:51:13.193  7591  7591 D HealthService: Received start request. Starting profile...
08-17 19:51:13.193  7591  7591 D HealthService: start()
,08-17 19:51:13.193  7591  7591 I bluedroid: get_profile_interface health
,08-17 19:51:13.193  7591  7591 D HealthService: mStartError = false
08-17 19:51:13.193  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
,08-17 19:51:13.193  7591  7591 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 19:51:13.193  1417  6968 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:51:13.203  1417  1417 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 19:51:13.203  1417  1417 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:51:13.203  1417  6968 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 19:51:13.203  7591  7591 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:51:13.203  7591  7591 D PanService: Received start request. Starting profile...
,08-17 19:51:13.203  7591  7591 D PanService: start()
08-17 19:51:13.203  7591  7591 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 19:51:13.203  7591  7591 I bluedroid: get_profile_interface pan
,08-17 19:51:13.203  7591  7591 D PanService: mStartError = false
,08-17 19:51:13.203  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
08-17 19:51:13.203  7591  7591 D HeadsetStateMachine: Proxy object connected
,08-17 19:51:13.203  7591  7591 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-17 19:51:13.203  7591  7621 D HeadsetStateMachine: Disconnected process message: 11,
,08-17 19:51:13.213  7591  7591 D BluetoothMapService: Received start request. Starting profile...
,08-17 19:51:13.213  7591  7591 D BluetoothMapService: start()
,08-17 19:51:13.213  7591  7591 D BluetoothMapService: mStartError = false,
08-17 19:51:13.213  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
08-17 19:51:13.213  7591  7591 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:51:13.213  7591  7621 D HeadsetStateMachine: Disconnected process message: 18
08-17 19:51:13.213  7591  7591 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-17 19:51:13.213  7591  7591 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 19:51:13.213  7591  7591 D SapService: Received start request. Starting profile...
08-17 19:51:13.213  7591  7591 D SapService: start()
08-17 19:51:13.213  7591  7591 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:51:13.213  7591  7591 I bluedroid: get_profile_interface sap
08-17 19:51:13.213  7591  7591 D SapService: mStartError = false
08-17 19:51:13.213  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
08-17 19:51:13.213  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-17 19:51:13.213  7591  7591 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:51:13.213  7591  7591 D BluetoothA2dp: Proxy object connected
08-17 19:51:13.213  7591  7591 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 19:51:13.213  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:51:13.213  7591  7621 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:51:13.213  7591  7621 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:51:13.213  7591  7621 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:51:13.223  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 19:51:13.223  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 19:51:13.223  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:51:13.243  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 19:51:13.243  7591  7591 E BluetoothAdapterService(502980631): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:51:13.243  7591  7613 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-17 19:51:13.243  7591  7613 I bluedroid: enable
,08-17 19:51:13.243  7591  7613 I bt_hci_bdroid: init
,08-17 19:51:13.243  7591  7613 I bt_vendor: bt-vendor : init
,08-17 19:51:13.243  7591  7613 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 19:51:13.243  7591  7613 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 19:51:13.243  7591  7613 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-17 19:51:13.253  7591  7631 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 19:51:13.253  7591  7613 D bt_userial_mct: userial_init
08-17 19:51:13.253  7591  7613 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 19:51:13.253  7591  7613 I bt_vendor: Starting hciattach daemon
08-17 19:51:13.253  7591  7613 I bt_vendor: try to set false
,08-17 19:51:13.253  7591  7613 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-17 19:51:13.253  7591  7613 I bt_vendor: Starting hciattach daemon
08-17 19:51:13.253  7591  7613 I bt_vendor: try to set true
,08-17 19:51:13.263  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 19:51:13.313  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 19:51:13.323  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:51:13.333  7644  7644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:51:13.343  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 19:51:13.353  7646  7646 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:51:13.363  7647  7647 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 19:51:13.623  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-17 19:51:13.633  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:51:13.663  7591  7613 I bt_vendor: bluetooth satus is on
,08-17 19:51:13.663  7591  7633 D bt_userial_mct: userial_open(port:0)
08-17 19:51:13.663  7591  7633 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 19:51:13.663  7591  7633 I bt_vendor: Done intiailizing UART,
,08-17 19:51:13.663  7591  7633 I bt_vendor: Done intiailizing UART
08-17 19:51:13.663  7591  7633 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 19:51:13.663  7591  7633 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 19:51:13.673  7591  7653 D bt_userial_mct: Entering userial_read_thread()
,08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_HCI,
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_PAN,
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_BTIF,
08-17 19:51:13.673  7591  7631 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 19:51:13.743   287   287 E SMD     : DCD OFF
,08-17 19:51:13.763  7591  7631 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 19:51:13.773  7591  7631 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41e8ed1 
,08-17 19:51:13.773  7591  7631 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41e8ed1 
,08-17 19:51:13.783  7591  7616 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 19:51:13.793  7591  7616 E bt-btif : Calling BTA_HhEnable
,08-17 19:51:13.793  7591  7616 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 19:51:13.793  7591  7616 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 19:51:13.793  7591  7616 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:51:13.793  7591  7616 I bluedroid: getModelRssiValues
08-17 19:51:13.793  7591  7616 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-17 19:51:13.793  7591  7616 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:51:13.803  1014  1014 D SettingsProvider: name = bluetooth_name
,08-17 19:51:13.803  7591  7616 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 19:51:13.803  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:13.803  7591  7616 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:51:13.813  7591  7616 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:51:13.813  7591  7616 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:51:13.813  7591  7616 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-17 19:51:13.813  7591  7616 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-17 19:51:13.813  7591  7616 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 19:51:13.813  7591  7616 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-17 19:51:13.813  7591  7616 E bt-btif : btif_sock_init: !vhci_init
08-17 19:51:13.813  7591  7616 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-17 19:51:13.813  7591  7616 D IOP_DB_BT: db_open: db_open : handle 3028430864l, read 13894 bytes onto local cache
08-17 19:51:13.813  7591  7616 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-17 19:51:13.813  7591  7616 D IOP_DB_BT: db_query: result 1
,08-17 19:51:13.813  7591  7616 I         : iop_db_open: iop_db_open status 0
,08-17 19:51:13.813  7591  7616 D bte_conf: Device ID record 1 : primary
08-17 19:51:13.813  7591  7616 D bte_conf:   vendorId            = 0075
08-17 19:51:13.813  7591  7616 D bte_conf:   vendorIdSource      = 0001
08-17 19:51:13.813  7591  7616 D bte_conf:   product             = 0100
08-17 19:51:13.813  7591  7616 D bte_conf:   version             = 0200
08-17 19:51:13.813  7591  7616 D bte_conf:   clientExecutableURL = 
08-17 19:51:13.813  7591  7616 D bte_conf:   serviceDescription  = 
08-17 19:51:13.813  7591  7616 D bte_conf:   documentationURL    = 
08-17 19:51:13.813  7591  7616 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 19:51:13.813  7591  7653 E bt_mct  : hci lib postload completed
,08-17 19:51:13.813  7591  7616 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:51:13.813  7591  7613 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 19:51:13.813  7591  7613 D BluetoothAdapterProperties: ScanMode =  20
,08-17 19:51:13.823  7591  7613 D BluetoothAdapterProperties: State =  11
,08-17 19:51:13.823  1014  1333 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:51:13.823  7591  7613 D BluetoothAdapterProperties: Setting state to 12
,08-17 19:51:13.823  7591  7613 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:51:13.823  7591  7616 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:51:13.823  7591  7616 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:51:13.823  7591  7616 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:51:13.833  1014  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-17 19:51:13.833  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:13.833  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:13.833  1014  1027 D SettingsProvider: selectionArgs: false
08-17 19:51:13.833  1014  1027 D SettingsProvider: selectionArgs: 1002
08-17 19:51:13.833  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:13.833  1014  1027 D SettingsProvider: ret = -1
,08-17 19:51:13.833  7591  7613 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:51:13.833  7591  7613 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 19:51:13.833  1014  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:13.833  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.833  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.843  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:51:13.843  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:13.843  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:13.843  7591  7613 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:51:13.843  7591  7613 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-17 19:51:13.843  7591  7613 D BluetoothAdapterService: starting service from this receiver
,08-17 19:51:13.853  1014  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:13.853  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.853  1305  7290 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:51:13.853  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.853  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.853  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.853  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-17 19:51:13.863  7591  7613 I BluetoothAdapterState: Entering On State from state = 11,
,08-17 19:51:13.863  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-17 19:51:13.863  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.863  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.863  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.863  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:13.863  1177  1848 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:13.863  1177  1848 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:13.863  7591  7591 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 19:51:13.863  2035  2211 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:13.863  2035  2211 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:13.873  1449  1485 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.873  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:51:13.873  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:13.873  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.873  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.873  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.873  1449  1485 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:13.873  1417  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.873  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:51:13.873  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:13.873  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.883  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.883  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.883  1417  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:13.883  1305  1316 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:51:13.883  7591  7591 I BluetoothPbapService: Handler(): got msg=1
,08-17 19:51:13.883  1305  1305 D BluetoothInputDevice: Proxy object connected
08-17 19:51:13.883  1305  1305 D HidProfile: Bluetooth service connected
08-17 19:51:13.883  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 19:51:13.883  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.883  1014  1476 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:51:13.883  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.883  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.883  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.883  7502  7517 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:13.883  7502  7517 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:13.893  1305  7561 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.893  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:51:13.893  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:13.893  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.893  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.893  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 19:51:13.893  1305  7561 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:13.893  1305  1305 D HeadsetProfile: Bluetooth service connected
,08-17 19:51:13.893  1305  1313 D BluetoothPan: Binding service...
,08-17 19:51:13.893  7591  7658 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 19:51:13.893  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:51:13.893  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.893  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.893  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.893  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.893  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:51:13.893  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.893  7591  7658 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:51:13.893  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:51:13.893  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:51:13.903  7591  7658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:51:13.903  1014  1014 D BluetoothA2dp: Proxy object connected
08-17 19:51:13.903  1305  1305 D BluetoothMap: Proxy object connected
08-17 19:51:13.903  1305  1305 D MapProfile: Bluetooth service connected
08-17 19:51:13.903  1305  1305 D BluetoothMap: getConnectedDevices()
,08-17 19:51:13.903  1305  1316 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 19:51:13.903  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-17 19:51:13.903  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.903  1305  1305 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:51:13.903  7591  7658 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-17 19:51:13.903  7591  7658 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:51:13.903  7591  7658 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:51:13.903  7591  7658 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e1cb839
08-17 19:51:13.903  7591  7658 D BluetoothSocket: channel: 19
08-17 19:51:13.903  7591  7658 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-17 19:51:13.903  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.903  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.903  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.903  7591  7657 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:13.903  1305  1305 D PanProfile: Bluetooth service connected
08-17 19:51:13.903  1449  5203 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:13.903  1449  5203 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:13.903  1305  1313 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:13.903  1305  1313 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.903  1305  1305 D BluetoothPbap: Proxy object connected
,08-17 19:51:13.903  1305  1305 D PbapServerProfile: Bluetooth service connected
,08-17 19:51:13.903  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:51:13.903  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:51:13.913  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.913  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.913  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.913  7591  7657 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:13.913  7591  7657 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:51:13.913  1305  1305 D BluetoothA2dp: Proxy object connected
08-17 19:51:13.913  1305  1305 D A2dpProfile: Bluetooth service connected
08-17 19:51:13.913  1305  7290 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:13.913  1305  7290 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:51:13.913  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:13.913  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:51:13.913  1014  1044 D BluetoothPan: Binding service...
,08-17 19:51:13.913  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:51:13.913  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 19:51:13.913  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:51:13.913  6762  6770 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:51:13.913  6762  6770 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:13.913  1417  6968 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.913  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:51:13.913  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:13.913  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.913  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.913  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.913  1417  6968 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:13.913  1417  1431 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:51:13.913  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:51:13.923  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:13.923  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.923  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.923  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.923  1417  1431 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:51:13.923  1305  7561 D Bluetoothsap: onBluetoothStateChange: up=true
,08-17 19:51:13.923  1305  7561 D Bluetoothsap: Binding service...
,08-17 19:51:13.923  1305  7561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 19:51:13.923  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-17 19:51:13.923  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.923  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:13.923  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.923  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:13.923  1305  7561 D Bluetoothsap: bindService called to Bluetooth SAP Service,
08-17 19:51:13.923  1305  1305 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 19:51:13.923  1305  1305 D SapProfile: Bluetooth service connected
08-17 19:51:13.923  1305  1305 D Bluetoothsap: getConnectedDevices()
,08-17 19:51:13.933  1432  1448 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:13.933  1432  1448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:51:13.933  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-17 19:51:13.933  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:51:13.933  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:51:13.933  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:51:13.933  1417  6968 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:51:13.933  1417  6968 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:51:13.933  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 19:51:13.933  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:51:13.933  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:51:13.943  1417  1417 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@19aee3fc, true
,08-17 19:51:13.943  1417  1417 D BluetoothHeadset: registerMessageListener
,08-17 19:51:13.943  1861  1861 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:51:13.943  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:51:13.943  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:13.943  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-17 19:51:13.943  1305  1305 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:13.943  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:13.953  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:13.953  1014  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:51:13.953  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.953  7591  7657 D HeadsetService: registerMessageListener
,08-17 19:51:13.953  7591  7657 D HeadsetService: registerMessageListener
,08-17 19:51:13.953  7591  7621 D HeadsetStateMachine: Disconnected process message: 70
08-17 19:51:13.953  7591  7621 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1771fe7e
,08-17 19:51:13.953  1417  1417 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 19:51:13.953  1417  1417 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:51:13.953  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:13.953  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-17 19:51:13.953  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:51:13.953  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.953  1417  1417 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 19:51:13.953  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:13.953  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:51:13.953  1417  1417 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-17 19:51:13.953  1417  1417 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 19:51:13.953  1014  1465 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:13.953  1014  4020 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 19:51:13.963  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:51:13.963  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:13.963  1305  1305 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-17 19:51:13.963  1305  1305 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 19:51:13.963  7591  7621 D HeadsetStateMachine: Disconnected process message: 9
,08-17 19:51:13.963  1305  1305 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:51:13.963  7591  7621 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-17 19:51:13.963  1305  1305 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:13.963  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:13.963  1177  1747 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:51:13.963  7591  7661 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 19:51:13.973   282   670 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-17 19:51:13.973   282   670 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 19:51:13.973   282   670 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:51:13.973   282   670 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:51:13.973   282   670 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 19:51:13.973   282   670 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 19:51:13.973   282   670 V audio_hw_primary: adev_set_parameters: exit
,08-17 19:51:13.973  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:13.973  7591  7621 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 19:51:13.973  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:13.973  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7355269 added. We now have 8 listener(s)
08-17 19:51:13.973  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:13.973  7591  7661 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:51:13.973  7591  7661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:13.983  7591  7661 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-17 19:51:13.983  7591  7661 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:51:13.983  7591  7661 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:51:13.983  7591  7661 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a87efdf
08-17 19:51:13.983  7591  7661 D BluetoothSocket: channel: 5
,08-17 19:51:13.983  1014  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:51:13.983  1014  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:51:13.983  1014  1495 D SecContentProvider2: mCursor = null
,08-17 19:51:13.983  1305  1305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:51:13.983  1014  1477 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:51:13.983  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:51:13.983  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:13.983  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:13.983  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-17 19:51:13.983  1014  1495 D WifiService: setWifiEnabled: false pid=6762, uid=10171
,08-17 19:51:13.983  1014  1495 D SettingsProvider: name = wifi_on
,08-17 19:51:13.993  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:13.993  1305  1305 D DockEventReceiver: finishStartingService: stopping service
08-17 19:51:13.993  1014  1323 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:51:13.993  1014  1323 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:51:13.993  1014  1323 D SecContentProvider2: mCursor = null
,08-17 19:51:13.993  1014  1323 D WifiService: setWifiEnabled: true pid=6762, uid=10171
08-17 19:51:13.993  1014  1323 W ActivityManager: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:51:13.993  1014  1323 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:51:13.993  1014  1323 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6762, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:51:13.993  1014  1323 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:51:13.993  1014  1323 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:51:13.993  1014  1323 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:51:13.993  1014  1323 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:51:13.993  1014  1323 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:51:13.993  1014  1323 D SettingsProvider: name = wifi_on
,08-17 19:51:13.993  1305  1305 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:51:14.003  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:14.003  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:51:14.003  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 19:51:14.013  7591  7591 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
,08-17 19:51:14.013  7591  7591 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:51:14.013  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:51:14.013  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:51:14.013  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:14.013  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:14.013  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:51:14.033  2035  2035 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:14.033  1014  4020 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:51:14.033  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:51:14.033  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:14.033  1014  4020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:14.033  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:14.043  1014  1486 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:51:14.053  2035  7674 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:51:14.053  2035  2035 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:51:14.053  1014  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:51:14.053  7591  7675 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:51:14.053  7591  7675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:14.063  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:14.063  1014  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:14.063  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:14.063  7591  7675 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-17 19:51:14.063  7591  7675 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:51:14.063  7591  7675 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:51:14.063  7591  7675 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aa5aafb
08-17 19:51:14.063  7591  7675 D BluetoothSocket: channel: 12
08-17 19:51:14.063  7591  7675 I BtOppRfcommListener: Accept thread started.
,08-17 19:51:14.073  1014  4019 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:51:14.073  1014  4019 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:14.073  1014  4019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:51:14.073  1014  4019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:51:14.083  2035  7674 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 19:51:14.333  1014  1042 D Tethering: interfaceAdded wlan0
,08-17 19:51:14.343  1014  1129 E Tethering: No numeric data
,08-17 19:51:14.343  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 19:51:14.343  1014  1129 D Tethering: clearTetheredNotification()
,08-17 19:51:14.343  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:14.343  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:51:14.343  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:14.343  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:51:14.343  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:51:14.343  1177  1177 D HotspotTile: updateTetherState():false, false
,08-17 19:51:14.353  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 19:51:14.353  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:14.353  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:14.353  1014  1129 D Tethering: InitialState.processMessage what=4
08-17 19:51:14.353  1014  1122 V NetworkStats: performPollLocked() took 11ms
,08-17 19:51:14.353  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:14.353  1014  1129 E Tethering: No numeric data
08-17 19:51:14.353  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:14.363  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:14.363  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 19:51:14.363  1014  1129 D Tethering: clearTetheredNotification()
,08-17 19:51:14.363  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 19:51:14.363  1177  1177 D HotspotTile: updateTetherState():false, false
,08-17 19:51:14.363  1014  1042 D Tethering: interfaceAdded p2p0
,08-17 19:51:14.363  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 19:51:14.363  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:14.363  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:51:14.363  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:51:14.373  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:51:14.373  1014  1122 V NetworkStats: performPollLocked() took 7ms
,08-17 19:51:14.373  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:14.373  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:51:14.373  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:51:14.383  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:14.383  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:51:14.383  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:14.383   277  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-17 19:51:14.383   277  1013 D SoftapController: Softap fwReload - Ok
08-17 19:51:14.383   277  1013 D CommandListener: Setting iface cfg
08-17 19:51:14.383   277  1013 D CommandListener: Trying to bring down wlan0
08-17 19:51:14.383   277  1013 D CommandListener: Clearing all IP addresses on wlan0
08-17 19:51:14.393  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
08-17 19:51:14.393  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 19:51:14.393  1014  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-17 19:51:14.403  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:14.403  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:14.403  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:14.403  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:51:14.403  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:51:14.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:14.403  1177  1177 D HotspotTile: onReceive : 2, 0
08-17 19:51:14.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:14.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:14.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:14.403  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:14.403  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-17 19:51:14.403  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:14.403  1014  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:51:14.403  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:51:14.403  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:14.403  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:14.403  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:51:14.413  1631  1631 I Hs20UtilService: Starting #19
08-17 19:51:14.413  1631  1717 I Hs20UtilService: Message received 5011
08-17 19:51:14.413  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:51:14.413  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:51:14.413  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:51:14.413  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:51:14.443  7683  7683 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-17 19:51:14.443  7683  7683 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 19:51:14.443  7683  7683 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:51:14.453  7683  7683 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-17 19:51:14.453   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7683
08-17 19:51:14.453   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:51:14.453  7683  7683 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:51:14.453  7683  7683 I wpa_supplicant: ssSupport state is = 1
08-17 19:51:14.453  7683  7683 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 19:51:14.453  7683  7683 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-17 19:51:14.463   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7683
08-17 19:51:14.463   379   379 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-17 19:51:14.613   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-17 19:51:14.623  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-17 19:51:14.663  7683  7683 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 19:51:14.663  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:51:14.673  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-17 19:51:14.673   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7683,
08-17 19:51:14.673   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:51:14.673  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:51:14.673  7683  7683 I wpa_supplicant: ssSupport state is = 1
08-17 19:51:14.673  7683  7683 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 19:51:14.673  7683  7683 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:51:14.673  7683  7683 E wpa_supplicant: SIM READ ERROR
08-17 19:51:14.673  7683  7683 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:51:14.673  7683  7683 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:51:14.673  7683  7683 E wpa_supplicant: SIM READ ERROR
08-17 19:51:14.673  7683  7683 I wpa_supplicant: Blacklist: Clear (all) 
08-17 19:51:14.673  7683  7683 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:51:14.673  7683  7683 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:51:14.673  7683  7683 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:51:14.673  7683  7683 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 19:51:14.673  7683  7683 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:51:14.673  7683  7683 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:51:14.673  7683  7683 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 19:51:14.683  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:51:14.683  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:14.683  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:51:14.773  7683  7683 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 19:51:14.943  7683  7683 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 19:51:14.943  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:51:14.953  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 19:51:14.953   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7683,
08-17 19:51:14.953   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-17 19:51:14.953  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:51:14.953  7683  7683 I wpa_supplicant: ssSupport state is = 1,
08-17 19:51:14.963  7683  7683 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:51:14.963  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:51:14.973  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 19:51:14.973   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7683
08-17 19:51:14.973   379   379 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:51:14.973  7683  7683 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-17 19:51:14.973  7683  7683 I wpa_supplicant: ssSupport state is = 1
08-17 19:51:14.973  7683  7683 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:51:14.973  7683  7683 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:51:14.973  7683  7683 E wpa_supplicant: SIM READ ERROR,
08-17 19:51:14.973  7683  7683 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:51:14.973  7683  7683 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:51:14.973  7683  7683 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 19:51:14.973  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:51:14.973  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:51:14.983  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:51:14.983  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:51:14.983  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:51:14.983  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:51:15.063  7683  7683 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-17 19:51:15.063  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:51:15.133  1014  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:51:15.133  1014  1477 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:51:15.133  7683  7683 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-17 19:51:15.133  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 19:51:15.133  7683  7683 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:51:15.133  1014  1477 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-17 19:51:15.133  1014  1477 D BatteryService: stay LED for fully charged
,08-17 19:51:15.133  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:51:15.143  1014  1014 I MotionRecognitionService: Plugged
,08-17 19:51:15.143  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:51:15.143  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:51:15.143  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:51:15.143  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:51:15.153  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:51:15.163  7591  7591 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:51:15.163  7591  7621 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:51:15.173  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-17 19:51:15.173  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 19:51:15.173  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 19:51:15.353  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:51:15.353  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:51:15.353  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:51:15.403  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-17 19:51:15.403  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-17 19:51:15.403  7683  7683 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 19:51:15.403  7683  7683 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:51:15.403  7683  7683 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:51:15.403  7683  7683 E wpa_supplicant: SIM READ ERROR
08-17 19:51:15.403  7683  7683 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:51:15.433  7683  7683 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-17 19:51:15.443  7683  7683 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:51:15.443  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:51:15.443  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:51:15.443  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:15.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:15.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:15.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:15.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:15.453  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:51:15.453  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-17 19:51:15.453  1177  1747 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:51:15.453  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:51:15.453  1305  1305 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:51:15.453  1177  1177 D HotspotTile: onReceive : 3, 0
,08-17 19:51:15.463  1014  1125 E WifiConfigStore: Not a HS20
,08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:15.463  6762  6762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:15.463  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:51:15.463  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 19:51:15.463  6762  6762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:15.463  1014  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:51:15.463  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:51:15.463  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 19:51:15.463  7683  7683 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:51:15.463  7683  7683 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 19:51:15.463  7683  7683 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:51:15.463  7683  7683 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:51:15.463  7683  7683 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 19:51:15.463  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:51:15.463  7683  7683 I wpa_supplicant: First Scan Start
08-17 19:51:15.463  7683  7683 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 19:51:15.463  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:15.463  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:15.463  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:51:15.473  1631  1631 I Hs20UtilService: Starting #20
,08-17 19:51:15.473  1631  1717 I Hs20UtilService: Message received 5011
08-17 19:51:15.473  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-17 19:51:15.473  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 19:51:15.473  1014  1125 I WifiNative-HAL: startHal
08-17 19:51:15.473  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d6f888c
08-17 19:51:15.473  1014  1125 I WifiNative-HAL: Could not start hal
08-17 19:51:15.473  7009  7009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:51:15.473  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:51:15.473  7033  7033 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:51:15.473  7033  7033 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:51:15.473  7033  7033 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:51:15.483  1014  1125 E WifiNative-wlan0: do suspend true
,08-17 19:51:15.483  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-17 19:51:15.483  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 19:51:15.483   277  1013 D CommandListener: Setting iface cfg
08-17 19:51:15.483   277  1013 D CommandListener: Trying to bring up p2p0
,08-17 19:51:15.483  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:51:15.483  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:51:15.483  1014  1125 E WifiNative-wlan0: invaild command id : 215
,08-17 19:51:15.483  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 19:51:15.483  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 19:51:15.483  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:51:15.483  1014  1148 I WifiNative-HAL: startHal
08-17 19:51:15.483  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ecb49bc
08-17 19:51:15.483  1014  1148 I WifiNative-HAL: Could not start hal
08-17 19:51:15.483  1014  1148 E WifiScanningService: could not start HAL
08-17 19:51:15.483  1014  1124 D WifiP2pService: P2pEnablingState
08-17 19:51:15.483  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:51:15.483  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:51:15.483  1014  1125 E WifiNative-wlan0: invaild command id : 215
08-17 19:51:15.483  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-17 19:51:15.483  1014  1124 D WifiP2pService: P2p socket connection successful
08-17 19:51:15.483  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-17 19:51:15.483  1014  1124 D WifiP2pService: P2pEnabledState
,08-17 19:51:15.483  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:51:15.483  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 19:51:15.483  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:51:15.493  7683  7683 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:51:15.493  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:51:15.493  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-17 19:51:15.493  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:51:15.493  7683  7683 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 19:51:15.493  1014  1045 D WifiDisplayController: disconnect
,08-17 19:51:15.493  1014  1045 D WifiDisplayController: updateConnection
08-17 19:51:15.493  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-17 19:51:15.493  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:51:15.493  7683  7683 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-17 19:51:15.493  1014  1125 E WifiStateMachine: Failed to set frequency band 0
,08-17 19:51:15.493  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:15.493  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:15.503  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:51:15.503  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:51:15.503  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:51:15.503  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:15.503  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:15.503  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:51:15.503  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:51:15.503  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:51:15.503  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:51:15.503  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 19:51:15.503  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-17 19:51:15.503  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:51:15.513  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:51:15.513  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:51:15.513  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  secondary type: null
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  wps: 0
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  grpcapab: 0
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  devcapab: 0
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  status: 3
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  wfdInfo: null
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-17 19:51:15.513  1014  1045 D WifiDisplayController:  SConnectInfo : null
08-17 19:51:15.513  1014  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-17 19:51:15.513  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:51:15.513  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:51:15.513  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:51:15.513  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:51:15.513  7373  7373 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:51:15.523  7373  7373 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:51:15.523  7373  7373 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:51:15.523  7388  7388 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:51:15.533  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 19:51:15.533  1014  1124 D WifiP2pService: InactiveState
,08-17 19:51:15.533  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:51:15.533  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:51:15.533  7683  7683 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-17 19:51:15.533  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:51:15.533  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:16.013  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:16.013  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:16.023  6762  6828 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 19:51:16.023  6762  6828 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 19:51:16.023  6762  6828 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3afdfd07 Bundle[{}]
,08-17 19:51:16.033  6762  6828 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 19:51:16.033  6762  6828 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 19:51:16.033  6762  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 19:51:16.033  6762  6828 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 19:51:16.033  6762  6828 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 19:51:16.033  6762  6828 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:51:16.043  6762  6828 I System.out: Running OutgoingSocketThread
,08-17 19:51:16.043  6762  7692 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1350)
,08-17 19:51:16.043  6762  7692 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44084
,08-17 19:51:16.043  6762  7692 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 19:51:16.673  7683  7683 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-17 19:51:16.673  7683  7683 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:51:16.673  7683  7683 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-17 19:51:16.673  7683  7683 I wpa_supplicant: Trying to associate with  'G700'
08-17 19:51:16.673  7683  7683 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-17 19:51:16.673  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-17 19:51:16.673  1014  7690 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 19:51:16.693  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:16.693  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:16.743   287   287 E SMD     : DCD OFF,
,08-17 19:51:16.793  7683  7683 E wpa_supplicant: Cmd 35605 not handled
,08-17 19:51:16.803  7683  7683 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 19:51:16.803  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:51:16.803  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:16.803  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:51:16.803  7683  7683 I wpa_supplicant: Associated with F4.99.3E
08-17 19:51:16.803  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:51:16.803  7683  7683 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:51:16.803  7683  7683 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 19:51:16.803  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:51:16.803  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:51:16.803  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:16.803  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:51:16.803  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-17 19:51:16.803  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-17 19:51:16.803  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:51:16.803  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:51:16.803  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:51:16.813  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 19:51:16.803  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:51:16.813  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:51:16.803  1014  1129 E Tethering: No numeric data
08-17 19:51:16.813  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:51:16.813  1014  1129 D Tethering: clearTetheredNotification()
08-17 19:51:16.813  7683  7683 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:51:16.813  7683  7683 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-17 19:51:16.813  7683  7683 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 19:51:16.813  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:51:16.813  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-17 19:51:16.813  1177  1177 D HotspotTile: updateTetherState():false, false
08-17 19:51:16.813  7683  7683 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:51:16.813  7683  7683 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 19:51:16.813  7683  7683 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 19:51:16.813  7683  7683 I wpa_supplicant: Blacklist: Clear (temp) 
,08-17 19:51:16.813  7683  7683 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 19:51:16.813  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:51:16.813  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:51:16.813  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:16.823  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:16.823  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:51:16.823  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:16.823  1014  1125 D SecContentProvider2: mCursor = null
08-17 19:51:16.823  1014  1122 V NetworkStats: performPollLocked() took 7ms
08-17 19:51:16.823  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:16.823  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:16.823  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:16.833  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 19:51:16.833  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:51:16.833  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:16.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:16.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:16.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:16.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:16.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:16.843  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 19:51:16.843  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 19:51:16.843  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:51:16.843  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:51:16.843  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:16.843  1014  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:51:16.843  1014  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:51:16.843  1014  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:16.853  1014  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:16.853  1014  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:51:16.853  1631  1631 I Hs20UtilService: Starting #21
,08-17 19:51:16.853  1631  1717 I Hs20UtilService: Message received 5007
,08-17 19:51:16.853  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:51:16.853  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:51:16.853  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:51:16.853  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:51:16.853  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:51:16.853  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:51:16.853  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:51:16.863  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:16.873   277  1013 D CommandListener: Setting iface cfg
,08-17 19:51:16.873  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-17 19:51:16.873  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:51:16.873  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:16.873  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 19:51:16.873  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:16.883  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:51:16.883  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:51:16.883  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:16.883  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:16.883  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:16.883  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:16.893  1014  1125 E WifiNative-wlan0: do suspend false
,08-17 19:51:16.893  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:51:16.893  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:51:16.903  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:51:16.903  1014  1125 D SecContentProvider2: mCursor = null
,08-17 19:51:17.043  6762  6828 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1351)
,08-17 19:51:17.043  6762  6828 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1351)
,08-17 19:51:17.043  6762  6828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1356)
,08-17 19:51:17.053  6762  6828 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 19:51:17.053  6762  6828 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1357)
,08-17 19:51:17.053  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:17.053  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370644ee added. We now have 2 listener(s)
,08-17 19:51:17.063  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:51:17.063  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:17.063  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:51:17.063  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:17.063  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c00d8f added. We now have 9 listener(s)
,08-17 19:51:17.063  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:17.063  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:17.063  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:17.073  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:17.073  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:17.073  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:51:17.083  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:17.083  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1147ac25 added. We now have 3 listener(s)
,08-17 19:51:17.083  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.083  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.083  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:51:17.083  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:17.083  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:51:17.083  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:17.083  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b95c1fa added. We now have 10 listener(s)
,08-17 19:51:17.083  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:17.093  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:51:17.093  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:17.093  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:51:17.093  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:17.093  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:17.093  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:17.093  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:51:17.093  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370644ee removed from the list
08-17 19:51:17.093  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.093  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c00d8f removed from the list
08-17 19:51:17.093  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:51:17.093  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.093  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:17.093  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.093  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:17.093  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:17.093  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.093  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c00d8f not in the list
08-17 19:51:17.093  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:17.093  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.103  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:17.103  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.103  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.103  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b95c1fa removed from the list
08-17 19:51:17.103  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:17.103  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.103  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.103  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.103  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1147ac25 removed from the list
,08-17 19:51:17.103  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:17.103  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139f3ab added. We now have 2 listener(s)
,08-17 19:51:17.103  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-17 19:51:17.103  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.103  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:17.103  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.103  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2d0a08 added. We now have 9 listener(s),
08-17 19:51:17.103  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:17.103  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:17.113  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:17.113  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:17.113  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:17.113  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:51:17.123  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:17.123  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6e03c6 added. We now have 3 listener(s)
08-17 19:51:17.123  7696  7696 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 19:51:17.123  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.123  7696  7696 I dhcpcd  : version 5.5.6 starting
,08-17 19:51:17.123  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.123  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:51:17.123  7696  7696 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 19:51:17.123  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.123  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:17.123  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.123  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b221f87 added. We now have 10 listener(s),
08-17 19:51:17.123  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:17.123  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:17.123  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:51:17.123  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:51:17.123  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:51:17.123  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:51:17.133  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:51:17.133  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:51:17.143  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:51:17.143  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:51:17.143  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:51:17.143  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:51:17.143  7591  7659 D BtGatt.GattService: registerClient() - UUID=b786e918-157d-457b-a17e-754808e14197
,08-17 19:51:17.183  7696  7696 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-17 19:51:17.183  7696  7696 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 19:51:17.183  7696  7696 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 19:51:17.183  7696  7696 I dhcpcd  : bssid match,
08-17 19:51:17.183  7696  7696 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-17 19:51:17.183  7591  7616 D BtGatt.GattService: onClientRegistered() - UUID=b786e918-157d-457b-a17e-754808e14197, clientIf=6,
,08-17 19:51:17.183  6762  6770 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:51:17.183  7591  7660 D BtGatt.GattService: start scan with filters
,08-17 19:51:17.193  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:51:17.193  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:51:17.193  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:51:17.193  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:51:17.193  7591  7620 D BtGatt.ScanManager: handling starting scan
,08-17 19:51:17.193  7591  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dfae017
,08-17 19:51:17.193  7591  7616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:51:17.193  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:51:17.193  7591  7620 D BtGatt.ScanManager: allow scan with filters
08-17 19:51:17.193  7591  7620 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:51:17.193  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:51:17.193  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:51:17.193  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:51:17.193  7591  7620 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-17 19:51:17.193  7591  7616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:51:17.193  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:51:17.203  7591  7620 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:51:17.203  7591  7620 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:51:17.203  7591  7616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:51:17.203  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:51:17.203  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.203  6762  6828 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:51:17.203  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:17.213  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:51:17.213  7591  7616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:51:17.213  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:51:17.213  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.213  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:51:17.213  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 19:51:17.213  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:51:17.213  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:51:17.213  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:51:17.213  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:51:17.213  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:51:17.213  7591  7657 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:51:17.213  7591  7662 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:51:17.213  7591  7620 D BtGatt.ScanManager: filter size is 1
08-17 19:51:17.213  7591  7620 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 19:51:17.213  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:51:17.213  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:51:17.213  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:51:17.213  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:51:17.213  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:51:17.213  7591  7616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:51:17.213  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.223  7591  7620 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:51:17.223  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:51:17.223  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:51:17.223  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:51:17.223  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:51:17.223  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:51:17.223  7591  7616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:51:17.223  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.223  7591  7620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:51:17.233  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:51:17.233  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:51:17.233  7591  7616 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:51:17.233  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.233  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:51:17.233  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:51:17.233  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:17.233  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:51:17.233  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:17.233  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:17.233  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:17.233  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:51:17.243  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139f3ab removed from the list
,08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.243  7696  7696 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-17 19:51:17.243  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2d0a08 removed from the list
,08-17 19:51:17.243  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:51:17.243  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.243  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:17.243  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.243  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2d0a08 not in the list
08-17 19:51:17.243  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:17.243  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.243  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b221f87 removed from the list
08-17 19:51:17.243  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:17.253  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:17.253  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6e03c6 removed from the list
,08-17 19:51:17.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:17.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10772d23 added. We now have 2 listener(s)
,08-17 19:51:17.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:51:17.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:17.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.253  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e911220 added. We now have 9 listener(s)
08-17 19:51:17.253  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:17.253  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:17.263  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:17.263  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:17.263  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:17.263  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:51:17.263  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:17.263  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a83c59e added. We now have 3 listener(s)
,08-17 19:51:17.263  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.273  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.273  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:51:17.273  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.273  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:51:17.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2685787f added. We now have 10 listener(s)
08-17 19:51:17.273  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:17.273  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:51:17.273  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:17.273  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:51:17.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:51:17.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:17.273  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:51:17.273  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:51:17.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:51:17.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:51:17.283  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:51:17.283  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:51:17.283  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:51:17.283  7591  7660 D BtGatt.GattService: registerClient() - UUID=1f3301c0-c974-49a4-ab8b-10e292bc70d8
,08-17 19:51:17.333  7591  7616 D BtGatt.GattService: onClientRegistered() - UUID=1f3301c0-c974-49a4-ab8b-10e292bc70d8, clientIf=6
,08-17 19:51:17.333  6762  6770 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 19:51:17.333  7591  7605 D BtGatt.GattService: start scan with filters
,08-17 19:51:17.333  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:51:17.333  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:51:17.333  7591  7620 D BtGatt.ScanManager: handling starting scan
08-17 19:51:17.333  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-17 19:51:17.333  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:51:17.333  7591  7616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:51:17.333  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:51:17.333  7591  7620 D BtGatt.ScanManager: allow scan with filters
08-17 19:51:17.333  7591  7620 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
08-17 19:51:17.333  7591  7620 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-17 19:51:17.333  7591  7616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 19:51:17.333  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.333  7591  7620 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:51:17.333  7591  7620 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:51:17.343  7591  7616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:51:17.343  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.343  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:17.343  7591  7616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:51:17.343  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.343  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:51:17.343  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:51:17.353  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:51:17.353  6762  6828 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 19:51:17.353  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:51:17.353  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:51:17.353  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:17.353  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.353  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.353  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10772d23 removed from the list
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:17.353  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e911220 removed from the list
08-17 19:51:17.353  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:51:17.353  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:17.353  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.353  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:51:17.353  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.353  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.353  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e911220 not in the list
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:51:17.353  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:51:17.353  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:51:17.353  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:51:17.363  7591  7657 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:51:17.363  7591  7620 D BtGatt.ScanManager: filter size is 1
08-17 19:51:17.363  7591  7620 D BtGatt.ScanManager: delete FilterIndex - 4
08-17 19:51:17.363  7591  7599 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:51:17.363  7591  7616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:51:17.363  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:51:17.363  7591  7620 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:51:17.363  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:51:17.363  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:51:17.363  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:51:17.363  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:51:17.363  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:51:17.363  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:51:17.363  7591  7616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:51:17.363  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.363  7591  7620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:51:17.373  7696  7696 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-17 19:51:17.373  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:51:17.373  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:51:17.373  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:51:17.373  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.373  7591  7616 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:51:17.373  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.373  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:17.373  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.373  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:17.373  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2685787f removed from the list
08-17 19:51:17.373  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:17.373  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.373  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:17.373  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.373  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a83c59e removed from the list
,08-17 19:51:17.373  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:17.373  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1031d9b added. We now have 2 listener(s)
08-17 19:51:17.373  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:51:17.373  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:51:17.373  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:51:17.383  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:51:17.383  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.383  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:17.383  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.383  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@223b0538 added. We now have 9 listener(s)
08-17 19:51:17.383  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:17.383  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:51:17.383  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:17.393  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:17.403  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:17.403  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:51:17.403  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:17.403  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca4ea76 added. We now have 3 listener(s)
,08-17 19:51:17.403  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.403  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:17.403  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:51:17.403  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.403  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:17.403  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.403  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebf877 added. We now have 10 listener(s)
08-17 19:51:17.403  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:17.413  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:17.413  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:51:17.413  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:51:17.413  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:51:17.413  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:51:17.423  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:51:17.443  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-17 19:51:17.453  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:51:17.463  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-17 19:51:17.463  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:51:17.463  6762  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:51:17.463  7591  7659 D BtGatt.GattService: registerClient() - UUID=74950e82-9631-4a1c-a97c-385d49b9bea1
,08-17 19:51:17.513  7591  7616 D BtGatt.GattService: onClientRegistered() - UUID=74950e82-9631-4a1c-a97c-385d49b9bea1, clientIf=6
,08-17 19:51:17.513  6762  6777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-17 19:51:17.513  7591  7660 D BtGatt.GattService: start scan with filters
08-17 19:51:17.513  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:51:17.513  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:51:17.513  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:51:17.513  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:51:17.513  7591  7620 D BtGatt.ScanManager: handling starting scan
08-17 19:51:17.513  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:17.513  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:51:17.513  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:17.513  7591  7616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:51:17.513  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-17 19:51:17.513  7591  7620 D BtGatt.ScanManager: allow scan with filters
08-17 19:51:17.513  7591  7620 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:51:17.513  7591  7620 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 19:51:17.523  7591  7616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 19:51:17.523  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.523  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:51:17.523  7591  7620 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:51:17.523  7591  7620 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:51:17.523  7591  7616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:51:17.523  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.533  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:51:17.533  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:51:17.533  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:17.533  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.533  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1031d9b removed from the list
08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:17.533  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@223b0538 removed from the list
08-17 19:51:17.533  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:51:17.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:17.533  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:51:17.533  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:17.533  7591  7616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:51:17.533  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:17.533  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@223b0538 not in the list
08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:51:17.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:51:17.533  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:51:17.533  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:51:17.533  7591  7659 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:51:17.543  7591  7620 D BtGatt.ScanManager: filter size is 1
08-17 19:51:17.543  7591  7620 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 19:51:17.543  7591  7616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 19:51:17.543  7591  7605 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:51:17.543  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.543  7591  7620 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:51:17.543  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:51:17.543  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 19:51:17.543  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:51:17.543  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:51:17.543  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:51:17.543  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:51:17.543  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:51:17.543  6762  6828 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:51:17.543  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:51:17.543  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.543  7591  7616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-17 19:51:17.543  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:51:17.543  7591  7620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:51:17.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-17 19:51:17.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:17.553  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:51:17.553  6762  6762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:51:17.553  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebf877 removed from the list
08-17 19:51:17.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:17.553  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:17.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:17.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.553  6762  6762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:51:17.553  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca4ea76 removed from the list,
08-17 19:51:17.553  7591  7616 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:51:17.553  7591  7616 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:51:17.553  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:17.553  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91da513 added. We now have 2 listener(s)
,08-17 19:51:17.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 19:51:17.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:17.553  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.553  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@299d4350 added. We now have 9 listener(s)
08-17 19:51:17.553  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:17.553  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:17.563  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:17.563  6762  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:17.563  6762  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-17 19:51:17.563  6762  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:51:17.563  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:17.573  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@387ad24e added. We now have 3 listener(s)
,08-17 19:51:17.573  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 19:51:17.573  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 19:51:17.573  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:17.573  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:17.573  6762  6762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:17.573  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:17.573  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb37f6f added. We now have 10 listener(s)
08-17 19:51:17.573  6762  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:17.573  6762  6828 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 19:51:17.573  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:51:17.573  6762  6828 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:51:17.573  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:17.573  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 19:51:17.573  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:17.573  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.573  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91da513 removed from the list
08-17 19:51:17.573  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 19:51:17.573  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@299d4350 removed from the list
08-17 19:51:17.573  6762  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:51:17.573  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.573  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.573  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:17.583  6762  6828 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@299d4350 not in the list
08-17 19:51:17.583  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.583  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:17.583  6762  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eb37f6f removed from the list
08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:17.583  6762  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:17.583  6762  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:17.583  6762  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:17.583  6762  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@387ad24e removed from the list
08-17 19:51:17.583  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 19:51:17.583  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 19:51:17.583  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 19:51:17.583  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:17.583  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 19:51:17.583  6762  6828 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:17.583  6762  7727 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1364, name: My test thread name)
,08-17 19:51:17.583  6762  7727 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1364, thread name: My test thread name)
08-17 19:51:17.583  6762  7727 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1364, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:51:17.593  6762  7728 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1366, name: My test thread name)
08-17 19:51:17.593  6762  7728 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1366, thread name: My test thread name)
08-17 19:51:17.593  6762  7728 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1366, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:51:17.593  6762  6828 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 19:51:17.593  6762  6828 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 19:51:17.593  6762  6828 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 19:51:17.593  6762  6828 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 19:51:17.593  6762  6828 D com.test.thalitest.ThaliTestRunner: Total duration: 23342 ms
,08-17 19:51:17.593  6762  6828 I jxcore-log: Total number of executed tests:  80
08-17 19:51:17.593  6762  6828 I jxcore-log: 
08-17 19:51:17.593  6762  6828 I jxcore-log: Number of passed tests:  80
,08-17 19:51:17.593  6762  6828 I jxcore-log: 
08-17 19:51:17.593  6762  6828 I jxcore-log: Number of failed tests:  0
08-17 19:51:17.593  6762  6828 I jxcore-log: 
08-17 19:51:17.593  6762  6828 I jxcore-log: Number of ignored tests:  0
08-17 19:51:17.593  6762  6828 I jxcore-log: 
,08-17 19:51:17.593  6762  6828 I jxcore-log: Total duration:  23342
08-17 19:51:17.593  6762  6828 I jxcore-log: 
08-17 19:51:17.593  6762  6828 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 19:51:17.593  6762  6828 I jxcore-log: 
,08-17 19:51:17.603  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:17.603  6762  6828 I jxcore-log: 
08-17 19:51:17.613  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:17.613  6762  6828 I jxcore-log: 
08-17 19:51:17.613  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:17.613  6762  6828 I jxcore-log: 
08-17 19:51:17.613  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:17.613  6762  6828 I jxcore-log: 
08-17 19:51:17.613  6762  6762 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 19:51:17.613  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:17.613  6762  6828 I jxcore-log: 
08-17 19:51:17.613  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:17.613  6762  6828 I jxcore-log: 
08-17 19:51:17.613  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:17.613  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.623  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.623  6762  6828 I jxcore-log: 
08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
,08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
,08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
,08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-17 19:51:17.633  6762  6828 I jxcore-log: 
08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
,08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-17 19:51:17.633  6762  6828 I jxcore-log: 
08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
,08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
,08-17 19:51:17.633  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:51:17.633  6762  6828 I jxcore-log: 
,08-17 19:51:17.713  1014  1125 E WifiNative-wlan0: do suspend true
,08-17 19:51:17.733  6762  6762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 19:51:17.733  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:51:17.733  6762  6828 I jxcore-log: 
,08-17 19:51:17.743  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:51:17.743  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 19:51:17.743  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-17 19:51:17.743  1014  1125 E WifiStateMachine: VerifyingLinkState enter
,08-17 19:51:17.743  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:17.743  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:17.743  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.743  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.743  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.743  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:17.743  1014  1127 E ConnectivityService: updateNetworkInfo()
,08-17 19:51:17.743  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-17 19:51:17.743  1014  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-17 19:51:17.753  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-17 19:51:17.753  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:51:17.753  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:17.753  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:51:17.753  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.753  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.753  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.753  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 19:51:17.753  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:51:17.753  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 19:51:17.753  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:51:17.763  1014  1472 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:51:17.763  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:51:17.763  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:51:17.763  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:17.763  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:51:17.763  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-17 19:51:17.773  1631  1631 I Hs20UtilService: Starting #22
,08-17 19:51:17.773  1631  1717 I Hs20UtilService: Message received 5007
,08-17 19:51:17.773  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:51:17.773  1305  1305 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:51:17.783  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
08-17 19:51:17.783  1014  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-17 19:51:17.783  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-17 19:51:17.783  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:51:17.783  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 19:51:17.783  1014  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1],
08-17 19:51:17.783  1014  1127 D ConnectivityService: LTETest block dns file not exists
,08-17 19:51:17.793  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:17.793  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:51:17.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:17.793  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:51:17.793  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0,
08-17 19:51:17.793  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,08-17 19:51:17.803  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 19:51:17.803  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 19:51:17.803  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:17.803  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:51:17.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:51:17.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:17.813  1014  1127 V NetworkStats: updateIfacesLocked()
08-17 19:51:17.813  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.813  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:51:17.813  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:17.813  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:51:17.823  1014  4020 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:51:17.823  1014  4020 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:51:17.823  1014  1127 V NetworkStats: performPollLocked() took 14ms
08-17 19:51:17.823  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.823  1014  4020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:17.823  1014  4020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:17.823  1014  4020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:51:17.823  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.823  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:17.823  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:51:17.823  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-17 19:51:17.823  1014  1127 E ConnectivityService: updateNetworkInfo()
08-17 19:51:17.823  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:51:17.823  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.823  1014  1127 V NetworkStats: updateIfacesLocked()
08-17 19:51:17.823  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:51:17.833  1631  1631 I Hs20UtilService: Starting #23
,08-17 19:51:17.833  1631  1717 I Hs20UtilService: Message received 5007
,08-17 19:51:17.833  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:51:17.833  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:17.833  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:51:17.833  1305  1305 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:51:17.833  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:51:17.833  1014  1127 V NetworkStats: performPollLocked() took 5ms
08-17 19:51:17.833  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:51:17.833  1305  1305 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:51:17.833  1305  1305 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:51:17.833  1305  2226 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:51:17.833  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:17.833  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.833  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-17 19:51:17.833  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.833  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 19:51:17.833  1014  7693 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:51:17.833  1014  7693 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-17 19:51:17.833  1014  7693 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:51:17.833  1014  7693 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700",
,08-17 19:51:17.833  1014  7693 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:51:17.843   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:51:17.843   277  1009 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-17 19:51:17.843  1014  1127 D ConnectivityService:    accepting network in place of null
,08-17 19:51:17.843  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 19:51:17.843  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:51:17.843  1449  1449 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 19:51:17.843  1449  1449 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:51:17.843  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 19:51:17.843  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-17 19:51:17.843  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 19:51:17.843  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-17 19:51:17.853  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-17 19:51:17.853  1014  1129 D Tethering: MasterInitialState.processMessage what=3
08-17 19:51:17.853  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.853  1014  1122 V NetworkStats: updateIfacesLocked()
08-17 19:51:17.853  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:51:17.853  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-17 19:51:17.853  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:17.853  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:51:17.853  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 19:51:17.853  1014  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:51:17.853  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-17 19:51:17.853  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:17.853  1014  1122 V NetworkStats: performPollLocked() took 5ms
08-17 19:51:17.853  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:17.853  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:51:17.853  1177  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:51:17.853  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-17 19:51:17.853  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:51:17.853  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:51:17.853  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-17 19:51:17.853  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:51:17.853  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 19:51:17.853  4728  6815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:51:17.853  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:17.863  1631  1631 I Hs20UtilService: Starting #24
,08-17 19:51:17.863  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.863  1631  1717 I Hs20UtilService: Message received 5007
,08-17 19:51:17.863  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.863  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.863  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 19:51:17.863  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.863  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.863  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:17.863  1305  1305 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 19:51:17.863  1305  1305 I NearbySettings: MountReceiver.onReceive - Keep current state
08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:51:17.863  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:17.863  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:17.873  1014  4020 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-17 19:51:17.873  1014  1333 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-17 19:51:17.873  1014  1333 D SecContentProvider2: mCursor = null
,08-17 19:51:17.873  1014  1027 D SecContentProvider2: uri = 15 selection = getToastGravity
08-17 19:51:17.873  1014  1027 D SecContentProvider2: mCursor = null
08-17 19:51:17.873  1014  1495 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
08-17 19:51:17.873  1014  1495 D SecContentProvider2: mCursor = null
08-17 19:51:17.873  1014  4019 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-17 19:51:17.873  1014  4019 D SecContentProvider2: mCursor = null
,08-17 19:51:17.873  6762  6762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 19:51:17.883  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:51:17.883  6762  6828 I jxcore-log: 
,08-17 19:51:17.883  1014  1323 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-17 19:51:17.883  1014  1323 D SecContentProvider2: mCursor = null
,08-17 19:51:17.883  1014  1026 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-17 19:51:17.883  1014  1026 D SecContentProvider2: mCursor = null
,08-17 19:51:17.903   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-17 19:51:17.913  1014  1333 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-17 19:51:17.923  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 19:51:17.923  7729  7729 D AndroidRuntime: 
08-17 19:51:17.923  7729  7729 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 19:51:17.923  1014  7693 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 19:51:17.923  7729  7729 D AndroidRuntime: CheckJNI is OFF,
08-17 19:51:17.923  7729  7729 D AndroidRuntime: readGMSProperty: start
08-17 19:51:17.923  7729  7729 D AndroidRuntime: readGMSProperty: already setted!!
08-17 19:51:17.923  7729  7729 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 19:51:17.923  7729  7729 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 19:51:17.923  7729  7729 D AndroidRuntime: readGMSProperty: end
08-17 19:51:17.923  7729  7729 D AndroidRuntime: addProductProperty: start
,08-17 19:51:18.023  1014  7693 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:51:18 GMT], X-Android-Received-Millis=[1471456278035], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471456278000]}
08-17 19:51:18.023  1014  7693 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 19:51:18.023  1014  7693 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-17 19:51:18.023  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-17 19:51:18.023  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 19:51:18.023  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-17 19:51:18.023  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 19:51:18.033  1177  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:51:18.033  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 19:51:18.033  4728  6815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:51:18.033  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
,08-17 19:51:18.033  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-17 19:51:18.033  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:51:18.033  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-17 19:51:18.033  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:51:18.033  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 19:51:18.033  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-17 19:51:18.033  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 19:51:18.043  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-17 19:51:18.043  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:51:18.043  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-17 19:51:18.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:18.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:18.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:51:18.043  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:51:18.053  6762  6762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:51:18.053  6762  6828 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,08-17 19:51:18.053  6762  6828 I jxcore-log: 
,08-17 19:51:18.063  7729  7729 E AffinityControl: AffinityControl: registerfunction enter
,08-17 19:51:18.093  7729  7729 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 19:51:18.113  1014  1476 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-17 19:51:18.113  1014  1476 D PackageManager: START PACKAGE DELETE: observer{413458386}
08-17 19:51:18.113  1014  1476 D PackageManager: pkg{<packageName>}
08-17 19:51:18.113  1014  1476 D PackageManager: user{0}
08-17 19:51:18.113  1014  1476 D PackageManager: caller{2000}
08-17 19:51:18.113  1014  1476 D PackageManager: flags{2}
08-17 19:51:18.113  1014  1476 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-17 19:51:18.113  1014  1476 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-17 19:51:18.113  1014  1476 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-17 19:51:18.113  1014  1476 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-17 19:51:18.123  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
08-17 19:51:18.123  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-17 19:51:18.123  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-17 19:51:18.123  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
08-17 19:51:18.123  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-17 19:51:18.123  1014  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-17 19:51:18.123  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-17 19:51:18.143  1014  1040 I ActivityManager: Killing 6762:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-17 19:51:18.213  1014  1054 W PackageSettings: Skipping PackageSetting{1cca1f66 com.example.hello/10168} due to missing metadata
,08-17 19:51:18.243  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{2edfa8c5 u0 com.test.thalitest/.MainActivity t3}
,08-17 19:51:18.243  1014  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 19:51:18.253  1014  1095 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
,08-17 19:51:18.253  1014  1095 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,08-17 19:51:18.263  1014  1040 D InputDispatcher: Focus left window: 6762
,08-17 19:51:18.263  1014  1040 W InputDispatcher: Attempted to unregister already unregistered input channel
,08-17 19:51:18.263   257  1100 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-17 19:51:18.263   257  1036 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-17 19:51:18.273  1014  1040 D InputDispatcher: Focused application released
,08-17 19:51:18.273  1014  1495 W WindowManager: Failed looking up window
08-17 19:51:18.273  1014  1495 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@fcdf9c does not exist
08-17 19:51:18.273  1014  1495 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
08-17 19:51:18.273  1014  1495 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
08-17 19:51:18.273  1014  1495 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
08-17 19:51:18.273  1014  1495 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,08-17 19:51:18.273  1014  1495 I WindowState: WIN DEATH: null
,08-17 19:51:18.273  1014  1040 D FocusedStackFrame: Set to : 0
,08-17 19:51:18.273  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-17 19:51:18.273  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:51:18.273   257  1100 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-17 19:51:18.283  1014  1040 W ActivityManager: mDVFSHelper.acquire()
,08-17 19:51:18.293  1014  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-17 19:51:18.293  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-17 19:51:18.303  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-17 19:51:18.343  1478  1478 D Launcher: onRestart, Launcher: 119395821
,08-17 19:51:18.343  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:18.363  2630  2630 I art     : Explicit concurrent mark sweep GC freed 19553(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 813us total 48.790ms
,08-17 19:51:18.363  1861  1861 E SamsungIME: mOCRHelper is null
,08-17 19:51:18.363  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 19:51:18.373   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:51:18.383  4728  4728 I art     : Explicit concurrent mark sweep GC freed 22370(1365KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.695ms total 86.623ms
,08-17 19:51:18.403  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:51:18.403  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-17 19:51:18.403  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-17 19:51:18.403  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:51:18.403  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:51:18.413  1478  1478 D Launcher: onStart, Launcher: 119395821
08-17 19:51:18.413  1478  1478 D Launcher.HomeView: onStart
,08-17 19:51:18.423  1478  1478 D Launcher: onResume, Launcher: 119395821
,08-17 19:51:18.423  1014  4020 D SettingsProvider: name = kids_home_mode
08-17 19:51:18.423  1014  4020 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:51:18.423  1014  4020 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:51:18.423  1014  4020 D SettingsProvider: selectionArgs: false
08-17 19:51:18.423  1014  4020 D SettingsProvider: selectionArgs: 10006
08-17 19:51:18.423  1014  4020 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:51:18.423  1014  4020 D SettingsProvider: ret = -1
,08-17 19:51:18.423  1014  1122 V NetworkStats: performPollLocked() took 29ms
08-17 19:51:18.423  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:18.433  1478  1478 D Launcher.HomeView: onResume
,08-17 19:51:18.433  1432  1432 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:51:18.443  1432  1432 D RegisteredServicesCache: empty dynamic service
,08-17 19:51:18.443  2862  2862 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 19:51:18 GMT+02:00 2016
,08-17 19:51:18.473  1432  1432 D RegisteredComponentCache: Collect Tech packages for Knox
,08-17 19:51:18.473  1432  1432 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:51:18.533  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:18.533  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:51:18.543  1014  1014 I art     : Explicit concurrent mark sweep GC freed 82377(5MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/36MB, paused 5.071ms total 235.747ms
08-17 19:51:18.543  1014  1054 I art     : WaitForGcToComplete blocked for 224.220ms for cause Explicit
,08-17 19:51:18.573  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-17 19:51:18.573  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-17 19:51:18.583  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-17 19:51:18.583  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-17 19:51:18.583  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-17 19:51:18.583  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-17 19:51:18.593  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-17 19:51:18.643  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-17 19:51:18.643  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicy: uID is 10171
08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 19:51:18.643  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 19:51:18.653  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicy: uID is 10171
08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 19:51:18.653  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-17 19:51:18.653  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=3_task.xml
,08-17 19:51:18.653  1014  3326 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-17 19:51:18.653  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-17 19:51:18.653  1014  1014 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-17 19:51:18.693  1014  1054 I art     : Explicit concurrent mark sweep GC freed 8994(609KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 2.938ms total 149.124ms
,08-17 19:51:18.693  1014  1486 I art     : WaitForGcToComplete blocked for 326.410ms for cause Explicit
,08-17 19:51:18.753  1014  1054 D PackageManager: delete codoeFile: 
,08-17 19:51:18.763  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-17 19:51:18.763  1014  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-17 19:51:18.763  1014  1054 D PackageManager: result of delete: 1{413458386}
,08-17 19:51:18.763  7729  7729 D AndroidRuntime: Shutting down VM
,08-17 19:51:18.773  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-17 19:51:18.773  1014  1054 D PackageManager: userId{-1}
08-17 19:51:18.773  1014  1054 D PackageManager: andCode{true}
,08-17 19:51:18.773  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-17 19:51:18.773  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:18.773  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.773  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:18.773  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:18.783  1014  1040 W ActivityManager: mDVFSHelper.release()
,08-17 19:51:18.783  7747  7747 E Zygote  : MountEmulatedStorage()
08-17 19:51:18.783  7747  7747 E Zygote  : v2
08-17 19:51:18.783  7747  7747 I libpersona: KNOX_SDCARD checking this for 10003
08-17 19:51:18.783  7747  7747 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:18.793  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:51:18.793  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:51:18.793  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:51:18.803  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7747 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-17 19:51:18.813   309   309 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 20.355ms,
,08-17 19:51:18.823  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:51:18.823  7747  7747 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:18.823   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.439ms
,08-17 19:51:18.843   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.153ms,
08-17 19:51:18.843  1014  1486 I art     : Explicit concurrent mark sweep GC freed 3418(208KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.499ms total 154.514ms,
,08-17 19:51:18.853  1014  4020 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 19:51:18.853  1014  1333 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 19:51:18.853  1014  4020 D SecContentProvider2: mCursor = null
08-17 19:51:18.853  1014  1333 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-17 19:51:18.853  2035  2204 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 19:51:18.853  1014  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-17 19:51:18.853  1014  1333 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:18.853  1014  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:18.853  1014  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-17 19:51:18.853  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-17 19:51:18.853  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-17 19:51:18.853  1014  1039 W TextServicesManagerService: no available spell checker services found
08-17 19:51:18.853  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-17 19:51:18.853  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{fbdabc6 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1}
,08-17 19:51:18.863  2862  2862 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 19:51:18.863  1478  1478 D MenuAppsGridFragment: onResume
,08-17 19:51:18.863  1014  1465 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-17 19:51:18.863  1014  1465 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-17 19:51:18.863  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:18.863  1014  1465 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-17 19:51:18.863  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 19:51:18.873  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.873  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.873  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.873  1014  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:18.873  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 19:51:18.873  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:18.873  2862  2862 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 19:51:18.883  2862  2862 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 19:51:18.883  7764  7764 E Zygote  : MountEmulatedStorage()
08-17 19:51:18.883  7764  7764 I libpersona: KNOX_SDCARD checking this for 10090
08-17 19:51:18.883  7764  7764 E Zygote  : v2
08-17 19:51:18.883  7764  7764 I libpersona: KNOX_SDCARD not a persona
08-17 19:51:18.883  2862  2862 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-17 19:51:18.883  7764  7764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:51:18.883  2862  7762 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-17 19:51:18.883  2862  7762 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-17 19:51:18.883  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:18.883  7764  7764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:51:18.893  7764  7764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:51:18.893  2862  7762 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-17 19:51:18.893  1014  1465 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7764 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-17 19:51:18.893  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:18.893  1014  1486 D ActivityManager: handle home activity for 0
,08-17 19:51:18.893  1014  1486 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-17 19:51:18.893  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-17 19:51:18.893  1014  1486 D KnoxTimeoutHandler: post home show event for user 0
08-17 19:51:18.893  1014  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 19:51:18.893  1014  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:51:18.893  1014  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-17 19:51:18.893  2862  7762 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-17 19:51:18.893  1478  1478 D Launcher.HomeView: onPause
08-17 19:51:18.893  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-17 19:51:18.893  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:51:18.893  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 19:51:18.893  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-17 19:51:18.903  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-17 19:51:18.913  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.913  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.913  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.913  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:18.913  1014  1465 I TactileAssist: enable value -1
08-17 19:51:18.913  1014  1465 I TactileAssist: internal enable value -1
08-17 19:51:18.913  1014  1465 I TactileAssist: intensity value -1
08-17 19:51:18.913  1014  1465 I TactileAssist: saveAppList value true
,08-17 19:51:18.913  1014  1465 I TactileAssist: List of disabled apps :
,08-17 19:51:18.933  7778  7778 E Zygote  : MountEmulatedStorage()
08-17 19:51:18.933  7778  7778 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:51:18.933  7778  7778 E Zygote  : v2
08-17 19:51:18.933  7778  7778 I libpersona: KNOX_SDCARD not a persona
08-17 19:51:18.933  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:18.933  7764  7764 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:51:18.933  7764  7764 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:18.933  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:51:18.933  1014  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7778 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:51:18.933  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:51:18.933  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-17 19:51:18.933  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.933  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.933  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:18.933  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:18.953  7793  7793 E Zygote  : MountEmulatedStorage()
,08-17 19:51:18.953  7793  7793 E Zygote  : v2
08-17 19:51:18.953  7793  7793 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:51:18.953  7793  7793 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:18.963  7793  7793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:18.963  2862  7762 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-17 19:51:18.963  7793  7793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:51:18.963  1014  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7793 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:51:18.963  7778  7778 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:51:18.963  7793  7793 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:51:18.963  7778  7778 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:18.973  7729  7729 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 19:51:18.983  1478  1478 I Choreographer: Skipped 37 frames!  The application may be doing too much work on its main thread.
,08-17 19:51:18.993  2862  7762 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-17 19:51:19.003  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-17 19:51:19.003  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:51:19.003  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:51:19.013  7793  7793 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:51:19.013  2862  7762 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-17 19:51:19.013  7793  7793 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:19.013  7764  7764 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-17 19:51:19.013  7764  7764 D elm:15121: ELMEngine.ELMEngine( context ).
,08-17 19:51:19.023  7764  7764 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-17 19:51:19.023  1014  1465 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-17 19:51:19.023  1014  1465 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-17 19:51:19.023  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:19.023  1014  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:19.023  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-17 19:51:19.033  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:51:19.033  7764  7764 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-17 19:51:19.033  2862  2862 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-17 19:51:19.033   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-17 19:51:19.043  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-17 19:51:19.043  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-17 19:51:19.043  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.043  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.043  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.043  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:19.043  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:51:19.043  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:51:19.043  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:51:19.043  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 19:51:19.043  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:51:19.043  1014  1495 D InputDispatcher: Focus entered window: 1478
,08-17 19:51:19.053  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:51:19.053  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:51:19.053  1478  1478 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 19:51:19.053  7811  7811 E Zygote  : MountEmulatedStorage()
,08-17 19:51:19.053  7811  7811 E Zygote  : v2
08-17 19:51:19.053  7811  7811 I libpersona: KNOX_SDCARD checking this for 10048,
,08-17 19:51:19.053  1014  1027 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7811 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-17 19:51:19.053  7811  7811 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:19.053  7811  7811 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 19:51:19.063  7811  7811 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:51:19.063  7811  7811 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:51:19.063  7778  7778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-17 19:51:19.063  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:51:19.063  7764  7764 D elm:15121: ElmAgentService : onCreate()
08-17 19:51:19.063  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:19.073  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 19:51:19.073  7764  7810 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-17 19:51:19.073  7764  7810 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-17 19:51:19.073  7764  7810 D elm:15121: MDMBridge.getInstance()
08-17 19:51:19.073  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.073  7764  7810 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-17 19:51:19.073  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.073  7764  7810 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-17 19:51:19.073  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.073  7793  7793 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
08-17 19:51:19.073  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.073  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:19.073  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:51:19.073  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:51:19.083  1478  1478 D Launcher.HomeView: onStop
08-17 19:51:19.083  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{3f12b9e7 token=android.os.BinderProxy@3031a1dc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-17 19:51:19.083  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:19.083  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-17 19:51:19.083  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:19.083  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:51:19.093  7822  7822 E Zygote  : MountEmulatedStorage()
08-17 19:51:19.093  7822  7822 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:51:19.093  7822  7822 E Zygote  : v2
08-17 19:51:19.093  7822  7822 I libpersona: KNOX_SDCARD not a persona
08-17 19:51:19.093  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:51:19.093  7822  7822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:19.093  1014  1472 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 19:51:19.093  7822  7822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:51:19.093  7822  7822 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:51:19.093  1014  1014 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:51:19.103  1014  1465 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-17 19:51:19.103  1014  1465 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-17 19:51:19.103  1014  1472 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6762 uid 10171
,08-17 19:51:19.103  1177  1177 I StatusBar: Icon Only
08-17 19:51:19.103  1014  1465 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:19.103  1014  1465 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:19.103  1014  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-17 19:51:19.103  1177  1177 D PanelView: There is/are notification(s) 
,08-17 19:51:19.103  7811  7811 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:51:19.113  1014  1026 D SecContentProvider2: uri = -1 selection = getSealedState
08-17 19:51:19.113  1014  1026 D SecContentProvider2: mCursor = null
08-17 19:51:19.113  7811  7811 D ActivityThread: Added TimaKeyStore provider
08-17 19:51:19.113  1014  1026 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 19:51:19.113  1014  1026 D SecContentProvider2: mCursor = null
,08-17 19:51:19.113  7793  7793 I PopupuiReceiver_KNOX: getSealedState : true
08-17 19:51:19.113  1014  7826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:51:19.113  1014  1323 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-17 19:51:19.113  1014  1323 D SecContentProvider2: mCursor = null
,08-17 19:51:19.113  7793  7793 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-17 19:51:19.113  1014  1333 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-17 19:51:19.113  1014  1333 D SecContentProvider2: mCursor = null
,08-17 19:51:19.123  7793  7793 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-17 19:51:19.123  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-17 19:51:19.123  7793  7793 D PopupuiReceiver: Action package removed
,08-17 19:51:19.123  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-17 19:51:19.133  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.133  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.133  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.133  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:19.133  7822  7822 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:51:19.133  7822  7822 D ActivityThread: Added TimaKeyStore provider
,08-17 19:51:19.133  7778  7839 W FileUtils: Failed to chmod(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-17 19:51:19.133  7778  7839 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-17 19:51:19.133  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-17 19:51:19.133  7778  7839 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM AMData WHERE appname=?] disk I/O error
,08-17 19:51:19.133  7778  7839 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,08-17 19:51:19.143  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:19.143  7778  7839 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-17 19:51:19.143  7778  7839 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:161)
08-17 19:51:19.143  7778  7839 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:19.143  7778  7839 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:51:19.163  7846  7846 E Zygote  : MountEmulatedStorage()
,08-17 19:51:19.163  7846  7846 E Zygote  : v2
08-17 19:51:19.163  7846  7846 I libpersona: KNOX_SDCARD checking this for 1000
,08-17 19:51:19.163  7846  7846 I libpersona: KNOX_SDCARD not a persona
08-17 19:51:19.163  1014  1026 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7846 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:51:19.173  7764  7764 D elm:15121: ElmAgentService : onDestroy().
,08-17 19:51:19.173  7846  7846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:51:19.173  1014  1026 I ActivityManager: Killing 7113:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-17 19:51:19.173  7846  7846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:51:19.173  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fbdabc6 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:160515
08-17 19:51:19.173  7846  7846 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:51:19.183  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-17 19:51:19.183  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:19.183  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.183  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.183  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:19.193  7811  7811 D Compatibility: onReceive() it will make start service
,08-17 19:51:19.203  7859  7859 E Zygote  : MountEmulatedStorage()
08-17 19:51:19.203  7859  7859 I libpersona: KNOX_SDCARD checking this for 10145
08-17 19:51:19.203  7859  7859 E Zygote  : v2
08-17 19:51:19.203  7859  7859 I libpersona: KNOX_SDCARD not a persona
,08-17 19:51:19.203  7859  7859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:51:19.203  1014  1026 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7859 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:51:19.203  1014  1026 I ActivityManager: Killing 7177:com.sec.android.diagmonagent/1000 (adj 15): empty #21
08-17 19:51:19.203  7859  7859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:51:19.203  7859  7859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:51:19.203  1014  1026 I ActivityManager: Killing 7147:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-17 19:51:19.213  7822  7822 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
08-17 19:51:19.213  1014  1476 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-17 19:51:19.213  7822  7822 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 19:51:19.213  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-17 19:51:19.213  7822  7822 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-17 19:51:19.213  7822  7822 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
08-17 19:51:19.213  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:51:19.213  1014  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:51:19.213  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-17 19:51:19.213  1014  4020 I ActivityManager: Killing 7194:com.osp.app.signin/u0a36 (adj 15): empty #21
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:19.213  7822  7822 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:19.213  7822  7822 D AndroidRuntime: Shutting down VM
,08-17 19:51:19.223  7822  7822 E AndroidRuntime: FATAL EXCEPTION: main
08-17 19:51:19.223  7822  7822 E AndroidRuntime: Process: com.sec.pcw.device, PID: 7822
08-17 19:51:19.223  7822  7822 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-17 19:51:19.223  ,7822  7822 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-17 19:51:19.223  7822  7822 E AndroidRuntime: 	... 11 more
08-17 19:51:19.223  1014  1476 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-17 19:51:19.223  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.223  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.223  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:51:19.223  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:51:19.233  7859  7859 D TimaKeyStoreProvider: TimaSignature is unavailable
```
