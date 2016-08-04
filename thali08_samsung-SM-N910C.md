#### Test 79426650eeb77ae_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
08-05 01:32:29.720  3569  7024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 01:32:30.095  3569  6895 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:24), CUR = 124, LCD = 0
--------- beginning of main
08-05 01:32:30.445 11436 11436 I FIPS_bssl: FIPS approved mode (1) | 11436 | app_process
08-05 01:32:30.455 11436 11436 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 01:32:30.455 11436 11436 D AndroidRuntime: CheckJNI is OFF
08-05 01:32:30.455 11436 11436 D AndroidRuntime: readGMSProperty: start
08-05 01:32:30.455 11436 11436 D AndroidRuntime: readGMSProperty: already setted!!
08-05 01:32:30.455 11436 11436 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 01:32:30.455 11436 11436 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 01:32:30.455 11436 11436 D AndroidRuntime: readGMSProperty: end
08-05 01:32:30.455 11436 11436 D AndroidRuntime: addProductProperty: start
08-05 01:32:30.485 11436 11436 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 01:32:30.515 11436 11436 I Radio-JNI: register_android_hardware_Radio DONE
08-05 01:32:30.520 11436 11436 E AffinityControl: AffinityControl: registerfunction enter
08-05 01:32:30.535 11436 11436 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 01:32:30.585  3569  5139 D GameManagerService: identifyGamePackage. com.test.thalitest
08-05 01:32:30.585  3569  5139 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-05 01:32:30.590  3569  5139 D ActivityManager: mDVFSHelper.acquire()
08-05 01:32:30.590  3569  5139 V WindowManager: addAppToken: AppWindowToken{c085f9e token=Token{8b969d9 ActivityRecord{d999c20 u0 com.test.thalitest/.MainActivity t108}}} to stack=1 task=108 at 0
08-05 01:32:30.605  3569  3812 D SecWifiDisplayUtil: Metadata value : none
08-05 01:32:30.605  3569  3812 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2e2c476 V.E...... R.....ID 0,0-0,0}
08-05 01:32:30.610  3569  3812 D ISSUE_DEBUG: InputChannelName : bb9a6e4 Starting com.test.thalitest
08-05 01:32:30.615  3569  5139 I ActivityManager: Start proc 11452:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
08-05 01:32:30.615 11452 11452 E Zygote  : v2
08-05 01:32:30.615 11452 11452 I libpersona: KNOX_SDCARD checking this for 10007
08-05 01:32:30.615 11452 11452 I libpersona: KNOX_SDCARD not a persona
08-05 01:32:30.615  3569  5139 D InputDispatcher: Focused application set to: xxxx
08-05 01:32:30.615 11452 11452 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
08-05 01:32:30.615 11452 11452 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:30.615  3569  5139 D InputDispatcher: Focus left window: 7605
08-05 01:32:30.620 11436 11436 D AndroidRuntime: Shutting down VM
08-05 01:32:30.620  3569  3739 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2f26070 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-05 01:32:30.620  3569  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-05 01:32:30.620  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-05 01:32:30.620 11452 11452 E Zygote  : accessInfo : 0
08-05 01:32:30.620 11452 11452 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-05 01:32:30.630  2906  2906 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
08-05 01:32:30.645 11452 11452 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 01:32:30.645 11452 11452 D ActivityThread: Added TimaKeyStore provider
08-05 01:32:30.650  3569  3812 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3569 uid:1000
08-05 01:32:30.650  3569  3812 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:30.650  3569  3812 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3569 uid:1000
08-05 01:32:30.650  3569  3812 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 01:32:30.650  3569  3812 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-05 01:32:30.650  3569  5306 V WindowOrientationListener: setCurrentAppOrientation :-1
08-05 01:32:30.650  3569  5306 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-05 01:32:30.655  3569  3739 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{bb9a6e4 u0 d0 Starting com.test.thalitest}
08-05 01:32:30.655  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-05 01:32:30.660  3569  5306 D ActivityManager:  Launching com.test.thalitest, updated priority
08-05 01:32:30.675  3569  3569 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-05 01:32:30.675  3569  3735 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-05 01:32:30.690  2906  5573 D libEGL  : eglTerminate EGLDisplay = 0xb1a84624
08-05 01:32:30.690  2906  5138 I SurfaceFlinger: id=18 Removed VSBConnecti (7/11)
08-05 01:32:30.695  2906  2994 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
08-05 01:32:30.695  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeea2474
08-05 01:32:30.695  2906  5573 D libEGL  : eglTerminate EGLDisplay = 0xb1a84624
08-05 01:32:30.695  2906  5573 D libEGL  : eglTerminate EGLDisplay = 0xb1a84624
08-05 01:32:30.700  2906  2999 I SurfaceFlinger: id=9 Removed Mauncher (4/10)
08-05 01:32:30.700  2906  2994 I SurfaceFlinger: id=9 Removed Mauncher (-2/10)
08-05 01:32:30.705  2906  5573 I SurfaceFlinger: id=19 Removed VSBConnecti (4/9)
08-05 01:32:30.710  2906  2994 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/9)
08-05 01:32:30.710  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeea2474
08-05 01:32:30.710  5108  5108 V ActivityThread: updateVisibility : ActivityRecord{9648eca token=android.os.BinderProxy@af0d915 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-05 01:32:30.710  5108  5108 D Launcher: onTrimMemory. Level: 20
08-05 01:32:30.710  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeea2474
08-05 01:32:30.715  7605  7605 V ActivityThread: updateVisibility : ActivityRecord{3e24649 token=android.os.BinderProxy@5d4f52 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-05 01:32:30.715  3569  3812 V WindowStateAnimator: Finishing drawing window Window{bb9a6e4 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-05 01:32:30.725  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeea240c
,08-05 01:32:30.985  3569  5306 I WindowManager: Screenshot max retries 4 of Token{8b969d9 ActivityRecord{d999c20 u0 com.test.thalitest/.MainActivity t108}} appWin=Window{bb9a6e4 u0 d0 Starting com.test.thalitest} drawState=2
,08-05 01:32:30.990  3569  3735 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,08-05 01:32:31.000  3569  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-05 01:32:31.015  3569  6895 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:31.030  3569  6895 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:31.075 11452 11452 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-05 01:32:31.110 11452 11452 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-05 01:32:31.120 11452 11452 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 4449-4452)
,08-05 01:32:31.120 11452 11452 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-05 01:32:31.135 11452 11466 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-05 01:32:31.135 11452 11452 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33fda91}
,08-05 01:32:31.135 11452 11452 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-05 01:32:31.140 11452 11452 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 01:32:31.145 11452 11452 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-05 01:32:31.185 11452 11452 D libEGL  : eglInitialize EGLDisplay = 0xbe9c3e7c
,08-05 01:32:31.215  3569  5306 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,08-05 01:32:31.215  3569  5306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-05 01:32:31.275 11452 11452 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-05 01:32:31.295 11452 11452 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 01:32:31.295 11452 11452 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
08-05 01:32:31.295 11452 11452 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-05 01:32:31.300 11452 11452 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-05 01:32:31.325 11452 11452 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-05 01:32:31.335 11452 11452 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung,
,08-05 01:32:31.465 11452 11452 D SecWifiDisplayUtil: Metadata value : none
,08-05 01:32:31.465 11452 11452 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{41c1f56 I.E...... R.....ID 0,0-0,0}
,08-05 01:32:31.475 11452 11503 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 01:32:31.480  3569  5303 D ISSUE_DEBUG: InputChannelName : 821d5f1 com.test.thalitest/com.test.thalitest.MainActivity
,08-05 01:32:31.485  3569  3735 W ActivityManager: Activity pause timeout for ActivityRecord{d999c20 u0 com.test.thalitest/.MainActivity t108}
,08-05 01:32:31.485  3569  5131 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-05 01:32:31.485  3569  5131 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 01:32:31.485  3569  3569 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 01:32:31.490  3569  3569 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-05 01:32:31.525 11452 11452 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 11452
,08-05 01:32:31.525  3569  5303 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/11452 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:31.525  3569  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-05 01:32:31.530  3569  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-05 01:32:31.530  3569  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-05 01:32:31.530  3569  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:31.530  3569  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:31.530  3569  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:31.530  3569  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-05 01:32:31.530  3569  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:31.530  3569  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 01:32:31.530  3569  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-05 01:32:31.530  3569  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:31.535 11452 11466 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-05 01:32:31.545 11452 11452 D SecWifiDisplayUtil: Metadata value : none
,08-05 01:32:31.560  2906  2906 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,08-05 01:32:31.565  3569  3591 D InputDispatcher: Focus entered window: 11452
,08-05 01:32:31.570  3569  3812 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3569 uid:1000
,08-05 01:32:31.570  3569  3812 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:31.570  3569  3812 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3569 uid:1000
08-05 01:32:31.570  3569  3812 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 01:32:31.570 11452 11503 D libEGL  : eglInitialize EGLDisplay = 0x9ce3f7c4
08-05 01:32:31.570 11452 11503 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 01:32:31.575 11452 11503 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-05 01:32:31.580 11452 11452 V ActivityThread: updateVisibility : ActivityRecord{30e1a9 token=android.os.BinderProxy@579f571 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-05 01:32:31.585 11452 11452 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,08-05 01:32:31.590 11452 11452 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 01:32:31.590  3569  5140 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 01:32:31.600 11452 11452 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-05 01:32:31.650 11452 11511 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 01:32:31.650 11452 11511 D libEGL  : eglInitialize EGLDisplay = 0x9c1003ec
,08-05 01:32:31.665  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeea240c
,08-05 01:32:31.670  3569  5305 V WindowStateAnimator: Finishing drawing window Window{821d5f1 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
08-05 01:32:31.675 11452 11452 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 01:32:31.675 11452 11452 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@579f571 time:335008
,08-05 01:32:31.685  3569  3812 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 01:32:31.685  3569  3569 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 01:32:31.685  3569  3569 I KnoxTimeoutHandler: SD activityfalse
,08-05 01:32:31.690  3569  3812 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +705ms (total +1s97ms),
08-05 01:32:31.690  3569  3812 D ActivityManager: mDVFSHelper.release(),
08-05 01:32:31.690  3569  3812 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d999c20 u0 com.test.thalitest/.MainActivity t108} time:335024
08-05 01:32:31.690  3569  3812 D ViewRootImpl: #3 mView = null
,08-05 01:32:31.695  2906  5573 I SurfaceFlinger: id=20 Removed uhalitest (7/9)
,08-05 01:32:31.695  2906  2999 I SurfaceFlinger: id=20 Removed uhalitest (-2/9)
,08-05 01:32:31.700  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeea2474
,08-05 01:32:31.715 11452 11452 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11452
,08-05 01:32:31.905 11452 11452 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 01:32:32.050 11452 11517 D jxcore_app_log: JniHelper::setJavaVM(0xb4874000), pthread_self() = -1760544464
08-05 01:32:32.050 11452 11517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 01:32:32.050 11452 11517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 01:32:32.050 11452 11517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 01:32:32.050 11452 11517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 01:32:32.050 11452 11517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 01:32:32.050 11452 11517 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b48c7 added. We now have 1 listener(s)
08-05 01:32:32.055 11452 11517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
08-05 01:32:32.055 11452 11517 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
08-05 01:32:32.055 11452 11517 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 01:32:32.055 11452 11517 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 01:32:32.060 11452 11517 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92bc092 added. We now have 1 listener(s)
08-05 01:32:32.060 11452 11517 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 01:32:32.060 11452 11517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 01:32:32.060 11452 11517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 01:32:32.060 11452 11517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 01:32:32.060 11452 11517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 01:32:32.060 11452 11517 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 01:32:32.065 11452 11517 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 01:32:32.065 11452 11517 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
08-05 01:32:32.070 11452 11517 D BluetoothAdapter: STATE_ON
08-05 01:32:32.070 11452 11517 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 01:32:32.070 11452 11517 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 01:32:32.070 11452 11517 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 01:32:32.070 11452 11517 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 01:32:32.070 11452 11517 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 01:32:32.075 11452 11452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 01:32:32.075 11452 11452 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 01:32:32.095 11452 11452 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-05 01:32:32.485  4689  4689 D Recents : onTaskStackChanged
08-05 01:32:32.500 11452 11518 W jxcore-log: Initializing JXcore engine
08-05 01:32:32.500 11452 11518 W jxcore-log: JXcore engine is ready
08-05 01:32:32.525  5713  5713 E audit   : type=1400 msg=audit(1470353552.525:268): avc:  denied  { ioctl } for  pid=11518 comm="Thread-1132" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5128 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 01:32:32.525  5713  5713 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:32.525  5713  5713 E audit   : type=1300 msg=audit(1470353552.525:268): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=965033c8 items=0 ppid=2962 ppcomm=main pid=11518 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1132" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 01:32:32.525  5713  5713 E audit   : type=1327 msg=audit(1470353552.525:268): proctitle="com.test.thalitest"
08-05 01:32:32.525  5713  5713 E audit   : type=1320 msg=audit(1470353552.525:268): 
08-05 01:32:32.525  5713  5713 E audit   : type=1400 msg=audit(1470353552.525:269): avc:  denied  { ioctl } for  pid=11518 comm="Thread-1132" path="socket:[43174]" dev="sockfs" ino=43174 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 01:32:32.525  5713  5713 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 01:32:32.525  5713  5713 E audit   : type=1300 msg=audit(1470353552.525:269): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=965033c8 items=0 ppid=2962 ppcomm=main pid=11518 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1132" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 01:32:32.525  5713  5713 E audit   : type=1327 msg=audit(1470353552.525:269): proctitle="com.test.thalitest"
08-05 01:32:32.525  5713  5713 E audit   : type=1320 msg=audit(1470353552.525:269): 
08-05 01:32:32.530 11452 11518 W jxcore-log: Starting JXcore engine
08-05 01:32:32.580 11452 11518 W jxcore-log: Platform android
08-05 01:32:32.580 11452 11518 W jxcore-log: 
08-05 01:32:32.580 11452 11518 W jxcore-log: Process ARCH arm
08-05 01:32:32.580 11452 11518 W jxcore-log: 
08-05 01:32:32.690 11452 11518 I jxcore-log: JXcore Cordova bridge is ready!
08-05 01:32:32.690 11452 11518 I jxcore-log: 
08-05 01:32:32.690 11452 11518 W jxcore-log: JXcore engine is started
08-05 01:32:32.695 11452 11517 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 01:32:32.700 11452 11452 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-05 01:32:33.475  3569  4914 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-05 01:32:33.475  3569  4914 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4351, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
08-05 01:32:33.475  3569  4914 D BatteryService: online:4, current avg:-9, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:-173
08-05 01:32:33.475  3569  4914 D BatteryService: stay LED for fully charged
08-05 01:32:33.475  3569  3569 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-05 01:32:33.475  3569  3569 I MotionRecognitionService: Plugged
08-05 01:32:33.475  3569  3569 D MotionRecognitionService:   cableConnection= 1
08-05 01:32:33.475  3569  3569 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-05 01:32:33.475  3569  3569 D MotionRecognitionService: skip setTransmitPower. 
08-05 01:32:33.480  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-05 01:32:33.480  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-05 01:32:33.480  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
08-05 01:32:33.480  5690  5690 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 01:32:33.480  5690  6204 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 01:32:33.500  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 01:32:33.500  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 01:32:33.500  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 01:32:33.600  3569  4498 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/108_task.xml.bak
,08-05 01:32:37.035  3569  6895 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:40.100  3569  6895 D SSRM:n  : SIOP:: AP = 300, PST = 279 (W:18), CUR = -9, LCD = 0
,08-05 01:32:40.645  3569  3881 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-05 01:32:40.665  3569  3881 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 01:32:40.765 11452 11518 E jxcore  : Error!: Cannot find module '../thalilogger'
08-05 01:32:40.765 11452 11518 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-05 01:32:40.770 11452 11452 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
08-05 01:32:40.770 11452 11452 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-05 01:32:40.780  3569  5306 D InputDispatcher: Focused application set to: xxxx
08-05 01:32:40.780  3569  5306 I ActivityManager: Killing 10498:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
08-05 01:32:40.785 11452 11452 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 01:32:40.785 11452 11452 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-05 01:32:40.785 11452 11452 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 01:32:40.785 11452 11452 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 01:32:40.785 11452 11452 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 01:32:40.785 11452 11452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 01:32:40.785 11452 11452 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b48c7 removed from the list
08-05 01:32:40.785 11452 11452 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 01:32:40.785 11452 11452 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92bc092 removed from the list
08-05 01:32:40.785 11452 11452 D io.jxcore.node.ConnectivityMonitor: stop
08-05 01:32:40.785 11452 11452 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-05 01:32:40.790 11452 11452 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-05 01:32:40.790 11452 11452 W cr_AwContents: WebView.destroy() called while WebView is still attached to window.
,08-05 01:32:40.795  3569  6895 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:40.795  3569  6895 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 01:32:40.805 11452 11452 D ViewRootImpl: #3 mView = null
,08-05 01:32:40.805  2906  5138 I SurfaceFlinger: id=21 Removed NainActivit (6/8)
08-05 01:32:40.805  2906  2994 I SurfaceFlinger: id=21 Removed NainActivit (-2/8)
,08-05 01:32:40.805  3569  4380 D InputDispatcher: Focus left window: 11452
,08-05 01:32:40.805  3569  3812 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3569 uid:1000
08-05 01:32:40.805  3569  3812 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:40.805  3569  3812 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3569 uid:1000
08-05 01:32:40.805  3569  3812 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:32:40.810 11452 11452 D cr_Ime  : [ImeAdapter.java:587] detach
,08-05 01:32:40.810 11452 11452 E ViewRootImpl: sendUserActionEvent() mView == null
,08-05 01:32:40.810  3569  5131 D ActivityManager: mDVFSHelper.acquire()
,08-05 01:32:40.820  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeea2474
,08-05 01:32:40.820  3569  3569 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
08-05 01:32:40.820  3569  3735 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-05 01:32:40.820  3569  5131 V WindowOrientationListener: setCurrentAppOrientation :1
08-05 01:32:40.820  3569  5131 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,08-05 01:32:40.830  3569  3591 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,08-05 01:32:40.835  3569  3735 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,08-05 01:32:40.835  2906  2906 I SurfaceFlinger: id=22 createSurf (1528x2333),1 flag=4, VSBConnecti
,08-05 01:32:40.840  3569  3739 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{8e63620 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-05 01:32:40.840  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-05 01:32:40.840  3569  4710 D InputDispatcher: Focus entered window: 7605
,08-05 01:32:40.840  7605 10290 D mali_winsys: new_window_surface returns 0x3000,  [1528x2333]-format:1
,08-05 01:32:40.845  3569  3812 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3569 uid:1000
08-05 01:32:40.845  3569  3812 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:32:40.845  3569  3812 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3569 uid:1000
08-05 01:32:40.845  3569  3812 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:32:40.845  5108  5108 D Launcher: onRestart, Launcher: 27869641
,08-05 01:32:40.845  5108  5108 D Launcher: onStart, Launcher: 27869641
08-05 01:32:40.845  5108  5108 D Launcher.HomeView: onStart
,08-05 01:32:40.845  3569  5140 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-05 01:32:40.845  3569  5140 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-05 01:32:40.845  3569  3569 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 01:32:40.845  5108  5108 V ActivityThread: updateVisibility : ActivityRecord{9648eca token=android.os.BinderProxy@af0d915 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-05 01:32:40.845  3569  3569 I KnoxTimeoutHandler: Shared devices show user statefalse
08-05 01:32:40.845  3569  3569 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-05 01:32:40.860  2906  2906 I SurfaceFlinger: id=23 createSurf (1440x2560),1 flag=4, Mauncher
,08-05 01:32:40.865  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-05 01:32:40.865  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
08-05 01:32:40.865  3569  3739 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{8e63620 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-05 01:32:40.865  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008000 mask=ffffffff oldVal=8000 newVal=40008000 diff=40000000
,08-05 01:32:40.870  3569  5131 V WindowStateAnimator: Finishing drawing window Window{8e63620 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-05 01:32:40.870  5108  5419 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
08-05 01:32:40.870  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeea240c
,08-05 01:32:40.875  2906  2906 I SurfaceFlinger: id=24 createSurf (1592x384),1 flag=4, VSBConnecti
,08-05 01:32:40.875  3569  3812 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-05 01:32:40.875  3569  3569 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 01:32:40.875  3569  3812 D ActivityManager: mDVFSHelper.release()
08-05 01:32:40.875  3569  3812 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ed8c5fa u0 com.samsung.android.MtpApplication/.USBConnection t107} time:344207
,08-05 01:32:40.875  7605 10290 D mali_winsys: new_window_surface returns 0x3000,  [1592x384]-format:1
,08-05 01:32:40.875  3569  3569 I KnoxTimeoutHandler: SD activityfalse
08-05 01:32:40.875  7605  7605 V ActivityThread: updateVisibility : ActivityRecord{3e24649 token=android.os.BinderProxy@5d4f52 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-05 01:32:40.900  3569  4914 V WindowStateAnimator: Finishing drawing window Window{717899e u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-05 01:32:40.900  7605  7605 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5d4f52 time:344232
,08-05 01:32:40.900  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeea240c
,08-05 01:32:40.905  3569  3812 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-05 01:32:40.905  3569  3569 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 01:32:40.905  3569  3569 I KnoxTimeoutHandler: SD activityfalse
,08-05 01:32:40.935  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbeea240c
,08-05 01:32:40.940  3569  3592 V WindowStateAnimator: Finishing drawing window Window{2f26070 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,08-05 01:32:40.940  5108  5108 D Launcher.HomeView: onStop
,08-05 01:32:40.945  3569  3812 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 01:32:40.945  3569  3569 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 01:32:40.945  3569  3812 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c0849a1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t106} time:344277
,08-05 01:32:40.945  3569  3569 I KnoxTimeoutHandler: SD activityfalse
,08-05 01:32:41.300 11521 11521 I FIPS_bssl: FIPS approved mode (1) | 11521 | app_process
,08-05 01:32:41.305 11521 11521 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-05 01:32:41.310 11521 11521 D AndroidRuntime: CheckJNI is OFF
,08-05 01:32:41.310 11521 11521 D AndroidRuntime: readGMSProperty: start
08-05 01:32:41.310 11521 11521 D AndroidRuntime: readGMSProperty: already setted!!
08-05 01:32:41.310 11521 11521 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 01:32:41.310 11521 11521 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 01:32:41.310 11521 11521 D AndroidRuntime: readGMSProperty: end
08-05 01:32:41.310 11521 11521 D AndroidRuntime: addProductProperty: start
,08-05 01:32:41.335 11521 11521 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-05 01:32:41.370 11521 11521 I Radio-JNI: register_android_hardware_Radio DONE
,08-05 01:32:41.375 11521 11521 E AffinityControl: AffinityControl: registerfunction enter
,08-05 01:32:41.390 11521 11521 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 01:32:41.390  3569  5131 D PackageManager: START PACKAGE DELETE: observer{5961067}
08-05 01:32:41.390  3569  5131 D PackageManager: pkg{<packageName>}
08-05 01:32:41.390  3569  5131 D PackageManager: user{0}
08-05 01:32:41.390  3569  5131 D PackageManager: caller{2000}
08-05 01:32:41.390  3569  5131 D PackageManager: flags{2}
08-05 01:32:41.390  3569  5131 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-05 01:32:41.395  3569  5131 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-05 01:32:41.395  3569  5131 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-05 01:32:41.395  3569  5131 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 01:32:41.395  3569  5131 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 01:32:41.395  3569  3881 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-05 01:32:41.395  3569  3881 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-05 01:32:41.395  3569  3881 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-05 01:32:41.395  3569  3881 D ApplicationPolicy: getApplicationUninstallationEnabled
08-05 01:32:41.395  3569  3881 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-05 01:32:41.395  3569  3881 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-05 01:32:41.395  3569  3881 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-05 01:32:41.395  3569  3881 D PackageManager: !@killApplicatoin: 10007, uninstall pkg
08-05 01:32:41.395  3569  3881 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-05 01:32:41.395  3569  3881 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-05 01:32:41.395  3569  3735 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=-1: uninstall pkg
08-05 01:32:41.395  3569  3735 I ActivityManager: Killing 11452:com.test.thalitest/u0a7 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-05 01:32:41.395  3569  3735 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 01:32:41.395  3569  3735 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-05 01:32:41.400  3569  3881 D AASAinstall: there is not AASApackages.xml file
,08-05 01:32:41.485  3569  4914 D GraphicsStats: Buffer count: 4
08-05 01:32:41.485  3569  3592 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@94348c8)
08-05 01:32:41.485  3569  4453 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:41.485  3569  4453 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 01:32:41.485  3569  4453 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:32:41.580  3569  3881 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-05 01:32:41.610  3569  3881 W PackageSettings: Skipping PackageSetting{25172b6 com.example.hello/10691} due to missing metadata
,08-05 01:32:41.660  3569  3881 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 01:32:41.660  2935  2935 W keystore: ENTER clear_uid from uid 1000 for 10007
,08-05 01:32:41.660  3569  3881 I art     : Starting a blocking GC Explicit
,08-05 01:32:41.745  3569  3881 I art     : Explicit concurrent mark sweep GC freed 149403(9MB) AllocSpace objects, 125(2MB) LOS objects, 33% free, 31MB/46MB, paused 1.139ms total 82.594ms
,08-05 01:32:41.750  3569  3881 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-05 01:32:41.750  3569  3881 D AASAuninstall: userId = 0, info.removedAppID = 10007, info.uid = 10007, packageName = com.test.thalitest
08-05 01:32:41.750  3569  3881 D AASAinstall: there is not AASApackages.xml file
08-05 01:32:41.750  3569  3881 D PackageManager: result of delete: 1{5961067}
,08-05 01:32:41.755 11521 11521 I art     : System.exit called, status: 0
08-05 01:32:41.755 11521 11521 I AndroidRuntime: VM exiting with result code 0.
,08-05 01:32:41.755  3569  3881 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-05 01:32:41.755  3569  3881 D PackageManager: userId{-1}
08-05 01:32:41.755  3569  3881 D PackageManager: andCode{true}
,08-05 01:32:41.760  3569  3881 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=0: pkg removed
,08-05 01:32:41.780 10386 11533 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-05 01:32:41.780 10386 11533 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-05 01:32:41.785 10386 11533 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-05 01:32:41.795  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-05 01:32:41.795  4512  4512 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-05 01:32:41.800  5637  5637 E SamsungIME: mOCRHelper is null
,08-05 01:32:41.800  3569  4416 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 01:32:41.800  5708  6085 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 01:32:41.805  3569  3722 D EnterpriseDeviceManagerService: Package has changed for user 0
08-05 01:32:41.805  3569  3722 W TextServicesManagerService: no available spell checker services found
08-05 01:32:41.805  3569  3722 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-05 01:32:41.810  3569  4443 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 01:32:41.810  3569  4443 V NetworkStats: removeUidsLocked() for UIDs [10007]
08-05 01:32:41.810  3569  4443 V NetworkStats: performPollLocked(flags=0x3)
,08-05 01:32:41.810  3569  4443 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 01:32:41.810  3569  4443 V NetworkStats: performPollLocked() took 4ms
,08-05 01:32:41.815  3569  3735 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{87b970e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{699da11 7963:com.samsung.klmsagent/u0a21}
,08-05 01:32:41.820  7963  7963 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 05 01:32:41 GMT+02:00 2016
,08-05 01:32:41.820  5093  5093 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-05 01:32:41.825  7963  7963 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-05 01:32:41.830  7963  7963 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-05 01:32:41.830  7963  7963 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 01:32:41.830  3569  4710 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-05 01:32:41.830  7963  7963 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-05 01:32:41.830  7963 11537 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-05 01:32:41.830  7963 11537 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-05 01:32:41.830  7963 11537 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-05 01:32:41.830  7963 11537 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
,08-05 01:32:41.840  3569  4380 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{87b970e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10050ef 3569:system/1000}
,08-05 01:32:41.840  3569  4444 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 01:32:41.840  3569  4444 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 01:32:41.840  7963 11537 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-05 01:32:41.840  7963 11537 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-05 01:32:41.840  7963 11537 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 01:32:41.845  7963 11537 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-05 01:32:41.845  4689  4689 D Recents : onTaskStackChanged
,08-05 01:32:41.855  5082 11538 D RegisteredComponentCache: Collect Tech packages for Knox
,08-05 01:32:41.855  7963 11537 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-05 01:32:41.860  7963 11537 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-05 01:32:41.860  7963 11537 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,08-05 01:32:41.865  3569  4380 D SettingsProvider: isChangeAllowed() SettingsProvider : name = klm_eula_shown
08-05 01:32:41.865  3569  4380 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-05 01:32:41.865  3569  4380 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 01:32:41.865  3569  4380 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 01:32:41.865  3569  4380 D SettingsProvider: selectionArgs: false
08-05 01:32:41.865  3569  4380 D SettingsProvider: selectionArgs: 10021
08-05 01:32:41.865  3569  4380 D SettingsProvider: ret = -1
,08-05 01:32:41.865  7963 11537 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-05 01:32:41.865  7963 11537 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,08-05 01:32:41.900  7963 11537 D KLMS-2.6.032: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 317
08-05 01:32:41.900  7963 11537 D KLMS-2.6.032: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
08-05 01:32:41.900  7963 11537 I KLMS-2.6.032: : KLMSSharedPreferences(): getNotificationAppList(): null
08-05 01:32:41.900  7963 11537 D KLMS-2.6.032: : Systemprocess(): Notification App List is Null. Remove Notification.
,08-05 01:32:41.900  7963 11537 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().START: com.test.thalitest
,08-05 01:32:41.905  7963 11537 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-05 01:32:41.905  7963 11537 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: #################################################################
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: #################################################################
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-05 01:32:41.905  7963 11537 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: #################################################################
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-05 01:32:41.905 , 7963 11537 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: #################################################################
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-05 01:32:41.905  7963 11537 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 01:32:41.905  7963 11537 W SQLiteOpenHelper: Opened klms.db in read-only mode
08-05 01:32:41.905  7963 11537 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
08-05 01:32:41.905  7963 11537 D KLMS-2.6.032: : Systemprocess(): PackageName is not Exist.
08-05 01:32:41.905  7963 11537 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().END
08-05 01:32:41.905  7963 11537 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().END
08-05 01:32:41.905  7963 11537 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().END
08-05 01:32:41.905  7963  7963 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
08-05 01:32:41.930  3569  3722 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-05 01:32:41.955  3569  3569 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-05 01:32:41.955  3569  3569 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-05 01:32:41.955  3569  3569 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-05 01:32:41.955  3569  3569 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-05 01:32:41.955  3569  3569 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-05 01:32:41.955  3569  3569 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-05 01:32:41.955  3569  3569 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10007 container id = 0
,08-05 01:32:41.955  3569  3569 I OTPFW   : ProvisionData::getAllEntries Enter
,08-05 01:32:41.960  3569  3569 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-05 01:32:41.960  3569  3569 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,08-05 01:32:41.970  3569  3722 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-05 01:32:41.970  5108  5108 E Launcher.Model: onPackageRemoved :com.test.thalitest
,08-05 01:32:41.970  5108  5186 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-05 01:32:41.970  5108  5186 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 01:32:41.975  3569  3722 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
08-05 01:32:41.975  3569  3722 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-05 01:32:41.975  5108  5186 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-05 01:32:41.975  5108  5186 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 5108
08-05 01:32:41.975  5108  5186 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:489)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$4.run(LauncherModel.java:601)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:605)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:539)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:2472)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-05 01:32:41.975  5108  5186 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 01:32:41.975  3569  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
08-05 01:32:41.975  3569  4388 D UsbHostManager: displayNotification : [02h,02h,01h]
08-05 01:32:41.975  3569  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
08-05 01:32:41.975  3569  4388 D UsbHostManager: displayNotification : [0ah,00h,00h]
08-05 01:32:41.975  3569  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
08-05 01:32:41.975  3569  4388 D UsbHostManager: displayNotification : [02h,0dh,00h]
08-05 01:32:41.975  3569  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
08-05 01:32:41.975  3569  4388 D UsbHostManager: displayNotification : [0ah,00h,01h]
08-05 01:32:41.975  3569  4388 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
08-05 01:32:41.975  3569  4388 D UsbHostManager: displayNotification : [09h,00h,00h]
,08-05 01:32:41.980  3569  4499 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
08-05 01:32:41.980  3569  4499 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
08-05 01:32:41.980  3569  4499 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,08-05 01:32:41.980  4882  4882 D MtpClient: onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
08-05 01:32:41.980  4882  4882 D MtpClient: ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,08-05 01:32:41.980  3569  5139 W ActivityManager:   Force finishing activity com.sec.android.app.launcher/com.android.launcher2.Launcher
,08-05 01:32:41.985  3569 11545 E DropBoxManagerService: Can't write: system_app_crash
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop205.tmp: open failed: EROFS (Read-only file system)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:18019)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:32:41.985  3569 11545 E DropBoxManagerService: 	... 5 more
08-05 01:32:41.985  3569 11545 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop205.tmp
,08-05 01:32:41.985  5108  5108 D Launcher: onTrimMemory. Level: 20
08-05 01:32:41.985  5108  5108 D MenuAppsGridFragment: onDestroyView
08-05 01:32:41.985  5108  5108 W Launcher.MenuAppsGrid: Trying to exit a state that hasn't been entered
,08-05 01:32:41.990  5108  5108 D Launcher.HomeView: onDestroyView
,08-05 01:32:41.990  5108  5108 D Launcher: onDestroy, Launcher: 27869641
,08-05 01:32:41.990  5108  5186 I Process : Sending signal. PID: 5108 SIG: 9
,08-05 01:32:42.025  3569  4499 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
08-05 01:32:42.025  3569  4499 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,08-05 01:32:42.050  3569  4416 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-05 01:32:42.075  3569  5306 D GraphicsStats: Buffer count: 3
08-05 01:32:42.075  3569  4380 I WindowState: WIN DEATH: Window{2f26070 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
,08-05 01:32:42.075  2906  5138 I SurfaceFlinger: id=23 Removed Mauncher (4/10)
08-05 01:32:42.080  2906  2994 I SurfaceFlinger: id=23 Removed Mauncher (-2/10)
08-05 01:32:42.085  3569  3592 I ActivityManager: Process com.sec.android.app.launcher (pid 5108)(adj 6) has died(276,1389)
08-05 01:32:42.090  3569  3592 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.launcher, Auto Run ON
08-05 01:32:42.095  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbeea2474
08-05 01:32:42.100  3569  4416 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-05 01:32:42.125  3569  4416 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-05 01:32:42.185  3569  4416 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-05 01:32:42.240  3569  4416 I EventHub: Removing device '/dev/input/event11' due to inotify event
,08-05 01:32:42.290  3569  4416 I EventHub: Removing device '/dev/input/event12' due to inotify event
,08-05 01:32:42.315  3569  4416 I EventHub: Removing device '/dev/input/event13' due to inotify event
,08-05 01:32:42.345  3569  4416 I EventHub: Removing device '/dev/input/event14' due to inotify event
,08-05 01:32:42.350  3569  4970 E Watchdog: !@Sync 11 [08-05 01:32:42.352]

```
