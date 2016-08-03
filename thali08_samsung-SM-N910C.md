#### Test 79689775e33639d_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,08-03 17:29:10.420  3573  6928 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), CUR = 124, LCD = 0
--------- beginning of main
08-03 17:29:11.160 11500 11500 I FIPS_bssl: FIPS approved mode (1) | 11500 | app_process
08-03 17:29:11.170 11500 11500 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 17:29:11.170 11500 11500 D AndroidRuntime: CheckJNI is OFF
08-03 17:29:11.170 11500 11500 D AndroidRuntime: readGMSProperty: start
08-03 17:29:11.170 11500 11500 D AndroidRuntime: readGMSProperty: already setted!!
08-03 17:29:11.170 11500 11500 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-03 17:29:11.170 11500 11500 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-03 17:29:11.170 11500 11500 D AndroidRuntime: readGMSProperty: end
08-03 17:29:11.170 11500 11500 D AndroidRuntime: addProductProperty: start
08-03 17:29:11.200 11500 11500 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 17:29:11.230 11500 11500 I Radio-JNI: register_android_hardware_Radio DONE
08-03 17:29:11.235 11500 11500 E AffinityControl: AffinityControl: registerfunction enter
08-03 17:29:11.250 11500 11500 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 17:29:11.305  3573  4718 D GameManagerService: identifyGamePackage. com.test.thalitest
08-03 17:29:11.305  3573  4718 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-03 17:29:11.310  3573  4718 D ActivityManager: mDVFSHelper.acquire()
08-03 17:29:11.310  3573  4718 V WindowManager: addAppToken: AppWindowToken{634d6a token=Token{94f7f55 ActivityRecord{d24ea0c u0 com.test.thalitest/.MainActivity t108}}} to stack=1 task=108 at 0
08-03 17:29:11.325  3573  3815 D SecWifiDisplayUtil: Metadata value : none
08-03 17:29:11.325  3573  3815 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4dc1fc2 V.E...... R.....ID 0,0-0,0}
08-03 17:29:11.330  3573  3815 D ISSUE_DEBUG: InputChannelName : a03d110 Starting com.test.thalitest
08-03 17:29:11.330 11516 11516 E Zygote  : v2
08-03 17:29:11.330 11516 11516 I libpersona: KNOX_SDCARD checking this for 10007
08-03 17:29:11.330 11516 11516 I libpersona: KNOX_SDCARD not a persona
08-03 17:29:11.335  3573  4718 I ActivityManager: Start proc 11516:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
08-03 17:29:11.335  3573  4718 D InputDispatcher: Focused application set to: xxxx
08-03 17:29:11.335 11516 11516 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
08-03 17:29:11.335  3573  4718 D InputDispatcher: Focus left window: 7658
08-03 17:29:11.335 11516 11516 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:11.335  3573  3749 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{218c44c u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-03 17:29:11.340 11500 11500 D AndroidRuntime: Shutting down VM
08-03 17:29:11.340  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-03 17:29:11.340  3573  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-03 17:29:11.340 11516 11516 E Zygote  : accessInfo : 0
08-03 17:29:11.340 11516 11516 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-03 17:29:11.350  2905  2905 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-03 17:29:11.370  3573  3815 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3573 uid:1000
08-03 17:29:11.370  3573  3815 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:11.370  3573  3815 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3573 uid:1000
08-03 17:29:11.370  3573  3815 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-03 17:29:11.370  3573  3815 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-03 17:29:11.370 11516 11516 D TimaKeyStoreProvider: TimaSignature is unavailable
08-03 17:29:11.370 11516 11516 D ActivityThread: Added TimaKeyStore provider
08-03 17:29:11.375  3573  4909 V WindowOrientationListener: setCurrentAppOrientation :-1
08-03 17:29:11.375  3573  4909 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-03 17:29:11.375  3573  3749 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a03d110 u0 d0 Starting com.test.thalitest}
08-03 17:29:11.375  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-03 17:29:11.385  3573  4909 D ActivityManager:  Launching com.test.thalitest, updated priority
08-03 17:29:11.410  3573  3573 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-03 17:29:11.410  3573  3745 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-03 17:29:11.415  2905  2981 D libEGL  : eglTerminate EGLDisplay = 0xb6901624
08-03 17:29:11.420  2905  5400 I SurfaceFlinger: id=17 Removed VSBConnecti (7/11)
08-03 17:29:11.420  2905  2981 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
08-03 17:29:11.425  2905  2985 D libEGL  : eglTerminate EGLDisplay = 0xb4fff624
08-03 17:29:11.425  2905  2985 D libEGL  : eglTerminate EGLDisplay = 0xb4fff624
08-03 17:29:11.425  2905  2981 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-03 17:29:11.425  2905 10149 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-03 17:29:11.425  7658  7658 V ActivityThread: updateVisibility : ActivityRecord{4ac28f4 token=android.os.BinderProxy@715a771 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-03 17:29:11.430  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbead0474
08-03 17:29:11.430  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbead0474
08-03 17:29:11.435  5116  5116 V ActivityThread: updateVisibility : ActivityRecord{59854d9 token=android.os.BinderProxy@708f29 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-03 17:29:11.435  5116  5116 D Launcher: onTrimMemory. Level: 20
08-03 17:29:11.440  3573  3815 V WindowStateAnimator: Finishing drawing window Window{a03d110 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-03 17:29:11.445  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbead040c
08-03 17:29:11.460  2905  2981 I SurfaceFlinger: id=18 Removed VSBConnecti (4/9)
08-03 17:29:11.460  2905  2985 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/9)
08-03 17:29:11.465  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbead0474
,08-03 17:29:11.715  3573  4909 I WindowManager: Screenshot max retries 4 of Token{94f7f55 ActivityRecord{d24ea0c u0 com.test.thalitest/.MainActivity t108}} appWin=Window{a03d110 u0 d0 Starting com.test.thalitest} drawState=4
,08-03 17:29:11.720  3573  3745 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,08-03 17:29:11.740  3573  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-03 17:29:11.765  3573  6928 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-03 17:29:11.775  3573  6928 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-03 17:29:11.815 11516 11516 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-03 17:29:11.850 11516 11516 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-03 17:29:11.855 11516 11516 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 4986-4988)
08-03 17:29:11.855 11516 11516 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-03 17:29:11.875 11516 11531 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-03 17:29:11.875 11516 11516 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {65858dc}
08-03 17:29:11.875 11516 11516 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-03 17:29:11.875 11516 11516 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 17:29:11.885 11516 11516 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-03 17:29:11.915 11516 11516 D libEGL  : eglInitialize EGLDisplay = 0xbec49e7c
,08-03 17:29:11.940  3573  3595 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
08-03 17:29:11.945  3573  3595 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-03 17:29:11.995 11516 11516 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-03 17:29:12.010 11516 11516 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 17:29:12.010 11516 11516 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-03 17:29:12.010 11516 11516 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-03 17:29:12.010 11516 11516 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-03 17:29:12.035 11516 11516 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-03 17:29:12.040 11516 11516 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung,
,08-03 17:29:12.110 11516 11516 D SecWifiDisplayUtil: Metadata value : none
,08-03 17:29:12.110 11516 11516 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e5b441a I.E...... R.....ID 0,0-0,0}
,08-03 17:29:12.120 11516 11568 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 17:29:12.125  3573  4718 D ISSUE_DEBUG: InputChannelName : 31dcced com.test.thalitest/com.test.thalitest.MainActivity
,08-03 17:29:12.130  3573  5122 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-03 17:29:12.130  3573  5122 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:12.130  3573  3573 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-03 17:29:12.130  3573  3573 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-03 17:29:12.160 11516 11516 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 11516
,08-03 17:29:12.165  3573  5789 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/11516 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:12.165  3573  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-03 17:29:12.165  3573  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-03 17:29:12.165  3573  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-03 17:29:12.165  3573  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:12.165  3573  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:12.165  3573  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-03 17:29:12.165  3573  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:12.165  3573  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-03 17:29:12.165  3573  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-03 17:29:12.165  3573  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-03 17:29:12.165  3573  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:12.175 11516 11531 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-03 17:29:12.185 11516 11516 D SecWifiDisplayUtil: Metadata value : none
,08-03 17:29:12.195  2905  2905 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-03 17:29:12.200  3573  4909 D InputDispatcher: Focus entered window: 11516
,08-03 17:29:12.205  3573  3815 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3573 uid:1000
,08-03 17:29:12.205  3573  3815 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:12.205  3573  3815 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3573 uid:1000
08-03 17:29:12.205  3573  3815 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-03 17:29:12.205 11516 11568 D libEGL  : eglInitialize EGLDisplay = 0x9c13f7c4
08-03 17:29:12.205 11516 11568 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 17:29:12.210 11516 11568 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-03 17:29:12.215 11516 11516 V ActivityThread: updateVisibility : ActivityRecord{4ec257d token=android.os.BinderProxy@c762c5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-03 17:29:12.220 11516 11516 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,08-03 17:29:12.220 11516 11516 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.,
,08-03 17:29:12.220  3573  5825 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-03 17:29:12.235 11516 11516 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-03 17:29:12.280 11516 11575 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 17:29:12.280 11516 11575 D libEGL  : eglInitialize EGLDisplay = 0x9b2a03ec
,08-03 17:29:12.285  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbead040c
,08-03 17:29:12.290  3573  4909 V WindowStateAnimator: Finishing drawing window Window{31dcced u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-03 17:29:12.290 11516 11516 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-03 17:29:12.290 11516 11516 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c762c5 time:365424
,08-03 17:29:12.300  3573  3815 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:12.300  3573  3573 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-03 17:29:12.305  3573  3573 I KnoxTimeoutHandler: SD activityfalse
,08-03 17:29:12.310  3573  3815 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +590ms (total +997ms)
,08-03 17:29:12.310  3573  3815 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d24ea0c u0 com.test.thalitest/.MainActivity t108} time:365442
08-03 17:29:12.310  3573  3815 D ActivityManager: mDVFSHelper.release()
08-03 17:29:12.310  3573  3815 D ViewRootImpl: #3 mView = null
,08-03 17:29:12.310  2905  2985 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-03 17:29:12.310  2905  5400 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,08-03 17:29:12.320  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbead0474
,08-03 17:29:12.330 11516 11516 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11516
,08-03 17:29:12.490 11516 11516 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 17:29:12.630 11516 11581 D jxcore_app_log: JniHelper::setJavaVM(0xb4874000), pthread_self() = -1754007248
,08-03 17:29:12.635 11516 11581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 17:29:12.635 11516 11581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 17:29:12.635 11516 11581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 17:29:12.635 11516 11581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 17:29:12.635 11516 11581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-03 17:29:12.635 11516 11581 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5aa6d3b added. We now have 1 listener(s)
08-03 17:29:12.635 11516 11581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
08-03 17:29:12.635 11516 11581 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
08-03 17:29:12.640 11516 11581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 17:29:12.640 11516 11581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 17:29:12.640 11516 11581 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@689b696 added. We now have 1 listener(s)
08-03 17:29:12.640 11516 11581 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 17:29:12.640 11516 11581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 17:29:12.640 11516 11581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 17:29:12.640 11516 11581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 17:29:12.645 11516 11581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 17:29:12.645 11516 11581 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 17:29:12.645 11516 11581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 17:29:12.645 11516 11581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,08-03 17:29:12.650 11516 11581 D BluetoothAdapter: STATE_ON
,08-03 17:29:12.650 11516 11581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 17:29:12.650 11516 11581 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 17:29:12.650 11516 11581 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 17:29:12.650 11516 11581 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 17:29:12.650 11516 11581 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 17:29:12.655 11516 11516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 17:29:12.655 11516 11516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 17:29:12.675 11516 11516 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 17:29:13.075 11516 11582 W jxcore-log: Initializing JXcore engine
08-03 17:29:13.075 11516 11582 W jxcore-log: JXcore engine is ready
,08-03 17:29:13.100  5751  5751 E audit   : type=1400 msg=audit(1470238153.100:268): avc:  denied  { ioctl } for  pid=11582 comm="Thread-1143" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4122 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
08-03 17:29:13.100  5751  5751 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:13.100  5751  5751 E audit   : type=1300 msg=audit(1470238153.100:268): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=9763a3c8 items=0 ppid=2965 ppcomm=main pid=11582 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1143" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-03 17:29:13.100  5751  5751 E audit   : type=1327 msg=audit(1470238153.100:268): proctitle="com.test.thalitest"
08-03 17:29:13.100  5751  5751 E audit   : type=1320 msg=audit(1470238153.100:268): 
08-03 17:29:13.100  5751  5751 E audit   : type=1400 msg=audit(1470238153.100:269): avc:  denied  { ioctl } for  pid=11582 comm="Thread-1143" path="socket:[39478]" dev="sockfs" ino=39478 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-03 17:29:13.100  5751  5751 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-03 17:29:13.100  5751  5751 E audit   : type=1300 msg=audit(1470238153.100:269): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=9763a3c8 items=0 ppid=2965 ppcomm=main pid=11582 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1143" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-03 17:29:13.100  5751  5751 E audit   : type=1327 msg=audit(1470238153.100:269): proctitle="com.test.thalitest"
08-03 17:29:13.100  5751  5751 E audit   : type=1320 msg=audit(1470238153.100:269): 
,08-03 17:29:13.105 11516 11582 W jxcore-log: Starting JXcore engine
,08-03 17:29:13.135  4696  4696 D Recents : onTaskStackChanged
,08-03 17:29:13.155 11516 11582 W jxcore-log: Platform android
08-03 17:29:13.155 11516 11582 W jxcore-log: 
08-03 17:29:13.155 11516 11582 W jxcore-log: Process ARCH arm
08-03 17:29:13.155 11516 11582 W jxcore-log: 
,08-03 17:29:13.265 11516 11582 I jxcore-log: JXcore Cordova bridge is ready!
08-03 17:29:13.265 11516 11582 I jxcore-log: 
08-03 17:29:13.265 11516 11582 W jxcore-log: JXcore engine is started
,08-03 17:29:13.270 11516 11581 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 17:29:13.270 11516 11516 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 17:29:13.280 11516 11582 E jxcore  : Error!: syntax error
08-03 17:29:13.280 11516 11582 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-03 17:29:13.285 11516 11516 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (57)
08-03 17:29:13.285 11516 11516 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-03 17:29:13.290  3573  3595 D InputDispatcher: Focused application set to: xxxx
08-03 17:29:13.295  3573  3595 I ActivityManager: Killing 10662:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,08-03 17:29:13.300 11516 11516 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-03 17:29:13.300 11516 11516 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-03 17:29:13.300 11516 11516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 17:29:13.300 11516 11516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 17:29:13.300 11516 11516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 17:29:13.300 11516 11516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 17:29:13.300 11516 11516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5aa6d3b removed from the list
08-03 17:29:13.300 11516 11516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 17:29:13.300 11516 11516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@689b696 removed from the list
08-03 17:29:13.300 11516 11516 D io.jxcore.node.ConnectivityMonitor: stop
08-03 17:29:13.300 11516 11516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-03 17:29:13.300 11516 11516 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 17:29:13.305 11516 11516 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-03 17:29:13.305  3573  6928 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-03 17:29:13.315 11516 11516 D ViewRootImpl: #3 mView = null
,08-03 17:29:13.315  2905 10149 I SurfaceFlinger: id=20 Removed NainActivit (6/8)
08-03 17:29:13.315  2905  2985 I SurfaceFlinger: id=20 Removed NainActivit (-2/8)
,08-03 17:29:13.315  3573  4550 D InputDispatcher: Focus left window: 11516
,08-03 17:29:13.320  3573  3815 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3573 uid:1000
08-03 17:29:13.320  3573  3815 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:13.320  3573  3815 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3573 uid:1000
08-03 17:29:13.320  3573  3815 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-03 17:29:13.320 11516 11516 D cr_Ime  : [ImeAdapter.java:587] detach
,08-03 17:29:13.320 11516 11516 E ViewRootImpl: sendUserActionEvent() mView == null
,08-03 17:29:13.320  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbead0474
,08-03 17:29:13.325  3573  5123 D ActivityManager: mDVFSHelper.acquire()
,08-03 17:29:13.335  3573  3573 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
08-03 17:29:13.335  3573  3745 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-03 17:29:13.335  3573  5123 V WindowOrientationListener: setCurrentAppOrientation :1
08-03 17:29:13.335  3573  5123 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-03 17:29:13.340  3573  3745 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,08-03 17:29:13.340  3573  3596 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,08-03 17:29:13.350  3573  3595 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-03 17:29:13.350  3573  3595 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-03 17:29:13.350  3573  3573 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-03 17:29:13.350  3573  3573 I KnoxTimeoutHandler: Shared devices show user statefalse
08-03 17:29:13.350  3573  3573 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-03 17:29:13.355  5116  5116 D Launcher: onRestart, Launcher: 143768032
,08-03 17:29:13.360  5116  5116 D Launcher: onStart, Launcher: 143768032
08-03 17:29:13.360  5116  5116 D Launcher.HomeView: onStart
,08-03 17:29:13.360  5116  5116 V ActivityThread: updateVisibility : ActivityRecord{59854d9 token=android.os.BinderProxy@708f29 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-03 17:29:13.370  2905  2905 I SurfaceFlinger: id=21 createSurf (1440x2560),1 flag=4, Mauncher
,08-03 17:29:13.370  3573  3749 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{218c44c u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
,08-03 17:29:13.375  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=8600 newVal=40008500 diff=40000300
,08-03 17:29:13.375  2905  2905 I SurfaceFlinger: id=22 createSurf (1528x2333),1 flag=4, VSBConnecti
,08-03 17:29:13.375  3573  3749 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d4709c8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-03 17:29:13.375  5116  5456 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-03 17:29:13.375  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008000 mask=ffffffff oldVal=40008500 newVal=40008000 diff=500
08-03 17:29:13.375  3573  5015 D InputDispatcher: Focus entered window: 7658
08-03 17:29:13.375  3573  3815 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3573 uid:1000
08-03 17:29:13.375  3573  3815 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:29:13.375  3573  3815 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3573 uid:1000
08-03 17:29:13.375  3573  3815 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-03 17:29:13.380  7658 10259 D mali_winsys: new_window_surface returns 0x3000,  [1528x2333]-format:1
,08-03 17:29:13.380  2905  2905 I SurfaceFlinger: id=23 createSurf (1592x384),1 flag=4, VSBConnecti
,08-03 17:29:13.380  7658 10259 D mali_winsys: new_window_surface returns 0x3000,  [1592x384]-format:1
,08-03 17:29:13.385  7658  7658 V ActivityThread: updateVisibility : ActivityRecord{4ac28f4 token=android.os.BinderProxy@715a771 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-03 17:29:13.410  3573  4909 V WindowStateAnimator: Finishing drawing window Window{d4709c8 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-03 17:29:13.415  3573  5798 V WindowStateAnimator: Finishing drawing window Window{2716986 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-03 17:29:13.415  7658  7658 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@715a771 time:366549
,08-03 17:29:13.425  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbead040c
08-03 17:29:13.425  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbead040c
,08-03 17:29:13.425  3573  3815 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-03 17:29:13.425  3573  3573 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-03 17:29:13.425  3573  3573 I KnoxTimeoutHandler: SD activityfalse
,08-03 17:29:13.425  3573  3815 D ActivityManager: mDVFSHelper.release()
08-03 17:29:13.425  3573  3815 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ce4d262 u0 com.samsung.android.MtpApplication/.USBConnection t107} time:366558
,08-03 17:29:13.435  3573  5018 V WindowStateAnimator: Finishing drawing window Window{218c44c u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-03 17:29:13.435  5116  5116 D Launcher.HomeView: onStop
,08-03 17:29:13.435  3573  3815 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:13.435  3573  3573 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-03 17:29:13.435  3573  3815 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f078139 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t106} time:366569
,08-03 17:29:13.440  3573  3573 I KnoxTimeoutHandler: SD activityfalse
,08-03 17:29:13.440  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbead040c
,08-03 17:29:13.810 11585 11585 I FIPS_bssl: FIPS approved mode (1) | 11585 | app_process
,08-03 17:29:13.815 11585 11585 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-03 17:29:13.820 11585 11585 D AndroidRuntime: CheckJNI is OFF
,08-03 17:29:13.820 11585 11585 D AndroidRuntime: readGMSProperty: start
08-03 17:29:13.820 11585 11585 D AndroidRuntime: readGMSProperty: already setted!!
08-03 17:29:13.820 11585 11585 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-03 17:29:13.820 11585 11585 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-03 17:29:13.820 11585 11585 D AndroidRuntime: readGMSProperty: end
08-03 17:29:13.820 11585 11585 D AndroidRuntime: addProductProperty: start
,08-03 17:29:13.850 11585 11585 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-03 17:29:13.875 11585 11585 I Radio-JNI: register_android_hardware_Radio DONE
08-03 17:29:13.880 11585 11585 E AffinityControl: AffinityControl: registerfunction enter
08-03 17:29:13.895 11585 11585 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 17:29:13.900  3573  4718 D PackageManager: START PACKAGE DELETE: observer{114236423}
08-03 17:29:13.900  3573  4718 D PackageManager: pkg{<packageName>}
08-03 17:29:13.900  3573  4718 D PackageManager: user{0}
08-03 17:29:13.900  3573  4718 D PackageManager: caller{2000}
08-03 17:29:13.900  3573  4718 D PackageManager: flags{2}
08-03 17:29:13.900  3573  4718 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-03 17:29:13.900  3573  4718 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-03 17:29:13.900  3573  4718 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-03 17:29:13.900  3573  4718 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-03 17:29:13.900  3573  4718 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-03 17:29:13.900  3573  3879 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-03 17:29:13.900  3573  3879 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-03 17:29:13.900  3573  3879 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-03 17:29:13.900  3573  3879 D ApplicationPolicy: getApplicationUninstallationEnabled
08-03 17:29:13.900  3573  3879 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-03 17:29:13.900  3573  3879 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-03 17:29:13.900  3573  3879 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-03 17:29:13.900  3573  3879 D PackageManager: !@killApplicatoin: 10007, uninstall pkg
08-03 17:29:13.900  3573  3879 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-03 17:29:13.900  3573  3879 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-03 17:29:13.900  3573  3745 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=-1: uninstall pkg
08-03 17:29:13.900  3573  3745 I ActivityManager: Killing 11516:com.test.thalitest/u0a7 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-03 17:29:13.900  3573  3745 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-03 17:29:13.900  3573  3745 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-03 17:29:13.905  3573  3879 D AASAinstall: there is not AASApackages.xml file
,08-03 17:29:13.975  3573  5018 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5234134)
,08-03 17:29:13.975  3573  3595 D GraphicsStats: Buffer count: 4
08-03 17:29:13.975  3573  4453 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 17:29:13.975  3573  4453 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:13.975  3573  4453 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:14.015  3573  5791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-03 17:29:14.015  3573  5791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
08-03 17:29:14.015  3573  5791 D BatteryService: online:4, current avg:-16, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:-175
08-03 17:29:14.015  3573  5791 D BatteryService: stay LED for fully charged
08-03 17:29:14.015  3573  3573 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-03 17:29:14.020  3573  3573 I MotionRecognitionService: Plugged
08-03 17:29:14.020  3573  3573 D MotionRecognitionService:   cableConnection= 1
08-03 17:29:14.020  3573  3573 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-03 17:29:14.020  3573  3573 D MotionRecognitionService: skip setTransmitPower. 
,08-03 17:29:14.020  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-03 17:29:14.020  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-03 17:29:14.020  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-03 17:29:14.025  5724  5724 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-03 17:29:14.025  5724  6199 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-03 17:29:14.040  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-03 17:29:14.040  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-03 17:29:14.040  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-03 17:29:14.090  3573  3879 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-03 17:29:14.105  3573  3879 W PackageSettings: Skipping PackageSetting{753852b com.example.hello/10691} due to missing metadata
,08-03 17:29:14.165  3573  3879 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-03 17:29:14.165  2936  2936 W keystore: ENTER clear_uid from uid 1000 for 10007
,08-03 17:29:14.165  3573  3879 I art     : Starting a blocking GC Explicit
,08-03 17:29:14.255  3573  3879 I art     : Explicit concurrent mark sweep GC freed 153520(9MB) AllocSpace objects, 130(2MB) LOS objects, 33% free, 31MB/46MB, paused 1.175ms total 88.664ms
,08-03 17:29:14.270  3573  3879 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-03 17:29:14.270  3573  3879 D AASAuninstall: userId = 0, info.removedAppID = 10007, info.uid = 10007, packageName = com.test.thalitest
,08-03 17:29:14.270  3573  3879 D AASAinstall: there is not AASApackages.xml file
08-03 17:29:14.270  3573  3879 D PackageManager: result of delete: 1{114236423}
,08-03 17:29:14.270 11585 11585 I art     : System.exit called, status: 0
08-03 17:29:14.270 11585 11585 I AndroidRuntime: VM exiting with result code 0.
08-03 17:29:14.270  3573  3879 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-03 17:29:14.270  3573  3879 D PackageManager: userId{-1}
08-03 17:29:14.270  3573  3879 D PackageManager: andCode{true}
,08-03 17:29:14.280  3573  3879 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=0: pkg removed
,08-03 17:29:14.300 10351 11598 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-03 17:29:14.305 10351 11598 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-03 17:29:14.305 10351 11598 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-03 17:29:14.315  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-03 17:29:14.315  4512  4512 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-03 17:29:14.320  5677  5677 E SamsungIME: mOCRHelper is null
,08-03 17:29:14.320  3573  4416 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 17:29:14.320  5746  6072 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-03 17:29:14.330  3573  3745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa936fc u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f06072 7975:com.samsung.klmsagent/u0a21}
,08-03 17:29:14.330  7975  7975 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Wed Aug 03 17:29:14 GMT+02:00 2016
,08-03 17:29:14.330  3573  3729 D EnterpriseDeviceManagerService: Package has changed for user 0
08-03 17:29:14.330  3573  3729 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-03 17:29:14.330  3573  3729 W TextServicesManagerService: no available spell checker services found
,08-03 17:29:14.345  5102  5102 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-03 17:29:14.345  3573  5018 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-03 17:29:14.350  7975  7975 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-03 17:29:14.355  7975  7975 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-03 17:29:14.355  7975  7975 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-03 17:29:14.355  7975  7975 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-03 17:29:14.355  7975 11603 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-03 17:29:14.355  7975 11603 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-03 17:29:14.355  7975 11603 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-03 17:29:14.355  7975 11603 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-03 17:29:14.355  7975 11603 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-03 17:29:14.355  7975 11603 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-03 17:29:14.360  7975 11603 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-03 17:29:14.360  7975 11603 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-03 17:29:14.360  7975 11603 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-03 17:29:14.365  3573  4443 D NtpTrustedTime: currentTimeMillis() cache hit
08-03 17:29:14.365  3573  4443 V NetworkStats: removeUidsLocked() for UIDs [10007]
08-03 17:29:14.365  3573  4443 V NetworkStats: performPollLocked(flags=0x3)
,08-03 17:29:14.365  7975 11603 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-03 17:29:14.365  4696  4696 D Recents : onTaskStackChanged
,08-03 17:29:14.365  3573  4443 V NetworkStats: performPollLocked() took 4ms
08-03 17:29:14.365  3573  4443 D NtpTrustedTime: currentTimeMillis() cache hit
,08-03 17:29:14.370  3573  5825 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa936fc u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae69ae0 3573:system/1000}
,08-03 17:29:14.375  3573  4444 D NtpTrustedTime: currentTimeMillis() cache hit
,08-03 17:29:14.375  3573  4444 D NtpTrustedTime: currentTimeMillis() cache hit
08-03 17:29:14.375  7975 11603 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,08-03 17:29:14.380  3573  5791 D SettingsProvider: isChangeAllowed() SettingsProvider : name = klm_eula_shown
08-03 17:29:14.380  3573  5791 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-03 17:29:14.380  3573  5791 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-03 17:29:14.380  3573  5791 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-03 17:29:14.380  3573  5791 D SettingsProvider: selectionArgs: false
08-03 17:29:14.380  5090 11604 D RegisteredComponentCache: Collect Tech packages for Knox
08-03 17:29:14.380  3573  5791 D SettingsProvider: selectionArgs: 10021
08-03 17:29:14.380  3573  5791 D SettingsProvider: ret = -1
,08-03 17:29:14.380  7975 11603 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-03 17:29:14.380  7975 11603 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,08-03 17:29:14.425  7975 11603 D KLMS-2.6.032: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 317
08-03 17:29:14.430  7975 11603 D KLMS-2.6.032: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
,08-03 17:29:14.435  7975 11603 I KLMS-2.6.032: : KLMSSharedPreferences(): getNotificationAppList(): null
08-03 17:29:14.435  7975 11603 D KLMS-2.6.032: : Systemprocess(): Notification App List is Null. Remove Notification.
,08-03 17:29:14.435  7975 11603 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().START: com.test.thalitest
,08-03 17:29:14.440  7975 11603 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-03 17:29:14.440  7975 11603 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: #################################################################
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: #################################################################
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-03 17:29:14.440  7975 11603 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: #################################################################
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-03 17:29:14.440 , 7975 11603 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: #################################################################
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-03 17:29:14.440  7975 11603 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 17:29:14.440  3573  3729 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-03 17:29:14.440  7975 11603 W SQLiteOpenHelper: Opened klms.db in read-only mode
08-03 17:29:14.440  7975 11603 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
08-03 17:29:14.440  7975 11603 D KLMS-2.6.032: : Systemprocess(): PackageName is not Exist.
08-03 17:29:14.445  7975 11603 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().END
08-03 17:29:14.445  7975 11603 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().END
08-03 17:29:14.445  7975 11603 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().END
08-03 17:29:14.445  7975  7975 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
08-03 17:29:14.455  3573  3573 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
08-03 17:29:14.455  3573  3573 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-03 17:29:14.460  3573  3573 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-03 17:29:14.460  3573  3573 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-03 17:29:14.460  3573  3573 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-03 17:29:14.460  3573  3573 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-03 17:29:14.460  3573  3573 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10007 container id = 0
08-03 17:29:14.460  3573  3573 I OTPFW   : ProvisionData::getAllEntries Enter
08-03 17:29:14.460  3573  3573 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-03 17:29:14.460  3573  3573 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
08-03 17:29:14.475  3573  3729 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-03 17:29:14.475  5116  5116 E Launcher.Model: onPackageRemoved :com.test.thalitest
08-03 17:29:14.480  5116  5193 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-03 17:29:14.480  5116  5193 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-03 17:29:14.480  3573  3729 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
08-03 17:29:14.480  3573  3729 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-03 17:29:14.480  5116  5193 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 17:29:14.480  5116  5193 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 5116
08-03 17:29:14.480  5116  5193 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:489)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$4.run(LauncherModel.java:601)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:605)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:539)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:2472)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-03 17:29:14.480  5116  5193 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 17:29:14.490  3573  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
08-03 17:29:14.490  3573  4389 D UsbHostManager: displayNotification : [02h,02h,01h]
08-03 17:29:14.490  3573  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
08-03 17:29:14.490  3573  4389 D UsbHostManager: displayNotification : [0ah,00h,00h]
08-03 17:29:14.490  3573  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
08-03 17:29:14.490  3573  4389 D UsbHostManager: displayNotification : [02h,0dh,00h]
08-03 17:29:14.490  3573  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
08-03 17:29:14.490  3573  4389 D UsbHostManager: displayNotification : [0ah,00h,01h]
08-03 17:29:14.490  3573  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
08-03 17:29:14.490  3573  4389 D UsbHostManager: displayNotification : [09h,00h,00h]
08-03 17:29:14.490  3573  5123 W ActivityManager:   Force finishing activity com.sec.android.app.launcher/com.android.launcher2.Launcher
08-03 17:29:14.490  3573  4499 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
08-03 17:29:14.490  3573  4499 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
08-03 17:29:14.490  3573  4499 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: Can't write: system_app_crash
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop206.tmp: open failed: EROFS (Read-only file system)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:18019)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 17:29:14.490  3573 11611 E DropBoxManagerService: 	... 5 more
08-03 17:29:14.490  3573 11611 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop206.tmp
08-03 17:29:14.495  5116  5116 D Launcher: onTrimMemory. Level: 20
08-03 17:29:14.495  5116  5116 D MenuAppsGridFragment: onDestroyView
08-03 17:29:14.495  5116  5116 W Launcher.MenuAppsGrid: Trying to exit a state that hasn't been entered
08-03 17:29:14.500  5116  5116 D Launcher.HomeView: onDestroyView
08-03 17:29:14.500  5116  5116 D Launcher: onDestroy, Launcher: 143768032
08-03 17:29:14.500  4877  4877 D MtpClient: onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
08-03 17:29:14.500  4877  4877 D MtpClient: ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
08-03 17:29:14.500  5116  5193 I Process : Sending signal. PID: 5116 SIG: 9
08-03 17:29:14.500  5116  5116 D Launcher: onDetachedFromWindow
,08-03 17:29:14.545  3573  4499 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
08-03 17:29:14.545  3573  4499 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,08-03 17:29:14.570  3573  4416 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-03 17:29:14.615  3573  5825 I WindowState: WIN DEATH: Window{218c44c u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-03 17:29:14.620  2905  5400 I SurfaceFlinger: id=21 Removed Mauncher (4/10)
08-03 17:29:14.620  3573  3595 D GraphicsStats: Buffer count: 3
08-03 17:29:14.620  3573  4416 I EventHub: Removing device '/dev/input/event7' due to inotify event
08-03 17:29:14.625  2905  2981 I SurfaceFlinger: id=21 Removed Mauncher (-2/10)
,08-03 17:29:14.630  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbead0474
,08-03 17:29:14.645  3573  4416 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-03 17:29:14.665  3573  3596 I ActivityManager: Process com.sec.android.app.launcher (pid 5116)(adj 6) has died(214,1442)
,08-03 17:29:14.670  3573  3596 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.launcher, Auto Run ON
,08-03 17:29:14.680  3573  4416 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-03 17:29:14.710  3573  4416 I EventHub: Removing device '/dev/input/event11' due to inotify event
,08-03 17:29:14.735  3573  4416 I EventHub: Removing device '/dev/input/event12' due to inotify event
,08-03 17:29:14.795  3573  4416 I EventHub: Removing device '/dev/input/event13' due to inotify event
,08-03 17:29:14.830  3573  4416 I EventHub: Removing device '/dev/input/event14' due to inotify event

```
