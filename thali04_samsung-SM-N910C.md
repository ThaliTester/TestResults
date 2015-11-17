#### Test 50388019b27d54e_thali04_samsung-SM-N910C Logs


```--------- beginning of system
,11-17 18:21:47.090  3527  5527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
11-17 18:21:47.500 10533 10533 D AndroidRuntime: 
11-17 18:21:47.500 10533 10533 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:21:47.505 10533 10533 D AndroidRuntime: CheckJNI is OFF
11-17 18:21:47.505 10533 10533 D AndroidRuntime: readGMSProperty: start
11-17 18:21:47.505 10533 10533 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:21:47.510 10533 10533 D AndroidRuntime: readGMSProperty: end
11-17 18:21:47.510 10533 10533 D AndroidRuntime: addProductProperty: start
11-17 18:21:47.625 10533 10533 E AffinityControl: AffinityControl: registerfunction enter
11-17 18:21:47.645 10533 10533 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:21:47.660  3527  4097 E PersonaManagerService: inState():  stateMachine is null !!
11-17 18:21:47.660  3527  4097 I PersonaManagerService: PersonaId don't exist
11-17 18:21:47.660  3527  4097 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
11-17 18:21:47.665  3527  4097 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:21:47.670  3527  4097 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:21:47.670  3527  4097 D ResourcesManager: creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
11-17 18:21:47.680  3527  4097 W ActivityManager: mDVFSHelper.acquire()
11-17 18:21:47.680  3527  4097 D FocusedStackFrame: Set to : 0
11-17 18:21:47.685  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:47.685  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:47.685  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:47.685  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:47.715 10555 10555 E Zygote  : MountEmulatedStorage()
11-17 18:21:47.715 10555 10555 E Zygote  : v2
11-17 18:21:47.715 10555 10555 I libpersona: KNOX_SDCARD checking this for 10398
11-17 18:21:47.715 10555 10555 I libpersona: KNOX_SDCARD not a persona
11-17 18:21:47.720 10555 10555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
11-17 18:21:47.725  3527  4097 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10555 uid=10398 gids={50398, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:21:47.725 10555 10555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
11-17 18:21:47.730 10555 10555 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
11-17 18:21:47.735 10533 10533 D AndroidRuntime: Shutting down VM
11-17 18:21:47.740  3527  3562 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:21:47.740  3527  3562 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:21:47.740  3527  3562 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:21:47.740  3527  3562 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
11-17 18:21:47.765 10555 10555 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:21:47.765 10555 10555 D ActivityThread: Added TimaKeyStore provider
11-17 18:21:47.770  3527  3785 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
11-17 18:21:47.770  3527  3785 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
11-17 18:21:47.770  3527  3785 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
11-17 18:21:47.770  3527  3785 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
11-17 18:21:47.770  3527  3785 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
11-17 18:21:47.810 10555 10555 D ResourcesManager: creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
11-17 18:21:47.820  2855  2948 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
11-17 18:21:47.820  2855  2950 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
11-17 18:21:47.825  3999  3999 V ActivityThread: updateVisibility : ActivityRecord{2de74271 token=android.os.BinderProxy@3d796dea {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
11-17 18:21:47.825  3999  3999 D Launcher: onTrimMemory. Level: 20
11-17 18:21:47.915 10555 10555 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
11-17 18:21:47.915 10555 10555 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
11-17 18:21:47.925 10555 10555 I LibraryLoader: Loading: webviewchromium
11-17 18:21:47.930 10555 10555 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6948-6952)
11-17 18:21:47.930 10555 10555 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:21:47.960 10555 10555 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36742bae}
11-17 18:21:47.960 10555 10555 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:21:47.960 10555 10555 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,11-17 18:21:47.980 10555 10555 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:21:47.980 10555 10555 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:21:47.990 10555 10572 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
11-17 18:21:48.000 10555 10555 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
11-17 18:21:48.000 10555 10555 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
11-17 18:21:48.000 10555 10555 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
11-17 18:21:48.000 10555 10576 D BluetoothAdapter: 190434639: getState() :  mService = null. Returning STATE_OFF
11-17 18:21:48.115 10555 10582 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
11-17 18:21:48.115 10555 10555 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
11-17 18:21:48.145 10555 10555 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:21:48.150 10555 10555 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:21:48.160 10555 10555 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
11-17 18:21:48.170 10555 10555 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:21:48.170 10555 10555 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:21:48.215 10555 10555 D Activity: performCreate Call secproduct feature valuefalse
11-17 18:21:48.215 10555 10555 D Activity: performCreate Call debug elastic valuetrue
11-17 18:21:48.230 10555 10607 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:21:48.240  3527  4190 D ActivityManager: post active user change for 0
11-17 18:21:48.240  3527  4190 D KnoxTimeoutHandler: postActiveUserChange for user 0
11-17 18:21:48.240  3527  3527 D KnoxTimeoutHandler: handleActiveUserChange for user 0
11-17 18:21:48.290  2855  2855 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
11-17 18:21:48.300  3527  3560 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:21:48.305  3527  3560 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:21:48.320  3527  3562 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:21:48.320  3527  3562 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:21:48.320  3527  3562 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:21:48.325  3527  3562 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
11-17 18:21:48.325 10555 10607 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:21:48.325 10555 10607 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278963440 
11-17 18:21:48.330 10555 10607 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
11-17 18:21:48.330 10555 10607 D OpenGLRenderer: Enabling debug mode 0
11-17 18:21:48.335 10555 10607 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
11-17 18:21:48.340 10555 10555 V ActivityThread: updateVisibility : ActivityRecord{39eea83f token=android.os.BinderProxy@376b8a2d {com.example.hello/com.example.hello.MainActivity}} show : true
11-17 18:21:48.430  3527  3992 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
11-17 18:21:48.435  3527 10622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:21:48.450  3527  3562 W ActivityManager: mDVFSHelper.release()
11-17 18:21:48.450  3527  3562 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8d645be u0 com.example.hello/.MainActivity t25} time:127473
11-17 18:21:48.600  3527  4188 I art     : Explicit concurrent mark sweep GC freed 29516(1845KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 48MB/64MB, paused 1.889ms total 159.676ms
11-17 18:21:48.610  3527 10627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:21:48.625 10555 10555 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
11-17 18:21:48.625 10555 10555 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@376b8a2d time:127646
11-17 18:21:48.700 10555 10555 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:21:48.700 10555 10631 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:21:48.755 10555 10555 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:21:48.765 10555 10555 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:21:48.765 10555 10555 I chromium: 
11-17 18:21:48.890 10555 10632 D jxcore_app_log: JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359522048
11-17 18:21:48.890 10555 10632 D JX-Cordova: jxcore cordova android initializing
11-17 18:21:48.945 10555 10555 W jxcore-log: Initializing JXcore engine
11-17 18:21:48.945 10555 10555 W jxcore-log: JXcore engine is ready
11-17 18:21:48.955 10555 10555 W jxcore-log: Starting JXcore engine
11-17 18:21:49.025  4546  4546 E auditd  : In denial and Property audit_ondenial is set to 1 
11-17 18:21:49.025  3527  3557 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
11-17 18:21:49.025  3527  3557 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
11-17 18:21:49.030  3527  3557 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
11-17 18:21:49.110 10555 10555 W jxcore-log: Platform android
11-17 18:21:49.110 10555 10555 W jxcore-log: 
11-17 18:21:49.110 10555 10555 W jxcore-log: Process ARCH arm
11-17 18:21:49.110 10555 10555 W jxcore-log: 
11-17 18:21:49.145 10555 10555 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:21:49.145 10555 10555 I jxcore-log: 
11-17 18:21:49.145 10555 10555 W jxcore-log: JXcore engine is started
11-17 18:21:49.210 10555 10555 E jxcore-log: >> samsung-SM-N910C
11-17 18:21:49.210 10555 10555 E jxcore-log: 
11-17 18:21:49.210 10555 10555 I jxcore-log: Total memory 2970812416
11-17 18:21:49.210 10555 10555 I jxcore-log: 
11-17 18:21:49.210 10555 10555 I jxcore-log: Free memory 169205760
11-17 18:21:49.210 10555 10555 I jxcore-log: 
11-17 18:21:49.210 10555 10555 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:21:49.210 10555 10555 I jxcore-log: 
11-17 18:21:49.210 10555 10555 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:21:49.210 10555 10555 I jxcore-log: 
11-17 18:21:49.215 10555 10555 I jxcore-log: userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
11-17 18:21:49.215 10555 10555 I jxcore-log: 
11-17 18:21:49.220 10555 10555 I jxcore-log: Size 1440 2560
11-17 18:21:49.220 10555 10555 I jxcore-log: 
11-17 18:21:49.220 10555 10555 I jxcore-log: Screen Brightness 134
11-17 18:21:49.220 10555 10555 I jxcore-log: 
11-17 18:21:49.220 10555 10555 E jxcore-log: Dummy Error Log.
11-17 18:21:49.220 10555 10555 E jxcore-log: 
,11-17 18:21:49.780 10555 10555 I jxcore-log: getBuffer is called!!!!
11-17 18:21:49.780 10555 10555 I jxcore-log: 
,11-17 18:21:53.885  3527  3833 E Watchdog: !@Sync 4,
,11-17 18:21:54.235 10555 10555 D BluetoothAdapter: disable()
,11-17 18:21:54.250  3527  4189 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,11-17 18:21:54.270  3527  3626 D WifiService: New client listening to asynchronous messages
,11-17 18:21:54.275 10555 10555 I WifiManager: packageName : com.example.hello
,11-17 18:21:54.275  3527  4190 D SecContentProvider: uri = 18 selection = isWifiEnabled
,11-17 18:21:54.275  3527  4190 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,11-17 18:21:54.275  3527  4190 D SecContentProvider2: mCursor = null
,11-17 18:21:54.285  3527  4190 D WifiService: setWifiEnabled: false pid=10555, uid=10398
,11-17 18:21:54.285  3527  4190 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 18:21:54.285  3527  4190 D SettingsProvider: name = wifi_on
,11-17 18:21:54.285 10555 10555 I jxcore-log: ****TEST TOOK:  5081  ms ****
11-17 18:21:54.285 10555 10555 I jxcore-log: 
,11-17 18:21:54.290 10555 10555 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:21:54.290 10555 10555 I jxcore-log: 
,11-17 18:21:54.660 10659 10659 D AndroidRuntime: 
11-17 18:21:54.660 10659 10659 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:21:54.665 10659 10659 D AndroidRuntime: CheckJNI is OFF
,11-17 18:21:54.665 10659 10659 D AndroidRuntime: readGMSProperty: start
11-17 18:21:54.665 10659 10659 D AndroidRuntime: readGMSProperty: already setted!!
,11-17 18:21:54.670 10659 10659 D AndroidRuntime: readGMSProperty: end
11-17 18:21:54.670 10659 10659 D AndroidRuntime: addProductProperty: start
,11-17 18:21:54.780 10659 10659 E AffinityControl: AffinityControl: registerfunction enter
,11-17 18:21:54.805 10659 10659 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:21:54.815  3527  3818 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,11-17 18:21:54.815  3527  3818 D PackageManager: START PACKAGE DELETE: observer{2212697}
11-17 18:21:54.815  3527  3818 D PackageManager: pkg{<packageName>}
11-17 18:21:54.815  3527  3818 D PackageManager: user{0}
11-17 18:21:54.815  3527  3818 D PackageManager: caller{2000}
11-17 18:21:54.815  3527  3818 D PackageManager: flags{3}
11-17 18:21:54.815  3527  3818 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
11-17 18:21:54.815  3527  3568 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,11-17 18:21:54.815  3527  3818 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
11-17 18:21:54.815  3527  3818 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
11-17 18:21:54.815  3527  3818 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
11-17 18:21:54.815  3527  3568 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:0
,11-17 18:21:54.815  3527  3568 D PackageManager: !@killApplicatoin: 10398, uninstall pkg
11-17 18:21:54.815  3527  3568 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:-1
11-17 18:21:54.815  3527  3555 I ActivityManager: Force stopping com.example.hello appid=10398 user=-1: uninstall pkg
11-17 18:21:54.815  3527  3568 D ApplicationPolicy: getApplicationUninstallationEnabled
,11-17 18:21:54.815  3527  3555 I ActivityManager: Killing 10555:com.example.hello/u0a398 (adj 0): stop com.example.hello
11-17 18:21:54.815  3527  3568 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,11-17 18:21:54.825  3527  3555 I ActivityManager:   Force finishing activity ActivityRecord{8d645be u0 com.example.hello/.MainActivity t25}
,11-17 18:21:54.845  2855  2948 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,11-17 18:21:54.850  2855  2950 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,11-17 18:21:54.855  3527  3562 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:21:54.855  3527  3562 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:21:54.855  3527  3562 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
11-17 18:21:54.855  3527  3562 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,11-17 18:21:54.925  3527  3568 W PackageSettings: Skipping PackageSetting{4bfc40d com.test.thalitest/10394} due to missing metadata
,11-17 18:21:54.930  3527  3626 D WifiService: Client connection lost with reason: 4
,11-17 18:21:54.945  3527  3568 I ActivityManager: Force stopping com.example.hello appid=10398 user=0: pkg removed
,11-17 18:21:54.990  8131  8131 I art     : Explicit concurrent mark sweep GC freed 1032(62KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 967us total 29.175ms
,11-17 18:21:55.000  7824  7824 I art     : Explicit concurrent mark sweep GC freed 31166(1714KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.135ms total 34.970ms
11-17 18:21:55.005  3527  3562 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,11-17 18:21:55.010  3527  3599 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:21:55.030  4241  4527 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:21:55.040 10345 10345 D LWLocationManager: getDeviceLocationId :  id = -100
11-17 18:21:55.040 10345 10345 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,11-17 18:21:55.045  3527  3555 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.045  3527  3555 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.045  3527  3555 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.045  3527  3555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.050  4436  4436 E SamsungIME: mOCRHelper is null
,11-17 18:21:55.060 10677 10677 E Zygote  : MountEmulatedStorage()
11-17 18:21:55.060 10677 10677 E Zygote  : v2
11-17 18:21:55.060 10677 10677 I libpersona: KNOX_SDCARD checking this for 10063
11-17 18:21:55.060 10677 10677 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.065 10677 10677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,11-17 18:21:55.065  3527  3555 I ActivityManager: Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10677 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:21:55.070 10677 10677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.070 10677 10677 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:55.105 10677 10677 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.105 10677 10677 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:55.125  3527  3527 I art     : Explicit concurrent mark sweep GC freed 13815(1298KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 48MB/64MB, paused 2.850ms total 156.009ms
11-17 18:21:55.125  3527  3568 I art     : WaitForGcToComplete blocked for 149.473ms for cause Explicit
,11-17 18:21:55.125  3527  3527 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,11-17 18:21:55.135 10677 10677 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,11-17 18:21:55.135  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,11-17 18:21:55.140  4934  4967 W ResourceType: For resource 0x7f020a0f, entry index(2575) is beyond type entryCount(725)
11-17 18:21:55.140  4934  4967 W ResourceType: Failure getting entry for 0x7f020a0f (t=1 e=2575) (error -75)
11-17 18:21:55.140  4934  4967 W ResourceType: For resource 0x7f020a62, entry index(2658) is beyond type entryCount(725)
11-17 18:21:55.140  4934  4967 W ResourceType: Failure getting entry for 0x7f020a62 (t=1 e=2658) (error -75)
,11-17 18:21:55.145  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,11-17 18:21:55.145  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,11-17 18:21:55.150  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,11-17 18:21:55.150  4934  4967 W ResourceType: For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,11-17 18:21:55.150  4934  4967 W ResourceType: Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
11-17 18:21:55.150 10677 10677 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
11-17 18:21:55.150 10677 10677 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
11-17 18:21:55.150  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
11-17 18:21:55.155 10677 10677 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.example.hello
,11-17 18:21:55.155  3527  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.155  3527  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.155  3527  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.155  3527  3818 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.155  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,11-17 18:21:55.165 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,11-17 18:21:55.170 10694 10694 E Zygote  : MountEmulatedStorage()
,11-17 18:21:55.170 10694 10694 E Zygote  : v2
11-17 18:21:55.170  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,11-17 18:21:55.170 10694 10694 I libpersona: KNOX_SDCARD checking this for 10021
11-17 18:21:55.170 10694 10694 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.175 10694 10694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,11-17 18:21:55.175  3527  3818 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10694 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
11-17 18:21:55.175  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,11-17 18:21:55.180  3527  3527 D ResourcesManager: creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,11-17 18:21:55.180 10694 10694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.180 10694 10694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:55.190  3527  5514 D SSRM:n  : SIOP:: AP = 270, PST = 298, CUR = 78
,11-17 18:21:55.215  3960  3960 D RegisteredServicesCache: empty dynamic service
,11-17 18:21:55.215 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,11-17 18:21:55.220 10694 10694 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.220 10694 10694 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:55.235 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,11-17 18:21:55.240  3527  3785 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
11-17 18:21:55.240  3527  3785 D SecContentProvider2: mCursor = null
,11-17 18:21:55.240 10694 10694 D ResourcesManager: creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,11-17 18:21:55.245 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,11-17 18:21:55.250  3527  4253 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
11-17 18:21:55.250  3527  4253 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
11-17 18:21:55.250  3527  4253 D BatteryService: online:4, current avg:81, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-54
11-17 18:21:55.250  3527  4253 D BatteryService: stay LED for fully charged
,11-17 18:21:55.260 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,11-17 18:21:55.270 10694 10694 I KLMS-2.4.521: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:21:55 GMT+01:00 2015
,11-17 18:21:55.275 10694 10694 I KLMS-2.4.521: : KLMSAbstractReciever(): onReceive().END.
,11-17 18:21:55.275  3527  4097 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=24, mSplitNum[2]=34 divideNum= 10 r.nextReceiver= 2 receivers.size=44
11-17 18:21:55.275  3527  4097 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,11-17 18:21:55.275 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,11-17 18:21:55.275 10694 10694 I KLMS-2.4.521: : KLMSIntentService(): onCreate()
11-17 18:21:55.275  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.275  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.275  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.275  3527  4097 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.280 10694 10694 I KLMS-2.4.521: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,11-17 18:21:55.280  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,11-17 18:21:55.285 10694 10694 I KLMS-2.4.521: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,11-17 18:21:55.285 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
11-17 18:21:55.285  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,11-17 18:21:55.290 10694 10710 I KLMS-2.4.521: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,11-17 18:21:55.290  3527  3568 I art     : Explicit concurrent mark sweep GC freed 5693(366KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 1.862ms total 162.943ms
,11-17 18:21:55.290  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
11-17 18:21:55.290 10694 10710 I KLMS-2.4.521: : KLMSIntentService(): PACKAGE_REMOVED
,11-17 18:21:55.295 10711 10711 E Zygote  : MountEmulatedStorage()
11-17 18:21:55.295 10711 10711 E Zygote  : v2
11-17 18:21:55.295 10711 10711 I libpersona: KNOX_SDCARD checking this for 10106
11-17 18:21:55.295 10711 10711 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.295 10711 10711 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
11-17 18:21:55.295 10694 10710 I KLMS-2.4.521: : KLMSIntentService(): listeningToPackageRemoved().START
,11-17 18:21:55.295 10694 10710 I KLMS-2.4.521: : KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,11-17 18:21:55.300 10711 10711 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.300 10711 10711 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:21:55.300 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
11-17 18:21:55.300  3527  4097 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10711 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,11-17 18:21:55.305  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,11-17 18:21:55.305 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,11-17 18:21:55.310  3527  3568 D PackageManager: delete codoeFile: 
,11-17 18:21:55.310  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,11-17 18:21:55.310  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,11-17 18:21:55.315  3527  3568 I AASAUninstall:  com.example.hello not target!
11-17 18:21:55.315  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,11-17 18:21:55.315  3527  3568 D PackageManager: result of delete: 1{2212697}
,11-17 18:21:55.315 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
11-17 18:21:55.315 10345 10688 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:21:55.315  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
11-17 18:21:55.315  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
11-17 18:21:55.315  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,11-17 18:21:55.320 10659 10659 D AndroidRuntime: Shutting down VM
11-17 18:21:55.320  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
11-17 18:21:55.325  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,11-17 18:21:55.325 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
11-17 18:21:55.325  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,11-17 18:21:55.325  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,11-17 18:21:55.330  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,11-17 18:21:55.335  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,11-17 18:21:55.335  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,11-17 18:21:55.335 10711 10711 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.335  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
11-17 18:21:55.335 10711 10711 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:55.340  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,11-17 18:21:55.340 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,11-17 18:21:55.340  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,11-17 18:21:55.345  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,11-17 18:21:55.350 10259 10259 I TapandpayWidget:TanpandpayAppWidgetProvider: onReceive()
11-17 18:21:55.350 10259 10259 D TapandpayWidget:TanpandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
11-17 18:21:55.350 10259 10259 I TapandpayWidget:Utils: Clear T&P info.
11-17 18:21:55.350  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,11-17 18:21:55.350 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,11-17 18:21:55.350 10259 10259 D TapandpayWidget:TanpandpayAppWidgetProvider: Widget is not attached.
,11-17 18:21:55.350  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,11-17 18:21:55.355  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,11-17 18:21:55.355  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,11-17 18:21:55.355 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,11-17 18:21:55.360 10345 10688 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:21:55.360 10345 10688 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:21:55.360 10345 10688 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:21:55.360 10345 10688 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,11-17 18:21:55.360 10694 10710 I KLMS-2.4.521: : KLMSIntentService(): listeningToPackageRemoved().END
,11-17 18:21:55.365 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,11-17 18:21:55.375 10129 10129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,11-17 18:21:55.375 10694 10694 I KLMS-2.4.521: : KLMSIntentService(): onDestroy()
11-17 18:21:55.380 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
11-17 18:21:55.380 10711 10711 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,11-17 18:21:55.385  7708  7708 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,11-17 18:21:55.385  3527  3527 D ResourcesManager: creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,11-17 18:21:55.390  3527  3527 D ResourcesManager: creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,11-17 18:21:55.390 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,11-17 18:21:55.400 10711 10711 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,11-17 18:21:55.405 10711 10711 D elm:14491: ELMEngine.ELMEngine( context ).
,11-17 18:21:55.405 10711 10711 D elm:14491: MDMBridge.setEnterpriseBridge()
,11-17 18:21:55.405  7708 10730 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,11-17 18:21:55.405  7708 10730 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,11-17 18:21:55.415 10711 10711 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,11-17 18:21:55.415  3527  3995 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.415  3527  3995 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.415  3527  3995 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.415  3527  3995 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.415 10711 10711 D elm:14491: ElmAgentService : onCreate()
11-17 18:21:55.415 10711 10731 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,11-17 18:21:55.420 10711 10731 D elm:14491: MainReceiver.listeningToPackageRemoved()
11-17 18:21:55.420 10711 10731 D elm:14491: MDMBridge.getInstance()
11-17 18:21:55.420 10711 10731 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:21:55.420 10711 10731 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:21:55.430 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,11-17 18:21:55.430 10733 10733 E Zygote  : MountEmulatedStorage()
11-17 18:21:55.430 10733 10733 E Zygote  : v2
11-17 18:21:55.430 10733 10733 I libpersona: KNOX_SDCARD checking this for 10116
11-17 18:21:55.430 10733 10733 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.430 10733 10733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,11-17 18:21:55.435 10733 10733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.435  3527  3995 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10733 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,11-17 18:21:55.435 10733 10733 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:21:55.440 10345 10688 D ResourcesManager: creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,11-17 18:21:55.445 10711 10711 D elm:14491: ElmAgentService : onDestroy().
,11-17 18:21:55.450 10345 10688 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,11-17 18:21:55.455  3527  4188 I TactileAssist: enable value -1
11-17 18:21:55.455  3527  4188 I TactileAssist: internal enable value -1
11-17 18:21:55.455  3527  4188 I TactileAssist: intensity value -1
11-17 18:21:55.455  3527  4188 I TactileAssist: saveAppList value true
,11-17 18:21:55.465  3527  4188 I TactileAssist: List of disabled apps :
,11-17 18:21:55.465 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,11-17 18:21:55.465  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.465  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.465  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.465  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.470 10733 10733 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.470 10733 10733 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:55.475 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
11-17 18:21:55.475  3527  3527 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,11-17 18:21:55.480  3527  3527 D RCPManagerService: PackageReceiver onReceive()
11-17 18:21:55.480  3527  3527 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,11-17 18:21:55.480  3527  3527 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,11-17 18:21:55.480  3527  3527 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
11-17 18:21:55.480  3527  3527 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicy: uID is 10398
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:21:55.480  3527  3527 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
11-17 18:21:55.485  3527  3527 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
11-17 18:21:55.485 10748 10748 E Zygote  : MountEmulatedStorage()
11-17 18:21:55.485 10748 10748 E Zygote  : v2
11-17 18:21:55.485 10748 10748 I libpersona: KNOX_SDCARD checking this for 10019
11-17 18:21:55.485 10748 10748 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.485 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,11-17 18:21:55.485 10748 10748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,11-17 18:21:55.490 10748 10748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.490  3527  4189 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10748 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,11-17 18:21:55.490 10748 10748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:55.495 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,11-17 18:21:55.500  3527  3658 D TaskPersister: removeObsoleteFile: deleting file=25_task.xml
,11-17 18:21:55.500  3527  3527 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,11-17 18:21:55.505 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,11-17 18:21:55.510  3692  3692 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,11-17 18:21:55.510  3692  3692 D KeyguardUpdateMonitor: handleBatteryUpdate
,11-17 18:21:55.515 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,11-17 18:21:55.515 10733 10733 D ResourcesManager: creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,11-17 18:21:55.515  3692  3692 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,11-17 18:21:55.520  3527  3527 I MotionRecognitionService: Plugged
11-17 18:21:55.520  3527  3527 I MotionRecognitionService: setPowerConnected  = true
,11-17 18:21:55.520 10748 10748 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.520 10748 10748 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:55.535  3692  3692 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:21:55.535  3692  3692 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,11-17 18:21:55.535  3692  3692 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:21:55.535 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,11-17 18:21:55.540 10307 10372 E ActivityThread: Failed to find provider info for com.facebook.appmanager.installrecord
,11-17 18:21:55.545 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,11-17 18:21:55.545 10748 10748 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,11-17 18:21:55.555 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,11-17 18:21:55.565  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.565  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.565  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.565  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.570 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,11-17 18:21:55.575 10733 10745 E SQLiteLog: (284) automatic index on titles(filter_id)
,11-17 18:21:55.580 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,11-17 18:21:55.580 10764 10764 E Zygote  : MountEmulatedStorage()
11-17 18:21:55.580 10764 10764 E Zygote  : v2
11-17 18:21:55.580 10764 10764 I libpersona: KNOX_SDCARD checking this for 10114
11-17 18:21:55.580 10764 10764 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.580 10764 10764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,11-17 18:21:55.585 10764 10764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.585 10764 10764 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
11-17 18:21:55.585  3527  4189 I ActivityManager: Start proc com.facebook.katana:dash for broadcast com.facebook.katana/com.facebook.dash.receivers.DashPackageUninstallReceiver: pid=10764 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,11-17 18:21:55.595 10748 10748 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
11-17 18:21:55.595 10748 10748 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.example.hello
11-17 18:21:55.595 10748 10748 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,11-17 18:21:55.600  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.600  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.600  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.600  3527  4189 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.600 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,11-17 18:21:55.610 10764 10764 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.615 10764 10764 D ActivityThread: Added TimaKeyStore provider
11-17 18:21:55.615  2882  2882 I art     : Explicit concurrent mark sweep GC freed 8713(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.358ms total 26.934ms
,11-17 18:21:55.615 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,11-17 18:21:55.625 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,11-17 18:21:55.630  2882  2882 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 368us total 18.020ms
,11-17 18:21:55.635 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,11-17 18:21:55.645  2882  2882 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 375us total 10.877ms
,11-17 18:21:55.645 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,11-17 18:21:55.655 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,11-17 18:21:55.660 10780 10780 E Zygote  : MountEmulatedStorage()
11-17 18:21:55.660 10780 10780 E Zygote  : v2
11-17 18:21:55.660 10780 10780 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:21:55.660 10780 10780 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.660  3527  4189 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10780 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:21:55.660 10780 10780 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,11-17 18:21:55.665 10780 10780 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.670 10780 10780 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:55.675  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,11-17 18:21:55.680  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,11-17 18:21:55.680  9995  9995 D Compatibility: onReceive() it will make start service
,11-17 18:21:55.685 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,11-17 18:21:55.685 10764 10764 D ResourcesManager: creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,11-17 18:21:55.685  3527  3995 I ActivityManager: Killing 9889:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,11-17 18:21:55.690 10780 10780 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.690 10780 10780 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:55.690  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,11-17 18:21:55.695  3527  3552 D EnterpriseDeviceManagerService: Package has changed for user 0
11-17 18:21:55.695  3527  3552 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,11-17 18:21:55.695  9995 10795 D Compatibility: onHandleIntent()
,11-17 18:21:55.700  9995 10795 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10398, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
11-17 18:21:55.700  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,11-17 18:21:55.700 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,11-17 18:21:55.700  9995 10795 D Compatibility: found: 2
,11-17 18:21:55.700  9995 10795 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
11-17 18:21:55.700  9995 10795 D Compatibility: skipping ResolveInfo{be4acdc com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
11-17 18:21:55.700  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.700  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,11-17 18:21:55.700  9995 10795 D Compatibility: considering ResolveInfo{b30d1e5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
11-17 18:21:55.700  9995 10795 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,11-17 18:21:55.705  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.705  9995 10795 D Compatibility: enabling receiver ResolveInfo{1fdb54ba com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
11-17 18:21:55.705  3527  3578 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
11-17 18:21:55.705  3527  3578 D UsbHostManager: displayNotification : [02h,02h,01h]
,11-17 18:21:55.705  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.705 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,11-17 18:21:55.705  3527  3578 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
11-17 18:21:55.710  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
11-17 18:21:55.710  3527  3578 D UsbHostManager: displayNotification : [0ah,00h,00h]
,11-17 18:21:55.710  3527  3578 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
11-17 18:21:55.710  3527  3578 D UsbHostManager: displayNotification : [02h,0dh,00h]
11-17 18:21:55.710  3527  3578 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
11-17 18:21:55.710  3527  3578 D UsbHostManager: displayNotification : [0ah,00h,01h]
,11-17 18:21:55.715  9995 10795 D Compatibility: enabling receiver ResolveInfo{260fef6b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:21:55.715  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,11-17 18:21:55.715  3527  3578 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
11-17 18:21:55.715  3527  3660 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
11-17 18:21:55.715  3527  3578 D UsbHostManager: displayNotification : [09h,00h,00h]
11-17 18:21:55.715  3527  3660 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
11-17 18:21:55.715  3527  3660 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,11-17 18:21:55.720 10345 10345 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,11-17 18:21:55.720 10345 10688 D ResourcesManager: creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,11-17 18:21:55.720  9995 10795 D Compatibility: enabling receiver ResolveInfo{277dbac8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:21:55.725 10780 10780 D ResourcesManager: creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,11-17 18:21:55.725  9278  9278 D MtpClient: onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
11-17 18:21:55.725  9278  9278 D MtpClient: ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,11-17 18:21:55.730  9995 10795 D Compatibility: enabling receiver ResolveInfo{1e21a761 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:21:55.735 10345 10688 D ResourcesManager: creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,11-17 18:21:55.735  4036 10802 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:21:55.735  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.735  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.735  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.735  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:55.745 10345 10688 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
11-17 18:21:55.750  9995 10795 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
11-17 18:21:55.755 10780 10780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
,11-17 18:21:55.755 10803 10803 E Zygote  : MountEmulatedStorage()
11-17 18:21:55.755 10803 10803 E Zygote  : v2
11-17 18:21:55.755 10803 10803 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:21:55.755 10803 10803 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:55.760 10803 10803 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
11-17 18:21:55.760  3527  3660 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
11-17 18:21:55.760 10345 10688 D ResourcesManager: creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
11-17 18:21:55.760  3527  3660 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,11-17 18:21:55.765  3527  3542 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10803 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
11-17 18:21:55.765 10803 10803 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:55.770 10803 10803 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:55.800  3527  3552 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
11-17 18:21:55.800  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,11-17 18:21:55.805  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:55.805  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:55.810  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:55.810 10764 10764 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:21:55.815  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
11-17 18:21:55.815  3527  3599 I EventHub: Removing device '/dev/input/event10' due to inotify event
,11-17 18:21:55.820 10163 10163 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,11-17 18:21:55.820 10163 10163 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
11-17 18:21:55.820 10163 10163 D UserAnalysis.UserAnalysisBroadcastReceiver: Create SecureDbHelper
11-17 18:21:55.820  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:55.825  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:55.825  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.825  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,11-17 18:21:55.830  3527  3552 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:21:55.830  3527  3552 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:21:55.830  3527  3552 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
11-17 18:21:55.835  3527  3552 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,11-17 18:21:55.840 10163 10814 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:21:55.840  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.840  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,11-17 18:21:55.850 10163 10814 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
11-17 18:21:55.850 10163 10814 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
11-17 18:21:55.855 10163 10814 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-17 18:21:55.855 10803 10803 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:55.860  3527  3552 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
11-17 18:21:55.860 10803 10803 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:55.865  4036 10802 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,11-17 18:21:55.865  4036 10802 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:21:55.870  4036 10802 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
11-17 18:21:55.870  4036 10802 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4036
11-17 18:21:55.870  4036 10802 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at csx.d(PG:186)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at cun.g(PG:594)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:334)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1343)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at cuw.Tg(PG:368)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at cuy.ub(PG:301)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:55.870  4036 10802 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:21:55.875  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
11-17 18:21:55.875  3527  3599 I EventHub: Removing device '/dev/input/event7' due to inotify event
,11-17 18:21:55.880 10163 10814 W SQLiteOpenHelper: Opened privacy in read-only mode
,11-17 18:21:55.885 10163 10814 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:21:55.890 10163 10814 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
11-17 18:21:55.890 10163 10814 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:21:55.890 10163 10814 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.890 10163 10814 W System.err: 	at android,.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.890 10163 10814 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:55.890 10163 10814 W System.err: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
11-17 18:21:55.890 10163 10814 W System.err: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
11-17 18:21:55.890 10163 10814 W System.err: 	at java.lang.Thread.run(Thread.java:818)
11-17 18:21:55.895  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.900  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.910  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.910  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:21:55.910  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
11-17 18:21:55.915 10016 10016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2994 
11-17 18:21:55.920  3527  3599 I EventHub: Removing device '/dev/input/event8' due to inotify event
,11-17 18:21:55.925 10780 10820 E SQLiteLog: (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:21:55.930 10780 10820 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:55.930 10780 10820 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:21:55.935 10780 10820 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
11-17 18:21:55.935 10780 10820 E AndroidRuntime: Process: com.android.keychain, PID: 10780
11-17 18:21:55.935 10780 10820 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:55.935 10780 10820 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:21:55.935  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.935  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,11-17 18:21:55.940  3527  3818 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
11-17 18:21:55.940  3527  3599 I EventHub: Removing device '/dev/input/event9' due to inotify event
11-17 18:21:55.945  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.945  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:21:55.945  3527  3552 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,11-17 18:21:55.950  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:55.950  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:21:55.950  3527  3552 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:55.965 10016 10821 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:21:55.970 10016 10821 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:55.970 10016 10821 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:21:55.970 10016 10821 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDataba,se.java:699)
11-17 18:21:55.975  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.970 10016 10821 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:55.975  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.970 10016 10821 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:55.975  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:55.975  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:55.970 10016 10821 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:55.970 10016 10821 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
11-17 18:21:55.970 10016 10821 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:55.970 10016 10821 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:21:55.980 10764 10764 D AndroidRuntime: Shutting down VM
11-17 18:21:55.985 10764 10764 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:21:55.985 10764 10764 E AndroidRuntime: Process: com.facebook.katana:dash, PID: 10764
11-17 18:21:55.985 10764 10764 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application com.facebook.katana.app.FacebookApplication: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.katana/libs-dir-lock: open failed: EROFS (Read-only file system)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5088)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5944)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: Caused by: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.katana/libs-dir-lock: open failed: EROFS (Read-only file system)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.facebook.sosource.FBSoLoader.a(FBSoLoader.java:66)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.facebook.base.app.DelegatingApplication.attachBaseContext(DelegatingApplication.java:81)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.Application.attach(Application.java:205)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.Instrumentation.newApplication(Instrumentation.java:1004)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	... 10 more
11-17 18:21:55.985 10764 10764 E AndroidRuntime: Caused by: java.io.FileNotFoundException: /data/data/com.facebook.katana/libs-dir-lock: open failed: EROFS (Read-only file system)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.facebook.soloader.FileLocker.<init>(FileLocker.java:20)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.facebook.soloader.FileLocker.a(FileLocker.java:16)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.facebook.soloader.SysUtil.a(SysUtil.java:215)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.facebook.sosource.DirectorySoSourceWithAssets.a(DirectorySoSourceWithAssets.java:69)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at com.facebook.sosource.FBSoLoader.a(FBSoLoader.java:63)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	... 15 more
11-17 18:21:55.985 10764 10764 E AndroidRuntime: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at libcore.io.Posix.open(Native Method)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:21:55.985 10764 10764 E AndroidRuntime: 	... 22 more
11-17 18:21:55.990 10803 10803 D ResourcesManager: creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
11-17 18:21:56.000  3527  3599 I EventHub: Removing device '/dev/input/event11' due to inotify event
,11-17 18:21:56.010 10822 10822 E Zygote  : MountEmulatedStorage()
11-17 18:21:56.010 10822 10822 E Zygote  : v2
11-17 18:21:56.010 10822 10822 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:21:56.010 10822 10822 I libpersona: KNOX_SDCARD not a persona
11-17 18:21:56.015 10822 10822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
11-17 18:21:56.020 10822 10822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
11-17 18:21:56.025 10822 10822 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:21:56.025  3527  3542 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
11-17 18:21:56.030  3527  3552 D UsbSettingsManager: clearDefaults: com.example.hello
11-17 18:21:56.030  3527  3552 I CrashAnrDetector: onPackageRemoved : com.example.hello
11-17 18:21:56.035  3527  4253 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.keychain
11-17 18:21:56.035 10803 10803 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
11-17 18:21:56.035 10803 10803 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
11-17 18:21:56.035 10803 10803 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
11-17 18:21:56.040 10803 10803 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
11-17 18:21:56.040  3527  3599 I EventHub: Removing device '/dev/input/event12' due to inotify event
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5944)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:21:56.045 10803 10803 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:21:56.045 10803 10803 D AndroidRuntime: Shutting down VM
11-17 18:21:56.045 10803 10803 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:21:56.045 10803 10803 E AndroidRuntime: Process: com.sec.pcw.device, PID: 10803
11-17 18:21:56.045 10803 10803 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5944)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
11-17 18:21:56.045 10803 10803 E AndroidRuntime: 	... 11 more
11-17 18:21:56.050  3527  4023 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.facebook.katana:dash
11-17 18:21:56.050  3527  4190 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
11-17 18:21:56.055  3527  3785 I ActivityManager: Killing 9906:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,11-17 18:21:56.075  3527  3599 I EventHub: Removing device '/dev/input/event13' due to inotify event
,11-17 18:21:56.080  3527 10834 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop180.tmp: open failed: EROFS (Read-only file system)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:21:56.080  3527 10834 E DropBoxManagerService: 	... 5 more
,11-17 18:21:56.085  3527 10833 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop179.tmp: open failed: EROFS (Read-only file system)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:21:56.085  3527 10833 E DropBoxManagerService: 	... 5 more
,11-17 18:21:56.085  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:56.090  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:56.090  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:56.090  3527  3542 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:56.115  3527  3599 I EventHub: Removing device '/dev/input/event14' due to inotify event
11-17 18:21:56.115 10822 10822 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:21:56.115 10822 10822 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:56.125 10839 10839 E Zygote  : MountEmulatedStorage()
11-17 18:21:56.125 10839 10839 E Zygote  : v2
11-17 18:21:56.125 10839 10839 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:21:56.125 10839 10839 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:56.130 10839 10839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,11-17 18:21:56.135 10839 10839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,11-17 18:21:56.135 10839 10839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:56.140  3527  3542 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=10839 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:21:56.165  3527 10850 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:21:56.165  3527 10850 E DropBoxManagerService: 	... 5 more
,11-17 18:21:56.175  3527 10852 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:21:56.175  3527 10852 E DropBoxManagerService: 	... 5 more
11-17 18:21:56.195 10839 10839 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:21:56.195 10839 10839 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:56.220 10822 10822 D ResourcesManager: creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,11-17 18:21:56.245  3527  3542 I ActivityManager: Killing 9931:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
11-17 18:21:56.250  4476 10856 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,11-17 18:21:56.260  2875  2875 I MMD     : [status_update_modem_state, 114] Modem is offline (status:0)
11-17 18:21:56.260  2875  2875 I MMD     : [send_state_on_socket, 92] Send state '0' on modem status socket
11-17 18:21:56.260  4476 10856 D AccountUtils: Clearing selected account for com.example.hello
,11-17 18:21:56.260  2876  2928 D DIP     : New modem state received: 0
11-17 18:21:56.260  2876  2928 D DIP     : Modem OFF signal received
,11-17 18:21:56.265 10839 10839 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,11-17 18:21:56.270 10839 10839 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
```
