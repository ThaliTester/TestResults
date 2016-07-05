#### Test 72145431fb64fa4_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-05 12:50:23.481   291   291 E SMD     : DCD OFF
07-05 12:50:24.491   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,--------- beginning of system
07-05 12:50:24.661  1014  3527 D SSRM:n  : SIOP:: AP = 310
07-05 12:50:24.761  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
07-05 12:50:24.761  1014  1046 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-05 12:50:24.761  1014  1046 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-05 12:50:24.761  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.notifications.GunsService' (uid=10011, pid=2029, ws=null) (elapsedTime=59794)
07-05 12:50:24.781  6675  6675 D AndroidRuntime: 
07-05 12:50:24.781  6675  6675 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:50:24.781  6675  6675 D AndroidRuntime: CheckJNI is OFF
07-05 12:50:24.781  6675  6675 D AndroidRuntime: readGMSProperty: start
07-05 12:50:24.781  6675  6675 D AndroidRuntime: readGMSProperty: already setted!!
07-05 12:50:24.781  6675  6675 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 12:50:24.781  6675  6675 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 12:50:24.781  6675  6675 D AndroidRuntime: readGMSProperty: end
07-05 12:50:24.781  6675  6675 D AndroidRuntime: addProductProperty: start
07-05 12:50:24.911  6675  6675 E AffinityControl: AffinityControl: registerfunction enter
07-05 12:50:24.931  6675  6675 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 12:50:24.951  1014  1134 E PersonaManagerService: inState():  stateMachine is null !!
07-05 12:50:24.951  1014  1134 I PersonaManagerService: PersonaId don't exist
07-05 12:50:24.951  1014  1134 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 12:50:24.951  1014  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:50:24.961  1014  1134 W ActivityManager: mDVFSHelper.acquire()
07-05 12:50:24.971  1014  1134 D FocusedStackFrame: Set to : 0
07-05 12:50:24.981  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-05 12:50:24.981  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-05 12:50:24.981  1014  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:24.981  1014  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:24.981  1014  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:24.991  1014  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:25.001  6686  6686 E Zygote  : MountEmulatedStorage()
07-05 12:50:25.001  6686  6686 E Zygote  : v2
07-05 12:50:25.001  6686  6686 I libpersona: KNOX_SDCARD checking this for 10170
07-05 12:50:25.001  6686  6686 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:25.001  1014  1134 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6686 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:50:25.001  6686  6686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:50:25.001  1014  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 12:50:25.001  1014  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:50:25.001  1014  1134 D InputDispatcher: Focused application set to: xxxx
07-05 12:50:25.001  1014  1134 D InputDispatcher: Focus left window: 1476
07-05 12:50:25.001  6675  6675 D AndroidRuntime: Shutting down VM
07-05 12:50:25.001  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-05 12:50:25.001  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-05 12:50:25.001  6686  6686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:25.001   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-05 12:50:25.001  6686  6686 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 12:50:25.021  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 12:50:25.021  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 12:50:25.021  6686  6686 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:25.021  6686  6686 D ActivityThread: Added TimaKeyStore provider
07-05 12:50:25.021  1014  3880 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-05 12:50:25.031  1014  1014 V ActivityManager: Display changed displayId=0
07-05 12:50:25.031  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:50:25.041  1014  3880 D PersonaManager: isKioskContainerExistOnDevice
07-05 12:50:25.061  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-05 12:50:25.091   258  1094 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-05 12:50:25.091   258  1095 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-05 12:50:25.091  1476  1476 V ActivityThread: updateVisibility : ActivityRecord{3ce707ef token=android.os.BinderProxy@b49e72d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 12:50:25.091  1476  1476 D Launcher: onTrimMemory. Level: 20
07-05 12:50:25.151  6686  6686 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 12:50:25.171  6686  6686 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 4450-4451)
07-05 12:50:25.171  6686  6686 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:25.191  6686  6686 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3eafd740}
07-05 12:50:25.191  6686  6686 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:25.191  6686  6686 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:50:25.211  6675  6675 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-05 12:50:25.231  6686  6686 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-05 12:50:25.231  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:25.231  6686  6686 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 12:50:25.251  6686  6686 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-05 12:50:25.251  6686  6686 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-05 12:50:25.251  6686  6686 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-05 12:50:25.261  6686  6686 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 12:50:25.261  6686  6686 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 12:50:25.261  6686  6686 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 12:50:25.261  6686  6686 I Adreno-EGL: Local Branch: 
07-05 12:50:25.261  6686  6686 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 12:50:25.261  6686  6686 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 12:50:25.261  6686  6686 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-05 12:50:25.461  6686  6712 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-05 12:50:25.491   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:25.511  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:25.521  6686  6686 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 12:50:25.531  6686  6686 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-05 12:50:25.531  6686  6686 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-05 12:50:25.541  6686  6686 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 12:50:25.541  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:25.541  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:50:25.551  1014  1039 W ActivityManager: Activity pause timeout for ActivityRecord{189b1d59 u0 com.test.thalitest/.MainActivity t43}
,07-05 12:50:25.611  6686  6725 D OpenGLRenderer: Render dirty regions requested: true
,07-05 12:50:25.621  1014  1217 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-05 12:50:25.621  1014  1217 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 12:50:25.621  1014  1217 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 12:50:25.621  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-05 12:50:25.621  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 12:50:25.631  6686  6686 V ActivityThread: updateVisibility : ActivityRecord{1dd7852b token=android.os.BinderProxy@2a8781a5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 12:50:25.631  6686  6686 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-05 12:50:25.631  6686  6686 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-05 12:50:25.641   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-05 12:50:25.641  1014  1026 D InputDispatcher: Focus entered window: 6686
,07-05 12:50:25.651  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
07-05 12:50:25.651  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 12:50:25.651  6686  6686 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-05 12:50:25.651  6686  6725 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 12:50:25.651  6686  6725 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
07-05 12:50:25.661  6686  6725 D OpenGLRenderer: Enabling debug mode 0
,07-05 12:50:25.671  1014  1474 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 12:50:25.671  1014  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:50:25.681  1177  1177 I StatusBar: Icon Only
,07-05 12:50:25.681  1177  1177 D PanelView: There is/are notification(s) 
,07-05 12:50:25.681  6686  6686 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a8781a5 time:114964
,07-05 12:50:25.691  6686  6686 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-05 12:50:25.701  1014  1044 I ActivityManager: Displayed Component not be shown by security: +655ms (total +719ms)
,07-05 12:50:25.701  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{189b1d59 u0 com.test.thalitest/.MainActivity t43} time:114988
,07-05 12:50:25.701  1014  1044 W ActivityManager: mDVFSHelper.release()
,07-05 12:50:25.711   258  1094 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,07-05 12:50:25.711   258  1865 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-05 12:50:25.731  1858  1858 I SamsungIME: getCurrentCandidateView
,07-05 12:50:25.811  6686  6686 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6686
,07-05 12:50:25.851  1858  1858 D SamsungIME: Dismiss ExpandCandiate
,07-05 12:50:25.871  5815  5815 D FactoryTest: Not factory mode
07-05 12:50:25.871  5815  5815 D FactoryTest: Not factory mode. isFactoryMode() returend false
07-05 12:50:25.871  5815  5815 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
07-05 12:50:25.871  5815  5815 D MTPRx   : still no open session command from host, so toast
07-05 12:50:25.881  5815  5815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
07-05 12:50:25.881  5815  5815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
07-05 12:50:25.881  5815  5815 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115162
07-05 12:50:25.881  1014  3802 E PersonaManagerService: inState():  stateMachine is null !!
07-05 12:50:25.881  1014  3802 I PersonaManagerService: PersonaId don't exist
07-05 12:50:25.881  1014  3802 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 12:50:25.881  1014  3802 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
07-05 12:50:25.881  1014  3802 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:25.881  1014  3802 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:25.881  1014  3802 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,07-05 12:50:25.891  1014  3802 W ActivityManager: mDVFSHelper.acquire(),
,07-05 12:50:25.901  1014  3802 D PersonaManager: isKioskContainerExistOnDevice
,07-05 12:50:25.921  1014  3802 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:50:25.921  1014  3802 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,07-05 12:50:25.921  1014  3802 D InputDispatcher: Focused application set to: xxxx
07-05 12:50:25.921  1014  3802 D InputDispatcher: Focus left window: 6686
,07-05 12:50:25.921  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-05 12:50:25.921  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 12:50:25.931  5815  5815 E MTPRx   : started activity for popup
,07-05 12:50:25.961  5815  5815 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
07-05 12:50:25.961  5815  5815 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,07-05 12:50:25.961  5815  5815 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 12:50:25.961  5815  5815 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:50:25.961  5815  5815 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 12:50:25.961  5815  5815 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-05 12:50:25.971  6686  6686 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 12:50:25.981  5815  5815 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,07-05 12:50:25.981  1014  1747 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,07-05 12:50:25.981  1014  1747 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:50:25.981  1014  1747 D InputDispatcher: Focused application set to: xxxx
,07-05 12:50:25.991  1014  1747 D InputDispatcher: Focus entered window: 6686
,07-05 12:50:25.991  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-05 12:50:25.991  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 12:50:25.991  1014  1474 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 12:50:25.991  1014  1474 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@30951356 attribute=null, token = android.os.BinderProxy@245ebc00
,07-05 12:50:26.041  1858  1858 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 12:50:26.051  5815  5815 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,07-05 12:50:26.061  5815  5815 D PhoneWindow: *FMB* installDecor mIsFloating : true
07-05 12:50:26.061  5815  5815 D PhoneWindow: *FMB* installDecor flags : 8388610
,07-05 12:50:26.081  1858  1858 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 12:50:26.091  1014  3802 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 12:50:26.091  1014  3802 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 12:50:26.091  1014  3802 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 12:50:26.091  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 12:50:26.091  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-05 12:50:26.091  1858  1858 I SamsungIME: KeybaordView init() : load resources
,07-05 12:50:26.101  6686  6730 D jxcore_app_log: JniHelper::setJavaVM(0xb7e7b2f0), pthread_self() = -1203938576
,07-05 12:50:26.101  6686  6686 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a8781a5 time:115388
,07-05 12:50:26.111  6686  6686 V ActivityThread: updateVisibility : ActivityRecord{1dd7852b token=android.os.BinderProxy@2a8781a5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 12:50:26.111  6686  6730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:50:26.111  6686  6730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:50:26.111  6686  6730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:50:26.111  6686  6730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:50:26.111  6686  6730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 12:50:26.111  6686  6730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e80f1b added. We now have 1 listener(s)
,07-05 12:50:26.121  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
,07-05 12:50:26.121  6686  6730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,07-05 12:50:26.121  6686  6730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,07-05 12:50:26.121  6686  6730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 12:50:26.121  6686  6730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:50:26.121  6686  6730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45da9f6 added. We now have 1 listener(s)
,07-05 12:50:26.121  6686  6730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 12:50:26.131  1858  1858 I SamsungIME: getCurrentKeyboard
07-05 12:50:26.131  1858  1858 I SamsungIME: getTextKeyboard
07-05 12:50:26.131  6686  6730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-05 12:50:26.131  6686  6730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 12:50:26.131  6686  6730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 12:50:26.131  6686  6730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 12:50:26.131  6686  6730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 12:50:26.141  6686  6730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 12:50:26.141  6686  6730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27,
,07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:26.141  6686  6730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 12:50:26.141  6686  6730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:50:26.141  6686  6730 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 12:50:26.141  6686  6730 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 12:50:26.151  6686  6686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:50:26.161  6686  6686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:50:26.171  1858  1858 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 12:50:26.191  6686  6686 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:50:26.481   291   291 E SMD     : DCD OFF
,07-05 12:50:26.491   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:26.721  6686  6736 W jxcore-log: Initializing JXcore engine
07-05 12:50:26.721  6686  6736 W jxcore-log: JXcore engine is ready
,07-05 12:50:26.771  2018  2018 E audit   : type=1400 msg=audit(1467715826.771:205): avc:  denied  { ioctl } for  pid=6736 comm="Thread-1208" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 12:50:26.771  2018  2018 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:26.771  2018  2018 E audit   : type=1300 msg=audit(1467715826.771:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f8808f8 items=0 ppid=307 ppcomm=main pid=6736 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1208" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 12:50:26.771  2018  2018 E audit   : type=1320 msg=audit(1467715826.771:205): 
,07-05 12:50:26.781  6686  6736 W jxcore-log: Starting JXcore engine
,07-05 12:50:26.881  6686  6736 W jxcore-log: Platform android
07-05 12:50:26.881  6686  6736 W jxcore-log: 
07-05 12:50:26.881  6686  6736 W jxcore-log: Process ARCH arm
07-05 12:50:26.881  6686  6736 W jxcore-log: 
,07-05 12:50:26.951  1014  1342 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:50:26.951  1014  1342 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-05 12:50:26.951  1014  1342 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:50:26.951  1014  1342 D BatteryService: stay LED for fully charged
07-05 12:50:26.951  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:50:26.961  1014  1014 I MotionRecognitionService: Plugged
,07-05 12:50:26.961  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:50:26.961  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:50:26.961  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:50:26.961  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:50:26.961  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:50:26.971  3399  3399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:50:26.971  3399  3493 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:50:26.981  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:50:26.981  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:50:26.981  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:50:27.091  6686  6736 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:50:27.091  6686  6736 I jxcore-log: 
,07-05 12:50:27.091  6686  6736 W jxcore-log: JXcore engine is started
,07-05 12:50:27.101  6686  6730 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 12:50:27.101  6686  6686 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 12:50:27.111  6686  6736 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-05 12:50:27.111  6686  6736 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-05 12:50:27.111  6686  6686 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-05 12:50:27.121  6686  6686 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
07-05 12:50:27.121  1014  1134 D FocusedStackFrame: Set to : 0
07-05 12:50:27.121  1014  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:50:27.121  1014  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 12:50:27.121  1014  1134 D InputDispatcher: Focused application set to: xxxx
,07-05 12:50:27.121  1014  1134 D InputDispatcher: Focus left window: 6686
07-05 12:50:27.121  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 12:50:27.121  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 12:50:27.121  1014  1134 I ActivityManager: Killing 6007:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
07-05 12:50:27.131  6686  6686 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-05 12:50:27.131  6686  6686 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-05 12:50:27.131  6686  6686 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-05 12:50:27.131  6686  6686 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-05 12:50:27.131  6686  6686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-05 12:50:27.131  6686  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-05 12:50:27.131  6686  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e80f1b removed from the list
07-05 12:50:27.131  6686  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-05 12:50:27.131  6686  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45da9f6 removed from the list
07-05 12:50:27.131  6686  6686 D io.jxcore.node.ConnectivityMonitor: stop
07-05 12:50:27.131  6686  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-05 12:50:27.131  6686  6686 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-05 12:50:27.141   258   450 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-05 12:50:27.151   258  1865 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-05 12:50:27.161  1014  1469 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-05 12:50:27.181  1476  1476 D Launcher: onRestart, Launcher: 123414380
,07-05 12:50:27.181  1476  1476 D Launcher: onStart, Launcher: 123414380
,07-05 12:50:27.181  1476  1476 D Launcher.HomeView: onStart
,07-05 12:50:27.181  1476  1476 D Launcher: onResume, Launcher: 123414380
,07-05 12:50:27.181  1014  1475 D SettingsProvider: name = kids_home_mode
,07-05 12:50:27.181  1014  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-05 12:50:27.181  1014  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-05 12:50:27.181  1014  1475 D SettingsProvider: selectionArgs: false
,07-05 12:50:27.181  1014  1475 D SettingsProvider: selectionArgs: 10006
07-05 12:50:27.181  1014  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-05 12:50:27.181  1014  1475 D SettingsProvider: ret = -1
,07-05 12:50:27.181  1476  1476 D Launcher.HomeView: onResume
,07-05 12:50:27.191  1476  1476 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,07-05 12:50:27.191  1476  1476 D MenuAppsGridFragment: onResume,
,07-05 12:50:27.201  1476  1476 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-05 12:50:27.201  1476  1476 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-05 12:50:27.201  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:27.201  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.201  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-05 12:50:27.201  1014  1747 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-05 12:50:27.201  1014  1747 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-05 12:50:27.201  1014  1747 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.201  1014  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.201  1014  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
07-05 12:50:27.201  1014  1747 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-05 12:50:27.221  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.221  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.221  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.221  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:27.231  6741  6741 E Zygote  : MountEmulatedStorage()
,07-05 12:50:27.231  6741  6741 E Zygote  : v2
07-05 12:50:27.231  6741  6741 I libpersona: KNOX_SDCARD checking this for 10039
07-05 12:50:27.231  6741  6741 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:27.231  1014  1747 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6741 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
07-05 12:50:27.231  6741  6741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:27.231  1014  1469 D ActivityManager: handle home activity for 0
07-05 12:50:27.231  1014  1469 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-05 12:50:27.231  1014  1469 D KnoxTimeoutHandler: post home show event for user 0
07-05 12:50:27.231  1014  1469 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 12:50:27.231  1014  1469 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 12:50:27.231  1014  1469 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 12:50:27.241  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-05 12:50:27.241  1476  1476 D Launcher.HomeView: onPause
07-05 12:50:27.241  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-05 12:50:27.241  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 12:50:27.241  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-05 12:50:27.241  1476  1476 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-05 12:50:27.241  6741  6741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:27.241  6741  6741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:50:27.241  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-05 12:50:27.241  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.241  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.241  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.241  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.241  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-05 12:50:27.241  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.241  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:27.241  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.241  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.241  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,07-05 12:50:27.261  6752  6752 E Zygote  : MountEmulatedStorage()
,07-05 12:50:27.261  6752  6752 E Zygote  : v2
07-05 12:50:27.261  6752  6752 I libpersona: KNOX_SDCARD checking this for 10089
07-05 12:50:27.261  6752  6752 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:27.261  6752  6752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:27.261  1014  1039 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6752 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a,
07-05 12:50:27.271  6752  6752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:27.271  6752  6752 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-05 12:50:27.271  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.271  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-05 12:50:27.271  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-05 12:50:27.271  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-05 12:50:27.271  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-05 12:50:27.271  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.271  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.271  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:27.281  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:27.281  6741  6741 D ActivityThread: Added TimaKeyStore provider
07-05 12:50:27.291  6770  6770 E Zygote  : MountEmulatedStorage()
07-05 12:50:27.291  6770  6770 E Zygote  : v2
07-05 12:50:27.291  6770  6770 I libpersona: KNOX_SDCARD checking this for 10139
07-05 12:50:27.291  6770  6770 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:27.291  6770  6770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:50:27.291  1014  1039 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6770 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
07-05 12:50:27.291  6770  6770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:27.301  6770  6770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:50:27.301  6752  6752 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:27.301  6752  6752 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:27.321  6770  6770 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:27.321  6770  6770 D ActivityThread: Added TimaKeyStore provider
07-05 12:50:27.321   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
07-05 12:50:27.321  1014  1134 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.321  1014  1134 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1476, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-05 12:50:27.321  1014  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.321  1014  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-05 12:50:27.321  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-05 12:50:27.321  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.321  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.321  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
07-05 12:50:27.321  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-05 12:50:27.331  1014  1217 D InputDispatcher: Focus entered window: 1476
07-05 12:50:27.331  2605  2605 D Recents_RecreateReceiver: onReceive by home
,07-05 12:50:27.331  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 12:50:27.331  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 12:50:27.331  1476  1476 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-05 12:50:27.331  1014  3801 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.331  1014  3801 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-05 12:50:27.331  1014  3801 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.331  1014  3801 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-05 12:50:27.341  1014  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.341  1014  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.341  1014  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.341  1014  3801 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:27.341  6741  6741 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 12:50:27.341  6741  6741 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:50:27.341  6741  6741 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 12:50:27.341  6741  6741 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-05 12:50:27.341  6741  6741 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 12:50:27.341  6741  6741 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-05 12:50:27.341  6741  6741 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-05 12:50:27.341  1476  1476 V ActivityThread: updateVisibility : ActivityRecord{3ce707ef token=android.os.BinderProxy@b49e72d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-05 12:50:27.341  1476  1476 D Launcher.HomeView: onStop
07-05 12:50:27.341  6752  6752 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 12:50:27.341  6752  6752 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-05 12:50:27.351  6787  6787 E Zygote  : MountEmulatedStorage()
,07-05 12:50:27.351  6787  6787 E Zygote  : v2
07-05 12:50:27.351  6787  6787 I libpersona: KNOX_SDCARD checking this for 10084
07-05 12:50:27.351  6787  6787 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:27.351  6787  6787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:27.351  1014  3801 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6787 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-05 12:50:27.351  1014  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 12:50:27.361  6787  6787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:27.361  1014  6793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 12:50:27.361  6787  6787 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-05 12:50:27.361  1177  1177 I StatusBar: Icon Only
07-05 12:50:27.361  1177  1177 D PanelView: There is/are notification(s) 
07-05 12:50:27.381  6686  6686 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-05 12:50:27.381  6787  6787 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:27.391  1476  1476 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b49e72d time:116670
,07-05 12:50:27.391  6787  6787 D ActivityThread: Added TimaKeyStore provider,
,07-05 12:50:27.391  6770  6770 V TaskCloserActivity: TaskCloserActivity enter()
,07-05 12:50:27.401  1858  1858 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,07-05 12:50:27.411  6738  6738 D AndroidRuntime: 
07-05 12:50:27.411  6738  6738 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-05 12:50:27.411  6738  6738 D AndroidRuntime: CheckJNI is OFF
07-05 12:50:27.411  6738  6738 D AndroidRuntime: readGMSProperty: start
07-05 12:50:27.411  6738  6738 D AndroidRuntime: readGMSProperty: already setted!!
07-05 12:50:27.411  6738  6738 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 12:50:27.411  6738  6738 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 12:50:27.411  6738  6738 D AndroidRuntime: readGMSProperty: end
07-05 12:50:27.411  6738  6738 D AndroidRuntime: addProductProperty: start
,07-05 12:50:27.421  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{33cdd948 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:116707
07-05 12:50:27.421  1014  1044 W ActivityManager: mDVFSHelper.release()
,07-05 12:50:27.431  6770  6770 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-05 12:50:27.431  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-05 12:50:27.441  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.441  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.441  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-05 12:50:27.441  1014  1026 I ActivityManager: Killing 6362:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-05 12:50:27.461  6787  6787 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 12:50:27.461  1014  1217 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:27.461  1014  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.461  1014  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-05 12:50:27.461  1014  1217 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,07-05 12:50:27.471  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.471  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-05 12:50:27.471  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.471  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:27.481  6814  6814 E Zygote  : MountEmulatedStorage()
,07-05 12:50:27.481  6814  6814 E Zygote  : v2
07-05 12:50:27.481  6814  6814 I libpersona: KNOX_SDCARD checking this for 10135
07-05 12:50:27.481  6814  6814 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:27.481  6814  6814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:27.481  1014  1217 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6814 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
07-05 12:50:27.481  1014  1217 I ActivityManager: Killing 6377:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,07-05 12:50:27.481  1014  1217 I ActivityManager: Killing 6402:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,07-05 12:50:27.491   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:50:27.491  6814  6814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:27.501  6814  6814 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:27.501  1014  3882 D PersonaManager: isKioskContainerExistOnDevice
,07-05 12:50:27.511  6814  6814 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:27.511  6814  6814 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:27.531  6814  6814 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-05 12:50:27.531  6814  6814 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 12:50:27.531  6814  6814 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-05 12:50:27.531  6814  6814 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-05 12:50:27.531  6814  6814 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-05 12:50:27.551  6738  6738 E AffinityControl: AffinityControl: registerfunction enter
,07-05 12:50:27.571  1014  3801 I ActivityManager: Killing 6440:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-05 12:50:27.581  6738  6738 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-05 12:50:27.581  6741  6741 D NearbySource: Nearby Source Create!,
07-05 12:50:27.591  6741  6741 D NearbyContext: Nearby Context Create!
,07-05 12:50:27.591  1014  1027 D PackageManager: START PACKAGE DELETE: observer{514878024}
07-05 12:50:27.591  1014  1027 D PackageManager: pkg{<packageName>}
07-05 12:50:27.591  1014  1027 D PackageManager: user{0}
07-05 12:50:27.591  1014  1027 D PackageManager: caller{2000}
07-05 12:50:27.591  1014  1027 D PackageManager: flags{2}
,07-05 12:50:27.591  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,07-05 12:50:27.591  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 12:50:27.591  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,07-05 12:50:27.591  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-05 12:50:27.591  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-05 12:50:27.591  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 12:50:27.591  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-05 12:50:27.591  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 12:50:27.591  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
,07-05 12:50:27.591  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-05 12:50:27.591  1014  1054 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,07-05 12:50:27.601  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
07-05 12:50:27.601  1014  1039 I ActivityManager: Killing 6686:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-05 12:50:27.621   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-05 12:50:27.621   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 12:50:27.621  6741  6741 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,07-05 12:50:27.631  6741  6741 D SLinkSource: Samsung link source created
,07-05 12:50:27.701  1014  1054 W PackageSettings: Skipping PackageSetting{12416683 com.example.hello/10168} due to missing metadata
,07-05 12:50:27.741  1014  3802 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-05 12:50:27.751  6741  6833 D ContactProvider: getAllContactInfoList Start
,07-05 12:50:27.761  1014  1747 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-05 12:50:27.761  6741  6741 D GalleryCacheReady: Receive : home resume
,07-05 12:50:27.761  1014  3802 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:27.761  1014  3802 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.761  1014  3802 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-05 12:50:27.771  6274  6274 D Mms/UIEventReceiver: ui event
,07-05 12:50:27.771  1014  3802 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-05 12:50:27.771  1014  3802 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:27.771  1014  3802 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:27.771  1014  3802 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-05 12:50:27.781  6770  6770 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-05 12:50:27.781  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-05 12:50:27.811  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-05 12:50:27.841  2740  2740 I art     : Explicit concurrent mark sweep GC freed 23425(1279KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 788us total 33.277ms
,07-05 12:50:27.841  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 12:50:27.851  6552  6552 I art     : Explicit concurrent mark sweep GC freed 613(35KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 719us total 49.826ms
,07-05 12:50:27.861  4719  4719 I art     : Explicit concurrent mark sweep GC freed 1424(61KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/16MB, paused 1.131ms total 67.540ms
,07-05 12:50:27.861  1858  1858 E SamsungIME: mOCRHelper is null
,07-05 12:50:27.861  2029  2196 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 12:50:27.881  1014  1121 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-05 12:50:27.881  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:50:27.881  1014  1121 V NetworkStats: performPollLocked(flags=0x3)
,07-05 12:50:27.881  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
07-05 12:50:27.881  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-05 12:50:27.891  1014  1121 V NetworkStats: performPollLocked() took 8ms
07-05 12:50:27.891  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 12:50:27.901  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:50:27.901  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 12:50:27.901  1435  1435 D PersonaManager: isKioskContainerExistOnDevice
,07-05 12:50:27.901  1435  1435 D RegisteredServicesCache: empty dynamic service
,07-05 12:50:27.921  2689  2689 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 05 12:50:27 GMT+02:00 2016
,07-05 12:50:27.921  1014  1217 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-05 12:50:27.921  1014  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-05 12:50:27.931  1014  1217 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:27.931  1014  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-05 12:50:27.931  1014  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-05 12:50:27.941  2689  2689 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-05 12:50:27.941  1014  3882 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
,07-05 12:50:27.941  1014  3882 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-05 12:50:27.941  1014  3882 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-05 12:50:27.941  1014  3882 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:27.941  1014  3882 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.941  1014  3882 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.941  1014  3882 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:27.951  2689  2689 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-05 12:50:27.951  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
07-05 12:50:27.951  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-05 12:50:27.951  1014  1038 W TextServicesManagerService: no available spell checker services found
,07-05 12:50:27.961  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,07-05 12:50:27.961  6836  6836 I libpersona: KNOX_SDCARD checking this for 10090
07-05 12:50:27.961  2689  2689 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 12:50:27.961  6836  6836 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:27.961  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 12:50:27.961  1014  3882 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6836 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
07-05 12:50:27.961  6836  6836 E Zygote  : MountEmulatedStorage()
07-05 12:50:27.961  6836  6836 E Zygote  : v2
07-05 12:50:27.961  6836  6836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:50:27.961  6836  6836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:27.971  6836  6836 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:27.971  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-05 12:50:27.971  6274  6274 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-05 12:50:27.971  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.971  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.971  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.971  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:27.981  2689  2689 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-05 12:50:27.991   307   307 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 661us total 24.212ms
,07-05 12:50:28.001  2689  6835 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-05 12:50:28.001  6836  6836 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.001  6836  6836 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.011   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 656us total 16.639ms
,07-05 12:50:28.021  2689  6835 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-05 12:50:28.021  2689  6835 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-05 12:50:28.021  2689  6835 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-05 12:50:28.021   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.603ms
,07-05 12:50:28.031  1014  1014 I art     : Explicit concurrent mark sweep GC freed 46013(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 2.950ms total 212.774ms
,07-05 12:50:28.031  1014  1054 I art     : WaitForGcToComplete blocked for 204.081ms for cause Explicit
,07-05 12:50:28.041  6851  6851 E Zygote  : MountEmulatedStorage()
07-05 12:50:28.041  6851  6851 I libpersona: KNOX_SDCARD checking this for 1000
07-05 12:50:28.041  6851  6851 E Zygote  : v2
07-05 12:50:28.041  6851  6851 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:28.041  6851  6851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:50:28.041  1014  1039 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6851 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 12:50:28.041  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
07-05 12:50:28.041  6851  6851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:28.051  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 12:50:28.051  6851  6851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.051  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.051  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.051  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.051  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.061  1014  1026 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 12:50:28.061  1014  1026 D SecContentProvider2: mCursor = null
,07-05 12:50:28.061  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.071  6858  6858 E Zygote  : MountEmulatedStorage(),
07-05 12:50:28.071  6858  6858 I libpersona: KNOX_SDCARD checking this for 1000
07-05 12:50:28.071  6858  6858 E Zygote  : v2
07-05 12:50:28.071  6858  6858 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:28.071  6858  6858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:50:28.071  1014  1039 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 12:50:28.071  6858  6858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:28.071  6858  6858 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.081  1435  1435 D RegisteredComponentCache: Collect Tech packages for Knox
,07-05 12:50:28.081  1435  1435 D PersonaManager: isKioskContainerExistOnDevice
,07-05 12:50:28.091  1014  3801 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,07-05 12:50:28.091  1014  3801 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.091  1014  3801 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.091  1014  3801 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:28.091  1014  3801 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,07-05 12:50:28.101  6851  6851 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:28.101  6851  6851 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.101  6741  6833 D ContactProvider: getAllContactInfoList End
,07-05 12:50:28.111  6741  6833 I syncContacts: thread: 1193, sync time = 443
,07-05 12:50:28.111  1014  1342 I TactileAssist: enable value -1
07-05 12:50:28.111  1014  1342 I TactileAssist: internal enable value -1
07-05 12:50:28.111  1014  1342 I TactileAssist: intensity value -1
07-05 12:50:28.111  1014  1342 I TactileAssist: saveAppList value true
,07-05 12:50:28.121  1014  1342 I TactileAssist: List of disabled apps :
,07-05 12:50:28.121  1014  1014 D RCPManagerService: PackageReceiver onReceive()
07-05 12:50:28.121  6274  6879 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-05 12:50:28.121  6274  6879 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-05 12:50:28.121  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-05 12:50:28.131  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-05 12:50:28.131  2689  6835 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-05 12:50:28.131  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-05 12:50:28.141  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-05 12:50:28.151  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,07-05 12:50:28.151  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty,
,07-05 12:50:28.161  2689  6835 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-05 12:50:28.161  6836  6836 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-05 12:50:28.161  6836  6836 D elm:15121: ELMEngine.ELMEngine( context ).
07-05 12:50:28.161  2689  6835 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-05 12:50:28.161  6532  6532 D Compatibility: onReceive() it will make start service
,07-05 12:50:28.161  6858  6858 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.161  6858  6858 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.171  6836  6836 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-05 12:50:28.171  1014  1134 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-05 12:50:28.171  1014  1134 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-05 12:50:28.171  1014  1134 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:28.171  1014  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:28.171  1014  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-05 12:50:28.181  1014  1747 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-05 12:50:28.181  2689  2689 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
07-05 12:50:28.181  1014  1747 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.181  1014  1747 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:28.181  1014  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:28.181  1014  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-05 12:50:28.191  6836  6836 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-05 12:50:28.201  6836  6836 D elm:15121: ElmAgentService : onCreate()
,07-05 12:50:28.201  1014  1134 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-05 12:50:28.201  1014  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.201  1014  1134 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.201  1014  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.201  1014  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-05 12:50:28.201  2870  2870 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-05 12:50:28.211  2870  2870 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-05 12:50:28.211  2870  2870 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-05 12:50:28.211  2870  2870 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 12:50:28.211  2870  2870 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-05 12:50:28.211  2870  2870 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-05 12:50:28.211  2870  2870 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-05 12:50:28.211  2870  2870 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:50:28.211  2870  2870 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:50:28.211  2870  2870 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 12:50:28.211  2870  2870 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:28.211  2870  2870 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:28.211  2870  2870 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 12:50:28.211  2870  2870 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-05 12:50:28.211  6836  6882 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 12:50:28.211  6836  6882 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-05 12:50:28.211  6836  6882 D elm:15121: MDMBridge.getInstance()
07-05 12:50:28.211  6836  6882 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-05 12:50:28.211  6532  6883 D Compatibility: onHandleIntent()
,07-05 12:50:28.211  6532  6883 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,07-05 12:50:28.211  6836  6882 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-05 12:50:28.221  6532  6883 D Compatibility: found: 2
07-05 12:50:28.221  6532  6883 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-05 12:50:28.221  6532  6883 D Compatibility: skipping ResolveInfo{35aa581f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-05 12:50:28.221  6532  6883 D Compatibility: considering ResolveInfo{75b276c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-05 12:50:28.221  6532  6883 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-05 12:50:28.221  6532  6883 D Compatibility: enabling receiver ResolveInfo{115ae135 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-05 12:50:28.221  6858  6858 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,07-05 12:50:28.231  1014  3886 D SecContentProvider2: uri = -1 selection = getSealedState
,07-05 12:50:28.231  1014  3886 D SecContentProvider2: mCursor = null
,07-05 12:50:28.231  6532  6883 D Compatibility: enabling receiver ResolveInfo{384e39ca com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-05 12:50:28.231  1014  1475 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,07-05 12:50:28.231  1014  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.231  6851  6851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-05 12:50:28.241  6858  6858 I PopupuiReceiver_KNOX: getSealedState : true
07-05 12:50:28.241  1014  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.241  6552  6884 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-05 12:50:28.241  1014  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.241  1014  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.241  1014  3882 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
07-05 12:50:28.241  1014  3882 D SecContentProvider2: mCursor = null
,07-05 12:50:28.251  6858  6858 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
07-05 12:50:28.251  1014  1475 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6886 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
07-05 12:50:28.251  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-05 12:50:28.251  1014  3802 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
07-05 12:50:28.251  1014  3802 D SecContentProvider2: mCursor = null
,07-05 12:50:28.261  6532  6883 D Compatibility: enabling receiver ResolveInfo{b26573b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
,07-05 12:50:28.261  6836  6836 D elm:15121: ElmAgentService : onDestroy().
07-05 12:50:28.261  6886  6886 I libpersona: KNOX_SDCARD checking this for 10055
07-05 12:50:28.261  6858  6858 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
07-05 12:50:28.261  6886  6886 I libpersona: KNOX_SDCARD not a persona,
07-05 12:50:28.261  6858  6858 D PopupuiReceiver: Action package removed,
07-05 12:50:28.261  6886  6886 E Zygote  : MountEmulatedStorage()
07-05 12:50:28.261  6886  6886 E Zygote  : v2
,07-05 12:50:28.261  6886  6886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-05 12:50:28.261  6886  6886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-05 12:50:28.261  1014  1054 W art     : Suspending all threads took: 6.993ms
,07-05 12:50:28.271  6886  6886 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.281  1014  1469 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-05 12:50:28.281  1014  1469 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.281  1014  1469 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.281  1014  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:28.281  1014  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,07-05 12:50:28.281  1014  3802 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-05 12:50:28.281  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.281  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.281  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.281  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.291  6886  6886 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.291  6886  6886 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.291  6532  6883 D Compatibility: enabling receiver ResolveInfo{20894e58 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-05 12:50:28.301  6897  6897 E Zygote  : MountEmulatedStorage()
07-05 12:50:28.301  6897  6897 E Zygote  : v2
07-05 12:50:28.301  6897  6897 I libpersona: KNOX_SDCARD checking this for 10145
07-05 12:50:28.301  6897  6897 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:28.301  6897  6897 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:28.301  6532  6883 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-05 12:50:28.301  6897  6897 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-05 12:50:28.311  1014  3802 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6897 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,07-05 12:50:28.311  6897  6897 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.321  1014  1054 I art     : Explicit concurrent mark sweep GC freed 11160(718KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 14.233ms total 289.328ms
07-05 12:50:28.321  1014  3802 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,07-05 12:50:28.321  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.321  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.321  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.321  1014  3802 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.321  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.331  6897  6897 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.331  6897  6897 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.341  6917  6917 E Zygote  : MountEmulatedStorage(),
07-05 12:50:28.341  6917  6917 E Zygote  : v2
07-05 12:50:28.341  6917  6917 I libpersona: KNOX_SDCARD checking this for 1000,
07-05 12:50:28.341  6917  6917 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:28.341  6917  6917 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-05 12:50:28.341  6917  6917 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-05 12:50:28.341  6917  6917 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.341  1014  3802 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6917 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,07-05 12:50:28.351  1014  1054 D PackageManager: delete codoeFile: 
,07-05 12:50:28.351  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,07-05 12:50:28.351  1014  1054 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-05 12:50:28.351  1014  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 12:50:28.351  1014  1054 D PackageManager: result of delete: 1{514878024}
,07-05 12:50:28.351  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:50:28.361  6738  6738 D AndroidRuntime: Shutting down VM
07-05 12:50:28.361  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.361  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-05 12:50:28.361  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 12:50:28.361  1014  1054 D PackageManager: userId{-1}
07-05 12:50:28.361  1014  1054 D PackageManager: andCode{true}
,07-05 12:50:28.371  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.381  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.381  6917  6917 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.381  6917  6917 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.391  1014  1342 I ActivityManager: Killing 6417:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-05 12:50:28.391  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 12:50:28.391  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 12:50:28.391  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 12:50:28.391  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.401  1014  3801 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 12:50:28.401  1014  3801 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.401  1014  3801 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.401  1014  3801 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.401  1014  3801 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 12:50:28.411  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.411  6886  6886 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-05 12:50:28.411  6917  6917 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 12:50:28.421  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-05 12:50:28.421  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 12:50:28.421  6897  6897 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-05 12:50:28.421  6897  6897 D ThemeInfoUtil: isCurrentFestival = false
,07-05 12:50:28.421  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-05 12:50:28.431  6917  6917 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-05 12:50:28.431  1014  3880 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,07-05 12:50:28.431  1014  1134 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,07-05 12:50:28.441  1014  1134 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-05 12:50:28.441  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.441  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.441  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.441  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.441  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.451  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.451  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 12:50:28.451  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 12:50:28.451  6886  6886 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-05 12:50:28.451  6886  6886 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-05 12:50:28.451  6886  6886 D UserAnalysis: Create SecureDbHelper
,07-05 12:50:28.451  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,07-05 12:50:28.461  6933  6933 E Zygote  : MountEmulatedStorage()
07-05 12:50:28.461  6933  6933 E Zygote  : v2
07-05 12:50:28.461  6933  6933 I libpersona: KNOX_SDCARD checking this for 10148
07-05 12:50:28.461  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 12:50:28.461  6933  6933 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:28.461  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 12:50:28.461  6933  6933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-05 12:50:28.461  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
07-05 12:50:28.461  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 12:50:28.461  6933  6933 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:28.461  1014  3880 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6933 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
07-05 12:50:28.461  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 12:50:28.461  6933  6933 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:50:28.461  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-05 12:50:28.461  1014  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-05 12:50:28.461  1014  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 12:50:28.461  1014  3527 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 12:50:28.461  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 12:50:28.461  1014  1217 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.461  1014  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.461  1014  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 12:50:28.471  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 12:50:28.471  1014  1014 V AlarmManagerEXT: com.test.thalitest(10170) is removed.,
,07-05 12:50:28.471  1014  3802 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.471  1014  3802 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.471  1014  3802 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.471  1014  3802 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:50:28.471  6886  6886 D IntelligenceServiceApplication: onCreate()
07-05 12:50:28.471  6886  6886 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-05 12:50:28.481  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-05 12:50:28.481  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-05 12:50:28.481  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=43_task.xml
,07-05 12:50:28.491  1014  3880 I ActivityManager: Killing 6478:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
07-05 12:50:28.491  1014  3880 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
07-05 12:50:28.491  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.491  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.491  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.491  1014  3880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.491  6886  6886 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-05 12:50:28.491   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:50:28.501  6933  6933 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.501  6933  6933 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.501  6948  6948 E Zygote  : MountEmulatedStorage()
07-05 12:50:28.501  6948  6948 I libpersona: KNOX_SDCARD checking this for 1000
07-05 12:50:28.501  6948  6948 E Zygote  : v2
07-05 12:50:28.501  6948  6948 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:28.501  6948  6948 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:28.511  6948  6948 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:28.511  6948  6948 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.511  1014  3880 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6948 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-05 12:50:28.521  1014  3880 I ActivityManager: Killing 6489:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21,
07-05 12:50:28.521  1014  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:50:28.521  1014  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.521  1014  1134 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.521  1014  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.521  1014  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 12:50:28.531  1014  3886 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-05 12:50:28.531  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,07-05 12:50:28.531  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.531  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.531  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.531  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.531  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-05 12:50:28.541  6948  6948 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.541  6948  6948 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.551  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-05 12:50:28.561  6966  6966 E Zygote  : MountEmulatedStorage(),
07-05 12:50:28.561  6966  6966 E Zygote  : v2
07-05 12:50:28.561  6966  6966 I libpersona: KNOX_SDCARD checking this for 1000,
07-05 12:50:28.561  6738  6738 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-05 12:50:28.561  6966  6966 I libpersona: KNOX_SDCARD not a persona
07-05 12:50:28.561  6966  6966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:28.571  6966  6966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 12:50:28.571  6966  6966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:50:28.571  1014  1014 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-05 12:50:28.581  1014  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 12:50:28.581  1014  1475 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.581  1014  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.581  1014  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 12:50:28.591  6573  6573 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,07-05 12:50:28.591  6573  6573 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
07-05 12:50:28.591  1014  3802 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-05 12:50:28.591  1014  3802 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
07-05 12:50:28.591  1014  3802 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.591  1014  3802 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:28.591  1014  3802 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,07-05 12:50:28.591  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
07-05 12:50:28.591  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-05 12:50:28.601  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,07-05 12:50:28.601  6573  6573 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,07-05 12:50:28.601  6966  6966 D ActivityThread: Added TimaKeyStore provider
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-05 12:50:28.601  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-05 12:50:28.601  6933  6933 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,07-05 12:50:28.611  6573  6975 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,07-05 12:50:28.611  6573  6975 D FilterUnInstaller: before removeFromFS
07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-05 12:50:28.611  1014  1474 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-05 12:50:28.611  6948  6948 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 12:50:28.611  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
07-05 12:50:28.611  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
07-05 12:50:28.611  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.611  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
07-05 12:50:28.611  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.631  6983  6983 E Zygote  : MountEmulatedStorage()
,07-05 12:50:28.631  6983  6983 I libpersona: KNOX_SDCARD checking this for 10095
07-05 12:50:28.631  6983  6983 E Zygote  : v2
07-05 12:50:28.631  6983  6983 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:28.631  6983  6983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:28.631  6983  6983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:28.631  6983  6983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.631  1014  1474 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6983 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
07-05 12:50:28.631  6886  6886 D BluetoothAdapter: cancelDiscovery
,07-05 12:50:28.641  1014  1747 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,07-05 12:50:28.641  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.641  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.641  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.641  1014  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.651  6983  6983 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.651  6983  6983 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.661  6998  6998 E Zygote  : MountEmulatedStorage()
07-05 12:50:28.661  6998  6998 E Zygote  : v2
,07-05 12:50:28.661  6998  6998 I libpersona: KNOX_SDCARD checking this for 1000
07-05 12:50:28.661  6998  6998 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:28.661  6998  6998 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:28.661  6998  6998 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:28.661  6998  6998 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:50:28.661  1014  1747 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6998 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-05 12:50:28.671  3399  3408 D BluetoothAdapterProperties: mDiscovering is false
07-05 12:50:28.671  3399  3408 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,07-05 12:50:28.671  6886  6886 D BluetoothAdapter: cancelDiscovery = true
,07-05 12:50:28.681  6886  6886 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,07-05 12:50:28.681  1014  1342 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-05 12:50:28.681  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,07-05 12:50:28.681  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.681  1014  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:50:28.681  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
07-05 12:50:28.681  6966  6966 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-05 12:50:28.681  6966  6966 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-05 12:50:28.681  6966  6966 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,07-05 12:50:28.691  1014  3801 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-05 12:50:28.691  1014  1469 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,07-05 12:50:28.691  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
07-05 12:50:28.691  1014  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.691  6948  6948 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
07-05 12:50:28.691  1014  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.691  1014  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:50:28.691  1014  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 12:50:28.691  4719  6949 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 12:50:28.691  4719  6949 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-05 12:50:28.701  6998  6998 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 12:50:28.701  6998  6998 D ActivityThread: Added TimaKeyStore provider
,07-05 12:50:28.701  7015  7015 E Zygote  : MountEmulatedStorage()
07-05 12:50:28.701  7015  7015 E Zygote  : v2
07-05 12:50:28.701  7015  7015 I libpersona: KNOX_SDCARD checking this for 10152
07-05 12:50:28.701  7015  7015 I libpersona: KNOX_SDCARD not a persona
,07-05 12:50:28.711  6966  6966 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,07-05 12:50:28.711  7015  7015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 12:50:28.711  1014  1469 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7015 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,07-05 12:50:28.711  7015  7015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:50:28.711  7015  7015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 12:50:28.721  6948  7006 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,07-05 12:50:28.731  6948  7006 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
,07-05 12:50:28.731  6886  6886 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-05 12:50:28.731   307   307 I art     : Explicit concurrent mark sweep GC freed 8733(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 23.670ms
,07-05 12:50:28.741  1014  3882 I ActivityManager: Killing 6513:com.wsomacp/u0a23 (adj 15): empty #21
,07-05 12:50:28.741  6948  7006 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/seatbelt.db'.
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:40)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:28)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at com.samsung.android.sm.common.r.n(Utils.java:2237)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at com.samsung.android.sm.common.o.run(SmartManagerReceiver.java:125)
07-05 12:50:28.741  6948  7006 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: FATAL EXCEPTION: Thread-1251
07-05 12:50:28.741  6948  7006 E AndroidRuntime: Process: com.samsung.android.sm, PID: 6948
07-05 12:50:28.741  6948  7006 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699,)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:40)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:28)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at com.samsung.android.sm.common.r.n(Utils.java:2237)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at com.samsung.android.sm.common.o.run(SmartManagerReceiver.java:125)
07-05 12:50:28.741  6948  7006 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 12:50:28.741  6948  6948 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 12:50:28.741  6948  6948 D AndroidRuntime: Shutting down VM
07-05 12:50:28.741  6948  6948 I Process : Sending signal. PID: 6948 SIG: 9
07-05 12:50:28.741  1014  3802 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
07-05 12:50:28.741  6886  6886 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
07-05 12:50:28.741  1014  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:50:28.741  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
07-05 12:50:28.741  7015  7015 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:50:28.751  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:50:28.751  1014  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:50:28.751  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:50:28.751  7015  7015 D ActivityThread: Added TimaKeyStore provider
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 12:50:28.751  6886  6886 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 12:50:28.751  6886  6886 E UserAnalysis: It failed to get the database for dump_log
07-05 12:50:28.751  6886  6886 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 12:50:28.761  6886  6886 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 12:50:28.761  6886  6886 E UserAnalysis: It failed to get the database for dump_log
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 12:50:28.761  6966  6966 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 12:50:28.761  6966  6966 D AndroidRuntime: Shutting down VM
07-05 12:50:28.761  6966  6966 E AndroidRuntime: FATAL EXCEPTION: main
07-05 12:50:28.761  6966  6966 E AndroidRuntime: Process: com.sec.pcw.device, PID: 6966
07-05 12:50:28.761  6966  6966 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-05 12:50:28.761  6966  6966 E AndroidRuntime: 	... 11 more
07-05 12:50:28.761  1014  3801 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
07-05 12:50:28.761   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 26.336ms
07-05 12:50:28.771  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast

```
