#### Test 794266509fa1f7f_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
08-05 02:13:25.032  3525  6922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 02:13:25.647  3525  6834 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:22), CUR = 8, LCD = 0
--------- beginning of main
08-05 02:13:25.767 11397 11397 I FIPS_bssl: FIPS approved mode (1) | 11397 | app_process
08-05 02:13:25.777 11397 11397 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 02:13:25.777 11397 11397 D AndroidRuntime: CheckJNI is OFF
08-05 02:13:25.777 11397 11397 D AndroidRuntime: readGMSProperty: start
08-05 02:13:25.777 11397 11397 D AndroidRuntime: readGMSProperty: already setted!!
08-05 02:13:25.777 11397 11397 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 02:13:25.777 11397 11397 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 02:13:25.777 11397 11397 D AndroidRuntime: readGMSProperty: end
08-05 02:13:25.777 11397 11397 D AndroidRuntime: addProductProperty: start
08-05 02:13:25.807 11397 11397 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 02:13:25.837 11397 11397 I Radio-JNI: register_android_hardware_Radio DONE
08-05 02:13:25.842 11397 11397 E AffinityControl: AffinityControl: registerfunction enter
08-05 02:13:25.852 11397 11397 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 02:13:25.867  3525  5016 D GameManagerService: identifyGamePackage. com.test.thalitest
08-05 02:13:25.867  3525  5016 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
08-05 02:13:25.867  3525  5016 D ActivityManager: mDVFSHelper.acquire()
08-05 02:13:25.867  3525  5016 V WindowManager: addAppToken: AppWindowToken{a88056e token=Token{19bc4e9 ActivityRecord{70f3970 u0 com.test.thalitest/.MainActivity t108}}} to stack=1 task=108 at 0
08-05 02:13:25.872  3525  3775 D SecWifiDisplayUtil: Metadata value : none
08-05 02:13:25.872  3525  3775 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7575446 V.E...... R.....ID 0,0-0,0}
08-05 02:13:25.872  3525  3775 D ISSUE_DEBUG: InputChannelName : fabc334 Starting com.test.thalitest
08-05 02:13:25.877 11413 11413 E Zygote  : v2
08-05 02:13:25.877 11413 11413 I libpersona: KNOX_SDCARD checking this for 10007
08-05 02:13:25.877 11413 11413 I libpersona: KNOX_SDCARD not a persona
08-05 02:13:25.877 11413 11413 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
08-05 02:13:25.877 11413 11413 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:25.877 11413 11413 E Zygote  : accessInfo : 0
08-05 02:13:25.877  3525  5016 I ActivityManager: Start proc 11413:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
08-05 02:13:25.877 11413 11413 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-05 02:13:25.877  3525  5016 D InputDispatcher: Focused application set to: xxxx
08-05 02:13:25.882  3525  5016 D InputDispatcher: Focus left window: 7017
08-05 02:13:25.882 11397 11397 D AndroidRuntime: Shutting down VM
08-05 02:13:25.882  3525  3698 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{77f0de u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-05 02:13:25.882  3525  4445 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-05 02:13:25.882  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-05 02:13:25.887  2906  2906 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
08-05 02:13:25.892 11413 11413 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 02:13:25.892 11413 11413 D ActivityThread: Added TimaKeyStore provider
08-05 02:13:25.902  3525  5100 V WindowOrientationListener: setCurrentAppOrientation :-1
08-05 02:13:25.902  3525  5100 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-05 02:13:25.902  3525  3775 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3525 uid:1000
08-05 02:13:25.902  3525  3775 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:13:25.902  3525  3775 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3525 uid:1000
08-05 02:13:25.902  3525  3775 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 02:13:25.902  3525  3775 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
08-05 02:13:25.902  3525  3698 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{fabc334 u0 d0 Starting com.test.thalitest}
08-05 02:13:25.902  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-05 02:13:25.907  3525  5100 D ActivityManager:  Launching com.test.thalitest, updated priority
08-05 02:13:25.912  3525  3525 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
08-05 02:13:25.912  3525  3694 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-05 02:13:25.927  2906  5169 I SurfaceFlinger: id=13 Removed VSBConnecti (5/11)
08-05 02:13:25.927  2906 10065 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/11)
08-05 02:13:25.932  7017  7017 V ActivityThread: updateVisibility : ActivityRecord{66da12 token=android.os.BinderProxy@101ff57 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-05 02:13:25.932  2906  2998 D libEGL  : eglTerminate EGLDisplay = 0xb663f624
08-05 02:13:25.932  2906  2998 D libEGL  : eglTerminate EGLDisplay = 0xb663f624
08-05 02:13:25.932  2906 10065 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
08-05 02:13:25.932  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe9ec474
08-05 02:13:25.932  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe9ec474
08-05 02:13:25.932  2906  5169 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
08-05 02:13:25.937  5094  5094 V ActivityThread: updateVisibility : ActivityRecord{5825ff9 token=android.os.BinderProxy@3e50265 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-05 02:13:25.937  5094  5094 D Launcher: onTrimMemory. Level: 20
08-05 02:13:25.947  3525  3775 V WindowStateAnimator: Finishing drawing window Window{fabc334 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-05 02:13:25.947  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe9ec40c
08-05 02:13:25.972  2906 10065 D libEGL  : eglTerminate EGLDisplay = 0xb1aa4624
08-05 02:13:25.972  2906  2991 I SurfaceFlinger: id=12 Removed VSBConnecti (5/9)
08-05 02:13:25.972  2906  2998 I SurfaceFlinger: id=12 Removed VSBConnecti (-2/9)
08-05 02:13:25.982  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe9ec474
,08-05 02:13:26.217  3525  5100 I WindowManager: Screenshot max retries 4 of Token{19bc4e9 ActivityRecord{70f3970 u0 com.test.thalitest/.MainActivity t108}} appWin=Window{fabc334 u0 d0 Starting com.test.thalitest} drawState=4
,08-05 02:13:26.217  3525  3694 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,08-05 02:13:26.232  3525  4445 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,08-05 02:13:26.252  3525  6834 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 02:13:26.262  3525  6834 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 02:13:26.302 11413 11413 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-05 02:13:26.337 11413 11413 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-05 02:13:26.342 11413 11413 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 3805-3808)
08-05 02:13:26.342 11413 11413 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-05 02:13:26.362 11413 11427 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-05 02:13:26.367 11413 11413 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {568a03a}
08-05 02:13:26.367 11413 11413 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-05 02:13:26.367 11413 11413 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 02:13:26.372 11413 11413 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-05 02:13:26.417 11413 11413 D libEGL  : eglInitialize EGLDisplay = 0xbec28e7c
,08-05 02:13:26.452  3525  4260 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,08-05 02:13:26.452  3525  4260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-05 02:13:26.512 11413 11413 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-05 02:13:26.527 11413 11413 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 02:13:26.527 11413 11413 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-05 02:13:26.527 11413 11413 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-05 02:13:26.527 11413 11413 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-05 02:13:26.542 11413 11413 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-05 02:13:26.547 11413 11413 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-05 02:13:26.617 11413 11413 D SecWifiDisplayUtil: Metadata value : none
,08-05 02:13:26.622 11413 11413 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b4c64cb I.E...... R.....ID 0,0-0,0}
,08-05 02:13:26.632 11413 11464 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 02:13:26.637  3525  5104 D ISSUE_DEBUG: InputChannelName : 62e4b01 com.test.thalitest/com.test.thalitest.MainActivity
,08-05 02:13:26.642  3525  5781 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-05 02:13:26.642  3525  5781 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 02:13:26.647  3525  3525 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 02:13:26.647  3525  3525 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-05 02:13:26.702 11413 11413 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 11413
,08-05 02:13:26.702  3525  5104 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/11413 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:26.702  3525  4454 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-05 02:13:26.702  3525  4454 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-05 02:13:26.707  3525  4454 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-05 02:13:26.707  3525  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:26.707  3525  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:26.707  3525  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-05 02:13:26.707  3525  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:26.707  3525  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:26.707  3525  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-05 02:13:26.707  3525  4454 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:26.712 11413 11427 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-05 02:13:26.722 11413 11413 D SecWifiDisplayUtil: Metadata value : none
,08-05 02:13:26.732  2906  2906 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,08-05 02:13:26.752  3525  4260 D InputDispatcher: Focus entered window: 11413
,08-05 02:13:26.757  3525  3775 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3525 uid:1000
08-05 02:13:26.757  3525  3775 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-05 02:13:26.757  3525  3775 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3525 uid:1000
08-05 02:13:26.757  3525  3775 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 02:13:26.757 11413 11464 D libEGL  : eglInitialize EGLDisplay = 0x9cdbf7c4
08-05 02:13:26.757 11413 11464 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 02:13:26.762 11413 11464 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,08-05 02:13:26.767 11413 11413 V ActivityThread: updateVisibility : ActivityRecord{2e02bf2 token=android.os.BinderProxy@2d4c39a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-05 02:13:26.777 11413 11413 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-05 02:13:26.832 11413 11469 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 02:13:26.832 11413 11469 D libEGL  : eglInitialize EGLDisplay = 0x9afbf3ec
,08-05 02:13:26.852  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe9ec40c
,08-05 02:13:26.857  3525  5422 V WindowStateAnimator: Finishing drawing window Window{62e4b01 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-05 02:13:26.857 11413 11413 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,08-05 02:13:26.857 11413 11413 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 02:13:26.862  3525  5781 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 02:13:26.862  3525  3775 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 02:13:26.862  3525  3525 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 02:13:26.862  3525  3775 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +645ms (total +994ms)
,08-05 02:13:26.867  3525  3525 I KnoxTimeoutHandler: SD activityfalse
,08-05 02:13:26.872  3525  3775 D ActivityManager: mDVFSHelper.release()
,08-05 02:13:26.872  3525  3775 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{70f3970 u0 com.test.thalitest/.MainActivity t108} time:334335
08-05 02:13:26.872  3525  3775 D ViewRootImpl: #3 mView = null
08-05 02:13:26.872  2906  5169 I SurfaceFlinger: id=14 Removed uhalitest (7/9),
,08-05 02:13:26.872  2906  5169 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
08-05 02:13:26.872  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe9ec474
,08-05 02:13:26.897 11413 11413 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 02:13:26.912  3525  3545 V WindowStateAnimator: Finishing drawing window Window{62e4b01 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-05 02:13:26.912 11413 11413 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11413
,08-05 02:13:26.917 11413 11413 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d4c39a time:334382
,08-05 02:13:26.917  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe9ec40c
,08-05 02:13:27.072 11413 11413 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 02:13:27.207 11413 11477 D jxcore_app_log: JniHelper::setJavaVM(0xb47f4000), pthread_self() = -1804379856
,08-05 02:13:27.212 11413 11477 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 02:13:27.212 11413 11477 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 02:13:27.212 11413 11477 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 02:13:27.212 11413 11477 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 02:13:27.212 11413 11477 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 02:13:27.212 11413 11477 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76cd7d8 added. We now have 1 listener(s)
,08-05 02:13:27.212 11413 11477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,08-05 02:13:27.212 11413 11477 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
08-05 02:13:27.217 11413 11477 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 02:13:27.217 11413 11477 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 02:13:27.217 11413 11477 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f36397 added. We now have 1 listener(s)
08-05 02:13:27.217 11413 11477 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 02:13:27.217 11413 11477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 02:13:27.217 11413 11477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 02:13:27.217 11413 11477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 02:13:27.217 11413 11477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 02:13:27.217 11413 11477 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 02:13:27.222 11413 11477 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 02:13:27.222 11413 11477 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,08-05 02:13:27.227 11413 11477 D BluetoothAdapter: STATE_ON
,08-05 02:13:27.227 11413 11477 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:13:27.227 11413 11477 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 02:13:27.227 11413 11477 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 02:13:27.227 11413 11477 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 02:13:27.227 11413 11477 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 02:13:27.232 11413 11413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 02:13:27.232 11413 11413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 02:13:27.257 11413 11413 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 02:13:27.657  4692  4692 D Recents : onTaskStackChanged
,08-05 02:13:27.677 11413 11478 W jxcore-log: Initializing JXcore engine
08-05 02:13:27.677 11413 11478 W jxcore-log: JXcore engine is ready
,08-05 02:13:27.702  5693  5693 E audit   : type=1400 msg=audit(1470356007.702:266): avc:  denied  { ioctl } for  pid=11478 comm="Thread-1139" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2206 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 02:13:27.702  5693  5693 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:27.702  5693  5693 E audit   : type=1300 msg=audit(1470356007.702:266): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=9373f3c8 items=0 ppid=2960 ppcomm=main pid=11478 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1139" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 02:13:27.702  5693  5693 E audit   : type=1327 msg=audit(1470356007.702:266): proctitle="com.test.thalitest"
08-05 02:13:27.702  5693  5693 E audit   : type=1320 msg=audit(1470356007.702:266): 
08-05 02:13:27.702  5693  5693 E audit   : type=1400 msg=audit(1470356007.702:267): avc:  denied  { ioctl } for  pid=11478 comm="Thread-1139" path="socket:[40351]" dev="sockfs" ino=40351 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 02:13:27.702  5693  5693 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:27.702  5693  5693 E audit   : type=1300 msg=audit(1470356007.702:267): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=9373f3c8 items=0 ppid=2960 ppcomm=main pid=11478 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1139" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 02:13:27.702  5693  5693 E audit   : type=1327 msg=audit(1470356007.702:267): proctitle="com.test.thalitest"
08-05 02:13:27.702  5693  5693 E audit   : type=1320 msg=audit(1470356007.702:267): 
,08-05 02:13:27.707 11413 11478 W jxcore-log: Starting JXcore engine
,08-05 02:13:27.757 11413 11478 W jxcore-log: Platform android
08-05 02:13:27.757 11413 11478 W jxcore-log: 
08-05 02:13:27.757 11413 11478 W jxcore-log: Process ARCH arm
08-05 02:13:27.757 11413 11478 W jxcore-log: 
,08-05 02:13:27.867 11413 11478 I jxcore-log: JXcore Cordova bridge is ready!
08-05 02:13:27.867 11413 11478 I jxcore-log: 
08-05 02:13:27.867 11413 11478 W jxcore-log: JXcore engine is started
,08-05 02:13:27.872 11413 11477 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 02:13:27.872 11413 11413 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 02:13:28.877  3525  4499 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/108_task.xml.bak
,08-05 02:13:29.037  3525  4550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 02:13:29.037  3525  4550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
08-05 02:13:29.037  3525  4550 D BatteryService: online:4, current avg:-45, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:-197
08-05 02:13:29.037  3525  4550 D BatteryService: stay LED for fully charged
08-05 02:13:29.037  3525  3525 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 02:13:29.037  3525  3525 I MotionRecognitionService: Plugged
08-05 02:13:29.037  3525  3525 D MotionRecognitionService:   cableConnection= 1
08-05 02:13:29.037  3525  3525 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-05 02:13:29.037  3525  3525 D MotionRecognitionService: skip setTransmitPower. 
,08-05 02:13:29.037  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-05 02:13:29.037  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-05 02:13:29.037  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-05 02:13:29.042  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 02:13:29.042  5673  5673 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 02:13:29.042  5673  6227 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-05 02:13:29.057  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:13:29.057  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 02:13:32.267  3525  6834 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 02:13:35.652  3525  6834 D SSRM:n  : SIOP:: AP = 310, PST = 278 (W:14), CUR = -45, LCD = 0
,08-05 02:13:35.737  2919  4369 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-05 02:13:35.737  2919  4369 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-05 02:13:35.917  3525  3830 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-05 02:13:35.937  3525  3830 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 02:13:37.857 11413 11478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 02:13:37.857 11413 11478 I jxcore-log: 
,08-05 02:13:37.862 11413 11478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 02:13:37.862 11413 11478 I jxcore-log: 
,08-05 02:13:37.862 11413 11478 D BluetoothAdapter: STATE_ON
,08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:13:37.862 11413 11478 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 02:13:37.862 11413 11478 D BluetoothAdapter: STATE_ON
08-05 02:13:37.867 11413 11478 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 02:13:37.867 11413 11478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 02:13:37.867 11413 11478 I jxcore-log: 
08-05 02:13:37.867 11413 11478 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 02:13:37.867 11413 11478 I jxcore-log: 
,08-05 02:13:38.057  3525  4968 E Watchdog: !@Sync 11 [08-05 02:13:38.062]
,08-05 02:13:38.082 11413 11478 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-05 02:13:38.082 11413 11478 I jxcore-log: Failed to execute UT.
08-05 02:13:38.082 11413 11478 I jxcore-log: 
,08-05 02:13:38.082 11413 11478 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-05 02:13:38.082 11413 11478 I jxcore-log: 
08-05 02:13:38.087 11413 11478 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 02:13:38.087 11413 11478 I jxcore-log: 
,08-05 02:13:38.092 11413 11413 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 02:13:38.742 11481 11481 I FIPS_bssl: FIPS approved mode (1) | 11481 | app_process
,08-05 02:13:38.747 11481 11481 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-05 02:13:38.752 11481 11481 D AndroidRuntime: CheckJNI is OFF
,08-05 02:13:38.752 11481 11481 D AndroidRuntime: readGMSProperty: start
08-05 02:13:38.752 11481 11481 D AndroidRuntime: readGMSProperty: already setted!!
08-05 02:13:38.752 11481 11481 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 02:13:38.752 11481 11481 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 02:13:38.752 11481 11481 D AndroidRuntime: readGMSProperty: end
08-05 02:13:38.752 11481 11481 D AndroidRuntime: addProductProperty: start
,08-05 02:13:38.777 11481 11481 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-05 02:13:38.812 11481 11481 I Radio-JNI: register_android_hardware_Radio DONE
,08-05 02:13:38.817 11481 11481 E AffinityControl: AffinityControl: registerfunction enter
,08-05 02:13:38.827 11481 11481 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 02:13:38.832  3525  4260 D PackageManager: START PACKAGE DELETE: observer{164381691}
08-05 02:13:38.832  3525  4260 D PackageManager: pkg{<packageName>}
08-05 02:13:38.832  3525  4260 D PackageManager: user{0}
08-05 02:13:38.832  3525  4260 D PackageManager: caller{2000}
08-05 02:13:38.832  3525  4260 D PackageManager: flags{2}
08-05 02:13:38.832  3525  4260 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-05 02:13:38.832  3525  4260 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-05 02:13:38.832  3525  4260 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-05 02:13:38.832  3525  4260 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 02:13:38.832  3525  4260 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 02:13:38.832  3525  3830 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-05 02:13:38.832  3525  3830 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-05 02:13:38.832  3525  3830 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-05 02:13:38.832  3525  3830 D ApplicationPolicy: getApplicationUninstallationEnabled
08-05 02:13:38.832  3525  3830 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-05 02:13:38.832  3525  3830 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-05 02:13:38.832  3525  3830 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-05 02:13:38.832  3525  3830 D PackageManager: !@killApplicatoin: 10007, uninstall pkg
08-05 02:13:38.832  3525  3830 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-05 02:13:38.832  3525  3830 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-05 02:13:38.832  3525  3694 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=-1: uninstall pkg
08-05 02:13:38.837  3525  3694 I ActivityManager: Killing 11413:com.test.thalitest/u0a7 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-05 02:13:38.837  3525  3694 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 02:13:38.837  3525  3694 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-05 02:13:38.842  3525  3830 D AASAinstall: there is not AASApackages.xml file
,08-05 02:13:38.847  3525  3694 D ActivityManager: mDVFSHelper.acquire()
,08-05 02:13:38.932  2906 10065 D libEGL  : eglTerminate EGLDisplay = 0xb1aa46fc
08-05 02:13:38.932  3525  5732 D GraphicsStats: Buffer count: 4
08-05 02:13:38.932  3525  3545 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@7d19c18)
08-05 02:13:38.932  3525  5422 I WindowState: WIN DEATH: Window{62e4b01 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:13:38.932  2906  2998 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
,08-05 02:13:38.932  3525  4454 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 02:13:38.932  2906  2991 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
08-05 02:13:38.932  2906 10065 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
08-05 02:13:38.932  3525  4454 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:38.932  3525  4454 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:38.932  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe9ec474
,08-05 02:13:38.937  3525  5422 D InputDispatcher: Focus left window: 11413
,08-05 02:13:38.997  3525  3830 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-05 02:13:39.012  3525  3830 W PackageSettings: Skipping PackageSetting{2ae8eab com.example.hello/10691} due to missing metadata
,08-05 02:13:39.057  3525  3830 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 02:13:39.062  3525  3694 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-05 02:13:39.062  3525  3694 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-05 02:13:39.062  2933  2933 W keystore: ENTER clear_uid from uid 1000 for 10007
08-05 02:13:39.062  3525  3694 E ActivityManager: Failure starting process com.test.thalitest
08-05 02:13:39.062  3525  3694 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5277)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5194)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5030)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3490)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2604)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:5007)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4968)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7379)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9146)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8769)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8924)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2599)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:39.062  3525  3694 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-05 02:13:39.062  3525  3830 I art     : Starting a blocking GC Explicit
08-05 02:13:39.067  3525  3694 I ActivityManager:   Force finishing activity ActivityRecord{70f3970 u0 com.test.thalitest/.MainActivity t108}
08-05 02:13:39.077  3525  3525 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
08-05 02:13:39.082  3525  3694 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-05 02:13:39.082  3525  3694 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
08-05 02:13:39.087  3525  3775 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 02:13:39.092  3525  3775 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-05 02:13:39.092  3525  3775 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-05 02:13:39.092  3525  3775 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-05 02:13:39.092  3525  3775 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4347)
08-05 02:13:39.092  3525  3775 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13476)
08-05 02:13:39.092  3525  3775 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:39.092  3525  3775 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-05 02:13:39.092  3525  3775 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:39.092  3525  3775 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 02:13:39.092  3525  3775 D SecWifiDisplayUtil: Metadata value : none
08-05 02:13:39.092  3525  3694 D InputDispatcher: Focused application released
08-05 02:13:39.092  3525  3775 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5ac17e2 V.E...... R.....ID 0,0-0,0}
08-05 02:13:39.092  3525  3775 W WindowManager: Attempted to add application window with unknown token Token{19bc4e9 ActivityRecord{70f3970 u0 com.test.thalitest/.MainActivity t108 f}}.  Aborting.
08-05 02:13:39.092  2906  2906 I SurfaceFlinger: id=16 createSurf (1528x2333),1 flag=4, VSBConnecti
08-05 02:13:39.097  3525  5125 V WindowOrientationListener: setCurrentAppOrientation :1
08-05 02:13:39.097  3525  5125 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-05 02:13:39.097  3525  3775 D ViewRootImpl: #3 mView = null
08-05 02:13:39.097  3525  3775 W WindowManager: Token{19bc4e9 ActivityRecord{70f3970 u0 com.test.thalitest/.MainActivity t108 f}} already running, starting window not displayed. Unable to add window -- token Token{19bc4e9 ActivityRecord{70f3970 u0 com.test.thalitest/.MainActivity t108 f}} is not valid; is your activity running?
08-05 02:13:39.097  3525  3775 W WindowManager: view not successfully added to wm, removing view
08-05 02:13:39.097  3525  3775 W WindowManager: Exception when adding starting window
08-05 02:13:39.097  3525  3775 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{5ac17e2 V.E...... R.....ID 0,0-0,0} not attached to window manager
08-05 02:13:39.097  3525  3775 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:122)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4404)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13476)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:39.097  3525  3775 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 02:13:39.097  3525  5125 D InputDispatcher: Focus entered window: 7017
08-05 02:13:39.097  7017 10300 D mali_winsys: new_window_surface returns 0x3000,  [1528x2333]-format:1
,08-05 02:13:39.102  3525  3698 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{c2161b3 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-05 02:13:39.102  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
08-05 02:13:39.102  5094  5094 D Launcher: onRestart, Launcher: 200935649
08-05 02:13:39.102  5094  5094 D Launcher: onStart, Launcher: 200935649
08-05 02:13:39.102  5094  5094 D Launcher.HomeView: onStart
08-05 02:13:39.102  3525  3775 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3525 uid:1000
08-05 02:13:39.102  3525  3775 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:13:39.102  3525  3775 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3525 uid:1000
08-05 02:13:39.102  5094  5094 V ActivityThread: updateVisibility : ActivityRecord{5825ff9 token=android.os.BinderProxy@3e50265 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-05 02:13:39.102  3525  3775 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 02:13:39.102  3525  6834 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-05 02:13:39.107  3525  6834 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-05 02:13:39.112  3525  3544 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-05 02:13:39.112  3525  3544 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 02:13:39.112  3525  3525 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 02:13:39.112  3525  3525 I KnoxTimeoutHandler: Shared devices show user statefalse
08-05 02:13:39.112  3525  3525 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
08-05 02:13:39.127  2906  2906 I SurfaceFlinger: id=17 createSurf (1440x2560),1 flag=4, Mauncher
08-05 02:13:39.127  3525  3698 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{c2161b3 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
08-05 02:13:39.127  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008000 mask=ffffffff oldVal=8000 newVal=40008000 diff=40000000
08-05 02:13:39.132  5094  5398 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
08-05 02:13:39.132  3525  4550 V WindowStateAnimator: Finishing drawing window Window{c2161b3 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-05 02:13:39.137  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe9ec40c
08-05 02:13:39.142  3525  3775 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-05 02:13:39.142  3525  3525 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 02:13:39.142  3525  3775 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e969835 u0 com.samsung.android.MtpApplication/.USBConnection t107} time:346605
08-05 02:13:39.142  3525  3775 D ActivityManager: mDVFSHelper.release()
08-05 02:13:39.142  3525  3525 I KnoxTimeoutHandler: SD activityfalse
,08-05 02:13:39.142  2906  2906 I SurfaceFlinger: id=18 createSurf (1592x384),1 flag=4, VSBConnecti
,08-05 02:13:39.147  7017 10300 D mali_winsys: new_window_surface returns 0x3000,  [1592x384]-format:1
,08-05 02:13:39.147  7017  7017 V ActivityThread: updateVisibility : ActivityRecord{66da12 token=android.os.BinderProxy@101ff57 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-05 02:13:39.162  3525  3830 I art     : Explicit concurrent mark sweep GC freed 134531(8MB) AllocSpace objects, 121(2MB) LOS objects, 33% free, 31MB/46MB, paused 1.605ms total 101.526ms
,08-05 02:13:39.172  3525  5099 V WindowStateAnimator: Finishing drawing window Window{b98d6e9 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-05 02:13:39.177  7017  7017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@101ff57 time:346640
,08-05 02:13:39.177  3525  3775 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 02:13:39.177  3525  3830 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-05 02:13:39.177  3525  3525 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-05 02:13:39.177  3525  3830 D AASAuninstall: userId = 0, info.removedAppID = 10007, info.uid = 10007, packageName = com.test.thalitest
08-05 02:13:39.177  3525  3830 D AASAinstall: there is not AASApackages.xml file
08-05 02:13:39.177  3525  3830 D PackageManager: result of delete: 1{164381691}
,08-05 02:13:39.182  3525  3525 I KnoxTimeoutHandler: SD activityfalse
08-05 02:13:39.182  3525  3830 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-05 02:13:39.182  3525  3830 D PackageManager: userId{-1}
08-05 02:13:39.182  3525  3830 D PackageManager: andCode{true}
,08-05 02:13:39.182 11481 11481 I art     : System.exit called, status: 0
08-05 02:13:39.182 11481 11481 I AndroidRuntime: VM exiting with result code 0.
,08-05 02:13:39.187  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe9ec40c
,08-05 02:13:39.187  3525  3830 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=0: pkg removed
,08-05 02:13:39.207  3525  3694 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-05 02:13:39.212  3525  3694 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 02:13:39.212  3525  3694 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-05 02:13:39.217 10412 11492 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
08-05 02:13:39.217 10412 11492 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
08-05 02:13:39.217  3525  5781 V WindowStateAnimator: Finishing drawing window Window{77f0de u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
08-05 02:13:39.217  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbe9ec40c
,08-05 02:13:39.217  5094  5094 D Launcher.HomeView: onStop
08-05 02:13:39.222 10412 11492 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-05 02:13:39.227  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-05 02:13:39.227  4512  4512 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-05 02:13:39.232  5686  6112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 02:13:39.237  5608  5608 E SamsungIME: mOCRHelper is null
,08-05 02:13:39.242  3525  3694 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38ea0de u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{91ed694 7887:com.samsung.klmsagent/u0a21}
08-05 02:13:39.242  7887  7887 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Fri Aug 05 02:13:39 GMT+02:00 2016
,08-05 02:13:39.247  7887  7887 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-05 02:13:39.252  7887  7887 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-05 02:13:39.252  7887  7887 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 02:13:39.252  7887  7887 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-05 02:13:39.252  7887 11495 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-05 02:13:39.252  7887 11495 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
08-05 02:13:39.252  7887 11495 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
08-05 02:13:39.252  7887 11495 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-05 02:13:39.257  5079  5079 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-05 02:13:39.257  3525  3775 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 02:13:39.257  3525  3775 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b7adaa u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t106} time:346722
08-05 02:13:39.257  3525  5104 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-05 02:13:39.257  7887 11495 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-05 02:13:39.257  7887 11495 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-05 02:13:39.262  3525  4444 V NetworkStats: removeUidsLocked() for UIDs [10007]
08-05 02:13:39.262  3525  4444 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 02:13:39.262  3525  4444 V NetworkStats: performPollLocked(flags=0x3)
,08-05 02:13:39.267  7887 11495 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 02:13:39.267  7887 11495 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-05 02:13:39.272  3525  4444 V NetworkStats: performPollLocked() took 10ms
08-05 02:13:39.272  3525  4444 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 02:13:39.272  3525  4417 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 02:13:39.277  7887 11495 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-05 02:13:39.277  3525  5781 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38ea0de u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8211660 3525:system/1000}
,08-05 02:13:39.277  7887 11495 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-05 02:13:39.282  7887 11495 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,08-05 02:13:39.282  3525  4445 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 02:13:39.282  3525  4445 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 02:13:39.287  5068 11497 D RegisteredComponentCache: Collect Tech packages for Knox
,08-05 02:13:39.287  3525  3545 D SettingsProvider: isChangeAllowed() SettingsProvider : name = klm_eula_shown
08-05 02:13:39.287  3525  3545 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-05 02:13:39.287  3525  3545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 02:13:39.287  3525  3545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 02:13:39.287  3525  3545 D SettingsProvider: selectionArgs: false
08-05 02:13:39.287  3525  3545 D SettingsProvider: selectionArgs: 10021
,08-05 02:13:39.297  3525  3545 D SettingsProvider: ret = -1
,08-05 02:13:39.297  7887 11495 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-05 02:13:39.297  7887 11495 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,08-05 02:13:39.317  3525  3525 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
,08-05 02:13:39.317  3525  3525 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-05 02:13:39.317  3525  3525 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
08-05 02:13:39.317  3525  3525 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
08-05 02:13:39.317  3525  3525 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-05 02:13:39.317  3525  3525 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-05 02:13:39.317  3525  3525 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10007 container id = 0
,08-05 02:13:39.317  3525  3681 D EnterpriseDeviceManagerService: Package has changed for user 0
08-05 02:13:39.317  3525  3681 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-05 02:13:39.317  3525  3681 W TextServicesManagerService: no available spell checker services found
,08-05 02:13:39.322  3525  3525 I OTPFW   : ProvisionData::getAllEntries Enter
,08-05 02:13:39.322  3525  3525 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-05 02:13:39.322  3525  3525 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
,08-05 02:13:39.342  7887 11495 D KLMS-2.6.032: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 317
,08-05 02:13:39.342  7887 11495 D KLMS-2.6.032: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
08-05 02:13:39.342  7887 11495 I KLMS-2.6.032: : KLMSSharedPreferences(): getNotificationAppList(): null
08-05 02:13:39.342  7887 11495 D KLMS-2.6.032: : Systemprocess(): Notification App List is Null. Remove Notification.
,08-05 02:13:39.342  7887 11495 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().START: com.test.thalitest
,08-05 02:13:39.347  7887 11495 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-05 02:13:39.347  7887 11495 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: #################################################################
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: #################################################################
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-05 02:13:39.347  7887 11495 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: #################################################################
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-05 02:13:39.347 , 7887 11495 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: #################################################################
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:132)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.IsTrackerIDExistInDeviceDB(Systemprocess.java:658)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:627)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-05 02:13:39.347  7887 11495 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:39.347  7887 11495 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-05 02:13:39.347  7887 11495 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
08-05 02:13:39.347  7887 11495 D KLMS-2.6.032: : Systemprocess(): PackageName is not Exist.
08-05 02:13:39.347  7887 11495 I KLMS-2.6.032: : Systemprocess(): IsTrackerIDExistInDeviceDB().END
08-05 02:13:39.347  7887 11495 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().END
08-05 02:13:39.347  7887 11495 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().END
,08-05 02:13:39.347  7887  7887 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
,08-05 02:13:39.382  3525  4390 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
08-05 02:13:39.382  3525  4390 D UsbHostManager: displayNotification : [02h,02h,01h]
08-05 02:13:39.382  3525  4390 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
08-05 02:13:39.382  3525  4390 D UsbHostManager: displayNotification : [0ah,00h,00h]
,08-05 02:13:39.382  3525  4390 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
08-05 02:13:39.382  3525  4390 D UsbHostManager: displayNotification : [02h,0dh,00h]
,08-05 02:13:39.382  3525  4390 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
08-05 02:13:39.382  3525  4390 D UsbHostManager: displayNotification : [0ah,00h,01h]
08-05 02:13:39.382  3525  4390 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
08-05 02:13:39.382  3525  4390 D UsbHostManager: displayNotification : [09h,00h,00h]
,08-05 02:13:39.382  3525  4501 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
08-05 02:13:39.382  3525  4501 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
08-05 02:13:39.382  3525  4501 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,08-05 02:13:39.387  4902  4902 D MtpClient: onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
08-05 02:13:39.387  4902  4902 D MtpClient: ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,08-05 02:13:39.402  3525  3681 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-05 02:13:39.432  3525  4501 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
08-05 02:13:39.432  3525  4501 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,08-05 02:13:39.442  3525  3681 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-05 02:13:39.442  5094  5094 E Launcher.Model: onPackageRemoved :com.test.thalitest
,08-05 02:13:39.447  5094  5170 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-05 02:13:39.447  5094  5170 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-05 02:13:39.447  3525  3681 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
08-05 02:13:39.447  3525  3681 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-05 02:13:39.452  5094  5170 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-05 02:13:39.452  5094  5170 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 5094
08-05 02:13:39.452  5094  5170 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:489)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$4.run(LauncherModel.java:601)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:605)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:539)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:2472)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-05 02:13:39.452  5094  5170 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:39.467  3525  4417 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-05 02:13:39.467  3525 11505 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop205.tmp: open failed: EROFS (Read-only file system)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:18019)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 02:13:39.467  3525 11505 E DropBoxManagerService: 	... 5 more
08-05 02:13:39.467  3525 11505 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop205.tmp
,08-05 02:13:39.472  3525  5781 W ActivityManager:   Force finishing activity com.sec.android.app.launcher/com.android.launcher2.Launcher
,08-05 02:13:39.487  5094  5094 D Launcher: onTrimMemory. Level: 20
08-05 02:13:39.487  5094  5170 I Process : Sending signal. PID: 5094 SIG: 9
08-05 02:13:39.487  5094  5094 D MenuAppsGridFragment: onDestroyView
,08-05 02:13:39.492  5094  5094 W Launcher.MenuAppsGrid: Trying to exit a state that hasn't been entered
,08-05 02:13:39.522  3525  4417 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-05 02:13:39.587  3525  4417 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-05 02:13:39.617  3525  4417 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-05 02:13:39.617  3525  5127 D GraphicsStats: Buffer count: 3
08-05 02:13:39.622  3525  3545 I WindowState: WIN DEATH: Window{77f0de u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
,08-05 02:13:39.622  2906  5169 I SurfaceFlinger: id=17 Removed Mauncher (4/10)
,08-05 02:13:39.622  2906  2991 I SurfaceFlinger: id=17 Removed Mauncher (-2/10),
,08-05 02:13:39.632  2906  5169 I SurfaceFlinger: id=17 Removed Mauncher (-2/10),
,08-05 02:13:39.637  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbe9ec474,
,08-05 02:13:39.662  3525  4417 I EventHub: Removing device '/dev/input/event11' due to inotify event
,08-05 02:13:39.667  3525  5732 I ActivityManager: Process com.sec.android.app.launcher (pid 5094)(adj 6) has died(292,1360)
,08-05 02:13:39.672  3525  5732 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.launcher, Auto Run ON
,08-05 02:13:39.762  3525  4759 I ActivityManager: Killing 10552:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,08-05 02:13:39.867  3525  5732 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON

```
