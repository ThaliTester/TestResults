#### Test 72145431fdae11f_thali04_samsung-SM-G920F Logs


```
--------- beginning of system
06-30 10:35:48.820  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
06-30 10:35:49.980  9631  9631 I FIPS_bssl: FIPS approved mode (1) | 9631 | app_process
06-30 10:35:49.990  9631  9631 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:35:49.990  9631  9631 D AndroidRuntime: CheckJNI is OFF
06-30 10:35:49.990  9631  9631 D AndroidRuntime: readGMSProperty: start
06-30 10:35:49.990  9631  9631 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:35:49.990  9631  9631 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:35:49.990  9631  9631 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:35:49.990  9631  9631 D AndroidRuntime: readGMSProperty: end
06-30 10:35:49.990  9631  9631 D AndroidRuntime: addProductProperty: start
06-30 10:35:50.060  9631  9631 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:35:50.170  9631  9631 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:35:50.190  9631  9631 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:35:50.220  9631  9631 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:35:50.240  3494  5970 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
06-30 10:35:50.250  3494  5970 D ResourcesManager: For user 0 new overlays fetched Null
06-30 10:35:50.250  3494  5970 D GameManagerService: identifyGamePackage. com.test.thalitest
06-30 10:35:50.250  3494  5970 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
06-30 10:35:50.260  3494  5970 D ActivityManager: mDVFSHelper.acquire()
06-30 10:35:50.260  3494  5957 D SSRM:n  : SIOP:: AP = 310, PST = 365 (W:12), CP = 253, CUR = 101, LCD = 0
06-30 10:35:50.260  3494  5970 V WindowManager: addAppToken: AppWindowToken{8d35ddd token=Token{9ba8db4 ActivityRecord{239ca87 u0 com.test.thalitest/.MainActivity t14}}} to stack=1 task=14 at 0
06-30 10:35:50.260  3494  3590 I InjectionManager: Inside getClassLibPath caller 
06-30 10:35:50.270  3494  3590 D SecWifiDisplayUtil: Metadata value : SecSettings2
06-30 10:35:50.270  3494  3590 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9e96b95 V.E...... R.....ID 0,0-0,0}
06-30 10:35:50.270  9657  9657 E Zygote  : v2
06-30 10:35:50.270  9657  9657 I libpersona: KNOX_SDCARD checking this for 10004
06-30 10:35:50.270  9657  9657 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:50.270  3494  5970 I ActivityManager: Start proc 9657:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 10:35:50.270  3494  3590 D ISSUE_DEBUG: InputChannelName : d9ad89b Starting com.test.thalitest
06-30 10:35:50.270  9657  9657 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
06-30 10:35:50.270  3494  5970 D InputDispatcher: Focused application set to: xxxx
06-30 10:35:50.270  3494  5970 D InputDispatcher: Focus left window: 5995
06-30 10:35:50.280  9631  9631 D AndroidRuntime: Shutting down VM
06-30 10:35:50.280  3494  3562 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{90ea75b u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
06-30 10:35:50.280  4077  4077 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
06-30 10:35:50.280  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 10:35:50.280  9657  9657 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:35:50.290  9657  9657 E Zygote  : accessInfo : 0
06-30 10:35:50.290  9657  9657 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 10:35:50.290  3045  3045 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
06-30 10:35:50.310  9657  9657 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:50.310  9657  9657 D ActivityThread: Added TimaKeyStore provider
06-30 10:35:50.310  3494  5957 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:35:50.320  3494  3988 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 10:35:50.320  3494  3988 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 10:35:50.320  3494  3590 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3494 uid:1000
06-30 10:35:50.320  3494  3590 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:35:50.320  3494  3590 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-30 10:35:50.320  3494  3562 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d9ad89b u0 d0 Starting com.test.thalitest}
06-30 10:35:50.330  3494  3988 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 10:35:50.340  3494  3494 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
06-30 10:35:50.340  3494  3560 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 10:35:50.350  3045  4675 I SurfaceFlinger: id=13 Removed VSBConnecti (5/12)
06-30 10:35:50.360  3045  3156 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/12)
06-30 10:35:50.360  3045  4675 I SurfaceFlinger: id=12 Removed VSBConnecti (6/11)
06-30 10:35:50.360  3045  3154 I SurfaceFlinger: id=12 Removed VSBConnecti (-2/11)
06-30 10:35:50.360  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fd18a7e88
06-30 10:35:50.360  3045  4459 D libEGL  : eglTerminate EGLDisplay = 0x7f9a2c4e78
06-30 10:35:50.360  3045  4459 D libEGL  : eglTerminate EGLDisplay = 0x7f9a2c4e78
06-30 10:35:50.360  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fd18a7e58
06-30 10:35:50.360  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fd18a7e58
06-30 10:35:50.360  3045  3154 I SurfaceFlinger: id=7 Removed MauncherAct (4/10)
06-30 10:35:50.360  3045  3156 I SurfaceFlinger: id=7 Removed MauncherAct (-2/10)
06-30 10:35:50.360  5995  5995 V ActivityThread: updateVisibility : ActivityRecord{b152392 token=android.os.BinderProxy@e4be6a4 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 10:35:50.370  4412  4412 V ActivityThread: updateVisibility : ActivityRecord{2de9992 token=android.os.BinderProxy@97f60f6 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
06-30 10:35:50.370  4412  4412 D Launcher: onTrimMemory. Level: 20
06-30 10:35:50.380  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fd18a7e88
06-30 10:35:50.380  3494  3590 V WindowStateAnimator: Finishing drawing window Window{d9ad89b u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 10:35:50.390  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fd18a7d58
,06-30 10:35:50.660  3494  3988 I WindowManager: Screenshot max retries 4 of Token{9ba8db4 ActivityRecord{239ca87 u0 com.test.thalitest/.MainActivity t14}} appWin=Window{d9ad89b u0 d0 Starting com.test.thalitest} drawState=2
06-30 10:35:50.680  9657  9657 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
06-30 10:35:50.680  3494  3511 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-30 10:35:50.680  9657  9657 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
06-30 10:35:50.700  9657  9657 D ResourcesManager: For user 0 new overlays fetched Null
06-30 10:35:50.700  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
06-30 10:35:50.710  3494  5957 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:35:50.710  3494  3587 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
06-30 10:35:50.720  9657  9657 I InjectionManager: Inside getClassLibPath caller 
06-30 10:35:50.730  9657  9657 D InjectionManager: InjectionManager
06-30 10:35:50.730  9657  9657 D InjectionManager: fillFeatureStoreMap com.test.thalitest
06-30 10:35:50.730  9657  9657 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
06-30 10:35:50.730  9657  9657 I InjectionManager: featureStore :{}
06-30 10:35:50.730  9657  9657 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
06-30 10:35:50.740  9657  9657 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
06-30 10:35:50.780  9657  9657 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410650)
06-30 10:35:50.820  9657  9657 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
06-30 10:35:50.830  9657  9657 D ResourcesManager: For user 0 new overlays fetched Null
06-30 10:35:50.830  9657  9657 I InjectionManager: Inside getClassLibPath caller 
06-30 10:35:50.840  9657  9657 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 10:35:50.870  9657  9657 I cr_LibraryLoader: Time to load native libraries: 15 ms (timestamps 1652-1667)
06-30 10:35:50.870  9657  9657 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 10:35:50.890  9657  9676 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
06-30 10:35:50.910  9657  9657 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2224612}
06-30 10:35:50.910  9657  9657 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 10:35:50.930  9657  9657 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:35:50.960  9657  9657 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-30 10:35:51.100  9657  9677 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
06-30 10:35:51.160  3494  3560 W ActivityManager: Activity pause timeout for ActivityRecord{239ca87 u0 com.test.thalitest/.MainActivity t14}
06-30 10:35:51.340  9657  9657 D libEGL  : loaded /vendor/lib/egl/libGLES_mali.so
06-30 10:35:51.380  9657  9657 D libEGL  : eglInitialize EGLDisplay = 0xfff9461c
06-30 10:35:51.390  9657  9657 D         : ro.exynos.dss isEnabled: 0
06-30 10:35:51.420  3494  4531 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
06-30 10:35:51.420  3494  4531 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29624 com.android.server.am.ActivityManagerService.registerReceiver:22495 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3988 
,06-30 10:35:51.490  9657  9657 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,06-30 10:35:51.510  9657  9657 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:35:51.510  9657  9657 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,06-30 10:35:51.510  9657  9657 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,06-30 10:35:51.510  9657  9657 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,06-30 10:35:51.530  9657  9657 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,06-30 10:35:51.540  9657  9657 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 10:35:51.570  9657  9657 D Activity: performCreate Call Injection manager
,06-30 10:35:51.570  9657  9657 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,06-30 10:35:51.580  9657  9657 D SecWifiDisplayUtil: Metadata value : SecSettings2
,06-30 10:35:51.590  9657  9657 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2263572 I.E...... R.....ID 0,0-0,0}
,06-30 10:35:51.600  9657  9714 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:35:51.600  3494  3988 D ISSUE_DEBUG: InputChannelName : c32f3ac com.test.thalitest/com.test.thalitest.MainActivity
,06-30 10:35:51.600  3494  3510 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 10:35:51.600  3494  3510 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:35:51.600  3494  3494 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 10:35:51.610  3494  3494 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 10:35:51.610  9657  9657 V ActivityThread: updateVisibility : ActivityRecord{7d29640 token=android.os.BinderProxy@52d9061 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 10:35:51.620  9657  9657 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 9657
,06-30 10:35:51.630  3494  3971 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/9657 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 10:35:51.650  9657  9676 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,06-30 10:35:51.650  9657  9657 D SecWifiDisplayUtil: Metadata value : SecSettings2
,06-30 10:35:51.670  3045  3045 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,06-30 10:35:51.680  3494  5958 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,06-30 10:35:51.680  3494  3988 D InputDispatcher: Focus entered window: 9657
,06-30 10:35:51.690  3494  3590 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3494 uid:1000
06-30 10:35:51.690  3494  3590 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 10:35:51.690  9657  9714 D libEGL  : eglInitialize EGLDisplay = 0xdd5ff7c4
06-30 10:35:51.690  9657  9714 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:35:51.690  9657  9714 D         : ro.exynos.dss isEnabled: 0
,06-30 10:35:51.700  9657  9714 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,06-30 10:35:51.700  9657  9657 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:35:51.720  3494  5968 V WindowStateAnimator: Finishing drawing window Window{c32f3ac u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-30 10:35:51.720  9657  9657 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,06-30 10:35:51.720  9657  9657 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 10:35:51.720  3494  5970 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 10:35:51.720  3494  3590 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 10:35:51.720  3494  3494 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:35:51.730  3494  3590 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s68ms (total +1s466ms)
,06-30 10:35:51.730  3494  3590 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{239ca87 u0 com.test.thalitest/.MainActivity t14} time:132521
06-30 10:35:51.730  3494  3590 D ActivityManager: mDVFSHelper.release()
06-30 10:35:51.730  3494  3590 D ViewRootImpl: #3 mView = null
06-30 10:35:51.730  3494  3494 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:35:51.730  3045  4459 I SurfaceFlinger: id=14 Removed uhalitest (7/10)
,06-30 10:35:51.730  3045  4675 I SurfaceFlinger: id=14 Removed uhalitest (-2/10)
,06-30 10:35:51.730  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fd18a7e88
,06-30 10:35:51.740  9657  9657 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 10:35:51.740  5109  5109 D SamsungIME: IMPL finishInput
,06-30 10:35:51.740  5109  5109 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
06-30 10:35:51.740  5109  5109 D SamsungIME: saveAndClear +
,06-30 10:35:51.740  5109  5109 D SamsungIME: saveAndClear -
,06-30 10:35:51.750  9657  9719 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:51.750  9657  9719 D libEGL  : eglInitialize EGLDisplay = 0xdaced3ec
,06-30 10:35:51.750  9657  9719 D         : ro.exynos.dss isEnabled: 0
,06-30 10:35:51.760  9657  9719 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,06-30 10:35:51.780  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fd18a7d58
,06-30 10:35:51.790  3494  4424 V WindowStateAnimator: Finishing drawing window Window{c32f3ac u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,06-30 10:35:51.810  9657  9657 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9657
,06-30 10:35:51.810  9657  9657 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@52d9061 time:132608
,06-30 10:35:51.960  9657  9657 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:35:52.090  9657  9726 D jxcore_app_log: JniHelper::setJavaVM(0xf4eb4000), pthread_self() = -634390224
,06-30 10:35:52.090  9657  9726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:52.090  9657  9726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:52.090  9657  9726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:52.090  9657  9726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:52.090  9657  9726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:35:52.090  9657  9726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5cfe4ed added. We now have 1 listener(s)
,06-30 10:35:52.090  9657  9726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 10:D3:8A:FB:85:D4
,06-30 10:35:52.090  9657  9726 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "10:D3:8A:FB:85:D4"
06-30 10:35:52.090  9657  9726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:35:52.090  9657  9726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 10:D3:8A:FB:85:D4
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:35:52.100  9657  9726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d80f70 added. We now have 1 listener(s)
06-30 10:35:52.100  9657  9726 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:35:52.100  9657  9726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:52.100  9657  9726 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:35:52.100  9657  9726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-30 10:35:52.100  9657  9726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:52.100  9657  9726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:35:52.100  9657  9726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 10:35:52.110  9657  9726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:35:52.110  9657  9726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 10:D3:8A:FB:85:D4
,06-30 10:35:52.110  9657  9726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:52.110  9657  9726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:52.110  9657  9726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:52.110  9657  9726 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:52.110  9657  9726 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:35:52.130  9657  9657 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:52.160  4159  4159 D Recents : onTaskStackChanged
,06-30 10:35:52.170  4159  4159 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,06-30 10:35:52.180  4159  4159 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:35:52.440  9657  9727 W jxcore-log: Initializing JXcore engine
06-30 10:35:52.440  9657  9727 W jxcore-log: JXcore engine is ready
,06-30 10:35:52.460  5131  5131 E audit   : type=1400 msg=audit(1467275752.460:268): avc:  denied  { ioctl } for  pid=9727 comm="Thread-123" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2465 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:35:52.460  5131  5131 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:35:52.460  5131  5131 E audit   : type=1300 msg=audit(1467275752.460:268): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d6f483c8 items=0 ppid=3098 ppcomm=main pid=9727 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 ses=4294967295 tty=(none) comm="Thread-123" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:35:52.460  5131  5131 E audit   : type=1327 msg=audit(1467275752.460:268): proctitle="com.test.thalitest"
06-30 10:35:52.460  5131  5131 E audit   : type=1320 msg=audit(1467275752.460:268): 
06-30 10:35:52.460  5131  5131 E audit   : type=1400 msg=audit(1467275752.460:269): avc:  denied  { ioctl } for  pid=9727 comm="Thread-123" path="socket:[37266]" dev="sockfs" ino=37266 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 10:35:52.460  5131  5131 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:35:52.460  5131  5131 E audit   : type=1300 msg=audit(1467275752.460:269): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=39 a1=5451 a2=2 a3=d6f483c8 items=0 ppid=3098 ppcomm=main pid=9727 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 ses=4294967295 tty=(none) comm="Thread-123" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:35:52.460  5131  5131 E audit   : type=1327 msg=audit(1467275752.460:269): proctitle="com.test.thalitest"
06-30 10:35:52.460  5131  5131 E audit   : type=1320 msg=audit(1467275752.460:269): 
,06-30 10:35:52.470  9657  9727 W jxcore-log: Starting JXcore engine
,06-30 10:35:52.510  9657  9727 W jxcore-log: Platform android
06-30 10:35:52.510  9657  9727 W jxcore-log: 
06-30 10:35:52.510  9657  9727 W jxcore-log: Process ARCH arm
06-30 10:35:52.510  9657  9727 W jxcore-log: 
,06-30 10:35:52.600  9657  9727 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:52.600  9657  9727 I jxcore-log: 
06-30 10:35:52.600  9657  9727 W jxcore-log: JXcore engine is started
,06-30 10:35:52.610  9657  9726 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:35:52.610  3494  3511 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in null rsrc of package com.android.packageinstaller
,06-30 10:35:52.620  3494  3511 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:35:52.620  3494  3511 D GameManagerService: identifyGamePackage. com.android.packageinstaller
06-30 10:35:52.620  3494  3511 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.android.packageinstaller)
,06-30 10:35:52.620  3494  3511 D ActivityManager: mDVFSHelper.acquire()
,06-30 10:35:52.620  3494  3511 V WindowManager: addAppToken: AppWindowToken{bb09fdc token=Token{9e1ac4f ActivityRecord{2c426ae u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t14}}} to stack=1 task=14 at 1
,06-30 10:35:52.630  9728  9728 E Zygote  : v2
06-30 10:35:52.630  9728  9728 I libpersona: KNOX_SDCARD checking this for 10130
06-30 10:35:52.630  9728  9728 I libpersona: KNOX_SDCARD not a persona
06-30 10:35:52.630  9728  9728 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
06-30 10:35:52.630  9728  9728 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:35:52.630  9728  9728 E Zygote  : accessInfo : 0
06-30 10:35:52.630  9728  9728 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
06-30 10:35:52.630  3494  3511 I ActivityManager: Start proc 9728:com.android.packageinstaller/u0a130 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 10:35:52.630  3494  3511 D InputDispatcher: Focused application set to: xxxx
06-30 10:35:52.640  3494  3511 D InputDispatcher: Focus left window: 9657
,06-30 10:35:52.640  9657  9726 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 10:35:52.640  3494  3590 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3494 uid:1000
06-30 10:35:52.640  3494  3590 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 10:35:52.640  9728  9728 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:35:52.640  9728  9728 D ActivityThread: Added TimaKeyStore provider
,06-30 10:35:52.650  3494  6920 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 10:35:52.650  3494  3560 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
06-30 10:35:52.650  3494  3494 D GameManagerService: NotifyRunnable. pkg: com.android.packageinstaller, type: 4, isMinimized: false, isTunableApp: false
,06-30 10:35:52.950  3494  6920 I WindowManager: Screenshot max retries 4 of Token{9e1ac4f ActivityRecord{2c426ae u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t14}} appWin=Window{c32f3ac u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 10:35:52.960  9728  9728 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package com.android.packageinstaller
,06-30 10:35:52.960  3494  4369 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
06-30 10:35:52.960  9728  9728 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-30 10:35:52.970  9728  9728 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:35:52.970  9728  9728 I InjectionManager: Inside getClassLibPath caller 
,06-30 10:35:52.980  9728  9728 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
,06-30 10:35:52.980  9728  9728 D InjectionManager: InjectionManager
,06-30 10:35:52.980  9728  9728 D InjectionManager: fillFeatureStoreMap com.android.packageinstaller
06-30 10:35:52.980  9728  9728 I InjectionManager: Constructor com.android.packageinstaller, Feature store :{}
06-30 10:35:52.980  9728  9728 I InjectionManager: featureStore :{}
,06-30 10:35:52.990  3494  5957 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true],
,06-30 10:35:52.990  9728  9728 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package com.android.packageinstaller
,06-30 10:35:53.000  9728  9728 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package com.android.packageinstaller
,06-30 10:35:53.020  9728  9728 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.packageinstaller rsrc of package com.test.thalitest
,06-30 10:35:53.030  9728  9728 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:35:53.040  9728  9728 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package android
,06-30 10:35:53.050  9728  9728 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:35:53.050  9728  9728 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package android
,06-30 10:35:53.060  9728  9728 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package android
,06-30 10:35:53.060  9728  9728 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package android
,06-30 10:35:53.060  9728  9728 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package android
,06-30 10:35:53.060  9728  9728 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package android
,06-30 10:35:53.160  9728  9728 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package android
,06-30 10:35:53.160  9728  9728 D Activity: performCreate Call Injection manager
,06-30 10:35:53.170  9728  9728 I InjectionManager: dispatchOnViewCreated > Target : com.android.packageinstaller.permission.ui.GrantPermissionsActivity isFragment :false
,06-30 10:35:53.170  9728  9728 D SecWifiDisplayUtil: Metadata value : SecSettings2
,06-30 10:35:53.170  9728  9728 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f97543d I.E...... R.....I. 0,0-0,0}
,06-30 10:35:53.170  9728  9740 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:35:53.180  3494  5975 D ISSUE_DEBUG: InputChannelName : 1128e61 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-30 10:35:53.180  3494  3511 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,06-30 10:35:53.180  3494  3511 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:35:53.180  3494  3494 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:35:53.180  3494  3494 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 10:35:53.180  3494  3494 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 10:35:53.200  3045  3045 I SurfaceFlinger: id=16 createSurf (193x193),1 flag=4, HrantPermis
,06-30 10:35:53.200  3494  3562 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1128e61 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-30 10:35:53.200  4077  4077 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 10:35:53.210  3494  4121 D InputDispatcher: Focus entered window: 9728,
,06-30 10:35:53.210  3494  3590 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3494 uid:1000
06-30 10:35:53.210  3494  3590 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 10:35:53.250  9728  9740 D libEGL  : loaded /vendor/lib64/egl/libGLES_mali.so
,06-30 10:35:53.270  3494  4042 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/14_task.xml.bak
,06-30 10:35:53.270  9728  9740 D libEGL  : eglInitialize EGLDisplay = 0x7f9097f178
06-30 10:35:53.270  9728  9740 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:35:53.270  9728  9740 D         : ro.exynos.dss isEnabled: 0
,06-30 10:35:53.280  9728  9740 D mali_winsys: new_window_surface returns 0x3000,  [1528x2656]-format:1
,06-30 10:35:53.300  9728  9728 V ActivityThread: updateVisibility : ActivityRecord{da9cdf5 token=android.os.BinderProxy@951d19d {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 10:35:53.300  9728  9728 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 10:35:53.300  3494  3510 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 10:35:53.300  5109  5109 D SamsungIME: IMPL finishInput
06-30 10:35:53.300  5109  5109 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
06-30 10:35:53.300  5109  5109 D SamsungIME: saveAndClear +
06-30 10:35:53.300  5109  5109 D SamsungIME: saveAndClear -
06-30 10:35:53.300  5109  5109 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 10:35:53.330  9728  9728 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:35:53.330  9728  9740 D libGLESv1: DTS_GLAPI : DTS is not allowed for Package : com.android.packageinstaller
,06-30 10:35:53.380  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fd18a7d58
,06-30 10:35:53.380  3494  6920 V WindowStateAnimator: Finishing drawing window Window{1128e61 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
06-30 10:35:53.380  9728  9728 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@951d19d time:134175
,06-30 10:35:53.390  3494  3590 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:35:53.390  3494  3494 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:35:53.390  3494  3494 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:35:53.400  3494  3590 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +445ms (total +774ms)
,06-30 10:35:53.400  3494  3590 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c426ae u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t14} time:134193
,06-30 10:35:53.400  3494  3590 D ActivityManager: mDVFSHelper.release()
,06-30 10:35:53.880  3494  4276 E Watchdog: !@Sync 4 [06-30 10:35:53.887]
,06-30 10:35:54.180  4159  4159 D Recents : onTaskStackChanged
,06-30 10:35:54.940  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:35:56.710  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -4 -200 -4 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:35:56.710  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:35:56.720  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -6 -200 -6 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:35:56.720  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:35:59.050  3494  5957 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:35:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:36:00.310  3494  3616 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 10:36:00.310  3494  5957 D SSRM:n  : SIOP:: AP = 310, PST = 349 (W:12), CP = 252, CUR = 101, LCD = 0
,06-30 10:36:00.340  3494  3616 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 10:36:08.830  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:10.360  3494  5957 D SSRM:n  : SIOP:: AP = 300, PST = 338 (W:12), CP = 251, CUR = 101, LCD = 0
,06-30 10:36:12.490  3494  3510 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:36:12.500  3494  3510 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:36:12.500  3494  3510 D BatteryService: online:4, current avg:6, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:36:12.500  3494  3510 D BatteryService: stay LED for fully charged
06-30 10:36:12.500  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:36:12.510  3494  3494 I MotionRecognitionService: Plugged
06-30 10:36:12.510  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:36:12.510  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:36:12.510  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:36:12.510  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:36:12.510  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:36:12.510  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:36:12.510  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:36:12.520  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:36:12.520  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:12.520  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2,
,06-30 10:36:12.540  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:36:12.550  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:36:12.550  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:36:12.550  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:13.300  4327  5656 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:36:15.040  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:36:15.060  3494  4346 D NtpTrustedTime: forceRefresh: no connectivity
06-30 10:36:15.060  3494  4346 V AlarmManager:  remove PendingIntent] PendingIntent{bd5789d: PendingIntentRecord{b126112 android broadcastIntent}}
,06-30 10:36:15.110  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d489de0 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a75e8d3 4327:com.google.android.gms.persistent/u0a10}
,06-30 10:36:15.120  3494  4498 V AlarmManager:  remove PendingIntent] PendingIntent{345a899: PendingIntentRecord{22f88cf com.google.android.gms broadcastIntent}}
,06-30 10:36:15.140  3494  3949 I ActivityManager: Start proc 9796:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-30 10:36:15.150  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:36:15.150  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:36:15.150  9796  9796 E Zygote  : v2
06-30 10:36:15.150  9796  9796 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:36:15.150  9796  9796 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
06-30 10:36:15.150  9796  9796 I libpersona: KNOX_SDCARD not a persona
,06-30 10:36:15.160  9796  9796 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:36:15.170  9796  9796 E Zygote  : accessInfo : 0
,06-30 10:36:15.210  9796  9796 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:36:15.210  9796  9796 D ActivityThread: Added TimaKeyStore provider
,06-30 10:36:15.250  9796  9796 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,06-30 10:36:15.250  3494  3971 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-30 10:36:15.250  9796  9796 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-30 10:36:15.260  9796  9796 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:36:15.260  9796  9796 I InjectionManager: Inside getClassLibPath caller 
,06-30 10:36:15.270  9796  9796 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,06-30 10:36:15.270  9796  9796 D InjectionManager: InjectionManager
06-30 10:36:15.270  9796  9796 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,06-30 10:36:15.270  9796  9796 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
06-30 10:36:15.270  9796  9796 I InjectionManager: featureStore :{}
,06-30 10:36:16.020  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:16.050  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:16.050  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:16.090  4327  6770 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:36:16.090  4327  6770 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:36:16.090  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:36:16.090  4327  6770 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:36:16.090  4327  6770 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:36:16.090  4327  6770 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:36:16.130  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:36:16.130  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:36:16.130  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 10:36:16.140  3494  4521 I ActivityManager: Killing 8743:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #31
,06-30 10:36:16.170  3494  3971 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,06-30 10:36:19.770  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -8 -200 -8 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:36:19.780  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:36:19.780  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -7 -200 -7 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:36:19.790  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:36:20.400  3494  5957 D SSRM:n  : SIOP:: AP = 300, PST = 330 (W:12), CP = 250, CUR = 6, LCD = 0
,06-30 10:36:23.880  3494  4276 E Watchdog: !@Sync 5 [06-30 10:36:23.889]
,06-30 10:36:28.830  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:30.460  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 322 (W:14), CP = 249, CUR = 6, LCD = 0
,06-30 10:36:40.330  3494  5958 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,06-30 10:36:40.340  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e41e31a u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{36ac4cf 9176:com.samsung.android.sm.provider/1000}
,06-30 10:36:40.450  3494  5958 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,06-30 10:36:40.460  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9f3e028 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{36ac4cf 9176:com.samsung.android.sm.provider/1000}
,06-30 10:36:40.490  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 313 (W:14), CP = 248, CUR = 6, LCD = 0
,06-30 10:36:42.560  3494  4424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:36:42.560  3494  4424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4324, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:36:42.560  3494  4424 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:36:42.560  3494  4424 D BatteryService: stay LED for fully charged
06-30 10:36:42.560  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:36:42.560  3494  3494 I MotionRecognitionService: Plugged
06-30 10:36:42.560  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:36:42.560  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:36:42.560  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:36:42.570  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:36:42.570  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:36:42.570  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:36:42.570  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:36:42.570  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:36:42.570  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:36:42.570  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:36:42.590  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:36:42.600  4676  4676 D BatteryMonitor: new battery level: 100
06-30 10:36:42.600  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:36:42.600  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:45.110  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:36:45.180  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fa407d u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a75e8d3 4327:com.google.android.gms.persistent/u0a10}
,06-30 10:36:45.190  3494  4121 V AlarmManager:  remove PendingIntent] PendingIntent{be1bb72: PendingIntentRecord{22f88cf com.google.android.gms broadcastIntent}}
,06-30 10:36:45.420  3494  3505 I art     : Background partial concurrent mark sweep GC freed 56259(4MB) AllocSpace objects, 55(1100KB) LOS objects, 31% free, 34MB/50MB, paused 2.483ms total 229.610ms
,06-30 10:36:45.720  4327  4327 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b8bf6458-d589-45d9-af3e-a13123938f5e
,06-30 10:36:45.730  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:45.730  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:45.730  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:45.780  4327  6771 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:36:45.780  4327  6771 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:36:45.780  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:36:45.780  4327  6771 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:36:45.780  4327  6771 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:36:45.780  4327  6771 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:36:45.830  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:36:45.830  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:36:45.830  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 10:36:45.920  4620  9863 D UdcContextInitService: registered all accounts: true
,06-30 10:36:45.920  4327  4729 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 10:36:45.950  4327  9869 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 10:36:46.020  3494  4121 V AlarmManager:  remove PendingIntent] PendingIntent{f8bf22a: PendingIntentRecord{22f88cf com.google.android.gms broadcastIntent}}
,06-30 10:36:46.080  4327  9869 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10010, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 10:36:46.090  4327  9874 I VacuumService: Vacuum at: now=1467275806104 tag=VacuumService
,06-30 10:36:46.100  4327  4327 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 10:36:46.190  3494  4521 V AlarmManager:  remove PendingIntent] PendingIntent{8891af7: PendingIntentRecord{22f88cf com.google.android.gms broadcastIntent}}
,06-30 10:36:48.830  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:36:50.540  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 310 (W:14), CP = 247, LCD = 0
,06-30 10:36:52.610  3494  3988 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:36:52.620  3494  3988 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:36:52.620  3494  3988 D BatteryService: online:4, current avg:74, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:114
06-30 10:36:52.620  3494  3988 D BatteryService: stay LED for fully charged
06-30 10:36:52.620  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:36:52.630  3494  3494 I MotionRecognitionService: Plugged
06-30 10:36:52.630  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:36:52.630  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:36:52.630  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:36:52.630  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:36:52.630  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:36:52.630  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:36:52.630  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:36:52.630  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:36:52.630  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:36:52.640  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:36:52.640  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:36:52.650  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:36:52.660  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:36:52.660  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:36:53.890  3494  4276 E Watchdog: !@Sync 6 [06-30 10:36:53.896]
,06-30 10:36:55.050  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:36:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:37:00.600  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 309 (W:14), CP = 247, CUR = 74, LCD = 0
,06-30 10:37:02.670  3494  3511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:37:02.670  3494  3511 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:37:02.670  3494  3511 D BatteryService: online:4, current avg:96, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:112
06-30 10:37:02.670  3494  3511 D BatteryService: stay LED for fully charged
06-30 10:37:02.670  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:37:02.680  3494  3494 I MotionRecognitionService: Plugged
06-30 10:37:02.680  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:37:02.680  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:37:02.680  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:37:02.680  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:37:02.680  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:37:02.680  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:37:02.680  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:02.680  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:02.680  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:37:02.680  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:02.690  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:37:02.700  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:37:02.710  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:02.710  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:08.830  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:10.650  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 307 (W:16), CP = 246, CUR = 96, LCD = 0
,06-30 10:37:12.160  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:37:12.200  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:37:12.200  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:37:12.210  3055  3733 D EnterpriseController: netId is 0
06-30 10:37:12.210  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10010
,06-30 10:37:12.220  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:37:12.220  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:37:12.230  3494  5975 V AlarmManager:  remove PendingIntent] PendingIntent{a5c9c82: PendingIntentRecord{654908a com.google.android.gms broadcastIntent}}
,06-30 10:37:12.260  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{faa6f93 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{30cf72 8377:com.google.android.talk/u0a114}
,06-30 10:37:12.740  3494  6920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:37:12.740  3494  6920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:37:12.740  3494  6920 D BatteryService: online:4, current avg:102, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:97
06-30 10:37:12.740  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:37:12.740  3494  6920 D BatteryService: stay LED for fully charged
06-30 10:37:12.750  3494  3494 I MotionRecognitionService: Plugged
06-30 10:37:12.750  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:37:12.750  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:37:12.750  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:37:12.750  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:37:12.750  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:37:12.750  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:37:12.750  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:37:12.750  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:12.760  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:37:12.750  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:12.770  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:37:12.780  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:12.780  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:12.790  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:37:15.140  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:37:15.180  6478  6478 I PedometerService: onStartCommand  true, true
,06-30 10:37:15.200  3494  4346 D NtpTrustedTime: forceRefresh: no connectivity
06-30 10:37:15.200  3494  4346 V AlarmManager:  remove PendingIntent] PendingIntent{bd5789d: PendingIntentRecord{b126112 android broadcastIntent}}
,06-30 10:37:15.230  3494  4346 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 10:37:15.810  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:15.840  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:15.840  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:15.890  4327  4339 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:37:15.890  4327  4339 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:37:15.890  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:37:15.890  4327  4339 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:37:15.890  4327  4339 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:37:15.890  4327  4339 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:37:15.930  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:37:15.930  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:37:15.930  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 10:37:20.700  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 298 (W:16), CP = 245, CUR = 102, LCD = 0
,06-30 10:37:22.200  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:37:22.200  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:37:22.800  3494  3510 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:37:22.800  3494  3510 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:37:22.800  3494  3510 D BatteryService: online:4, current avg:102, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:104
06-30 10:37:22.800  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:37:22.800  3494  3510 D BatteryService: stay LED for fully charged
06-30 10:37:22.810  3494  3494 I MotionRecognitionService: Plugged
06-30 10:37:22.810  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:37:22.810  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:37:22.810  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:37:22.810  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:37:22.810  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:37:22.810  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:37:22.810  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:37:22.810  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:22.820  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:37:22.810  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:22.830  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:37:22.840  4676  4676 D BatteryMonitor: new battery level: 100
06-30 10:37:22.840  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:22.840  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:23.890  3494  4276 E Watchdog: !@Sync 7 [06-30 10:37:23.903]
,06-30 10:37:28.840  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:30.760  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:16), CP = 245, CUR = 102, LCD = 0
,06-30 10:37:32.860  3494  4424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:37:32.860  3494  4424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:37:32.860  3494  4424 D BatteryService: online:4, current avg:99, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:95
06-30 10:37:32.860  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:37:32.870  3494  4424 D BatteryService: stay LED for fully charged
06-30 10:37:32.870  3494  3494 I MotionRecognitionService: Plugged
06-30 10:37:32.870  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:37:32.870  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:37:32.870  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:37:32.870  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:37:32.870  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:37:32.870  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:37:32.870  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:32.890  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:32.890  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:37:32.890  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:32.900  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:37:32.910  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:37:32.910  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:32.910  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:40.790  3494  5957 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:16), CP = 244, CUR = 99, LCD = 0
,06-30 10:37:42.930  3494  4521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:37:42.930  3494  4521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:37:42.930  3494  4521 D BatteryService: online:4, current avg:95, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:87
06-30 10:37:42.930  3494  4521 D BatteryService: stay LED for fully charged
06-30 10:37:42.930  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:37:42.930  3494  3494 I MotionRecognitionService: Plugged
06-30 10:37:42.930  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:37:42.930  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:37:42.930  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:37:42.930  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:37:42.930  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:37:42.930  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:37:42.930  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:37:42.940  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:37:42.940  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:37:42.940  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:37:42.960  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:37:42.970  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:37:42.970  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:37:42.970  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:37:44.240  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -4 -200 -4 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:37:44.260  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:37:44.260  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -6 -200 -6 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:37:44.260  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:37:46.310  4327  9869 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 10:37:46.310  4327  9869 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 10:37:46.310  4327  9869 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 10:37:46.310  4327  9869 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 10:37:46.310  4327  9869 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 10:37:46.350  4327  9869 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 10:37:48.840  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:37:50.840  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 291 (W:18), CP = 244, CUR = 95, LCD = 0
,06-30 10:37:53.900  3494  4276 E Watchdog: !@Sync 8 [06-30 10:37:53.911]
,06-30 10:37:55.160  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:37:55.290  4510  4564 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 2Kb duration : 120ms lastUpdatedAfter : 152526ms
,06-30 10:37:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:38:00.870  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:18), CP = 244, CUR = 95, LCD = 0
,06-30 10:38:08.840  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:10.910  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:18), CP = 243, CUR = 95, LCD = 0
,06-30 10:38:12.980  3494  4424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:38:12.990  3494  4424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:38:12.990  3494  4424 D BatteryService: online:4, current avg:6, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:38:12.990  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:38:12.990  3494  3494 I MotionRecognitionService: Plugged
06-30 10:38:12.990  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:38:12.990  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:38:12.990  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:38:12.990  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:38:12.990  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:38:12.990  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:38:12.990  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:38:12.990  3494  4424 D BatteryService: stay LED for fully charged
,06-30 10:38:13.000  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:38:13.000  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:13.000  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:38:13.020  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:38:13.030  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:38:13.030  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:13.030  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:20.960  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:18), CP = 243, CUR = 6, LCD = 0
,06-30 10:38:23.910  3494  4276 E Watchdog: !@Sync 9 [06-30 10:38:23.920]
,06-30 10:38:28.850  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:31.010  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:20), CP = 243, CUR = 6, LCD = 0
,06-30 10:38:41.070  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:20), CP = 243, CUR = 6, LCD = 0
,06-30 10:38:43.030  3494  5968 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:38:43.030  3494  5968 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:38:43.030  3494  5968 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
,06-30 10:38:43.030  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:43.040  3494  5968 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
06-30 10:38:43.040  3494  5968 D BatteryService: stay LED for fully charged
,06-30 10:38:43.050  3494  3494 I MotionRecognitionService: Plugged
06-30 10:38:43.050  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:38:43.050  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:38:43.050  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:38:43.050  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:38:43.050  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:38:43.050  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:38:43.050  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:38:43.050  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:38:43.050  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:43.060  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:38:43.070  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:38:43.080  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:43.080  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:43.090  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:38:48.850  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:51.140  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:20), CP = 242, LCD = 0
,06-30 10:38:51.170  3494  3931 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:38:51.170  3494  3931 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
06-30 10:38:51.170  3494  3930 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:38:51.180  3494  3931 I TLC_TIMA_PKM_initialize: initializing...
,06-30 10:38:51.180  3494  3931 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
,06-30 10:38:51.180  3494  3931 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: root = 0, root_len = 1
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: device_id = 0x0
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: tlc_open() was called
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: Opening MobiCore device
,06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: Allocating message buffer for TCI
06-30 10:38:51.180  3494  3931 I TZ: mc_tlc_communication: Opening the session
,06-30 10:38:51.220  3494  3931 I TZ: mc_tlc_communication: tlc_open() succeeded
,06-30 10:38:51.230  3494  3931 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 10:38:53.920  3494  4276 E Watchdog: !@Sync 10 [06-30 10:38:53.927]
,06-30 10:38:55.390  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:38:57.940  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:38:57.940  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:38:57.950  3494  3931 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:38:57.960  3494  3931 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:39:01.190  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:20), CP = 242, LCD = 0
,06-30 10:39:08.850  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:11.250  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:22), CP = 242, LCD = 0
,06-30 10:39:13.080  3494  4530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:39:13.080  3494  4530 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:39:13.080  3494  4530 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:39:13.080  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:39:13.080  3494  4530 D BatteryService: stay LED for fully charged
06-30 10:39:13.090  3494  3494 I MotionRecognitionService: Plugged
06-30 10:39:13.090  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:39:13.090  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:39:13.090  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:39:13.090  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:39:13.090  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:39:13.090  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:39:13.090  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:39:13.100  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:39:13.100  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:13.110  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2,
,06-30 10:39:13.120  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:39:13.120  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:39:13.130  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:13.130  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:16.180  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:39:16.220  3494  3949 E Parcel  : Class not found when unmarshalling: com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler
06-30 10:39:16.220  3494  3949 E Parcel  : java.lang.ClassNotFoundException: com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler
06-30 10:39:16.220  3494  3949 E Parcel  : 	at java.lang.Class.classForName(Native Method)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at java.lang.Class.forName(Class.java:324)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.os.Parcel.readParcelableCreator(Parcel.java:2404)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.os.Parcel.readParcelable(Parcel.java:2358)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.os.Parcel.readValue(Parcel.java:2264)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.os.Parcel.readArrayMapInternal(Parcel.java:2614)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.os.BaseBundle.unparcel(BaseBundle.java:221)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.os.Bundle.putAll(Bundle.java:182)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.content.Intent.fillIn(Intent.java:8227)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at com.android.server.am.PendingIntentRecord.sendInner(PendingIntentRecord.java:265)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at com.android.server.am.PendingIntentRecord.sendInner(PendingIntentRecord.java:233)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at com.android.server.am.PendingIntentRecord.send(PendingIntentRecord.java:225)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at android.app.PendingIntent.send(PendingIntent.java:851)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at com.android.server.AlarmManagerService.deliverAlarmsLocked(AlarmManagerService.java:2989)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at com.android.server.AlarmManagerService$AlarmThread.run(AlarmManagerService.java:3233)
06-30 10:39:16.220  3494  3949 E Parcel  : Caused by: java.lang.ClassNotFoundException: com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler
06-30 10:39:16.220  3494  3949 E Parcel  : 	at java.lang.Class.classForName(Native Method)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
06-30 10:39:16.220  3494  3949 E Parcel  : 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
06-30 10:39:16.220  3494  3949 E Parcel  : 	... 15 more
06-30 10:39:16.220  3494  3949 E Parcel  : Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack trace available
,06-30 10:39:16.230  3494  3949 W Intent  : Failure filling in extras
06-30 10:39:16.230  3494  3949 W Intent  : android.os.BadParcelableException: ClassNotFoundException when unmarshalling: com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.os.Parcel.readParcelableCreator(Parcel.java:2432)
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.os.Parcel.readParcelable(Parcel.java:2358)
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.os.Parcel.readValue(Parcel.java:2264)
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.os.Parcel.readArrayMapInternal(Parcel.java:2614)
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.os.BaseBundle.unparcel(BaseBundle.java:221)
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.os.Bundle.putAll(Bundle.java:182)
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.content.Intent.fillIn(Intent.java:8227)
06-30 10:39:16.230  3494  3949 W Intent  : 	at com.android.server.am.PendingIntentRecord.sendInner(PendingIntentRecord.java:265)
06-30 10:39:16.230  3494  3949 W Intent  : 	at com.android.server.am.PendingIntentRecord.sendInner(PendingIntentRecord.java:233)
06-30 10:39:16.230  3494  3949 W Intent  : 	at com.android.server.am.PendingIntentRecord.send(PendingIntentRecord.java:225)
06-30 10:39:16.230  3494  3949 W Intent  : 	at android.app.PendingIntent.send(PendingIntent.java:851)
06-30 10:39:16.230  3494  3949 W Intent  : 	at com.android.server.AlarmManagerService.deliverAlarmsLocked(AlarmManagerService.java:2989)
06-30 10:39:16.230  3494  3949 W Intent  : 	at com.android.server.AlarmManagerService$AlarmThread.run(AlarmManagerService.java:3233)
,06-30 10:39:16.250  3494  3560 I ActivityManager: Start proc 10016:com.sec.spp.push:RemoteNotiProcess/u0a33 for broadcast-3 com.sec.spp.push/.notisvc.alarm.AlarmEventManager
,06-30 10:39:16.260  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:39:16.260  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:39:16.270 10016 10016 E Zygote  : v2
,06-30 10:39:16.290 10016 10016 I libpersona: KNOX_SDCARD checking this for 10033
,06-30 10:39:16.290 10016 10016 I libpersona: KNOX_SDCARD not a persona
,06-30 10:39:16.290 10016 10016 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
,06-30 10:39:16.290 10016 10016 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:39:16.300 10016 10016 E Zygote  : accessInfo : 0
,06-30 10:39:16.300 10016 10016 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.spp.push:RemoteNotiProcess 
,06-30 10:39:16.350 10016 10016 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:39:16.350 10016 10016 D ActivityThread: Added TimaKeyStore provider
,06-30 10:39:16.380  3494  5970 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a59b4df u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c8252c 10016:com.sec.spp.push:RemoteNotiProcess/u0a33}
,06-30 10:39:16.390 10016 10016 W ResourcesManager: getTopLevelResources: /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk / 1.0 running in com.sec.spp.push rsrc of package com.sec.spp.push
,06-30 10:39:16.390  3494  4369 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-30 10:39:16.390 10016 10016 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-30 10:39:16.390 10016 10016 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:39:16.400 10016 10016 I InjectionManager: Inside getClassLibPath caller 
,06-30 10:39:16.400 10016 10016 W System  : ClassLoader referenced unknown path: /system/priv-app/SPPPushClient_Prod/lib/arm64
,06-30 10:39:16.420 10016 10016 D SPPClientService: Create
,06-30 10:39:16.420 10016 10016 D InjectionManager: InjectionManager
06-30 10:39:16.420 10016 10016 D InjectionManager: fillFeatureStoreMap com.sec.spp.push
,06-30 10:39:16.420 10016 10016 I InjectionManager: Constructor com.sec.spp.push, Feature store :{}
06-30 10:39:16.420 10016 10016 I InjectionManager: featureStore :{}
,06-30 10:39:16.420 10016 10031 D SPPClientService: Create
,06-30 10:39:16.430 10016 10031 E SPPClientService: ShipBuild Binary : True
,06-30 10:39:16.630  3494  3971 I ActivityManager: Killing 8333:com.google.android.gm/u0a112 (adj 15): DHA:empty #31
,06-30 10:39:16.660  3494  5970 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,06-30 10:39:17.580  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:17.610  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:17.610  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:17.650  4327  6770 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:39:17.650  4327  6770 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:39:17.650  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:39:17.650  4327  6770 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:39:17.650  4327  6770 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:39:17.650  4327  6770 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:39:17.680  4327  6770 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:39:17.680  4327  6770 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:39:17.680  4327  6770 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:39:17.680  4327  6770 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:39:17.680  4327  6770 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:39:17.680  4327  6770 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:39:17.680  4327  6770 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:39:17.690  8671  8710 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:39:17.690  8671  8710 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:39:17.690  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:39:17.690  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:39:17.690  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:39:17.690  8671  8710 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:39:17.690  8671  8710 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:39:17.700  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:39:17.700  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:39:17.700  3055  3733 D EnterpriseController: netId is 0
06-30 10:39:17.700  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10023
,06-30 10:39:21.310  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:22), CP = 242, LCD = 0
,06-30 10:39:23.930  3494  4276 E Watchdog: !@Sync 11 [06-30 10:39:23.935]
,06-30 10:39:28.850  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:31.360  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:22), CP = 241, LCD = 0
,06-30 10:39:39.430  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -8 -200 -8 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:39:39.450  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:39:39.460  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -7 -200 -7 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:39:39.460  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:39:41.400  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:22), CP = 241, LCD = 0
,06-30 10:39:43.130  3494  6920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:39:43.130  3494  6920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,06-30 10:39:43.130  3494  6920 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:39:43.130  3494  6920 D BatteryService: stay LED for fully charged
06-30 10:39:43.140  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:43.150  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:39:43.150  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:39:43.150  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:43.160  3494  3494 I MotionRecognitionService: Plugged
,06-30 10:39:43.160  3494  3494 E MotionRecognitionService: support TA ~,
,06-30 10:39:43.170  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792,
06-30 10:39:43.170  4676  4676 D CommonServiceConfiguration: getStringValueSetting
06-30 10:39:43.170  3494  3494 D MotionRecognitionService:  TA connected ,  33792
,06-30 10:39:43.170  3494  3494 I MotionRecognitionService: skip setTransmitPower. ,
06-30 10:39:43.170  3494  3494 D MotionRecognitionService:   cableConnection= 1,
06-30 10:39:43.170  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
,06-30 10:39:43.170  4676  4676 D BatteryMonitor: new battery level: 100,
06-30 10:39:43.170  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:39:43.180  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:43.180  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:48.860  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:51.470  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:24), CP = 241, LCD = 0
,06-30 10:39:53.930  3494  4276 E Watchdog: !@Sync 12 [06-30 10:39:53.942]
,06-30 10:39:55.490  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:39:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:40:01.540  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:24), CP = 241, LCD = 0
,06-30 10:40:07.970  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:40:08.860  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:11.590  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:24), CP = 240, LCD = 0
,06-30 10:40:13.180  3494  4369 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:21.640  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:24), CP = 240, LCD = 0
,06-30 10:40:23.940  3494  4276 E Watchdog: !@Sync 13 [06-30 10:40:23.949]
,06-30 10:40:28.870  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:31.680  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:26), CP = 240, LCD = 0
,06-30 10:40:32.550  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:40:32.580  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:40:32.580  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:40:32.600  6478  6478 I PedometerService: onStartCommand  true, true
,06-30 10:40:32.610  3055  3733 D EnterpriseController: netId is 0
06-30 10:40:32.610  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10010
,06-30 10:40:32.620  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:40:32.620  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 10:40:32.620  3494  4498 V AlarmManager:  remove PendingIntent] PendingIntent{b9539e1: PendingIntentRecord{654908a com.google.android.gms broadcastIntent}}
,06-30 10:40:32.660  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b326306 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{30cf72 8377:com.google.android.talk/u0a114}
,06-30 10:40:41.740  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:26), CP = 240, LCD = 0
,06-30 10:40:42.580  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:40:42.580  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:40:43.230  3494  5970 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:40:43.230  3494  5970 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:40:43.230  3494  5970 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:40:43.240  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:40:43.240  3494  5970 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
06-30 10:40:43.240  3494  5970 D BatteryService: stay LED for fully charged
06-30 10:40:43.240  3494  3494 I MotionRecognitionService: Plugged
06-30 10:40:43.240  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:40:43.240  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:40:43.240  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:40:43.240  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:40:43.240  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:40:43.240  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:40:43.240  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:40:43.250  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:40:43.250  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:40:43.250  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:43.270  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:40:43.280  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:40:43.280  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:40:43.280  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:48.870  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,06-30 10:40:51.790  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:26), CP = 240, LCD = 0
,06-30 10:40:53.950  3494  4276 E Watchdog: !@Sync 14 [06-30 10:40:53.955]
,06-30 10:40:55.590  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:40:55.670  4510  4564 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 76ms lastUpdatedAfter : 180381ms
,06-30 10:40:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:41:01.840  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:26), CP = 240, LCD = 0
,06-30 10:41:06.460  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -4 -200 -4 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:41:06.480  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:41:06.490  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -6 -200 -6 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:41:06.490  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:41:08.880  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:11.880  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:28), CP = 240, LCD = 0
,06-30 10:41:13.280  3494  3510 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:41:13.290  3494  3510 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:41:13.290  3494  3510 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:41:13.290  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:41:13.290  3494  3510 D BatteryService: stay LED for fully charged
06-30 10:41:13.290  3494  3494 I MotionRecognitionService: Plugged
06-30 10:41:13.290  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:41:13.290  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:41:13.290  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:41:13.290  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:41:13.290  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:41:13.290  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:41:13.290  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:41:13.300  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:41:13.300  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:13.310  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:41:13.320  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:41:13.330  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 10:41:13.330  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:13.330  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:41:21.940  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:28), CP = 240, LCD = 0
,06-30 10:41:23.950  3494  4276 E Watchdog: !@Sync 15 [06-30 10:41:23.962]
,06-30 10:41:28.880  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:32.000  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:28), CP = 240, LCD = 0
,06-30 10:41:42.060  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:28), CP = 239, LCD = 0
,06-30 10:41:43.340  3494  4424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:41:43.340  3494  4424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:41:43.340  3494  4424 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:41:43.340  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:41:43.340  3494  4424 D BatteryService: stay LED for fully charged
06-30 10:41:43.340  3494  3494 I MotionRecognitionService: Plugged
06-30 10:41:43.340  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:41:43.340  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:41:43.340  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:41:43.340  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:41:43.340  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:41:43.340  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:41:43.340  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:41:43.350  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:41:43.350  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:43.350  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:41:43.370  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:41:43.380  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:41:43.380  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:41:43.380  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:44.160  3110  3110 I bootchecker: bootchecker wake up!!
,06-30 10:41:48.880  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:52.100  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,06-30 10:41:53.960  3494  4276 E Watchdog: !@Sync 16 [06-30 10:41:53.970]
,06-30 10:41:55.760  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:42:02.140  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,06-30 10:42:08.890  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:12.210  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 240, LCD = 0
,06-30 10:42:13.200  4676  4757 I CellLocationSupport: onCellLocationChanged
,06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:42:13.210  3494  3510 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:42:13.230  3494  3988 I AppOps  : sendInfoToFLP, code=12 , uid=10010 , packageName=com.google.android.gms , type=noteOp
,06-30 10:42:13.380  3494  3971 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:42:13.380  3494  3971 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:42:13.380  3494  3971 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:42:13.380  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:42:13.380  3494  3971 D BatteryService: stay LED for fully charged
06-30 10:42:13.390  3494  3494 I MotionRecognitionService: Plugged
06-30 10:42:13.390  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:42:13.390  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:42:13.390  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:42:13.390  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:42:13.390  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:42:13.390  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:42:13.390  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:42:13.400  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:42:13.410  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:42:13.400  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:13.420  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:42:13.430  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:42:13.440  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:13.440  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:22.260  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 240, LCD = 0
,06-30 10:42:23.970  3494  4276 E Watchdog: !@Sync 17 [06-30 10:42:23.982]
,06-30 10:42:27.430  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -8 -200 -8 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:42:27.440  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:42:27.460  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -8 -200 -8 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
06-30 10:42:27.460  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:42:28.890  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:32.310  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,06-30 10:42:41.690  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:42:41.750  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a01a992 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e57919 4620:com.google.android.gms/u0a10}
,06-30 10:42:41.810  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:42:41.810  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:42:41.840  3494  5968 V AlarmManager:  remove PendingIntent] PendingIntent{f3d7db: PendingIntentRecord{86e59e3 com.vodafone.smhs startService}}
,06-30 10:42:41.860  3494  3971 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vodafone.vodafone360updates cmp = com.vodafone.lib.sec.receiver.ConnectivityReceiver newState = 1 callingPackage = 10071
,06-30 10:42:41.870  3494  3510 V AlarmManager:  remove PendingIntent] PendingIntent{1f9d278: PendingIntentRecord{6f0682f com.vodafone.vodafone360updates startService}}
,06-30 10:42:41.900  4620 10150 I EventLogService: Aggregate from 1467274361585 (log), 1467274361585 (data)
,06-30 10:42:42.080 10156 10156 E Zygote  : v2
06-30 10:42:42.080 10156 10156 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:42:42.080 10156 10156 I libpersona: KNOX_SDCARD not a persona
06-30 10:42:42.080  3494  3560 I ActivityManager: Start proc 10156:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,06-30 10:42:42.080 10156 10156 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
,06-30 10:42:42.080 10156 10156 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:42:42.080 10156 10156 E Zygote  : accessInfo : 0
,06-30 10:42:42.110 10156 10156 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:42:42.110 10156 10156 D ActivityThread: Added TimaKeyStore provider
,06-30 10:42:42.130  3494  4369 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{64f5d51 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bdf99b6 10156:com.samsung.android.sm/1000}
,06-30 10:42:42.140 10156 10156 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package com.samsung.android.sm
,06-30 10:42:42.140  3494  4424 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,06-30 10:42:42.140 10156 10156 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,06-30 10:42:42.150 10156 10156 D ResourcesManager: For user 0 new overlays fetched Null
,06-30 10:42:42.150 10156 10156 I InjectionManager: Inside getClassLibPath caller 
,06-30 10:42:42.170 10156 10156 D InjectionManager: InjectionManager
06-30 10:42:42.170 10156 10156 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm
,06-30 10:42:42.170 10156 10156 I InjectionManager: Constructor com.samsung.android.sm, Feature store :{}
06-30 10:42:42.170 10156 10156 I InjectionManager: featureStore :{}
,06-30 10:42:42.180  3494  3988 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7ce16b7 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bdf99b6 10156:com.samsung.android.sm/1000}
,06-30 10:42:42.190  3494  3988 I ActivityManager: Killing 8080:com.samsung.storyservice/5004 (adj 15): DHA:empty #31
,06-30 10:42:42.210  3494  4521 D ActivityManager: isAutoRunBlockedApp:: com.samsung.storyservice, Auto Run ON
,06-30 10:42:42.360  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,06-30 10:42:43.440  3494  5975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:48.900  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:52.400  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,06-30 10:42:53.980  3494  4276 E Watchdog: !@Sync 18 [06-30 10:42:53.990]
,06-30 10:42:55.890  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:42:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:43:02.440  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 238, LCD = 0
,06-30 10:43:07.970  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:43:08.900  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:12.480  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 238, LCD = 0
,06-30 10:43:13.490  3494  5975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:43:13.490  3494  5975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:43:13.490  3494  5975 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:43:13.490  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:43:13.500  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:43:13.500  3494  3494 I MotionRecognitionService: Plugged
06-30 10:43:13.500  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:43:13.500  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:43:13.500  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:43:13.500  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:43:13.500  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:43:13.500  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:43:13.500  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:43:13.500  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:43:13.510  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:43:13.510  3494  5975 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
06-30 10:43:13.510  3494  5975 D BatteryService: stay LED for fully charged
,06-30 10:43:13.530  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:43:13.540  4676  4676 D BatteryMonitor: new battery level: 100,
06-30 10:43:13.540  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:43:13.540  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:22.550  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), CP = 238, LCD = 0
,06-30 10:43:23.990  3494  4276 E Watchdog: !@Sync 19 [06-30 10:43:23.995]
,06-30 10:43:28.900  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:32.610  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), CP = 238, LCD = 0
,06-30 10:43:42.670  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), CP = 238, LCD = 0
,06-30 10:43:43.540  3494  4424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:43:43.540  3494  4424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:43:43.540  3494  4424 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
,06-30 10:43:43.550  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:43:43.550  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:43:43.550  3494  3494 I MotionRecognitionService: Plugged
06-30 10:43:43.560  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:43:43.550  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:43:43.550  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:43:43.550  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:43:43.550  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:43:43.550  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:43:43.550  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:43:43.550  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:43:43.560  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:43:43.560  3494  4424 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
06-30 10:43:43.560  3494  4424 D BatteryService: stay LED for fully charged
,06-30 10:43:43.580  4676  4676 D CommonServiceConfiguration: getStringValueSetting,
,06-30 10:43:43.590  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 10:43:43.590  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:43.590  4676  4676 D BatteryMonitor: new battery level: 100,
,06-30 10:43:48.900  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:51.160  3494  3931 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:43:51.160  3494  3931 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:43:51.170  3494  3930 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:43:52.740  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), CP = 238, LCD = 0
,06-30 10:43:53.990  3494  4276 E Watchdog: !@Sync 20 [06-30 10:43:54.003]
,06-30 10:43:56.010  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:43:56.100  4510  4564 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 65ms lastUpdatedAfter : 180427ms
,06-30 10:43:56.610  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:43:56.610  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:43:56.630  3494  3931 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:43:56.630  3494  3931 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10020, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10024, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10028, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10030, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10038, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10051, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLock,ed: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10060, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10062, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10066, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10071, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10088, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10096, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10103, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10107, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10144, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10148, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10157, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10158, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10169, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10183, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10187, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10191, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10197, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10198, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10210, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:43:58.270  3494  3554 D NetworkPolicy: isUidForegroundLocked: 10211, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:43:58.470  3494  3590 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,06-30 10:43:58.480  3494  3590 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 10:44:02.790  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), CP = 237, LCD = 0
,06-30 10:44:08.910  3494  5966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:44:12.850  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), CP = 237, LCD = 0
,06-30 10:44:13.590  3494  3510 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:13.600  3494  3510 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:44:13.600  3494  3510 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:44:13.600  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:44:13.600  3494  3494 I MotionRecognitionService: Plugged
06-30 10:44:13.600  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:44:13.600  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:44:13.600  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:44:13.600  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:44:13.600  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:44:13.600  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:44:13.600  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:44:13.610  3494  3510 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
06-30 10:44:13.610  3494  3510 D BatteryService: stay LED for fully charged
,06-30 10:44:13.610  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:44:13.610  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:13.620  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:44:13.630  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:44:13.630  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:44:13.640  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:13.640  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:17.850  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:17.880  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:17.880  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:17.930  4327  6771 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:44:17.930  4327  6771 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:44:17.930  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:44:17.930  4327  6771 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:44:17.930  4327  6771 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:44:17.930  4327  6771 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:17.950  4327  6771 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:44:17.950  4327  6771 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:44:17.950  4327  6771 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:44:17.950  4327  6771 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:44:17.950  4327  6771 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:44:17.950  4327  6771 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:44:17.950  4327  6771 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:17.960  8671  8710 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:44:17.960  8671  8710 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:44:17.960  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:44:17.960  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:44:17.960  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:44:17.960  8671  8710 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:44:17.960  8671  8710 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:17.960  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:44:17.960  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:44:17.960  3055  3733 D EnterpriseController: netId is 0
06-30 10:44:17.960  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10023
,06-30 10:44:22.920  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), CP = 237, LCD = 0
,06-30 10:44:24.000  3494  4276 E Watchdog: !@Sync 21 [06-30 10:44:24.009]
,06-30 10:44:29.780  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:44:32.990  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), CP = 237, LCD = 0
,06-30 10:44:43.060  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), CP = 238, LCD = 0
,06-30 10:44:43.640  3494  4424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:44:43.640  3494  4424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:44:43.640  3494  4424 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:44:43.640  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:44:43.640  3494  4424 D BatteryService: stay LED for fully charged
06-30 10:44:43.650  3494  3494 I MotionRecognitionService: Plugged
06-30 10:44:43.650  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:44:43.650  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:44:43.650  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:44:43.650  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:44:43.650  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:44:43.650  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:44:43.650  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:44:43.660  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:44:43.660  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:44:43.660  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:43.680  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:44:43.690  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:44:43.690  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:43.690  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:53.120  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), CP = 237, LCD = 0
,06-30 10:44:54.010  3494  4276 E Watchdog: !@Sync 22 [06-30 10:44:54.016]
,06-30 10:44:56.200  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:45:03.180  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), CP = 237, LCD = 0
,06-30 10:45:13.260  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), CP = 237, LCD = 0
,06-30 10:45:13.690  3494  4531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:45:13.690  3494  4531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:45:13.700  3494  4531 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:45:13.700  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:45:13.700  3494  3494 I MotionRecognitionService: Plugged
06-30 10:45:13.700  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:45:13.700  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:45:13.700  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:45:13.700  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:45:13.700  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:45:13.700  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:45:13.700  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:45:13.710  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:45:13.710  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:13.710  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:45:13.720  3494  4531 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
06-30 10:45:13.720  3494  4531 D BatteryService: stay LED for fully charged
,06-30 10:45:13.730  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:45:13.740  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:45:13.740  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:13.740  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:23.320  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), CP = 237, LCD = 0
,06-30 10:45:24.010  3494  4276 E Watchdog: !@Sync 23 [06-30 10:45:24.023]
,06-30 10:45:33.390  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), CP = 237, LCD = 0
,06-30 10:45:43.460  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), CP = 237, LCD = 0
,06-30 10:45:43.740  3494  3510 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:44.730  4676  4757 I CellLocationSupport: onCellLocationChanged
,06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:45:44.740  3494  3988 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:45:44.750  3494  6920 I AppOps  : sendInfoToFLP, code=12 , uid=10010 , packageName=com.google.android.gms , type=noteOp
,06-30 10:45:53.520  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), CP = 238, LCD = 0
,06-30 10:45:54.020  3494  4276 E Watchdog: !@Sync 24 [06-30 10:45:54.027]
,06-30 10:45:56.330  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:45:58.310  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -4 -200 -4 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:45:58.330  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:45:58.340  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -7 -200 -7 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:45:58.340  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:46:03.580  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), CP = 237, LCD = 0
,06-30 10:46:07.970  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:46:13.640  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), CP = 237, LCD = 0
,06-30 10:46:13.790  3494  4531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:46:13.790  3494  4531 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:46:13.790  3494  4531 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:46:13.800  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:46:13.800  3494  3494 I MotionRecognitionService: Plugged
06-30 10:46:13.800  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:46:13.800  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:46:13.800  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:46:13.800  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:46:13.800  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:46:13.800  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:46:13.800  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:46:13.800  3494  4531 D BatteryService: stay LED for fully charged
,06-30 10:46:13.810  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:13.810  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:46:13.810  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:46:13.820  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:46:13.830  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:46:13.840  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:13.840  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:23.700  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), CP = 236, LCD = 0
,06-30 10:46:24.020  3494  4276 E Watchdog: !@Sync 25 [06-30 10:46:24.034]
,06-30 10:46:33.770  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), CP = 236, LCD = 0
,06-30 10:46:43.830  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), CP = 236, LCD = 0
,06-30 10:46:43.850  3494  3988 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:46:43.850  3494  3988 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:46:43.850  3494  3988 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:46:43.850  3494  3988 D BatteryService: stay LED for fully charged
06-30 10:46:43.850  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:46:43.850  3494  3494 I MotionRecognitionService: Plugged
06-30 10:46:43.850  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:46:43.850  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:46:43.850  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:46:43.850  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:46:43.850  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:46:43.850  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:46:43.850  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:46:43.860  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:46:43.860  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:43.870  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:46:43.870  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:43.870  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:46:43.880  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:46:43.890  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:53.890  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), CP = 236, LCD = 0
,06-30 10:46:54.040  3494  4276 E Watchdog: !@Sync 26 [06-30 10:46:54.047]
,06-30 10:46:56.440  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:46:56.520  4510  4564 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 69ms lastUpdatedAfter : 180420ms
,06-30 10:46:58.460  3494  5241 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
06-30 10:46:58.460  3494  5241 V MARsPolicyManager: updateSMDBValues
,06-30 10:46:58.460  3494  3587 E MARsDBManager: updateDBAll : begin --size 0
06-30 10:46:58.460  3494  3587 E MARsDBManager: updateDBAll : end
,06-30 10:47:03.940  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), CP = 237, LCD = 0
,06-30 10:47:04.010  3494  3505 I art     : Background sticky concurrent mark sweep GC freed 64645(8MB) AllocSpace objects, 371(7MB) LOS objects, 31% free, 34MB/50MB, paused 3.500ms total 109.382ms
,06-30 10:47:13.260  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:47:13.300  6478  6478 I PedometerService: onStartCommand  true, true
,06-30 10:47:13.310  6478  6478 I PedometerService: onStartCommand  true, true
,06-30 10:47:13.310  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:47:13.310  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:47:13.340  3494  3560 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,06-30 10:47:13.350  3055  3733 D EnterpriseController: netId is 0
06-30 10:47:13.350  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10010
,06-30 10:47:13.350  3494  4121 V AlarmManager:  remove PendingIntent] PendingIntent{9a4cb43: PendingIntentRecord{654908a com.google.android.gms broadcastIntent}}
,06-30 10:47:13.360  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:47:13.360  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:47:13.400  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9eb25c0 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{30cf72 8377:com.google.android.talk/u0a114}
,06-30 10:47:13.910  3494  4367 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:47:13.910  3494  4367 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:47:13.910  3494  4367 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:47:13.920  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:47:13.920  3494  4367 D BatteryService: stay LED for fully charged
,06-30 10:47:13.920  3494  3494 I MotionRecognitionService: Plugged
06-30 10:47:13.920  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:47:13.920  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:47:13.920  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:47:13.920  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:47:13.920  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:47:13.920  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:47:13.920  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:47:13.930  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:47:13.930  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:47:13.940  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:47:13.950  4676  4676 D CommonServiceConfiguration: getStringValueSetting,
,06-30 10:47:13.960  4676  4676 D BatteryMonitor: new battery level: 100,
,06-30 10:47:13.960  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:47:13.960  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:13.990  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), CP = 236, LCD = 0
,06-30 10:47:23.350  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:47:23.350  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,06-30 10:47:24.020  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), CP = 236, LCD = 0
,06-30 10:47:24.040  3494  4276 E Watchdog: !@Sync 27 [06-30 10:47:24.054]
,06-30 10:47:34.050  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), CP = 236, LCD = 0
,06-30 10:47:43.960  3494  3971 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:47:43.960  3494  3971 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:47:43.960  3494  3971 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:47:43.960  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:47:43.970  3494  3971 D BatteryService: stay LED for fully charged
,06-30 10:47:43.980  3494  3494 I MotionRecognitionService: Plugged
06-30 10:47:43.980  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:47:43.980  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:47:43.980  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:47:43.980  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:47:43.980  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:47:43.980  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:47:43.980  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:47:43.990  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:47:43.990  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:47:43.990  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:47:44.000  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:47:44.010  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:47:44.020  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:47:44.020  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:44.090  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), CP = 237, LCD = 0
,06-30 10:47:54.050  3494  4276 E Watchdog: !@Sync 28 [06-30 10:47:54.055]
,06-30 10:47:54.130  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 236, LCD = 0
,06-30 10:47:56.630  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:47:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:48:04.170  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 236, LCD = 0
,06-30 10:48:11.580  4676  4757 I CellLocationSupport: onCellLocationChanged
,06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:48:11.590  3494  4369 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:48:11.620  3494  3971 I AppOps  : sendInfoToFLP, code=12 , uid=10010 , packageName=com.google.android.gms , type=noteOp
,06-30 10:48:14.010  3494  3511 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:48:14.020  3494  3511 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:48:14.020  3494  3511 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:48:14.020  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:48:14.020  3494  3511 D BatteryService: stay LED for fully charged
06-30 10:48:14.020  3494  3494 I MotionRecognitionService: Plugged
06-30 10:48:14.020  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:48:14.020  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:48:14.020  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:48:14.020  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:48:14.020  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:48:14.020  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:48:14.020  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:48:14.030  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:48:14.030  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:48:14.030  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:14.040  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:14.040  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:48:14.050  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:48:14.060  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:14.200  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 238, LCD = 0
,06-30 10:48:23.270  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -8 -200 -8 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:48:23.280  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:48:23.300  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -8 -200 -8 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:48:23.300  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0,
,06-30 10:48:24.050  3494  4276 E Watchdog: !@Sync 29 [06-30 10:48:24.063]
,06-30 10:48:24.240  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 236, LCD = 0
,06-30 10:48:34.280  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 236, LCD = 0
,06-30 10:48:44.070  3494  3971 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:44.330  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:48:51.160  3494  3931 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:48:51.160  3494  3931 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:48:51.170  3494  3930 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:48:54.060  3494  4276 E Watchdog: !@Sync 30 [06-30 10:48:54.070]
,06-30 10:48:54.400  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:48:56.740  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:48:57.750  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:48:57.750  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:48:57.770  3494  3931 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:48:57.770  3494  3931 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:49:04.430  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:49:08.910  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:49:10.770  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:49:10.860  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:49:10.860  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:49:10.960  3494  4367 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{93cddec u0 com.sec.spp.push.ACTION_CONNECTION_STATE_CHECK qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45a51c 7242:com.sec.spp.push/u0a33}
,06-30 10:49:10.960  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:49:10.960  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 10:49:11.000  3494  6920 V AlarmManager:  remove PendingIntent] PendingIntent{2ab144a: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.030  3494  4369 V AlarmManager:  remove PendingIntent] PendingIntent{e425fbb: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.050  3494  3988 V AlarmManager:  remove PendingIntent] PendingIntent{10fecd8: PendingIntentRecord{938195 com.sec.spp.push broadcastIntent}}
,06-30 10:49:11.060  3494  3510 V AlarmManager:  remove PendingIntent] PendingIntent{501d831: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.100  7242  7242 E SPPClientService: [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,06-30 10:49:11.110  3494  5975 V AlarmManager:  remove PendingIntent] PendingIntent{88e2b16: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.140  3494  4498 V AlarmManager:  remove PendingIntent] PendingIntent{ead3c97: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.160  3494  3971 V AlarmManager:  remove PendingIntent] PendingIntent{c02fe84: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.180  3494  5975 V AlarmManager:  remove PendingIntent] PendingIntent{4eac66d: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.200  3494  3510 V AlarmManager:  remove PendingIntent] PendingIntent{5b9e2a2: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.200  3494  4531 V AlarmManager:  remove PendingIntent] PendingIntent{e7f0b33: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.200  3494  4521 V AlarmManager:  remove PendingIntent] PendingIntent{df37ef0: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.210  3494  3971 V AlarmManager:  remove PendingIntent] PendingIntent{efa5c69: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.210  3494  5975 V AlarmManager:  remove PendingIntent] PendingIntent{af786ee: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.220  3494  5970 V AlarmManager:  remove PendingIntent] PendingIntent{95278f: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.220  3494  6920 V AlarmManager:  remove PendingIntent] PendingIntent{9299a1c: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.220  3494  4498 V AlarmManager:  remove PendingIntent] PendingIntent{1535625: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.230  3494  4369 V AlarmManager:  remove PendingIntent] PendingIntent{a5923fa: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.230  3494  3511 V AlarmManager:  remove PendingIntent] PendingIntent{e46adab: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.230  3494  4121 V AlarmManager:  remove PendingIntent] PendingIntent{a443c08: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.240  3494  3988 V AlarmManager:  remove PendingIntent] PendingIntent{f882fa1: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.240  3494  5968 V AlarmManager:  remove PendingIntent] PendingIntent{30585c6: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.250  3494  4424 V AlarmManager:  remove PendingIntent] PendingIntent{5407987: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.250  3494  4530 V AlarmManager:  remove PendingIntent] PendingIntent{6e510b4: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.260  3494  4367 V AlarmManager:  remove PendingIntent] PendingIntent{9d724dd: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.260  3494  3510 V AlarmManager:  remove PendingIntent] PendingIntent{dc43852: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.270  3494  4531 V AlarmManager:  remove PendingIntent] PendingIntent{7212723: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.280  3494  4521 V AlarmManager:  remove PendingIntent] PendingIntent{b1c8420: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.280  3494  3971 V AlarmManager:  remove PendingIntent] PendingIntent{c2631d9: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.290  3494  5975 V AlarmManager:  remove PendingIntent] PendingIntent{649879e: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.290  3494  5970 V AlarmManager:  remove PendingIntent] PendingIntent{6d5127f: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.300  3494  6920 V AlarmManager:  remove PendingIntent] PendingIntent{195c24c: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.310  3494  4498 V AlarmManager:  remove PendingIntent] PendingIntent{bf1295: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.310  3494  4369 V AlarmManager:  remove PendingIntent] PendingIntent{d427faa: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.320  3494  3511 V AlarmManager:  remove PendingIntent] PendingIntent{fb2579b: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.330  3494  4121 V AlarmManager:  remove PendingIntent] PendingIntent{282b738: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.330  3494  3988 V AlarmManager:  remove PendingIntent] PendingIntent{2cb4311: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.340  3494  5968 V AlarmManager:  remove PendingIntent] PendingIntent{f20ec76: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}},
,06-30 10:49:11.340  3494  4424 V AlarmManager:  remove PendingIntent] PendingIntent{254d277: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.350  3494  4530 V AlarmManager:  remove PendingIntent] PendingIntent{5480ee4: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.350  3494  4367 V AlarmManager:  remove PendingIntent] PendingIntent{c8fff4d: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.360  3494  3510 V AlarmManager:  remove PendingIntent] PendingIntent{ba75a02: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.370  3494  4531 V AlarmManager:  remove PendingIntent] PendingIntent{33a1f13: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.370  3494  4521 V AlarmManager:  remove PendingIntent] PendingIntent{e93550: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.380  3494  3971 V AlarmManager:  remove PendingIntent] PendingIntent{d6a4349: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.390  3494  5975 V AlarmManager:  remove PendingIntent] PendingIntent{a35144e: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.400  3494  5970 V AlarmManager:  remove PendingIntent] PendingIntent{71d996f: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:11.410  3494  6920 V AlarmManager:  remove PendingIntent] PendingIntent{734567c: PendingIntentRecord{b1095b5 com.android.bluetooth broadcastIntent}}
,06-30 10:49:14.120  3494  4498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:49:14.120  3494  4498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:49:14.120  3494  4498 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:49:14.120  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:14.130  3494  3494 I MotionRecognitionService: Plugged
06-30 10:49:14.130  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:49:14.130  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:49:14.130  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:49:14.130  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:49:14.130  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:49:14.130  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:49:14.130  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:49:14.130  3494  4498 D BatteryService: stay LED for fully charged
,06-30 10:49:14.140  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:49:14.140  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:14.150  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:49:14.160  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,06-30 10:49:14.160  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:49:14.170  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:49:14.170  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:14.470  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:49:18.110  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:18.140  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:18.140  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:18.180  4327  4343 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:49:18.180  4327  4343 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:49:18.180  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:49:18.180  4327  4343 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:18.180  4327  4343 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:18.180  4327  4343 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:18.210  4327  4343 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:49:18.210  4327  4343 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:49:18.210  4327  4343 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:49:18.210  4327  4343 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:49:18.210  4327  4343 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:18.210  4327  4343 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:18.210  4327  4343 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:18.210  8671  8710 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:49:18.210  8671  8710 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:49:18.210  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:49:18.210  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:49:18.210  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:49:18.210  8671  8710 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:49:18.210  8671  8710 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:18.210  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:49:18.210  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:18.210  3055  3733 D EnterpriseController: netId is 0
06-30 10:49:18.210  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10023
,06-30 10:49:20.920  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:49:20.920  3494  3991 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 10:49:24.070  3494  4276 E Watchdog: !@Sync 31 [06-30 10:49:24.077]
,06-30 10:49:24.540  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:49:28.840  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:49:28.940  8671  8671 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,06-30 10:49:28.960  6478  6478 I PedometerService: onStartCommand  true, true
,06-30 10:49:28.970  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:28.980  3494  3494 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
06-30 10:49:28.980  3494  3494 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
06-30 10:49:28.980  3494  3494 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 10:49:28.980  3494  3494 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
,06-30 10:49:29.010  4691 10382 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm64
,06-30 10:49:29.010  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.020  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.060  4327  4343 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:49:29.060  4327  4343 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:29.060  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:49:29.060  4327  4343 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:29.060  4327  4343 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:29.060  4327  4343 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:29.080  8443 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:49:29.080  8443 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:29.080  3055  3733 D EnterpriseController: netId is 0
06-30 10:49:29.080  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10028
,06-30 10:49:29.080  4691 10380 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-30 10:49:29.090  3494  6920 V AlarmManager:  remove PendingIntent] PendingIntent{6b77d6b: PendingIntentRecord{9a1da95 com.sec.android.app.shealth startService}}
,06-30 10:49:29.110  8671  8671 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 10:49:29.120  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.140  4327  6770 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:49:29.140  4327  6770 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:29.140  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:49:29.140  4327  6770 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:29.140  4327  6770 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:29.140  4327  6770 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:29.180  4691 10380 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
06-30 10:49:29.180  4691 10380 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-30 10:49:29.190  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.200  4691 10380 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
06-30 10:49:29.200  4691 10380 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-30 10:49:29.200  3494  3919 I Sensors : #>LightSensor r=0 g=0 b=0 c=0 atime=245 again=64 lux=0
06-30 10:49:29.200  3494  3919 E Sensors : RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1687.000000, REAL LUX : 0.000000 a_time = 245, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=1957120
06-30 10:49:29.200  3494  3603 D LightsService: [SvcLED]  onSensorChanged::light value = 0
06-30 10:49:29.200  3494  3603 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 10:49:29.210  3494  3603 D SensorManager: unregisterListener ::   
06-30 10:49:29.210  3494  3603 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,06-30 10:49:29.210  3494  3603 V AlarmManager:  remove PendingIntent] PendingIntent{f8b51e3: PendingIntentRecord{9d737e0 android broadcastIntent}}
,06-30 10:49:29.210  4327  6771 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:49:29.210  4327  6771 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:29.210  4327  6771 E Auth    : 	,at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:29.210  4327  6771 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:49:29.210  4327  6771 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:29.210  4327  6771 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:29.210  4327  6771 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:29.240  4691 10380 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
06-30 10:49:29.240  4691 10380 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-30 10:49:29.250  8671  8671 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 10:49:29.360  4620  8683 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,06-30 10:49:29.420  4620  8683 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,06-30 10:49:29.770  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:29.800  4327  6770 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:49:29.800  4327  6770 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:29.800  4327  6770 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:49:29.800  4327  6770 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:29.800  4327  6770 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:29.800  4327  6770 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:29.830  8671  8671 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 10:49:29.830  8671  8671 D Finsky  : [1] WearSupportService.startHygiene: disabled
,06-30 10:49:29.830  8671  8671 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,06-30 10:49:29.840  8671  8671 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,06-30 10:49:29.850  4327  4343 D DeviceConnectionService: client connected with version: 8296000
,06-30 10:49:30.000  4691 10380 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-30 10:49:30.050  4620  8690 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-30 10:49:30.070  4620  8690 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,06-30 10:49:30.100  4620  8691 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:30.110  4620  8691 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,06-30 10:49:30.130  4620  6712 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:30.150  4620  6712 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,06-30 10:49:30.170  4620  8690 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:30.190  4620  8690 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,06-30 10:49:30.200  4691 10380 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,06-30 10:49:30.840  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:49:30.840  3494  3560 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2df07be u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{34226cd 8671:com.android.vending/u0a23}
,06-30 10:49:30.870  8671 10404 D Finsky  : [805] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,06-30 10:49:30.880  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:30.900  4327  6767 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:49:30.900  4327  6767 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:49:30.900  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:49:30.900  4327  6767 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:30.900  4327  6767 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:30.900  4327  6767 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:30.920  4327  6767 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:49:30.920  4327  6767 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:49:30.920  4327  6767 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:49:30.920  4327  6767 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:49:30.920  4327  6767 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:30.920  4327  6767 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:30.920  4327  6767 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:30.920  8671  8710 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:49:30.920  8671  8710 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:49:30.920  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:49:30.920  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:49:30.920  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:49:30.920  8671  8710 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:49:30.920  8671  8710 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:30.920  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:49:30.920  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:30.930  3055  3733 D EnterpriseController: netId is 0
06-30 10:49:30.930  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10023
,06-30 10:49:34.580  3494  5957 D SSRM:n  : SIOP:: AP = 280, PST = 270 (W:28), CP = 235, LCD = 0
,06-30 10:49:44.180  3494  4369 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:49:44.180  3494  4369 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:49:44.180  3494  4369 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:49:44.180  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:49:44.180  3494  3494 I MotionRecognitionService: Plugged
06-30 10:49:44.180  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:49:44.180  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:49:44.180  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:49:44.180  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:49:44.180  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:49:44.180  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:49:44.180  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:49:44.190  3494  4369 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
06-30 10:49:44.190  3494  4369 D BatteryService: stay LED for fully charged
,06-30 10:49:44.200  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:44.200  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:44.200  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:49:44.210  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:49:44.220  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:49:44.220  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:44.220  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:44.250  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:49:44.600  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), CP = 235, LCD = 0
,06-30 10:49:44.780  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:44.810  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:44.810  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:44.860  4327  4339 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:49:44.860  4327  4339 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:49:44.860  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:49:44.860  4327  4339 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:44.860  4327  4339 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:44.860  4327  4339 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:44.920  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:49:44.920  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:49:44.920  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 10:49:54.070  3494  4276 E Watchdog: !@Sync 32 [06-30 10:49:54.084]
,06-30 10:49:54.650  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), CP = 235, LCD = 0
,06-30 10:49:56.870  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:49:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:50:04.690  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), CP = 235, LCD = 0
,06-30 10:50:04.930  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:50:04.980  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:50:04.980  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:50:05.630  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:05.640  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:05.650  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:05.680  4327  4822 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:50:05.680  4327  4822 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:50:05.680  4327  4822 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:50:05.680  4327  4822 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:50:05.680  4327  4822 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:50:05.680  4327  4822 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:50:05.740  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:50:05.740  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:50:05.740  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 10:50:14.220  3494  5975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:50:14.230  3494  5975 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:50:14.230  3494  5975 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:50:14.230  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:50:14.230  3494  5975 D BatteryService: stay LED for fully charged
06-30 10:50:14.240  3494  3494 I MotionRecognitionService: Plugged
06-30 10:50:14.240  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:50:14.240  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:50:14.240  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:50:14.240  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:50:14.240  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:50:14.240  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:50:14.240  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:50:14.250  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:50:14.250  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:50:14.250  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:14.270  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:50:14.280  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:50:14.280  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:50:14.280  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:14.730  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:50:24.080  3494  4276 E Watchdog: !@Sync 33 [06-30 10:50:24.092]
,06-30 10:50:24.800  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:50:25.750  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:50:26.350  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:26.380  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:26.390  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:26.440  4327  4821 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:50:26.440  4327  4821 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:50:26.440  4327  4821 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:50:26.440  4327  4821 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:50:26.440  4327  4821 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:50:26.440  4327  4821 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:50:26.500  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:50:26.500  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:50:26.500  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 10:50:26.920  3494  3505 I art     : Background partial concurrent mark sweep GC freed 49996(4MB) AllocSpace objects, 122(2MB) LOS objects, 31% free, 34MB/50MB, paused 5.099ms total 389.773ms
,06-30 10:50:34.830  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:50:38.950  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -4 -200 -4 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:50:38.970  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:50:38.970  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -6 -200 -6 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:50:38.980  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:50:44.280  3494  4531 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:44.870  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:50:46.500  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:50:47.230  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:47.250  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:47.250  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:50:47.290  4327  4339 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:50:47.290  4327  4339 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:50:47.290  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:50:47.290  4327  4339 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:50:47.290  4327  4339 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:50:47.290  4327  4339 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:50:47.310  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:50:47.320  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:50:47.320  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 10:50:54.090  3494  4276 E Watchdog: !@Sync 34 [06-30 10:50:54.099]
,06-30 10:50:54.940  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:50:56.940  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:50:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:51:04.970  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:51:07.320  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:51:07.370  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:51:07.370  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:51:07.910  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:51:07.930  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:51:07.930  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:51:07.970  4327  4339 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:51:07.970  4327  4339 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:51:07.970  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:51:07.970  4327  4339 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:51:07.970  4327  4339 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:51:07.970  4327  4339 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:51:08.000  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:51:08.000  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:51:08.010  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 10:51:14.330  3494  5968 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:15.040  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:51:24.100  3494  4276 E Watchdog: !@Sync 35 [06-30 10:51:24.106]
,06-30 10:51:25.110  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:51:28.010  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:51:28.560  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:51:28.590  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:51:28.590  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:51:28.630  4327  4339 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
06-30 10:51:28.630  4327  4339 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:51:28.630  4327  4339 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
06-30 10:51:28.630  4327  4339 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:51:28.630  4327  4339 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:51:28.630  4327  4339 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:51:28.680  8671  8671 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:51:28.680  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:51:28.680  8671  8671 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 10:51:35.150  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:51:35.280  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -8 -200 -8 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:51:35.300  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:51:35.300  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -8 -200 -8 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:51:35.310  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:51:44.380  3494  3988 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:51:44.380  3494  3988 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:51:44.380  3494  3988 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:51:44.380  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:44.390  3494  3494 I MotionRecognitionService: Plugged
06-30 10:51:44.390  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:51:44.390  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:51:44.390  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:51:44.390  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:51:44.390  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:51:44.390  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:51:44.390  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:51:44.400  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:51:44.400  3494  3988 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
06-30 10:51:44.400  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:51:44.400  3494  3988 D BatteryService: stay LED for fully charged
06-30 10:51:44.400  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:51:44.420  4676  4676 D CommonServiceConfiguration: getStringValueSetting,
,06-30 10:51:44.430  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 10:51:44.430  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:44.430  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:51:45.190  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:51:54.100  3494  4276 E Watchdog: !@Sync 36 [06-30 10:51:54.114]
,06-30 10:51:55.260  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:51:57.050  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:51:57.120  4510  4564 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 1Kb duration : 65ms lastUpdatedAfter : 147882ms
,06-30 10:51:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:52:05.300  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:52:14.430  3494  3971 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:15.370  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:52:24.110  3494  4276 E Watchdog: !@Sync 37 [06-30 10:52:24.121]
,06-30 10:52:25.440  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:52:35.480  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:52:44.480  3494  4369 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:45.540  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:52:54.120  3494  4276 E Watchdog: !@Sync 38 [06-30 10:52:54.128]
,06-30 10:52:55.620  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:52:57.210  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:53:04.850  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 8 99 -4 -200 -4 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2,
,06-30 10:53:04.870  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:53:04.870  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -5 -200 -5 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:53:04.870  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:53:05.660  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:53:14.530  3494  5968 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:53:14.530  3494  5968 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:53:14.530  3494  5968 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:53:14.540  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:53:14.550  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:53:14.540  3494  3494 I MotionRecognitionService: Plugged
06-30 10:53:14.550  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:53:14.540  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:53:14.540  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:53:14.540  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:53:14.540  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:53:14.540  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:53:14.540  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:53:14.540  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:53:14.550  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:53:14.550  3494  5968 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
06-30 10:53:14.550  3494  5968 D BatteryService: stay LED for fully charged
,06-30 10:53:14.570  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:53:14.580  4676  4676 D BatteryMonitor: new battery level: 100
06-30 10:53:14.580  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:53:14.580  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:15.700  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 236, LCD = 0
,06-30 10:53:24.130  3494  4276 E Watchdog: !@Sync 39 [06-30 10:53:24.135]
,06-30 10:53:25.770  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:53:35.820  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 235, LCD = 0
,06-30 10:53:44.580  3494  4521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:53:44.580  3494  4521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:53:44.580  3494  4521 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:53:44.580  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:53:44.580  3494  4521 D BatteryService: stay LED for fully charged
06-30 10:53:44.590  3494  3494 I MotionRecognitionService: Plugged
06-30 10:53:44.590  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:53:44.590  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:53:44.590  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:53:44.590  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:53:44.590  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:53:44.590  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:53:44.590  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:53:44.600  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:53:44.610  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:53:44.600  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:44.620  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:53:44.630  4676  4676 D BatteryMonitor: new battery level: 100,
,06-30 10:53:44.630  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 10:53:44.630  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:45.850  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:53:51.160  3494  3931 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:53:51.160  3494  3931 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:53:51.170  3494  3930 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:53:51.600  3494  3554 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:53:51.830  4676  4757 I CellLocationSupport: onCellLocationChanged
,06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:53:51.840  3494  4530 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:53:51.860  3494  3510 I AppOps  : sendInfoToFLP, code=12 , uid=10010 , packageName=com.google.android.gms , type=noteOp
,06-30 10:53:54.130  3494  4276 E Watchdog: !@Sync 40 [06-30 10:53:54.143]
,06-30 10:53:55.930  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:53:56.650  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:53:56.650  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:53:56.670  3494  3931 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:53:56.670  3494  3931 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:57.330  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:54:05.980  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 234, LCD = 0
,06-30 10:54:07.400  3074  3119 D Sensorhubs: readLargeContextData: 1, 1, 26, 4, 1, -42, -80, 24, 1, 1, 2, 18, 79, -91
06-30 10:54:07.410  3494  3952 D SensorHubManager: onGetSensorHubDataLocked: library(14) = 1, 1, 26, 4, 1, -42, -80, 24, 1, 1, 2, 18, 79, -91
,06-30 10:54:07.420  3494  3951 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 8, 54, 7,
06-30 10:54:07.420  3494  3951 D SensorHubManager: SendSensorHubData: send data = -63, 14, 8, 54, 7
,06-30 10:54:07.420  3074  3127 D Sensorhubs: sendContextData: -63, 14, 8, 54, 7
,06-30 10:54:07.430  3494  3951 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :14], AP_SLEEP
,06-30 10:54:07.430  3494  3951 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 14
,06-30 10:54:07.430  3494  3951 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 4, 1, -42, -80, 24, 1, 1, 2, 18, 79, -91,
,06-30 10:54:07.430  3494  3951 W CAE     : parse(ActivityTrackerBatchRunner.java:236) - parse start
,06-30 10:54:07.440  3494  3951 I CAE     : getMostActivity(ActivityTrackerBatchRunner.java:321) - size:1,
06-30 10:54:07.440  3494  3951 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER_BATCH =================
,06-30 10:54:07.440  3494  3951 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], Duration=[1200037], Count=[1], OperationMode=[2], ActivityType=[1], MostActivity=[1], TimeStamp=[1467275647000]
,06-30 10:54:07.440  3494  3954 D SContextService: updateSContext() : event = Activity Batch
,06-30 10:54:07.440  3494  3951 W CAE     : parse(ActivityTrackerBatchRunner.java:307) - parse end
,06-30 10:54:14.630  3494  5968 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 10:54:16.060  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:54:18.360  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:18.380  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:18.390  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:18.420  4327  6767 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:54:18.420  4327  6767 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:54:18.420  4327  6767 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:54:18.420  4327  6767 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:54:18.420  4327  6767 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:54:18.420  4327  6767 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:18.460  4327  6767 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:54:18.460  4327  6767 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:54:18.460  4327  6767 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:54:18.460  4327  6767 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:54:18.460  4327  6767 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:54:18.460  4327  6767 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:54:18.460  4327  6767 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:18.460  8671  8710 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:54:18.460  8671  8710 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:54:18.460  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:54:18.460  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:54:18.460  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:54:18.460  8671  8710 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:54:18.460  8671  8710 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:18.460  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:54:18.460  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:54:18.460  3055  3733 D EnterpriseController: netId is 0
06-30 10:54:18.460  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10023
,06-30 10:54:22.090  3494  3949 V AlarmManager: Expired Alarm result :4
,06-30 10:54:22.110  6478  6478 I PedometerService: onStartCommand  true, true
,06-30 10:54:22.130  3494  3494 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
06-30 10:54:22.130  3494  3494 V AlarmManagerEXT: <AppSync3 Whitelist>
06-30 10:54:22.130  3494  3494 V AlarmManagerEXT: (AppSync) ### 0 added ###
,06-30 10:54:22.130  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:54:22.130  4077  4077 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:54:22.190  3494  4531 V AlarmManager:  remove PendingIntent] PendingIntent{ed0accb: PendingIntentRecord{a71965a com.sec.android.app.shealth broadcastIntent}}
,06-30 10:54:24.140  3494  4276 E Watchdog: !@Sync 41 [06-30 10:54:24.152]
,06-30 10:54:26.130  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:54:36.180  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:54:44.680  3494  4424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:46.260  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:54:48.230  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -8 -200 -8 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:54:48.250  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:54:48.250  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -7 -200 -7 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x3 gsm|lte level=3
,06-30 10:54:48.260  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:54:54.150  3494  4276 E Watchdog: !@Sync 42 [06-30 10:54:54.159]
,06-30 10:54:56.330  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:54:57.430  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:54:57.510  4510  4564 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 67ms lastUpdatedAfter : 180387ms
,06-30 10:54:59.990  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:55:00.360  3074  3119 D Sensorhubs: readContextData: 1, 1, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 44, 1, 1, 4, 1, -41, 127, 89, 2, 0, 0, 0, 0, 0, 0, 0, 0, 4, -109, -89, 2, 0, 0, 0, 0, 0, 0, 0, 0, 3, -55, -44, 1, 0, 0, 0, 0, 0, 0, 0, 0, 5, 93, -20, 1, 0, 0, 0, 0, 0, 0, 0, 0, 4, -109, -32
,06-30 10:55:00.370  3494  3952 D SensorHubManager: onGetSensorHubDataLocked: library(76) = 1, 1, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 44, 1, 1, 4, 1, -41, 127, 89, 2, 0, 0, 0, 0, 0, 0, 0, 0, 4, -109, -89, 2, 0, 0, 0, 0, 0, 0, 0, 0, 3, -55, -44, 1, 0, 0, 0, 0, 0, 0, 0, 0, 5, 93, -20, 1, 0, 0, 0, 0, 0, 0, 0, 0, 4, -109, -32
06-30 10:55:00.370  3494  3951 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 8, 55, 0,
06-30 10:55:00.370  3494  3951 D SensorHubManager: SendSensorHubData: send data = -63, 14, 8, 55, 0
,06-30 10:55:00.380  3074  3074 D Sensorhubs: sendContextData: -63, 14, 8, 55, 0,
,06-30 10:55:00.390  3494  3951 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :76], AP_SLEEP,
,06-30 10:55:00.390  3494  3951 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 76,
,06-30 10:55:00.390  3494  3951 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 44, 1, 1, 4, 1, -41, 127, 89, 2, 0, 0, 0, 0, 0, 0, 0, 0, 4, -109, -89, 2, 0, 0, 0, 0, 0, 0, 0, 0, 3, -55, -44, 1, 0, 0, 0, 0, 0, 0, 0, 0, 5, 93, -20, 1, 0, 0, 0, 0, 0, 0, 0, 0, 4, -109, -32,,
06-30 10:55:00.400  3494  3951 I CAE     : parse(PedometerRunner.java:353) - parse start:3,
06-30 10:55:00.400  3494  3951 D CAE     : display(PedometerRunner.java:317) - ================= PEDOMETER =================
,06-30 10:55:00.400  3494  3951 I CAE     : display(PedometerRunner.java:339) - C=[0.0], WF=[0.0], WUSCD=[0], UDSCD=[0], RSCD=[0], RUSCD=[0], WSC=[0], RUSC=[0], DD=[0.0], WDSC=[0], RDSCD=[0], RDSC=[0], S=[0.0], WUSC=[0], D=[0.0], SS=[0], TSCD=[0], WDSCD=[0], RSC=[0], TSC=[0], UDSC=[0], CD=[0.0], WSCD=[0]
06-30 10:55:00.400  3494  3954 D SContext.CaeProvider.PedometerImpl: display() : mode = [normal],  tsc = [0], wsc = [0], rsc = [0]
06-30 10:55:00.400  3494  3954 D SContextService: updateSContext() : event = Pedometer
,06-30 10:55:00.400  3494  3951 I CAE     : parse(PedometerRunner.java:823) - parse end:18
06-30 10:55:00.410  3494  3951 I CAE     : parse(SLMonitorRunner.java:301) - parse:22
06-30 10:55:00.410  3494  3951 D CAE     : parse(SLMonitorRunner.java:323) - dataSize:4
06-30 10:55:00.410  3494  3951 D CAE     : display(SLMonitorRunner.java:604) - ================= STEP_LEVEL_MONITOR =================
,06-30 10:55:00.410  3494  3951 I CAE     : display(SLMonitorRunner.java:721) - DT=[1], DC=[4], TS=[1467275700057], ST=[SE,SE,ST,ST], SC=[0,0,0,0], DI=[0.0,0.0,0.0,0.0], CA=[0.0,0.0,0.0,0.0], DU=[299943,248276,351724,300000]
06-30 10:55:00.410  3494  3954 D SContextService: updateSContext() : event = Step Level Monitor
06-30 10:55:00.410  6478  6478 I Sensor[0x06]: [0x01] 2
06-30 10:55:00.420  6478  6478 I Sensor[0x06]: [0x01] 33
,06-30 10:55:00.420  6478  6478 I Sensor[0x04]: [0x01] 1467275700057[0x02] 0[0x03] 2[0x04] 299943
06-30 10:55:00.420  6478  6478 I Sensor[0x04]: [0x01] 1467276000000[0x02] 0[0x03] 2[0x04] 248276
06-30 10:55:00.420  6478  6478 I Sensor[0x04]: [0x01] 1467276248276[0x02] 0[0x03] 1[0x04] 351724
,06-30 10:55:00.420  6478  6478 I Sensor[0x04]: [0x01] 1467276600000[0x02] 0[0x03] 1[0x04] 300000
,06-30 10:55:06.360  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:55:07.970  3494  3949 V AlarmManager: Expired Alarm result :8
,06-30 10:55:14.730  3494  4521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:55:14.740  3494  4521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:55:14.740  3494  4521 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:55:14.740  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:55:14.740  3494  4521 D BatteryService: stay LED for fully charged
06-30 10:55:14.740  3494  3494 I MotionRecognitionService: Plugged
06-30 10:55:14.740  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:55:14.750  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:55:14.750  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:55:14.750  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:55:14.750  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:55:14.750  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:55:14.750  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:55:14.750  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:55:14.750  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:14.760  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:55:14.770  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:55:14.780  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:14.780  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:14.780  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:55:16.390  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:55:24.160  3494  4276 E Watchdog: !@Sync 43 [06-30 10:55:24.167]
,06-30 10:55:26.470  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:55:31.770  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 7 99 -4 -200 -4 -200 -1 0 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
06-30 10:55:31.770  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:55:31.770  4077  4272 D NetworkController.MobileSignalController(0/2147483643): onSignalStrengthsChanged signalStrength=SignalStrength: 6 99 -6 -200 -6 -200 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x2 gsm|lte level=2
,06-30 10:55:31.770  4077  4272 D NetworkController.MobileSignalController(0/2147483643): getMobileIconGroup(): 0
,06-30 10:55:36.510  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:55:44.790  3494  6920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:55:44.790  3494  6920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:55:44.790  3494  6920 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:55:44.790  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:55:44.800  3494  3494 I MotionRecognitionService: Plugged
06-30 10:55:44.800  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:55:44.800  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:55:44.800  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:55:44.800  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:55:44.800  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:55:44.800  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:55:44.800  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:55:44.810  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:55:44.810  3494  6920 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
06-30 10:55:44.810  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:55:44.810  3494  6920 D BatteryService: stay LED for fully charged
,06-30 10:55:44.810  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
,06-30 10:55:44.820  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:55:44.830  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:55:44.840  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:44.840  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:46.550  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:55:54.160  3494  4276 E Watchdog: !@Sync 44 [06-30 10:55:54.173]
,06-30 10:55:56.630  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 233, LCD = 0
,06-30 10:55:57.610  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:56:06.670  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:56:14.840  3494  5975 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:16.750  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:56:24.170  3494  4276 E Watchdog: !@Sync 45 [06-30 10:56:24.181]
,06-30 10:56:26.830  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:56:36.870  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:56:44.900  3494  6920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:46.950  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:56:54.180  3494  4276 E Watchdog: !@Sync 46 [06-30 10:56:54.188]
,06-30 10:56:57.030  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:56:57.720  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:57:07.070  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:57:14.950  3494  4530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:17.150  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:57:24.190  3494  4276 E Watchdog: !@Sync 47 [06-30 10:57:24.195]
,06-30 10:57:27.230  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:57:37.270  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:57:45.000  3494  4367 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:57:45.000  3494  4367 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:57:45.000  3494  4367 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
,06-30 10:57:45.010  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:57:45.020  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:57:45.010  3494  3494 I MotionRecognitionService: Plugged
06-30 10:57:45.020  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:57:45.010  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:57:45.010  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:57:45.010  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:57:45.010  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:57:45.010  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:57:45.010  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:57:45.010  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:57:45.020  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:57:45.020  3494  4367 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
06-30 10:57:45.020  3494  4367 D BatteryService: stay LED for fully charged
,06-30 10:57:45.040  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:57:45.050  4676  4676 D BatteryMonitor: new battery level: 100
06-30 10:57:45.050  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:45.050  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:47.300  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:57:54.190  3494  4276 E Watchdog: !@Sync 48 [06-30 10:57:54.202]
,06-30 10:57:57.390  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:57:57.820  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:57:57.910  4510  4564 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 75ms lastUpdatedAfter : 180400ms
,06-30 10:58:07.430  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 232, LCD = 0
,06-30 10:58:15.050  3494  4521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:58:15.050  3494  4521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:58:15.050  3494  4521 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:58:15.050  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:58:15.050  3494  4521 D BatteryService: stay LED for fully charged
06-30 10:58:15.060  3494  3494 I MotionRecognitionService: Plugged
06-30 10:58:15.060  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:58:15.060  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:58:15.060  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:58:15.060  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:58:15.060  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:58:15.060  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:58:15.060  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:58:15.070  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:58:15.070  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:58:15.070  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:58:15.090  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:58:15.100  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:58:15.100  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:15.100  4676  4676 D BatteryMonitor: new battery level: 100
,06-30 10:58:17.470  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 231, LCD = 0
,06-30 10:58:24.200  3494  4276 E Watchdog: !@Sync 49 [06-30 10:58:24.210]
,06-30 10:58:27.550  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 231, LCD = 0
,06-30 10:58:37.590  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 231, LCD = 0
,06-30 10:58:45.110  3494  6920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:47.670  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 231, LCD = 0
,06-30 10:58:51.160  3494  3931 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:58:51.160  3494  3931 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:58:51.170  3494  3930 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:58:54.210  3494  4276 E Watchdog: !@Sync 50 [06-30 10:58:54.218]
,06-30 10:58:57.750  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 231, LCD = 0
,06-30 10:58:57.800  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:58:57.800  3494  3931 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:58:57.820  3494  3931 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:58:57.820  3494  3931 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:58:58.000  4510  4564 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:58:58.470  3494  5241 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
06-30 10:58:58.470  3494  5241 V MARsPolicyManager: updateSMDBValues
,06-30 10:58:58.470  3494  3587 E MARsDBManager: updateDBAll : begin --size 0
06-30 10:58:58.470  3494  3587 E MARsDBManager: updateDBAll : end
,06-30 10:59:07.790  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 231, LCD = 0
,06-30 10:59:15.160  3494  4530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:59:15.160  3494  4530 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
06-30 10:59:15.160  3494  4530 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
06-30 10:59:15.160  3494  3494 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:59:15.160  3494  4530 D BatteryService: stay LED for fully charged
06-30 10:59:15.170  3494  3494 I MotionRecognitionService: Plugged
06-30 10:59:15.170  3494  3494 E MotionRecognitionService: support TA ~
06-30 10:59:15.170  3494  3494 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
06-30 10:59:15.170  3494  3494 D MotionRecognitionService:  TA connected ,  33792
06-30 10:59:15.170  3494  3494 I MotionRecognitionService: skip setTransmitPower. 
06-30 10:59:15.170  3494  3494 D MotionRecognitionService:   cableConnection= 1
06-30 10:59:15.170  3494  3494 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
06-30 10:59:15.170  3494  3494 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:59:15.180  4077  4077 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:59:15.180  4077  4077 D PowerUI : priorPlugType = 2 mPlugType =  2
06-30 10:59:15.180  4077  4077 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:59:15.200  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,06-30 10:59:15.210  4676  4676 D BatteryMonitor: new battery level: 100
06-30 10:59:15.210  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:59:15.210  4077  4077 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:59:17.840  3494  5957 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), CP = 231, LCD = 0
,06-30 10:59:18.600  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:59:18.620  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:59:18.630  4327  4327 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:59:18.670  4327  4343 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
06-30 10:59:18.670  4327  4343 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:59:18.670  4327  4343 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:59:18.670  4327  4343 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:59:18.670  4327  4343 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:59:18.670  4327  4343 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:59:18.690  4327  4343 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
06-30 10:59:18.690  4327  4343 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
06-30 10:59:18.690  4327  4343 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
06-30 10:59:18.690  4327  4343 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
06-30 10:59:18.690  4327  4343 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:59:18.690  4327  4343 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:59:18.690  4327  4343 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:59:18.700  8671  8710 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:59:18.700  8671  8710 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:59:18.700  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
06-30 10:59:18.700  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
06-30 10:59:18.700  8671  8710 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
06-30 10:59:18.700  8671  8710 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:59:18.700  8671  8710 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:59:18.700  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:59:18.700  8671  8710 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:59:18.700  3055  3733 D EnterpriseController: netId is 0
06-30 10:59:18.700  3055  3733 D Netd    : getNetworkForDns: using netid 0 for uid 10023
,TIME-OUT KILL (timeout was 1400000ms),06-30 10:59:22.670 10742 10742 I FIPS_bssl: FIPS approved mode (1) | 10742 | app_process
06-30 10:59:22.680 10742 10742 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:59:22.690 10742 10742 D AndroidRuntime: CheckJNI is OFF
06-30 10:59:22.690 10742 10742 D AndroidRuntime: readGMSProperty: start
06-30 10:59:22.690 10742 10742 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:59:22.690 10742 10742 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:59:22.690 10742 10742 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:59:22.690 10742 10742 D AndroidRuntime: readGMSProperty: end
06-30 10:59:22.690 10742 10742 D AndroidRuntime: addProductProperty: start
06-30 10:59:22.760 10742 10742 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:59:22.820 10742 10742 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:59:22.840 10742 10742 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:59:22.860 10742 10742 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 10:59:22.880  3494  3510 D PackageManager: START PACKAGE DELETE: observer{83457558}
06-30 10:59:22.880  3494  3510 D PackageManager: pkg{<packageName>}
06-30 10:59:22.880  3494  3510 D PackageManager: user{0}
06-30 10:59:22.880  3494  3510 D PackageManager: caller{2000}
06-30 10:59:22.880  3494  3510 D PackageManager: flags{2}
06-30 10:59:22.880  3494  3510 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 10:59:22.880  3494  3510 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 10:59:22.880  3494  3510 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 10:59:22.880  3494  3510 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:59:22.880  3494  3510 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 10:59:22.880  3494  3616 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 10:59:22.880  3494  3616 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 10:59:22.880  3494  3616 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 10:59:22.880  3494  3616 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 10:59:22.880  3494  3616 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 10:59:22.890  3494  3616 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 10:59:22.890  3494  3616 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 10:59:22.890  3494  3616 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
06-30 10:59:22.890  3494  3616 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 10:59:22.890  3494  3616 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 10:59:22.890  3494  3560 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
06-30 10:59:22.890  3494  3560 I ActivityManager: Killing 9657:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
06-30 10:59:22.890  3494  3560 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
06-30 10:59:22.910  3494  3616 D mjtest  : there is not file
06-30 10:59:23.020  3494  6920 I WindowState: WIN DEATH: Window{c32f3ac u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 10:59:23.020  3494  3510 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@b362b97)
06-30 10:59:23.020  3494  4005 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:59:23.020  3494  4005 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:59:23.020  3494  4005 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:59:23.020  3045  3156 I SurfaceFlinger: id=15 Removed NainActivit (4/10)
06-30 10:59:23.020  3494  4498 D GraphicsStats: Buffer count: 4
06-30 10:59:23.030  3045  4675 I SurfaceFlinger: id=15 Removed NainActivit (-2/10)
06-30 10:59:23.030  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fd18a7e88
06-30 10:59:23.200  3494  3505 I art     : Background sticky concurrent mark sweep GC freed 129041(9MB) AllocSpace objects, 322(6MB) LOS objects, 30% free, 34MB/50MB, paused 3.789ms total 102.534ms
06-30 10:59:23.230  3494  3616 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
06-30 10:59:23.270  3494  3616 W PackageSettings: Skipping PackageSetting{6d7e00e com.example.hello/10189} due to missing metadata
06-30 10:59:23.340  3494  3616 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
06-30 10:59:23.340  3494  3560 W PackageManager: Package com.test.thalitest is missing; assuming frozen
06-30 10:59:23.350  3494  3560 E ActivityManager: Failure starting process com.test.thalitest
06-30 10:59:23.350  3494  3560 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5270)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5187)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5026)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2636)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2338)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityStack.ensureActivitiesVisibleLocked(ActivityStack.java:2215)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.ensureActivitiesVisibleLocked(ActivityStackSupervisor.java:6654)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7385)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9140)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8763)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8918)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$900(ActivityManagerService.java:461)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2595)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:59:23.350  3494  3560 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
06-30 10:59:23.350  3072  3072 W keystore: ENTER clear_uid from uid 1000 for 10004
06-30 10:59:23.350  3494  3616 I art     : Starting a blocking GC Explicit
06-30 10:59:23.360  3494  3560 I ActivityManager:   Force finishing activity ActivityRecord{239ca87 u0 com.test.thalitest/.MainActivity t14}
06-30 10:59:23.370  3494  3560 I ActivityManager:   Force finishing activity ActivityRecord{2c426ae u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t14}
06-30 10:59:23.370  3494  3560 D InputDispatcher: Focused application set to: xxxx
06-30 10:59:23.380  3494  3560 I ActivityManager: Killing 8547:com.android.calendar/u0a148 (adj 15): DHA:empty #31
06-30 10:59:23.400  3494  3560 D ActivityManager: mDVFSHelper.acquire()
06-30 10:59:23.410  9728  9728 D ViewRootImpl: #3 mView = null
06-30 10:59:23.410  3045  4459 I SurfaceFlinger: id=16 Removed HrantPermis (6/9)
06-30 10:59:23.410  3045  3154 I SurfaceFlinger: id=16 Removed HrantPermis (-2/9)
06-30 10:59:23.410  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fd18a7e88
06-30 10:59:23.420  3494  4521 D InputDispatcher: Focus left window: 9728
06-30 10:59:23.430  3045  3045 I SurfaceFlinger: id=17 createSurf (1528x2445),1 flag=4, VSBConnecti
06-30 10:59:23.430  3494  4498 D InputDispatcher: Focus entered window: 5995
06-30 10:59:23.450  4412  4412 D Launcher: onRestart, Launcher: 92559298
06-30 10:59:23.520  3494  3616 I art     : Explicit concurrent mark sweep GC freed 18912(1456KB) AllocSpace objects, 4(80KB) LOS objects, 32% free, 33MB/49MB, paused 2.339ms total 174.315ms
06-30 10:59:23.550  3494  3616 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
06-30 10:59:23.550  3494  3616 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
06-30 10:59:23.550  3494  3616 D mjtest  : there is not file
06-30 10:59:23.550  3494  3616 D PackageManager: result of delete: 1{83457558}
06-30 10:59:23.560  3494  3616 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 10:59:23.560  3494  3616 D PackageManager: userId{-1}
06-30 10:59:23.560  3494  3616 D PackageManager: andCode{true}
06-30 10:59:23.560 10742 10742 I art     : System.exit called, status: 0
06-30 10:59:23.560 10742 10742 I AndroidRuntime: VM exiting with result code 0.

```
