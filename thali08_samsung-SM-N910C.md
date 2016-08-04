#### Test 794266502283b5d_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,08-04 11:16:06.627  3572  6959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-04 11:16:06.927  3572  6863 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:24), CUR = 123, LCD = 0
--------- beginning of main
08-04 11:16:07.377 11325 11325 I FIPS_bssl: FIPS approved mode (1) | 11325 | app_process
08-04 11:16:07.382 11325 11325 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 11:16:07.387 11325 11325 D AndroidRuntime: CheckJNI is OFF
08-04 11:16:07.387 11325 11325 D AndroidRuntime: readGMSProperty: start
08-04 11:16:07.387 11325 11325 D AndroidRuntime: readGMSProperty: already setted!!
08-04 11:16:07.387 11325 11325 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-04 11:16:07.387 11325 11325 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-04 11:16:07.387 11325 11325 D AndroidRuntime: readGMSProperty: end
08-04 11:16:07.387 11325 11325 D AndroidRuntime: addProductProperty: start
08-04 11:16:07.417 11325 11325 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 11:16:07.442 11325 11325 I Radio-JNI: register_android_hardware_Radio DONE
08-04 11:16:07.447 11325 11325 E AffinityControl: AffinityControl: registerfunction enter
08-04 11:16:07.462 11325 11325 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 11:16:07.472  3572  7301 D GameManagerService: identifyGamePackage. com.test.thalitest
08-04 11:16:07.472  3572  7301 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-04 11:16:07.477  3572  7301 D ActivityManager: mDVFSHelper.acquire()
08-04 11:16:07.477  3572  7301 V WindowManager: addAppToken: AppWindowToken{5b8180e token=Token{24bfe09 ActivityRecord{9262310 u0 com.test.thalitest/.MainActivity t108}}} to stack=1 task=108 at 0
08-04 11:16:07.477  3572  3808 D SecWifiDisplayUtil: Metadata value : none
08-04 11:16:07.477  3572  3808 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ce31ae6 V.E...... R.....ID 0,0-0,0}
08-04 11:16:07.482  3572  3808 D ISSUE_DEBUG: InputChannelName : cbc7ad4 Starting com.test.thalitest
08-04 11:16:07.487 11341 11341 E Zygote  : v2
08-04 11:16:07.487 11341 11341 I libpersona: KNOX_SDCARD checking this for 10007
08-04 11:16:07.487 11341 11341 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
08-04 11:16:07.487 11341 11341 I libpersona: KNOX_SDCARD not a persona
08-04 11:16:07.487 11341 11341 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:07.487  3572  7301 I ActivityManager: Start proc 11341:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
08-04 11:16:07.487  3572  7301 D InputDispatcher: Focused application set to: xxxx
08-04 11:16:07.487 11341 11341 E Zygote  : accessInfo : 0
08-04 11:16:07.487 11341 11341 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-04 11:16:07.487  3572  7301 D InputDispatcher: Focus left window: 7747
08-04 11:16:07.487 11325 11325 D AndroidRuntime: Shutting down VM
08-04 11:16:07.487  3572  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-04 11:16:07.487  3572  3736 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{96d9c6 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-04 11:16:07.487  4507  4507 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-04 11:16:07.497  2906  2906 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-04 11:16:07.507 11341 11341 D TimaKeyStoreProvider: TimaSignature is unavailable
08-04 11:16:07.507 11341 11341 D ActivityThread: Added TimaKeyStore provider
08-04 11:16:07.517  3572  5127 V WindowOrientationListener: setCurrentAppOrientation :-1
08-04 11:16:07.517  3572  5127 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-04 11:16:07.517  3572  3808 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3572 uid:1000
08-04 11:16:07.517  3572  3808 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:16:07.517  3572  3808 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3572 uid:1000
08-04 11:16:07.517  3572  3808 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 11:16:07.517  3572  3808 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-04 11:16:07.517  3572  3736 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{cbc7ad4 u0 d0 Starting com.test.thalitest}
08-04 11:16:07.517  4507  4507 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-04 11:16:07.517  3572  5127 D ActivityManager:  Launching com.test.thalitest, updated priority
08-04 11:16:07.527  3572  3572 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-04 11:16:07.527  3572  3732 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-04 11:16:07.542  2906  5186 I SurfaceFlinger: id=18 Removed VSBConnecti (5/11)
08-04 11:16:07.542  2906  2991 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
08-04 11:16:07.547  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeae6474
08-04 11:16:07.547  2906  2991 D libEGL  : eglTerminate EGLDisplay = 0xb65ff624
08-04 11:16:07.547  2906  2991 D libEGL  : eglTerminate EGLDisplay = 0xb65ff624
08-04 11:16:07.547  2906  2988 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
08-04 11:16:07.547  2906 10065 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
08-04 11:16:07.552  5110  5110 V ActivityThread: updateVisibility : ActivityRecord{875909e token=android.os.BinderProxy@d00972d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-04 11:16:07.552  5110  5110 D Launcher: onTrimMemory. Level: 20
08-04 11:16:07.552  2906  5186 D libEGL  : eglTerminate EGLDisplay = 0xb1b25624
08-04 11:16:07.557  2906  2988 I SurfaceFlinger: id=17 Removed VSBConnecti (5/9)
08-04 11:16:07.557  2906 10065 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/9)
08-04 11:16:07.557  7747  7747 V ActivityThread: updateVisibility : ActivityRecord{a9ba73 token=android.os.BinderProxy@6908294 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-04 11:16:07.562  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeae6474
08-04 11:16:07.562  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeae6474
08-04 11:16:07.567  3572  3808 V WindowStateAnimator: Finishing drawing window Window{cbc7ad4 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-04 11:16:07.582  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeae640c
,08-04 11:16:07.827  3572  5127 I WindowManager: Screenshot max retries 4 of Token{24bfe09 ActivityRecord{9262310 u0 com.test.thalitest/.MainActivity t108}} appWin=Window{cbc7ad4 u0 d0 Starting com.test.thalitest} drawState=2
,08-04 11:16:07.832  3572  3732 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,08-04 11:16:07.842  3572  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-04 11:16:07.862  3572  6863 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:07.872  3572  6863 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:07.917 11341 11341 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-04 11:16:07.952 11341 11341 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-04 11:16:07.962 11341 11341 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 4503-4505)
08-04 11:16:07.962 11341 11341 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-04 11:16:07.977 11341 11355 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-04 11:16:07.982 11341 11341 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c67677b}
08-04 11:16:07.982 11341 11341 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-04 11:16:07.982 11341 11341 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 11:16:07.992 11341 11341 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-04 11:16:08.032 11341 11341 D libEGL  : eglInitialize EGLDisplay = 0xbe91ce7c
,08-04 11:16:08.062  3572  4700 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,08-04 11:16:08.062  3572  4700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-04 11:16:08.127 11341 11341 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-04 11:16:08.142 11341 11341 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-04 11:16:08.142 11341 11341 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-04 11:16:08.142 11341 11341 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-04 11:16:08.142 11341 11341 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-04 11:16:08.162 11341 11341 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-04 11:16:08.172 11341 11341 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-04 11:16:08.272 11341 11341 D SecWifiDisplayUtil: Metadata value : none
,08-04 11:16:08.277 11341 11341 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a08e3f8 I.E...... R.....ID 0,0-0,0}
,08-04 11:16:08.292 11341 11392 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-04 11:16:08.307  3572  5127 D ISSUE_DEBUG: InputChannelName : 4ed9821 com.test.thalitest/com.test.thalitest.MainActivity
,08-04 11:16:08.317  3572  3595 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-04 11:16:08.317  3572  3595 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-04 11:16:08.317  3572  3572 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-04 11:16:08.327  3572  3572 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-04 11:16:08.367 11341 11341 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 11341
,08-04 11:16:08.372  3572  5127 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/11341 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:16:08.372  3572  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-04 11:16:08.372  3572  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-04 11:16:08.372  3572  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-04 11:16:08.372  3572  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:08.372  3572  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:08.372  3572  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-04 11:16:08.372  3572  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:08.372  3572  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-04 11:16:08.372  3572  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-04 11:16:08.372  3572  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:16:08.377 11341 11355 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-04 11:16:08.392 11341 11341 D SecWifiDisplayUtil: Metadata value : none
,08-04 11:16:08.402  2906  2906 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-04 11:16:08.417  3572  5124 D InputDispatcher: Focus entered window: 11341
,08-04 11:16:08.422  3572  3808 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3572 uid:1000
08-04 11:16:08.422  3572  3808 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-04 11:16:08.422  3572  3808 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3572 uid:1000
08-04 11:16:08.422  3572  3808 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 11:16:08.422 11341 11392 D libEGL  : eglInitialize EGLDisplay = 0x9ce3f7c4
08-04 11:16:08.422 11341 11392 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 11:16:08.427 11341 11392 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-04 11:16:08.432 11341 11341 V ActivityThread: updateVisibility : ActivityRecord{d1b3ed3 token=android.os.BinderProxy@9763f5b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-04 11:16:08.437 11341 11341 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView),
,08-04 11:16:08.502 11341 11397 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 11:16:08.502 11341 11397 D libEGL  : eglInitialize EGLDisplay = 0x9b1ff3ec
,08-04 11:16:08.512  3572  7301 V WindowStateAnimator: Finishing drawing window Window{4ed9821 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-04 11:16:08.512 11341 11341 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,08-04 11:16:08.517 11341 11341 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-04 11:16:08.517  3572  4890 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-04 11:16:08.517  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeae640c
,08-04 11:16:08.517  3572  3808 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-04 11:16:08.517  3572  3572 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-04 11:16:08.522  3572  3808 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +689ms (total +1s44ms)
,08-04 11:16:08.522  3572  3572 I KnoxTimeoutHandler: SD activityfalse
,08-04 11:16:08.532  3572  3808 D ActivityManager: mDVFSHelper.release()
08-04 11:16:08.532  3572  3808 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9262310 u0 com.test.thalitest/.MainActivity t108} time:335075
,08-04 11:16:08.532  3572  3808 D ViewRootImpl: #3 mView = null
,08-04 11:16:08.532  2906  2991 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
,08-04 11:16:08.532  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeae645c
,08-04 11:16:08.537 11341 11341 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-04 11:16:08.552  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeae640c
,08-04 11:16:08.552  3572  7301 V WindowStateAnimator: Finishing drawing window Window{4ed9821 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-04 11:16:08.552 11341 11341 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9763f5b time:335098
,08-04 11:16:08.567 11341 11341 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11341
,08-04 11:16:08.747 11341 11341 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 11:16:08.922 11341 11405 D jxcore_app_log: JniHelper::setJavaVM(0xb4874000), pthread_self() = -1731200720
,08-04 11:16:08.927 11341 11405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 11:16:08.927 11341 11405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 11:16:08.927 11341 11405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 11:16:08.927 11341 11405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 11:16:08.927 11341 11405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 11:16:08.927 11341 11405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1949041 added. We now have 1 listener(s)
,08-04 11:16:08.927 11341 11405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
08-04 11:16:08.927 11341 11405 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
08-04 11:16:08.927 11341 11405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:16:08.927 11341 11405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 11:16:08.932 11341 11405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebae1d4 added. We now have 1 listener(s)
08-04 11:16:08.932 11341 11405 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:16:08.932 11341 11405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:16:08.932 11341 11405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 11:16:08.932 11341 11405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 11:16:08.932 11341 11405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 11:16:08.932 11341 11405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 11:16:08.937 11341 11405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:16:08.937 11341 11405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,08-04 11:16:08.942 11341 11405 D BluetoothAdapter: STATE_ON
,08-04 11:16:08.942 11341 11405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:16:08.942 11341 11405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:16:08.942 11341 11405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 11:16:08.942 11341 11405 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:16:08.942 11341 11405 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 11:16:08.947 11341 11341 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:16:08.947 11341 11341 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:16:08.972 11341 11341 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 11:16:09.332  4695  4695 D Recents : onTaskStackChanged
,08-04 11:16:09.362 11341 11406 W jxcore-log: Initializing JXcore engine
08-04 11:16:09.362 11341 11406 W jxcore-log: JXcore engine is ready
,08-04 11:16:09.387  5745  5745 E audit   : type=1400 msg=audit(1470302169.387:266): avc:  denied  { ioctl } for  pid=11406 comm="Thread-1127" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2200 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
08-04 11:16:09.387  5745  5745 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:09.387  5745  5745 E audit   : type=1300 msg=audit(1470302169.387:266): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=969083c8 items=0 ppid=2964 ppcomm=main pid=11406 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1127" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-04 11:16:09.387  5745  5745 E audit   : type=1327 msg=audit(1470302169.387:266): proctitle="com.test.thalitest"
08-04 11:16:09.387  5745  5745 E audit   : type=1320 msg=audit(1470302169.387:266): 
08-04 11:16:09.387  5745  5745 E audit   : type=1400 msg=audit(1470302169.387:267): avc:  denied  { ioctl } for  pid=11406 comm="Thread-1127" path="socket:[41176]" dev="sockfs" ino=41176 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-04 11:16:09.387  5745  5745 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-04 11:16:09.387  5745  5745 E audit   : type=1300 msg=audit(1470302169.387:267): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=969083c8 items=0 ppid=2964 ppcomm=main pid=11406 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1127" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-04 11:16:09.387  5745  5745 E audit   : type=1327 msg=audit(1470302169.387:267): proctitle="com.test.thalitest"
08-04 11:16:09.387  5745  5745 E audit   : type=1320 msg=audit(1470302169.387:267): 
,08-04 11:16:09.397 11341 11406 W jxcore-log: Starting JXcore engine
,08-04 11:16:09.447 11341 11406 W jxcore-log: Platform android
08-04 11:16:09.447 11341 11406 W jxcore-log: 
08-04 11:16:09.447 11341 11406 W jxcore-log: Process ARCH arm
08-04 11:16:09.447 11341 11406 W jxcore-log: 
,08-04 11:16:09.552 11341 11406 I jxcore-log: JXcore Cordova bridge is ready!
08-04 11:16:09.552 11341 11406 I jxcore-log: 
,08-04 11:16:09.552 11341 11406 W jxcore-log: JXcore engine is started
,08-04 11:16:09.552 11341 11405 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 11:16:09.552 11341 11341 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 11:16:09.892  2915  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-04 11:16:09.892  2915  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
08-04 11:16:10.292  3572  7303 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-04 11:16:10.292  3572  7303 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
08-04 11:16:10.292  3572  7303 D BatteryService: online:4, current avg:-15, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:-196
08-04 11:16:10.292  3572  7303 D BatteryService: stay LED for fully charged
08-04 11:16:10.292  3572  3572 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-04 11:16:10.292  3572  3572 I MotionRecognitionService: Plugged
08-04 11:16:10.292  3572  3572 D MotionRecognitionService:   cableConnection= 1
08-04 11:16:10.292  3572  3572 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-04 11:16:10.292  3572  3572 D MotionRecognitionService: skip setTransmitPower. 
08-04 11:16:10.292  4507  4507 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-04 11:16:10.292  4507  4507 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-04 11:16:10.292  4507  4507 D KeyguardUpdateMonitor: handleBatteryUpdate
08-04 11:16:10.297  5723  5723 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 11:16:10.297  5723  6164 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 11:16:10.297  4507  4507 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:16:10.297  4507  4507 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:16:10.297  4507  4507 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:16:10.487  3572  4497 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/108_task.xml.bak
,08-04 11:16:13.882  3572  6863 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:16.932  3572  6863 D SSRM:n  : SIOP:: AP = 300, PST = 278 (W:18), CUR = -15, LCD = 0
,08-04 11:16:17.527  3572  3876 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-04 11:16:17.547  3572  3876 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-04 11:16:17.647 11341 11406 E jxcore  : Error!: Cannot find module '../thalilogger'
08-04 11:16:17.647 11341 11406 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-04 11:16:17.652 11341 11341 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
08-04 11:16:17.652 11341 11341 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-04 11:16:17.657  3572  7305 D InputDispatcher: Focused application set to: xxxx
08-04 11:16:17.662  3572  7305 I ActivityManager: Killing 10438:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): DHA:empty #31
,08-04 11:16:17.662 11341 11341 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 11:16:17.667 11341 11341 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-04 11:16:17.667 11341 11341 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:16:17.667 11341 11341 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:16:17.667 11341 11341 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:16:17.667 11341 11341 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:16:17.667 11341 11341 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1949041 removed from the list
08-04 11:16:17.667 11341 11341 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:16:17.667 11341 11341 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebae1d4 removed from the list
08-04 11:16:17.667 11341 11341 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:16:17.667 11341 11341 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-04 11:16:17.667 11341 11341 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 11:16:17.667 11341 11341 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-04 11:16:17.672  3572  6863 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:17.677  3572  6863 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-04 11:16:17.682  2906  2991 D libEGL  : eglTerminate EGLDisplay = 0xb65ff624
,08-04 11:16:17.682 11341 11341 D ViewRootImpl: #3 mView = null
08-04 11:16:17.682  2906 10065 I SurfaceFlinger: id=20 Removed NainActivit (6/8)
,08-04 11:16:17.682  2906  2988 I SurfaceFlinger: id=20 Removed NainActivit (-2/8)
,08-04 11:16:17.682  3572  5127 D InputDispatcher: Focus left window: 11341
,08-04 11:16:17.687  3572  3808 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3572 uid:1000
08-04 11:16:17.687  3572  3808 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:16:17.687  3572  3808 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3572 uid:1000
08-04 11:16:17.687  3572  3808 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 11:16:17.687 11341 11341 D cr_Ime  : [ImeAdapter.java:587] detach
,08-04 11:16:17.687 11341 11341 E ViewRootImpl: sendUserActionEvent() mView == null
,08-04 11:16:17.692  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeae6474
,08-04 11:16:17.692  3572  5125 D ActivityManager: mDVFSHelper.acquire()
,08-04 11:16:17.702  3572  3572 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
08-04 11:16:17.702  3572  3732 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-04 11:16:17.707  3572  5125 V WindowOrientationListener: setCurrentAppOrientation :1
08-04 11:16:17.707  3572  5125 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-04 11:16:17.712  3572  4550 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,08-04 11:16:17.717  3572  3732 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,08-04 11:16:17.717  2906  2906 I SurfaceFlinger: id=21 createSurf (1528x2333),1 flag=4, VSBConnecti
,08-04 11:16:17.722  3572  3736 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d334e99 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-04 11:16:17.722  4507  4507 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-04 11:16:17.722  3572  4548 D InputDispatcher: Focus entered window: 7747
,08-04 11:16:17.722  7747 10213 D mali_winsys: new_window_surface returns 0x3000,  [1528x2333]-format:1
,08-04 11:16:17.722  3572  3808 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3572 uid:1000
08-04 11:16:17.722  3572  3808 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-04 11:16:17.722  3572  3808 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3572 uid:1000
08-04 11:16:17.727  3572  3808 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 11:16:17.727  3572  5035 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-04 11:16:17.727  3572  5035 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-04 11:16:17.727  3572  3572 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:17.727  5110  5110 D Launcher: onRestart, Launcher: 259815721
08-04 11:16:17.727  3572  3572 I KnoxTimeoutHandler: Shared devices show user statefalse
08-04 11:16:17.727  3572  3572 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-04 11:16:17.727  5110  5110 D Launcher: onStart, Launcher: 259815721
08-04 11:16:17.727  5110  5110 D Launcher.HomeView: onStart
,08-04 11:16:17.727  5110  5110 V ActivityThread: updateVisibility : ActivityRecord{875909e token=android.os.BinderProxy@d00972d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-04 11:16:17.742  2906  2906 I SurfaceFlinger: id=22 createSurf (1440x2560),1 flag=4, Mauncher
,08-04 11:16:17.742  3572  3736 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d334e99 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-04 11:16:17.747  4507  4507 D PhoneStatusBar: setSystemUiVisibility vis=40008000 mask=ffffffff oldVal=8000 newVal=40008000 diff=40000000
,08-04 11:16:17.747  5110  5435 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
08-04 11:16:17.747  3572  5125 V WindowStateAnimator: Finishing drawing window Window{d334e99 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-04 11:16:17.752  2906  2906 I SurfaceFlinger: id=23 createSurf (1592x384),1 flag=4, VSBConnecti
,08-04 11:16:17.752  3572  3808 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:17.752  3572  3572 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-04 11:16:17.757  3572  3808 D ActivityManager: mDVFSHelper.release()
08-04 11:16:17.757  3572  3808 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{79db46b u0 com.samsung.android.MtpApplication/.USBConnection t107} time:344300
,08-04 11:16:17.757  7747 10213 D mali_winsys: new_window_surface returns 0x3000,  [1592x384]-format:1
,08-04 11:16:17.757  3572  3572 I KnoxTimeoutHandler: SD activityfalse
,08-04 11:16:17.757  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeae640c
,08-04 11:16:17.757  7747  7747 V ActivityThread: updateVisibility : ActivityRecord{a9ba73 token=android.os.BinderProxy@6908294 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-04 11:16:17.782  3572  7303 V WindowStateAnimator: Finishing drawing window Window{a015d3f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-04 11:16:17.782  7747  7747 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6908294 time:344326
,08-04 11:16:17.787  3572  3808 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-04 11:16:17.787  3572  3572 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-04 11:16:17.787  3572  3572 I KnoxTimeoutHandler: SD activityfalse
,08-04 11:16:17.792  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeae640c
,08-04 11:16:17.822  3572  3595 V WindowStateAnimator: Finishing drawing window Window{96d9c6 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-04 11:16:17.822  5110  5110 D Launcher.HomeView: onStop
,08-04 11:16:17.827  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeae640c
,08-04 11:16:17.827  3572  3808 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-04 11:16:17.827  3572  3572 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-04 11:16:17.827  3572  3808 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4b27cce u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t106} time:344371
08-04 11:16:17.827  3572  3572 I KnoxTimeoutHandler: SD activityfalse
,08-04 11:16:18.177 11410 11410 I FIPS_bssl: FIPS approved mode (1) | 11410 | app_process
,08-04 11:16:18.187 11410 11410 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 11:16:18.187 11410 11410 D AndroidRuntime: CheckJNI is OFF
,08-04 11:16:18.192 11410 11410 D AndroidRuntime: readGMSProperty: start
08-04 11:16:18.192 11410 11410 D AndroidRuntime: readGMSProperty: already setted!!
08-04 11:16:18.192 11410 11410 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-04 11:16:18.192 11410 11410 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-04 11:16:18.192 11410 11410 D AndroidRuntime: readGMSProperty: end
08-04 11:16:18.192 11410 11410 D AndroidRuntime: addProductProperty: start
,08-04 11:16:18.217 11410 11410 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 11:16:18.247 11410 11410 I Radio-JNI: register_android_hardware_Radio DONE
,08-04 11:16:18.252 11410 11410 E AffinityControl: AffinityControl: registerfunction enter
,08-04 11:16:18.267 11410 11410 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 11:16:18.272  3572  5126 D PackageManager: START PACKAGE DELETE: observer{82349083}
08-04 11:16:18.272  3572  5126 D PackageManager: pkg{<packageName>}
08-04 11:16:18.272  3572  5126 D PackageManager: user{0}
08-04 11:16:18.272  3572  5126 D PackageManager: caller{2000}
08-04 11:16:18.272  3572  5126 D PackageManager: flags{2}
08-04 11:16:18.272  3572  5126 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-04 11:16:18.272  3572  5126 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-04 11:16:18.272  3572  5126 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-04 11:16:18.272  3572  5126 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-04 11:16:18.272  3572  5126 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-04 11:16:18.272  3572  3876 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-04 11:16:18.272  3572  3876 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-04 11:16:18.272  3572  3876 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-04 11:16:18.272  3572  3876 D ApplicationPolicy: getApplicationUninstallationEnabled
08-04 11:16:18.272  3572  3876 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-04 11:16:18.272  3572  3876 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-04 11:16:18.272  3572  3876 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-04 11:16:18.272  3572  3876 D PackageManager: !@killApplicatoin: 10007, uninstall pkg
08-04 11:16:18.272  3572  3876 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-04 11:16:18.272  3572  3876 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-04 11:16:18.272  3572  3732 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=-1: uninstall pkg
08-04 11:16:18.272  3572  3732 I ActivityManager: Killing 11341:com.test.thalitest/u0a7 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-04 11:16:18.272  3572  3732 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 11:16:18.272  3572  3732 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-04 11:16:18.282  3572  3876 D AASAinstall: there is not AASApackages.xml file
,08-04 11:16:18.372  3572  3595 D GraphicsStats: Buffer count: 4
08-04 11:16:18.372  3572  7303 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@99611b8)
,08-04 11:16:18.372  3572  4453 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:16:18.372  3572  4453 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:16:18.372  3572  4453 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:16:18.442  3572  3876 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-04 11:16:18.457  3572  3876 W PackageSettings: Skipping PackageSetting{4e405b1 com.example.hello/10691} due to missing metadata
,08-04 11:16:18.497  3572  3876 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-04 11:16:18.497  2937  2937 W keystore: ENTER clear_uid from uid 1000 for 10007
,08-04 11:16:18.497  3572  3876 I art     : Starting a blocking GC Explicit
,08-04 11:16:18.582  3572  3876 I art     : Explicit concurrent mark sweep GC freed 137954(8MB) AllocSpace objects, 121(2MB) LOS objects, 33% free, 31MB/46MB, paused 1.188ms total 85.553ms
,08-04 11:16:18.592  3572  3876 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-04 11:16:18.592  3572  3876 D AASAuninstall: userId = 0, info.removedAppID = 10007, info.uid = 10007, packageName = com.test.thalitest
,08-04 11:16:18.592  3572  3876 D AASAinstall: there is not AASApackages.xml file
08-04 11:16:18.592  3572  3876 D PackageManager: result of delete: 1{82349083}
,08-04 11:16:18.597  3572  3876 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-04 11:16:18.597  3572  3876 D PackageManager: userId{-1}
08-04 11:16:18.597  3572  3876 D PackageManager: andCode{true}
08-04 11:16:18.597 11410 11410 I art     : System.exit called, status: 0
08-04 11:16:18.597 11410 11410 I AndroidRuntime: VM exiting with result code 0.
,08-04 11:16:18.602  3572  3876 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=0: pkg removed
,08-04 11:16:18.617 10320 11421 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-04 11:16:18.627 10320 11421 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-04 11:16:18.632 10320 11421 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-04 11:16:18.637  4507  4507 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-04 11:16:18.637  4507  4507 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-04 11:16:18.642  5660  5660 E SamsungIME: mOCRHelper is null
,08-04 11:16:18.642  5733  6043 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 11:16:18.642  3572  4416 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 11:16:18.647  3572  4443 V NetworkStats: removeUidsLocked() for UIDs [10007]
08-04 11:16:18.647  3572  4443 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:16:18.647  3572  4443 V NetworkStats: performPollLocked(flags=0x3)
,08-04 11:16:18.652  3572  3732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8ceb85 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bd7017 7864:com.samsung.klmsagent/u0a21}
,08-04 11:16:18.657  3572  4443 V NetworkStats: performPollLocked() took 7ms
08-04 11:16:18.657  3572  4443 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:16:18.657  7864  7864 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Thu Aug 04 11:16:18 GMT+02:00 2016
,08-04 11:16:18.662  3572  3719 D EnterpriseDeviceManagerService: Package has changed for user 0
08-04 11:16:18.662  3572  3719 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-04 11:16:18.662  3572  3719 W TextServicesManagerService: no available spell checker services found
,08-04 11:16:18.667  3572  5125 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-04 11:16:18.672  7864  7864 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-04 11:16:18.677  7864  7864 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-04 11:16:18.677  5098  5098 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-04 11:16:18.677  7864  7864 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 11:16:18.677  3572  4548 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8ceb85 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ce4dae 3572:system/1000}
,08-04 11:16:18.677  7864  7864 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-04 11:16:18.677  7864 11423 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-04 11:16:18.677  7864 11423 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-04 11:16:18.677  7864 11423 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-04 11:16:18.677  7864 11423 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-04 11:16:18.677  7864 11423 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-04 11:16:18.682  7864 11423 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-04 11:16:18.682  3572  4444 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:16:18.682  3572  4444 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:16:18.682  7864 11423 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 11:16:18.687  7864 11423 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-04 11:16:18.697  7864 11423 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-04 11:16:18.697  5086 11426 D RegisteredComponentCache: Collect Tech packages for Knox
,08-04 11:16:18.697  7864 11423 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-04 11:16:18.702  7864 11423 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,08-04 11:16:18.707  3572  4700 D SettingsProvider: isChangeAllowed() SettingsProvider : name = klm_eula_shown
08-04 11:16:18.707  3572  4700 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:16:18.707  3572  4700 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:16:18.707  3572  4700 D SettingsProvider: selectionArgs: false
08-04 11:16:18.707  3572  4700 D SettingsProvider: selectionArgs: 10021
08-04 11:16:18.707  3572  4700 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-04 11:16:18.707  3572  4700 D SettingsProvider: ret = -1
08-04 11:16:18.707  7864 11423 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-04 11:16:18.707  7864 11423 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,08-04 11:16:18.727  4695  4695 D Recents : onTaskStackChanged
,08-04 11:16:18.747  7864 11423 D KLMS-2.6.032: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 317
08-04 11:16:18.747  7864 11423 D KLMS-2.6.032: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
,08-04 11:16:18.747  7864 11423 I KLMS-2.6.032: : KLMSSharedPreferences(): getNotificationAppList(): null
08-04 11:16:18.747  7864 11423 D KLMS-2.6.032: : Systemprocess(): Notification App List is Null. Remove Notification.
08-04 11:16:18.747  7864 11423 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().START: com.test.thalitest
,08-04 11:16:18.752  7864 11423 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-04 11:16:18.752  7864 11423 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: #################################################################
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: #################################################################
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-04 11:16:18.752  7864 11423 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: #################################################################
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-04 11:16:18.757 , 7864 11423 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: #################################################################
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-04 11:16:18.757  7864 11423 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:16:18.757  7864 11423 W SQLiteOpenHelper: Opened klms.db in read-only mode
08-04 11:16:18.757  7864 11423 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
08-04 11:16:18.757  7864 11423 D KLMS-2.6.032: : Systemprocess(): PackageName is not Exist.
08-04 11:16:18.757  7864 11423 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().END
08-04 11:16:18.757  7864 11423 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().END
08-04 11:16:18.757  7864 11423 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().END
08-04 11:16:18.757  7864  7864 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
08-04 11:16:18.772  3572  3719 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-04 11:16:18.787  3572  3572 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
08-04 11:16:18.787  3572  3572 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-04 11:16:18.787  3572  3572 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-04 11:16:18.787  3572  3572 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-04 11:16:18.787  3572  3572 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-04 11:16:18.787  3572  3572 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-04 11:16:18.787  3572  3572 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10007 container id = 0
08-04 11:16:18.787  3572  3572 I OTPFW   : ProvisionData::getAllEntries Enter
,08-04 11:16:18.792  3572  3572 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-04 11:16:18.797  3572  3572 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
08-04 11:16:18.797  3572  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
08-04 11:16:18.797  3572  4389 D UsbHostManager: displayNotification : [02h,02h,01h]
08-04 11:16:18.797  3572  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
08-04 11:16:18.797  3572  4389 D UsbHostManager: displayNotification : [0ah,00h,00h]
08-04 11:16:18.802  3572  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
08-04 11:16:18.802  3572  4389 D UsbHostManager: displayNotification : [02h,0dh,00h]
08-04 11:16:18.802  3572  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
08-04 11:16:18.802  3572  4389 D UsbHostManager: displayNotification : [0ah,00h,01h]
08-04 11:16:18.802  3572  4389 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
08-04 11:16:18.802  3572  4389 D UsbHostManager: displayNotification : [09h,00h,00h]
08-04 11:16:18.802  3572  4498 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
08-04 11:16:18.802  3572  4498 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
08-04 11:16:18.802  3572  4498 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
08-04 11:16:18.802  4904  4904 D MtpClient: onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
08-04 11:16:18.802  4904  4904 D MtpClient: ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
08-04 11:16:18.807  3572  3719 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-04 11:16:18.807  5110  5110 E Launcher.Model: onPackageRemoved :com.test.thalitest
08-04 11:16:18.812  5110  5191 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-04 11:16:18.812  5110  5191 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-04 11:16:18.812  3572  3719 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
08-04 11:16:18.812  3572  3719 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-04 11:16:18.812  5110  5191 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-04 11:16:18.812  5110  5191 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 5110
08-04 11:16:18.812  5110  5191 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:489)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$4.run(LauncherModel.java:601)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:605)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:539)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:2472)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-04 11:16:18.812  5110  5191 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:16:18.822  3572  7303 W ActivityManager:   Force finishing activity com.sec.android.app.launcher/com.android.launcher2.Launcher
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop206.tmp: open failed: EROFS (Read-only file system)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:18019)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 11:16:18.822  3572 11433 E DropBoxManagerService: 	... 5 more
08-04 11:16:18.822  3572 11433 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop206.tmp
08-04 11:16:18.827  5110  5110 D Launcher: onTrimMemory. Level: 20
08-04 11:16:18.827  5110  5110 D MenuAppsGridFragment: onDestroyView
08-04 11:16:18.827  5110  5110 W Launcher.MenuAppsGrid: Trying to exit a state that hasn't been entered
08-04 11:16:18.832  5110  5110 D Launcher.HomeView: onDestroyView
08-04 11:16:18.832  5110  5110 D Launcher: onDestroy, Launcher: 259815721
08-04 11:16:18.832  5110  5191 I Process : Sending signal. PID: 5110 SIG: 9
,08-04 11:16:18.857  3572  4498 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
08-04 11:16:18.857  3572  4498 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,08-04 11:16:18.887  3572  4416 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-04 11:16:18.907  3572  4416 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-04 11:16:18.912  3572  5124 D GraphicsStats: Buffer count: 3,
,08-04 11:16:18.917  3572  4700 I WindowState: WIN DEATH: Window{96d9c6 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-04 11:16:18.922  2906  2988 I SurfaceFlinger: id=22 Removed Mauncher (4/10),
,08-04 11:16:18.932  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeae6474
08-04 11:16:18.942  3572  4416 I EventHub: Removing device '/dev/input/event8' due to inotify event
08-04 11:16:18.962  3572  5035 I ActivityManager: Process com.sec.android.app.launcher (pid 5110)(adj 6) has died(283,1404)
,08-04 11:16:18.972  3572  5035 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.launcher, Auto Run ON
,08-04 11:16:18.982  3572  4416 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-04 11:16:19.052  3572  4416 I EventHub: Removing device '/dev/input/event11' due to inotify event
,08-04 11:16:19.102  3572  4416 I EventHub: Removing device '/dev/input/event12' due to inotify event
,08-04 11:16:19.107  3572  4967 E Watchdog: !@Sync 11 [08-04 11:16:19.105]
,08-04 11:16:19.132  3572  4416 I EventHub: Removing device '/dev/input/event13' due to inotify event
,08-04 11:16:19.162  3572  4416 I EventHub: Removing device '/dev/input/event14' due to inotify event

```
