#### Test 757892685fc4836_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,07-05 15:39:16.332  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:39:16.332  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-05 15:39:16.977  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
07-05 15:39:17.172 11330 11330 I FIPS_bssl: FIPS approved mode (1) | 11330 | app_process
07-05 15:39:17.182 11330 11330 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 15:39:17.182 11330 11330 D AndroidRuntime: CheckJNI is OFF
07-05 15:39:17.187 11330 11330 D AndroidRuntime: readGMSProperty: start
07-05 15:39:17.187 11330 11330 D AndroidRuntime: readGMSProperty: already setted!!
07-05 15:39:17.187 11330 11330 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 15:39:17.187 11330 11330 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 15:39:17.187 11330 11330 D AndroidRuntime: readGMSProperty: end
07-05 15:39:17.187 11330 11330 D AndroidRuntime: addProductProperty: start
07-05 15:39:17.212 11330 11330 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 15:39:17.242 11330 11330 I Radio-JNI: register_android_hardware_Radio DONE
07-05 15:39:17.247 11330 11330 E AffinityControl: AffinityControl: registerfunction enter
07-05 15:39:17.262 11330 11330 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 15:39:17.312  3618  3644 D GameManagerService: identifyGamePackage. com.test.thalitest
07-05 15:39:17.312  3618  3644 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
07-05 15:39:17.317  3618  3644 D ActivityManager: mDVFSHelper.acquire()
07-05 15:39:17.317  3618  3644 V WindowManager: addAppToken: AppWindowToken{2f81784 token=Token{c531997 ActivityRecord{1dd5c16 u0 com.test.thalitest/.MainActivity t69}}} to stack=1 task=69 at 0
07-05 15:39:17.332  3618  3866 D SecWifiDisplayUtil: Metadata value : none
07-05 15:39:17.332  3618  3866 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{488d31c V.E...... R.....ID 0,0-0,0}
07-05 15:39:17.337  3618  3866 D ISSUE_DEBUG: InputChannelName : eb184fa Starting com.test.thalitest
07-05 15:39:17.337 11346 11346 E Zygote  : v2
07-05 15:39:17.337 11346 11346 I libpersona: KNOX_SDCARD checking this for 10007
07-05 15:39:17.337  3618  3644 I ActivityManager: Start proc 11346:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
07-05 15:39:17.337 11346 11346 I libpersona: KNOX_SDCARD not a persona
07-05 15:39:17.337  3618  3644 D InputDispatcher: Focused application set to: xxxx
07-05 15:39:17.337 11346 11346 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-05 15:39:17.337 11346 11346 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 15:39:17.337  3618  3644 D InputDispatcher: Focus left window: 7004
07-05 15:39:17.342 11346 11346 E Zygote  : accessInfo : 0
07-05 15:39:17.342 11330 11330 D AndroidRuntime: Shutting down VM
07-05 15:39:17.342  3618  3794 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7cb09c7 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-05 15:39:17.342  3618  4443 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-05 15:39:17.342  4513  4513 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-05 15:39:17.342 11346 11346 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 15:39:17.352  2906  2906 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
07-05 15:39:17.372 11346 11346 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:39:17.372 11346 11346 D ActivityThread: Added TimaKeyStore provider
07-05 15:39:17.377  3618  5127 V WindowOrientationListener: setCurrentAppOrientation :-1
07-05 15:39:17.377  3618  5127 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-05 15:39:17.377  3618  3866 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3618 uid:1000
07-05 15:39:17.377  3618  3866 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 15:39:17.377  3618  3866 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3618 uid:1000
07-05 15:39:17.377  3618  3866 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 15:39:17.377  3618  3866 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-05 15:39:17.382  3618  3794 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{eb184fa u0 d0 Starting com.test.thalitest}
07-05 15:39:17.382  4513  4513 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-05 15:39:17.387  3618  5127 D ActivityManager:  Launching com.test.thalitest, updated priority
07-05 15:39:17.402  3618  3618 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-05 15:39:17.402  3618  3790 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-05 15:39:17.412  2906  2981 I SurfaceFlinger: id=19 Removed VSBConnecti (5/11)
07-05 15:39:17.412  2906 10197 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
07-05 15:39:17.417  2906  2981 D libEGL  : eglTerminate EGLDisplay = 0xb6881624
07-05 15:39:17.417  2906  2981 D libEGL  : eglTerminate EGLDisplay = 0xb6881624
07-05 15:39:17.422  2906 10197 I SurfaceFlinger: id=9 Removed Mauncher (4/10)
07-05 15:39:17.422  2906  5213 I SurfaceFlinger: id=9 Removed Mauncher (-2/10)
07-05 15:39:17.422  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe82d474
07-05 15:39:17.422  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe82d474
07-05 15:39:17.432  2906  2985 D libEGL  : eglTerminate EGLDisplay = 0xb663f624
07-05 15:39:17.432  2906  5213 I SurfaceFlinger: id=18 Removed VSBConnecti (5/9)
07-05 15:39:17.432  2906  2981 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/9)
07-05 15:39:17.432  5112  5112 V ActivityThread: updateVisibility : ActivityRecord{cc41b32 token=android.os.BinderProxy@614a4b6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 15:39:17.432  5112  5112 D Launcher: onTrimMemory. Level: 20
07-05 15:39:17.437  7004  7004 V ActivityThread: updateVisibility : ActivityRecord{252fe1a token=android.os.BinderProxy@e3163f {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-05 15:39:17.442  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe82d474
07-05 15:39:17.447  3618  3866 V WindowStateAnimator: Finishing drawing window Window{eb184fa u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-05 15:39:17.457  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe82d40c
,07-05 15:39:17.722  3618  5127 I WindowManager: Screenshot max retries 4 of Token{c531997 ActivityRecord{1dd5c16 u0 com.test.thalitest/.MainActivity t69}} appWin=Window{eb184fa u0 d0 Starting com.test.thalitest} drawState=2
,07-05 15:39:17.727  3618  3790 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-05 15:39:17.742  3618  4443 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false,
,07-05 15:39:17.757  3618  6879 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:39:17.772  3618  6879 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:39:17.822 11346 11346 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-05 15:39:17.857 11346 11346 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-05 15:39:17.862 11346 11346 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 3691-3694)
07-05 15:39:17.867 11346 11346 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-05 15:39:17.882 11346 11360 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-05 15:39:17.882 11346 11346 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4c2db42}
07-05 15:39:17.882 11346 11346 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-05 15:39:17.882 11346 11346 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 15:39:17.892 11346 11346 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-05 15:39:17.932 11346 11346 D libEGL  : eglInitialize EGLDisplay = 0xbee90e7c
,07-05 15:39:17.962  3618  5043 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,07-05 15:39:17.967  3618  5043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,07-05 15:39:17.972  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 301 (W:22), CUR = 150, LCD = 0
,07-05 15:39:18.027 11346 11346 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-05 15:39:18.037 11346 11346 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 15:39:18.037 11346 11346 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-05 15:39:18.037 11346 11346 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-05 15:39:18.042 11346 11346 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-05 15:39:18.057 11346 11346 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-05 15:39:18.067 11346 11346 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 15:39:18.182 11346 11346 D SecWifiDisplayUtil: Metadata value : none
,07-05 15:39:18.182 11346 11346 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ccd4b33 I.E...... R.....ID 0,0-0,0}
,07-05 15:39:18.192 11346 11397 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 15:39:18.197  3618  5126 D ISSUE_DEBUG: InputChannelName : 4966f com.test.thalitest/com.test.thalitest.MainActivity
,07-05 15:39:18.197  3618  5096 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-05 15:39:18.197  3618  5096 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:39:18.197  3618  3618 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:39:18.202  3618  3618 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-05 15:39:18.232 11346 11346 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 11346
,07-05 15:39:18.232  3618  3644 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/11346 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 15:39:18.232  3618  4452 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-05 15:39:18.232  3618  4452 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-05 15:39:18.232  3618  4452 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-05 15:39:18.232  3618  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:18.232  3618  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:18.232  3618  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-05 15:39:18.232  3618  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:18.237  3618  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:18.237  3618  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-05 15:39:18.237  3618  4452 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 15:39:18.237 11346 11360 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-05 15:39:18.252 11346 11346 D SecWifiDisplayUtil: Metadata value : none
,07-05 15:39:18.262  2906  2906 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,07-05 15:39:18.277  3618  3643 D InputDispatcher: Focus entered window: 11346
,07-05 15:39:18.282  3618  3866 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3618 uid:1000,
,07-05 15:39:18.282  3618  3866 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 15:39:18.282  3618  3866 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3618 uid:1000
07-05 15:39:18.282  3618  3866 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 15:39:18.282 11346 11397 D libEGL  : eglInitialize EGLDisplay = 0x9c1bf7c4
07-05 15:39:18.282 11346 11397 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 15:39:18.287 11346 11397 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,07-05 15:39:18.292 11346 11346 V ActivityThread: updateVisibility : ActivityRecord{a063fa token=android.os.BinderProxy@f5922a2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 15:39:18.297 11346 11346 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,07-05 15:39:18.297 11346 11346 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-05 15:39:18.342 11346 11402 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 15:39:18.342 11346 11402 D libEGL  : eglInitialize EGLDisplay = 0x9973f3ec
,07-05 15:39:18.352  3618  5126 V WindowStateAnimator: Finishing drawing window Window{4966f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-05 15:39:18.352 11346 11346 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 15:39:18.352  3618  5043 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 15:39:18.357  3618  3866 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 15:39:18.357  3618  3618 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 15:39:18.362  3618  3618 I KnoxTimeoutHandler: SD activityfalse
07-05 15:39:18.362  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe82d40c
,07-05 15:39:18.362  3618  3866 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +641ms (total +1s44ms)
,07-05 15:39:18.367 11346 11346 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 15:39:18.367  3618  3866 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1dd5c16 u0 com.test.thalitest/.MainActivity t69} time:294199,
07-05 15:39:18.367  3618  3866 D ActivityManager: mDVFSHelper.release(),
,07-05 15:39:18.377  3618  3866 D ViewRootImpl: #3 mView = null
,07-05 15:39:18.377  2906  5213 I SurfaceFlinger: id=20 Removed uhalitest (7/9)
,07-05 15:39:18.377  2906  2985 I SurfaceFlinger: id=20 Removed uhalitest (-2/9)
07-05 15:39:18.382 11346 11346 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f5922a2 time:294210
,07-05 15:39:18.392  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe82d474
,07-05 15:39:18.397 11346 11346 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11346
,07-05 15:39:18.557 11346 11346 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 15:39:18.587 11346 11346 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 15:39:18.692 11346 11410 D jxcore_app_log: JniHelper::setJavaVM(0xb48b4000), pthread_self() = -1743259344
07-05 15:39:18.692 11346 11410 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 15:39:18.692 11346 11410 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 15:39:18.692 11346 11410 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 15:39:18.692 11346 11410 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 15:39:18.692 11346 11410 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 15:39:18.692 11346 11410 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdc420 added. We now have 1 listener(s)
07-05 15:39:18.697 11346 11410 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
07-05 15:39:18.697 11346 11410 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
07-05 15:39:18.697 11346 11410 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 15:39:18.697 11346 11410 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd7527f added. We now have 1 listener(s)
07-05 15:39:18.702 11346 11410 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 15:39:18.702 11346 11410 D BluetoothAdapter: STATE_ON
07-05 15:39:18.702 11346 11410 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-05 15:39:18.707 11346 11410 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 15:39:18.707 11346 11410 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 15:39:18.707 11346 11410 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 15:39:18.707 11346 11410 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-05 15:39:18.707 11346 11410 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 15:39:18.707 11346 11410 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
07-05 15:39:18.712 11346 11410 D BluetoothAdapter: STATE_ON
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 15:39:18.712 11346 11410 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 15:39:18.712 11346 11410 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 15:39:18.717 11346 11410 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 15:39:18.717 11346 11410 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 15:39:18.717 11346 11346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 15:39:18.717 11346 11346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 15:39:18.727 11346 11346 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-05 15:39:19.107 11346 11411 W jxcore-log: Initializing JXcore engine
07-05 15:39:19.107 11346 11411 W jxcore-log: JXcore engine is ready
07-05 15:39:19.132  5827  5827 E audit   : type=1400 msg=audit(1467725959.127:266): avc:  denied  { ioctl } for  pid=11411 comm="Thread-1131" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3223 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 15:39:19.132  5827  5827 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:39:19.132  5827  5827 E audit   : type=1300 msg=audit(1467725959.127:266): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=980553c8 items=0 ppid=2961 ppcomm=main pid=11411 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1131" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 15:39:19.132  5827  5827 E audit   : type=1327 msg=audit(1467725959.127:266): proctitle="com.test.thalitest"
07-05 15:39:19.132  5827  5827 E audit   : type=1320 msg=audit(1467725959.127:266): 
07-05 15:39:19.132  5827  5827 E audit   : type=1400 msg=audit(1467725959.132:267): avc:  denied  { ioctl } for  pid=11411 comm="Thread-1131" path="socket:[44337]" dev="sockfs" ino=44337 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-05 15:39:19.132  5827  5827 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:39:19.132  5827  5827 E audit   : type=1300 msg=audit(1467725959.132:267): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=980553c8 items=0 ppid=2961 ppcomm=main pid=11411 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1131" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 15:39:19.132  5827  5827 E audit   : type=1327 msg=audit(1467725959.132:267): proctitle="com.test.thalitest"
07-05 15:39:19.132  5827  5827 E audit   : type=1320 msg=audit(1467725959.132:267): 
07-05 15:39:19.137 11346 11411 W jxcore-log: Starting JXcore engine
07-05 15:39:19.182 11346 11411 W jxcore-log: Platform android
07-05 15:39:19.182 11346 11411 W jxcore-log: 
07-05 15:39:19.182 11346 11411 W jxcore-log: Process ARCH arm
07-05 15:39:19.182 11346 11411 W jxcore-log: 
07-05 15:39:19.207  4686  4686 D Recents : onTaskStackChanged
07-05 15:39:19.277 11346 11411 I jxcore-log: JXcore Cordova bridge is ready!
07-05 15:39:19.277 11346 11411 I jxcore-log: 
07-05 15:39:19.277 11346 11411 W jxcore-log: JXcore engine is started
,07-05 15:39:20.337  3618  4496 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/69_task.xml.bak
07-05 15:39:20.862  3618  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:39:20.862  3618  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:39:20.862  3618  5116 D BatteryService: online:4, current avg:132, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:132
07-05 15:39:20.862  3618  5116 D BatteryService: stay LED for fully charged
07-05 15:39:20.862  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:39:20.867  3618  3618 I MotionRecognitionService: Plugged
07-05 15:39:20.867  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:39:20.867  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:39:20.867  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
07-05 15:39:20.877  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:20.877  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:20.877  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 15:39:20.892  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:39:20.892  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 15:39:20.902  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:20.902  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:20.902  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:23.802  3618  6879 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:39:27.367  3618  3928 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 15:39:27.422  3618  3928 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-05 15:39:28.027  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 299 (W:24), CUR = 132, LCD = 0
,07-05 15:39:30.997  3618  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:39:30.997  3618  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:39:30.997  3618  4438 D BatteryService: online:4, current avg:141, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:148
07-05 15:39:30.997  3618  4438 D BatteryService: stay LED for fully charged
,07-05 15:39:31.002  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:39:31.007  3618  3618 I MotionRecognitionService: Plugged
07-05 15:39:31.007  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:39:31.007  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:39:31.007  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:39:31.012  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:31.012  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:31.017  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:39:31.032  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:39:31.032  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:39:31.042  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:31.042  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:31.042  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:31.367  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:39:31.367  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:39:34.347  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:39:34.347  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:39:36.452  3618  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:39:36.457  3618  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:39:36.462  3618  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:39:36.477  3618  4390 I TLC_TIMA_PKM_initialize: initializing...
,07-05 15:39:36.477  3618  4390 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
,07-05 15:39:36.477  3618  4390 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
,07-05 15:39:36.482  3618  4390 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
,07-05 15:39:36.482  3618  4390 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-05 15:39:36.482  3618  4390 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-05 15:39:36.482  3618  4390 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
,07-05 15:39:36.487  3618  4390 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-05 15:39:36.487  3618  4390 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-05 15:39:36.487  3618  4390 I TZ: mc_tlc_communication: device_id = 0x0
07-05 15:39:36.487  3618  4390 I TZ: mc_tlc_communication: tlc_open() was called
07-05 15:39:36.487  3618  4390 I TZ: mc_tlc_communication: Opening MobiCore device
,07-05 15:39:36.487  3618  4390 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-05 15:39:36.492  3618  4390 I TZ: mc_tlc_communication: Opening the session
,07-05 15:39:36.517  3618  4390 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-05 15:39:36.527  3618  4390 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 15:39:36.977  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:39:38.047  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 297 (W:24), CUR = 141, LCD = 0
,07-05 15:39:39.907  3618  4975 E Watchdog: !@Sync 10 [07-05 15:39:39.913]
,07-05 15:39:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:39:40.712  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:39:40.712  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:39:41.112  3618  4894 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:39:41.112  3618  4894 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:39:41.112  3618  4894 D BatteryService: online:4, current avg:141, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:136
07-05 15:39:41.112  3618  4894 D BatteryService: stay LED for fully charged
,07-05 15:39:41.112  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:39:41.117  3618  3618 I MotionRecognitionService: Plugged
07-05 15:39:41.117  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:39:41.117  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:39:41.117  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:39:41.122  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:41.122  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:41.122  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:39:41.127  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:41.132  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:39:41.132  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:39:41.147  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:41.147  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:41.187  3618  4400 V AlarmManager: Expired Alarm result :4
,07-05 15:39:41.192  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:39:41.192  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 15:39:41.192  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:39:41.202  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:39:41.207  4948  4948 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-05 15:39:41.207  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:39:41.207  4948  4948 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-05 15:39:41.222  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.227  4948  4948 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-05 15:39:41.227  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.227  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.227  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.227  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.232  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.232  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.312  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:43.402  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 15:39:43.402  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:39:43.417  3618  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 15:39:43.422  3618  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:39:45.082  4948  4948 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,07-05 15:39:45.087  2915  4367 D Netd    : Iface wlan0 link up
07-05 15:39:45.092  3618  3801 D Tethering: interfaceLinkStateChanged wlan0, true
07-05 15:39:45.092  3618  3801 D Tethering: interfaceStatusChanged wlan0, true
,07-05 15:39:45.102  4948  4948 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!,
,07-05 15:39:45.117  3618  4444 D WifiP2pService: InactiveState{ what=147461 }
07-05 15:39:45.117  3618  4444 D WifiP2pService: P2pEnabledState{ what=147461 }
07-05 15:39:45.117  3618  4444 D WifiP2pService: DefaultState{ what=147461 }
,07-05 15:39:45.157  3618  3790 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5edf95f u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0bf9b9 4513:com.android.systemui/u0a60}
,07-05 15:39:48.077  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:24), CUR = 141, LCD = 0
,07-05 15:39:50.487  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:39:50.487  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:39:51.257  3618  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:39:51.257  3618  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:39:51.257  3618  4438 D BatteryService: online:4, current avg:141, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:134
07-05 15:39:51.257  3618  4438 D BatteryService: stay LED for fully charged
,07-05 15:39:51.257  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:39:51.262  3618  3618 I MotionRecognitionService: Plugged
07-05 15:39:51.262  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:39:51.262  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:39:51.262  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:39:51.272  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:51.272  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:51.272  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:39:51.292  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:39:51.292  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:39:51.297  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:51.297  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:51.297  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:56.987  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:39:58.107  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:24), CUR = 141, LCD = 0
,07-05 15:39:59.997  3618  4400 V AlarmManager: Expired Alarm result :8
,07-05 15:40:01.392  3618  4647 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:40:01.392  3618  4647 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:40:01.392  3618  4647 D BatteryService: online:4, current avg:140, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:139
07-05 15:40:01.392  3618  4647 D BatteryService: stay LED for fully charged
,07-05 15:40:01.397  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:40:01.402  3618  3618 I MotionRecognitionService: Plugged
07-05 15:40:01.402  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:40:01.402  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:40:01.402  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:01.407  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:40:01.407  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:01.407  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:01.427  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:40:01.427  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:01.432  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 15:40:01.432  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:01.432  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:08.132  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:26), CUR = 140, LCD = 0
,07-05 15:40:09.167  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:40:09.167  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:40:09.907  3618  4975 E Watchdog: !@Sync 11 [07-05 15:40:09.914]
,07-05 15:40:11.537  3618  5044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:40:11.537  3618  5044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:40:11.537  3618  5044 D BatteryService: online:4, current avg:138, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:141
07-05 15:40:11.537  3618  5044 D BatteryService: stay LED for fully charged
,07-05 15:40:11.537  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:40:11.542  3618  3618 I MotionRecognitionService: Plugged
07-05 15:40:11.542  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:40:11.542  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:40:11.542  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:11.552  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:11.552  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:11.552  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:11.572  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:40:11.572  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:11.577  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:11.577  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:11.577  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:16.737  5819  5819 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:40:16.757  5819  5819 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:40:16.762  5819  5819 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:40:16.832  9884  9913 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 15:40:16.832  9884  9913 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 15:40:16.842  2915  4370 D EnterpriseController: netId is 0
07-05 15:40:16.842  2915  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10031
,07-05 15:40:16.987  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:40:18.162  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:26), CUR = 138, LCD = 0
,07-05 15:40:21.672  3618  5904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:40:21.672  3618  5904 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:40:21.672  3618  5904 D BatteryService: online:4, current avg:136, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:142
07-05 15:40:21.672  3618  5904 D BatteryService: stay LED for fully charged
,07-05 15:40:21.672  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:40:21.677  3618  3618 I MotionRecognitionService: Plugged
07-05 15:40:21.677  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:40:21.677  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:40:21.677  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:21.687  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:21.687  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:40:21.687  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:21.702  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:40:21.707  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:21.717  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:21.717  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:21.717  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:28.192  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:26), CUR = 136, LCD = 0
,07-05 15:40:31.822  3618  5127 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:40:31.822  3618  5127 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:40:31.822  3618  5127 D BatteryService: online:4, current avg:135, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:137
07-05 15:40:31.822  3618  5127 D BatteryService: stay LED for fully charged
,07-05 15:40:31.822  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:40:31.827  3618  3618 I MotionRecognitionService: Plugged
07-05 15:40:31.827  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:40:31.827  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:40:31.827  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:31.832  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:31.832  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:31.832  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:31.857  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:40:31.857  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:31.862  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:31.862  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:31.862  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:32.007  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:40:32.007  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:40:36.992  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:40:38.227  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:26), CUR = 135, LCD = 0
,07-05 15:40:39.917  3618  4975 E Watchdog: !@Sync 12 [07-05 15:40:39.918]
,07-05 15:40:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:40:40.857  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:40:40.857  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:40:41.937  3618  4685 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:40:41.937  3618  4685 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:40:41.937  3618  4685 D BatteryService: online:4, current avg:133, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:119
07-05 15:40:41.937  3618  4685 D BatteryService: stay LED for fully charged
,07-05 15:40:41.942  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:40:41.942  3618  3618 I MotionRecognitionService: Plugged
07-05 15:40:41.942  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:40:41.942  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:40:41.942  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:41.952  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:41.952  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:41.952  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:41.962  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:41.962  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:40:41.962  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:41.962  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:41.977  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:48.252  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:28), CUR = 133, LCD = 0
,07-05 15:40:52.082  3618  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:40:52.082  3618  5113 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:40:52.082  3618  5113 D BatteryService: online:4, current avg:130, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:126
07-05 15:40:52.082  3618  5113 D BatteryService: stay LED for fully charged
,07-05 15:40:52.082  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:40:52.087  3618  3618 I MotionRecognitionService: Plugged
07-05 15:40:52.087  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:40:52.087  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:40:52.087  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:52.092  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:52.092  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:52.092  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:52.102  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:40:52.102  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:52.117  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:52.117  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:52.117  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:56.997  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:40:58.282  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:28), CUR = 130, LCD = 0
,07-05 15:41:02.217  3618  5096 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:41:02.217  3618  5096 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:41:02.217  3618  5096 D BatteryService: online:4, current avg:129, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:134
07-05 15:41:02.217  3618  5096 D BatteryService: stay LED for fully charged
,07-05 15:41:02.222  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:41:02.227  3618  3618 I MotionRecognitionService: Plugged
07-05 15:41:02.227  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:41:02.227  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:41:02.227  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:41:02.232  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:41:02.232  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:41:02.232  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:41:02.257  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:41:02.257  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:41:02.262  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:02.262  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:02.262  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:08.307  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:28), CUR = 129, LCD = 0
,07-05 15:41:08.452  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:41:08.452  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:41:09.917  3618  4975 E Watchdog: !@Sync 13 [07-05 15:41:09.922]
,07-05 15:41:12.352  3618  4685 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:41:12.357  3618  4685 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:41:12.357  3618  4685 D BatteryService: online:4, current avg:128, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:126
07-05 15:41:12.357  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:41:12.357  3618  4685 D BatteryService: stay LED for fully charged
,07-05 15:41:12.362  3618  3618 I MotionRecognitionService: Plugged
07-05 15:41:12.362  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:41:12.367  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:41:12.367  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:41:12.372  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:41:12.372  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:41:12.372  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:41:12.392  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:41:12.392  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:41:12.397  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:12.397  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:12.397  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:16.997  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:41:18.332  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:28), CUR = 128, LCD = 0
,07-05 15:41:22.497  3618  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:41:22.497  3618  5113 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:41:22.497  3618  5113 D BatteryService: online:4, current avg:126, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:114
07-05 15:41:22.497  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:41:22.497  3618  5113 D BatteryService: stay LED for fully charged
,07-05 15:41:22.502  3618  3618 I MotionRecognitionService: Plugged
07-05 15:41:22.502  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:41:22.502  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:41:22.502  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:41:22.512  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:41:22.512  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:41:22.512  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:41:22.532  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:41:22.532  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:41:22.537  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:22.537  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:22.537  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:25.207  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:41:25.207  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:41:28.357  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:30), CUR = 126, LCD = 0
,07-05 15:41:29.217  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:41:29.217  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:41:32.637  3618  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:41:32.642  3618  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:41:32.642  3618  5116 D BatteryService: online:4, current avg:125, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:111
07-05 15:41:32.642  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:41:32.642  3618  5116 D BatteryService: stay LED for fully charged
,07-05 15:41:32.647  3618  3618 I MotionRecognitionService: Plugged
07-05 15:41:32.647  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:41:32.647  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:41:32.647  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:41:32.652  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:41:32.652  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:41:32.652  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:41:32.672  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:41:32.672  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:41:32.677  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 15:41:32.677  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:32.677  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:36.997  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:41:38.382  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:30), CUR = 125, LCD = 0
,07-05 15:41:39.922  3618  4975 E Watchdog: !@Sync 14 [07-05 15:41:39.926]
,07-05 15:41:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:41:40.967  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:41:40.967  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:41:41.057  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 78ms lastUpdatedAfter : 180458ms
,07-05 15:41:44.287  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:41:44.287  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:41:48.412  3618  6879 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:30), CUR = 125, LCD = 0
,07-05 15:41:57.002  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:41:58.442  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:30), CUR = 125, LCD = 0
,07-05 15:42:02.737  3618  4894 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:42:02.737  3618  4894 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4379, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:42:02.737  3618  4894 D BatteryService: online:4, current avg:8, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:42:02.737  3618  4894 D BatteryService: stay LED for fully charged
,07-05 15:42:02.737  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:42:02.747  3618  3618 I MotionRecognitionService: Plugged
07-05 15:42:02.747  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:42:02.747  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:42:02.747  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:42:02.752  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:42:02.752  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:42:02.752  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:42:02.772  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:42:02.772  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:42:02.777  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:42:02.777  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:42:02.777  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:08.472  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:30), CUR = 8, LCD = 0
,07-05 15:42:09.927  3618  4975 E Watchdog: !@Sync 15 [07-05 15:42:09.930]
,07-05 15:42:17.007  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:42:18.497  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:30), CUR = 8, LCD = 0
,07-05 15:42:28.527  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:30), CUR = 8, LCD = 0
,07-05 15:42:28.802  2989  2989 I bootchecker: bootchecker wake up!!
,07-05 15:42:32.832  3618  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:42:32.837  3618  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:42:32.837  3618  4438 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:42:32.837  3618  4438 D BatteryService: stay LED for fully charged
07-05 15:42:32.837  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:42:32.842  3618  3618 I MotionRecognitionService: Plugged
07-05 15:42:32.842  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:42:32.842  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:42:32.842  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:42:32.852  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:42:32.852  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:42:32.857  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:42:32.877  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:42:32.877  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:42:32.882  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:42:32.882  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:42:32.882  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:37.007  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:42:38.562  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:30), LCD = 0
,07-05 15:42:39.937  3618  4975 E Watchdog: !@Sync 16 [07-05 15:42:39.937]
,07-05 15:42:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:42:41.177  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:42:41.177  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:42:48.587  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:30), LCD = 0
,07-05 15:42:57.007  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:42:58.617  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), LCD = 0
,07-05 15:42:59.992  3618  4400 V AlarmManager: Expired Alarm result :8
07-05 15:42:59.992  3618  4400 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=515824 batch.start=672850
,07-05 15:43:02.932  3618  5126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:43:02.932  3618  5126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:43:02.932  3618  5126 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:43:02.932  3618  5126 D BatteryService: stay LED for fully charged
,07-05 15:43:02.932  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:43:02.937  3618  3618 I MotionRecognitionService: Plugged
07-05 15:43:02.937  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:43:02.937  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:43:02.937  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:43:02.947  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:43:02.947  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:43:02.947  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:43:02.957  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:43:02.957  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:43:02.972  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:43:02.972  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:43:02.972  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:43:08.642  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), LCD = 0
,07-05 15:43:09.937  3618  4975 E Watchdog: !@Sync 17 [07-05 15:43:09.943]
,07-05 15:43:17.012  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:43:18.662  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), LCD = 0
,07-05 15:43:28.687  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), LCD = 0
,07-05 15:43:33.037  3618  4685 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:43:33.037  3618  4685 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:43:33.037  3618  4685 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:43:33.037  3618  4685 D BatteryService: stay LED for fully charged
,07-05 15:43:33.037  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:43:33.042  3618  3618 I MotionRecognitionService: Plugged
07-05 15:43:33.042  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:43:33.042  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:43:33.042  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:43:33.047  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:43:33.047  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:43:33.047  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:43:33.067  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:43:33.067  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:43:33.077  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:43:33.077  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:43:33.077  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:43:37.012  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:43:38.717  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), LCD = 0
,07-05 15:43:39.942  3618  4975 E Watchdog: !@Sync 18 [07-05 15:43:39.947]
,07-05 15:43:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:43:41.322  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:43:41.322  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:43:48.747  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), LCD = 0
,07-05 15:43:57.017  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:43:58.772  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), LCD = 0
,07-05 15:44:03.127  3618  5096 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:44:03.127  3618  5096 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:44:03.127  3618  5096 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:44:03.127  3618  5096 D BatteryService: stay LED for fully charged
,07-05 15:44:03.127  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:44:03.137  3618  3618 I MotionRecognitionService: Plugged
07-05 15:44:03.137  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:44:03.137  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:44:03.137  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:44:03.147  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:44:03.147  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:44:03.147  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:44:03.152  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:44:03.152  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:44:03.167  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:44:03.167  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:44:03.167  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:44:08.802  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), LCD = 0
,07-05 15:44:09.952  3618  4975 E Watchdog: !@Sync 19 [07-05 15:44:09.952]
,07-05 15:44:17.022  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:44:17.797  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:44:17.797  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:44:18.827  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), LCD = 0
,07-05 15:44:28.857  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), LCD = 0
,07-05 15:44:32.807  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:44:32.807  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:44:33.212  3618  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:44:36.457  3618  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 15:44:36.457  3618  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:44:36.462  3618  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:44:37.022  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:44:38.897  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), LCD = 0
,07-05 15:44:39.952  3618  4975 E Watchdog: !@Sync 20 [07-05 15:44:39.956]
,07-05 15:44:40.052  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 15:44:40.052  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:44:40.067  3618  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 15:44:40.072  3618  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:44:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:44:41.412  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:44:41.412  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:44:41.502  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 77ms lastUpdatedAfter : 180444ms
,07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLock,ed: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.172  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:43.177  3618  3774 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:43.392  3618  3866 I ActivityManager: setMaxStartingBackgroundTimer onfinish
07-05 15:44:43.392  3618  3866 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-05 15:44:48.922  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), LCD = 0
,07-05 15:44:57.027  3618  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:44:58.957  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), LCD = 0
,07-05 15:45:03.312  3618  5904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:45:03.312  3618  5904 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:45:03.312  3618  5904 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:45:03.312  3618  5904 D BatteryService: stay LED for fully charged
,07-05 15:45:03.312  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:45:03.317  3618  3618 I MotionRecognitionService: Plugged
07-05 15:45:03.317  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:45:03.317  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:45:03.317  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:45:03.322  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:45:03.322  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:45:03.322  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:45:03.342  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:45:03.342  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:45:03.352  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:45:03.352  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:45:03.352  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:45:08.992  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), LCD = 0
,07-05 15:45:09.962  3618  4975 E Watchdog: !@Sync 21 [07-05 15:45:09.965]
,07-05 15:45:16.997  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:45:16.997  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:45:19.017  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), LCD = 0
,07-05 15:45:29.047  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), LCD = 0
,07-05 15:45:32.087  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:45:32.087  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:45:33.402  3618  3643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:45:33.402  3618  3643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:45:33.402  3618  3643 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:45:33.402  3618  3643 D BatteryService: stay LED for fully charged
,07-05 15:45:33.407  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:45:33.407  3618  3618 I MotionRecognitionService: Plugged
07-05 15:45:33.407  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:45:33.407  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:45:33.407  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:45:33.417  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:45:33.417  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:45:33.417  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:45:33.432  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:45:33.432  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-05 15:45:33.442  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:45:33.442  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:45:33.442  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:45:39.072  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), LCD = 0
,07-05 15:45:39.972  3618  4975 E Watchdog: !@Sync 22 [07-05 15:45:39.973]
,07-05 15:45:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:45:41.607  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:45:41.607  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:45:49.102  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), LCD = 0
,07-05 15:45:59.132  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), LCD = 0
,07-05 15:46:03.507  3618  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:46:09.157  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), LCD = 0
,07-05 15:46:09.977  3618  4975 E Watchdog: !@Sync 23 [07-05 15:46:09.978]
,07-05 15:46:19.182  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), LCD = 0
,07-05 15:46:24.192  3618  3630 I art     : Background sticky concurrent mark sweep GC freed 86367(8MB) AllocSpace objects, 303(5MB) LOS objects, 32% free, 31MB/46MB, paused 3.365ms total 109.171ms
,07-05 15:46:29.217  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:46:33.607  3618  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:46:33.607  3618  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:46:33.607  3618  3644 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:46:33.612  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:46:33.612  3618  3644 D BatteryService: stay LED for fully charged
,07-05 15:46:33.617  3618  3618 I MotionRecognitionService: Plugged
07-05 15:46:33.617  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:46:33.617  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:46:33.617  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:46:33.622  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:46:33.622  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:46:33.622  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:46:33.642  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:46:33.642  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:46:33.647  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:46:33.647  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:46:33.647  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:46:39.247  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:46:39.982  3618  4975 E Watchdog: !@Sync 24 [07-05 15:46:39.984]
,07-05 15:46:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:46:41.742  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:46:41.742  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:46:49.277  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:46:59.307  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:47:03.707  3618  4894 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:47:03.707  3618  4894 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:47:03.707  3618  4894 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:47:03.707  3618  4894 D BatteryService: stay LED for fully charged
,07-05 15:47:03.707  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:47:03.712  3618  3618 I MotionRecognitionService: Plugged
07-05 15:47:03.712  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:47:03.712  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:47:03.712  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:47:03.717  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:47:03.717  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:47:03.717  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:47:03.737  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:47:03.737  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:47:03.747  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:47:03.747  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:47:03.747  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:09.337  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:47:09.987  3618  4975 E Watchdog: !@Sync 25 [07-05 15:47:09.991]
,07-05 15:47:19.362  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:47:29.387  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:47:33.797  3618  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:47:33.797  3618  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:47:33.797  3618  4438 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:47:33.797  3618  4438 D BatteryService: stay LED for fully charged
,07-05 15:47:33.802  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:47:33.807  3618  3618 I MotionRecognitionService: Plugged
07-05 15:47:33.807  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:47:33.807  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:47:33.807  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:47:33.812  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:47:33.812  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:47:33.812  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:47:33.827  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:47:33.832  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:47:33.842  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:47:33.842  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:47:33.842  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:39.412  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:47:40.002  3618  4975 E Watchdog: !@Sync 26 [07-05 15:47:40.003]
,07-05 15:47:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:47:41.857  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:47:41.857  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:47:41.937  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 61ms lastUpdatedAfter : 180433ms
,07-05 15:47:43.382  3618  5906 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
07-05 15:47:43.382  3618  5906 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-05 15:47:43.382  3618  5906 V MARsPolicyManager: updateSMDBValues
,07-05 15:47:43.387  3618  3861 E MARsDBManager: updateDBAll : begin --size 1
,07-05 15:47:43.442  3618  3861 E MARsDBManager: updateDBAll : end
,07-05 15:47:43.442  3618  3861 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-05 15:47:49.437  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:47:59.462  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:48:03.892  3618  5126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:48:03.892  3618  5126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:48:03.892  3618  5126 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:48:03.897  3618  5126 D BatteryService: stay LED for fully charged
,07-05 15:48:03.897  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:48:03.902  3618  3618 I MotionRecognitionService: Plugged
07-05 15:48:03.902  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:48:03.902  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:48:03.902  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:48:03.907  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:48:03.907  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:48:03.912  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:48:03.927  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:48:03.927  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:48:03.937  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:48:03.937  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:48:03.937  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:09.487  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:48:10.002  3618  4975 E Watchdog: !@Sync 27 [07-05 15:48:10.007]
,07-05 15:48:19.512  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:48:29.532  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:48:33.987  3618  4685 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:48:33.992  3618  4685 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:48:33.992  3618  4685 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:48:33.992  3618  4685 D BatteryService: stay LED for fully charged
,07-05 15:48:33.992  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:48:33.997  3618  3618 I MotionRecognitionService: Plugged
07-05 15:48:33.997  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:48:33.997  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:48:33.997  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:48:34.007  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:48:34.007  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:48:34.007  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:48:34.012  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:48:34.017  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:48:34.027  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:34.027  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:48:34.027  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:39.557  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:48:40.007  3618  4975 E Watchdog: !@Sync 28 [07-05 15:48:40.012]
,07-05 15:48:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:48:42.047  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:48:42.047  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:48:49.587  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:48:59.617  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:49:04.082  3618  4647 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:49:09.647  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-05 15:49:10.012  3618  4975 E Watchdog: !@Sync 29 [07-05 15:49:10.016]
,07-05 15:49:19.677  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), LCD = 0
,07-05 15:49:29.712  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), LCD = 0
,07-05 15:49:34.182  3618  5044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:49:34.182  3618  5044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:49:34.182  3618  5044 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:49:34.182  3618  5044 D BatteryService: stay LED for fully charged
,07-05 15:49:34.187  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:49:34.192  3618  3618 I MotionRecognitionService: Plugged
07-05 15:49:34.192  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:49:34.192  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:49:34.192  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:49:34.197  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:49:34.197  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:49:34.197  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-05 15:49:34.217  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:49:34.222  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
07-05 15:49:34.222  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:49:34.222  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:49:34.222  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,07-05 15:49:36.452  3618  4390 D TimaService: TIMA: TimaService scheduler is intialized. ,
,07-05 15:49:36.452  3618  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
,07-05 15:49:36.457  3618  4389 D TimaService: TimaServiceHandler.handleMessage what =1,
,07-05 15:49:39.737  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), LCD = 0
,07-05 15:49:40.017  3618  4975 E Watchdog: !@Sync 30 [07-05 15:49:40.023]
,07-05 15:49:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:49:42.202  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:49:42.202  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:49:43.287  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 15:49:43.287  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:49:43.302  3618  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 15:49:43.302  3618  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:49:45.507  3618  4400 V AlarmManager: Expired Alarm result :4
,07-05 15:49:45.542  3618  3790 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
07-05 15:49:45.547  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 15:49:45.547  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 15:49:45.547  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:49:45.572  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:49:45.572  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:49:45.582  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:45.582  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:45.582  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:49:45.582  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:45.582  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:45.587  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:45.587  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:45.592  5802  5984 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns,
,07-05 15:49:45.622  3618  5104 V AlarmManager:  remove PendingIntent] PendingIntent{f2df84f: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.647  3618  5043 V AlarmManager:  remove PendingIntent] PendingIntent{454fbdc: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.667  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:45.677  3618  4894 V AlarmManager:  remove PendingIntent] PendingIntent{51474e5: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.712  3618  4685 V AlarmManager:  remove PendingIntent] PendingIntent{371bbba: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.717  3618  5904 V AlarmManager:  remove PendingIntent] PendingIntent{a7bca6b: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.722  3618  4894 V AlarmManager:  remove PendingIntent] PendingIntent{823f9c8: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.727  3618  7316 V AlarmManager:  remove PendingIntent] PendingIntent{61c7a61: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.732  3618  4438 V AlarmManager:  remove PendingIntent] PendingIntent{f6fd986: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.737  3618  5904 V AlarmManager:  remove PendingIntent] PendingIntent{a8aa247: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.742  3618  4894 V AlarmManager:  remove PendingIntent] PendingIntent{462ea74: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.742  3618  7316 V AlarmManager:  remove PendingIntent] PendingIntent{b455b9d: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.747  3618  4438 V AlarmManager:  remove PendingIntent] PendingIntent{6e00812: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.752  3618  5904 V AlarmManager:  remove PendingIntent] PendingIntent{fc51be3: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.757  3618  4894 V AlarmManager:  remove PendingIntent] PendingIntent{9fe39e0: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.762  3618  7316 V AlarmManager:  remove PendingIntent] PendingIntent{a211499: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.762  3618  4438 V AlarmManager:  remove PendingIntent] PendingIntent{bb2935e: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.767  3618  5904 V AlarmManager:  remove PendingIntent] PendingIntent{ca3933f: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.772  3618  4894 V AlarmManager:  remove PendingIntent] PendingIntent{a3d140c: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.777  3618  7316 V AlarmManager:  remove PendingIntent] PendingIntent{5656155: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.782  3618  4438 V AlarmManager:  remove PendingIntent] PendingIntent{c90876a: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.787  3618  5904 V AlarmManager:  remove PendingIntent] PendingIntent{8c8245b: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.787  3618  5116 V AlarmManager:  remove PendingIntent] PendingIntent{1ad64f8: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.792  3618  5127 V AlarmManager:  remove PendingIntent] PendingIntent{b67bdd1: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.797  3618  3643 V AlarmManager:  remove PendingIntent] PendingIntent{7a7b036: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.797  3618  4438 V AlarmManager:  remove PendingIntent] PendingIntent{9daab37: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.802  3618  4647 V AlarmManager:  remove PendingIntent] PendingIntent{5cfd8a4: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.807  3618  5044 V AlarmManager:  remove PendingIntent] PendingIntent{59660d: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.807  3618  5113 V AlarmManager:  remove PendingIntent] PendingIntent{e3699c2: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.812  3618  7316 V AlarmManager:  remove PendingIntent] PendingIntent{e24c3d3: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.817  3618  4685 V AlarmManager:  remove PendingIntent] PendingIntent{183db10: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
07-05 15:49:45.817  3618  5104 V AlarmManager:  remove PendingIntent] PendingIntent{435609: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.822  3618  5096 V AlarmManager:  remove PendingIntent] PendingIntent{4d8900e: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.822  3618  4894 V AlarmManager:  remove PendingIntent] PendingIntent{4edca2f: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}},
,07-05 15:49:45.827  3618  5043 V AlarmManager:  remove PendingIntent] PendingIntent{c33983c: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.832  3618  3644 V AlarmManager:  remove PendingIntent] PendingIntent{4c249c5: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.832  3618  5126 V AlarmManager:  remove PendingIntent] PendingIntent{c919f1a: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.837  3618  5904 V AlarmManager:  remove PendingIntent] PendingIntent{96da4b: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:45.842  3618  5116 V AlarmManager:  remove PendingIntent] PendingIntent{7bffc28: PendingIntentRecord{fa222ae com.android.bluetooth broadcastIntent}}
,07-05 15:49:49.767  3618  6879 D SSRM:n  : SIOP:: AP = 280, PST = 279 (W:28), LCD = 0
,07-05 15:49:59.792  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:28), LCD = 0
,07-05 15:49:59.997  3618  4400 V AlarmManager: Expired Alarm result :8
,07-05 15:50:04.282  3618  5904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:50:09.817  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:28), LCD = 0
,07-05 15:50:10.017  3618  4975 E Watchdog: !@Sync 31 [07-05 15:50:10.024]
,07-05 15:50:19.842  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:28), LCD = 0
,07-05 15:50:29.872  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), LCD = 0
,07-05 15:50:34.382  3618  5126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:50:35.857  3618  4400 V AlarmManager: Expired Alarm result :8
,07-05 15:50:36.002  3618  3790 W ProcessCpuTracker: Skipping unknown process pid 11871
,07-05 15:50:39.902  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-05 15:50:40.027  3618  4975 E Watchdog: !@Sync 32 [07-05 15:50:40.030]
,07-05 15:50:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:50:42.327  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:50:42.327  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:50:42.412  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 67ms lastUpdatedAfter : 180474ms
,07-05 15:50:49.932  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-05 15:50:59.957  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-05 15:51:04.477  3618  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:51:04.477  3618  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:51:04.477  3618  3644 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:51:04.477  3618  3644 D BatteryService: stay LED for fully charged
,07-05 15:51:04.482  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:51:04.487  3618  3618 I MotionRecognitionService: Plugged
,07-05 15:51:04.487  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:51:04.487  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:51:04.487  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:51:04.502  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,07-05 15:51:04.502  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:51:04.502  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:51:04.522  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:51:04.522  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:51:04.532  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:51:04.532  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:51:04.532  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:51:09.982  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-05 15:51:10.032  3618  4975 E Watchdog: !@Sync 33 [07-05 15:51:10.038]
,07-05 15:51:20.017  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-05 15:51:30.042  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-05 15:51:34.572  3618  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:51:40.042  3618  4975 E Watchdog: !@Sync 34 [07-05 15:51:40.046]
,07-05 15:51:40.072  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-05 15:51:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:51:42.522  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:51:42.522  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:51:50.107  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-05 15:52:00.132  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-05 15:52:04.662  3618  3643 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:52:04.667  3618  3643 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:52:04.667  3618  3643 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:52:04.667  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:52:04.667  3618  3643 D BatteryService: stay LED for fully charged
,07-05 15:52:04.672  3618  3618 I MotionRecognitionService: Plugged
07-05 15:52:04.672  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:52:04.672  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:52:04.672  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:52:04.682  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:52:04.682  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:52:04.682  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:52:04.692  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:52:04.692  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:52:04.707  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:52:04.707  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:52:04.707  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:52:10.057  3618  4975 E Watchdog: !@Sync 35 [07-05 15:52:10.060]
,07-05 15:52:10.157  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-05 15:52:20.187  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-05 15:52:30.217  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-05 15:52:34.762  3618  4685 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:52:34.762  3618  4685 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:52:34.762  3618  4685 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:52:34.762  3618  4685 D BatteryService: stay LED for fully charged
,07-05 15:52:34.767  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:52:34.772  3618  3618 I MotionRecognitionService: Plugged
07-05 15:52:34.772  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:52:34.772  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:52:34.772  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:52:34.777  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:52:34.777  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:52:34.777  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:52:34.797  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:52:34.797  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:52:34.802  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:52:34.802  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:52:34.802  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:52:40.062  3618  4975 E Watchdog: !@Sync 36 [07-05 15:52:40.067]
,07-05 15:52:40.247  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-05 15:52:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:52:42.637  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:52:42.637  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:52:50.272  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-05 15:53:00.302  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-05 15:53:04.857  3618  5126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:53:10.072  3618  4975 E Watchdog: !@Sync 37 [07-05 15:53:10.075]
,07-05 15:53:10.332  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-05 15:53:20.362  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-05 15:53:30.387  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-05 15:53:34.957  3618  3644 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:53:34.957  3618  3644 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:53:34.957  3618  3644 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:53:34.957  3618  3644 D BatteryService: stay LED for fully charged
,07-05 15:53:34.957  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:53:34.967  3618  3618 I MotionRecognitionService: Plugged
07-05 15:53:34.967  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:53:34.967  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:53:34.967  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:53:34.972  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:53:34.972  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:53:34.972  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:53:34.987  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:53:34.987  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:53:34.997  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:53:34.997  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:53:34.997  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:53:40.077  3618  4975 E Watchdog: !@Sync 38 [07-05 15:53:40.082]
,07-05 15:53:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:53:40.412  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:53:42.762  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:53:42.762  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:53:42.852  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 81ms lastUpdatedAfter : 180443ms
,07-05 15:53:50.442  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:54:00.472  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:54:05.052  3618  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:54:05.052  3618  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:54:05.052  3618  4438 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:54:05.052  3618  4438 D BatteryService: stay LED for fully charged
,07-05 15:54:05.057  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:54:05.062  3618  3618 I MotionRecognitionService: Plugged
07-05 15:54:05.062  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:54:05.062  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:54:05.062  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:54:05.072  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:54:05.072  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:54:05.072  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:54:05.087  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,07-05 15:54:05.087  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:54:05.097  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:54:05.097  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:54:05.097  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:54:10.087  3618  4975 E Watchdog: !@Sync 39 [07-05 15:54:10.094]
,07-05 15:54:10.497  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:54:20.527  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:54:30.552  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:54:35.147  3618  4647 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:54:35.147  3618  4647 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:54:35.147  3618  4647 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:54:35.147  3618  4647 D BatteryService: stay LED for fully charged
,07-05 15:54:35.147  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:54:35.152  3618  3618 I MotionRecognitionService: Plugged
07-05 15:54:35.152  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:54:35.152  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:54:35.152  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:54:35.162  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:54:35.162  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:54:35.162  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:54:35.177  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:54:35.177  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:54:35.187  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:54:35.187  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:54:35.187  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:54:36.457  3618  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 15:54:36.457  3618  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:54:36.457  3618  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:54:36.852  3618  3774 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 15:54:40.077  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 15:54:40.077  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:54:40.092  3618  4975 E Watchdog: !@Sync 40 [07-05 15:54:40.100]
07-05 15:54:40.097  3618  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 15:54:40.097  3618  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:54:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:54:40.582  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:54:42.957  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:54:42.957  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:54:50.612  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:55:00.637  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:55:05.242  3618  5904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:55:10.097  3618  4975 E Watchdog: !@Sync 41 [07-05 15:55:10.101]
,07-05 15:55:10.662  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:55:20.687  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:55:30.717  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:55:35.342  3618  5126 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:55:35.342  3618  5126 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:55:35.342  3618  5126 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:55:35.342  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:55:35.342  3618  5126 D BatteryService: stay LED for fully charged
,07-05 15:55:35.347  3618  3618 I MotionRecognitionService: Plugged
07-05 15:55:35.347  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:55:35.347  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:55:35.347  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:55:35.357  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:55:35.357  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:55:35.357  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:55:35.377  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:55:35.377  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:55:35.387  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:55:35.387  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:55:35.387  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:55:40.107  3618  4975 E Watchdog: !@Sync 42 [07-05 15:55:40.109]
,07-05 15:55:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:55:40.747  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:55:43.102  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:55:43.102  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:55:50.777  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:56:00.807  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:56:05.432  3618  5104 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:56:10.112  3618  4975 E Watchdog: !@Sync 43 [07-05 15:56:10.115]
,07-05 15:56:10.832  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:56:20.862  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:56:30.892  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:56:35.532  3618  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:56:35.532  3618  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:56:35.532  3618  4438 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:56:35.532  3618  4438 D BatteryService: stay LED for fully charged
,07-05 15:56:35.532  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:56:35.537  3618  3618 I MotionRecognitionService: Plugged
07-05 15:56:35.537  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:56:35.537  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:56:35.537  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:56:35.547  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:56:35.547  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:56:35.547  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:56:35.567  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:56:35.567  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:56:35.572  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:56:35.572  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:56:35.572  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:56:40.122  3618  4975 E Watchdog: !@Sync 44 [07-05 15:56:40.123]
,07-05 15:56:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:56:40.917  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:56:43.207  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:56:43.207  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:56:43.287  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 69ms lastUpdatedAfter : 180435ms
,07-05 15:56:50.937  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:57:00.962  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:57:05.632  3618  5096 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:57:05.632  3618  5096 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:57:05.632  3618  5096 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:57:05.632  3618  5096 D BatteryService: stay LED for fully charged
,07-05 15:57:05.637  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:57:05.642  3618  3618 I MotionRecognitionService: Plugged
07-05 15:57:05.642  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:57:05.642  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:57:05.642  3618  3618 D MotionRecognitionService: skip setTransmitPower. ,
,07-05 15:57:05.647  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 15:57:05.647  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:57:05.652  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:57:05.667  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:57:05.667  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:57:05.677  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 15:57:05.677  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:57:05.677  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:57:10.122  3618  4975 E Watchdog: !@Sync 45 [07-05 15:57:10.128]
,07-05 15:57:10.992  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:57:21.022  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:57:31.052  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:57:35.727  3618  5044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:57:35.732  3618  5044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:57:35.732  3618  5044 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:57:35.732  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:57:35.737  3618  3618 I MotionRecognitionService: Plugged
07-05 15:57:35.737  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:57:35.737  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:57:35.737  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:57:35.742  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:57:35.742  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:57:35.742  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-05 15:57:35.747  3618  5044 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 17ms
07-05 15:57:35.747  3618  5044 D BatteryService: stay LED for fully charged,
,07-05 15:57:35.762  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 15:57:35.762  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:57:35.772  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:57:35.772  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:57:35.772  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:57:40.127  3618  4975 E Watchdog: !@Sync 46 [07-05 15:57:40.133]
,07-05 15:57:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:57:41.077  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:57:43.387  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:57:43.387  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:57:51.107  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:58:01.127  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:58:05.822  3618  4894 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:58:10.132  3618  4975 E Watchdog: !@Sync 47 [07-05 15:58:10.135]
,07-05 15:58:11.157  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:58:21.187  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:58:31.212  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:58:35.917  3618  5904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:58:35.917  3618  5904 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:58:35.917  3618  5904 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:58:35.917  3618  5904 D BatteryService: stay LED for fully charged
,07-05 15:58:35.917  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:58:35.922  3618  3618 I MotionRecognitionService: Plugged
07-05 15:58:35.922  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:58:35.922  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:58:35.922  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:58:35.932  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:58:35.932  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:58:35.932  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:58:35.947  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:58:35.947  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:58:35.962  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:58:35.962  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:58:35.962  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:58:40.137  3618  4975 E Watchdog: !@Sync 48 [07-05 15:58:40.139]
,07-05 15:58:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:58:41.237  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:58:43.512  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:58:43.512  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:58:51.262  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:59:01.287  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:59:04.637  3618  3630 I art     : Background sticky concurrent mark sweep GC freed 45611(7MB) AllocSpace objects, 384(7MB) LOS objects, 32% free, 31MB/46MB, paused 4.058ms total 102.201ms
,07-05 15:59:06.037  3618  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:59:06.037  3618  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 15:59:06.037  3618  5116 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 15:59:06.037  3618  5116 D BatteryService: stay LED for fully charged
07-05 15:59:06.037  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:59:06.047  3618  3618 I MotionRecognitionService: Plugged
07-05 15:59:06.047  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 15:59:06.047  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:59:06.047  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:59:06.057  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:59:06.057  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:59:06.057  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:59:06.067  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:59:06.067  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:59:06.077  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:59:06.077  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:59:06.077  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:59:10.142  3618  4975 E Watchdog: !@Sync 49 [07-05 15:59:10.145]
,07-05 15:59:11.317  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:59:21.342  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:59:31.377  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:59:36.137  3618  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:59:36.452  3618  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 15:59:36.457  3618  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-05 15:59:36.457  3618  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:59:40.147  3618  4975 E Watchdog: !@Sync 50 [07-05 15:59:40.154]
,07-05 15:59:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 15:59:41.402  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 15:59:43.357  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 15:59:43.357  3618  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:59:43.372  3618  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 15:59:43.372  3618  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:59:43.402  3618  5906 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
07-05 15:59:43.402  3618  5906 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-05 15:59:43.402  3618  5906 V MARsPolicyManager: updateSMDBValues
07-05 15:59:43.402  3618  3861 E MARsDBManager: updateDBAll : begin --size 0
07-05 15:59:43.402  3618  3861 E MARsDBManager: updateDBAll : end
,07-05 15:59:43.632  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 15:59:43.632  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 15:59:43.712  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 67ms lastUpdatedAfter : 180422ms
,07-05 15:59:51.427  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:00:01.452  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:00:06.227  3618  5044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:00:10.152  3618  4975 E Watchdog: !@Sync 51 [07-05 16:00:10.156]
,07-05 16:00:11.477  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:00:21.502  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:00:31.532  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:00:36.322  3618  5104 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:00:36.327  3618  5104 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 16:00:36.327  3618  5104 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 16:00:36.327  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 16:00:36.327  3618  5104 D BatteryService: stay LED for fully charged
,07-05 16:00:36.332  3618  3618 I MotionRecognitionService: Plugged
07-05 16:00:36.332  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 16:00:36.332  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 16:00:36.332  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 16:00:36.342  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:00:36.342  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:00:36.342  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 16:00:36.362  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 16:00:36.362  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 16:00:36.367  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 16:00:36.372  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 16:00:36.372  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:00:40.157  3618  4975 E Watchdog: !@Sync 52 [07-05 16:00:40.164]
,07-05 16:00:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 16:00:41.567  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:00:43.792  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 16:00:43.792  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 16:00:51.592  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:01:01.617  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:01:06.422  3618  5904 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 16:01:06.422  3618  5904 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 16:01:06.422  3618  5904 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 16:01:06.422  3618  5904 D BatteryService: stay LED for fully charged
,07-05 16:01:06.422  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 16:01:06.427  3618  3618 I MotionRecognitionService: Plugged
07-05 16:01:06.427  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 16:01:06.432  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 16:01:06.432  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 16:01:06.437  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:01:06.437  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:01:06.437  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 16:01:06.452  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 16:01:06.452  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 16:01:06.462  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 16:01:06.462  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 16:01:06.462  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:10.167  3618  4975 E Watchdog: !@Sync 53 [07-05 16:01:10.171]
,07-05 16:01:11.642  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:01:21.667  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:01:31.692  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:01:36.522  3618  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 16:01:36.522  3618  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-05 16:01:36.522  3618  5116 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-05 16:01:36.522  3618  5116 D BatteryService: stay LED for fully charged
,07-05 16:01:36.522  3618  3618 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 16:01:36.527  3618  3618 I MotionRecognitionService: Plugged
07-05 16:01:36.527  3618  3618 D MotionRecognitionService:   cableConnection= 1
07-05 16:01:36.532  3618  3618 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 16:01:36.532  3618  3618 D MotionRecognitionService: skip setTransmitPower. 
,07-05 16:01:36.537  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:01:36.537  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:01:36.537  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 16:01:36.557  5802  5802 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 16:01:36.557  5802  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 16:01:36.562  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 16:01:36.562  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 16:01:36.562  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:40.177  3618  4975 E Watchdog: !@Sync 54 [07-05 16:01:40.178]
,07-05 16:01:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 16:01:41.727  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:01:43.942  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 16:01:43.942  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 16:01:51.747  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:02:01.772  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:02:06.612  3618  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:02:10.177  3618  4975 E Watchdog: !@Sync 55 [07-05 16:02:10.183]
,07-05 16:02:11.802  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:02:21.832  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:02:31.857  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:02:36.707  3618  5044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:02:40.187  3618  4975 E Watchdog: !@Sync 56 [07-05 16:02:40.191]
,07-05 16:02:40.362  2954  5135 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-05 16:02:41.887  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-05 16:02:44.062  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-05 16:02:44.062  4977  5047 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-05 16:02:44.142  4977  5047 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 72ms lastUpdatedAfter : 180431ms
,07-05 16:02:51.917  3618  6879 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,TIME-OUT KILL (timeout was 1401000ms)
```
