#### Test 7578926851a8f91_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
06-30 12:52:05.490  3621  6674 D SSRM:n  : SIOP:: AP = 290, PST = 314 (W:12), CUR = 100, LCD = 0
,--------- beginning of main
06-30 12:52:06.445 10375 10375 I FIPS_bssl: FIPS approved mode (1) | 10375 | app_process
06-30 12:52:06.455 10375 10375 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 12:52:06.455 10375 10375 D AndroidRuntime: CheckJNI is OFF
06-30 12:52:06.455 10375 10375 D AndroidRuntime: readGMSProperty: start
06-30 12:52:06.455 10375 10375 D AndroidRuntime: readGMSProperty: already setted!!
06-30 12:52:06.455 10375 10375 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 12:52:06.455 10375 10375 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 12:52:06.455 10375 10375 D AndroidRuntime: readGMSProperty: end
06-30 12:52:06.455 10375 10375 D AndroidRuntime: addProductProperty: start
06-30 12:52:06.485 10375 10375 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 12:52:06.510 10375 10375 I Radio-JNI: register_android_hardware_Radio DONE
06-30 12:52:06.515 10375 10375 E AffinityControl: AffinityControl: registerfunction enter
06-30 12:52:06.530 10375 10375 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 12:52:06.575  3621  4439 D GameManagerService: identifyGamePackage. com.test.thalitest
06-30 12:52:06.575  3621  4439 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
06-30 12:52:06.585  3621  4439 D ActivityManager: mDVFSHelper.acquire()
06-30 12:52:06.590  3621  4439 V WindowManager: addAppToken: AppWindowToken{928474d token=Token{f7476e4 ActivityRecord{151da77 u0 com.test.thalitest/.MainActivity t69}}} to stack=1 task=69 at 0
06-30 12:52:06.615  3621  3845 D SecWifiDisplayUtil: Metadata value : none
06-30 12:52:06.615  3621  3845 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1e41305 V.E...... R.....ID 0,0-0,0}
06-30 12:52:06.615  3621  3845 D ISSUE_DEBUG: InputChannelName : 102e58b Starting com.test.thalitest
06-30 12:52:06.620  3621  4439 I ActivityManager: Start proc 10391:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
06-30 12:52:06.620 10391 10391 E Zygote  : v2
06-30 12:52:06.620 10391 10391 I libpersona: KNOX_SDCARD checking this for 10007
06-30 12:52:06.620 10391 10391 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:06.620  3621  4439 D InputDispatcher: Focused application set to: xxxx
06-30 12:52:06.620 10391 10391 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 12:52:06.620 10391 10391 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 12:52:06.620  3621  4439 D InputDispatcher: Focus left window: 6782
06-30 12:52:06.625 10391 10391 E Zygote  : accessInfo : 0
06-30 12:52:06.625 10391 10391 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 12:52:06.625  3621  3779 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{63b54e9 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-30 12:52:06.625 10375 10375 D AndroidRuntime: Shutting down VM
06-30 12:52:06.625  3621  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 12:52:06.625  4513  4513 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-30 12:52:06.635  2905  2905 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
06-30 12:52:06.650  3621  3845 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3621 uid:1000
06-30 12:52:06.650  3621  3845 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:52:06.650  3621  3845 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3621 uid:1000
06-30 12:52:06.650  3621  3845 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 12:52:06.650  3621  3845 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-30 12:52:06.655 10391 10391 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:06.655 10391 10391 D ActivityThread: Added TimaKeyStore provider
06-30 12:52:06.660  3621  5013 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 12:52:06.660  3621  5013 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 12:52:06.660  3621  3779 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{102e58b u0 d0 Starting com.test.thalitest}
06-30 12:52:06.660  4513  4513 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 12:52:06.675  3621  5013 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 12:52:06.690  3621  3621 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
06-30 12:52:06.690  3621  3775 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 12:52:06.700  2905  2987 D libEGL  : eglTerminate EGLDisplay = 0xb663f624
06-30 12:52:06.700  2905  2985 I SurfaceFlinger: id=11 Removed VSBConnecti (7/11)
06-30 12:52:06.700  2905  4788 I SurfaceFlinger: id=11 Removed VSBConnecti (-2/11)
06-30 12:52:06.705  2905  2985 D libEGL  : eglTerminate EGLDisplay = 0xb6881624
06-30 12:52:06.705  2905  2985 D libEGL  : eglTerminate EGLDisplay = 0xb6881624
06-30 12:52:06.705  3621  3845 V WindowStateAnimator: Finishing drawing window Window{102e58b u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 12:52:06.705  2905  2985 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
06-30 12:52:06.705  2905  2987 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
06-30 12:52:06.705  6782  6782 V ActivityThread: updateVisibility : ActivityRecord{b74521d token=android.os.BinderProxy@e679b56 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 12:52:06.710  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbec7c474
06-30 12:52:06.710  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbec7c474
06-30 12:52:06.710  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbec7c40c
06-30 12:52:06.715  5100  5100 V ActivityThread: updateVisibility : ActivityRecord{ffafe96 token=android.os.BinderProxy@583bddc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 12:52:06.715  5100  5100 D Launcher: onTrimMemory. Level: 20
06-30 12:52:06.730  2905  4788 I SurfaceFlinger: id=12 Removed VSBConnecti (4/9)
06-30 12:52:06.730  2905  2985 I SurfaceFlinger: id=12 Removed VSBConnecti (-2/9)
06-30 12:52:06.740  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbec7c474
,06-30 12:52:07.000  3621  5013 I WindowManager: Screenshot max retries 4 of Token{f7476e4 ActivityRecord{151da77 u0 com.test.thalitest/.MainActivity t69}} appWin=Window{102e58b u0 d0 Starting com.test.thalitest} drawState=4
06-30 12:52:07.005  3621  3775 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
06-30 12:52:07.025  3621  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
06-30 12:52:07.040  3621  6674 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 12:52:07.050  3621  6674 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 12:52:07.095 10391 10391 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
06-30 12:52:07.130 10391 10391 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 12:52:07.140 10391 10391 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 1979-1982)
06-30 12:52:07.140 10391 10391 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 12:52:07.155 10391 10405 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
06-30 12:52:07.160 10391 10391 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {57027e5}
06-30 12:52:07.160 10391 10391 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 12:52:07.160 10391 10391 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 12:52:07.170 10391 10391 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-30 12:52:07.185 10391 10406 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
06-30 12:52:07.190  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
06-30 12:52:07.205 10391 10391 D libEGL  : eglInitialize EGLDisplay = 0xbebe8e7c
06-30 12:52:07.235  3621  5652 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
06-30 12:52:07.235  3621  5652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
06-30 12:52:07.275 10391 10391 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
06-30 12:52:07.285 10391 10391 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:52:07.285 10391 10391 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
06-30 12:52:07.285 10391 10391 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
06-30 12:52:07.285 10391 10391 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
06-30 12:52:07.300 10391 10391 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
06-30 12:52:07.305 10391 10391 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-30 12:52:07.385 10391 10391 D SecWifiDisplayUtil: Metadata value : none
06-30 12:52:07.390 10391 10391 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b0e561a I.E...... R.....ID 0,0-0,0}
06-30 12:52:07.400 10391 10442 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 12:52:07.410  3621  4439 D ISSUE_DEBUG: InputChannelName : 5ba2adc com.test.thalitest/com.test.thalitest.MainActivity
06-30 12:52:07.420  3621  5632 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 12:52:07.420  3621  5632 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 12:52:07.420  3621  3621 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 12:52:07.425  3621  3621 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 12:52:07.465 10391 10391 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 10391
06-30 12:52:07.470  3621  5117 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/10391 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 12:52:07.480 10391 10405 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
06-30 12:52:07.495 10391 10391 D SecWifiDisplayUtil: Metadata value : none
06-30 12:52:07.505  2905  2905 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
06-30 12:52:07.515  3621  5112 D InputDispatcher: Focus entered window: 10391
06-30 12:52:07.520  3621  3845 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3621 uid:1000
06-30 12:52:07.520  3621  3845 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:52:07.520  3621  3845 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3621 uid:1000
06-30 12:52:07.520  3621  3845 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 12:52:07.520 10391 10442 D libEGL  : eglInitialize EGLDisplay = 0x9ceff7c4
06-30 12:52:07.520 10391 10442 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:52:07.525 10391 10442 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
06-30 12:52:07.530 10391 10391 V ActivityThread: updateVisibility : ActivityRecord{ca66b27 token=android.os.BinderProxy@6f37cc5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 12:52:07.530 10391 10391 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-30 12:52:07.550 10391 10391 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 12:52:07.550  3621  4550 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 12:52:07.565 10391 10391 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
06-30 12:52:07.600 10391 10448 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:52:07.600 10391 10448 D libEGL  : eglInitialize EGLDisplay = 0x9b1ff3ec
06-30 12:52:07.630  3621  5653 V WindowStateAnimator: Finishing drawing window Window{5ba2adc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
06-30 12:52:07.630  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbec7c40c
06-30 12:52:07.630 10391 10391 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 12:52:07.635 10391 10391 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6f37cc5 time:132477
06-30 12:52:07.645  3621  3845 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 12:52:07.645  3621  3621 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 12:52:07.645  3621  3621 I KnoxTimeoutHandler: SD activityfalse
06-30 12:52:07.650  3621  3845 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +649ms (total +1s59ms)
06-30 12:52:07.655  3621  3845 D ActivityManager: mDVFSHelper.release()
06-30 12:52:07.655  3621  3845 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{151da77 u0 com.test.thalitest/.MainActivity t69} time:132495
06-30 12:52:07.655  3621  3845 D ViewRootImpl: #3 mView = null
06-30 12:52:07.660  2905  4788 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
06-30 12:52:07.660  2905  2987 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
06-30 12:52:07.665  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbec7c474
06-30 12:52:07.665 10391 10391 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10391
06-30 12:52:07.830 10391 10391 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:52:07.960 10391 10455 D jxcore_app_log: JniHelper::setJavaVM(0xb4874000), pthread_self() = -1716782800
06-30 12:52:07.965 10391 10455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:52:07.965 10391 10455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:52:07.965 10391 10455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:52:07.965 10391 10455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:52:07.965 10391 10455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:52:07.965 10391 10455 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2862135 added. We now have 1 listener(s)
06-30 12:52:07.965 10391 10455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
06-30 12:52:07.965 10391 10455 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
06-30 12:52:07.965 10391 10455 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:52:07.965 10391 10455 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:52:07.970 10391 10455 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71d8e58 added. We now have 1 listener(s)
06-30 12:52:07.970 10391 10455 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:52:07.970 10391 10455 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:07.970 10391 10455 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 12:52:07.970 10391 10455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 12:52:07.970 10391 10455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 12:52:07.970 10391 10455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:52:07.970 10391 10455 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 12:52:07.975 10391 10455 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 12:52:07.975 10391 10455 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
06-30 12:52:07.975 10391 10455 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:07.975 10391 10455 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:52:07.975 10391 10455 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:52:07.975 10391 10455 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:52:07.975 10391 10455 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 12:52:08.005 10391 10391 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:52:08.355 10391 10456 W jxcore-log: Initializing JXcore engine
,06-30 12:52:08.355 10391 10456 W jxcore-log: JXcore engine is ready
,06-30 12:52:08.380  5630  5630 E audit   : type=1400 msg=audit(1467283928.380:260): avc:  denied  { ioctl } for  pid=10456 comm="Thread-1019" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3241 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
,06-30 12:52:08.380  5630  5630 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 12:52:08.380  5630  5630 E audit   : type=1300 msg=audit(1467283928.380:260): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=2 a3=9999a3c8 items=0 ppid=2963 ppcomm=main pid=10456 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1019" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 12:52:08.380  5630  5630 E audit   : type=1327 msg=audit(1467283928.380:260): proctitle="com.test.thalitest"
06-30 12:52:08.380  5630  5630 E audit   : type=1320 msg=audit(1467283928.380:260): 
06-30 12:52:08.380  5630  5630 E audit   : type=1400 msg=audit(1467283928.380:261): avc:  denied  { ioctl } for  pid=10456 comm="Thread-1019" path="socket:[36431]" dev="sockfs" ino=36431 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
06-30 12:52:08.380  5630  5630 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 12:52:08.380  5630  5630 E audit   : type=1300 msg=audit(1467283928.380:261): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=2 a3=9999a3c8 items=0 ppid=2963 ppcomm=main pid=10456 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1019" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 12:52:08.380  5630  5630 E audit   : type=1327 msg=audit(1467283928.380:261): proctitle="com.test.thalitest"
,06-30 12:52:08.380  5630  5630 E audit   : type=1320 msg=audit(1467283928.380:261): 
,06-30 12:52:08.385 10391 10456 W jxcore-log: Starting JXcore engine
,06-30 12:52:08.435  4695  4695 D Recents : onTaskStackChanged
,06-30 12:52:08.435 10391 10456 W jxcore-log: Platform android,
06-30 12:52:08.435 10391 10456 W jxcore-log: 
06-30 12:52:08.435 10391 10456 W jxcore-log: Process ARCH arm
06-30 12:52:08.435 10391 10456 W jxcore-log: 
,06-30 12:52:08.525 10391 10456 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:52:08.525 10391 10456 I jxcore-log: 
06-30 12:52:08.525 10391 10456 W jxcore-log: JXcore engine is started
,06-30 12:52:08.530 10391 10455 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 12:52:08.535  3621  4904 D GameManagerService: identifyGamePackage. com.android.packageinstaller
,06-30 12:52:08.535  3621  4904 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.android.packageinstaller)
,06-30 12:52:08.535  3621  4904 D ActivityManager: mDVFSHelper.acquire()
,06-30 12:52:08.540  3621  4904 V WindowManager: addAppToken: AppWindowToken{2cc030c token=Token{96cde3f ActivityRecord{1f62a5e u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}}} to stack=1 task=69 at 1
,06-30 12:52:08.545 10457 10457 E Zygote  : v2
06-30 12:52:08.545 10457 10457 I libpersona: KNOX_SDCARD checking this for 10141
06-30 12:52:08.545 10457 10457 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:08.545 10457 10457 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 12:52:08.545 10457 10457 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 12:52:08.545 10457 10457 E Zygote  : accessInfo : 0
,06-30 12:52:08.545 10457 10457 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
06-30 12:52:08.550  3621  4904 I ActivityManager: Start proc 10457:com.android.packageinstaller/u0a141 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 12:52:08.550  3621  4904 D InputDispatcher: Focused application set to: xxxx
06-30 12:52:08.550  3621  4904 D InputDispatcher: Focus left window: 10391
06-30 12:52:08.550 10391 10455 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 12:52:08.550  3621  3845 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3621 uid:1000
06-30 12:52:08.550  3621  3845 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:52:08.550  3621  3845 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3621 uid:1000
06-30 12:52:08.550  3621  3845 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 12:52:08.560 10457 10457 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:08.560 10457 10457 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:08.560  3621  5014 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 12:52:08.565  3621  3621 D GameManagerService: NotifyRunnable. pkg: com.android.packageinstaller, type: 4, isMinimized: false, isTunableApp: false
06-30 12:52:08.565  3621  3775 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 12:52:08.870  3621  5014 I WindowManager: Screenshot max retries 4 of Token{96cde3f ActivityRecord{1f62a5e u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}} appWin=Window{5ba2adc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 12:52:08.875  3621  3775 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 12:52:08.895  3621  6674 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 12:52:08.915 10457 10457 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 12:52:09.080 10457 10457 D SecWifiDisplayUtil: Metadata value : none
,06-30 12:52:09.085 10457 10457 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5a6f8ef I.E...... R.....I. 0,0-0,0}
,06-30 12:52:09.090 10457 10469 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 12:52:09.090  3621  4439 D ISSUE_DEBUG: InputChannelName : 7aeb0d1 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-30 12:52:09.095  3621  5653 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 12:52:09.095  3621  5653 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 12:52:09.095  3621  3621 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 12:52:09.095  3621  3621 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 12:52:09.095  3621  3621 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 12:52:09.120  2905  2905 I SurfaceFlinger: id=15 createSurf (193x193),1 flag=4, HrantPermis
,06-30 12:52:09.120  3621  3779 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7aeb0d1 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-30 12:52:09.120  4513  4513 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 12:52:09.140  3621  4904 D InputDispatcher: Focus entered window: 10457
,06-30 12:52:09.145  3621  3845 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3621 uid:1000
06-30 12:52:09.145  3621  3845 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:52:09.145  3621  3845 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3621 uid:1000
06-30 12:52:09.145  3621  3845 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 12:52:09.150 10457 10469 D libEGL  : eglInitialize EGLDisplay = 0xae9eb7c4
06-30 12:52:09.150 10457 10469 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:52:09.165 10457 10469 D mali_winsys: new_window_surface returns 0x3000,  [1528x2656]-format:1
,06-30 12:52:09.170 10457 10457 V ActivityThread: updateVisibility : ActivityRecord{1c1713d token=android.os.BinderProxy@49241ce {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 12:52:09.170 10457 10457 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
06-30 12:52:09.175  3621  3645 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 12:52:09.180  5555  5555 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 12:52:09.200 10457 10457 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 12:52:09.290  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbec7c40c
,06-30 12:52:09.295  3621  5116 V WindowStateAnimator: Finishing drawing window Window{7aeb0d1 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
,06-30 12:52:09.300 10457 10457 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@49241ce time:134143
,06-30 12:52:09.305  3621  3845 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 12:52:09.305  3621  3621 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 12:52:09.310  3621  3621 I KnoxTimeoutHandler: SD activityfalse
,06-30 12:52:09.315  3621  3845 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +444ms (total +777ms)
,06-30 12:52:09.315  3621  3845 D ActivityManager: mDVFSHelper.release()
06-30 12:52:09.315  3621  3845 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f62a5e u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69} time:134158
,06-30 12:52:09.530  3621  5653 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:09.530  3621  5653 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:52:09.530  3621  5653 D BatteryService: online:4, current avg:109, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:178
06-30 12:52:09.530  3621  5653 D BatteryService: stay LED for fully charged
06-30 12:52:09.530  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:09.530  3621  3621 I MotionRecognitionService: Plugged
06-30 12:52:09.530  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:52:09.530  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:52:09.530  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:09.535  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:09.535  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:09.535  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:09.540  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:09.560  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:09.560  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:09.605  3621  4494 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/69_task.xml.bak
,06-30 12:52:10.105  4695  4695 D Recents : onTaskStackChanged,
,06-30 12:52:10.750  3621  4965 E Watchdog: !@Sync 4 [06-30 12:52:10.750]
,06-30 12:52:11.305  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:52:11.305  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:52:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:52:14.930  3621  6674 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 12:52:15.520  3621  6674 D SSRM:n  : SIOP:: AP = 290, PST = 308 (W:12), CUR = 109, LCD = 0
,06-30 12:52:16.635  3621  3908 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 12:52:16.675  3621  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 12:52:19.665  3621  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:52:19.665  3621  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:52:19.665  3621  3644 D BatteryService: online:4, current avg:141, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:151
06-30 12:52:19.665  3621  3644 D BatteryService: stay LED for fully charged
,06-30 12:52:19.665  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:52:19.670  3621  3621 I MotionRecognitionService: Plugged
06-30 12:52:19.670  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:52:19.670  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:52:19.670  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:19.685  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:19.685  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:19.685  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:19.705  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:19.705  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:19.710  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:19.845 10099 10246 V xAnalytics: xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,06-30 12:52:25.555  3621  6674 D SSRM:n  : SIOP:: AP = 280, PST = 302 (W:12), CUR = 141, LCD = 0
,06-30 12:52:27.190  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:29.805  3621  5013 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:52:29.805  3621  5013 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:52:29.805  3621  5013 D BatteryService: online:4, current avg:150, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:152
06-30 12:52:29.805  3621  5013 D BatteryService: stay LED for fully charged
,06-30 12:52:29.805  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:29.815  3621  3621 I MotionRecognitionService: Plugged
06-30 12:52:29.815  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:52:29.815  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:52:29.815  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:29.820  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:52:29.820  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:29.825  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:29.830  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,06-30 12:52:29.845  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:29.845  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:34.125  5614  6553 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:52:35.580  3621  6674 D SSRM:n  : SIOP:: AP = 280, PST = 297 (W:12), CUR = 150, LCD = 0
,06-30 12:52:39.950  3621  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:52:39.950  3621  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:52:39.950  3621  3644 D BatteryService: online:4, current avg:149, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:146
06-30 12:52:39.950  3621  3644 D BatteryService: stay LED for fully charged
,06-30 12:52:39.950  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:52:39.955  3621  3621 I MotionRecognitionService: Plugged
06-30 12:52:39.955  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:52:39.955  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:52:39.955  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:39.960  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:39.960  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:39.965  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:39.990  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:39.990  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:39.990  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:40.755  3621  4965 E Watchdog: !@Sync 5 [06-30 12:52:40.759]
,06-30 12:52:45.615  3621  6674 D SSRM:n  : SIOP:: AP = 280, PST = 292 (W:14), CUR = 149, LCD = 0
,06-30 12:52:47.195  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:50.085  3621  3645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:52:50.085  3621  3645 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:52:50.085  3621  3645 D BatteryService: online:4, current avg:145, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:145
06-30 12:52:50.085  3621  3645 D BatteryService: stay LED for fully charged
,06-30 12:52:50.090  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:52:50.090  3621  3621 I MotionRecognitionService: Plugged
06-30 12:52:50.090  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:52:50.095  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:52:50.095  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:52:50.100  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:50.100  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:50.100  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:50.125  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:50.125  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:50.125  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:55.645  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 287 (W:14), CUR = 145, LCD = 0
,06-30 12:52:56.270  3621  6675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,06-30 12:52:56.285  3621  3775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a15a909 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e090b0 9835:com.samsung.android.sm.provider/1000}
,06-30 12:52:56.385  3621  6675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,06-30 12:52:56.395  3621  3775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{81fd52f u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7e090b0 9835:com.samsung.android.sm.provider/1000}
,06-30 12:52:59.995  3621  4401 V AlarmManager: Expired Alarm result :8
,06-30 12:53:00.225  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:53:00.225  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:53:00.225  3621  5014 D BatteryService: online:4, current avg:140, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:145
06-30 12:53:00.225  3621  5014 D BatteryService: stay LED for fully charged
,06-30 12:53:00.230  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:53:00.230  3621  3621 I MotionRecognitionService: Plugged
06-30 12:53:00.230  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:53:00.230  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:53:00.230  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:00.240  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:00.240  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:53:00.240  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:00.265  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:00.270  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:00.270  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:05.680  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 285 (W:14), CUR = 140, LCD = 0
,06-30 12:53:05.695  3621  4401 V AlarmManager: Expired Alarm result :4
,06-30 12:53:05.730  3621  4401 I ActivityManager: Start proc 10562:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-30 12:53:05.735  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:53:05.740  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 12:53:05.740  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:53:05.755  3621  5028 D NtpTrustedTime: forceRefresh: no connectivity
06-30 12:53:05.755  3621  5028 V AlarmManager:  remove PendingIntent] PendingIntent{c3cb60c: PendingIntentRecord{e995b55 android broadcastIntent}}
,06-30 12:53:05.760 10562 10562 E Zygote  : v2
,06-30 12:53:05.760 10562 10562 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:53:05.760 10562 10562 I libpersona: KNOX_SDCARD not a persona
,06-30 12:53:05.765 10562 10562 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,06-30 12:53:05.770  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:53:05.780  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:53:05.785 10562 10562 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 12:53:05.785  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:05.785  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:05.790 10562 10562 E Zygote  : accessInfo : 0
06-30 12:53:05.790  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:05.790  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:05.795  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:05.795  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 12:53:05.795  3621  3621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{125c9e6 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8652b5b 5614:com.google.android.gms.persistent/u0a14}
06-30 12:53:05.795  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:05.815  3621  4896 V AlarmManager:  remove PendingIntent] PendingIntent{e7f3b27: PendingIntentRecord{afd4869 com.google.android.gms broadcastIntent}}
,06-30 12:53:05.820 10562 10562 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:53:05.820 10562 10562 D ActivityThread: Added TimaKeyStore provider
,06-30 12:53:05.825  8679  8679 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
06-30 12:53:05.825  8679  8679 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 12:53:05.825  8679  8679 V GCMBaseIntentService: Acquiring wakelock
,06-30 12:53:05.850  8679  8679 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-8
,06-30 12:53:05.855  8679 10578 V GCMRegistrar: Unregistering app flipboard.app
,06-30 12:53:05.860 10562 10562 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,06-30 12:53:05.880  8679 10578 V GCMBaseIntentService: Releasing wakelock
,06-30 12:53:06.010  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:53:06.100  5614  6214 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,06-30 12:53:06.130  5614  6214 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:53:06.150  5614  6214 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:53:06.185  2916  4371 D EnterpriseController: netId is 0
06-30 12:53:06.185  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10014
,06-30 12:53:06.250  3621  3775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{66a7896 u0 com.google.android.c2dm.intent.REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{366b4d5 8679:flipboard.app/u0a119}
,06-30 12:53:06.250  8679  8679 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
06-30 12:53:06.250  8679  8679 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 12:53:06.250  8679  8679 V GCMBaseIntentService: Acquiring wakelock
,06-30 12:53:06.265  8679  8679 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-9
,06-30 12:53:06.265  8679 10598 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
06-30 12:53:06.265  8679 10598 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
06-30 12:53:06.265  8679 10598 D GCMBaseIntentService: Scheduling registration retry, backoff = 76102 (96000)
,06-30 12:53:06.275  8679 10598 V GCMBaseIntentService: Releasing wakelock
,06-30 12:53:06.535  5614  5614 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=119e3c98-fa88-436e-915b-87fc258e1297
,06-30 12:53:06.540  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:53:06.540  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:53:06.675  3621  3633 I art     : Background partial concurrent mark sweep GC freed 51207(3MB) AllocSpace objects, 47(940KB) LOS objects, 33% free, 30MB/45MB, paused 2.040ms total 164.176ms
06-30 12:53:06.675  5614  5859 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 12:53:06.675  5883 10587 D UdcContextInitService: registered all accounts: true
,06-30 12:53:06.695  5614  5968 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 12:53:06.765  3621  4550 I ActivityManager: Killing 9534:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 15): DHA:empty #31
,06-30 12:53:06.780  3621  5654 V AlarmManager:  remove PendingIntent] PendingIntent{e95b52a: PendingIntentRecord{afd4869 com.google.android.gms broadcastIntent}}
,06-30 12:53:06.800  5614  5968 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10014, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 12:53:06.815  3621  4904 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,06-30 12:53:06.875  5614  5614 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 12:53:06.875  5614 10607 I VacuumService: Vacuum at: now=1467283986881 tag=VacuumService
,06-30 12:53:07.010  3621  5013 V AlarmManager:  remove PendingIntent] PendingIntent{6d2a8b8: PendingIntentRecord{afd4869 com.google.android.gms broadcastIntent}}
,06-30 12:53:07.200  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:10.360  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:53:10.360  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:53:10.365  3621  5014 D BatteryService: online:4, current avg:137, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:132
06-30 12:53:10.365  3621  5014 D BatteryService: stay LED for fully charged
,06-30 12:53:10.365  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:53:10.370  3621  3621 I MotionRecognitionService: Plugged
06-30 12:53:10.370  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:53:10.370  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:53:10.370  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:10.375  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:10.375  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:10.375  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:10.390  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:10.390  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:10.390  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:10.765  3621  4965 E Watchdog: !@Sync 6 [06-30 12:53:10.767]
,06-30 12:53:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:53:11.410  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:53:11.410  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:53:15.715  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 284 (W:14), CUR = 137, LCD = 0
,06-30 12:53:20.495  3621  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:53:20.495  3621  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
,06-30 12:53:20.500  3621  3644 D BatteryService: online:4, current avg:133, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:129
06-30 12:53:20.500  3621  3644 D BatteryService: stay LED for fully charged
06-30 12:53:20.500  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:20.505  3621  3621 I MotionRecognitionService: Plugged
06-30 12:53:20.505  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:53:20.505  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:53:20.505  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:20.515  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:20.515  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:53:20.515  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:20.540  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:20.540  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:20.540  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:25.750  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:16), CUR = 133, LCD = 0
,06-30 12:53:27.200  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:30.635  3621  4904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:30.640  3621  4904 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:53:30.640  3621  4904 D BatteryService: online:4, current avg:130, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:142
06-30 12:53:30.640  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:53:30.640  3621  4904 D BatteryService: stay LED for fully charged
,06-30 12:53:30.645  3621  3621 I MotionRecognitionService: Plugged
06-30 12:53:30.645  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:53:30.645  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:53:30.645  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:30.655  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:30.655  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:30.655  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:30.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:30.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:30.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:35.780  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 281 (W:16), CUR = 130, LCD = 0
,06-30 12:53:40.775  3621  4965 E Watchdog: !@Sync 7 [06-30 12:53:40.777]
,06-30 12:53:40.780  3621  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:53:40.780  3621  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:53:40.780  3621  3644 D BatteryService: online:4, current avg:128, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:132
06-30 12:53:40.780  3621  3644 D BatteryService: stay LED for fully charged
06-30 12:53:40.780  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:40.785  3621  3621 I MotionRecognitionService: Plugged
06-30 12:53:40.785  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:53:40.785  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:53:40.785  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:40.795  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:40.795  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:53:40.795  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:40.820  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:40.820  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:40.820  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:45.825  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:16), CUR = 128, LCD = 0
,06-30 12:53:47.205  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:50.920  3621  4904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:53:50.925  3621  4904 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:53:50.925  3621  4904 D BatteryService: online:4, current avg:126, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:122
,06-30 12:53:50.930  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:50.935  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:50.935  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:53:50.935  3621  3621 I MotionRecognitionService: Plugged
06-30 12:53:50.935  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:53:50.935  3621  3621 D MotionRecognitionService:   cableConnection= 1,
06-30 12:53:50.935  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:53:50.935  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:53:50.945  3621  4904 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms,
06-30 12:53:50.945  3621  4904 D BatteryService: stay LED for fully charged
,06-30 12:53:50.970  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:50.970  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:50.970  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:55.860  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:16), CUR = 126, LCD = 0
,06-30 12:53:59.995  3621  4401 V AlarmManager: Expired Alarm result :8
,06-30 12:54:01.070  3621  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:54:01.070  3621  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:54:01.070  3621  3644 D BatteryService: online:4, current avg:125, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:122
06-30 12:54:01.070  3621  3644 D BatteryService: stay LED for fully charged
,06-30 12:54:01.070  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:54:01.075  3621  3621 I MotionRecognitionService: Plugged
06-30 12:54:01.075  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:54:01.075  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:54:01.075  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:54:01.085  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:54:01.085  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:54:01.085  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:01.110  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:54:01.110  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:54:01.110  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:05.890  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:18), CUR = 125, LCD = 0
,06-30 12:54:06.990  5614  5968 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:54:06.990  5614  5968 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 12:54:06.990  5614  5968 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 12:54:06.990  5614  5968 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 12:54:06.990  5614  5968 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 12:54:07.015  5614  5968 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 12:54:07.210  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,06-30 12:54:10.775  3621  4965 E Watchdog: !@Sync 8 [06-30 12:54:10.779]
,06-30 12:54:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:54:11.525  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:54:11.525  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:54:11.635  5015  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 7 size : 1Kb duration : 104ms lastUpdatedAfter : 149073ms
,06-30 12:54:15.930  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:18), CUR = 125, LCD = 0
,06-30 12:54:22.375  3621  4401 V AlarmManager: Expired Alarm result :8
,06-30 12:54:25.955  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:18), CUR = 125, LCD = 0
,06-30 12:54:27.215  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:31.170  3621  4550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:54:31.170  3621  4550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4379, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
,06-30 12:54:31.175  3621  4550 D BatteryService: online:4, current avg:8, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:54:31.175  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:54:31.180  3621  3621 I MotionRecognitionService: Plugged
06-30 12:54:31.180  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:54:31.180  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:54:31.180  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
06-30 12:54:31.180  3621  4550 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
06-30 12:54:31.180  3621  4550 D BatteryService: stay LED for fully charged
,06-30 12:54:31.185  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:31.185  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:54:31.185  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:31.215  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:54:31.215  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:54:31.215  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:35.985  3621  6674 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:18), CUR = 8, LCD = 0
,06-30 12:54:40.780  3621  4965 E Watchdog: !@Sync 9 [06-30 12:54:40.781]
,06-30 12:54:46.020  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 270 (W:20), CUR = 8, LCD = 0
,06-30 12:54:47.215  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:56.055  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:20), CUR = 8, LCD = 0
,06-30 12:55:01.255  3621  4550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:55:01.255  3621  4550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:55:01.255  3621  4550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:55:01.255  3621  4550 D BatteryService: stay LED for fully charged
,06-30 12:55:01.260  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:55:01.265  3621  3621 I MotionRecognitionService: Plugged
06-30 12:55:01.265  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:55:01.265  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:55:01.265  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:55:01.270  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:01.270  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:01.270  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:01.295  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:01.295  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:01.295  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:06.085  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:20), LCD = 0
,06-30 12:55:07.220  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:07.415  3621  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:55:07.420  3621  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:55:07.435  3621  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 12:55:07.445  3621  4391 I TLC_TIMA_PKM_initialize: initializing...
,06-30 12:55:07.445  3621  4391 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
06-30 12:55:07.445  3621  4391 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
,06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: root = 0, root_len = 1
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: device_id = 0x0
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: tlc_open() was called
06-30 12:55:07.445  3621  4391 I TZ: mc_tlc_communication: Opening MobiCore device
,06-30 12:55:07.455  3621  4391 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,06-30 12:55:07.460  3621  4391 I TZ: mc_tlc_communication: Opening the session
,06-30 12:55:07.485  3621  4391 I TZ: mc_tlc_communication: tlc_open() succeeded
,06-30 12:55:07.495  3621  4391 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 12:55:10.785  3621  4965 E Watchdog: !@Sync 10 [06-30 12:55:10.788]
,06-30 12:55:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:55:11.760  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:55:11.760  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:55:14.480  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 12:55:14.480  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 12:55:14.495  3621  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 12:55:14.500  3621  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:55:16.115  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:20), LCD = 0
,06-30 12:55:26.145  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:22), LCD = 0
,06-30 12:55:27.220  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:31.355  3621  4550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:31.355  3621  4550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:55:31.355  3621  4550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:55:31.355  3621  4550 D BatteryService: stay LED for fully charged
06-30 12:55:31.360  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:31.365  3621  3621 I MotionRecognitionService: Plugged
06-30 12:55:31.365  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:55:31.365  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:55:31.365  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:55:31.375  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:31.375  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:31.375  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:31.395  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:31.395  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:31.395  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:36.170  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:22), LCD = 0
,06-30 12:55:38.650  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:38.670  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:38.670  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:38.715  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:55:38.715  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:55:38.715  2916  4371 D EnterpriseController: netId is 0
06-30 12:55:38.715  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 12:55:40.790  3621  4965 E Watchdog: !@Sync 11 [06-30 12:55:40.794]
,06-30 12:55:44.320  3621  4401 V AlarmManager: Expired Alarm result :4
,06-30 12:55:44.345  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 12:55:44.345  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 12:55:44.345  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:55:44.365  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:55:44.370  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:55:44.380  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:44.380  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:44.390  3621  5028 D NtpTrustedTime: forceRefresh: no connectivity
06-30 12:55:44.390  3621  5028 V AlarmManager:  remove PendingIntent] PendingIntent{c3cb60c: PendingIntentRecord{e995b55 android broadcastIntent}}
,06-30 12:55:44.400  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:44.400  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:44.410  3621  5028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 12:55:44.425  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:44.425  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:44.435  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:44.440  8679  8679 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
06-30 12:55:44.440  8679  8679 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 12:55:44.440  8679  8679 V GCMBaseIntentService: Acquiring wakelock
,06-30 12:55:44.455  8679  8679 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-10
,06-30 12:55:44.460  8679 10739 V GCMRegistrar: Unregistering app flipboard.app
,06-30 12:55:44.480  8679 10739 V GCMBaseIntentService: Releasing wakelock
,06-30 12:55:44.510  5614  7050 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,06-30 12:55:44.540  5614  7050 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:55:44.540  5614  7050 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:55:44.540  2916  4371 D EnterpriseController: netId is 0
06-30 12:55:44.540  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10014
,06-30 12:55:44.555  3621  3775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{69ec13d u0 com.google.android.c2dm.intent.REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{366b4d5 8679:flipboard.app/u0a119}
,06-30 12:55:44.555  8679  8679 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
06-30 12:55:44.555  8679  8679 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 12:55:44.555  8679  8679 V GCMBaseIntentService: Acquiring wakelock
,06-30 12:55:44.575  8679  8679 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-11
,06-30 12:55:44.575  8679 10747 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
06-30 12:55:44.575  8679 10747 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
06-30 12:55:44.575  8679 10747 D GCMBaseIntentService: Scheduling registration retry, backoff = 235815 (192000)
,06-30 12:55:44.590  8679 10747 V GCMBaseIntentService: Releasing wakelock
,06-30 12:55:44.615  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 12:55:46.200  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:22), LCD = 0
,06-30 12:55:47.225  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:56.230  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:22), LCD = 0
,06-30 12:55:59.995  3621  4401 V AlarmManager: Expired Alarm result :8
,06-30 12:56:01.450  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:56:01.450  3621  5117 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:56:01.450  3621  5117 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:56:01.450  3621  5117 D BatteryService: stay LED for fully charged
,06-30 12:56:01.450  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:56:01.455  3621  3621 I MotionRecognitionService: Plugged
06-30 12:56:01.455  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:56:01.455  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:56:01.455  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:56:01.465  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:56:01.465  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:56:01.465  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:01.490  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:01.490  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:01.490  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:06.260  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:24), LCD = 0
,06-30 12:56:07.225  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:10.795  3621  4965 E Watchdog: !@Sync 12 [06-30 12:56:10.797]
,06-30 12:56:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:56:11.875  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:56:11.875  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:56:16.285  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:24), LCD = 0
,06-30 12:56:26.325  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:24), LCD = 0
,06-30 12:56:27.230  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:31.545  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:56:31.545  3621  5117 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:56:31.545  3621  5117 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:56:31.545  3621  5117 D BatteryService: stay LED for fully charged
,06-30 12:56:31.550  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:56:31.555  3621  3621 I MotionRecognitionService: Plugged
06-30 12:56:31.555  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:56:31.555  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:56:31.555  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:56:31.560  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:56:31.560  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:56:31.560  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:31.585  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:31.585  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:31.585  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:36.365  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:24), LCD = 0
,06-30 12:56:40.800  3621  4965 E Watchdog: !@Sync 13 [06-30 12:56:40.804]
,06-30 12:56:46.395  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:26), LCD = 0
,06-30 12:56:47.235  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:56.430  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:26), LCD = 0
,06-30 12:57:01.650  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:01.650  3621  5117 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:57:01.650  3621  5117 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:57:01.650  3621  5117 D BatteryService: stay LED for fully charged
06-30 12:57:01.650  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:01.650  3621  3621 I MotionRecognitionService: Plugged
06-30 12:57:01.650  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:57:01.655  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:57:01.655  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:57:01.655  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:01.655  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:57:01.655  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:01.660  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:01.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:01.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:06.465  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:26), LCD = 0
,06-30 12:57:07.240  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:10.805  3621  4965 E Watchdog: !@Sync 14 [06-30 12:57:10.810]
,06-30 12:57:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:57:11.980  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:57:11.980  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:57:12.085  5015  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 94ms lastUpdatedAfter : 180449ms
,06-30 12:57:16.495  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:26), LCD = 0
,06-30 12:57:26.530  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), LCD = 0
,06-30 12:57:27.240  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:31.735  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:57:31.735  3621  5117 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:57:31.735  3621  5117 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
,06-30 12:57:31.735  3621  5117 D BatteryService: stay LED for fully charged
06-30 12:57:31.740  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:57:31.745  3621  3621 I MotionRecognitionService: Plugged
06-30 12:57:31.745  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:57:31.745  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:57:31.745  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:57:31.755  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:57:31.755  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:57:31.755  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:31.760  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:31.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:31.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:36.560  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), LCD = 0
,06-30 12:57:40.815  3621  4965 E Watchdog: !@Sync 15 [06-30 12:57:40.817]
,06-30 12:57:46.585  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), LCD = 0
,06-30 12:57:47.245  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:56.625  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), LCD = 0
,06-30 12:57:59.720  2976  2976 I bootchecker: bootchecker wake up!!
,06-30 12:58:01.835  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:06.650  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:58:07.250  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:10.825  3621  4965 E Watchdog: !@Sync 16 [06-30 12:58:10.827]
,06-30 12:58:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:58:12.190  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:58:12.190  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:58:16.680  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:58:26.715  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:58:27.250  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:31.925  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:58:31.925  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:58:31.925  3621  5014 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:58:31.925  3621  5014 D BatteryService: stay LED for fully charged
,06-30 12:58:31.925  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:31.930  3621  3621 I MotionRecognitionService: Plugged
06-30 12:58:31.930  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:58:31.930  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:58:31.930  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:58:31.940  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:58:31.940  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:58:31.940  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:58:31.970  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:58:31.970  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:58:31.970  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:36.745  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:58:40.830  3621  4965 E Watchdog: !@Sync 17 [06-30 12:58:40.833]
,06-30 12:58:46.770  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:58:47.255  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:56.795  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:59:02.020  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:02.025  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:59:02.025  3621  5014 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:59:02.025  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:59:02.030  3621  5014 D BatteryService: stay LED for fully charged
,06-30 12:59:02.035  3621  3621 I MotionRecognitionService: Plugged
06-30 12:59:02.035  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:59:02.035  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:59:02.035  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:59:02.040  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:59:02.040  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:59:02.040  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:02.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:02.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:02.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:06.830  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:59:07.260  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:10.835  3621  4965 E Watchdog: !@Sync 18 [06-30 12:59:10.840]
,06-30 12:59:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 12:59:12.320  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 12:59:12.320  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 12:59:16.875  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:59:26.920  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:59:27.265  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:32.110  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:59:32.110  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 12:59:32.110  3621  5014 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 12:59:32.110  3621  5014 D BatteryService: stay LED for fully charged
,06-30 12:59:32.115  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:59:32.120  3621  3621 I MotionRecognitionService: Plugged
06-30 12:59:32.120  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 12:59:32.120  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 12:59:32.120  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 12:59:32.125  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:59:32.125  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:59:32.125  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:32.150  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:32.155  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:32.155  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:36.950  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:59:40.395  3621  4401 V AlarmManager: Expired Alarm result :8
,06-30 12:59:40.840  3621  4965 E Watchdog: !@Sync 19 [06-30 12:59:40.845]
,06-30 12:59:46.975  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 12:59:47.265  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:57.010  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:00:02.210  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:00:02.210  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:00:02.210  3621  5014 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:00:02.210  3621  5014 D BatteryService: stay LED for fully charged
06-30 13:00:02.215  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:00:02.215  3621  3621 I MotionRecognitionService: Plugged
06-30 13:00:02.215  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:00:02.215  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:00:02.215  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:00:02.225  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:00:02.225  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:00:02.225  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:00:02.250  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:00:02.250  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:00:02.250  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:07.035  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:00:07.275  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:07.415  3621  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 13:00:07.415  3621  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:00:07.420  3621  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:00:10.850  3621  4965 E Watchdog: !@Sync 20 [06-30 13:00:10.851]
,06-30 13:00:11.210  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 13:00:11.210  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:00:11.225  3621  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 13:00:11.225  3621  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:00:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:00:12.440  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:00:12.440  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:00:12.555  5015  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 95ms lastUpdatedAfter : 180469ms
,06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLock,ed: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.490  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.495  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.495  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:13.495  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.495  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.495  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.495  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 13:00:13.495  3621  3768 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 13:00:13.715  3621  3845 I ActivityManager: setMaxStartingBackgroundTimer onfinish
06-30 13:00:13.715  3621  3845 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 13:00:17.070  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:00:27.100  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:00:27.275  3621  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:32.300  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:37.135  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:00:38.865  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:38.890  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:38.890  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:38.930  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:00:38.930  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:00:38.930  2916  4371 D EnterpriseController: netId is 0
06-30 13:00:38.930  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 13:00:40.855  3621  4965 E Watchdog: !@Sync 21 [06-30 13:00:40.859]
,06-30 13:00:45.220  3621  4401 V AlarmManager: Expired Alarm result :8
,06-30 13:00:47.175  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:00:57.215  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:01:02.395  3621  3645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:01:02.395  3621  3645 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:01:02.395  3621  3645 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:01:02.395  3621  3645 D BatteryService: stay LED for fully charged
,06-30 13:01:02.395  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:01:02.400  3621  3621 I MotionRecognitionService: Plugged
06-30 13:01:02.400  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:01:02.400  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:01:02.400  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:01:02.410  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:01:02.410  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:01:02.410  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:02.435  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:02.435  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:02.435  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:07.255  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:01:10.860  3621  4965 E Watchdog: !@Sync 22 [06-30 13:01:10.863]
,06-30 13:01:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:01:12.655  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:01:12.655  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:01:17.295  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:01:27.335  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:01:32.495  3621  3645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:01:32.495  3621  3645 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:01:32.495  3621  3645 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:01:32.495  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:01:32.495  3621  3645 D BatteryService: stay LED for fully charged
,06-30 13:01:32.500  3621  3621 I MotionRecognitionService: Plugged
06-30 13:01:32.500  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:01:32.500  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:01:32.500  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:01:32.505  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:01:32.505  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:01:32.505  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate,
,06-30 13:01:32.520  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,06-30 13:01:32.535  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:32.535  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:37.370  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:01:40.865  3621  4965 E Watchdog: !@Sync 23 [06-30 13:01:40.869]
,06-30 13:01:47.400  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:01:57.435  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:02:02.585  3621  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:07.465  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:02:10.875  3621  4965 E Watchdog: !@Sync 24 [06-30 13:02:10.875]
,06-30 13:02:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:02:12.755  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:02:12.755  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:02:17.495  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:02:27.530  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:02:32.680  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:02:32.680  3621  5117 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:02:32.680  3621  5117 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:02:32.680  3621  5117 D BatteryService: stay LED for fully charged
,06-30 13:02:32.685  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:32.690  3621  3621 I MotionRecognitionService: Plugged
06-30 13:02:32.690  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:02:32.690  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:02:32.690  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:02:32.695  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:02:32.695  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:02:32.695  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:32.725  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:32.725  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:32.725  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:37.565  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:02:40.880  3621  4965 E Watchdog: !@Sync 25 [06-30 13:02:40.883]
,06-30 13:02:47.595  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:02:57.630  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:03:02.775  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:03:02.775  3621  5117 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:03:02.775  3621  5117 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:03:02.775  3621  5117 D BatteryService: stay LED for fully charged
,06-30 13:03:02.775  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:02.780  3621  3621 I MotionRecognitionService: Plugged
06-30 13:03:02.780  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:03:02.780  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:03:02.780  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:03:02.785  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:03:02.785  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:03:02.785  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:02.815  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:03:02.815  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:03:02.815  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:07.665  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:03:10.885  3621  4965 E Watchdog: !@Sync 26 [06-30 13:03:10.887]
,06-30 13:03:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:03:12.855  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:03:12.855  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:03:12.950  5015  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 83ms lastUpdatedAfter : 180394ms
,06-30 13:03:13.705  3621  5690 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 13:03:13.710  3621  5690 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 13:03:13.715  3621  5690 V MARsPolicyManager: updateSMDBValues
,06-30 13:03:13.715  3621  3843 E MARsDBManager: updateDBAll : begin --size 1
,06-30 13:03:13.750  3621  3843 E MARsDBManager: updateDBAll : end
06-30 13:03:13.750  3621  3843 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 13:03:17.695  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:03:27.730  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:03:32.870  3621  5117 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:37.765  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:03:40.890  3621  4965 E Watchdog: !@Sync 27 [06-30 13:03:40.893]
,06-30 13:03:47.795  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:03:57.835  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:04:02.965  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:04:02.965  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:04:02.965  3621  5014 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:04:02.965  3621  5014 D BatteryService: stay LED for fully charged
,06-30 13:04:02.965  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:04:02.970  3621  3621 I MotionRecognitionService: Plugged
06-30 13:04:02.970  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:04:02.970  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:04:02.970  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:04:02.980  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:04:02.980  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:04:02.980  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:04:03.005  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:03.005  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:03.005  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:07.865  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:04:10.895  3621  4965 E Watchdog: !@Sync 28 [06-30 13:04:10.897]
,06-30 13:04:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:04:13.060  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:04:13.060  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:04:17.900  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:04:27.940  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:04:33.065  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:33.065  3621  5014 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:04:33.065  3621  5014 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:04:33.070  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:04:33.075  3621  5014 D BatteryService: stay LED for fully charged
06-30 13:04:33.075  3621  3621 I MotionRecognitionService: Plugged
06-30 13:04:33.075  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:04:33.075  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:04:33.075  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:04:33.080  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:04:33.080  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:04:33.080  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:04:33.110  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:33.110  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:04:33.110  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:37.970  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:04:40.900  3621  4965 E Watchdog: !@Sync 29 [06-30 13:04:40.901]
,06-30 13:04:48.010  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:04:58.040  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:05:03.155  3621  5014 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:07.420  3621  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 13:05:07.420  3621  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:05:07.420  3621  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:05:08.090  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:05:10.905  3621  4965 E Watchdog: !@Sync 30 [06-30 13:05:10.908]
,06-30 13:05:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:05:13.195  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:05:13.195  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:05:14.460  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 13:05:14.460  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:05:14.475  3621  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:14.475  3621  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:18.130  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:05:28.165  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:05:33.255  3621  5179 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:38.215  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:05:39.110  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:39.130  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:39.130  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:05:39.170  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:05:39.170  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:05:39.170  2916  4371 D EnterpriseController: netId is 0
06-30 13:05:39.170  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 13:05:40.905  3621  4965 E Watchdog: !@Sync 31 [06-30 13:05:40.910]
,06-30 13:05:43.900  3621  4401 V AlarmManager: Expired Alarm result :4
,06-30 13:05:43.965  5278 10988 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,06-30 13:05:44.035  5278 10986 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-30 13:05:44.065  3621  3775 W ProcessCpuTracker: Skipping unknown process pid 10987
,06-30 13:05:44.075  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 13:05:44.075  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 13:05:44.075  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:05:44.090  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:05:44.095  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:05:44.100  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 13:05:44.100  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 13:05:44.100  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:05:44.105  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:05:44.105  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:05:44.105  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:05:44.105  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:05:44.110  3621  3775 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,06-30 13:05:44.140  3621  3621 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 13:05:44.140  3621  3621 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,06-30 13:05:44.140  3621  3621 I Sensors : Light old sensor_state 1, new sensor_state : 513 en : 1
,06-30 13:05:44.155  3621  3621 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,06-30 13:05:44.165  3621  3621 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fa3af4 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f505651 5883:com.google.android.gms/u0a14}
,06-30 13:05:44.185  5278 10986 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
06-30 13:05:44.185  5278 10986 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-30 13:05:44.195  5278 10986 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
06-30 13:05:44.195  5278 10986 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-30 13:05:44.240  8679  8679 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
06-30 13:05:44.240  8679  8679 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 13:05:44.240  8679  8679 V GCMBaseIntentService: Acquiring wakelock
,06-30 13:05:44.255  8679  8679 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-12
,06-30 13:05:44.260  8679 11000 V GCMRegistrar: Unregistering app flipboard.app
,06-30 13:05:44.285  8679 11000 V GCMBaseIntentService: Releasing wakelock
,06-30 13:05:44.310  5278 10986 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
06-30 13:05:44.310  5278 10986 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-30 13:05:44.320  3621  3645 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b5df48c u0 bg_app_info qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{da23c1 7192:tv.peel.smartremote/u0a186}
,06-30 13:05:44.340  5614  7439 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,06-30 13:05:44.340  5883 10999 I EventLogChimeraService: Aggregate from 1467282892229 (log), 1467282892229 (data)
,06-30 13:05:44.385  3621  4380 I Sensors : #>LightSensor r=0 g=1 b=2 c=3 atime=238 again=64 lux=0.000000
,06-30 13:05:44.385  3621  3874 I Sensors : Light old sensor_state 513, new sensor_state : 1 en : 0
06-30 13:05:44.385  3621  3874 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,06-30 13:05:44.390  3621  3874 D SensorManager: unregisterListener ::   
,06-30 13:05:44.390  3621  3874 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
06-30 13:05:44.390  3621  3874 V AlarmManager:  remove PendingIntent] PendingIntent{2137b0d: PendingIntentRecord{ad78ac2 android broadcastIntent}}
,06-30 13:05:44.390  5614  7439 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:05:44.390  5614  7439 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:05:44.395  2916  4371 D EnterpriseController: netId is 0
06-30 13:05:44.395  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10014
,06-30 13:05:44.420  3621  3644 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1c4924 u0 com.google.android.c2dm.intent.REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{366b4d5 8679:flipboard.app/u0a119}
,06-30 13:05:44.420  8679  8679 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
06-30 13:05:44.420  8679  8679 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 13:05:44.420  8679  8679 V GCMBaseIntentService: Acquiring wakelock
,06-30 13:05:44.445  8679  8679 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-13
,06-30 13:05:44.445  8679 11007 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,06-30 13:05:44.445  8679 11007 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
,06-30 13:05:44.445  8679 11007 D GCMBaseIntentService: Scheduling registration retry, backoff = 444521 (384000)
,06-30 13:05:44.445  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:05:44.475  3621  5652 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10014
,06-30 13:05:44.500  8679 11007 V GCMBaseIntentService: Releasing wakelock
,06-30 13:05:44.555  5883  9516 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,06-30 13:05:44.600 11009 11009 E Zygote  : v2
06-30 13:05:44.600 11009 11009 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:05:44.600 11009 11009 I libpersona: KNOX_SDCARD not a persona
,06-30 13:05:44.605  3621  3775 I ActivityManager: Start proc 11009:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
06-30 13:05:44.605 11009 11009 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 13:05:44.605 11009 11009 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:05:44.605 11009 11009 E Zygote  : accessInfo : 0
,06-30 13:05:44.645 11009 11009 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:05:44.645 11009 11009 D ActivityThread: Added TimaKeyStore provider
,06-30 13:05:44.665  3621  5654 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3b8045 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c8d39a 11009:com.samsung.android.sm/1000}
,06-30 13:05:44.675  5883 11008 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 13:05:44.725  3621  5179 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3b8045 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f505651 5883:com.google.android.gms/u0a14}
,06-30 13:05:44.750  3621  3644 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bf984a8 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c8d39a 11009:com.samsung.android.sm/1000}
,06-30 13:05:44.780  3621  4550 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bf984a8 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f505651 5883:com.google.android.gms/u0a14}
,06-30 13:05:44.805  5278 10986 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
06-30 13:05:44.805  5278 10986 E native  : request_context {
06-30 13:05:44.805  5278 10986 E native  :   type: DYNAMIC_CLASS
06-30 13:05:44.805  5278 10986 E native  :   dynamic_class_context {
06-30 13:05:44.805  5278 10986 E native  :     class_type: APP_NAME
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Maps"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Settings"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Facebook"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Gmail"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "YouTube"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Hangouts"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Google+"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Play Store"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Chrome"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Instagram"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Play Books"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Play Music"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Dropbox"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Play Movies & TV"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "WhatsApp"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Contacts"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Phone"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Flipboard"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Play Newsstand"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Evernote"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Drive"
06-30 13:05:44.805  5278 10986 E native  ,:     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Pages Manager"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Player"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "ThaliTest"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Photos"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Music"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "S Health"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Peel Smart Remote"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Calculator"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Messages"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "S Planner"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Camera"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Clock"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "My Files"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Email"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Smart Manager"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Video"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Scrapbook"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Gallery"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Voice Recorder"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "S Note"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Galaxy Apps"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Play Games"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "PEN.UP"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "S Voice"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :     instance {
06-30 13:05:44.805  5278 10986 E native  :       value: "Internet"
06-30 13:05:44.805  5278 10986 E native  :     }
06-30 13:05:44.805  5278 10986 E native  :   }
06-30 13:05:44.805  5278 10986 E native  : }
06-30 13:05:44.805  5278 10986 E native  : 
06-30 13:05:44.805  5278 10986 E ContextCompilationHandl: Compiling recognition context failed for APP_NAMES en-US
06-30 13:05:44.805  5278 10986 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-30 13:05:44.845  5883  9513 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-30 13:05:44.885  5883  9513 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 13:05:44.890  5883 11021 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-30 13:05:44.905  5883 11021 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-30 13:05:44.940  5883  9513 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 13:05:44.965  5883  9513 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 13:05:44.985  5278 10986 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
06-30 13:05:44.985  5278 10986 E native  : request_context {
06-30 13:05:44.985  5278 10986 E native  :   type: DYNAMIC_CLASS
06-30 13:05:44.985  5278 10986 E native  :   dynamic_class_context {
06-30 13:05:44.985  5278 10986 E native  :     class_type: SONG_NAME
06-30 13:05:44.985  5278 10986 E native  :     instance {
06-30 13:05:44.985  5278 10986 E native  :       value: "Over the Horizon"
06-30 13:05:44.985  5278 10986 E native  :     }
06-30 13:05:44.985  5278 10986 E native  :   }
06-30 13:05:44.985  5278 10986 E native  : }
06-30 13:05:44.985  5278 10986 E native  : request_context {
06-30 13:05:44.985  5278 10986 E native  :   type: DYNAMIC_CLASS
06-30 13:05:44.985  5278 10986 E native  :   dynamic_class_context {
06-30 13:05:44.985  5278 10986 E native  :     class_type: UNKNOWN_DYNAMIC_CLASS
06-30 13:05:44.985  5278 10986 E native  :     instance {
06-30 13:05:44.985  5278 10986 E native  :       value: "Brand Music"
06-30 13:05:44.985  5278 10986 E native  :     }
06-30 13:05:44.985  5278 10986 E native  :   }
06-30 13:05:44.985  5278 10986 E native  : }
06-30 13:05:44.985  5278 10986 E native  : request_context {
06-30 13:05:44.985  5278 10986 E native  :   type: DYNAMIC_CLASS
06-30 13:05:44.985  5278 10986 E native  :   dynamic_class_context {
06-30 13:05:44.985  5278 10986 E native  :     class_type: ARTIST_NAME
06-30 13:05:44.985  5278 10986 E native  :     instance {
06-30 13:05:44.985  5278 10986 E native  :       value: "Samsung"
06-30 13:05:44.985  5278 10986 E native  :     }
06-30 13:05:44.985  5278 10986 E native  :   }
06-30 13:05:44.985  5278 10986 E native  : }
06-30 13:05:44.985  5278 10986 E native  : 
,06-30 13:05:44.990  5278 10986 E ContextCompilationHandl: Compiling recognition context failed for MUSIC_NAMES en-US
,06-30 13:05:45.165  7192  7245 I System.out: Thread-458(ApacheHTTPLog):isSBSettingEnabled false
06-30 13:05:45.165  7192  7245 I System.out: Thread-458(ApacheHTTPLog):isShipBuild true
06-30 13:05:45.165  7192  7245 I System.out: Thread-458(ApacheHTTPLog):getDebugLevel 0x4f4c
06-30 13:05:45.165  7192  7245 I System.out: Thread-458(ApacheHTTPLog):Smart Bonding Setting is false
06-30 13:05:45.165  7192  7245 I System.out: Thread-458(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,06-30 13:05:45.170  2916  4371 D EnterpriseController: netId is 0
06-30 13:05:45.170  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10186
,06-30 13:05:45.170  7192  7245 I System.out: non-ui calls detatch()
,06-30 13:05:48.260  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:05:50.005  3621  5116 I ActivityManager: Killing 9864:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,06-30 13:05:50.080  3621  5632 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,06-30 13:05:58.305  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:05:59.995  3621  4401 V AlarmManager: Expired Alarm result :8
,06-30 13:06:03.360  3621  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:08.340  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:06:10.920  3621  4965 E Watchdog: !@Sync 32 [06-30 13:06:10.924]
,06-30 13:06:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:06:13.295  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:06:13.295  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:06:18.375  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:06:28.420  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:06:33.450  3621  5179 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:06:33.450  3621  5179 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:06:33.450  3621  5179 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:06:33.450  3621  5179 D BatteryService: stay LED for fully charged
,06-30 13:06:33.450  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:06:33.455  3621  3621 I MotionRecognitionService: Plugged
06-30 13:06:33.455  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:06:33.455  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:06:33.455  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:06:33.465  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:33.465  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:33.465  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:33.490  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:06:33.490  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:06:33.495  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:38.455  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:06:40.930  3621  4965 E Watchdog: !@Sync 33 [06-30 13:06:40.931]
,06-30 13:06:48.485  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:06:58.530  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:07:03.545  3621  5179 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:08.555  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:07:10.935  3621  4965 E Watchdog: !@Sync 34 [06-30 13:07:10.939]
,06-30 13:07:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:07:13.410  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:07:13.410  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:07:18.605  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:07:28.645  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:07:33.635  3621  5654 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:07:33.635  3621  5654 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:07:33.635  3621  5654 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:07:33.640  3621  5654 D BatteryService: stay LED for fully charged
,06-30 13:07:33.640  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:07:33.645  3621  3621 I MotionRecognitionService: Plugged
06-30 13:07:33.645  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:07:33.645  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:07:33.645  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:07:33.650  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:07:33.650  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:07:33.650  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:33.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:07:33.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:07:33.680  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:38.685  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:07:40.940  3621  4965 E Watchdog: !@Sync 35 [06-30 13:07:40.943]
,06-30 13:07:48.720  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:07:58.770  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:08:03.735  3621  5653 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:08:03.740  3621  5653 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:08:03.740  3621  5653 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:08:03.740  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:08:03.740  3621  5653 D BatteryService: stay LED for fully charged
,06-30 13:08:03.745  3621  3621 I MotionRecognitionService: Plugged
06-30 13:08:03.745  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:08:03.745  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:08:03.745  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:08:03.750  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:08:03.750  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:08:03.750  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:03.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:03.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:03.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:08.795  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:08:10.945  3621  4965 E Watchdog: !@Sync 36 [06-30 13:08:10.947]
,06-30 13:08:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:08:13.530  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:08:13.530  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:08:13.640  5015  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 2Kb duration : 92ms lastUpdatedAfter : 148977ms
,06-30 13:08:18.825  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:08:28.860  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:08:33.830  3621  5653 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:08:33.830  3621  5653 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:08:33.830  3621  5653 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:08:33.830  3621  5653 D BatteryService: stay LED for fully charged
,06-30 13:08:33.835  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:08:33.840  3621  3621 I MotionRecognitionService: Plugged
06-30 13:08:33.840  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:08:33.840  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:08:33.840  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:08:33.845  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:08:33.845  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:08:33.850  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:33.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:33.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:33.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:38.905  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:08:40.950  3621  4965 E Watchdog: !@Sync 37 [06-30 13:08:40.951]
,06-30 13:08:48.950  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:08:58.990  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:09:03.930  3621  5653 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:03.935  3621  5653 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:09:03.935  3621  5653 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:09:03.935  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:09:03.940  3621  5653 D BatteryService: stay LED for fully charged
,06-30 13:09:03.945  3621  3621 I MotionRecognitionService: Plugged
06-30 13:09:03.945  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:09:03.945  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:09:03.945  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:09:03.950  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:09:03.950  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:09:03.950  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:03.975  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:03.975  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:03.975  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:09.025  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:09:10.955  3621  4965 E Watchdog: !@Sync 38 [06-30 13:09:10.959]
,06-30 13:09:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:09:13.750  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:09:13.750  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:09:19.065  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:09:29.095  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:09:34.020  3621  5653 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:09:34.020  3621  5653 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:09:34.020  3621  5653 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:09:34.020  3621  5653 D BatteryService: stay LED for fully charged
,06-30 13:09:34.025  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:34.030  3621  3621 I MotionRecognitionService: Plugged
06-30 13:09:34.030  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:09:34.030  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 13:09:34.030  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:09:34.045  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:09:34.045  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:09:34.045  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:34.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:34.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:34.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:39.120  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:09:40.965  3621  4965 E Watchdog: !@Sync 39 [06-30 13:09:40.966]
,06-30 13:09:49.165  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:09:59.200  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:10:04.125  3621  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:10:04.125  3621  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:10:04.125  3621  5116 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:10:04.130  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:10:04.130  3621  5116 D BatteryService: stay LED for fully charged
,06-30 13:10:04.135  3621  3621 I MotionRecognitionService: Plugged
06-30 13:10:04.135  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:10:04.135  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:10:04.135  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:10:04.140  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:10:04.140  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:10:04.140  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:04.170  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:04.170  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:04.170  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:07.415  3621  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 13:10:07.420  3621  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:10:07.420  3621  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:10:07.815  3621  3768 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:10:09.250  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:10:10.975  3621  4965 E Watchdog: !@Sync 40 [06-30 13:10:10.977]
,06-30 13:10:11.020  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 13:10:11.020  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:10:11.035  3621  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 13:10:11.035  3621  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:10:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:10:13.880  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:10:13.880  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:10:19.290  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:10:29.325  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:10:34.215  3621  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:39.325  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:39.345  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:39.345  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:10:39.355  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:10:39.400  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:10:39.400  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:10:39.405  2916  4371 D EnterpriseController: netId is 0
06-30 13:10:39.405  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 13:10:40.985  3621  4965 E Watchdog: !@Sync 41 [06-30 13:10:40.985]
,06-30 13:10:49.400  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:10:59.430  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:11:04.305  3621  5632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:11:04.305  3621  5632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:11:04.305  3621  5632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:11:04.305  3621  5632 D BatteryService: stay LED for fully charged
,06-30 13:11:04.310  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:11:04.315  3621  3621 I MotionRecognitionService: Plugged
06-30 13:11:04.315  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:11:04.315  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:11:04.315  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:11:04.320  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:11:04.320  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:11:04.320  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:04.350  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:04.350  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:04.350  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:09.465  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:11:10.990  3621  4965 E Watchdog: !@Sync 42 [06-30 13:11:10.993]
,06-30 13:11:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:11:14.005  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:11:14.005  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:11:14.100  5015  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 85ms lastUpdatedAfter : 180463ms
,06-30 13:11:19.500  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:11:29.535  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:11:34.405  3621  5632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:11:34.405  3621  5632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:11:34.405  3621  5632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
,06-30 13:11:34.410  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:11:34.420  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:11:34.420  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:11:34.420  3621  3621 I MotionRecognitionService: Plugged
06-30 13:11:34.420  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:11:34.420  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:11:34.420  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:11:34.420  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:11:34.425  3621  5632 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms,
06-30 13:11:34.425  3621  5632 D BatteryService: stay LED for fully charged
,06-30 13:11:34.450  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:34.450  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:34.450  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:39.565  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:11:40.995  3621  4965 E Watchdog: !@Sync 43 [06-30 13:11:40.997]
,06-30 13:11:49.610  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:11:59.655  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:12:04.500  3621  5632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:12:04.500  3621  5632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:12:04.500  3621  5632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:12:04.500  3621  5632 D BatteryService: stay LED for fully charged
,06-30 13:12:04.500  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:12:04.505  3621  3621 I MotionRecognitionService: Plugged
06-30 13:12:04.505  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:12:04.505  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:12:04.505  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:12:04.515  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:12:04.515  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:12:04.515  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:04.525  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:04.540  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:12:04.540  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:09.695  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:12:11.000  3621  4965 E Watchdog: !@Sync 44 [06-30 13:12:11.004]
,06-30 13:12:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:12:14.185  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:12:14.185  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:12:19.720  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:12:29.765  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:12:34.600  3621  5632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:12:34.600  3621  5632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:12:34.600  3621  5632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:12:34.600  3621  5632 D BatteryService: stay LED for fully charged
,06-30 13:12:34.600  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:12:34.605  3621  3621 I MotionRecognitionService: Plugged
06-30 13:12:34.605  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:12:34.605  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:12:34.605  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:12:34.615  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:12:34.615  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:12:34.615  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:34.640  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:12:34.640  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:12:34.640  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:39.800  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:12:41.010  3621  4965 E Watchdog: !@Sync 45 [06-30 13:12:41.012]
,06-30 13:12:49.830  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:12:59.865  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:13:04.690  3621  5632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:13:04.690  3621  5632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:13:04.690  3621  5632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:13:04.690  3621  5632 D BatteryService: stay LED for fully charged
,06-30 13:13:04.695  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:13:04.700  3621  3621 I MotionRecognitionService: Plugged
06-30 13:13:04.700  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:13:04.700  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:13:04.700  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:13:04.710  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:13:04.710  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:13:04.710  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:04.730  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:04.730  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:13:04.730  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:09.905  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:13:11.015  3621  4965 E Watchdog: !@Sync 46 [06-30 13:13:11.019]
,06-30 13:13:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:13:14.300  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:13:14.300  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:13:19.955  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:13:30.000  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:13:34.790  3621  5632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:13:34.790  3621  5632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:13:34.790  3621  5632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:13:34.790  3621  5632 D BatteryService: stay LED for fully charged
06-30 13:13:34.795  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:13:34.795  3621  3621 I MotionRecognitionService: Plugged
06-30 13:13:34.795  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:13:34.795  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:13:34.795  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
06-30 13:13:34.800  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:13:34.800  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:13:34.800  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:34.830  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:34.830  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:13:34.830  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:40.030  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:13:41.020  3621  4965 E Watchdog: !@Sync 47 [06-30 13:13:41.024]
,06-30 13:13:50.075  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:14:00.120  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:14:04.880  3621  5632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:10.165  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:14:11.025  3621  4965 E Watchdog: !@Sync 48 [06-30 13:14:11.028]
,06-30 13:14:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:14:14.415  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:14:14.415  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:14:14.510  5015  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 83ms lastUpdatedAfter : 180409ms
,06-30 13:14:20.205  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:14:30.255  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:14:34.980  3621  4550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:14:34.980  3621  4550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:14:34.980  3621  4550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:14:34.980  3621  4550 D BatteryService: stay LED for fully charged
,06-30 13:14:34.980  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:14:34.985  3621  3621 I MotionRecognitionService: Plugged
06-30 13:14:34.985  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:14:34.985  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:14:34.985  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:14:34.995  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:14:34.995  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:14:34.995  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:35.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:14:35.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:14:35.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:40.290  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:14:41.030  3621  4965 E Watchdog: !@Sync 49 [06-30 13:14:41.032]
,06-30 13:14:50.335  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:15:00.365  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:15:05.070  3621  4550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:15:05.070  3621  4550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:15:05.070  3621  4550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:15:05.070  3621  4550 D BatteryService: stay LED for fully charged
,06-30 13:15:05.075  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:15:05.080  3621  3621 I MotionRecognitionService: Plugged
06-30 13:15:05.080  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:15:05.080  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:15:05.080  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:15:05.085  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:15:05.085  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:15:05.085  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:05.115  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:15:05.115  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:15:05.115  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:07.415  3621  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 13:15:07.415  3621  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:15:07.420  3621  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:15:10.420  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:15:11.030  3621  4965 E Watchdog: !@Sync 50 [06-30 13:15:11.035]
,06-30 13:15:11.320  2950  5168 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:15:13.735  3621  5690 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
06-30 13:15:13.735  3621  5690 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
06-30 13:15:13.735  3621  5690 V MARsPolicyManager: updateSMDBValues
,06-30 13:15:13.740  3621  3843 E MARsDBManager: updateDBAll : begin --size 0
,06-30 13:15:13.740  3621  3843 E MARsDBManager: updateDBAll : end,
,06-30 13:15:14.435  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 13:15:14.435  3621  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:15:14.455  3621  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 13:15:14.455  3621  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:15:14.620  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:15:14.620  5015  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:15:20.470  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:15:30.510  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 13:15:35.165  3621  4550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:15:35.165  3621  4550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:15:35.165  3621  4550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:15:35.165  3621  4550 D BatteryService: stay LED for fully charged
,06-30 13:15:35.165  3621  3621 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:15:35.170  3621  3621 I MotionRecognitionService: Plugged
06-30 13:15:35.170  3621  3621 D MotionRecognitionService:   cableConnection= 1
06-30 13:15:35.170  3621  3621 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:15:35.170  3621  3621 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:15:35.180  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:15:35.180  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:15:35.180  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:15:35.205  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:15:35.205  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:15:35.205  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),06-30 13:15:39.570  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 13:15:39.590  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 13:15:39.595  5614  5614 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 13:15:39.635  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:15:39.635  9239  9271 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:15:39.640  2916  4371 D EnterpriseController: netId is 0
06-30 13:15:39.640  2916  4371 D Netd    : getNetworkForDns: using netid 0 for uid 10031
06-30 13:15:40.555  3621  6674 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
06-30 13:15:41.040  3621  4965 E Watchdog: !@Sync 51 [06-30 13:15:41.041]
06-30 13:15:42.115 11259 11259 I FIPS_bssl: FIPS approved mode (1) | 11259 | app_process
06-30 13:15:42.120 11259 11259 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:15:42.125 11259 11259 D AndroidRuntime: CheckJNI is OFF
06-30 13:15:42.125 11259 11259 D AndroidRuntime: readGMSProperty: start
06-30 13:15:42.125 11259 11259 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:15:42.125 11259 11259 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:15:42.125 11259 11259 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:15:42.125 11259 11259 D AndroidRuntime: readGMSProperty: end
06-30 13:15:42.125 11259 11259 D AndroidRuntime: addProductProperty: start
06-30 13:15:42.155 11259 11259 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:15:42.180 11259 11259 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:15:42.185 11259 11259 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:15:42.200 11259 11259 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 13:15:42.210  3621  5653 D PackageManager: START PACKAGE DELETE: observer{177625582}
06-30 13:15:42.210  3621  5653 D PackageManager: pkg{<packageName>}
06-30 13:15:42.210  3621  5653 D PackageManager: user{0}
06-30 13:15:42.210  3621  5653 D PackageManager: caller{2000}
06-30 13:15:42.210  3621  5653 D PackageManager: flags{2}
06-30 13:15:42.210  3621  5653 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 13:15:42.210  3621  5653 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 13:15:42.210  3621  5653 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 13:15:42.210  3621  5653 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:15:42.210  3621  5653 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:15:42.210  3621  3908 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 13:15:42.210  3621  3908 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 13:15:42.210  3621  3908 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 13:15:42.210  3621  3908 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 13:15:42.210  3621  3908 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 13:15:42.215  3621  3908 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 13:15:42.215  3621  3908 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 13:15:42.215  3621  3908 D PackageManager: !@killApplicatoin: 10007, uninstall pkg
06-30 13:15:42.215  3621  3908 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 13:15:42.215  3621  3775 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=-1: uninstall pkg
06-30 13:15:42.215  3621  3908 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 13:15:42.215  3621  3775 I ActivityManager: Killing 10391:com.test.thalitest/u0a7 (adj 1): stop com.test.thalitest cause uninstall pkg
06-30 13:15:42.220  3621  3775 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:15:42.220  3621  3775 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
06-30 13:15:42.250  3621  3908 D AASAinstall: there is not AASApackages.xml file
06-30 13:15:42.255  3621  3775 I ActivityManager: Start proc 11275:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
06-30 13:15:42.260 11275 11275 E Zygote  : v2
06-30 13:15:42.260 11275 11275 I libpersona: KNOX_SDCARD checking this for 10007
06-30 13:15:42.260 11275 11275 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:42.265 11275 11275 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 13:15:42.270 11275 11275 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 13:15:42.270  3621  3775 I ActivityManager:   Force finishing activity ActivityRecord{151da77 u0 com.test.thalitest/.MainActivity t69}
06-30 13:15:42.270  3621  3775 I ActivityManager:   Force finishing activity ActivityRecord{1f62a5e u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}
06-30 13:15:42.275 11275 11275 E Zygote  : accessInfo : 0
06-30 13:15:42.275 11275 11275 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 13:15:42.285  3621  3775 D InputDispatcher: Focused application set to: xxxx
06-30 13:15:42.295  3621  3775 I ActivityManager: Killing 9879:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): DHA:empty #31
06-30 13:15:42.310 11275 11275 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:42.310 11275 11275 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:42.310  3621  3775 D ActivityManager: mDVFSHelper.acquire()
06-30 13:15:42.345  3621  3645 D GraphicsStats: Buffer count: 5
06-30 13:15:42.345  3621  5632 I WindowState: WIN DEATH: Window{5ba2adc u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:15:42.345  2905  2987 I SurfaceFlinger: id=14 Removed NainActivit (4/9)
06-30 13:15:42.345  3621  5116 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d7efe8f)
06-30 13:15:42.345  2905  2985 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
06-30 13:15:42.345  3621  4453 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:15:42.345  2905  2985 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
06-30 13:15:42.345  3621  4453 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:15:42.345  3621  4453 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:15:42.350  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbec7c474
06-30 13:15:42.535  3621  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
06-30 13:15:42.565  3621  3908 W PackageSettings: Skipping PackageSetting{db45f88 com.example.hello/10691} due to missing metadata
06-30 13:15:42.630  3621  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
06-30 13:15:42.630  2937  2937 W keystore: ENTER clear_uid from uid 1000 for 10007
06-30 13:15:42.635  3621  3908 I art     : Starting a blocking GC Explicit
06-30 13:15:42.645 10457 10457 D ViewRootImpl: #3 mView = null
06-30 13:15:42.645  2905  4788 I SurfaceFlinger: id=15 Removed HrantPermis (6/8)
06-30 13:15:42.650  2905  2985 I SurfaceFlinger: id=15 Removed HrantPermis (-2/8)
06-30 13:15:42.650  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbec7c474
06-30 13:15:42.650  3621  5653 D InputDispatcher: Focus left window: 10457
06-30 13:15:42.655  2905  2905 I SurfaceFlinger: id=16 createSurf (1528x2333),1 flag=4, VSBConnecti
06-30 13:15:42.665  3621  4439 D InputDispatcher: Focus entered window: 6782
06-30 13:15:42.670  6782  9736 D mali_winsys: new_window_surface returns 0x3000,  [1528x2333]-format:1
06-30 13:15:42.690  5100  5100 D Launcher: onRestart, Launcher: 124618952
06-30 13:15:42.750  3621  3908 I art     : Explicit concurrent mark sweep GC freed 18559(1441KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 30MB/45MB, paused 1.688ms total 117.132ms
06-30 13:15:42.775  3621  3908 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
06-30 13:15:42.775  3621  3908 D AASAuninstall: userId = 0, info.removedAppID = 10007, info.uid = 10007, packageName = com.test.thalitest
06-30 13:15:42.780  3621  3908 D AASAinstall: there is not AASApackages.xml file
06-30 13:15:42.780  3621  3908 D PackageManager: result of delete: 1{177625582}
06-30 13:15:42.780 11259 11259 I art     : System.exit called, status: 0
06-30 13:15:42.780 11259 11259 I AndroidRuntime: VM exiting with result code 0.
06-30 13:15:42.780  3621  3908 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 13:15:42.780  3621  3908 D PackageManager: userId{-1}
06-30 13:15:42.780  3621  3908 D PackageManager: andCode{true}
06-30 13:15:42.975  3621  3775 I WindowManager: Screenshot max retries 4 of Token{c2c82b8 ActivityRecord{cfe211b u0 com.samsung.android.MtpApplication/.USBConnection t68}} appWin=Window{8f618c9 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
06-30 13:15:42.975  3621  3621 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
06-30 13:15:42.990  3621  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
06-30 13:15:42.990  3621  4388 D UsbHostManager: displayNotification : [02h,02h,01h]
06-30 13:15:42.995  3621  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
06-30 13:15:42.995  3621  4388 D UsbHostManager: displayNotification : [0ah,00h,00h]
06-30 13:15:42.995  3621  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
06-30 13:15:42.995  3621  4388 D UsbHostManager: displayNotification : [02h,0dh,00h]
06-30 13:15:42.995  3621  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
06-30 13:15:42.995  3621  4388 D UsbHostManager: displayNotification : [0ah,00h,01h]
06-30 13:15:43.000  3621  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
06-30 13:15:43.000  3621  4388 D UsbHostManager: displayNotification : [09h,00h,00h]
06-30 13:15:43.005  3621  4499 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
06-30 13:15:43.005  3621  4499 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
06-30 13:15:43.005  3621  4499 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
06-30 13:15:43.015  3621  3845 I Choreographer: Skipped 38 frames!  The application may be doing too much work on its main thread.
06-30 13:15:43.025  3621  5654 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
06-30 13:15:43.045  5100  5100 D Launcher: onStart, Launcher: 124618952
06-30 13:15:43.045  5100  5100 D Launcher.HomeView: onStart
06-30 13:15:43.065  5100  5100 V ActivityThread: updateVisibility : ActivityRecord{ffafe96 token=android.os.BinderProxy@583bddc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
06-30 13:15:43.065  3621  3908 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=0: pkg removed
06-30 13:15:43.065  3621  3908 I ActivityManager: Killing 11275:com.test.thalitest/u0a7 (adj -100): stop com.test.thalitest cause pkg removed
06-30 13:15:43.070  3621  4415 I EventHub: Removing device '/dev/input/event10' due to inotify event
06-30 13:15:43.075  3621  3908 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:15:43.075  3621  3908 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
06-30 13:15:43.080  2905  2905 I SurfaceFlinger: id=17 createSurf (1440x2560),1 flag=4, Mauncher
06-30 13:15:43.080  3621  4439 V WindowOrientationListener: setCurrentAppOrientation :1
06-30 13:15:43.080  3621  4439 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 13:15:43.100  5100  5416 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
06-30 13:15:43.105  3621  4415 I EventHub: Removing device '/dev/input/event7' due to inotify event
06-30 13:15:43.135  3621  4415 I EventHub: Removing device '/dev/input/event8' due to inotify event
06-30 13:15:43.170  3621  4415 I EventHub: Removing device '/dev/input/event9' due to inotify event
06-30 13:15:43.200  9788 11299 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
06-30 13:15:43.220  3621  4415 I EventHub: Removing device '/dev/input/event11' due to inotify event
06-30 13:15:43.225  3621  3845 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3621 uid:1000
06-30 13:15:43.225  3621  3845 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:15:43.225  3621  3845 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3621 uid:1000
06-30 13:15:43.225  3621  3845 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:15:43.230  3621  5117 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 13:15:43.230  3621  5117 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:15:43.230  9788 11299 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
06-30 13:15:43.235  3621  3621 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:15:43.240  3621  3644 W ActivityManager: No pending application record for pid 11275 (IApplicationThread android.app.ApplicationThreadProxy@576f4ab); dropping process
06-30 13:15:43.245  6782  6782 I Choreographer: Skipped 32 frames!  The application may be doing too much work on its main thread.
06-30 13:15:43.245  3621  3621 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 13:15:43.245  3621  3621 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
06-30 13:15:43.250  9788 11299 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
06-30 13:15:43.250  3621  4499 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
06-30 13:15:43.255  3621  4415 I EventHub: Removing device '/dev/input/event12' due to inotify event
06-30 13:15:43.250  3621  4499 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
06-30 13:15:43.250  3621  3775 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
06-30 13:15:43.265  3621  3775 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
06-30 13:15:43.285  3621  4415 I EventHub: Removing device '/dev/input/event13' due to inotify event
06-30 13:15:43.320  3621  4415 I EventHub: Removing device '/dev/input/event14' due to inotify event
06-30 13:15:43.355  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbec7c40c
06-30 13:15:43.365  3621  3779 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{8f618c9 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
06-30 13:15:43.380  3621  4439 V WindowStateAnimator: Finishing drawing window Window{8f618c9 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
06-30 13:15:43.415  2905  2905 I SurfaceFlinger: id=18 createSurf (1592x384),1 flag=4, VSBConnecti
06-30 13:15:43.425  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
06-30 13:15:43.425  4513  4513 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED

```
