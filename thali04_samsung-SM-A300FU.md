#### Test 83084099807e426_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
08-31 16:50:39.054   291   291 E SMD     : DCD OFF
08-31 16:50:39.334  5870  5870 D AndroidRuntime: 
08-31 16:50:39.334  5870  5870 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 16:50:39.334  5870  5870 D AndroidRuntime: CheckJNI is OFF
08-31 16:50:39.334  5870  5870 D AndroidRuntime: readGMSProperty: start
08-31 16:50:39.334  5870  5870 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:50:39.334  5870  5870 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:50:39.334  5870  5870 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:50:39.334  5870  5870 D AndroidRuntime: readGMSProperty: end
08-31 16:50:39.334  5870  5870 D AndroidRuntime: addProductProperty: start
08-31 16:50:39.454  5870  5870 E AffinityControl: AffinityControl: registerfunction enter
08-31 16:50:39.484  5870  5870 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 16:50:39.494  1016  1469 E PersonaManagerService: inState():  stateMachine is null !!
08-31 16:50:39.494  1016  1469 I PersonaManagerService: PersonaId don't exist
08-31 16:50:39.494  1016  1469 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 16:50:39.494  1016  1469 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-31 16:50:39.514  1016  1469 W ActivityManager: mDVFSHelper.acquire()
08-31 16:50:39.514   258   258 I SurfaceFlinger: id=9 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-31 16:50:39.514   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(An
08-31 16:50:39.524  1016  1469 D FocusedStackFrame: Set to : 0
08-31 16:50:39.534  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.534  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.534  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.534  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:39.534  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 16:50:39.534  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 16:50:39.544  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 16:50:39.544  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 16:50:39.544   258   258 I SurfaceFlinger: id=11 createSurf (540x960),1 flag=404, uhalitest
08-31 16:50:39.554  5881  5881 E Zygote  : MountEmulatedStorage()
08-31 16:50:39.554  5881  5881 E Zygote  : v2
08-31 16:50:39.554  5881  5881 I libpersona: KNOX_SDCARD checking this for 10171
08-31 16:50:39.554  5881  5881 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:39.554  5881  5881 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:50:39.554  1016  1469 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5881 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 16:50:39.554  1016  1469 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 16:50:39.554  1016  1469 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:39.554  5881  5881 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:50:39.554  5881  5881 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 16:50:39.554  1016  1469 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:39.554  1016  1469 D InputDispatcher: Focus left window: 1477
08-31 16:50:39.564  5870  5870 D AndroidRuntime: Shutting down VM
08-31 16:50:39.564  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:50:39.564  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:50:39.574  5881  5881 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:39.574  5881  5881 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:39.584  1016  2985 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 16:50:39.584  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 16:50:39.594  1016  1016 V ActivityManager: Display changed displayId=0
08-31 16:50:39.604  1016  2985 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:50:39.614  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 16:50:39.644   258  5200 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-31 16:50:39.644   258  5199 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-31 16:50:39.644  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{381c31ce token=android.os.BinderProxy@22cef998 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 16:50:39.654  1477  1477 D Launcher: onTrimMemory. Level: 20
08-31 16:50:39.744  5881  5881 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-31 16:50:39.764  5870  5870 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 16:50:39.814  5881  5881 I cr.library_loader: Time to load native libraries: 12 ms (timestamps 7707-7719)
08-31 16:50:39.814  5881  5881 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 16:50:39.834  5881  5881 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1166c27}
08-31 16:50:39.834  5881  5881 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 16:50:39.844  5881  5881 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 16:50:39.884  5881  5881 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-31 16:50:39.884  5881  5881 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:39.894  5881  5881 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 16:50:39.934  5881  5900 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
08-31 16:50:39.944  5881  5881 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:50:39.944  5881  5881 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:50:39.944  5881  5881 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:50:39.944  5881  5881 I Adreno-EGL: Local Branch: 
08-31 16:50:39.944  5881  5881 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:50:39.944  5881  5881 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:50:39.944  5881  5881 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-31 16:50:40.024  5881  5911 D BluetoothAdapter: 844514162: getState() :  mService = null. Returning STATE_OFF
08-31 16:50:40.044  5881  5881 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 16:50:40.054  5881  5881 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-31 16:50:40.064  5881  5881 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-31 16:50:40.064  5881  5881 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 16:50:40.064  5881  5881 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 16:50:40.074  4926  4926 D FactoryTest: Not factory mode
08-31 16:50:40.074  4926  4926 D FactoryTest: Not factory mode. isFactoryMode() returend false
08-31 16:50:40.074  4926  4926 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-31 16:50:40.074  4926  4926 D MTPRx   : still no open session command from host, so toast
08-31 16:50:40.104  4926  4926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-31 16:50:40.104  4926  4926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
08-31 16:50:40.104  4926  4926 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:108012
08-31 16:50:40.104  1016  3695 E PersonaManagerService: inState():  stateMachine is null !!
08-31 16:50:40.104  1016  3695 I PersonaManagerService: PersonaId don't exist
08-31 16:50:40.104  1016  3695 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 16:50:40.104  1016  3695 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 16:50:40.104  1016  3695 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:50:40.104  1016  3695 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:50:40.104  1016  3695 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
08-31 16:50:40.114  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{2bf2cd28 u0 com.test.thalitest/.MainActivity t2}
08-31 16:50:40.114  1016  3695 W ActivityManager: mDVFSHelper.acquire()
08-31 16:50:40.124  1016  3695 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:40.124  1016  3695 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 16:50:40.124  1016  3695 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:40.124  4926  4926 E MTPRx   : started activity for popup
08-31 16:50:40.134  1016  1041 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:50:40.164  4926  4926 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-31 16:50:40.164  4926  4926 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-31 16:50:40.164  4926  4926 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 16:50:40.164  4926  4926 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:50:40.164  4926  4926 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:50:40.164  4926  4926 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 16:50:40.194  4926  4926 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
08-31 16:50:40.204  5881  5881 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:40.214  1016  3684 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 16:50:40.214  1016  3684 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:40.214  1016  3684 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:40.224  5881  5881 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 16:50:40.234  1016  1312 E Watchdog: !@Sync 3
08-31 16:50:40.234  5881  5881 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 16:50:40.234  5881  5881 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-31 16:50:40.244  5881  5881 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-31 16:50:40.254  5881  5881 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:40.254  5881  5881 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 16:50:40.254  4926  4926 D SettingsReceiverActivity: dev.kiessupport is : TRUE
08-31 16:50:40.264  4926  4926 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-31 16:50:40.264  4926  4926 D PhoneWindow: *FMB* installDecor flags : 8388610
08-31 16:50:40.294  5881  5922 D OpenGLRenderer: Render dirty regions requested: true
08-31 16:50:40.294  1016  3695 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 16:50:40.294  1016  3695 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 16:50:40.294  1016  3695 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 16:50:40.294  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 16:50:40.294  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 16:50:40.294  5881  5909 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-31 16:50:40.304  5881  5881 V ActivityThread: updateVisibility : ActivityRecord{2659734 token=android.os.BinderProxy@36e92c21 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 16:50:40.304  5881  5881 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 16:50:40.304  5881  5881 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 16:50:40.324   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
08-31 16:50:40.334  1016  1447 D InputDispatcher: Focus entered window: 5881
08-31 16:50:40.334  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:50:40.334  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:50:40.334  5881  5881 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-31 16:50:40.334  5881  5922 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 16:50:40.344  5881  5922 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-31 16:50:40.344  5881  5922 D OpenGLRenderer: Enabling debug mode 0
08-31 16:50:40.354  1016  1029 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{2bf2cd28 u0 com.test.thalitest/.MainActivity t2}
08-31 16:50:40.364  1016  3693 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-31 16:50:40.364  1016  5927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-31 16:50:40.364  1176  1176 I StatusBar: Icon Only
08-31 16:50:40.364  1176  1176 D PanelView: There is/are notification(s) 
08-31 16:50:40.374  1016  3695 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 16:50:40.374  1016  3695 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 16:50:40.374  1016  3695 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 16:50:40.374  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 16:50:40.374  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 16:50:40.434  1016  1046 W ActivityManager: mDVFSHelper.release()
08-31 16:50:40.434  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2bf2cd28 u0 com.test.thalitest/.MainActivity t2} time:108342
08-31 16:50:40.434  1016  2984 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:50:40.444  1777  1777 I SamsungIME: getCurrentCandidateView
08-31 16:50:40.454   258   445 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
08-31 16:50:40.454   258  1098 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
08-31 16:50:40.454  5881  5881 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-31 16:50:40.464  5881  5881 V ActivityThread: updateVisibility : ActivityRecord{2659734 token=android.os.BinderProxy@36e92c21 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 16:50:40.464  5881  5881 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36e92c21 time:108372
08-31 16:50:40.464  5881  5881 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36e92c21 time:108373
08-31 16:50:40.574  5881  5881 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5881
08-31 16:50:40.574  1777  1777 D SamsungIME: Dismiss ExpandCandiate
,08-31 16:50:40.734  1777  1777 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 16:50:40.774  1777  1777 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 16:50:40.784  1777  1777 I SamsungIME: KeybaordView init() : load resources
,08-31 16:50:40.804  5881  5881 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:50:40.804  1777  1777 I SamsungIME: getCurrentKeyboard
08-31 16:50:40.804  1777  1777 I SamsungIME: getTextKeyboard
,08-31 16:50:40.824  1777  1777 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 16:50:40.894  5881  5929 D jxcore_app_log: JniHelper::setJavaVM(0xb75942b0), pthread_self() = -1213033992
,08-31 16:50:40.904  5881  5929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:50:40.904  5881  5929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:50:40.904  5881  5929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:50:40.904  5881  5929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:50:40.904  5881  5929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 16:50:40.904  5881  5929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6d7a2a added. We now have 1 listener(s)
,08-31 16:50:40.914  5881  5929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-31 16:50:40.914  5881  5929 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 16:50:40.914  5881  5929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 16:50:40.914  5881  5929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 16:50:40.924  5881  5929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ca45f91 added. We now have 1 listener(s)
,08-31 16:50:40.924  5881  5929 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 16:50:40.924  5881  5929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 16:50:40.924  5881  5929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 16:50:40.924  5881  5929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 16:50:40.934  5881  5929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-31 16:50:40.934  5881  5929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 16:50:40.934  5881  5929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 16:50:40.934  5881  5929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-31 16:50:40.934  5881  5929 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:40.934  5881  5929 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:50:40.934  5881  5929 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:50:40.934  5881  5929 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 16:50:40.944  5881  5929 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 16:50:40.974  5881  5881 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 16:50:41.024   324   324 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 16:50:41.024   324   324 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-31 16:50:41.604  5881  5936 W jxcore-log: Initializing JXcore engine
08-31 16:50:41.604  5881  5936 W jxcore-log: JXcore engine is ready
,08-31 16:50:41.654  1917  1917 E audit   : type=1400 msg=audit(1472655041.654:203): avc:  denied  { ioctl } for  pid=5936 comm="Thread-1080" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 16:50:41.654  1917  1917 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:50:41.654  1917  1917 E audit   : type=1300 msg=audit(1472655041.654:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f2ff8f8 items=0 ppid=311 ppcomm=main pid=5936 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1080" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 16:50:41.654  1917  1917 E audit   : type=1320 msg=audit(1472655041.654:203): 
,08-31 16:50:41.674  5881  5936 W jxcore-log: Starting JXcore engine
,08-31 16:50:41.774  5881  5936 W jxcore-log: Platform android
08-31 16:50:41.774  5881  5936 W jxcore-log: 
08-31 16:50:41.774  5881  5936 W jxcore-log: Process ARCH arm
08-31 16:50:41.774  5881  5936 W jxcore-log: 
,08-31 16:50:41.984  5881  5936 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:50:41.984  5881  5936 I jxcore-log: 
,08-31 16:50:41.984  5881  5936 W jxcore-log: JXcore engine is started
,08-31 16:50:41.994  5881  5929 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 16:50:41.994  5881  5881 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 16:50:42.054   291   291 E SMD     : DCD OFF
,08-31 16:50:45.054   291   291 E SMD     : DCD OFF,
,08-31 16:50:45.804  1016  2632 D SSRM:n  : SIOP:: AP = 330
,08-31 16:50:46.024   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:47.024   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:47.264  1016  2646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:48.024   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:48.054   291   291 E SMD     : DCD OFF,
,08-31 16:50:48.294  1016  2985 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-31 16:50:48.294  1016  2985 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 16:50:48.294  1016  2985 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 16:50:48.294  1016  2985 D BatteryService: stay LED for fully charged
08-31 16:50:48.294  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:50:48.294  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-31 16:50:48.294  1016  1016 I MotionRecognitionService: Plugged,
08-31 16:50:48.294  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 16:50:48.294  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 16:50:48.304  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 16:50:48.304  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 16:50:48.324  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 16:50:48.324  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-31 16:50:48.324  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:50:48.324  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:50:48.324  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 16:50:49.024   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:49.584  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-31 16:50:50.024   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:51.034   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-31 16:50:51.054   291   291 E SMD     : DCD OFF,
,08-31 16:50:52.094  1016  1096 V AlarmManager: waitForAlarm result :4
,08-31 16:50:52.094  1016  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-31 16:50:52.214  4104  4104 D ConnectivityManager: CallingUid : 10011, CallingPid : 4104
,08-31 16:50:52.214  1016  1474 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:52.274  4104  5943 W DriveInitializer: Background init thread started
,08-31 16:50:52.304   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-31 16:50:52.304   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:50:52.304  4104  5943 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-31 16:50:52.344  4104  5943 W DriveInitializer: Background init thread ended
,08-31 16:50:54.054   291   291 E SMD     : DCD OFF,
,08-31 16:50:55.824  1016  2632 D SSRM:n  : SIOP:: AP = 340
,08-31 16:50:56.034   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:57.034   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:57.054   291   291 E SMD     : DCD OFF,
,08-31 16:50:58.034   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:58.344  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:50:59.034   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:59.984  1016  1096 V AlarmManager: waitForAlarm result :8
,08-31 16:51:00.034   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:51:00.054   291   291 E SMD     : DCD OFF
,08-31 16:51:00.214  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 16:51:00.214  5881  5936 I jxcore-log: 
,08-31 16:51:00.224  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 16:51:00.224  5881  5936 I jxcore-log: 
,08-31 16:51:00.224  5881  5936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:00.224  5881  5936 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:51:00.224  5881  5936 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:00.224  5881  5936 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:51:00.224  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:51:00.224  5881  5936 I jxcore-log: 
,08-31 16:51:00.224  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:51:00.224  5881  5936 I jxcore-log: 
,08-31 16:51:00.264  1016  1048 I PowerManagerService: [PWL] Off : 75s ago
,08-31 16:51:00.694  5881  5936 I jxcore-log: Running unit tests
08-31 16:51:00.694  5881  5936 I jxcore-log: 
,08-31 16:51:00.694  5881  5936 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:51:00.694  5881  5936 I jxcore-log: Failed to execute UT.
08-31 16:51:00.694  5881  5936 I jxcore-log: 
,08-31 16:51:00.694  5881  5936 I jxcore-log: Unit Test app is loaded
08-31 16:51:00.694  5881  5936 I jxcore-log: 
,08-31 16:51:00.704  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:51:00.704  5881  5936 I jxcore-log: 
,08-31 16:51:00.704  5881  5881 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 16:51:00.714  1016  1469 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 16:51:00.714  1016  1469 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 16:51:00.714  1016  1469 D SecContentProvider2: mCursor = null
,08-31 16:51:00.714  1016  1469 D WifiService: setWifiEnabled: true pid=5881, uid=10171
,08-31 16:51:00.714  1016  1469 W ActivityManager: Permission Denial: getCurrentUser() from pid=5881, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:51:00.714  1016  1469 W WifiService: Failed getting userId using ActivityManagerNative
08-31 16:51:00.714  1016  1469 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5881, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:51:00.714  1016  1469 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 16:51:00.714  1016  1469 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 16:51:00.714  1016  1469 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 16:51:00.714  1016  1469 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 16:51:00.714  1016  1469 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 16:51:00.724  1016  1469 D SettingsProvider: name = wifi_on
,08-31 16:51:00.724  1016  1129 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 16:51:00.724  1016  1434 I WifiService: disconnect: pid=5881, uid=10171
,08-31 16:51:00.734  5881  5936 D BluetoothAdapter: enable()
,08-31 16:51:00.744  1016  1492 W ActivityManager: Permission Denial: getCurrentUser() from pid=5881, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-31 16:51:00.794  1016  1492 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-31 16:51:00.794  1016  1492 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5881, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:51:00.794  1016  1492 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 16:51:00.794  1016  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 16:51:00.794  1016  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 16:51:00.794  1016  1492 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 16:51:00.794  1016  1492 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 16:51:00.794  1016  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:00.794  1016  1492 D SettingsProvider: name = bluetooth_on
08-31 16:51:00.794  1016  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:51:00.814  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:51:00.814  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:00.814  5881  5936 I jxcore-log: My device name is: samsung-SM-A300FU
08-31 16:51:00.814  5881  5936 I jxcore-log: 
,08-31 16:51:00.814  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-31 16:51:00.814  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 16:51:00.814  5881  5936 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 16:51:00.814  5881  5936 I jxcore-log: 
,08-31 16:51:00.814  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:00.814  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.814  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.814  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:00.824  5960  5960 E Zygote  : MountEmulatedStorage()
,08-31 16:51:00.834  5960  5960 E Zygote  : v2
,08-31 16:51:00.834  5960  5960 I libpersona: KNOX_SDCARD checking this for 1002
08-31 16:51:00.834  5960  5960 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:00.834  5960  5960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:00.834  5960  5960 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:00.834  5960  5960 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:00.844  1016  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5960 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-31 16:51:00.874  5960  5960 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:00.874  5960  5960 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:00.884  5960  5960 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 16:51:00.884  5960  5960 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:51:00.934  5960  5960 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 16:51:00.984  5960  5960 D BtSettings.ProfileConfig: Adding GattService
,08-31 16:51:00.984  5960  5960 D BtSettings.ProfileConfig: Adding HeadsetService
,08-31 16:51:00.984  5960  5960 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 16:51:00.984  5960  5960 D BtSettings.ProfileConfig: Adding HidService
,08-31 16:51:00.984  5960  5960 D BtSettings.ProfileConfig: Adding HealthService
08-31 16:51:00.994  5960  5960 D BtSettings.ProfileConfig: Adding PanService
08-31 16:51:00.994  5960  5960 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 16:51:00.994  5960  5960 D BtSettings.ProfileConfig: Adding SapService
08-31 16:51:00.994  5960  5960 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-31 16:51:00.994  5960  5960 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 16:51:00.994  5960  5960 D BtSettings.ProfileConfig: Adding SapClientService
08-31 16:51:00.994  5960  5960 D BtSettings.ProfileConfig: Adding HidDevService
,08-31 16:51:00.994  5960  5960 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 16:51:00.994  1016  2984 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 16:51:00.994  1016  2984 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.994  1016  2984 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.994  1016  2984 D SettingsProvider: selectionArgs: false
08-31 16:51:00.994  1016  2984 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.994  1016  2984 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.994  1016  2984 D SettingsProvider: ret = -1
,08-31 16:51:01.004  1016  2984 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.014  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 16:51:01.014  1016  1077 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-31 16:51:01.014  1016  1077 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.014  1016  1077 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.014  1016  1077 D SettingsProvider: selectionArgs: false
08-31 16:51:01.014  1016  1077 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.014  1016  1077 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.014  1016  1077 D SettingsProvider: ret = -1
,08-31 16:51:01.024  1016  1077 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.024  1016  1434 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.024  1016  1434 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.024  1016  1434 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.024  1016  1434 D SettingsProvider: selectionArgs: false
08-31 16:51:01.024  1016  1434 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.024  1016  1434 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.024  1016  1434 D SettingsProvider: ret = -1
08-31 16:51:01.034  1016  1434 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
08-31 16:51:01.034   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
08-31 16:51:01.034  1016  3695 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 16:51:01.034  1016  3695 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.034  1016  3695 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.034  1016  3695 D SettingsProvider: selectionArgs: false
08-31 16:51:01.034  1016  3695 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.034  1016  3695 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.034  1016  3695 D SettingsProvider: ret = -1
08-31 16:51:01.034  1016  3695 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
08-31 16:51:01.044  1016  2984 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 16:51:01.044  1016  2984 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.044  1016  2984 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.044  1016  2984 D SettingsProvider: selectionArgs: false
08-31 16:51:01.044  1016  2984 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.044  1016  2984 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.044  1016  2984 D SettingsProvider: ret = -1
08-31 16:51:01.044  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-31 16:51:01.054  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-31 16:51:01.054  1016  2984 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.054  1016  3693 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 16:51:01.054  1016  3693 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.054  1016  3693 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.054  1016  3693 D SettingsProvider: selectionArgs: false
08-31 16:51:01.054  1016  3693 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.054  1016  3693 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.054  1016  3693 D SettingsProvider: ret = -1
,08-31 16:51:01.064  1016  3693 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.064  1016  2985 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 16:51:01.064  1016  2985 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.064  1016  2985 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.064  1016  2985 D SettingsProvider: selectionArgs: false
08-31 16:51:01.064  1016  2985 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.064  1016  2985 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.064  1016  2985 D SettingsProvider: ret = -1
08-31 16:51:01.064  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-31 16:51:01.074  1016  2985 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.074  1016  1474 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-31 16:51:01.074  1016  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.074  1016  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.074  1016  1474 D SettingsProvider: selectionArgs: false
,08-31 16:51:01.074  1016  1474 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.074  1016  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.074  1016  1474 D SettingsProvider: ret = -1
,08-31 16:51:01.074  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.074  1016  1474 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.084  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:51:01.084  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:51:01.084  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.084  1016  1029 D SettingsProvider: selectionArgs: false
08-31 16:51:01.084  1016  1029 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.084  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.084  1016  1029 D SettingsProvider: ret = -1
,08-31 16:51:01.084  1016  1029 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,08-31 16:51:01.084  1016  2985 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:51:01.084  1016  2985 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.084  1016  2985 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 16:51:01.094  1016  2985 D SettingsProvider: selectionArgs: false
08-31 16:51:01.094  1016  2985 D SettingsProvider: selectionArgs: 1002
,08-31 16:51:01.094  1016  2985 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.094  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.094  1016  2985 D SettingsProvider: ret = -1
,08-31 16:51:01.094  1016  2985 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.094  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.104  1016  3695 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-31 16:51:01.104  1016  3695 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.104  1016  3695 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.104  1016  3695 D SettingsProvider: selectionArgs: false
08-31 16:51:01.104  1016  3695 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.104  1016  3695 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.104  1016  3695 D SettingsProvider: ret = -1
,08-31 16:51:01.104  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.104  1016  3695 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.114  1016  2984 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-31 16:51:01.114  1016  2984 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.114  1016  2984 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 16:51:01.114  1016  2984 D SettingsProvider: selectionArgs: false
08-31 16:51:01.114  1016  2984 D SettingsProvider: selectionArgs: 1002
,08-31 16:51:01.114  1016  2984 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 16:51:01.114  1016  2984 D SettingsProvider: ret = -1
,08-31 16:51:01.114  1016  2984 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.124  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.134  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,08-31 16:51:01.134  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.144  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.154  5960  5960 D BluetoothAdapterState: make
,08-31 16:51:01.154  5960  5960 I bluedroid: init
,08-31 16:51:01.164  5960  5986 I BluetoothAdapterState: Entering OffState
,08-31 16:51:01.164  5960  5960 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 16:51:01.174  5960  5960 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 16:51:01.174  5960  5960 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 16:51:01.174  5960  5960 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 16:51:01.174  5960  5960 E bt-btif : btif_fetch_local_ble_random_bdaddr,
08-31 16:51:01.174  5960  5960 I bluedroid: get_profile_interface socket
,08-31 16:51:01.174  5960  5960 I bluedroid: get_profile_interface map_client
,08-31 16:51:01.174  5960  5960 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-31 16:51:01.184  5960  5989 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 16:51:01.184  5960  5960 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:01.184  1016  1077 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 16:51:01.184  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.184  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.184  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.184  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.194  5960  5989 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-31 16:51:01.194  5960  5989 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:51:01.194  5960  5989 I bluedroid: getModelRssiValues
08-31 16:51:01.194  5960  5989 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:51:01.194  5960  5989 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-31 16:51:01.194  5960  5989 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 16:51:01.194  1016  1016 D SettingsProvider: name = bluetooth_name
,08-31 16:51:01.194  5960  5973 I bluedroid: config_hci_snoop_log
,08-31 16:51:01.194  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-31 16:51:01.204  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-31 16:51:01.214  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-31 16:51:01.214  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 16:51:01.214  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 16:51:01.214  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:01.214  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:01.224  5960  5960 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 16:51:01.224  1016  1043 D Tethering: interfaceAdded wlan0,
,08-31 16:51:01.234  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 16:51:01.244  1016  1132 E Tethering: No numeric data
,08-31 16:51:01.244  1016  1126 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:01.254  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 16:51:01.254  1016  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 16:51:01.254  1016  1132 D Tethering: clearTetheredNotification()
08-31 16:51:01.254  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 16:51:01.254  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 16:51:01.254  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 16:51:01.254  1016  1132 D Tethering: InitialState.processMessage what=4
,08-31 16:51:01.254  5960  5986 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-31 16:51:01.254  5960  5986 D BluetoothAdapterProperties: Setting state to 11
08-31 16:51:01.254  5960  5986 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 16:51:01.254  5960  5986 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:51:01.254  5960  5986 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 16:51:01.254  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:01.254  1176  1176 D HotspotTile: updateTetherState():false, false
,08-31 16:51:01.254  1016  1043 D Tethering: interfaceAdded p2p0
,08-31 16:51:01.254  5960  5986 D BluetoothAdapterService: Autoconnection is available 
08-31 16:51:01.254  5960  5986 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 16:51:01.264  1016  1132 E Tethering: No numeric data
08-31 16:51:01.264   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:01.264   278   972 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:01.264  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 16:51:01.264  5960  5986 D BluetoothSecureManager: getInstant: null
08-31 16:51:01.264  5960  5986 D BluetoothSecureManager: calling getMethod for getService
,08-31 16:51:01.264  5960  5986 D BluetoothSecureManager: calling getService
08-31 16:51:01.264   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:01.264   278   972 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:01.264  5960  5986 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1fe2b91f
08-31 16:51:01.264  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:01.264  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-31 16:51:01.264  1016  1126 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:01.264  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:01.264  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:01.264  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:01.264  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.264  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.264  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:01.274   278   976 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 16:51:01.274   278   976 D SoftapController: Softap fwReload - Ok
,08-31 16:51:01.274  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 16:51:01.284  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:01.284   278   976 D CommandListener: Setting iface cfg
08-31 16:51:01.284   278   976 D CommandListener: Trying to bring down wlan0
,08-31 16:51:01.284  1016  1126 V NetworkStats: performPollLocked() took 13ms
08-31 16:51:01.284  1777  1777 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 16:51:01.284  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-31 16:51:01.284   278   976 D CommandListener: Clearing all IP addresses on wlan0
,08-31 16:51:01.284  1176  1699 D BluetoothTile:  handleUpdatestate:false name:null,
08-31 16:51:01.284  1176  1699 D STATUSBAR-QSTileView: onStateChanged: Bluetooth,
,08-31 16:51:01.284  5881  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:01.294  1016  2985 D BluetoothSecureManagerService: isSecureModeEnabled
,08-31 16:51:01.294  1016  2985 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-31 16:51:01.294  5960  5986 D BtConfig.SecureMode: isSecureModeOn:false
08-31 16:51:01.294  1016  3684 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 16:51:01.294  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 16:51:01.294  1016  1469 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 16:51:01.294  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 16:51:01.294  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 16:51:01.294  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 16:51:01.294  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.294  1016  1129 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 16:51:01.294  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.294  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 16:51:01.294  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService,
08-31 16:51:01.294  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 16:51:01.294  1016  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 16:51:01.294  1016  1132 D Tethering: clearTetheredNotification()
,08-31 16:51:01.294  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 16:51:01.294  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 16:51:01.294  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 16:51:01.304  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 16:51:01.304  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 16:51:01.304  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 16:51:01.304  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 16:51:01.304  5960  5986 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 16:51:01.304  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:51:01.304  5960  5986 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:01.304  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:51:01.304  5960  5986 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:01.304  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 16:51:01.304  5960  5986 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-31 16:51:01.304  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 16:51:01.304  5960  5986 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-31 16:51:01.304  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 16:51:01.304  1016  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:01.304  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.304  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.314  1176  1176 D HotspotTile: updateTetherState():false, false
08-31 16:51:01.304  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:01.304  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:01.314  1016  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 16:51:01.314  1016  1126 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:01.314  1016  1126 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:01.314  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:01.314  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:01.314  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:01.324  1016  1126 V NetworkStats: performPollLocked() took 4ms
,08-31 16:51:01.324  5960  5986 D BluetoothBondStateMachine: make
08-31 16:51:01.324  1176  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 16:51:01.324  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:01.324  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.324  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 16:51:01.324  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.324  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.324  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.324  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.324  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.324  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 16:51:01.334  1176  1176 D HotspotTile: onReceive : 2, 0
,08-31 16:51:01.334  5881  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:01.334  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 16:51:01.334  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 16:51:01.334  5960  5986 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 16:51:01.334  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:01.334  1016  2984 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.334  1016  2984 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.334  1016  1127 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:01.334  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:01.334  1016  1127 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:01.344  1016  3695 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.334  1016  2984 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.344  1016  3695 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 16:51:01.334  1016  2984 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.334  1016  2984 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.344  5960  5994 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 16:51:01.344  5960  5960 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 16:51:01.344  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 16:51:01.344  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:51:01.344  5960  5986 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 16:51:01.344  5960  5960 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:51:01.344  5960  5960 D BtGatt.GattService: start()
08-31 16:51:01.344  5960  5960 D BtGatt.GattService: start()
08-31 16:51:01.344  5960  5960 I bluedroid: get_profile_interface gatt
08-31 16:51:01.344  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.344  5960  5960 D BtGatt.AdvertiseManager: advertise manager created
08-31 16:51:01.344  1016  3695 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.344  1016  3695 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.344  1016  3695 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.344  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.344  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.344  5960  5986 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.344  1016  1078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.344  1016  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.344  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.344  1016  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.344  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.354  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 16:51:01.354  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:51:01.354  5960  5986 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 16:51:01.354  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.354  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 16:51:01.354  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.354  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.354  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.354  1281  1281 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.364  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 16:51:01.364  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 16:51:01.364  5960  5986 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 16:51:01.364  5960  5960 D BtGatt.GattService: mStartError = false
08-31 16:51:01.364  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.364  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.364  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 16:51:01.364  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.364  1281  1281 D BluetoothNotiBroadcastReceiver: onReceive
08-31 16:51:01.364  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.364  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.374  5993  5993 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 16:51:01.374  5993  5993 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 16:51:01.374  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 16:51:01.374  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 16:51:01.374  5960  5986 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 16:51:01.374  5993  5993 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 16:51:01.384  5960  5960 D HeadsetService: Received start request. Starting profile...
08-31 16:51:01.384  1016  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.384  5960  5960 D HeadsetService: start()
08-31 16:51:01.384  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 16:51:01.394  5960  5960 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 16:51:01.394  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:01.394  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-31 16:51:01.394  5960  5960 D HeadsetStateMachine: make
08-31 16:51:01.394  5960  5960 E HeadsetStateMachine: # of Max HF connection is 2
08-31 16:51:01.394  5993  5993 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-31 16:51:01.404  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.404  1016  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.404  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.404   401   401 I SecureStorage: [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5993
08-31 16:51:01.404   401   401 I SecureStorage: [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
08-31 16:51:01.404  5993  5993 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 16:51:01.404  5993  5993 I wpa_supplicant: ssSupport state is = 1
08-31 16:51:01.404  5993  5993 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 16:51:01.404  5993  5993 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 16:51:01.404   401   401 I SecureStorage: [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5993
08-31 16:51:01.404   401   401 I SecureStorage: [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
08-31 16:51:01.404  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 16:51:01.404  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 16:51:01.404  5960  5986 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 16:51:01.404  1016  1447 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-31 16:51:01.414  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.414  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.414  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.414  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.434  6000  6000 E Zygote  : MountEmulatedStorage(),
08-31 16:51:01.434  6000  6000 E Zygote  : v2
08-31 16:51:01.434  6000  6000 I libpersona: KNOX_SDCARD checking this for 10055
08-31 16:51:01.434  6000  6000 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:01.434  6000  6000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:01.444  6000  6000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:01.444  6000  6000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-31 16:51:01.444  1016  1447 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6000 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-31 16:51:01.444  1016  2984 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 16:51:01.444  1016  2984 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.444  1016  2984 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.444  1016  2984 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.444  1016  2984 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 16:51:01.444  1016  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 16:51:01.444  1016  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-31 16:51:01.454  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:01.454  1016  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.454  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.454  1016  1434 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 16:51:01.454  1016  1434 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.454  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 16:51:01.454  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 16:51:01.454  5960  5986 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 16:51:01.454  1016  1434 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.454  1016  1434 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.454  1016  1434 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 16:51:01.454  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.454  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-31 16:51:01.454  5960  5960 I bluedroid: get_profile_interface handsfree
,08-31 16:51:01.454  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.454  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.454  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:01.464  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:01.464  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 16:51:01.464  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 16:51:01.464  5960  5986 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 16:51:01.464  5960  5986 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 16:51:01.464  5960  5986 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 16:51:01.484  5960  5960 I DualScoManager: Instantiating Dual Sco Manager
08-31 16:51:01.484  5960  5960 I DualScoManager: Set HeadsetServiceHelper
,08-31 16:51:01.484  6000  6000 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:01.484  6000  6000 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:01.484  5960  5960 D BluetoothAtMessage: createCMTIContentObservers
,08-31 16:51:01.494  1016  1077 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 16:51:01.494  1016  1077 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.494  1016  1077 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.494  1016  1077 D SettingsProvider: selectionArgs: false
08-31 16:51:01.494  1016  1077 D SettingsProvider: selectionArgs: 1002
08-31 16:51:01.494  1016  1077 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.494  1016  1077 D SettingsProvider: ret = -1
,08-31 16:51:01.494  1016  1077 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:01.504  5960  5999 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 16:51:01.504  5960  5960 D HeadsetService: mStartError = false
08-31 16:51:01.504  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.504  5960  5999 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 16:51:01.504  5960  5999 D HeadsetStateMachine: map size, before remove : 0
08-31 16:51:01.504  5960  5999 D HeadsetStateMachine: map size, after remove: 0
,08-31 16:51:01.504  1016  1016 D BluetoothA2dp: Proxy object connected
08-31 16:51:01.504  5960  5960 D A2dpService: Received start request. Starting profile...
08-31 16:51:01.504  5960  5960 D A2dpService: start()
,08-31 16:51:01.514  5960  5960 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 16:51:01.514  5960  5960 I bluedroid: get_profile_interface avrcp
,08-31 16:51:01.524  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.524  5960  5960 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 16:51:01.534  5960  5960 D Avrcp   : Initialize Media Controller
08-31 16:51:01.534  5960  5960 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 16:51:01.534  5960  5960 E Avrcp   : getActiveSessions
,08-31 16:51:01.534  5960  5960 D Avrcp   : pick active media Controller
,08-31 16:51:01.534  5960  5960 D Avrcp   : Get the active Media Controller 
,08-31 16:51:01.554  5960  5960 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 16:51:01.554  5960  6016 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 16:51:01.564  5960  5960 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:51:01.564  5960  5960 D A2dpStateMachine: make
,08-31 16:51:01.564  5960  5960 I bluedroid: get_profile_interface a2dp
,08-31 16:51:01.564  5960  6018 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 16:51:01.564  5960  5960 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 16:51:01.564  5960  5960 D A2dpService: mStartError = false
08-31 16:51:01.564  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.564  5960  6017 D A2dpStateMachine: Enter Disconnected: -2,
08-31 16:51:01.564  5960  5960 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 16:51:01.574  6000  6000 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 16:51:01.574  5960  6016 D BluetoothMediaBrowser: no now playing list
,08-31 16:51:01.574  5960  6016 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 16:51:01.604  5960  5960 D HidService: Received start request. Starting profile...,
08-31 16:51:01.604  5960  5960 D HidService: start()
08-31 16:51:01.604  5960  5960 I bluedroid: get_profile_interface hidhost
08-31 16:51:01.604  5960  5960 D HidService: setHidService(): set to: null
08-31 16:51:01.604  5960  5960 D HidService: mStartError = false,
08-31 16:51:01.604  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6,
08-31 16:51:01.604  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-31 16:51:01.604  5960  5960 I BluetoothHealthServiceJni: classInitNative: succeeds,
08-31 16:51:01.604  5960  5960 D HealthService: Received start request. Starting profile...
08-31 16:51:01.604  5960  5960 D HealthService: start()
08-31 16:51:01.604  5960  5960 I bluedroid: get_profile_interface health
08-31 16:51:01.604  5960  5960 D HealthService: mStartError = false,
08-31 16:51:01.604  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.644  6000  6000 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 16:51:01.644  6000  6000 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-31 16:51:01.644  6000  6000 D UserAnalysis: Create SecureDbHelper
,08-31 16:51:01.654  6000  6000 D IntelligenceServiceApplication: onCreate()
,08-31 16:51:01.654   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0,
,08-31 16:51:01.664  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)Processing data has been completed,
,08-31 16:51:01.664  5960  5960 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 16:51:01.674  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:51:01.674  5960  5960 D PanService: Received start request. Starting profile...
08-31 16:51:01.674  5960  5960 D PanService: start()
08-31 16:51:01.674  6000  6000 D IntelligenceServiceApplication: no applications having user consent for prediction
08-31 16:51:01.674  5960  5960 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 16:51:01.674  5960  5960 I bluedroid: get_profile_interface pan
08-31 16:51:01.674  1016  2985 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-31 16:51:01.674  5960  5960 D PanService: mStartError = false
08-31 16:51:01.674  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.674  6000  6000 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-31 16:51:01.674  5960  5960 D HeadsetStateMachine: Try to query the phonestate on bind
08-31 16:51:01.684  1422  1437 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 16:51:01.684  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 16:51:01.684  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 16:51:01.684  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 16:51:01.684  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 16:51:01.694  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 16:51:01.704  6000  6000 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 16:51:01.714  1422  1422 W BluetoothHeadset: Proxy not attached to service
08-31 16:51:01.714  1422  1437 I Telecom : BluetoothPhoneService: Result of Message : true
08-31 16:51:01.714  5960  5960 D BluetoothMapService: Received start request. Starting profile...
08-31 16:51:01.714  5960  5960 D BluetoothMapService: start()
08-31 16:51:01.714  5960  5960 D BluetoothMapService: mStartError = false
08-31 16:51:01.714  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.714  5960  5960 D HeadsetStateMachine: Proxy object connected
08-31 16:51:01.714  5960  5960 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 16:51:01.724  5960  5960 D SapService: Received start request. Starting profile...
08-31 16:51:01.724  5960  5960 D SapService: start()
08-31 16:51:01.724  5960  5960 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 16:51:01.724  5960  5960 I bluedroid: get_profile_interface sap
08-31 16:51:01.724  5960  5960 D SapService: mStartError = false
08-31 16:51:01.724  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.724  5960  5960 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 16:51:01.724  5960  5960 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:51:01.724  5960  5999 D HeadsetStateMachine: Disconnected process message: 11
08-31 16:51:01.724  5960  5999 D HeadsetStateMachine: Disconnected process message: 18
08-31 16:51:01.724  5960  5960 D HeadsetPhoneState: Signal level : previous=0 curr=0,
08-31 16:51:01.724  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 16:51:01.724  5960  5960 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:51:01.724  5960  5960 D BluetoothA2dp: Proxy object connected
08-31 16:51:01.724  5960  5960 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 16:51:01.724  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 16:51:01.724  5960  5999 D HeadsetStateMachine: Disconnected process message: 10
,08-31 16:51:01.724  5960  5999 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 16:51:01.724  5993  5993 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 16:51:01.724  5960  5999 D HeadsetStateMachine: Disconnected process message: 11
08-31 16:51:01.724  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,08-31 16:51:01.734  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 16:51:01.734  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 16:51:01.734  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 16:51:01.734  1016  1447 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 16:51:01.734  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 16:51:01.734  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.734  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.734  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.744  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage
08-31 16:51:01.744   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5993
08-31 16:51:01.744   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 16:51:01.744  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
08-31 16:51:01.744  5993  5993 I wpa_supplicant: ssSupport state is = 1
08-31 16:51:01.744  1016  3695 I art     : Explicit concurrent mark sweep GC freed 37212(2MB) AllocSpace objects, 25(400KB) LOS objects, 33% free, 24MB/36MB, paused 3.556ms total 191.761ms
08-31 16:51:01.754  6024  6024 E Zygote  : MountEmulatedStorage()
08-31 16:51:01.754  6024  6024 E Zygote  : v2
08-31 16:51:01.754  1016  1447 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6024 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-31 16:51:01.754  6024  6024 I libpersona: KNOX_SDCARD checking this for 10105
08-31 16:51:01.754  6024  6024 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:01.754  6024  6024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:01.754  5993  5993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.754  5993  5993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.754  5993  5993 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.754  5993  5993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.754  5993  5993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.754  5993  5993 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.754  5993  5993 I wpa_supplicant: Blacklist: Clear (all) 
08-31 16:51:01.754  5993  5993 I wpa_supplicant: wpa_default_ap_write_once
08-31 16:51:01.754  5993  5993 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 16:51:01.754  5993  5993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.754  5993  5993 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 16:51:01.754  5993  5993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.754  5993  5993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.754  6024  6024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:01.754  6024  6024 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:01.754  5993  5993 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:51:01.764  1016  1469 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,08-31 16:51:01.764  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:01.764  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 16:51:01.764  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:01.764  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.764  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.764  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.764  1016  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.774  6024  6024 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:01.774  6024  6024 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:01.784  6035  6035 E Zygote  : MountEmulatedStorage()
08-31 16:51:01.784  6035  6035 E Zygote  : v2
08-31 16:51:01.784  6035  6035 I libpersona: KNOX_SDCARD checking this for 10141
08-31 16:51:01.784  6035  6035 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:01.784  6035  6035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:01.784  1016  1469 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6035 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-31 16:51:01.784  1016  2984 I ActivityManager: Killing 5170:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-31 16:51:01.784  6035  6035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:01.784  6035  6035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:01.804  5993  5993 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 16:51:01.804  6035  6035 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:01.804  6035  6035 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:01.834  6035  6035 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-31 16:51:01.834  6035  6035 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:01.834  6035  6035 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:51:01.834  6035  6035 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 16:51:01.934  5993  5993 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-31 16:51:01.934  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,08-31 16:51:01.944  1016  1077 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.954  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage,
08-31 16:51:01.954   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5993
08-31 16:51:01.954   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 16:51:01.954  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
08-31 16:51:01.954  5993  5993 I wpa_supplicant: ssSupport state is = 1
,08-31 16:51:01.964  5993  5993 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 16:51:01.964  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,08-31 16:51:01.974  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage
,08-31 16:51:01.974   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5993
08-31 16:51:01.974   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 16:51:01.974  5993  5993 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
08-31 16:51:01.974  5993  5993 I wpa_supplicant: ssSupport state is = 1
08-31 16:51:01.974  5993  5993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.974  5993  5993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.974  5993  5993 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.974  5993  5993 I wpa_supplicant: wpa_default_ap_write_once
08-31 16:51:01.974  5993  5993 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 16:51:01.974  5993  5993 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:51:01.974  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.974  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.974  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:01.974  1016  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.984  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.984  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.984  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:02.014   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 16:51:02.014   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:02.014  6024  6060 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 16:51:02.024   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 16:51:02.024   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:02.034  5993  5993 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-31 16:51:02.034  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 16:51:02.044  6024  6060 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 16:51:02.054  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 16:51:02.054  5960  5960 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 16:51:02.054  1016  1447 I ActivityManager: Killing 5503:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-31 16:51:02.054  5960  5986 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 16:51:02.054  5960  5986 I bluedroid: enable
,08-31 16:51:02.064  5960  6070 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-31 16:51:02.064  5960  5986 I bt_hci_bdroid: init
,08-31 16:51:02.064  5960  5986 I bt_vendor: bt-vendor : init
,08-31 16:51:02.064  5960  5986 I bt_vendor: bt-vendor : get_bt_soc_type
,08-31 16:51:02.064  5960  5986 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-31 16:51:02.064  5960  5986 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,08-31 16:51:02.064  5960  5986 D bt_userial_mct: userial_init
,08-31 16:51:02.064  5960  5986 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 16:51:02.064  5960  5986 I bt_vendor: Starting hciattach daemon
08-31 16:51:02.064  5960  5986 I bt_vendor: try to set false
,08-31 16:51:02.074  5960  5986 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-31 16:51:02.074  5960  5986 I bt_vendor: Starting hciattach daemon
08-31 16:51:02.074  5960  5986 I bt_vendor: try to set true
,08-31 16:51:02.084  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:02.094  5993  5993 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-31 16:51:02.094  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 16:51:02.094  5993  5993 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 16:51:02.104  1016  3684 D RCPManagerService: exchangeData() failure , invalid userId,
,08-31 16:51:02.104  1016  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 16:51:02.104  6076  6076 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 16:51:02.114  1016  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-31 16:51:02.114  5653  5665 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
08-31 16:51:02.114  5993  5993 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 16:51:02.114  5993  5993 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 16:51:02.114  5993  5993 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:02.114  5993  5993 E wpa_supplicant: SIM READ ERROR
08-31 16:51:02.114  5993  5993 I wpa_supplicant: Blacklist: Clear (all) ,
,08-31 16:51:02.164  5993  5993 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 16:51:02.164  5653  5665 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-31 16:51:02.164  5653  5665 D BadgeProvider: sendNotify, [notify] : null
,08-31 16:51:02.164  5653  5665 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-31 16:51:02.164  5653  5665 D BadgeProvider: update, [BadgeCount] : badgecount=0
,08-31 16:51:02.164  5653  5665 D BadgeProvider: update, [UpdateCount] : 1
,08-31 16:51:02.164  1477  1477 D Launcher.Model: reloadBadges entered.
,08-31 16:51:02.174  6087  6087 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 16:51:02.184  6088  6088 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 16:51:02.194  1016  1469 D RCPManagerService: exchangeData() failure , invalid userId,
08-31 16:51:02.194  5993  5993 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 16:51:02.204  6090  6090 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
08-31 16:51:02.204  1016  3693 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:02.214  6092  6092 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 16:51:02.224  1016  1129 D WifiConfigStore: Loading config and enabling all networks 
,08-31 16:51:02.224  6094  6094 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 16:51:02.224  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.224  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:02.224  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:02.234  1281  1281 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-31 16:51:02.234  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:02.234  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,08-31 16:51:02.244  5881  5881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:02.244  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:51:02.254  6095  6095 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 16:51:02.254  5881  5881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:51:02.254  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:02.254  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:02.254  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:02.254  1176  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 16:51:02.254  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:02.254  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:02.254  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:02.254  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 16:51:02.264  5881  5881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:51:02.264  1016  1129 E WifiConfigStore: Not a HS20
,08-31 16:51:02.284  1016  1129 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
08-31 16:51:02.294  1176  1176 D HotspotTile: onReceive : 3, 0
,08-31 16:51:02.294  1016  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 16:51:02.304  1016  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 16:51:02.304  5993  5993 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 16:51:02.304  5993  5993 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 16:51:02.304  5993  5993 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 16:51:02.304  5993  5993 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 16:51:02.304  5993  5993 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 16:51:02.304  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 16:51:02.304  5993  5993 I wpa_supplicant: First Scan Start
08-31 16:51:02.304  5993  5993 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 16:51:02.304  1016  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-31 16:51:02.304  1016  1129 D WifiStateMachine: Setting OUI to DA-A1-19
,08-31 16:51:02.304  1016  1129 I WifiNative-HAL: startHal
08-31 16:51:02.304  1016  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9d2fa88c
,08-31 16:51:02.304  1016  1129 I WifiNative-HAL: Could not start hal
,08-31 16:51:02.314  1016  1129 E WifiNative-wlan0: do suspend true
,08-31 16:51:02.314  1016  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 16:51:02.314  1016  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 16:51:02.314  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 16:51:02.314  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-31 16:51:02.314  1016  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:02.314  1016  1150 I WifiNative-HAL: startHal
08-31 16:51:02.314  1016  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e29e9bc
08-31 16:51:02.314  1016  1150 I WifiNative-HAL: Could not start hal
08-31 16:51:02.314  1016  1150 E WifiScanningService: could not start HAL
,08-31 16:51:02.324  1016  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:02.324  1016  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 16:51:02.324  1016  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 16:51:02.324  1016  1129 E WifiNative-wlan0: invaild command id : 215
,08-31 16:51:02.324   278   976 D CommandListener: Setting iface cfg
08-31 16:51:02.324   278   976 D CommandListener: Trying to bring up p2p0
,08-31 16:51:02.324  1016  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 16:51:02.324  1016  1128 D WifiP2pService: P2pEnablingState
,08-31 16:51:02.324  5993  5993 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 16:51:02.334  1016  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 16:51:02.334  5993  5993 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 16:51:02.334  1016  1128 D WifiP2pService: P2p socket connection successful
,08-31 16:51:02.334  1016  1128 D WifiP2pService: P2pEnabledState
,08-31 16:51:02.334  5993  5993 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-31 16:51:02.334  1016  1129 E WifiStateMachine: Failed to set frequency band 0
,08-31 16:51:02.334  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 16:51:02.334  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 16:51:02.334  1016  1128 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,08-31 16:51:02.334  1016  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:02.334  1016  1129 D SecContentProvider2: mCursor = null
,08-31 16:51:02.334  1016  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:02.334  1016  1129 D SecContentProvider2: mCursor = null
,08-31 16:51:02.354  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 16:51:02.354  1016  1046 D WifiDisplayController: disconnect
08-31 16:51:02.354  1016  1046 D WifiDisplayController: updateConnection
08-31 16:51:02.354  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 16:51:02.354  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:02.354  1016  1128 D WifiP2pService: create mNetworkAgent
,08-31 16:51:02.354  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 16:51:02.364  1016  3695 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:02.364  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 16:51:02.374  1016  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 16:51:02.374  1016  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 16:51:02.374  1016  1131 E ConnectivityService: updateNetworkInfo()
,08-31 16:51:02.374  1016  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:02.374  1016  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,08-31 16:51:02.374  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=340 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=338 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=337 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=336 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=335 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=286 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=286 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.384  6024  6024 D StrictMode: StrictMode policy violation; ~duration=285 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:02.384  6024  6024 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:02.394  1016  1128 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 16:51:02.394  1016  1028 I ActivityManager: Killing 5522:com.sec.spp.push/u0a32 (adj 15): empty #21
08-31 16:51:02.394  1016  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-31 16:51:02.394  1016  1128 D WifiP2pService: DeviceAddress: 0a:76:28
08-31 16:51:02.394  1858  1858 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 16:51:02.394  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  secondary type: null
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  wps: 0
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  grpcapab: 0
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  devcapab: 0
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  status: 3
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  wfdInfo: null
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-31 16:51:02.394  1016  1046 D WifiDisplayController:  SConnectInfo : null
08-31 16:51:02.404  1858  1858 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 16:51:02.414  1016  3693 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:02.414  1016  3693 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 16:51:02.414  1016  3693 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.414  1016  3693 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.414  1016  3693 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:02.414  1016  1434 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-31 16:51:02.414  3561  3561 I Hs20UtilService: Starting #2
08-31 16:51:02.414  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.414  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.414  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.414  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.424  3561  3597 I Hs20UtilService: Message received 5011
08-31 16:51:02.424  1016  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
08-31 16:51:02.434  6105  6105 E Zygote  : MountEmulatedStorage()
08-31 16:51:02.434  6105  6105 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:02.434  6105  6105 E Zygote  : v2
08-31 16:51:02.434  6105  6105 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:02.434  6105  6105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:02.434  6105  6105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:02.434  1016  1434 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6105 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 16:51:02.434  6105  6105 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:02.434  1016  1128 D WifiP2pService: InactiveState
08-31 16:51:02.444  5993  5993 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 16:51:02.444  1016  1128 D WifiP2pService: InactiveState{ what=143376 }
08-31 16:51:02.444  1016  1131 E ConnectivityService: updateNetworkInfo()
08-31 16:51:02.444  1016  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
08-31 16:51:02.444  1016  1128 D WifiP2pService: InactiveState{ what=143376 }
08-31 16:51:02.444  1016  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 16:51:02.464  6105  6105 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:02.464  6105  6105 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:02.484  6024  6101 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 16:51:02.494  6120  6120 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-31 16:51:02.504  6121  6121 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 16:51:02.514  6105  6105 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-31 16:51:02.514  6105  6105 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:02.524  6105  6105 D SecurityLogAgent: StateMachine : Current State = 1
08-31 16:51:02.524  6105  6105 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 16:51:02.524  1016  1029 I ActivityManager: Killing 5537:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
08-31 16:51:02.524  5960  5986 I bt_vendor: bluetooth satus is on
08-31 16:51:02.524  5960  6073 D bt_userial_mct: userial_open(port:0)
,08-31 16:51:02.524  5960  6073 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-31 16:51:02.524  5960  6073 I bt_vendor: Done intiailizing UART
,08-31 16:51:02.524  5960  6073 I bt_vendor: Done intiailizing UART
08-31 16:51:02.524  5960  6073 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-31 16:51:02.524  5960  6073 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-31 16:51:02.534  5960  6125 D bt_userial_mct: Entering userial_read_thread()
,08-31 16:51:02.534  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:02.534  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:02.534  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.534  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.534  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 16:51:02.534  3561  3561 I Hs20UtilService: Starting #3
,08-31 16:51:02.534  3561  3597 I Hs20UtilService: Message received 5011
,08-31 16:51:02.544  1016  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 16:51:02.544  1016  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 16:51:02.544  1016  1129 E WifiNative-wlan0: invaild command id : 215
,08-31 16:51:02.544  6105  6105 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 16:51:02.544  6105  6105 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:02.544  6105  6105 D SecurityLogAgent: StateMachine : Current State = 1
08-31 16:51:02.544  6105  6105 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 16:51:02.544  5960  6070 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 16:51:02.554  5960  6070 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 16:51:02.554  5960  6070 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 16:51:02.554  5960  6070 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 16:51:02.554  5960  6070 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 16:51:02.554  1016  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:02.554  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.554  1016  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:02.554  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.554  1281  1281 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 16:51:02.564  1281  1281 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:51:02.564  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 16:51:02.574  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:51:02.574  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 16:51:02.574  1281  1281 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 16:51:02.574  1281  3070 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 16:51:02.574  1016  1078 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 16:51:02.574  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.574  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.574  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.574  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.594  6127  6127 E Zygote  : MountEmulatedStorage()
,08-31 16:51:02.594  6127  6127 E Zygote  : v2
08-31 16:51:02.594  6127  6127 I libpersona: KNOX_SDCARD checking this for 10064
08-31 16:51:02.594  6127  6127 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:02.594  6127  6127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 16:51:02.594  1016  1078 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6127 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:02.594  6127  6127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:02.594  6127  6127 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:02.614  6127  6127 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:02.614  6127  6127 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:02.634  5960  6070 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 16:51:02.634  5960  6070 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41b5ed1 
,08-31 16:51:02.634  5960  6070 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41b5ed1 
,08-31 16:51:02.644  6127  6127 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 16:51:02.644  5960  5989 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 16:51:02.644  5960  5989 E bt-btif : Calling BTA_HhEnable
,08-31 16:51:02.644  5960  5989 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 16:51:02.654  5960  5989 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-31 16:51:02.654  5960  5989 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:51:02.654  5960  5989 I bluedroid: getModelRssiValues
08-31 16:51:02.654  5960  5989 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:51:02.654  5960  5989 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 16:51:02.654  5960  5989 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 16:51:02.654  1016  1016 D SettingsProvider: name = bluetooth_name
,08-31 16:51:02.664  5881  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:02.664  5960  5989 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:51:02.664  5960  5989 D BluetoothAdapterProperties: Scan Mode:20
,08-31 16:51:02.664  5960  5989 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:51:02.664  6127  6127 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:51:02.664  5960  5989 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-31 16:51:02.664  5960  5989 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 16:51:02.664  5960  5989 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 16:51:02.664  5960  5989 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 16:51:02.664  5960  5989 E bt-btif : btif_sock_init: !vhci_init
08-31 16:51:02.664  5960  5989 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 16:51:02.664  6127  6127 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 16:51:02.664  5960  6125 E bt_mct  : hci lib postload completed
,08-31 16:51:02.674  5960  5989 D IOP_DB_BT: db_open: db_open : handle 3026067472l, read 13894 bytes onto local cache
,08-31 16:51:02.674  5960  5989 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-31 16:51:02.674  5960  5989 D IOP_DB_BT: db_query: result 1
,08-31 16:51:02.674  5960  5989 I         : iop_db_open: iop_db_open status 0
,08-31 16:51:02.674  5960  5989 D bte_conf: Device ID record 1 : primary
,08-31 16:51:02.674  5960  5989 D bte_conf:   vendorId            = 0075
08-31 16:51:02.674  5960  5989 D bte_conf:   vendorIdSource      = 0001
08-31 16:51:02.674  5960  5989 D bte_conf:   product             = 0100
08-31 16:51:02.674  5960  5989 D bte_conf:   version             = 0200
08-31 16:51:02.674  5960  5989 D bte_conf:   clientExecutableURL = 
08-31 16:51:02.674  5960  5989 D bte_conf:   serviceDescription  = 
08-31 16:51:02.674  5960  5989 D bte_conf:   documentationURL    = 
08-31 16:51:02.674  5960  5989 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 16:51:02.674  5960  5989 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 16:51:02.674  5960  5986 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 16:51:02.674  5960  5986 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:51:02.674  5960  5986 D BluetoothAdapterProperties: State =  11
,08-31 16:51:02.674  1016  1493 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 16:51:02.684  5881  5881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:51:02.684  5960  5989 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:51:02.684  5960  5989 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:51:02.684  5960  5989 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 16:51:02.684  5960  5986 D BluetoothAdapterProperties: Setting state to 12
08-31 16:51:02.684  5960  5986 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 16:51:02.684  1016  1078 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 16:51:02.684  1016  1078 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:02.684  1016  1078 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:02.684  1016  1078 D SettingsProvider: selectionArgs: false
08-31 16:51:02.684  1016  1078 D SettingsProvider: selectionArgs: 1002
08-31 16:51:02.694  1016  1078 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:02.694  1016  1078 D SettingsProvider: ret = -1
,08-31 16:51:02.694  5881  5881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 16:51:02.694  1016  1078 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:02.694  5960  5986 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:51:02.694  5960  5986 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 16:51:02.694  1016  2985 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:02.694  1016  2985 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.694  1016  2985 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.704  1016  2985 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:02.704  1016  2985 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.704  5881  5881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 16:51:02.704  6127  6127 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 16:51:02.704  5960  5986 D BluetoothAdapterService: Autoconnection is available 
08-31 16:51:02.704  5960  5986 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 16:51:02.704  5960  5986 D BluetoothAdapterService: starting service from this receiver
,08-31 16:51:02.704  1016  1492 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 16:51:02.704  6024  6032 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:02.704  6024  6032 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.714  5881  5881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:02.714  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:51:02.714  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.714  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.714  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.714  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.714  1858  1866 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:02.714  1858  1866 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.714  5881  5881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:51:02.724  1441  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.724  1441  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.724  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.724  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.724  5960  5978 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:02.724  5960  5978 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.724  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 16:51:02.724  5881  5889 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:51:02.724  6146  6146 I libpersona: KNOX_SDCARD checking this for 10065
08-31 16:51:02.724  5881  5889 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.724  6146  6146 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:02.724  5960  5960 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 16:51:02.724  5960  5960 I BluetoothPbapService: Handler(): got msg=1
08-31 16:51:02.724  6146  6146 E Zygote  : MountEmulatedStorage()
08-31 16:51:02.724  6146  6146 E Zygote  : v2
08-31 16:51:02.724  6146  6146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:02.734  1016  1492 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6146 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 16:51:02.734  1016  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:02.734  1016  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 16:51:02.734  6146  6146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:02.734  1016  1447 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 16:51:02.734  1176  1895 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.734  1176  1895 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.734  5960  6008 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:02.734  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.734  1016  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.734  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:02.734  1422  1440 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.734  1422  1440 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.734  1016  1493 I ActivityManager: Killing 5560:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
08-31 16:51:02.734  1460  1639 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.734  1460  1639 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.734  6146  6146 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:02.734  5960  5986 I BluetoothAdapterState: Entering On State from state = 11
,08-31 16:51:02.734  1176  1176 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-31 16:51:02.734  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-31 16:51:02.734  1016  1028 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
08-31 16:51:02.744  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 16:51:02.744  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 16:51:02.744  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:02.744  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-31 16:51:02.744  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 16:51:02.744  5960  6154 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 16:51:02.754  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-31 16:51:02.754  1422  1422 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@47332ff, true
,08-31 16:51:02.754  1777  1777 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 16:51:02.754  1422  1422 D BluetoothHeadset: registerMessageListener
,08-31 16:51:02.764  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 16:51:02.764  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:02.764  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-31 16:51:02.764  1176  1699 D BluetoothTile:  handleUpdatestate:false name:null
08-31 16:51:02.764  1016  1469 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:02.764  1016  1469 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.764  5960  5973 D HeadsetService: registerMessageListener
,08-31 16:51:02.764  1016  1469 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.764  1016  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:02.764  1016  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:02.764  5960  5973 D HeadsetService: registerMessageListener
08-31 16:51:02.764  5881  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:02.764  5960  5999 D HeadsetStateMachine: Disconnected process message: 70
08-31 16:51:02.764  5960  5999 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@27373564
,08-31 16:51:02.764  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 16:51:02.764  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 16:51:02.774  1176  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:02.774  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-31 16:51:02.774  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 16:51:02.774  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 16:51:02.774  6146  6146 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:02.774  6146  6146 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:02.784  1016  1493 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 16:51:02.784  1016  3695 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 16:51:02.784  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 16:51:02.784  1176  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:02.784  5960  6154 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:51:02.784  5960  6154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:02.794  5960  5999 D HeadsetStateMachine: Disconnected process message: 9
,08-31 16:51:02.794  5960  5999 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 16:51:02.794  1016  3693 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.794  5960  6154 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-31 16:51:02.794  5960  6154 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:02.794  5960  6154 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:02.794  5960  6154 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ce443d0
,08-31 16:51:02.794  5960  6154 D BluetoothSocket: channel: 19
,08-31 16:51:02.804  5960  6154 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 16:51:02.804  1016  3684 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.814   283   703 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 16:51:02.814   283   703 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 16:51:02.814   283   703 V voice   : voice_set_parameters: exit with code(-2)
08-31 16:51:02.814   283   703 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 16:51:02.814   283   703 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 16:51:02.814   283   703 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 16:51:02.814   283   703 V audio_hw_primary: adev_set_parameters: exit
08-31 16:51:02.814  5960  5999 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 16:51:02.814  5960  6164 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 16:51:02.824  5960  6164 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:51:02.824  5960  6164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:02.824  5960  6164 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]},
08-31 16:51:02.824  5960  6164 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:02.824  5960  6164 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:02.824  5960  6164 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37e706ce
,08-31 16:51:02.824  5960  6164 D BluetoothSocket: channel: 5
,08-31 16:51:02.834  6146  6146 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:51:02.834  1016  1474 I ActivityManager: Killing 5572:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-31 16:51:02.854  1281  1281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 16:51:02.854  1016  3693 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 16:51:02.854  1016  3693 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.854  1016  3693 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.854  1016  3693 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.854  1016  3693 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 16:51:02.884  1281  1281 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:51:02.894  1281  1281 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:02.894  1016  2985 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 16:51:02.894  1016  2985 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.894  1016  2985 W ActivityManager: userId = 0, bbcId = -10000,
08-31 16:51:02.894  1016  2985 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.894  1016  2985 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.894  1281  1281 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 16:51:02.904  1281  1281 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:51:02.904  1281  1281 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:02.904  1016  1447 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 16:51:02.904  1016  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 16:51:02.904  1016  1447 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.904  1016  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.904  1016  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.904  1281  1281 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 16:51:02.904  1281  1281 D BluetoothMap: Create BluetoothMap proxy object
,08-31 16:51:02.904  1016  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-31 16:51:02.904  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.914  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.914  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:02.914  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.914  1016  1474 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 16:51:02.914  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.914  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.914  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.914  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.924  1281  1281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-31 16:51:02.924  1016  3695 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 16:51:02.924  1016  3695 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.924  1016  3695 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.924  1016  3695 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.924  1016  3695 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.924  1281  1281 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 16:51:02.924  1016  1078 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 16:51:02.924  1016  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.934  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.934  1016  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.934  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.934  1016  1474 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 16:51:02.934  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.934  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.934  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.934  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.934  1281  1281 D LocalBluetoothProfileManager: PANU : true
08-31 16:51:02.934  1281  1281 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
08-31 16:51:02.934  1281  1281 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 16:51:02.944  1281  1281 D DockEventReceiver: finishStartingService: stopping service
,08-31 16:51:02.944  1281  1281 D BluetoothNotiBroadcastReceiver: onReceive
08-31 16:51:02.944  1281  1281 D BluetoothA2dp: Proxy object connected
08-31 16:51:02.944  1281  1281 D A2dpProfile: Bluetooth service connected
,08-31 16:51:02.944  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:51:02.944  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 16:51:02.954  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:02.954  5960  5960 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 16:51:02.954  1281  1281 D HeadsetProfile: Bluetooth service connected
,08-31 16:51:02.954  1016  3693 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:02.954  1016  3693 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
08-31 16:51:02.964  1016  3693 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.964  1016  3693 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:02.964  1016  3693 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.964  1281  1281 D BluetoothMap: Proxy object connected
08-31 16:51:02.964  1281  1281 D MapProfile: Bluetooth service connected
,08-31 16:51:02.964  1281  1281 D BluetoothMap: getConnectedDevices()
,08-31 16:51:02.974  1281  1281 D BluetoothPbap: Proxy object connected
08-31 16:51:02.974  1281  1281 D PbapServerProfile: Bluetooth service connected
,08-31 16:51:02.974  1281  1281 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 16:51:02.974  1281  1281 D SapProfile: Bluetooth service connected
08-31 16:51:02.974  1281  1281 D Bluetoothsap: getConnectedDevices()
,08-31 16:51:02.974  1281  1281 D BluetoothInputDevice: Proxy object connected
,08-31 16:51:02.974  1281  1281 D HidProfile: Bluetooth service connected
,08-31 16:51:02.974  1858  1858 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 16:51:02.974  1016  1078 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:02.974  1016  1078 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.974  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.984  1016  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:02.984  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.984  1281  1281 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:51:02.984  1281  1281 D PanProfile: Bluetooth service connected
,08-31 16:51:02.984  1858  6170 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 16:51:02.984  1858  1858 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 16:51:02.994  1016  1434 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:02.994  1016  1434 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.994  1016  1434 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:02.994  1016  1434 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:03.014  1016  1492 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:51:03.014  1016  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:03.024  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:03.024  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:03.024  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:03.034  1858  6170 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 16:51:03.044  5960  6174 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:51:03.044  5960  6174 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:03.044  5960  6174 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-31 16:51:03.044  5960  6174 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:03.044  5960  6174 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:03.044  5960  6174 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@82cbce8
08-31 16:51:03.044  5960  6174 D BluetoothSocket: channel: 12
08-31 16:51:03.044  5960  6174 I BtOppRfcommListener: Accept thread started.
,08-31 16:51:03.064   291   291 E SMD     : DCD OFF
,08-31 16:51:03.644  5993  5993 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
08-31 16:51:03.644  5993  5993 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:51:03.644  5993  5993 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-31 16:51:03.644  5993  5993 I wpa_supplicant: Trying to associate with  'G700'
08-31 16:51:03.644  5993  5993 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-31 16:51:03.644  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 16:51:03.644  1016  6077 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-31 16:51:03.654  1016  1129 I WifiNative-HAL: startHal
,08-31 16:51:03.654  1016  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9d2fa8ac
08-31 16:51:03.654  1016  1129 I WifiNative-HAL: Could not start hal
,08-31 16:51:03.664  1016  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:51:03.664  1016  1129 D SecContentProvider2: mCursor = null
,08-31 16:51:03.734   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb72807c8
08-31 16:51:03.734   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 16:51:03.734   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 16:51:03.734   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1222113992)
,08-31 16:51:03.754  5993  5993 E wpa_supplicant: Cmd 35605 not handled,
08-31 16:51:03.754  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 16:51:03.754  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.754  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.754  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:03.764  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 16:51:03.754  5993  5993 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 16:51:03.754  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 16:51:03.754  5993  5993 I wpa_supplicant: Associated with F4.99.3E
,08-31 16:51:03.754  5993  5993 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 16:51:03.764  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.754  5993  5993 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 16:51:03.754  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 16:51:03.754  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 16:51:03.754  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:03.764  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.764  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:03.764  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 16:51:03.764  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:51:03.764  1016  1132 E Tethering: No numeric data
08-31 16:51:03.764  1016  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 16:51:03.764  1016  1132 D Tethering: clearTetheredNotification()
08-31 16:51:03.764  1016  1126 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:03.774  5993  5993 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 16:51:03.774  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:03.774  5993  5993 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 16:51:03.774  1176  1176 D HotspotTile: updateTetherState():false, false
08-31 16:51:03.774  5993  5993 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 16:51:03.774  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 16:51:03.774   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:03.774   278   972 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 16:51:03.774  1016  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.774  1016  1129 D SecContentProvider2: mCursor = null
,08-31 16:51:03.774  5993  5993 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:51:03.774  5993  5993 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 16:51:03.774  5993  5993 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 16:51:03.774  5993  5993 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 16:51:03.774  5993  5993 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 16:51:03.774  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 16:51:03.774  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.774  1016  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.774  1016  1129 D SecContentProvider2: mCursor = null
08-31 16:51:03.774  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:51:03.774   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:03.774   278   972 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:03.774  1016  1126 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:03.774  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:03.774  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:03.774  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:03.784   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-31 16:51:03.784   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 16:51:03.784   273   325 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1222113992) wakelock released: 1, error no: 0
08-31 16:51:03.784   273   325 I rmt_storage: 
,08-31 16:51:03.784   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb72807c8
,08-31 16:51:03.784  1016  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 16:51:03.784  1016  1126 V NetworkStats: performPollLocked() took 7ms
,08-31 16:51:03.784  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:03.784  1016  1127 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:03.784  1016  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 16:51:03.794  1016  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 16:51:03.794  1016  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 16:51:03.794  1016  1131 E ConnectivityService: updateNetworkInfo()
08-31 16:51:03.794  1016  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 16:51:03.804  1016  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 16:51:03.804  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:03.804  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:03.804  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.804  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.804  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.804  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.804  1016  1447 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:03.804  1016  1447 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:03.804  1016  1447 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:03.804  1016  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:03.804  1016  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 16:51:03.804  3561  3561 I Hs20UtilService: Starting #4
,08-31 16:51:03.804  3561  3597 I Hs20UtilService: Message received 5007
,08-31 16:51:03.804  1281  1281 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 16:51:03.814  1281  1281 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 16:51:03.814  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 16:51:03.814  1016  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 16:51:03.814  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:51:03.814  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 16:51:03.814  1281  1281 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 16:51:03.814  1281  3070 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 16:51:03.824   278   976 D CommandListener: Setting iface cfg
,08-31 16:51:03.824  1016  1129 E WifiStateMachine: Start Dhcp Watchdog 1
,08-31 16:51:03.834  1016  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:51:03.834  1016  1129 D SecContentProvider2: mCursor = null
,08-31 16:51:03.844  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:03.844  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:03.844  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.844  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.844  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.844  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.844  1016  1129 E WifiNative-wlan0: do suspend false
,08-31 16:51:03.844  1016  1128 D WifiP2pService: InactiveState{ what=143375 },
08-31 16:51:03.844  1016  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 16:51:03.844  1016  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 16:51:03.844  1016  1129 D SecContentProvider2: mCursor = null
,08-31 16:51:04.064  6182  6182 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 16:51:04.064  6182  6182 I dhcpcd  : version 5.5.6 starting,
,08-31 16:51:04.064  6182  6182 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 16:51:04.114  6182  6182 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 16:51:04.114  6182  6182 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 16:51:04.114  6182  6182 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 16:51:04.114  6182  6182 I dhcpcd  : bssid match,
,08-31 16:51:04.114  6182  6182 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-31 16:51:04.194  6182  6182 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-31 16:51:04.274  6182  6182 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-31 16:51:04.454  1016  1129 E WifiNative-wlan0: do suspend true,
,08-31 16:51:04.474  1016  1128 D WifiP2pService: InactiveState{ what=143375 },
08-31 16:51:04.474  1016  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:51:04.484  1016  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 16:51:04.484  1016  1129 E WifiStateMachine: VerifyingLinkState enter
,08-31 16:51:04.484  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:04.484  1016  1131 E ConnectivityService: updateNetworkInfo()
,08-31 16:51:04.484  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 16:51:04.484  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.484  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 16:51:04.484  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.484  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.494  1016  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 16:51:04.494  1016  1131 D ConnectivityService: Adding iface wlan0 to network 502
,08-31 16:51:04.494  1016  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-31 16:51:04.494  1016  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-31 16:51:04.494  1016  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 16:51:04.494  1016  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 16:51:04.494  1016  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,08-31 16:51:04.504  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.504  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:04.504  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.504  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.504  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.504  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.504  1016  3684 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:04.504  1016  3684 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 16:51:04.504  1016  3684 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:04.514  1016  3684 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:04.514  1016  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-31 16:51:04.514  1016  3684 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.514  3561  3561 I Hs20UtilService: Starting #5
,08-31 16:51:04.514  3561  3597 I Hs20UtilService: Message received 5007
,08-31 16:51:04.514  1281  1281 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.524  1281  1281 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:51:04.524  1016  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,08-31 16:51:04.534  1016  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,08-31 16:51:04.534  1016  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,08-31 16:51:04.534  1016  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 16:51:04.534  1016  1131 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
08-31 16:51:04.534  1016  1131 D ConnectivityService: LTETest block dns file not exists
,08-31 16:51:04.534  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 16:51:04.534  1016  1131 V NetworkStats: updateIfacesLocked()
,08-31 16:51:04.534  1016  1131 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:04.534  1016  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:04.534  1016  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:04.544  1016  1131 V NetworkStats: performPollLocked() took 4ms
,08-31 16:51:04.544  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.544  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:04.544  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.544  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.544  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.544  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.554  1016  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:51:04.554  1016  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:51:04.554  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 16:51:04.554  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
,08-31 16:51:04.564  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,08-31 16:51:04.564  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:04.564  1016  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.564   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:04.564   278   972 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:04.564  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.564  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 16:51:04.564  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.564   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:04.564   278   972 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:04.564  1016  1127 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.574  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.574  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.574  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.574  1016  1131 E ConnectivityService: updateNetworkInfo()
08-31 16:51:04.574  1016  1131 E ConnectivityService: updateNetworkInfo()
08-31 16:51:04.574  1016  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 16:51:04.574  1016  1131 V NetworkStats: updateIfacesLocked()
08-31 16:51:04.574  1016  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:04.574  1016  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 16:51:04.574  1016  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:04.574  1016  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:04.574  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:04.574  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:04.574  1016  1131 V NetworkStats: performPollLocked() took 4ms
,08-31 16:51:04.574  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:04.574  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.584  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:04.584  3561  3561 I Hs20UtilService: Starting #6
,08-31 16:51:04.584  1016  1127 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.584  1016  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.584  1016  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.584  1016  6179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:04.584  1016  6179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
,08-31 16:51:04.584  3561  3597 I Hs20UtilService: Message received 5007
,08-31 16:51:04.584  1281  1281 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.584  1281  1281 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 16:51:04.584  1016  6179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:04.584  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 16:51:04.594  1016  6179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-31 16:51:04.594  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:51:04.594  1281  1281 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 16:51:04.594  1281  1281 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 16:51:04.594  1016  1131 D ConnectivityService:    accepting network in place of null
,08-31 16:51:04.594  1016  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:51:04.594  1016  1131 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
08-31 16:51:04.594  1016  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 16:51:04.594  1281  3070 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 16:51:04.594  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-31 16:51:04.594  1460  1460 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:51:04.604  1016  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 16:51:04.604  1016  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,08-31 16:51:04.604  1016  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 16:51:04.604  1016  6179 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 16:51:04.604  1016  6179 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:51:04.604  1016  6179 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 16:51:04.604  1016  6179 I System.out: (HTTPLog)-Thread-174-36806088: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 16:51:04.604  1016  6179 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:04.604   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:04.604   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-31 16:51:04.604  1016  1469 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:04.614  1016  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-31 16:51:04.614  1016  1469 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:04.614  1016  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
08-31 16:51:04.614  1016  1469 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:04.614  1016  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:04.614  1016  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.614  3561  3561 I Hs20UtilService: Starting #7
,08-31 16:51:04.614  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-31 16:51:04.614  1016  1132 D Tethering: MasterInitialState.processMessage what=3
,08-31 16:51:04.614  3561  3597 I Hs20UtilService: Message received 5007
,08-31 16:51:04.614  1176  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:04.614  1016  1126 V NetworkStats: updateIfacesLocked()
08-31 16:51:04.614  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:04.614  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:04.614  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:04.614  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:04.614  1016  1127 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.624  4104  5942 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:04.624  1016  1126 V NetworkStats: performPollLocked() took 5ms
,08-31 16:51:04.624  1281  1281 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.624  1281  1281 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 16:51:04.624  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,08-31 16:51:04.624  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 16:51:04.624  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 16:51:04.624  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-31 16:51:04.624  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-31 16:51:04.624  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 16:51:04.624  1016  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-31 16:51:04.634  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:04.634  1016  1127 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.634  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.634  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.644  1016  1028 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 16:51:04.644  1016  1029 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-31 16:51:04.644  1016  1029 D SecContentProvider2: mCursor = null
,08-31 16:51:04.644  1016  2985 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-31 16:51:04.644  1016  2985 D SecContentProvider2: mCursor = null
,08-31 16:51:04.654  1016  1474 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-31 16:51:04.654  1016  1474 D SecContentProvider2: mCursor = null
,08-31 16:51:04.654  1016  1493 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-31 16:51:04.654  1016  1493 D SecContentProvider2: mCursor = null
,08-31 16:51:04.664  1016  1078 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-31 16:51:04.664  1016  1078 D SecContentProvider2: mCursor = null
,08-31 16:51:04.664  1016  3695 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-31 16:51:04.664  1016  3695 D SecContentProvider2: mCursor = null
,08-31 16:51:04.694   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,08-31 16:51:04.714  1016  1492 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-31 16:51:04.714  1016  6179 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:04.714  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 16:51:04.774  1016  6179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 14:51:04 GMT], X-Android-Received-Millis=[1472655064786], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472655064752]}
,08-31 16:51:04.774  1016  6179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-31 16:51:04.774  1016  6179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-31 16:51:04.774  1016  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.774  1016  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-31 16:51:04.774  1016  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,08-31 16:51:04.784  1016  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.784  1176  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:04.784  1016  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 16:51:04.784  4104  5942 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:04.784  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,08-31 16:51:04.784  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 16:51:04.784  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-31 16:51:04.784  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-31 16:51:04.784  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 16:51:04.794  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.794  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.794  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.914  5881  5936 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:51:04.914  5881  5936 I jxcore-log: 
,08-31 16:51:05.114  1016  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.114  1016  1382 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:05.124  1016  1382 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:05.134  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 16:51:05.134  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.134  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.134  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.134  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 16:51:05.134  5881  5881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 16:51:05.144  5881  5881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 16:51:05.144  6218  6218 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.144  6218  6218 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:05.144  6218  6218 E Zygote  : v2
08-31 16:51:05.144  6218  6218 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:05.144  6218  6218 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.154  6218  6218 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:05.154  1016  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6218 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 16:51:05.154  6218  6218 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.184  6218  6218 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.184  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
08-31 16:51:05.184  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.184  6218  6218 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.194  1858  1858 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-31 16:51:05.194  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-31 16:51:05.194  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.234  6218  6218 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-31 16:51:05.234  6218  6218 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 16:51:05.234  6218  6218 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 16:51:05.254  6218  6218 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 16:51:05.254  6218  6218 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 16:51:05.254  6218  6218 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 16:51:05.254  6218  6218 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.254  1016  2984 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-31 16:51:05.254  1016  2984 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 16:51:05.264  1016  1434 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:05.264  1016  1434 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.264  1016  1434 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:05.264  1016  1434 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:05.264  1016  1434 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:05.274  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 16:51:05.274  1717  1717 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:05.274  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.274  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.274  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.274  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.284  6238  6238 E Zygote  : MountEmulatedStorage(),
08-31 16:51:05.294  6238  6238 E Zygote  : v2
08-31 16:51:05.294  6238  6238 I libpersona: KNOX_SDCARD checking this for 10121
08-31 16:51:05.294  6238  6238 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.294  6238  6238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:05.294  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6238 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,08-31 16:51:05.294  6238  6238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 16:51:05.294  6238  6238 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.294  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 16:51:05.304  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.304  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.304  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.304  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.314  6248  6248 E Zygote  : MountEmulatedStorage(),
08-31 16:51:05.314  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6248 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:05.314  6248  6248 E Zygote  : v2
08-31 16:51:05.314  6248  6248 I libpersona: KNOX_SDCARD checking this for 10001
08-31 16:51:05.314  6248  6248 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:05.314  6248  6248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.324  1016  1474 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-31 16:51:05.324  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.324  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:05.324  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:05.324  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-31 16:51:05.324  6248  6248 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:05.324  6248  6248 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.324  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
08-31 16:51:05.324  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.334  6238  6238 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.334  6238  6238 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.344  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 16:51:05.344  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.344  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.344  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.344  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.344   311   311 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 29.099ms
,08-31 16:51:05.354  2459  2467 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-31 16:51:05.354  6248  6248 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.364  6248  6248 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:05.364   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.541ms
,08-31 16:51:05.374   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.173ms
,08-31 16:51:05.394  6272  6272 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.394  6272  6272 E Zygote  : v2
08-31 16:51:05.394  6272  6272 I libpersona: KNOX_SDCARD checking this for 10031
08-31 16:51:05.394  6272  6272 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.394  6272  6272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.394  6272  6272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 16:51:05.394  1016  1028 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6272 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-31 16:51:05.394  6272  6272 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.404  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
08-31 16:51:05.404  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.424  1717  1717 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-31 16:51:05.424  1717  1717 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-31 16:51:05.424  1717  1717 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-31 16:51:05.424  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:05.434  1717  1717 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:05.434  1717  1717 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 16:51:05.434  1016  3693 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 16:51:05.434  1016  3693 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.434  1016  3693 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.444  6272  6272 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:05.434  1016  3693 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.444  6272  6272 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:05.434  1016  3693 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.444  6238  6238 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:05.444  6238  6238 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 16:51:05.444  6238  6238 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:51:05.454  6288  6288 E Zygote  : MountEmulatedStorage(),
08-31 16:51:05.454  6288  6288 E Zygote  : v2
08-31 16:51:05.454  6288  6288 I libpersona: KNOX_SDCARD checking this for 10077
08-31 16:51:05.454  6288  6288 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.464  6288  6288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.464  1016  3693 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6288 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:05.464  6288  6288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:05.464  6288  6288 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.514  6288  6288 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.514  6288  6288 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.584  1016  1493 I ActivityManager: Killing 5425:com.android.mms/u0a41 (adj 15): empty #21
,08-31 16:51:05.584  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:05.584  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.594  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:05.594  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.594  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:05.614  1016  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 16:51:05.614  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.624  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.624  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.624  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.624  1016  3693 D CountryDetector: No listener is left
,08-31 16:51:05.634  6307  6307 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.634  6307  6307 E Zygote  : v2
08-31 16:51:05.634  6307  6307 I libpersona: KNOX_SDCARD checking this for 10032
08-31 16:51:05.634  6307  6307 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.634  6307  6307 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.634  1016  1474 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6307 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 16:51:05.644  6307  6307 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:05.644  6307  6307 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-31 16:51:05.644  3235  6305 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:05.644  3235  6305 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-31 16:51:05.644  1016  2984 I art     : Explicit concurrent mark sweep GC freed 59675(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.860ms total 182.256ms
,08-31 16:51:05.654  1016  1493 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:05.654  1016  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.654  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:05.654  1016  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.654  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:05.654  1016  3695 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-31 16:51:05.654  1016  3695 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.664  3235  6305 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 16:51:05.664  3235  6305 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,08-31 16:51:05.664  6238  6238 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.664  3235  6305 I DBG_POLICYDM: [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,08-31 16:51:05.674  3235  3389 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,08-31 16:51:05.674  3235  3389 I DBG_POLICYDM: [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT
,08-31 16:51:05.674  6238  6238 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 16:51:05.674  3235  3389 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:05.694  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
08-31 16:51:05.694  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.704  6307  6307 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.704  6307  6307 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.704  6238  6238 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 16:51:05.714  3235  3389 I DBG_POLICYDM: [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 7
,08-31 16:51:05.714  5881  5936 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:51:05.714  5881  5936 I jxcore-log: 
,08-31 16:51:05.724  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
08-31 16:51:05.724  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.724  3235  3389 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,08-31 16:51:05.744  1016  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.744  1016  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.744  1016  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.744  1016  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.744  1016  2985 D RCPManagerService: exchangeData() failure , invalid userId
08-31 16:51:05.744  3235  3389 I DBG_POLICYDM: [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 7
,08-31 16:51:05.754  6328  6328 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.754  6328  6328 E Zygote  : v2
08-31 16:51:05.754  6328  6328 I libpersona: KNOX_SDCARD checking this for 10039
08-31 16:51:05.754  6328  6328 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:05.754  6328  6328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.754  5881  5936 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-31 16:51:05.754  5881  5936 I jxcore-log: 
08-31 16:51:05.764  1016  2984 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:05.764  1016  1040 I ActivityManager: Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=6328 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-31 16:51:05.764  6328  6328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:05.764  6328  6328 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.764  4104  6314 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-31 16:51:05.764  4104  6314 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-31 16:51:05.774  1016  6306 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-31 16:51:05.774  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.774  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.774  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.784  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.794  6328  6328 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.794  6328  6328 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.804  6343  6343 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.804  1016  6306 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=6343 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-31 16:51:05.804  6343  6343 E Zygote  : v2
08-31 16:51:05.804  6343  6343 I libpersona: KNOX_SDCARD checking this for 10009
08-31 16:51:05.804  6343  6343 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.804  6343  6343 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.804  6343  6343 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:05.804  1016  6306 I ActivityManager: Killing 5653:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-31 16:51:05.804  6343  6343 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.814  6307  6350 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-31 16:51:05.814  6307  6350 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 16:51:05.824  1016  6306 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 16:51:05.824  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.824  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.824  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.824  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.834  6307  6307 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-31 16:51:05.834  6343  6343 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.834  6343  6343 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.834  6307  6350 D SPPClientService: PushLog.txt file is not deleted.
,08-31 16:51:05.844  6307  6350 D SPPClientService: PushLog.txt file is not deleted.
,08-31 16:51:05.844  6307  6350 D SPPClientService: ============PushLog. stop!
,08-31 16:51:05.844  6361  6361 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.844  6361  6361 E Zygote  : v2
08-31 16:51:05.844  6361  6361 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:05.844  6361  6361 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:05.844  6361  6361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:05.844  6361  6361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:05.844  6361  6361 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 16:51:05.844  1016  6306 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6361 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 16:51:05.854  1016  2632 D SSRM:n  : SIOP:: AP = 370
,08-31 16:51:05.854  6328  6328 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 16:51:05.854  1016  6306 I ActivityManager: Killing 5672:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-31 16:51:05.854  6328  6328 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:51:05.854  6328  6328 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:51:05.854  6328  6328 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-31 16:51:05.854  6328  6328 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 16:51:05.854  6328  6328 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 16:51:05.854  6328  6328 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 16:51:05.874  1016  6306 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast,
,08-31 16:51:05.874  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.874  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.874  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.874  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.874  6361  6361 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.884  6361  6361 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.884  6376  6376 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.884  6376  6376 I libpersona: KNOX_SDCARD checking this for 10036
08-31 16:51:05.884  6376  6376 E Zygote  : v2
08-31 16:51:05.884  6376  6376 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.894  1016  6306 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=6376 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:05.894  6376  6376 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:05.894  1016  6306 I ActivityManager: Killing 5690:com.wsomacp/u0a23 (adj 15): empty #21
,08-31 16:51:05.894  6376  6376 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:05.894  6376  6376 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.924  6376  6376 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.924  6376  6376 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.924  1858  1858 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:06.024  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:06.044  6328  6328 D NearbySource: Nearby Source Create!
,08-31 16:51:06.044  6328  6328 D NearbyContext: Nearby Context Create!
,08-31 16:51:06.054  6376  6376 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3425e62f
,08-31 16:51:06.064   291   291 E SMD     : DCD OFF
,08-31 16:51:06.064  6343  6343 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-31 16:51:06.084  4104  6396 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,08-31 16:51:06.084  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
,08-31 16:51:06.094   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-31 16:51:06.094   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:06.104  6328  6328 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-31 16:51:06.104  6328  6328 D SLinkSource: Samsung link source created
,08-31 16:51:06.114  6361  6361 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 16:51:06.114  1016  1040 E GpsLocationProvider: No APN found to select.
,08-31 16:51:06.114  6376  6376 I SA      : [SSP] onCreated
,08-31 16:51:06.124  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0,
,08-31 16:51:06.134  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0
,08-31 16:51:06.134  3235  3390 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,08-31 16:51:06.144  3235  3390 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:06.144  1016  1040 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 24442, reason: UserStart, SyncResult: databaseError: true stats []
,08-31 16:51:06.144  1016  1040 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 164149, reason: UserStart
,08-31 16:51:06.164  6376  6376 I SA      : [TPM] There is no property file
,08-31 16:51:06.174  6328  6402 D ContactProvider: getAllContactInfoList Start
,08-31 16:51:06.174  1016  1492 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:06.174  6376  6376 I SA      : [SCU] isHaveSA() - false
,08-31 16:51:06.184  1016  1077 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:06.184  6376  6376 I SA      : [TPM] getModelProperty : null
08-31 16:51:06.184  6376  6376 I SA      : [TPM] getCSCProperty : null
,08-31 16:51:06.184  6376  6376 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-31 16:51:06.184  6376  6376 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 16:51:06.184  6376  6376 I SA      : [DM] TFT FEATURE: false
,08-31 16:51:06.194  6376  6376 I SA      : [DM] init START
,08-31 16:51:06.194  3235  3390 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:51:06.204  3235  3390 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
08-31 16:51:06.204  3235  3389 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
,08-31 16:51:06.204  6376  6376 I SA      : [DM] This device is not a Vodafone
08-31 16:51:06.204  3235  3389 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
,08-31 16:51:06.204  3235  3390 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,08-31 16:51:06.214  3235  3390 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,08-31 16:51:06.214  3235  3390 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,08-31 16:51:06.214  3235  3390 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 16:51:06.224  6376  6376 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-31 16:51:06.224  6376  6376 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-31 16:51:06.234  3235  3390 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,08-31 16:51:06.234  3235  3390 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-31 16:51:06.234  6376  6376 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-31 16:51:06.244  6376  6376 I SA      : [SCU] isHaveSA() - false
08-31 16:51:06.244  6376  6376 I SA      : support phone number id : false
08-31 16:51:06.244  6376  6376 I SA      : [DM] Supports Ref Jpn : true
,08-31 16:51:06.244  6376  6376 I SA      : [DM] init END
08-31 16:51:06.244  6376  6376 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-31 16:51:06.244  6376  6376 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-31 16:51:06.244  6376  6376 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 16:51:06.244  6376  6376 I SA      : [SLFUCHKMGR] constructor called
,08-31 16:51:06.254  1016  1077 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 16:51:06.254  1016  1077 D SecContentProvider2: mCursor = null
,08-31 16:51:06.254  3235  3389 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/09/01/16:26:27
,08-31 16:51:06.264  3235  3389 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/08/31/16:51:06
,08-31 16:51:06.264  3235  3389 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
,08-31 16:51:06.284  1016  1474 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-31 16:51:06.284  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.284  6328  6402 D ContactProvider: getAllContactInfoList End
,08-31 16:51:06.284  6328  6402 I syncContacts: thread: 1128, sync time = 134
,08-31 16:51:06.284  1858  1858 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:06.294  3235  3389 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,08-31 16:51:06.304  6376  6376 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-31 16:51:06.304  6376  6376 I SA      : [OR] == isSIMCardReady false ==
,08-31 16:51:06.314  3235  3390 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0
,08-31 16:51:06.314  1016  1474 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-31 16:51:06.314  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.314  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.314  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.314  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-31 16:51:06.314  6376  6376 I SA      : [SCU] == networkStateCheck == true
,08-31 16:51:06.314  6376  6376 I SA      : [DM] getCountryCodeFromCSC : PL
08-31 16:51:06.314  6376  6376 I SA      : isChinaCountryCode : false
08-31 16:51:06.314  6376  6376 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-31 16:51:06.314  6376  6376 I SA      : [OR] == networkStateCheck true ==
,08-31 16:51:06.334  1016  1492 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast,
,08-31 16:51:06.334  6376  6376 I SA      : [OR] GetMyCountryZoneTask
,08-31 16:51:06.334  6376  6376 I SA      : [OR] onReceive END
,08-31 16:51:06.344  3235  3389 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] 
,08-31 16:51:06.374  6376  6412 I SA      : [SRS] prepareGetMyCountryZone
08-31 16:51:06.374  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.374  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.374  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.374  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.384  1016  1492 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6414 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 16:51:06.384  6414  6414 E Zygote  : MountEmulatedStorage()
08-31 16:51:06.384  6414  6414 I libpersona: KNOX_SDCARD checking this for 10102
08-31 16:51:06.384  6414  6414 E Zygote  : v2
08-31 16:51:06.384  6414  6414 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:06.394  6414  6414 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:06.394  6414  6414 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:06.394  6376  6412 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 16:51:06.394  6414  6414 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:06.394  6376  6412 I SA      : [SSP] query invoked
,08-31 16:51:06.404  1016  1492 I ActivityManager: Killing 5710:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-31 16:51:06.414  3235  3390 I DBG_POLICYDM: [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,08-31 16:51:06.424  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:06.424  1016  1492 I ActivityManager: Killing 5760:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-31 16:51:06.454  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
08-31 16:51:06.454  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.464  6376  6412 I SA      : [TPMU] GetMccFromDB : null,
,08-31 16:51:06.464  6376  6412 I SA      : [SCU] getMccFromPreferece mcc = 260
08-31 16:51:06.464  6376  6412 I SA      : [LBE] isSupportCheckDomainRegion : false
08-31 16:51:06.464  6376  6412 I SA      : [TPM] isNoProxy(default) : true
,08-31 16:51:06.464  6414  6414 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:06.464  6414  6414 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.474  3235  3389 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,08-31 16:51:06.474  6361  6361 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 16:51:06.484  3235  3389 I DBG_POLICYDM: [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,08-31 16:51:06.494  1016  1434 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-31 16:51:06.494  6361  6361 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 16:51:06.494  1016  1434 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.494  6376  6412 E File    : fail readDirectory() errno=2
,08-31 16:51:06.494  1016  1434 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.494  1016  1434 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:06.494  1016  1434 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-31 16:51:06.504  6361  6361 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:06.514  1016  1434 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-31 16:51:06.514  1016  1434 D SecContentProvider2: mCursor = null
,08-31 16:51:06.524  6414  6414 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 16:51:06.524  6361  6361 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:51:06.524  6361  6361 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-31 16:51:06.524  6361  6361 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-31 16:51:06.594  6328  6433 D PicasaService: start picasa sync
,08-31 16:51:06.634  4104  6394 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-31 16:51:06.634  6328  6433 D PicasaService: end picasa sync
,08-31 16:51:06.664  1016  1447 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-31 16:51:06.664  1016  1447 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.664  1016  1447 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.664  1016  1447 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:51:06.664  1016  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-31 16:51:06.674  1016  3684 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-31 16:51:06.674  1016  3684 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.674  1016  3684 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.674  1016  3684 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.674  1016  3684 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.674  3235  3390 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:51:06.694  6436  6436 E Zygote  : MountEmulatedStorage()
08-31 16:51:06.694  6436  6436 E Zygote  : v2
,08-31 16:51:06.694  6436  6436 I libpersona: KNOX_SDCARD checking this for 10008
08-31 16:51:06.694  6436  6436 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:06.694  6436  6436 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:06.694  6436  6436 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:06.694  1016  3684 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6436 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 16:51:06.694  6436  6436 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 16:51:06.704  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:06.704  6343  6343 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
08-31 16:51:06.704  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.704  6343  6343 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
08-31 16:51:06.704  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.704  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.704  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:06.704  6343  6343 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-31 16:51:06.704  6343  6343 D InitializeManagerStateMachine: exit::IDLE
08-31 16:51:06.704  6343  6343 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-31 16:51:06.714  3235  3390 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,08-31 16:51:06.724  6343  6343 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-31 16:51:06.724  6343  6343 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-31 16:51:06.724  6343  6343 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-31 16:51:06.724  6343  6343 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-31 16:51:06.724  6343  6343 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-31 16:51:06.724  6343  6343 D InitializeManagerStateMachine: entry::SUCCESS
08-31 16:51:06.724  6343  6343 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-31 16:51:06.724  1016  1077 I ActivityManager: Killing 5777:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,08-31 16:51:06.734  6436  6436 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:06.734   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-31 16:51:06.734   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 16:51:06.744  6343  6343 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,08-31 16:51:06.744  6436  6436 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.744  4104  6446 I iu.SyncManager: SYNC; picasa accounts
,08-31 16:51:06.744  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-31 16:51:06.754  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.764  6343  6343 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-31 16:51:06.764  6343  6343 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-31 16:51:06.764  6343  6343 D InitializeManagerStateMachine: exit::SUCCESS
08-31 16:51:06.764  6343  6343 D InitializeManagerStateMachine: entry::IDLE
08-31 16:51:06.764  4104  4104 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 16:51:06.764  1016  6306 I ActivityManager: Killing 5792:com.samsung.helphub/1000 (adj 15): empty #21
,08-31 16:51:06.764  4104  4104 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 16:51:06.784  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-31 16:51:06.794  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.794  4104  6446 I iu.UploadsManager: num queued entries: 0
,08-31 16:51:06.794  4104  6446 I iu.UploadsManager: num updated entries: 0
,08-31 16:51:06.794  4104  6446 I iu.SyncManager: NEXT; no task
,08-31 16:51:06.934  1858  6451 I qtaguid : Tagging socket 50 with tag 1000040700000000{268436487,0} for uid -1, pid: 1858, getuid(): 10011
,08-31 16:51:06.954  6436  6436 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 16:51:06.954  6436  6436 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-31 16:51:06.964  6436  6436 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-31 16:51:06.964  1858  6451 I GCM     : GCM config loaded
,08-31 16:51:06.964  6436  6436 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-31 16:51:06.964  1016  1029 I ActivityManager: Killing 5826:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-31 16:51:06.994  3617  3617 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 16:51:06 GMT+02:00 2016
,08-31 16:51:06.994  6414  6463 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-31 16:51:06.994  6414  6463 I Babel_SMS: MmsConfig.loadMmsSettings
08-31 16:51:06.994  6414  6463 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-31 16:51:06.994  6414  6463 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 16:51:06.994  1016  1447 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 16:51:06.994  1016  1447 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.994  1016  1447 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.994  1016  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:06.994  1016  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 16:51:06.994  3617  3617 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:51:07.004  3617  3617 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 16:51:07.014  3617  3617 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:51:07.014  3617  3617 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:51:07.024  3617  6470 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 16:51:07.024  3617  6470 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 16:51:07.024  3617  6470 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-31 16:51:07.024  3617  6470 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-31 16:51:07.034  1016  1447 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:07.034  1016  1447 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.034  1016  1447 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.034  1016  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.034  1016  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.044  3617  6470 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-31 16:51:07.054  6414  6463 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 16:51:07.054  6414  6463 I Babel_SMS: MmsConfig.loadFromResources
,08-31 16:51:07.054  6414  6463 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 16:51:07.054  6414  6463 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 16:51:07.074  3617  6470 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-31 16:51:07.084  3617  6470 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-31 16:51:07.104  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:07.104  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.104  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.104  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.104  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.114  3617  3617 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 16:51:07.124  6414  6428 W art     : Suspending all threads took: 8.641ms
,08-31 16:51:07.174  1016  2984 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-31 16:51:07.174  1016  2984 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.174  1016  2984 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.174  1016  2984 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.174  1016  2984 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.204  1016  3684 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:07.204  1016  3684 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.204  1016  3684 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:07.204  1016  3684 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.214  6414  6414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 16:51:07.214  1016  2985 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:07.224  1016  2985 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.224  1016  2985 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:07.224  1016  2985 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.224  6414  6414 I Babel_Crash: startup - clean
,08-31 16:51:07.264  1016  2646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:51:07.274  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 16:51:07.274  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.274  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.274  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.274  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.284  1016  1474 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-31 16:51:07.284  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.284  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.284  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.284  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.294  6475  6475 E Zygote  : MountEmulatedStorage(),
08-31 16:51:07.294  6475  6475 E Zygote  : v2
08-31 16:51:07.294  6475  6475 I libpersona: KNOX_SDCARD checking this for 10110
08-31 16:51:07.294  6475  6475 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:07.294  6475  6475 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:07.304  1016  1474 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6475 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:07.304  6475  6475 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:07.304  6475  6475 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-31 16:51:07.304  1016  1492 I ActivityManager: Killing 5729:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-31 16:51:07.314  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:07.314  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.314  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.314  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.324  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.324  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.324  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.324  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.334  6475  6475 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:07.334  6475  6475 D ActivityThread: Added TimaKeyStore provider,
,08-31 16:51:07.334  6414  6414 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.344  6490  6490 E Zygote  : MountEmulatedStorage()
08-31 16:51:07.344  6490  6490 E Zygote  : v2
08-31 16:51:07.344  6490  6490 I libpersona: KNOX_SDCARD checking this for 10011
08-31 16:51:07.344  6490  6490 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:07.344  6490  6490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 16:51:07.344  6490  6490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:07.344  6490  6490 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 16:51:07.344  6414  6414 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 16:51:07.344  6414  6414 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 16:51:07.354  1016  1028 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6490 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-31 16:51:07.354  6414  6414 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 16:51:07.354  6414  6414 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 16:51:07.374  6414  6414 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 16:51:07.374   311   311 I art     : Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 23.497ms
,08-31 16:51:07.374  6414  6414 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 16:51:07.384  6414  6414 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 16:51:07.384  6414  6414 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 16:51:07.394  6490  6490 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:07.394  6490  6490 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:07.394   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 18.154ms
,08-31 16:51:07.404  6414  6414 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 16:51:07.404  6490  6490 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 16:51:07.404  6490  6490 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 16:51:07.414  6414  6414 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 16:51:07.414   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 764us total 17.657ms
,08-31 16:51:07.424  6414  6414 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 16:51:07.424  6414  6414 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 16:51:07.424  6414  6414 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 16:51:07.434  6414  6414 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 16:51:07.434  6414  6414 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 16:51:07.434  6414  6414 W VideoCapabilities: Unsupported mime video/mp43
,08-31 16:51:07.444  6414  6414 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 16:51:07.444  6414  6414 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 16:51:07.464  6414  6414 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 16:51:07.494  6490  6490 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 16:51:07.494  6490  6490 I MultiDex: install
,08-31 16:51:07.494  6490  6490 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:51:07.534  1016  2985 I art     : Explicit concurrent mark sweep GC freed 34011(1621KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.832ms total 178.640ms
,08-31 16:51:07.534  6490  6490 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 16:51:07.534  6414  6414 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.564  1016  1149 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,08-31 16:51:07.594  6414  6414 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.594  6414  6414 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.624  6490  6490 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 16:51:07.624  6490  6490 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e165793: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-31 16:51:07.624  6490  6490 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 16:51:07.644  6490  6490 D ChimeraCfgMgr: Reading stored module config,
,08-31 16:51:07.654  6414  6414 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.654  6414  6414 I vclib   : onServiceConnected
,08-31 16:51:07.664  1016  3695 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-31 16:51:07.664  1016  3695 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.664  1016  3695 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.664  1016  3695 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:07.664  1016  3695 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.674  6414  6508 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-31 16:51:07.674  6414  6508 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:07.674  6414  6508 I System.out: (HTTPLog)-Static: isShipBuild true
,08-31 16:51:07.684  6414  6508 I System.out: (HTTPLog)-Thread-1154-206700571: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-31 16:51:07.684  6414  6508 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:07.684   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:07.684   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 10102
,08-31 16:51:07.724  6490  6504 I art     : Background sticky concurrent mark sweep GC freed 28478(1324KB) AllocSpace objects, 2(32KB) LOS objects, 2% free, 7MB/7MB, paused 5.845ms total 69.702ms
,08-31 16:51:07.724  1016  1078 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:07.724  6414  6508 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:07.784  6490  6507 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-31 16:51:07.784  6414  6508 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-31 16:51:07.794  6490  6504 I art     : Background partial concurrent mark sweep GC freed 1019(201KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 7.657ms total 60.587ms
,08-31 16:51:07.814  6490  6490 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 16:51:07.814  6490  6490 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 16:51:07.844  1016  1077 I ActivityManager: Killing 5359:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-31 16:51:07.904   283   703 D WVCdm   : Instantiating CDM.
,08-31 16:51:07.914   283   283 I WVCdm   : CdmEngine::OpenSession
,08-31 16:51:07.914   283   283 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-31 16:51:07.954   283   283 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-31 16:51:07.964  3528  3539 I art     : Explicit concurrent mark sweep GC freed 1598(57KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 708us total 27.404ms
,08-31 16:51:07.984   283   283 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-31 16:51:07.994  1016  1447 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-31 16:51:08.014  1016  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.014  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.024  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.024  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.024  1016  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.024  1016  1493 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:08.024  1016  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.024  1016  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.034   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 16:51:08.034   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.034  6475  6520 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 16:51:08.034   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 16:51:08.034   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.034  6475  6520 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 16:51:08.044   283   283 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-31 16:51:08.044   283   703 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-31 16:51:08.044   283   703 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-31 16:51:08.044   283   703 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-31 16:51:08.044   283   703 D WVCdm   : PrepareKeyRequest: nonce=2375712389
,08-31 16:51:08.084   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 16:51:08.084   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.094  6475  6521 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 16:51:08.104  6475  6475 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 16:51:08.104  6475  6475 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 16:51:08.104  6475  6475 I GAv4    :   adb logcat -s GAv4
,08-31 16:51:08.104  1858  1858 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=2aef27fa-3e04-49fa-a70b-a625f374923f
,08-31 16:51:08.104   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 16:51:08.104   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.104  6475  6521 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 16:51:08.124  1016  1029 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 16:51:08.124  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 16:51:08.134  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:08.134  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.134  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.134  6490  6498 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-31 16:51:08.134  6490  6498 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:08.144  6490  6498 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 16:51:08.144  6490  6498 I System.out: (HTTPLog)-Thread-1156-814006164: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 16:51:08.144  6490  6498 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:08.144   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:08.144   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 16:51:08.144  1858  1858 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:08.144  1858  1858 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:08.174  6475  6475 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:51:08.174  1016  2984 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:08.184   258  5200 I SurfaceFlinger: id=13 Removed Uoast (8/9)
,08-31 16:51:08.184   258  1098 I SurfaceFlinger: id=13 Removed Uoast (-2/9)
,08-31 16:51:08.184  1016  1028 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 136096
,08-31 16:51:08.184  1016  1028 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
08-31 16:51:08.184  1016  1028 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10049}) (elapsedTime=3476)
,08-31 16:51:08.194  6490  6498 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:08.194  6490  6498 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6490, getuid(): 10011
,08-31 16:51:08.204  6475  6475 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:51:08.214  6475  6525 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:51:08.234  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.234  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:08.234  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.234  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.274  6182  6182 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-31 16:51:08.274  6182  6182 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-31 16:51:08.364  1016  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 16:51:08.364  1016  1131 V NetworkStats: updateIfacesLocked()
08-31 16:51:08.364  1016  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:08.364  1016  1131 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:08.364  1016  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 16:51:08.364  1016  1131 V NetworkStats: performPollLocked() took 4ms
08-31 16:51:08.364  1016  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
08-31 16:51:08.374  1176  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:08.374  1016  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:08.374  1176  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:08.374  1016  1127 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:08.374  4104  5942 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:08.374   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:08.374   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-31 16:51:08.384  4104  5942 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:08.414  1016  1469 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:51:08.414  1016  1469 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 16:51:08.414  1016  1469 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 16:51:08.414  1016  1469 D BatteryService: stay LED for fully charged
,08-31 16:51:08.414  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:51:08.424  1016  1016 I MotionRecognitionService: Plugged
,08-31 16:51:08.424  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 16:51:08.424  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:51:08.424  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:51:08.434  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 16:51:08.434  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 16:51:08.454  1016  1127 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472655068280 mCachedNtpElapsedRealtime : 136365 mCachedNtpCertainty : 12,
08-31 16:51:08.454  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-31 16:51:08.454  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:08.454  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 16:51:08.454  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-31 16:51:08.464  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 16:51:08.464  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:51:08.464  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 16:51:08.464  5960  5960 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 16:51:08.464  5960  5999 D HeadsetStateMachine: Disconnected process message: 10
,08-31 16:51:08.464  5881  5936 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:51:08.464  5881  5936 I jxcore-log: 
,08-31 16:51:08.534  6490  6498 I qtaguid : Untagging socket 30
,08-31 16:51:08.674  6475  6475 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 16:51:08.684  5960  5987 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 16:51:08.704  6475  6475 I cr.library_loader: Time to load native libraries: 1 ms (timestamps 6612-6613)
08-31 16:51:08.704  6475  6475 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 16:51:08.724  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.724  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.724  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.724  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.744  6475  6475 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3084bf94}
,08-31 16:51:08.744  6475  6475 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 16:51:08.744  6475  6475 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:51:08.784  6475  6475 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 16:51:08.784  6475  6475 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:51:08.784  6475  6475 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 16:51:08.844  6475  6475 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:51:08.844  6475  6475 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:08.844  6475  6475 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:08.844  6475  6475 I Adreno-EGL: Local Branch: 
08-31 16:51:08.844  6475  6475 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:08.844  6475  6475 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:08.844  6475  6475 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:08.854  5881  5936 I jxcore-log: ERROR runTests: 
08-31 16:51:08.854  5881  5936 I jxcore-log: 
,08-31 16:51:08.854  5881  5936 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:08.854  5881  5936 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 16:51:08.854  5881  5936 I jxcore-log: WARN testUtils: logCallback not set!
08-31 16:51:08.854  5881  5936 I jxcore-log: 
,08-31 16:51:08.874  5881  5936 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _functionName: 'loadFile',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _lineNumber: '26',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _columnNumber: '11',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:51:08.874  5881  5936 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _functionName: '',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _lineNumber: '38',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _columnNumber: '7',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:51:08.874  5881  5936 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _functionName: '',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _lineNumber: '35',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _columnNumber: '3',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:51:08.874  5881  5936 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _lineNumber: '621',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _columnNumber: '8',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:51:08.874  5881  5936 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _lineNumber: '651',
08-31 16:51:08.874  5881  5936 I jxcore-log:     _columnNumber: '1',
08-31 16:51:08.874  5881  5936 I jxcore-log:    
08-31 16:51:08.874  5881  5936 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:51:08.874  5881  5936 I jxcore-log: 
,08-31 16:51:08.874  5881  5936 E jxcore-log: Error: 
08-31 16:51:08.874  5881  5936 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:08.874  5881  5936 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:51:08.874  5881  5936 E jxcore-log: 
08-31 16:51:08.874  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 16:51:08.874  5881  5936 I jxcore-log: 
08-31 16:51:08.884  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:51:08.884  5881  5936 I jxcore-log: 
08-31 16:51:08.884  5881  5936 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 16:51:08.884  5881  5936 I jxcore-log: 
,08-31 16:51:08.894  1016  1474 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-31 16:51:08.894  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-31 16:51:08.894  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.894  1016  1474 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:51:08.894  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-31 16:51:08.974  6376  6412 I SA      : [RC New] Execute method=[GET] start,
08-31 16:51:08.984  6475  6556 W cr.media: Requires BLUETOOTH permission
,08-31 16:51:09.044  6475  6475 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 16:51:09.054  6376  6412 I SA      : [RC New] Security=[true]
,08-31 16:51:09.064   291   291 E SMD     : DCD OFF,
08-31 16:51:09.064  6376  6412 I System.out: Thread-1146(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-31 16:51:09.074  6376  6412 I System.out: Thread-1146(ApacheHTTPLog):isSBSettingEnabled false
08-31 16:51:09.074  6376  6412 I System.out: Thread-1146(ApacheHTTPLog):isShipBuild true
08-31 16:51:09.074  6376  6412 I System.out: Thread-1146(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-31 16:51:09.074  6376  6412 I System.out: Thread-1146(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-31 16:51:09.074  1858  2072 I art     : Explicit concurrent mark sweep GC freed 54214(3MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 11MB/18MB, paused 6.652ms total 371.973ms
,08-31 16:51:09.084  6475  6475 I NSApplication: Starting up...
,08-31 16:51:09.084  1016  2984 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:09.084   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:09.084   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,08-31 16:51:09.094  1016  3695 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 16:51:09.114  1016  6306 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 16:51:09.124  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.124  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.124  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.124  1016  6306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.124  6564  6564 I dex2oat : ----------------------------------------------------
08-31 16:51:09.124  6564  6564 I dex2oat : <SS>: S T A R T I N G . . .
08-31 16:51:09.124  6564  6564 I dex2oat : <SS>: Zip is absent. Canceled.
08-31 16:51:09.124  6564  6564 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 16:51:09.154  6570  6570 E Zygote  : MountEmulatedStorage(),
08-31 16:51:09.154  6570  6570 E Zygote  : v2
08-31 16:51:09.154  6570  6570 I libpersona: KNOX_SDCARD checking this for 10117
08-31 16:51:09.154  6570  6570 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.154  6570  6570 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:09.154  6570  6570 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:09.154  1016  6306 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6570 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 16:51:09.154  6558  6558 D AndroidRuntime: 
08-31 16:51:09.154  6558  6558 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 16:51:09.154  6570  6570 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 16:51:09.154  6558  6558 D AndroidRuntime: CheckJNI is OFF
,08-31 16:51:09.164  6558  6558 D AndroidRuntime: readGMSProperty: start
08-31 16:51:09.164  6558  6558 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:51:09.164  6558  6558 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:51:09.164  6558  6558 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:51:09.164  6558  6558 D AndroidRuntime: readGMSProperty: end
08-31 16:51:09.164  6558  6558 D AndroidRuntime: addProductProperty: start
,08-31 16:51:09.194  6570  6570 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:09.194  6570  6570 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.214  1016  1029 I ActivityManager: Killing 5158:com.android.vending/u0a26 (adj 15): empty #21
,08-31 16:51:09.224  6564  6564 I dex2oat : dex2oat took 94.324ms (threads: 4)
,08-31 16:51:09.234  6490  6498 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:51:09.234  6490  6498 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:09.234  6490  6498 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:09.234  6490  6498 I Adreno-EGL: Local Branch: 
08-31 16:51:09.234  6490  6498 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:09.234  6490  6498 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:09.234  6490  6498 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:09.244  1858  2050 W GCoreFlp: No location to return for getLastLocation()
,08-31 16:51:09.244  6570  6570 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:51:09.284  1016  1434 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:09.284  1016  1434 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:09.284  1016  1434 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:09.284  1016  1434 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:09.294  1016  1077 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:09.294  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:09.294  1016  1077 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:09.294  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:09.304  1016  2984 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:09.304  6558  6558 E AffinityControl: AffinityControl: registerfunction enter
08-31 16:51:09.304  1016  2984 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:09.304  1016  2984 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:09.304  1016  2984 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:09.334  6490  6498 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:51:09.334  6490  6498 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:09.334  6490  6498 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:09.334  6490  6498 I Adreno-EGL: Local Branch: 
08-31 16:51:09.334  6490  6498 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:09.334  6490  6498 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:09.334  6490  6498 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:09.334  6558  6558 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 16:51:09.364  1016  1474 D PackageManager: START PACKAGE DELETE: observer{919967903}
08-31 16:51:09.364  1016  1474 D PackageManager: pkg{<packageName>}
08-31 16:51:09.364  1016  1474 D PackageManager: user{0}
08-31 16:51:09.364  1016  1474 D PackageManager: caller{2000}
08-31 16:51:09.364  1016  1474 D PackageManager: flags{2}
,08-31 16:51:09.364  1016  1474 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-31 16:51:09.364  1016  1474 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-31 16:51:09.364  1016  1474 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-31 16:51:09.364  1016  1474 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 16:51:09.364  1016  1474 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 16:51:09.374  1858  2053 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:51:09.384  4104  6471 D UdcContextInitService: registered all accounts: true
,08-31 16:51:09.384  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-31 16:51:09.384  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-31 16:51:09.384  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-31 16:51:09.384  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-31 16:51:09.384  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 16:51:09.394  1858  2072 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-31 16:51:09.394  1016  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-31 16:51:09.404  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-31 16:51:09.414  1016  1041 I ActivityManager: Killing 5881:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-31 16:51:09.474  1016  1056 W PackageSettings: Skipping PackageSetting{1fa82ab7 com.example.hello/10168} due to missing metadata
,08-31 16:51:09.484  1016  3684 I WindowState: WIN DEATH: Window{9d58c34 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:51:09.484   258  5200 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-31 16:51:09.484   258  1098 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-31 16:51:09.494  1016  3684 D InputDispatcher: Focus left window: 5881
,08-31 16:51:09.494  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 16:51:09.494  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 16:51:09.534  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{2bf2cd28 u0 com.test.thalitest/.MainActivity t2}
,08-31 16:51:09.554  6490  6498 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:51:09.554  6490  6498 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:09.554  6490  6498 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:09.554  6490  6498 I Adreno-EGL: Local Branch: 
08-31 16:51:09.554  6490  6498 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:09.554  6490  6498 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:09.554  6490  6498 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:09.554  1016  1041 D InputDispatcher: Focused application released
,08-31 16:51:09.554  1016  1041 D FocusedStackFrame: Set to : 0
,08-31 16:51:09.554  1016  1041 W ActivityManager: mDVFSHelper.acquire()
,08-31 16:51:09.564  1016  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-31 16:51:09.574  3235  3389 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-31 16:51:09.574  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-31 16:51:09.574  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-31 16:51:09.584  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-31 16:51:09.584  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-31 16:51:09.594  1477  1477 D Launcher: onRestart, Launcher: 844514162
,08-31 16:51:09.594  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-31 16:51:09.604  3235  3249 W art     : Suspending all threads took: 12.292ms
,08-31 16:51:09.634  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 16:51:09.634  1016  6306 W ActivityManager: Spurious death for ProcessRecord{176c9dec 5881:com.test.thalitest/u0a171}, curProc for 5881: null
,08-31 16:51:09.634  1477  1477 D Launcher: onStart, Launcher: 844514162
08-31 16:51:09.634  1477  1477 D Launcher.HomeView: onStart
,08-31 16:51:09.634  1477  1477 D Launcher: onResume, Launcher: 844514162
,08-31 16:51:09.634  1016  1028 D SettingsProvider: name = kids_home_mode
08-31 16:51:09.634  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:09.634  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:09.634  1016  1028 D SettingsProvider: selectionArgs: false
08-31 16:51:09.634  1016  1028 D SettingsProvider: selectionArgs: 10006
08-31 16:51:09.634  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:09.634  1016  1028 D SettingsProvider: ret = -1
08-31 16:51:09.634  1477  1477 D Launcher.HomeView: onResume
,08-31 16:51:09.644  1477  1477 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-31 16:51:09.644  5597  5597 I art     : Explicit concurrent mark sweep GC freed 23553(1252KB) AllocSpace objects, 2(32KB) LOS objects, 49% free, 4MB/8MB, paused 748us total 39.880ms
,08-31 16:51:09.644  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-31 16:51:09.644  3235  3389 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-31 16:51:09.674  3235  3389 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-31 16:51:09.684  1777  1777 E SamsungIME: mOCRHelper is null
,08-31 16:51:09.684  1858  2053 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:51:09.694  1477  1477 D MenuAppsGridFragment: onResume
,08-31 16:51:09.694  1477  1477 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-31 16:51:09.694  1477  1477 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-31 16:51:09.734  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-31 16:51:09.744  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 16:51:09.744  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 16:51:09.744  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 16:51:09.744  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-31 16:51:09.744  1016  1078 D ActivityManager: handle home activity for 0
08-31 16:51:09.744  1016  1078 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-31 16:51:09.744  1016  1078 D KnoxTimeoutHandler: post home show event for user 0
08-31 16:51:09.744  1016  1078 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 16:51:09.744  1016  1078 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 16:51:09.744  1016  1078 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 16:51:09.744  1477  1477 D Launcher.HomeView: onPause
,08-31 16:51:09.754  1477  1477 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-31 16:51:09.754  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:51:09.754  1016  1126 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-31 16:51:09.754  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:09.754  1016  1126 V NetworkStats: performPollLocked(flags=0x3)
,08-31 16:51:09.754  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-31 16:51:09.754  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:09.764  1441  1441 D RegisteredServicesCache: empty dynamic service
,08-31 16:51:09.764  1016  1126 V NetworkStats: performPollLocked() took 8ms
08-31 16:51:09.764  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:09.784   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-31 16:51:09.784  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 16:51:09.794  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:09.794  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:09.794  1016  2985 D InputDispatcher: Focus entered window: 1477
,08-31 16:51:09.804  1477  1477 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 16:51:09.804  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 16:51:09.804  3235  3389 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-31 16:51:09.814  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:51:09.834  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{381c31ce token=android.os.BinderProxy@22cef998 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-31 16:51:09.844  1477  1477 D Launcher.HomeView: onStop
,08-31 16:51:09.844  4104  4104 I art     : Explicit concurrent mark sweep GC freed 14442(1001KB) AllocSpace objects, 17(272KB) LOS objects, 25% free, 13MB/17MB, paused 11.453ms total 251.390ms
,08-31 16:51:09.844  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:51:09.844  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 16:51:09.844  1016  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 16:51:09.854  3235  3389 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:09.884  1016  1492 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 16:51:09.884  1016  1492 D SecContentProvider2: mCursor = null
,08-31 16:51:09.894  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 16:51:09.894  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 16:51:09.914   283   687 I WVCdm   : CdmEngine::CloseSession
,08-31 16:51:09.914  6376  6412 I SA      : [RC New] [v2liruge] api execute + 865
08-31 16:51:09.914  6376  6412 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,08-31 16:51:09.914   283   687 I WVCdm   : L3 Terminate.
,08-31 16:51:09.924  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 16:51:09.924  1016  1028 I ActivityManager: Killing 6105:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-31 16:51:09.924  1016  1046 W ActivityManager: mDVFSHelper.release()
08-31 16:51:09.924  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f5ffafa u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:137838
,08-31 16:51:09.944  6376  6412 I System.out: AsyncTask #1 calls detatch()
,08-31 16:51:09.964  6376  6412 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,08-31 16:51:09.964  1016  2984 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 16:51:09.964  1016  2984 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.974  1016  2984 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:09.974  1016  2984 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:09.974  1016  2984 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:09.974  6376  6412 I SA      : [OCP] update openData : PL
,08-31 16:51:09.994  6376  6412 I SA      : [TPMU] getNetworkMcc : 
,08-31 16:51:09.994  1858  6473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:09.994  6376  6412 I SA      : [SCU] saveMccToPreferece Start
08-31 16:51:09.994  6376  6412 I SA      : [SCU] RegionMCC : 260
08-31 16:51:09.994  6376  6412 I SA      : [SSP] query invoked
,08-31 16:51:10.004   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:10.004   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 16:51:10.004  6376  6412 I SA      : [TPMU] GetMccFromDB : null
,08-31 16:51:10.004  6376  6412 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-31 16:51:10.014  6376  6412 I SA      : [SCU] saveMccToPreferece End
,08-31 16:51:10.014  6376  6412 I SA      : [RC New] executeRequest [v2liruge] end. 1028
08-31 16:51:10.014  6376  6412 I SA      : [RC New] Execute end
,08-31 16:51:10.014  6376  6376 I SA      : [OR] GetMyCountryZoneTask mcc = 260
08-31 16:51:10.014  6376  6376 I SA      : [OR] GetMyCountryZoneTask Success
,08-31 16:51:10.024  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 16:51:10.024  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 16:51:10.024  1016  1077 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 16:51:10.024  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 16:51:10.034  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 16:51:10.034  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-31 16:51:10.034  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-31 16:51:10.034  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 16:51:10.044  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 16:51:10.044  1016  2632 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-31 16:51:10.044  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-31 16:51:10.044  1016  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-31 16:51:10.044  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-31 16:51:10.044  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.044  1858  6473 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:10.044  1858  6473 I qtaguid : Tagging socket 56 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1858, getuid(): 10011
,08-31 16:51:10.064  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.064  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.064  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.104  1858  6473 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1858, getuid(): 10011
,08-31 16:51:10.114  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-31 16:51:10.114  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-31 16:51:10.114  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 16:51:10.114  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-31 16:51:10.154  1016  1056 I art     : Explicit concurrent mark sweep GC freed 41381(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 24MB/36MB, paused 5.885ms total 435.551ms
,08-31 16:51:10.184  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 16:51:10.184  1016  3684 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-31 16:51:10.184  1016  1078 I ActivityManager: Killing 6127:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-31 16:51:10.194  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:10.194  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:10.194  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:10.204  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:10.204  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:10.204  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-31 16:51:10.214  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.224  1016  6306 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 16:51:10.224  1016  6306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 16:51:10.224  1016  6306 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:10.224  1016  6306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:10.224  1016  6306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:10.224  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.234  1016  1312 E Watchdog: !@Sync 4
,08-31 16:51:10.244  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.254  6218  6218 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,08-31 16:51:10.264  1016  1056 D PackageManager: delete codoeFile: 
,08-31 16:51:10.274  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 16:51:10.274  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:10.274  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:10.274  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.274  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-31 16:51:10.304  1016  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-31 16:51:10.304  1016  1056 D PackageManager: result of delete: 1{919967903}
,08-31 16:51:10.304  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.304  6218  6610 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,08-31 16:51:10.304  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.304  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:10.304  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:10.314  6558  6558 D AndroidRuntime: Shutting down VM
,08-31 16:51:10.314  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.314  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:10.314  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:10.324  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.324  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:10.324  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:10.334  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-31 16:51:10.334  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 16:51:10.334  3617  3617 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 16:51:10 GMT+02:00 2016
,08-31 16:51:10.334  1016  1077 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 16:51:10.334  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:10.344  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:10.344  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:10.344  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 16:51:10.354  3617  3617 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:51:10.354  1016  1447 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-31 16:51:10.354  1016  1447 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-31 16:51:10.354  1016  1447 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-31 16:51:10.354  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.354  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.354  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.354  1016  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.364  3617  3617 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 16:51:10.364  3617  3617 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:51:10.364  1016  6306 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 16:51:10.364  1016  6613 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:51:10.374  6614  6614 E Zygote  : MountEmulatedStorage()
,08-31 16:51:10.374  6614  6614 E Zygote  : v2
08-31 16:51:10.374  6614  6614 I libpersona: KNOX_SDCARD checking this for 10090
08-31 16:51:10.374  6614  6614 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:10.374  6218  6610 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
08-31 16:51:10.374  6614  6614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:10.374  1016  6306 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5881 uid 10171
,08-31 16:51:10.374  6614  6614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:10.374  6614  6614 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:10.374  1176  1176 I StatusBar: Icon Only
08-31 16:51:10.374  1016  1447 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6614 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-31 16:51:10.374  1176  1176 D PanelView: There is/are notification(s) 
08-31 16:51:10.374  3617  3617 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-31 16:51:10.384  1016  1434 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:10.384  1016  1434 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
08-31 16:51:10.384  1477  1477 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22cef998 time:138290
08-31 16:51:10.384  6218  6610 I ReactiveServiceManager: Supported : 1
,08-31 16:51:10.384  1777  1777 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-31 16:51:10.384  1016  1434 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:10.384  1016  1434 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:10.384  1016  1434 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:10.384  3617  6612 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 16:51:10.394  3617  6612 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-31 16:51:10.394  1016  1469 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,08-31 16:51:10.394  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-31 16:51:10.394  1016  1469 D QSEECOMAPI: : App is not loaded in QSEE
08-31 16:51:10.394  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.394  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.394  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.394  3617  6612 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-31 16:51:10.394  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.404  3617  6612 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-31 16:51:10.404  1016  1029 I TactileAssist: enable value -1
,08-31 16:51:10.404  1016  1029 I TactileAssist: internal enable value -1
08-31 16:51:10.404  1016  1029 I TactileAssist: intensity value -1
,08-31 16:51:10.404  1016  1029 I TactileAssist: saveAppList value true
,08-31 16:51:10.414  1016  1029 I TactileAssist: List of disabled apps :
,08-31 16:51:10.414  6630  6630 E Zygote  : MountEmulatedStorage()
08-31 16:51:10.414  6630  6630 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:10.414  6630  6630 E Zygote  : v2
08-31 16:51:10.414  6630  6630 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:10.414  6630  6630 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 16:51:10.414  6630  6630 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:10.424  6630  6630 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:10.424  6614  6614 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 16:51:10.424  6614  6614 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:10.424  1016  1469 D QSEECOMAPI: : Loaded image: APP id = 10
,08-31 16:51:10.424  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6630 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 16:51:10.424  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-31 16:51:10.434  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.434  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.434  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.434  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.434  1016  1469 D QSEECOMAPI: : QSEECom_dealloc_memory ,
08-31 16:51:10.434  1016  1469 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
08-31 16:51:10.434  1016  1469 E terrier : handleString: Failed to handle string(-4)
08-31 16:51:10.434  1016  1469 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,08-31 16:51:10.434  6218  6610 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
08-31 16:51:10.434  6218  6610 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,08-31 16:51:10.444  6218  6610 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 16:51:10.444  6218  6610 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 16:51:10.444  6218  6610 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 16:51:10.444  6218  6610 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,08-31 16:51:10.444  6630  6630 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:10.444  6630  6630 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:10.444  6645  6645 E Zygote  : MountEmulatedStorage()
,08-31 16:51:10.444  6645  6645 E Zygote  : v2
08-31 16:51:10.444  6645  6645 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:10.444  6645  6645 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:10.454  6645  6645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:10.454  1016  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6645 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 16:51:10.454  6645  6645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:10.454  6645  6645 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:10.464  3617  6612 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-31 16:51:10.474  1016  1078 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-31 16:51:10.484  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.484  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.484  3617  6612 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-31 16:51:10.484  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.484  1016  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.484  6645  6645 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:10.484  6645  6645 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:10.484  3617  6612 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-31 16:51:10.494  6660  6660 E Zygote  : MountEmulatedStorage()
08-31 16:51:10.494  6660  6660 E Zygote  : v2
08-31 16:51:10.494  6660  6660 I libpersona: KNOX_SDCARD checking this for 10048
08-31 16:51:10.494  6660  6660 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:10.494  6660  6660 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:10.494  1016  1078 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6660 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a,
08-31 16:51:10.504  6660  6660 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:10.504  6660  6660 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 16:51:10.504  6614  6614 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-31 16:51:10.504  3617  3617 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 16:51:10.504  6614  6614 D elm:15121: ELMEngine.ELMEngine( context ).
,08-31 16:51:10.514  6614  6614 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-31 16:51:10.514  1016  2984 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-31 16:51:10.514  1016  2984 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-31 16:51:10.524  1016  2984 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:10.524  1016  2984 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:10.524  1016  2984 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-31 16:51:10.524  6630  6630 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-31 16:51:10.524  6614  6614 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-31 16:51:10.524  6558  6558 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 16:51:10.524  1016  1078 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-31 16:51:10.524  1016  1078 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-31 16:51:10.524  6614  6614 D elm:15121: ElmAgentService : onCreate()
08-31 16:51:10.534  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:10.534  1016  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:10.534  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-31 16:51:10.534  6660  6660 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:10.534  6660  6660 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:10.534  6614  6672 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-31 16:51:10.534  6218  6218 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 16:51:10.534  6218  6218 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 16:51:10.534  6218  6218 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 16:51:10.534  6218  6218 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-31 16:51:10.534  6614  6672 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-31 16:51:10.534  6614  6672 D elm:15121: MDMBridge.getInstance()
08-31 16:51:10.534  6614  6672 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 16:51:10.544  1016  1434 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-31 16:51:10.544  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 16:51:10.544  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.544  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.544  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.554  6614  6672 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 16:51:10.554  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 16:51:10.554  1016  1056 D PackageManager: userId{-1}
08-31 16:51:10.554  1016  1056 D PackageManager: andCode{true}
,08-31 16:51:10.564  6678  6678 E Zygote  : MountEmulatedStorage(),
08-31 16:51:10.564  6678  6678 I libpersona: KNOX_SDCARD checking this for 10029
08-31 16:51:10.564  6678  6678 E Zygote  : v2
08-31 16:51:10.564  6678  6678 I libpersona: KNOX_SDCARD not a persona,
08-31 16:51:10.564  6678  6678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:10.564  6678  6678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 16:51:10.564  1016  1434 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6678 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-31 16:51:10.564  6678  6678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:10.564  1016  1434 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-31 16:51:10.574  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.574  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.574  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.574  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.574  6645  6645 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
08-31 16:51:10.584  1016  1434 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 16:51:10.584  6690  6690 E Zygote  : MountEmulatedStorage()
08-31 16:51:10.584  6690  6690 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:10.584  6690  6690 E Zygote  : v2
08-31 16:51:10.584  6690  6690 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:10.584  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-31 16:51:10.594  6690  6690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:10.594  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.594  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.594  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.594  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.594  6690  6690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:10.594  6690  6690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 16:51:10.604  6678  6678 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:10.604  6703  6703 E Zygote  : MountEmulatedStorage()
08-31 16:51:10.604  6703  6703 E Zygote  : v2
,08-31 16:51:10.604  6703  6703 I libpersona: KNOX_SDCARD checking this for 10003
08-31 16:51:10.604  6703  6703 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:10.604  6678  6678 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:10.614  6703  6703 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 16:51:10.614  6703  6703 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:10.614  1016  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6703 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 16:51:10.614  6703  6703 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:10.614  6614  6614 D elm:15121: ElmAgentService : onDestroy().
,08-31 16:51:10.624  1016  1028 D SecContentProvider2: uri = -1 selection = getSealedState
08-31 16:51:10.624  1016  1028 D SecContentProvider2: mCursor = null
08-31 16:51:10.624  6645  6645 I PopupuiReceiver_KNOX: getSealedState : true
,08-31 16:51:10.624  1016  1077 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages,
08-31 16:51:10.624  1016  1077 D SecContentProvider2: mCursor = null
08-31 16:51:10.624  6645  6645 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-31 16:51:10.624  1016  1492 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-31 16:51:10.624  1016  1492 D SecContentProvider2: mCursor = null
,08-31 16:51:10.624  6645  6645 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,08-31 16:51:10.624  6645  6645 D PopupuiReceiver: Action package removed
,08-31 16:51:10.634  6690  6690 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:10.634  6690  6690 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:10.634  1016  1029 I ActivityManager: Killing 6146:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-31 16:51:10.634  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-31 16:51:10.644  6703  6703 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:10.644  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.644  6703  6703 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:10.644  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.644  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.644  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.654  6690  6690 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:10.664  6724  6724 E Zygote  : MountEmulatedStorage()
,08-31 16:51:10.664  6724  6724 E Zygote  : v2
08-31 16:51:10.664  6724  6724 I libpersona: KNOX_SDCARD checking this for 10145
08-31 16:51:10.664  6724  6724 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:10.664  6660  6660 D Compatibility: onReceive() it will make start service
08-31 16:51:10.664  1016  1029 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6724 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:10.664  1016  1029 I ActivityManager: Killing 6000:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-31 16:51:10.664  6724  6724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 16:51:10.664  1016  2985 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-31 16:51:10.664  1016  2985 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-31 16:51:10.674  1016  2985 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:10.674  1016  2985 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:10.674  1016  2985 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-31 16:51:10.674  6724  6724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 16:51:10.674  6724  6724 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:10.674  1016  1493 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-31 16:51:10.674  1016  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.674  1858  2072 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-31 16:51:10.674  1016  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.674  1016  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.674  1016  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:10.684  6660  6731 D Compatibility: onHandleIntent()
,08-31 16:51:10.694  6660  6731 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-31 16:51:10.694  1858  2072 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-31 16:51:10.694  6744  6744 E Zygote  : MountEmulatedStorage()
,08-31 16:51:10.704  6744  6744 E Zygote  : v2
08-31 16:51:10.704  6744  6744 I libpersona: KNOX_SDCARD checking this for 10052
08-31 16:51:10.704  6744  6744 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:10.704  1016  1493 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6744 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-31 16:51:10.704  6744  6744 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 16:51:10.704  6660  6731 D Compatibility: found: 2
,08-31 16:51:10.714  6724  6724 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:10.714  6724  6724 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:10.714  1016  1029 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,08-31 16:51:10.714  6744  6744 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 16:51:10.724  6744  6744 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:10.724  6690  6690 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-31 16:51:10.724  6660  6731 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-31 16:51:10.734  1016  3693 I ActivityManager: Killing 6024:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-31 16:51:10.734  6660  6731 D Compatibility: skipping ResolveInfo{b9dc5c5 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-31 16:51:10.734  6660  6731 D Compatibility: considering ResolveInfo{3fcd6b1a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-31 16:51:10.734  6660  6731 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-31 16:51:10.734  6660  6731 D Compatibility: enabling receiver ResolveInfo{3134b64b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-31 16:51:10.744  6660  6731 D Compatibility: enabling receiver ResolveInfo{bfea828 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-31 16:51:10.754  6744  6744 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:10.754  6744  6744 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:10.754  6660  6731 D Compatibility: enabling receiver ResolveInfo{2999f941 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-31 16:51:10.754  1858  6742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:10.764  1858  1858 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/ns.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 16:51:10.764   278   972 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 16:51:10.764   278   972 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-31 16:51:10.764  6660  6731 D Compatibility: enabling receiver ResolveInfo{29c71ee6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-31 16:51:10.764  6678  6753 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-31 16:51:10.764  6660  6731 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-31 16:51:10.764  1858  6742 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:10.764  1858  6742 I qtaguid : Tagging socket 66 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1858, getuid(): 10011
,08-31 16:51:10.774  1016  1493 I ActivityManager: Killing 6238:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-31 16:51:10.774  1858  1858 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at ivh.c(:com.google.android.gms:19519)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at oek.a(:com.google.android.gms:284)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at oeh.d(:com.google.android.gms:1080)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at oeh.a(:com.google.android.gms:482)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at oei.a(:com.google.android.gms:25054)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at oei.handleMessage(:com.google.android.gms:179)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:10.774  1858  1858 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:10.774  1858  1858 D AndroidRuntime: Shutting down VM
,08-31 16:51:10.784  1016  1447 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-31 16:51:10.784  1016  1447 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-31 16:51:10.784  1016  1434 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-31 16:51:10.794  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.794  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.794  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:10.794  1016  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
