#### Test 72145431fdae11f_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
06-30 10:38:13.825  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:18), CUR = 8, LCD = 0
,06-30 10:38:15.065  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
06-30 10:38:15.480 10602 10602 I FIPS_bssl: FIPS approved mode (1) | 10602 | app_process
06-30 10:38:15.485 10602 10602 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:38:15.490 10602 10602 D AndroidRuntime: CheckJNI is OFF
06-30 10:38:15.490 10602 10602 D AndroidRuntime: readGMSProperty: start
06-30 10:38:15.490 10602 10602 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:38:15.490 10602 10602 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:38:15.490 10602 10602 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:38:15.490 10602 10602 D AndroidRuntime: readGMSProperty: end
06-30 10:38:15.490 10602 10602 D AndroidRuntime: addProductProperty: start
06-30 10:38:15.515 10602 10602 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:38:15.545 10602 10602 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:38:15.550 10602 10602 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:38:15.565 10602 10602 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:38:15.605  3557  5769 D GameManagerService: identifyGamePackage. com.test.thalitest
06-30 10:38:15.605  3557  5769 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
06-30 10:38:15.610  3557  5769 D ActivityManager: mDVFSHelper.acquire()
06-30 10:38:15.615  3557  5769 V WindowManager: addAppToken: AppWindowToken{d52f83d token=Token{2289594 ActivityRecord{7bd85e7 u0 com.test.thalitest/.MainActivity t69}}} to stack=1 task=69 at 0
06-30 10:38:15.630  3557  3798 D SecWifiDisplayUtil: Metadata value : none
06-30 10:38:15.630  3557  3798 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ab5f1f5 V.E...... R.....ID 0,0-0,0}
06-30 10:38:15.630  3557  3798 D ISSUE_DEBUG: InputChannelName : 313b5fb Starting com.test.thalitest
06-30 10:38:15.635 10618 10618 E Zygote  : v2
06-30 10:38:15.635 10618 10618 I libpersona: KNOX_SDCARD checking this for 10007
06-30 10:38:15.635 10618 10618 I libpersona: KNOX_SDCARD not a persona
06-30 10:38:15.635 10618 10618 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 10:38:15.635 10618 10618 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:15.635  3557  5769 I ActivityManager: Start proc 10618:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
06-30 10:38:15.635  3557  5769 D InputDispatcher: Focused application set to: xxxx
06-30 10:38:15.640 10618 10618 E Zygote  : accessInfo : 0
06-30 10:38:15.640  3557  5769 D InputDispatcher: Focus left window: 6797
06-30 10:38:15.640 10618 10618 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 10:38:15.640 10602 10602 D AndroidRuntime: Shutting down VM
06-30 10:38:15.640  3557  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 10:38:15.640  4515  4515 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-30 10:38:15.640  3557  3724 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{14e33d8 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-30 10:38:15.650  2904  2904 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
06-30 10:38:15.670 10618 10618 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:38:15.670 10618 10618 D ActivityThread: Added TimaKeyStore provider
06-30 10:38:15.670  3557  3798 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3557 uid:1000
06-30 10:38:15.670  3557  3798 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:15.670  3557  3798 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3557 uid:1000
06-30 10:38:15.670  3557  3798 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 10:38:15.670  3557  3798 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-30 10:38:15.675  3557  4887 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 10:38:15.675  3557  4887 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 10:38:15.675  3557  3724 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{313b5fb u0 d0 Starting com.test.thalitest}
06-30 10:38:15.675  4515  4515 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 10:38:15.685  3557  4887 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 10:38:15.695  3557  3557 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
06-30 10:38:15.695  3557  3720 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 10:38:15.720  2904  3010 D libEGL  : eglTerminate EGLDisplay = 0xb6901624
06-30 10:38:15.720  2904  3012 D libEGL  : eglTerminate EGLDisplay = 0xb667f624
06-30 10:38:15.720  2904  3012 D libEGL  : eglTerminate EGLDisplay = 0xb667f624
06-30 10:38:15.725  2904  4413 I SurfaceFlinger: id=11 Removed VSBConnecti (7/11)
06-30 10:38:15.725  2904  3010 I SurfaceFlinger: id=11 Removed VSBConnecti (-2/11)
06-30 10:38:15.725  2904  3010 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
06-30 10:38:15.730  2904  3012 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
06-30 10:38:15.730  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbed48474
06-30 10:38:15.730  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbed48474
06-30 10:38:15.735  2904  4413 I SurfaceFlinger: id=12 Removed VSBConnecti (4/9)
06-30 10:38:15.735  2904  3010 I SurfaceFlinger: id=12 Removed VSBConnecti (-2/9)
06-30 10:38:15.740  6797  6797 V ActivityThread: updateVisibility : ActivityRecord{71833f1 token=android.os.BinderProxy@8eca55a {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 10:38:15.740  3557  3798 V WindowStateAnimator: Finishing drawing window Window{313b5fb u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 10:38:15.740  5184  5184 V ActivityThread: updateVisibility : ActivityRecord{9d5849a token=android.os.BinderProxy@470e883 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 10:38:15.740  5184  5184 D Launcher: onTrimMemory. Level: 20
06-30 10:38:15.750  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbed48474
06-30 10:38:15.750  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbed4840c
,06-30 10:38:16.005  3557  4887 I WindowManager: Screenshot max retries 4 of Token{2289594 ActivityRecord{7bd85e7 u0 com.test.thalitest/.MainActivity t69}} appWin=Window{313b5fb u0 d0 Starting com.test.thalitest} drawState=2
,06-30 10:38:16.030  3557  3720 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 10:38:16.040  3557  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,06-30 10:38:16.045  3557  3796 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 10:38:16.050  3557  6655 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:38:16.060  3557  6655 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:38:16.095 10618 10618 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,06-30 10:38:16.130 10618 10618 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-30 10:38:16.140 10618 10618 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 2977-2980)
06-30 10:38:16.140 10618 10618 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 10:38:16.155 10618 10632 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,06-30 10:38:16.160 10618 10618 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd98b39}
06-30 10:38:16.160 10618 10618 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 10:38:16.160 10618 10618 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:38:16.170 10618 10618 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-30 10:38:16.190 10618 10633 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,06-30 10:38:16.210 10618 10618 D libEGL  : eglInitialize EGLDisplay = 0xbeda1e7c
,06-30 10:38:16.240  3557  3582 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,06-30 10:38:16.245  3557  3582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,06-30 10:38:16.310 10618 10618 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,06-30 10:38:16.325 10618 10618 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:38:16.325 10618 10618 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,06-30 10:38:16.325 10618 10618 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,06-30 10:38:16.325 10618 10618 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,06-30 10:38:16.350 10618 10618 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,06-30 10:38:16.360 10618 10618 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung,
,06-30 10:38:16.450 10618 10618 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:38:16.455 10618 10618 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{889eade I.E...... R.....ID 0,0-0,0}
,06-30 10:38:16.460 10618 10669 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:38:16.465  3557  7043 D ISSUE_DEBUG: InputChannelName : e3d878c com.test.thalitest/com.test.thalitest.MainActivity
,06-30 10:38:16.470  3557  5075 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 10:38:16.470  3557  5075 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:38:16.470  3557  3557 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 10:38:16.470  3557  3557 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 10:38:16.495 10618 10618 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 10618
,06-30 10:38:16.500  3557  5217 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/10618 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 10:38:16.515 10618 10632 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,06-30 10:38:16.520 10618 10618 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:38:16.535  2904  2904 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,06-30 10:38:16.555  3557  7042 D InputDispatcher: Focus entered window: 10618
,06-30 10:38:16.555  3557  3798 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3557 uid:1000
06-30 10:38:16.555  3557  3798 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:16.555  3557  3798 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3557 uid:1000
06-30 10:38:16.555  3557  3798 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 10:38:16.555 10618 10669 D libEGL  : eglInitialize EGLDisplay = 0x9cebf7c4
06-30 10:38:16.555 10618 10669 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:38:16.565 10618 10669 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,06-30 10:38:16.570 10618 10618 V ActivityThread: updateVisibility : ActivityRecord{33fddb token=android.os.BinderProxy@3e91a19 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-30 10:38:16.575 10618 10618 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:38:16.640 10618 10674 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:38:16.640 10618 10674 D libEGL  : eglInitialize EGLDisplay = 0x9c5fc3ec
,06-30 10:38:16.655  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbed4840c
,06-30 10:38:16.655  3557  7044 V WindowStateAnimator: Finishing drawing window Window{e3d878c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
06-30 10:38:16.655 10618 10618 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,06-30 10:38:16.660  3557  3798 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:38:16.660  3557  3557 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 10:38:16.660  3557  3798 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +655ms (total +1s47ms)
,06-30 10:38:16.660 10618 10618 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 10:38:16.665  3557  5073 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 10:38:16.665  3557  3798 D ActivityManager: mDVFSHelper.release()
06-30 10:38:16.665  3557  3798 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7bd85e7 u0 com.test.thalitest/.MainActivity t69} time:273505
06-30 10:38:16.665  3557  3557 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:38:16.670  3557  3798 D ViewRootImpl: #3 mView = null
06-30 10:38:16.670 10618 10618 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 10:38:16.680  2904  3012 I SurfaceFlinger: id=13 Removed uhalitest (7/9),
06-30 10:38:16.680  2904  3010 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,06-30 10:38:16.685  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbed48474
,06-30 10:38:16.695  3557  7042 V WindowStateAnimator: Finishing drawing window Window{e3d878c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,06-30 10:38:16.695 10618 10618 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3e91a19 time:273539
,06-30 10:38:16.705  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbed4840c
,06-30 10:38:16.710 10618 10618 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10618
,06-30 10:38:16.885 10618 10618 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:38:17.065 10618 10682 D jxcore_app_log: JniHelper::setJavaVM(0xb4834000), pthread_self() = -1724909264
,06-30 10:38:17.070 10618 10682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:38:17.070 10618 10682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:38:17.070 10618 10682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:38:17.070 10618 10682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:38:17.070 10618 10682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:38:17.070 10618 10682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd7bb89 added. We now have 1 listener(s)
,06-30 10:38:17.070 10618 10682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,06-30 10:38:17.075 10618 10682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
06-30 10:38:17.075 10618 10682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:38:17.075 10618 10682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:38:17.075 10618 10682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b295bbc added. We now have 1 listener(s)
06-30 10:38:17.075 10618 10682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:38:17.075 10618 10682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:38:17.075 10618 10682 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:38:17.080 10618 10682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,06-30 10:38:17.080 10618 10682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:38:17.080 10618 10682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:38:17.080 10618 10682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:38:17.080 10618 10682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:38:17.080 10618 10682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,06-30 10:38:17.080 10618 10682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:38:17.080 10618 10682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:38:17.085 10618 10682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:38:17.085 10618 10682 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:38:17.085 10618 10682 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:38:17.110 10618 10618 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:38:17.465 10618 10683 W jxcore-log: Initializing JXcore engine
06-30 10:38:17.465 10618 10683 W jxcore-log: JXcore engine is ready
,06-30 10:38:17.475  4702  4702 D Recents : onTaskStackChanged
,06-30 10:38:17.490  5698  5698 E audit   : type=1400 msg=audit(1467275897.490:260): avc:  denied  { ioctl } for  pid=10683 comm="Thread-1023" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3235 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 10:38:17.490  5698  5698 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:17.490  5698  5698 E audit   : type=1300 msg=audit(1467275897.490:260): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=979ff3c8 items=0 ppid=2962 ppcomm=main pid=10683 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1023" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:38:17.490  5698  5698 E audit   : type=1327 msg=audit(1467275897.490:260): proctitle="com.test.thalitest"
06-30 10:38:17.490  5698  5698 E audit   : type=1320 msg=audit(1467275897.490:260): 
06-30 10:38:17.490  5698  5698 E audit   : type=1400 msg=audit(1467275897.490:261): avc:  denied  { ioctl } for  pid=10683 comm="Thread-1023" path="socket:[35477]" dev="sockfs" ino=35477 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
06-30 10:38:17.490  5698  5698 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:17.490  5698  5698 E audit   : type=1300 msg=audit(1467275897.490:261): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=979ff3c8 items=0 ppid=2962 ppcomm=main pid=10683 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1023" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:38:17.490  5698  5698 E audit   : type=1327 msg=audit(1467275897.490:261): proctitle="com.test.thalitest"
06-30 10:38:17.490  5698  5698 E audit   : type=1320 msg=audit(1467275897.490:261): 
,06-30 10:38:17.495 10618 10683 W jxcore-log: Starting JXcore engine
,06-30 10:38:17.545 10618 10683 W jxcore-log: Platform android
06-30 10:38:17.545 10618 10683 W jxcore-log: 
06-30 10:38:17.545 10618 10683 W jxcore-log: Process ARCH arm
06-30 10:38:17.545 10618 10683 W jxcore-log: 
,06-30 10:38:17.635 10618 10683 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:38:17.635 10618 10683 I jxcore-log: 
06-30 10:38:17.635 10618 10683 W jxcore-log: JXcore engine is started
,06-30 10:38:17.640 10618 10682 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:38:17.640  3557  4887 D GameManagerService: identifyGamePackage. com.android.packageinstaller
06-30 10:38:17.640  3557  4887 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.android.packageinstaller)
,06-30 10:38:17.645  3557  4887 D ActivityManager: mDVFSHelper.acquire()
,06-30 10:38:17.645  3557  4887 V WindowManager: addAppToken: AppWindowToken{f7ebbc token=Token{6893baf ActivityRecord{ddcd78e u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}}} to stack=1 task=69 at 1
,06-30 10:38:17.655 10684 10684 E Zygote  : v2
06-30 10:38:17.655 10684 10684 I libpersona: KNOX_SDCARD checking this for 10141
06-30 10:38:17.655 10684 10684 I libpersona: KNOX_SDCARD not a persona
,06-30 10:38:17.655 10684 10684 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 10:38:17.655 10684 10684 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:38:17.655 10684 10684 E Zygote  : accessInfo : 0
06-30 10:38:17.655 10684 10684 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,06-30 10:38:17.655  3557  4887 I ActivityManager: Start proc 10684:com.android.packageinstaller/u0a141 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 10:38:17.655  3557  4887 D InputDispatcher: Focused application set to: xxxx
06-30 10:38:17.655  3557  4887 D InputDispatcher: Focus left window: 10618
,06-30 10:38:17.655 10618 10682 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 10:38:17.660  3557  3798 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3557 uid:1000
06-30 10:38:17.660  3557  3798 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:17.660  3557  3798 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3557 uid:1000
06-30 10:38:17.660  3557  3798 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:38:17.665 10684 10684 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:38:17.665 10684 10684 D ActivityThread: Added TimaKeyStore provider
,06-30 10:38:17.670  3557  5075 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 10:38:17.675  3557  3557 D GameManagerService: NotifyRunnable. pkg: com.android.packageinstaller, type: 4, isMinimized: false, isTunableApp: false
06-30 10:38:17.675  3557  3720 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 10:38:17.975  3557  5075 I WindowManager: Screenshot max retries 4 of Token{6893baf ActivityRecord{ddcd78e u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}} appWin=Window{e3d878c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 10:38:17.975  3557  3720 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 10:38:17.985  3557  6655 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:38:17.995 10684 10684 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 10:38:18.145 10684 10684 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:38:18.145 10684 10684 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c308d23 I.E...... R.....I. 0,0-0,0}
,06-30 10:38:18.150 10684 10696 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:38:18.150  3557  4439 D ISSUE_DEBUG: InputChannelName : 846a2c1 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-30 10:38:18.150  3557  5769 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 10:38:18.150  3557  5769 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:38:18.155  3557  3557 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:38:18.155  3557  3557 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 10:38:18.155  3557  3557 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 10:38:18.175  2904  2904 I SurfaceFlinger: id=15 createSurf (193x193),1 flag=4, HrantPermis
,06-30 10:38:18.180  3557  3724 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{846a2c1 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-30 10:38:18.180  4515  4515 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 10:38:18.195  3557  7043 D InputDispatcher: Focus entered window: 10684
,06-30 10:38:18.195  3557  3798 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3557 uid:1000
,06-30 10:38:18.195  3557  3798 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:18.195  3557  3798 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3557 uid:1000
06-30 10:38:18.195  3557  3798 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:38:18.200 10684 10696 D libEGL  : eglInitialize EGLDisplay = 0xae9ab7c4
,06-30 10:38:18.200 10684 10696 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:38:18.210 10684 10696 D mali_winsys: new_window_surface returns 0x3000,  [1528x2656]-format:1,
,06-30 10:38:18.220 10684 10684 V ActivityThread: updateVisibility : ActivityRecord{744e538 token=android.os.BinderProxy@5797652 {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 10:38:18.220 10684 10684 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 10:38:18.220  3557  5768 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 10:38:18.225  5575  5575 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 10:38:18.245 10684 10684 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:38:18.325  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbed4840c
,06-30 10:38:18.335  3557  5198 V WindowStateAnimator: Finishing drawing window Window{846a2c1 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING,
,06-30 10:38:18.340 10684 10684 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5797652 time:275182
,06-30 10:38:18.345  3557  3798 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 10:38:18.345  3557  3557 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:38:18.345  3557  3557 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:38:18.355  3557  3798 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +376ms (total +708ms)
,06-30 10:38:18.355  3557  3798 D ActivityManager: mDVFSHelper.release()
06-30 10:38:18.355  3557  3798 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ddcd78e u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69} time:275196
,06-30 10:38:18.630  3557  4498 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/69_task.xml.bak
,06-30 10:38:18.905  3557  5073 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:18.905  3557  5073 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:38:18.905  3557  5073 D BatteryService: online:4, current avg:-7, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:38:18.905  3557  5073 D BatteryService: stay LED for fully charged
06-30 10:38:18.905  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:18.915  3557  3557 I MotionRecognitionService: Plugged
,06-30 10:38:18.915  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:38:18.915  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:38:18.915  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:38:18.920  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:38:18.920  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:18.925  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:18.930  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:18.950  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:18.950  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:19.160  4702  4702 D Recents : onTaskStackChanged
,06-30 10:38:23.865  3557  6655 D SSRM:n  : SIOP:: AP = 280, PST = 273 (W:16), CUR = -7, LCD = 0
,06-30 10:38:24.010  3557  6655 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:38:25.645  3557  3855 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 10:38:25.680  3557  3855 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 10:38:28.760  3557  4999 E Watchdog: !@Sync 9 [06-30 10:38:28.762]
,06-30 10:38:33.890  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:16), CUR = -7, LCD = 0
,06-30 10:38:35.070  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:43.915  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:16), CUR = -7, LCD = 0
,06-30 10:38:48.995  3557  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:38:48.995  3557  4439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:38:48.995  3557  4439 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:38:48.995  3557  4439 D BatteryService: stay LED for fully charged
,06-30 10:38:48.995  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:38:49.000  3557  3557 I MotionRecognitionService: Plugged
06-30 10:38:49.000  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:38:49.000  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:38:49.000  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:38:49.005  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:38:49.005  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:38:49.010  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:49.035  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:49.035  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:49.035  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:53.955  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:16), LCD = 0
,06-30 10:38:55.075  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:55.295  3557  4389 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:38:55.295  3557  4388 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:38:55.305  3557  4389 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:38:55.320  3557  4389 I TLC_TIMA_PKM_initialize: initializing...
06-30 10:38:55.320  3557  4389 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
06-30 10:38:55.320  3557  4389 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: root = 0, root_len = 1
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: device_id = 0x0
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: tlc_open() was called
06-30 10:38:55.320  3557  4389 I TZ: mc_tlc_communication: Opening MobiCore device
,06-30 10:38:55.330  3557  4389 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,06-30 10:38:55.335  3557  4389 I TZ: mc_tlc_communication: Opening the session
,06-30 10:38:55.355  3557  4389 I TZ: mc_tlc_communication: tlc_open() succeeded
,06-30 10:38:55.365  3557  4389 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 10:38:58.765  3557  4999 E Watchdog: !@Sync 10 [06-30 10:38:58.768]
,06-30 10:38:59.140  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:38:59.140  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:38:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:39:02.415  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:39:02.420  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:39:02.435  3557  4389 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:39:02.435  3557  4389 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:39:03.985  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:18), LCD = 0
,06-30 10:39:14.020  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:18), LCD = 0
,06-30 10:39:15.075  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:19.100  3557  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:24.055  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:18), LCD = 0
,06-30 10:39:24.895  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:24.920  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:24.925  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:24.965  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:39:24.965  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:39:24.970  2914  4369 D EnterpriseController: netId is 0
06-30 10:39:24.970  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 10:39:25.080  3557  3569 I art     : Background partial concurrent mark sweep GC freed 66387(5MB) AllocSpace objects, 126(2MB) LOS objects, 33% free, 30MB/45MB, paused 3.285ms total 213.732ms
,06-30 10:39:28.775  3557  4999 E Watchdog: !@Sync 11 [06-30 10:39:28.777]
,06-30 10:39:32.420  3557  4400 V AlarmManager: Expired Alarm result :4
,06-30 10:39:32.450  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:39:32.450  4515  4515 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 10:39:32.450  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:39:32.465  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 10:39:32.465  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 10:39:32.485  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:32.485  3557  5103 D NtpTrustedTime: forceRefresh: no connectivity
06-30 10:39:32.485  3557  5103 V AlarmManager:  remove PendingIntent] PendingIntent{3c39197: PendingIntentRecord{26b2f84 android broadcastIntent}}
,06-30 10:39:32.490  3557  5103 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 10:39:32.495  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:32.495  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:32.505  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:32.505  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:32.515  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:32.515  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:32.540  8639  8639 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,06-30 10:39:32.540  8639  8639 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
,06-30 10:39:32.555  8639  8639 V GCMBaseIntentService: Acquiring wakelock
,06-30 10:39:32.575  8639  8639 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-10
,06-30 10:39:32.575  8639 10787 V GCMRegistrar: Unregistering app flipboard.app
,06-30 10:39:32.600  8639 10787 V GCMBaseIntentService: Releasing wakelock
,06-30 10:39:32.630  5693  7050 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,06-30 10:39:32.660  5693  7050 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:39:32.660  5693  7050 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:39:32.660  2914  4369 D EnterpriseController: netId is 0
06-30 10:39:32.660  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10014
,06-30 10:39:32.680  3557  3720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d2c133 u0 com.google.android.c2dm.intent.REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a8ce05 8639:flipboard.app/u0a119}
,06-30 10:39:32.680  8639  8639 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
06-30 10:39:32.680  8639  8639 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 10:39:32.680  8639  8639 V GCMBaseIntentService: Acquiring wakelock
,06-30 10:39:32.700  8639  8639 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-11
,06-30 10:39:32.700  8639 10791 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
06-30 10:39:32.700  8639 10791 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
06-30 10:39:32.700  8639 10791 D GCMBaseIntentService: Scheduling registration retry, backoff = 126761 (192000)
,06-30 10:39:32.725  8639 10791 V GCMBaseIntentService: Releasing wakelock
,06-30 10:39:32.735  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:34.090  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:18), LCD = 0
,06-30 10:39:35.080  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:44.115  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:20), LCD = 0
,06-30 10:39:49.185  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:39:49.185  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
,06-30 10:39:49.190  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:39:49.190  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:39:49.190  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:39:49.195  3557  3557 I MotionRecognitionService: Plugged
06-30 10:39:49.195  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:39:49.195  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:39:49.195  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:39:49.205  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:39:49.205  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:39:49.205  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:49.230  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:49.230  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:49.230  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:54.150  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:20), LCD = 0
,06-30 10:39:55.085  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:58.785  3557  4999 E Watchdog: !@Sync 12 [06-30 10:39:58.786]
,06-30 10:39:59.250  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:39:59.250  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:39:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:39:59.995  3557  4400 V AlarmManager: Expired Alarm result :8
,06-30 10:40:04.185  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:20), LCD = 0
,06-30 10:40:14.215  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:20), LCD = 0
,06-30 10:40:15.085  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:19.285  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:40:19.285  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:40:19.285  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:40:19.285  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:40:19.285  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:19.295  3557  3557 I MotionRecognitionService: Plugged
06-30 10:40:19.295  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:40:19.295  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:40:19.295  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:40:19.300  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:40:19.300  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:40:19.300  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:19.325  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:40:19.325  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:19.325  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:24.240  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), LCD = 0
,06-30 10:40:28.790  3557  4999 E Watchdog: !@Sync 13 [06-30 10:40:28.794]
,06-30 10:40:34.270  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), LCD = 0
,06-30 10:40:35.090  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:44.300  3557  6655 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), LCD = 0
,06-30 10:40:49.385  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:40:49.385  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:40:49.385  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:40:49.385  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:40:49.385  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:49.395  3557  3557 I MotionRecognitionService: Plugged
06-30 10:40:49.395  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:40:49.395  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:40:49.395  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:40:49.400  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:40:49.400  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:40:49.400  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:49.410  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:49.425  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:40:49.425  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:54.330  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 270 (W:22), LCD = 0
,06-30 10:40:55.095  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:58.800  3557  4999 E Watchdog: !@Sync 14 [06-30 10:40:58.802]
,06-30 10:40:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:40:59.380  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:40:59.380  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:40:59.450  4892  4966 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 62ms lastUpdatedAfter : 180429ms
,06-30 10:41:04.365  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:24), LCD = 0
,06-30 10:41:14.400  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:24), LCD = 0
,06-30 10:41:15.095  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:19.475  3557  5198 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:41:19.480  3557  5198 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:41:19.480  3557  5198 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:41:19.480  3557  5198 D BatteryService: stay LED for fully charged
,06-30 10:41:19.480  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:41:19.485  3557  3557 I MotionRecognitionService: Plugged
06-30 10:41:19.485  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:41:19.485  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:41:19.485  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:41:19.490  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:41:19.490  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:41:19.490  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:19.515  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:41:19.515  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:41:19.515  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:24.430  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:24), LCD = 0
,06-30 10:41:28.805  3557  4999 E Watchdog: !@Sync 15 [06-30 10:41:28.807]
,06-30 10:41:34.460  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:24), LCD = 0
,06-30 10:41:35.100  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:39.470  3557  4400 V AlarmManager: Expired Alarm result :8
,06-30 10:41:44.505  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:26), LCD = 0
,06-30 10:41:47.795  2978  2978 I bootchecker: bootchecker wake up!!
,06-30 10:41:49.575  3557  5198 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:54.535  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:26), LCD = 0
,06-30 10:41:55.100  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:58.810  3557  4999 E Watchdog: !@Sync 16 [06-30 10:41:58.815]
,06-30 10:41:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:41:59.550  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:41:59.550  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:42:04.570  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:26), LCD = 0
,06-30 10:42:14.605  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:26), LCD = 0
,06-30 10:42:15.105  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:19.670  3557  5073 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:42:19.670  3557  5073 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:42:19.670  3557  5073 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:42:19.670  3557  5073 D BatteryService: stay LED for fully charged
,06-30 10:42:19.670  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:42:19.675  3557  3557 I MotionRecognitionService: Plugged
06-30 10:42:19.675  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:42:19.675  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:42:19.675  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:42:19.690  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:42:19.690  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:42:19.690  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:19.695  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:19.715  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:19.715  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:24.630  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:28), LCD = 0
,06-30 10:42:28.820  3557  4999 E Watchdog: !@Sync 17 [06-30 10:42:28.820]
,06-30 10:42:34.660  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:28), LCD = 0
,06-30 10:42:35.110  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:44.695  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:28), LCD = 0
,06-30 10:42:49.765  3557  5073 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:42:49.765  3557  5073 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:42:49.765  3557  5073 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:42:49.765  3557  5073 D BatteryService: stay LED for fully charged
,06-30 10:42:49.770  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:42:49.775  3557  3557 I MotionRecognitionService: Plugged
06-30 10:42:49.775  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:42:49.775  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:42:49.775  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:42:49.780  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:42:49.780  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:42:49.780  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:49.810  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:49.810  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:49.810  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:54.725  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:28), LCD = 0
,06-30 10:42:55.110  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:58.825  3557  4999 E Watchdog: !@Sync 18 [06-30 10:42:58.827]
,06-30 10:42:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:42:59.680  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:42:59.680  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:43:04.760  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,06-30 10:43:14.795  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,06-30 10:43:15.120  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:19.855  3557  5073 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:24.820  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,06-30 10:43:28.835  3557  4999 E Watchdog: !@Sync 19 [06-30 10:43:28.835]
,06-30 10:43:34.850  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,06-30 10:43:35.125  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:44.880  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,06-30 10:43:49.955  3557  3583 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:43:49.955  3557  3583 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:43:49.955  3557  3583 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:43:49.955  3557  3583 D BatteryService: stay LED for fully charged
,06-30 10:43:49.955  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:43:49.960  3557  3557 I MotionRecognitionService: Plugged
06-30 10:43:49.960  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:43:49.960  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:43:49.960  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:43:49.965  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:43:49.965  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:43:49.965  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:43:49.995  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:43:49.995  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:43:49.995  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:54.915  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,06-30 10:43:55.125  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:55.295  3557  4389 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:43:55.295  3557  4389 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:43:55.295  3557  4388 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:43:58.840  3557  4999 E Watchdog: !@Sync 20 [06-30 10:43:58.842]
,06-30 10:43:59.085  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:43:59.085  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:43:59.105  3557  4389 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:43:59.105  3557  4389 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:43:59.790  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:43:59.790  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:43:59.860  4892  4966 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 62ms lastUpdatedAfter : 180411ms
,06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLock,ed: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.685  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:01.690  3557  3704 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:01.885  3557  3798 I ActivityManager: setMaxStartingBackgroundTimer onfinish
06-30 10:44:01.885  3557  3798 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 10:44:04.955  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:44:14.985  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:44:15.130  3557  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:44:20.045  3557  3583 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:44:20.045  3557  3583 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:44:20.045  3557  3583 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:44:20.045  3557  3583 D BatteryService: stay LED for fully charged
,06-30 10:44:20.045  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:44:20.050  3557  3557 I MotionRecognitionService: Plugged
06-30 10:44:20.050  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:44:20.050  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:44:20.050  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:44:20.055  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:44:20.055  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:44:20.055  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate,
,06-30 10:44:20.085  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:20.085  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:20.085  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:25.015  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:44:25.140  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:25.160  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:25.160  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:25.200  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:44:25.200  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:44:25.200  2914  4369 D EnterpriseController: netId is 0
06-30 10:44:25.200  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 10:44:28.840  3557  4999 E Watchdog: !@Sync 21 [06-30 10:44:28.844]
,06-30 10:44:33.090  3557  4400 V AlarmManager: Expired Alarm result :8
,06-30 10:44:35.045  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:44:45.070  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:44:50.140  3557  5768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:44:50.140  3557  5768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:44:50.140  3557  5768 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:44:50.145  3557  5768 D BatteryService: stay LED for fully charged
,06-30 10:44:50.145  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:50.150  3557  3557 I MotionRecognitionService: Plugged
,06-30 10:44:50.150  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:44:50.150  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:44:50.150  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:44:50.160  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:44:50.160  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:44:50.160  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:50.170  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:50.190  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:50.190  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:55.110  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:44:58.850  3557  4999 E Watchdog: !@Sync 22 [06-30 10:44:58.851]
,06-30 10:44:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:44:59.970  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:44:59.970  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:45:05.155  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:45:15.195  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:45:20.240  3557  5768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:25.230  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:45:28.855  3557  4999 E Watchdog: !@Sync 23 [06-30 10:45:28.858]
,06-30 10:45:35.270  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:45:45.295  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:45:50.345  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:45:50.345  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:45:50.345  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:45:50.345  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:45:50.345  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:45:50.350  3557  3557 I MotionRecognitionService: Plugged
06-30 10:45:50.350  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:45:50.350  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:45:50.350  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:45:50.360  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:45:50.360  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:45:50.360  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:50.365  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:50.380  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:45:50.380  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:55.330  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:45:58.860  3557  4999 E Watchdog: !@Sync 24 [06-30 10:45:58.862]
,06-30 10:45:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:46:00.085  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:46:00.085  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:46:05.365  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:46:15.395  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:46:20.445  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:20.445  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:46:20.445  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:46:20.450  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:46:20.455  3557  3557 I MotionRecognitionService: Plugged
06-30 10:46:20.455  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:46:20.455  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:46:20.455  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:46:20.460  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:46:20.460  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:46:20.460  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:20.465  3557  4552 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms,
06-30 10:46:20.465  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:46:20.490  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:20.490  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:20.490  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:25.420  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:46:28.870  3557  4999 E Watchdog: !@Sync 25 [06-30 10:46:28.870]
,06-30 10:46:35.450  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:46:45.495  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:46:50.535  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:46:50.535  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:46:50.535  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:46:50.535  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:46:50.540  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:46:50.545  3557  3557 I MotionRecognitionService: Plugged
06-30 10:46:50.545  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:46:50.545  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:46:50.545  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:46:50.550  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:46:50.550  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:46:50.550  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:50.575  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:50.575  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:50.575  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:55.535  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:46:58.875  3557  4999 E Watchdog: !@Sync 26 [06-30 10:46:58.877]
,06-30 10:46:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:47:00.170  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:47:00.170  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:47:00.230  4892  4966 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 53ms lastUpdatedAfter : 180368ms
,06-30 10:47:01.845  3557  5784 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 10:47:01.850  3557  5784 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 10:47:01.855  3557  5784 V MARsPolicyManager: updateSMDBValues
,06-30 10:47:01.855  3557  3796 E MARsDBManager: updateDBAll : begin --size 0,
06-30 10:47:01.855  3557  3796 E MARsDBManager: updateDBAll : end
,06-30 10:47:05.570  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:47:15.600  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:47:20.640  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:20.640  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:47:20.645  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
,06-30 10:47:20.645  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:47:20.650  3557  3557 I MotionRecognitionService: Plugged
06-30 10:47:20.650  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:47:20.650  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:47:20.650  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:47:20.650  3557  4552 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
06-30 10:47:20.650  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:47:20.660  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:47:20.660  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:47:20.660  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:47:20.665  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:20.685  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:20.685  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:25.635  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:47:28.880  3557  4999 E Watchdog: !@Sync 27 [06-30 10:47:28.882]
,06-30 10:47:35.665  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:47:45.700  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:47:50.725  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:47:50.725  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:47:50.730  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:47:50.730  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:47:50.730  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:47:50.735  3557  3557 I MotionRecognitionService: Plugged
06-30 10:47:50.735  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:47:50.735  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:47:50.735  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:47:50.740  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:47:50.740  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:47:50.740  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:47:50.765  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:47:50.765  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:47:50.765  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:55.730  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:47:58.885  3557  4999 E Watchdog: !@Sync 28 [06-30 10:47:58.889]
,06-30 10:47:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:48:00.320  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:48:00.320  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:48:05.770  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:48:15.800  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:48:20.825  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:48:20.825  3557  4552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:48:20.825  3557  4552 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:48:20.825  3557  4552 D BatteryService: stay LED for fully charged
,06-30 10:48:20.830  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:48:20.830  3557  3557 I MotionRecognitionService: Plugged
06-30 10:48:20.830  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:48:20.830  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:48:20.830  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:48:20.840  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:48:20.840  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:48:20.840  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:20.865  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:48:20.865  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:48:20.865  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:25.830  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:48:28.890  3557  4999 E Watchdog: !@Sync 29 [06-30 10:48:28.893]
,06-30 10:48:35.875  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:48:45.900  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:48:50.915  3557  4552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:55.295  3557  4389 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:48:55.295  3557  4389 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:48:55.295  3557  4388 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:48:55.945  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:48:58.895  3557  4999 E Watchdog: !@Sync 30 [06-30 10:48:58.897]
,06-30 10:48:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:49:00.460  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:49:00.460  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:49:02.320  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:49:02.320  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:49:02.335  3557  4389 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:49:02.340  3557  4389 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:49:05.975  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:49:16.005  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:49:21.010  3557  3582 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:49:21.010  3557  3582 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:49:21.010  3557  3582 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:49:21.010  3557  3582 D BatteryService: stay LED for fully charged
,06-30 10:49:21.010  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:49:21.015  3557  3557 I MotionRecognitionService: Plugged
06-30 10:49:21.015  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:49:21.015  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:49:21.015  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:49:21.025  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:49:21.025  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:49:21.025  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:21.050  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:21.050  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:21.050  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:25.385  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:25.405  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:25.405  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:25.450  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:49:25.450  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:25.450  2914  4369 D EnterpriseController: netId is 0
06-30 10:49:25.450  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 10:49:26.035  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:49:28.905  3557  4999 E Watchdog: !@Sync 31 [06-30 10:49:28.907]
,06-30 10:49:32.105  3557  4400 V AlarmManager: Expired Alarm result :4
,06-30 10:49:32.200  3557  3720 W ProcessCpuTracker: Skipping unknown process pid 11005
,06-30 10:49:32.230  3557  4400 I ActivityManager: Start proc 11012:com.wssyncmldm/1000 for service com.wssyncmldm/com.samsung.android.app.fotaclient.device.PollingIntentService
,06-30 10:49:32.235 11012 11012 E Zygote  : v2
06-30 10:49:32.235 11012 11012 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:49:32.235 11012 11012 I libpersona: KNOX_SDCARD not a persona
,06-30 10:49:32.235 11012 11012 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,06-30 10:49:32.235 11012 11012 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:49:32.240 11012 11012 E Zygote  : accessInfo : 0
,06-30 10:49:32.250  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 10:49:32.250  4515  4515 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 10:49:32.250  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:49:32.260  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 10:49:32.260  3557  3720 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,06-30 10:49:32.265  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 10:49:32.270  5334 11028 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,06-30 10:49:32.275  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 10:49:32.275  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:49:32.275  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:49:32.275  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:49:32.275  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:49:32.280  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:49:32.280  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:49:32.290  3557  3557 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 10:49:32.295  3557  3557 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,06-30 10:49:32.295  3557  3557 I Sensors : Light old sensor_state 1, new sensor_state : 513 en : 1
,06-30 10:49:32.305  3557  3557 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,06-30 10:49:32.310 11012 11012 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:49:32.310 11012 11012 D ActivityThread: Added TimaKeyStore provider
,06-30 10:49:32.320  3557  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0d513 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{487f303 5849:com.google.android.gms/u0a14}
,06-30 10:49:32.320  5334 11026 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-30 10:49:32.365 11012 11012 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
,06-30 10:49:32.395  8639  8639 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
06-30 10:49:32.395  8639  8639 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 10:49:32.395  8639  8639 V GCMBaseIntentService: Acquiring wakelock
,06-30 10:49:32.400 11012 11012 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,06-30 10:49:32.425  8639  8639 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-12
,06-30 10:49:32.430  8639 11039 V GCMRegistrar: Unregistering app flipboard.app
,06-30 10:49:32.450  8639 11039 V GCMBaseIntentService: Releasing wakelock
,06-30 10:49:32.470  3557  7042 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9dbd38b u0 bg_app_info qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e76165d 7254:tv.peel.smartremote/u0a186}
,06-30 10:49:32.500 11012 11012 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2007/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,06-30 10:49:32.505  5334 11026 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,06-30 10:49:32.505  5334 11026 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-30 10:49:32.520  5849 11038 I EventLogChimeraService: Aggregate from 1467274727287 (log), 1467274727287 (data)
,06-30 10:49:32.520  5693  7428 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,06-30 10:49:32.520  5334 11026 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
06-30 10:49:32.520  5334 11026 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-30 10:49:32.525  3557  4377 I Sensors : #>LightSensor r=0 g=1 b=2 c=3 atime=238 again=64 lux=0.000000
,06-30 10:49:32.525  3557  3822 D LightsService: [SvcLED]  onSensorChanged::light value = 0
06-30 10:49:32.525  3557  3822 I Sensors : Light old sensor_state 513, new sensor_state : 1 en : 0
,06-30 10:49:32.530  3557  3822 D SensorManager: unregisterListener ::   
06-30 10:49:32.530  3557  3822 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,06-30 10:49:32.530  3557  3822 V AlarmManager:  remove PendingIntent] PendingIntent{8212cdf: PendingIntentRecord{193a3f5 android broadcastIntent}}
,06-30 10:49:32.565 11012 11012 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,06-30 10:49:32.565 11012 11012 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,06-30 10:49:32.565 11012 11012 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,06-30 10:49:32.580  5693  7428 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:49:32.580  5693  7428 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:32.580  2914  4369 D EnterpriseController: netId is 0
06-30 10:49:32.580  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10014
,06-30 10:49:32.585 11012 11012 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3203/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,06-30 10:49:32.590 11012 11012 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3255/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,06-30 10:49:32.600  3557  3720 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a481bbd u0 com.google.android.c2dm.intent.REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a8ce05 8639:flipboard.app/u0a119}
,06-30 10:49:32.600  8639  8639 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
06-30 10:49:32.600  8639  8639 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 10:49:32.600  8639  8639 V GCMBaseIntentService: Acquiring wakelock
06-30 10:49:32.600 11012 11012 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,06-30 10:49:32.600 11012 11046 I FOTA_AGENT: [com.samsung.android.app.fotaclient.device.PollingIntentService(19/onHandleIntent)] Polling State: Start to check polling
,06-30 10:49:32.605 11012 11046 I FOTA_AGENT: [IIllIIllIIIlllIlIIll(56/llIIIIlllllIIllIIllI)] Polling State: Check condition to update polling
,06-30 10:49:32.605 11012 11046 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(87/llIIIIlllllIIllIIllI)] Polling State: updating polling by current URL
,06-30 10:49:32.610  5334 11026 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
,06-30 10:49:32.610  5334 11026 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-30 10:49:32.615 11012 11046 W FOTA_AGENT: [IIllIllllIIlIlIIlIII(37/llIIIIlllllIIllIIllI)] NetworkInfo is null
,06-30 10:49:32.615 11012 11046 W FOTA_AGENT: [com.samsung.android.fem.network.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Fail to set up!
,06-30 10:49:32.615 11012 11046 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(133/llIIIIlllllIIllIIllI)] Receive result: fail in PollingRestClient
06-30 10:49:32.615 11012 11046 I FOTA_AGENT: [IIlllIlIIlIllIlllIll(135/llIIIIlllllIIllIIllI)] Network is not available. Wait next repeat time
,06-30 10:49:32.615 11012 11046 I FOTA_AGENT: [com.samsung.android.app.fotaclient.device.PollingIntentService(25/onHandleIntent)] Polling State: Finish to check polling
,06-30 10:49:32.635  8639  8639 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-13
,06-30 10:49:32.635  8639 11048 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
06-30 10:49:32.635  8639 11048 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
06-30 10:49:32.635  8639 11048 D GCMBaseIntentService: Scheduling registration retry, backoff = 570592 (384000)
,06-30 10:49:32.645  5334 11026 E ContextCompilationHandl: No recognition context built for APP_NAMES en-US
,06-30 10:49:32.645  5334 11026 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-30 10:49:32.665  8639 11048 V GCMBaseIntentService: Releasing wakelock
,06-30 10:49:32.710  3557  5075 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10014
,06-30 10:49:32.755  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:49:32.795  5849  9477 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-30 10:49:32.800 11051 11051 E Zygote  : v2
06-30 10:49:32.800 11051 11051 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:49:32.800 11051 11051 I libpersona: KNOX_SDCARD not a persona
,06-30 10:49:32.800  3557  3720 I ActivityManager: Start proc 11051:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,06-30 10:49:32.800 11051 11051 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 10:49:32.800 11051 11051 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:49:32.805 11051 11051 E Zygote  : accessInfo : 0
,06-30 10:49:32.845 11051 11051 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:49:32.845 11051 11051 D ActivityThread: Added TimaKeyStore provider
,06-30 10:49:32.865  3557  3583 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{316ef98 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55483f1 11051:com.samsung.android.sm/1000}
,06-30 10:49:32.875  5849  9477 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:32.930  3557  4887 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{316ef98 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{487f303 5849:com.google.android.gms/u0a14}
,06-30 10:49:32.940  5849  9477 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:32.965  5849 11050 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 10:49:32.975  5849  9477 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
06-30 10:49:32.975  3557  5769 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9576d44 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55483f1 11051:com.samsung.android.sm/1000}
,06-30 10:49:33.000  3557  4552 I ActivityManager: Killing 9891:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,06-30 10:49:33.010  3557  4552 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9576d44 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{487f303 5849:com.google.android.gms/u0a14}
,06-30 10:49:33.060  3557  4552 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,06-30 10:49:33.170  5334 11026 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
06-30 10:49:33.170  5334 11026 E native  : request_context {
06-30 10:49:33.170  5334 11026 E native  :   type: DYNAMIC_CLASS
06-30 10:49:33.170  5334 11026 E native  :   dynamic_class_context {
06-30 10:49:33.170  5334 11026 E native  :     class_type: SONG_NAME
06-30 10:49:33.170  5334 11026 E native  :     instance {
06-30 10:49:33.170  5334 11026 E native  :       value: "Over the Horizon"
06-30 10:49:33.170  5334 11026 E native  :     }
06-30 10:49:33.170  5334 11026 E native  :   }
06-30 10:49:33.170  5334 11026 E native  : }
06-30 10:49:33.170  5334 11026 E native  : request_context {
06-30 10:49:33.170  5334 11026 E native  :   type: DYNAMIC_CLASS
06-30 10:49:33.170  5334 11026 E native  :   dynamic_class_context {
06-30 10:49:33.170  5334 11026 E native  :     class_type: UNKNOWN_DYNAMIC_CLASS
06-30 10:49:33.170  5334 11026 E native  :     instance {
06-30 10:49:33.170  5334 11026 E native  :       value: "Brand Music"
06-30 10:49:33.170  5334 11026 E native  :     }
06-30 10:49:33.170  5334 11026 E native  :   }
06-30 10:49:33.170  5334 11026 E native  : }
06-30 10:49:33.170  5334 11026 E native  : request_context {
06-30 10:49:33.170  5334 11026 E native  :   type: DYNAMIC_CLASS
06-30 10:49:33.170  5334 11026 E native  :   dynamic_class_context {
06-30 10:49:33.170  5334 11026 E native  :     class_type: ARTIST_NAME
06-30 10:49:33.170  5334 11026 E native  :     instance {
06-30 10:49:33.170  5334 11026 E native  :       value: "Samsung"
06-30 10:49:33.170  5334 11026 E native  :     }
06-30 10:49:33.170  5334 11026 E native  :   }
06-30 10:49:33.170  5334 11026 E native  : }
06-30 10:49:33.170  5334 11026 E native  : 
,06-30 10:49:33.170  5334 11026 E ContextCompilationHandl: Compiling recognition context failed for MUSIC_NAMES en-US
06-30 10:49:33.170  5849 11063 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-30 10:49:33.175  5849 11063 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-30 10:49:33.265  7254  7295 I System.out: Thread-474(ApacheHTTPLog):isSBSettingEnabled false
06-30 10:49:33.265  7254  7295 I System.out: Thread-474(ApacheHTTPLog):isShipBuild true
06-30 10:49:33.265  7254  7295 I System.out: Thread-474(ApacheHTTPLog):getDebugLevel 0x4f4c
06-30 10:49:33.265  7254  7295 I System.out: Thread-474(ApacheHTTPLog):Smart Bonding Setting is false
06-30 10:49:33.265  7254  7295 I System.out: Thread-474(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,06-30 10:49:33.270  2914  4369 D EnterpriseController: netId is 0
06-30 10:49:33.270  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10186
,06-30 10:49:33.270  7254  7295 I System.out: non-ui calls detatch()
,06-30 10:49:36.075  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:49:38.010  3557  4887 I ActivityManager: Killing 9906:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): DHA:empty #31
,06-30 10:49:38.100  3557  4439 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,06-30 10:49:46.100  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:49:51.115  3557  3582 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:49:51.115  3557  3582 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:49:51.115  3557  3582 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:49:51.115  3557  3582 D BatteryService: stay LED for fully charged
,06-30 10:49:51.120  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:49:51.120  3557  3557 I MotionRecognitionService: Plugged
06-30 10:49:51.125  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:49:51.125  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:49:51.125  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:49:51.130  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:49:51.130  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:49:51.130  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate,
,06-30 10:49:51.160  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:51.160  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:51.160  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:56.140  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:49:58.910  3557  4999 E Watchdog: !@Sync 32 [06-30 10:49:58.911]
,06-30 10:49:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:49:59.995  3557  4400 V AlarmManager: Expired Alarm result :8
,06-30 10:50:00.580  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:50:00.580  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:50:06.190  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:50:16.215  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:50:21.200  3557  3582 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:50:21.200  3557  3582 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:50:21.200  3557  3582 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:50:21.200  3557  3582 D BatteryService: stay LED for fully charged
,06-30 10:50:21.205  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:50:21.210  3557  3557 I MotionRecognitionService: Plugged
06-30 10:50:21.210  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:50:21.210  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:50:21.210  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:50:21.215  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:50:21.215  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:50:21.215  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:21.240  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:50:21.240  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:50:21.240  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:26.245  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:50:28.915  3557  4999 E Watchdog: !@Sync 33 [06-30 10:50:28.919]
,06-30 10:50:36.285  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:50:46.320  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:50:51.300  3557  3582 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:50:51.300  3557  3582 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:50:51.300  3557  3582 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:50:51.300  3557  3582 D BatteryService: stay LED for fully charged
,06-30 10:50:51.305  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:50:51.305  3557  3557 I MotionRecognitionService: Plugged
06-30 10:50:51.305  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:50:51.310  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:50:51.310  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:50:51.315  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:50:51.315  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:50:51.315  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:51.345  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:50:51.345  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:50:51.345  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:56.345  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:50:58.920  3557  4999 E Watchdog: !@Sync 34 [06-30 10:50:58.924]
,06-30 10:50:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:51:00.700  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:51:00.700  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:51:06.385  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:51:16.435  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:51:21.395  3557  3582 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:26.470  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:51:28.925  3557  4999 E Watchdog: !@Sync 35 [06-30 10:51:28.929]
,06-30 10:51:36.530  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:51:36.595  3557  3569 I art     : Background sticky concurrent mark sweep GC freed 54557(7MB) AllocSpace objects, 365(7MB) LOS objects, 32% free, 30MB/45MB, paused 3.192ms total 100.041ms
,06-30 10:51:46.570  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:51:51.495  3557  7044 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:51:51.495  3557  7044 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:51:51.495  3557  7044 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:51:51.495  3557  7044 D BatteryService: stay LED for fully charged
,06-30 10:51:51.495  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:51:51.500  3557  3557 I MotionRecognitionService: Plugged
06-30 10:51:51.500  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:51:51.500  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:51:51.500  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:51:51.505  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:51:51.505  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:51:51.505  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:51.535  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:51.535  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:51.535  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:56.600  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:51:58.935  3557  4999 E Watchdog: !@Sync 36 [06-30 10:51:58.935]
,06-30 10:51:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:52:00.795  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:52:00.795  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:52:00.885  4892  4966 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 78ms lastUpdatedAfter : 148004ms
,06-30 10:52:06.635  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:52:16.680  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:52:21.585  3557  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:52:21.585  3557  4887 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:52:21.585  3557  4887 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:52:21.585  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:52:21.590  3557  4887 D BatteryService: stay LED for fully charged
,06-30 10:52:21.595  3557  3557 I MotionRecognitionService: Plugged
06-30 10:52:21.595  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:52:21.595  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:52:21.595  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:52:21.600  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:52:21.600  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:52:21.600  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:52:21.625  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:52:21.625  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:52:21.625  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:26.710  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:52:28.940  3557  4999 E Watchdog: !@Sync 37 [06-30 10:52:28.943]
,06-30 10:52:36.740  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:52:46.785  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:52:51.680  3557  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:52:51.680  3557  4887 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:52:51.680  3557  4887 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:52:51.680  3557  4887 D BatteryService: stay LED for fully charged
,06-30 10:52:51.680  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:52:51.690  3557  3557 I MotionRecognitionService: Plugged
06-30 10:52:51.690  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:52:51.690  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:52:51.690  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:52:51.695  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:52:51.695  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:52:51.700  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:52:51.705  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:51.725  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:52:51.725  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:56.815  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:52:58.950  3557  4999 E Watchdog: !@Sync 38 [06-30 10:52:58.951]
,06-30 10:52:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:53:00.975  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:53:00.975  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:53:06.865  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:53:16.895  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:53:21.775  3557  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:53:21.775  3557  4887 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:53:21.775  3557  4887 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:53:21.775  3557  4887 D BatteryService: stay LED for fully charged
,06-30 10:53:21.780  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:53:21.785  3557  3557 I MotionRecognitionService: Plugged
06-30 10:53:21.785  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:53:21.785  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:53:21.785  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:53:21.790  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:53:21.790  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:21.790  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:21.820  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:53:21.820  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:53:21.820  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:26.925  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:53:28.955  3557  4999 E Watchdog: !@Sync 39 [06-30 10:53:28.958]
,06-30 10:53:36.960  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:53:46.990  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:53:51.870  3557  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:53:51.870  3557  4887 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:53:51.870  3557  4887 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:53:51.870  3557  4887 D BatteryService: stay LED for fully charged
,06-30 10:53:51.875  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:53:51.875  3557  3557 I MotionRecognitionService: Plugged
06-30 10:53:51.875  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:53:51.880  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:53:51.880  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:53:51.885  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:53:51.885  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:53:51.885  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate,
,06-30 10:53:51.915  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:53:51.915  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:53:51.915  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:55.295  3557  4389 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:53:55.295  3557  4389 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:53:55.295  3557  4388 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:53:55.695  3557  3704 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:53:57.035  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:53:58.955  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 10:53:58.955  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:53:58.960  3557  4999 E Watchdog: !@Sync 40 [06-30 10:53:58.965]
,06-30 10:53:58.970  3557  4389 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 10:53:58.970  3557  4389 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:54:01.075  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:54:01.075  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:54:07.085  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:54:17.115  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:54:21.960  3557  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:54:21.960  3557  4887 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:54:21.960  3557  4887 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:54:21.960  3557  4887 D BatteryService: stay LED for fully charged
,06-30 10:54:21.965  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:54:21.970  3557  3557 I MotionRecognitionService: Plugged
06-30 10:54:21.970  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:54:21.970  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:54:21.970  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:54:21.975  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:54:21.975  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:54:21.975  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:21.990  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,06-30 10:54:21.990  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 10:54:21.995  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:25.605  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:25.625  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:25.625  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:25.675  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:54:25.675  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:54:25.675  2914  4369 D EnterpriseController: netId is 0
06-30 10:54:25.675  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 10:54:27.155  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:54:28.965  3557  4999 E Watchdog: !@Sync 41 [06-30 10:54:28.966]
,06-30 10:54:37.205  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:54:47.250  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:54:52.065  3557  7043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:52.065  3557  7043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:54:52.065  3557  7043 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:54:52.070  3557  7043 D BatteryService: stay LED for fully charged
06-30 10:54:52.070  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:54:52.070  3557  3557 I MotionRecognitionService: Plugged
06-30 10:54:52.070  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:54:52.070  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:54:52.070  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:54:52.080  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:54:52.080  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:54:52.080  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:52.085  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,06-30 10:54:52.105  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:54:52.105  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:57.285  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:54:58.970  3557  4999 E Watchdog: !@Sync 42 [06-30 10:54:58.973]
,06-30 10:54:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:55:01.175  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:55:01.175  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:55:01.245  4892  4966 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 57ms lastUpdatedAfter : 180354ms
,06-30 10:55:07.330  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:55:17.365  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:55:22.150  3557  7043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:55:22.150  3557  7043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:55:22.150  3557  7043 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:55:22.150  3557  7043 D BatteryService: stay LED for fully charged
,06-30 10:55:22.155  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:55:22.160  3557  3557 I MotionRecognitionService: Plugged
06-30 10:55:22.160  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:55:22.160  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:55:22.160  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:55:22.165  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:55:22.165  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:55:22.165  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:22.195  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:22.195  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:22.195  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:27.390  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:55:28.975  3557  4999 E Watchdog: !@Sync 43 [06-30 10:55:28.977]
,06-30 10:55:37.415  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:55:47.440  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:55:52.245  3557  7043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:55:52.245  3557  7043 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:55:52.245  3557  7043 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:55:52.245  3557  7043 D BatteryService: stay LED for fully charged
,06-30 10:55:52.245  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:55:52.250  3557  3557 I MotionRecognitionService: Plugged
06-30 10:55:52.250  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:55:52.250  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:55:52.250  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:55:52.260  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:55:52.260  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:55:52.260  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:52.285  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:52.285  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:55:52.285  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:57.485  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:55:58.980  3557  4999 E Watchdog: !@Sync 44 [06-30 10:55:58.981]
,06-30 10:55:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:56:01.330  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:56:01.330  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:56:07.535  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:56:17.580  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0,
,06-30 10:56:22.340  3557  7043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:27.610  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:56:28.985  3557  4999 E Watchdog: !@Sync 45 [06-30 10:56:28.987]
,06-30 10:56:37.635  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:56:47.685  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:56:52.435  3557  4888 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:56:52.435  3557  4888 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:56:52.435  3557  4888 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:56:52.435  3557  4888 D BatteryService: stay LED for fully charged
,06-30 10:56:52.435  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:56:52.440  3557  3557 I MotionRecognitionService: Plugged
06-30 10:56:52.440  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:56:52.440  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:56:52.440  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:56:52.445  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:56:52.445  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:56:52.450  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:52.460  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:52.475  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:56:52.480  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:57.715  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:56:58.990  3557  4999 E Watchdog: !@Sync 46 [06-30 10:56:58.994]
,06-30 10:56:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:57:01.430  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:57:01.430  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:57:07.770  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 10:57:17.800  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:30), LCD = 0
,06-30 10:57:22.525  3557  4888 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:57:22.525  3557  4888 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:57:22.525  3557  4888 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:57:22.525  3557  4888 D BatteryService: stay LED for fully charged
,06-30 10:57:22.530  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:57:22.535  3557  3557 I MotionRecognitionService: Plugged
06-30 10:57:22.535  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:57:22.535  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:57:22.535  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:57:22.540  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 10:57:22.540  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:57:22.540  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:22.570  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:22.570  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:22.570  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:27.840  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 259 (W:28), LCD = 0
,06-30 10:57:29.000  3557  4999 E Watchdog: !@Sync 47 [06-30 10:57:29.000]
,06-30 10:57:37.890  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:28), LCD = 0
,06-30 10:57:47.915  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:28), LCD = 0
,06-30 10:57:52.620  3557  4888 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:57:52.620  3557  4888 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:57:52.620  3557  4888 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:57:52.620  3557  4888 D BatteryService: stay LED for fully charged
,06-30 10:57:52.625  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:57:52.630  3557  3557 I MotionRecognitionService: Plugged
06-30 10:57:52.630  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:57:52.630  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:57:52.630  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:57:52.635  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:57:52.635  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:57:52.635  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:52.660  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:52.660  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:52.660  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:57.965  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:28), LCD = 0
,06-30 10:57:59.005  3557  4999 E Watchdog: !@Sync 48 [06-30 10:57:59.010]
,06-30 10:57:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:58:01.540  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:58:01.540  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:58:01.615  4892  4966 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 67ms lastUpdatedAfter : 180371ms
,06-30 10:58:07.995  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 258 (W:26), LCD = 0
,06-30 10:58:18.025  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:26), LCD = 0
,06-30 10:58:22.715  3557  4888 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:28.050  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:26), LCD = 0
,06-30 10:58:29.015  3557  4999 E Watchdog: !@Sync 49 [06-30 10:58:29.017]
,06-30 10:58:38.095  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:26), LCD = 0
,06-30 10:58:48.140  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:28), LCD = 0
,06-30 10:58:52.815  3557  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:58:52.815  3557  4439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:58:52.815  3557  4439 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 10:58:52.820  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:58:52.820  3557  3557 I MotionRecognitionService: Plugged
06-30 10:58:52.820  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:58:52.825  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:58:52.825  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:58:52.825  3557  4439 D BatteryService: stay LED for fully charged
,06-30 10:58:52.830  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:58:52.830  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:58:52.830  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:58:52.860  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:58:52.860  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:58:52.860  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:55.290  3557  4389 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 10:58:55.290  3557  4389 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:58:55.295  3557  4388 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:58:58.190  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:28), LCD = 0
,06-30 10:58:59.020  3557  4999 E Watchdog: !@Sync 50 [06-30 10:58:59.024]
,06-30 10:58:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 10:59:01.740  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 10:59:01.740  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 10:59:01.865  3557  5784 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 10:59:01.865  3557  5784 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 10:59:01.865  3557  5784 V MARsPolicyManager: updateSMDBValues
06-30 10:59:01.870  3557  3796 E MARsDBManager: updateDBAll : begin --size 0
06-30 10:59:01.870  3557  3796 E MARsDBManager: updateDBAll : end
,06-30 10:59:02.400  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3,
06-30 10:59:02.400  3557  4389 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:59:02.415  3557  4389 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
06-30 10:59:02.420  3557  4389 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:59:08.240  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 256 (W:26), LCD = 0
,06-30 10:59:18.285  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:26), LCD = 0
,06-30 10:59:22.915  3557  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 10:59:22.915  3557  4439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 10:59:22.915  3557  4439 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
,06-30 10:59:22.920  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:59:22.925  3557  3557 I MotionRecognitionService: Plugged
06-30 10:59:22.925  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 10:59:22.925  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:59:22.925  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:59:22.925  3557  4439 D BatteryService: stay LED for fully charged
,06-30 10:59:22.930  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:59:22.930  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:59:22.930  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate,
,06-30 10:59:22.960  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:59:22.960  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:59:22.960  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:59:25.830  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:59:25.850  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:59:25.850  5693  5693 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:59:25.895  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:59:25.895  9181  9210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:59:25.895  2914  4369 D EnterpriseController: netId is 0
06-30 10:59:25.895  2914  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 10:59:28.330  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:24), LCD = 0
,06-30 10:59:29.020  3557  4999 E Watchdog: !@Sync 51 [06-30 10:59:29.025]
,06-30 10:59:38.355  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:24), LCD = 0
,06-30 10:59:48.385  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:24), LCD = 0
,06-30 10:59:53.005  3557  5217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:59:58.400  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:24), LCD = 0
,06-30 10:59:59.025  3557  4999 E Watchdog: !@Sync 52 [06-30 10:59:59.026]
,06-30 10:59:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 11:00:01.875  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 11:00:01.875  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 11:00:08.430  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:26), LCD = 0
,06-30 11:00:18.470  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:26), LCD = 0
,06-30 11:00:23.100  3557  5198 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:00:28.495  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:26), LCD = 0
,06-30 11:00:29.025  3557  4999 E Watchdog: !@Sync 53 [06-30 11:00:29.028]
,06-30 11:00:38.530  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:26), LCD = 0
,06-30 11:00:48.570  3557  6655 D SSRM:n  : SIOP:: AP = 260, PST = 254 (W:24), LCD = 0
,06-30 11:00:53.190  3557  7043 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:00:58.585  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:24), LCD = 0
,06-30 11:00:59.025  3557  4999 E Watchdog: !@Sync 54 [06-30 11:00:59.029]
,06-30 11:00:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 11:01:01.980  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 11:01:01.980  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 11:01:02.045  4892  4966 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 62ms lastUpdatedAfter : 180433ms
,06-30 11:01:08.600  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:24), LCD = 0
,06-30 11:01:18.615  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:24), LCD = 0
,06-30 11:01:23.280  3557  5769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 11:01:23.280  3557  5769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 11:01:23.280  3557  5769 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 11:01:23.280  3557  5769 D BatteryService: stay LED for fully charged
,06-30 11:01:23.285  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 11:01:23.290  3557  3557 I MotionRecognitionService: Plugged
06-30 11:01:23.290  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 11:01:23.290  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 11:01:23.290  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 11:01:23.300  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 11:01:23.300  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 11:01:23.300  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 11:01:23.325  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 11:01:23.325  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 11:01:23.325  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:01:28.655  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:26), LCD = 0
,06-30 11:01:29.030  3557  4999 E Watchdog: !@Sync 55 [06-30 11:01:29.030]
,06-30 11:01:38.690  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:26), LCD = 0
,06-30 11:01:48.705  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:26), LCD = 0
,06-30 11:01:53.375  3557  5769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 11:01:53.375  3557  5769 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 11:01:53.375  3557  5769 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 11:01:53.375  3557  3557 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 11:01:53.380  3557  5769 D BatteryService: stay LED for fully charged
,06-30 11:01:53.390  3557  3557 I MotionRecognitionService: Plugged
06-30 11:01:53.390  3557  3557 D MotionRecognitionService:   cableConnection= 1
06-30 11:01:53.390  3557  3557 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 11:01:53.390  3557  3557 D MotionRecognitionService: skip setTransmitPower. 
,06-30 11:01:53.395  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 11:01:53.395  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 11:01:53.395  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 11:01:53.420  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 11:01:53.420  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 11:01:53.420  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:01:58.720  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:26), LCD = 0
,06-30 11:01:59.030  3557  4999 E Watchdog: !@Sync 56 [06-30 11:01:59.032]
,06-30 11:01:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 11:02:02.140  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 11:02:02.140  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 11:02:08.735  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:28), LCD = 0
,06-30 11:02:18.770  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:28), LCD = 0
,06-30 11:02:23.465  3557  5769 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:02:28.795  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:28), LCD = 0
,06-30 11:02:29.030  3557  4999 E Watchdog: !@Sync 57 [06-30 11:02:29.033]
,06-30 11:02:38.830  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:28), LCD = 0
,06-30 11:02:48.870  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:30), LCD = 0
,06-30 11:02:53.560  3557  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:02:58.895  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:30), LCD = 0
,06-30 11:02:59.030  3557  4999 E Watchdog: !@Sync 58 [06-30 11:02:59.035]
,06-30 11:02:59.365  2954  5215 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 11:03:02.285  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 11:03:02.285  4892  4966 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 11:03:08.910  3557  6655 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:30), LCD = 0
,TIME-OUT KILL (timeout was 1400000ms)
```
