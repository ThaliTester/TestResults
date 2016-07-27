#### Test 78968685940d272_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,07-27 09:40:24.168  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-27 09:40:24.268  3597  6913 D SSRM:n  : SIOP:: AP = 320, PST = 339 (W:12), CUR = 186, LCD = 0
--------- beginning of main
07-27 09:40:25.133 11251 11251 I FIPS_bssl: FIPS approved mode (1) | 11251 | app_process
07-27 09:40:25.138 11251 11251 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 09:40:25.143 11251 11251 D AndroidRuntime: CheckJNI is OFF
07-27 09:40:25.143 11251 11251 D AndroidRuntime: readGMSProperty: start
07-27 09:40:25.143 11251 11251 D AndroidRuntime: readGMSProperty: already setted!!
07-27 09:40:25.143 11251 11251 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 09:40:25.143 11251 11251 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 09:40:25.143 11251 11251 D AndroidRuntime: readGMSProperty: end
07-27 09:40:25.143 11251 11251 D AndroidRuntime: addProductProperty: start
07-27 09:40:25.173 11251 11251 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 09:40:25.198 11251 11251 I Radio-JNI: register_android_hardware_Radio DONE
07-27 09:40:25.203 11251 11251 E AffinityControl: AffinityControl: registerfunction enter
07-27 09:40:25.218 11251 11251 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 09:40:25.263  3597  5130 D GameManagerService: identifyGamePackage. com.test.thalitest
07-27 09:40:25.263  3597  5130 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
07-27 09:40:25.273  3597  5130 D ActivityManager: mDVFSHelper.acquire()
07-27 09:40:25.273  3597  5130 V WindowManager: addAppToken: AppWindowToken{e8c9b5c token=Token{a0a65cf ActivityRecord{29dd62e u0 com.test.thalitest/.MainActivity t108}}} to stack=1 task=108 at 0
07-27 09:40:25.288  3597  3837 D SecWifiDisplayUtil: Metadata value : none
07-27 09:40:25.288  3597  3837 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{afef9f4 V.E...... R.....ID 0,0-0,0}
07-27 09:40:25.293  3597  3837 D ISSUE_DEBUG: InputChannelName : d356392 Starting com.test.thalitest
07-27 09:40:25.293 11280 11280 E Zygote  : v2
07-27 09:40:25.293 11280 11280 I libpersona: KNOX_SDCARD checking this for 10007
07-27 09:40:25.293 11280 11280 I libpersona: KNOX_SDCARD not a persona
07-27 09:40:25.293  3597  5130 I ActivityManager: Start proc 11280:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
07-27 09:40:25.293  3597  5130 D InputDispatcher: Focused application set to: xxxx
07-27 09:40:25.293 11280 11280 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 09:40:25.293 11280 11280 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:25.293  3597  5130 D InputDispatcher: Focus left window: 7060
07-27 09:40:25.298 11251 11251 D AndroidRuntime: Shutting down VM
07-27 09:40:25.298  3597  3769 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{e7e3ad1 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-27 09:40:25.298  4522  4522 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-27 09:40:25.298  3597  4443 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-27 09:40:25.298 11280 11280 E Zygote  : accessInfo : 0
07-27 09:40:25.298 11280 11280 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-27 09:40:25.308  2904  2904 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
07-27 09:40:25.328  3597  3837 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3597 uid:1000
07-27 09:40:25.328  3597  3837 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:40:25.328  3597  3837 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3597 uid:1000
07-27 09:40:25.328  3597  3837 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 09:40:25.328  3597  3837 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-27 09:40:25.328 11280 11280 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:40:25.328 11280 11280 D ActivityThread: Added TimaKeyStore provider
07-27 09:40:25.333  3597  5010 V WindowOrientationListener: setCurrentAppOrientation :-1
07-27 09:40:25.333  3597  5010 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-27 09:40:25.338  3597  3769 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{d356392 u0 d0 Starting com.test.thalitest}
07-27 09:40:25.338  4522  4522 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-27 09:40:25.343  3597  5010 D ActivityManager:  Launching com.test.thalitest, updated priority
07-27 09:40:25.353  3597  3597 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-27 09:40:25.353  3597  3765 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-27 09:40:25.373  2904  2992 D libEGL  : eglTerminate EGLDisplay = 0xb6901624
07-27 09:40:25.373  2904  2994 I SurfaceFlinger: id=17 Removed VSBConnecti (7/11)
07-27 09:40:25.378  2904  5133 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
07-27 09:40:25.378  2904  2994 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
07-27 09:40:25.378  2904  2994 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
07-27 09:40:25.383  2904  5133 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
07-27 09:40:25.383  2904  5566 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
07-27 09:40:25.383  2904  2994 I SurfaceFlinger: id=18 Removed VSBConnecti (4/9)
07-27 09:40:25.388  2904  5133 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/9)
07-27 09:40:25.388  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbee77474
07-27 09:40:25.388  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbee77474
07-27 09:40:25.388  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbee77474
07-27 09:40:25.393  7060  7060 V ActivityThread: updateVisibility : ActivityRecord{f78bed9 token=android.os.BinderProxy@1b71ba2 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-27 09:40:25.393  5115  5115 V ActivityThread: updateVisibility : ActivityRecord{63163c token=android.os.BinderProxy@efe6a5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 09:40:25.393  5115  5115 D Launcher: onTrimMemory. Level: 20
07-27 09:40:25.398  3597  3837 V WindowStateAnimator: Finishing drawing window Window{d356392 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-27 09:40:25.403  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbee7740c
,07-27 09:40:25.663  3597  5010 I WindowManager: Screenshot max retries 4 of Token{a0a65cf ActivityRecord{29dd62e u0 com.test.thalitest/.MainActivity t108}} appWin=Window{d356392 u0 d0 Starting com.test.thalitest} drawState=2
,07-27 09:40:25.673  3597  3765 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-27 09:40:25.693  3597  4443 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,07-27 09:40:25.703  3597  6913 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:40:25.708  3597  6913 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:40:25.758 11280 11280 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-27 09:40:25.788 11280 11280 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 09:40:25.798 11280 11280 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 4418-4421)
07-27 09:40:25.798 11280 11280 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 09:40:25.813 11280 11294 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-27 09:40:25.818 11280 11280 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7e5f121}
07-27 09:40:25.818 11280 11280 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 09:40:25.818 11280 11280 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 09:40:25.823 11280 11280 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-27 09:40:25.828  3597  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:40:25.828  3597  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:40:25.828  3597  5114 D BatteryService: online:4, current avg:197, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:203
07-27 09:40:25.828  3597  5114 D BatteryService: stay LED for fully charged
07-27 09:40:25.828  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:40:25.828  3597  3597 I MotionRecognitionService: Plugged
07-27 09:40:25.828  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:40:25.833  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:40:25.833  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:40:25.833  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:25.833  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:40:25.833  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:40:25.838  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:25.838  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:40:25.838  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:25.853  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:25.853  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:25.858 11280 11280 D libEGL  : eglInitialize EGLDisplay = 0xbeaf7e7c
,07-27 09:40:25.893  3597  5114 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,07-27 09:40:25.893  3597  5114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,07-27 09:40:25.948 11280 11280 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-27 09:40:25.963 11280 11280 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 09:40:25.963 11280 11280 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-27 09:40:25.963 11280 11280 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 09:40:25.963 11280 11280 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 09:40:25.978 11280 11280 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-27 09:40:25.983 11280 11280 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung,
,07-27 09:40:26.113 11280 11280 D SecWifiDisplayUtil: Metadata value : none
,07-27 09:40:26.118 11280 11280 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6d382a6 I.E...... R.....ID 0,0-0,0}
,07-27 09:40:26.123 11280 11333 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 09:40:26.128  3597  5128 D ISSUE_DEBUG: InputChannelName : f602da7 com.test.thalitest/com.test.thalitest.MainActivity
,07-27 09:40:26.133  3597  5130 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-27 09:40:26.133  3597  5130 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 09:40:26.133  3597  3597 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 09:40:26.133  3597  3597 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-27 09:40:26.163 11280 11280 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 11280
,07-27 09:40:26.168  3597  5128 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/11280 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 09:40:26.168  3597  4452 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-27 09:40:26.168  3597  4452 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -35]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 09:40:26.168  3597  4452 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 09:40:26.168  3597  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:26.173  3597  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:26.173  3597  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-27 09:40:26.173  3597  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:26.173  3597  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:40:26.173  3597  4452 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-27 09:40:26.173  3597  4452 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 09:40:26.178 11280 11294 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-27 09:40:26.198 11280 11280 D SecWifiDisplayUtil: Metadata value : none
,07-27 09:40:26.213  2904  2904 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,07-27 09:40:26.223  3597  4438 D InputDispatcher: Focus entered window: 11280
,07-27 09:40:26.228  3597  3837 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3597 uid:1000,
07-27 09:40:26.228  3597  3837 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 09:40:26.228  3597  3837 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3597 uid:1000
07-27 09:40:26.228  3597  3837 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 09:40:26.228 11280 11333 D libEGL  : eglInitialize EGLDisplay = 0x9cc007c4
,07-27 09:40:26.228 11280 11333 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 09:40:26.233 11280 11333 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,07-27 09:40:26.238 11280 11280 V ActivityThread: updateVisibility : ActivityRecord{288c239 token=android.os.BinderProxy@4ce9401 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-27 09:40:26.243 11280 11280 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,07-27 09:40:26.243 11280 11280 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-27 09:40:26.248  3597  5010 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 09:40:26.263 11280 11280 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-27 09:40:26.273 11280 11338 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 09:40:26.273 11280 11338 D libEGL  : eglInitialize EGLDisplay = 0x9b3ac3ec
,07-27 09:40:26.318  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbee7740c
,07-27 09:40:26.328  3597  5277 V WindowStateAnimator: Finishing drawing window Window{f602da7 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-27 09:40:26.333 11280 11280 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-27 09:40:26.338  3597  3837 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 09:40:26.338  3597  3597 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 09:40:26.338  3597  3837 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +670ms (total +1s63ms)
,07-27 09:40:26.338  3597  3837 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29dd62e u0 com.test.thalitest/.MainActivity t108} time:154962
07-27 09:40:26.338  3597  3837 D ActivityManager: mDVFSHelper.release()
07-27 09:40:26.338  3597  3597 I KnoxTimeoutHandler: SD activityfalse
07-27 09:40:26.338  3597  3837 D ViewRootImpl: #3 mView = null
,07-27 09:40:26.338  2904  5133 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
07-27 09:40:26.338  2904  2992 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,07-27 09:40:26.353  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbee77474
,07-27 09:40:26.358 11280 11280 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4ce9401 time:154984
07-27 09:40:26.363 11280 11280 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11280
,07-27 09:40:26.558 11280 11280 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 09:40:26.708 11280 11345 D jxcore_app_log: JniHelper::setJavaVM(0xb4834000), pthread_self() = -1700529872
,07-27 09:40:26.713 11280 11345 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 09:40:26.713 11280 11345 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 09:40:26.713 11280 11345 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 09:40:26.713 11280 11345 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 09:40:26.713 11280 11345 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 09:40:26.713 11280 11345 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89755d7 added. We now have 1 listener(s)
,07-27 09:40:26.718 11280 11345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,07-27 09:40:26.718 11280 11345 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,07-27 09:40:26.718 11280 11345 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 09:40:26.718 11280 11345 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 09:40:26.718 11280 11345 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@708bce2 added. We now have 1 listener(s)
07-27 09:40:26.718 11280 11345 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 09:40:26.723 11280 11345 D BluetoothAdapter: STATE_ON
,07-27 09:40:26.723 11280 11345 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-27 09:40:26.728 11280 11345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 09:40:26.728 11280 11345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 09:40:26.728 11280 11345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 09:40:26.728 11280 11345 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 09:40:26.728 11280 11345 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 09:40:26.728 11280 11345 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,07-27 09:40:26.733 11280 11345 D BluetoothAdapter: STATE_ON
,07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:40:26.733 11280 11345 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 09:40:26.733 11280 11345 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 09:40:26.733 11280 11345 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 09:40:26.738 11280 11345 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 09:40:26.738 11280 11280 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 09:40:26.743 11280 11280 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 09:40:26.758 11280 11280 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 09:40:27.078 11280 11346 W jxcore-log: Initializing JXcore engine
07-27 09:40:27.078 11280 11346 W jxcore-log: JXcore engine is ready
,07-27 09:40:27.103  5775  5775 E audit   : type=1400 msg=audit(1469605227.103:266): avc:  denied  { ioctl } for  pid=11346 comm="Thread-1119" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4244 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 09:40:27.103  5775  5775 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:27.103  5775  5775 E audit   : type=1300 msg=audit(1469605227.103:266): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=2 a3=9a91a3c8 items=0 ppid=2968 ppcomm=main pid=11346 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1119" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 09:40:27.103  5775  5775 E audit   : type=1327 msg=audit(1469605227.103:266): proctitle="com.test.thalitest"
07-27 09:40:27.103  5775  5775 E audit   : type=1320 msg=audit(1469605227.103:266): 
07-27 09:40:27.103  5775  5775 E audit   : type=1400 msg=audit(1469605227.103:267): avc:  denied  { ioctl } for  pid=11346 comm="Thread-1119" path="socket:[41111]" dev="sockfs" ino=41111 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-27 09:40:27.103  5775  5775 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 09:40:27.103  5775  5775 E audit   : type=1300 msg=audit(1469605227.103:267): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=2 a3=9a91a3c8 items=0 ppid=2968 ppcomm=main pid=11346 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1119" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 09:40:27.103  5775  5775 E audit   : type=1327 msg=audit(1469605227.103:267): proctitle="com.test.thalitest"
07-27 09:40:27.103  5775  5775 E audit   : type=1320 msg=audit(1469605227.103:267): 
,07-27 09:40:27.108 11280 11346 W jxcore-log: Starting JXcore engine
,07-27 09:40:27.138  4686  4686 D Recents : onTaskStackChanged
,07-27 09:40:27.158 11280 11346 W jxcore-log: Platform android
07-27 09:40:27.158 11280 11346 W jxcore-log: 
07-27 09:40:27.158 11280 11346 W jxcore-log: Process ARCH arm
07-27 09:40:27.158 11280 11346 W jxcore-log: 
,07-27 09:40:27.233 11280 11346 I jxcore-log: JXcore Cordova bridge is ready!
07-27 09:40:27.233 11280 11346 I jxcore-log: 
07-27 09:40:27.233 11280 11346 W jxcore-log: JXcore engine is started
,07-27 09:40:27.238 11280 11345 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 09:40:27.238 11280 11280 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 09:40:28.283  3597  4496 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/108_task.xml.bak
,07-27 09:40:31.718  3597  6913 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:40:31.933  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:40:31.933  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:40:33.503 11280 11346 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 09:40:33.503 11280 11346 I jxcore-log: 
,07-27 09:40:33.503 11280 11346 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 09:40:33.503 11280 11346 I jxcore-log: 
,07-27 09:40:33.508 11280 11346 D BluetoothAdapter: STATE_ON
,07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 09:40:33.508 11280 11346 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 09:40:33.508 11280 11346 D BluetoothAdapter: STATE_ON
,07-27 09:40:33.508 11280 11346 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 09:40:33.508 11280 11346 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 09:40:33.508 11280 11346 I jxcore-log: 
,07-27 09:40:33.513 11280 11346 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 09:40:33.513 11280 11346 I jxcore-log: 
,07-27 09:40:33.723 11280 11346 I jxcore-log: Unit Test app is loaded
07-27 09:40:33.723 11280 11346 I jxcore-log: 
,07-27 09:40:33.723 11280 11346 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 09:40:33.723 11280 11346 I jxcore-log: 
,07-27 09:40:33.728 11280 11280 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 09:40:33.728 11280 11346 I jxcore-log: My device name is: samsung-SM-N910C
07-27 09:40:33.728 11280 11346 I jxcore-log: 
,07-27 09:40:33.728 11280 11346 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 09:40:33.728 11280 11346 I jxcore-log: 
,07-27 09:40:34.278  3597  6913 D SSRM:n  : SIOP:: AP = 340, PST = 336 (W:10), CUR = 197, LCD = 0
,07-27 09:40:35.298  3597  3903 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 09:40:35.318  3597  3903 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-27 09:40:35.953  3597  5128 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:40:35.953  3597  5128 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:40:35.953  3597  5128 D BatteryService: online:4, current avg:-40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:-298
07-27 09:40:35.953  3597  5128 D BatteryService: stay LED for fully charged
07-27 09:40:35.953  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:40:35.953  3597  3597 I MotionRecognitionService: Plugged
07-27 09:40:35.953  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:40:35.953  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:40:35.953  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
07-27 09:40:35.953  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:35.953  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:35.953  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 09:40:35.958  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:35.958  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:40:35.958  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:35.973  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:35.973  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:36.203 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 09:40:36.203 11280 11346 I jxcore-log: 
,07-27 09:40:36.443 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 09:40:36.443 11280 11346 I jxcore-log: 
,07-27 09:40:36.458 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 09:40:36.458 11280 11346 I jxcore-log: 
,07-27 09:40:36.458 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 09:40:36.458 11280 11346 I jxcore-log: 
,07-27 09:40:36.468 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 09:40:36.468 11280 11346 I jxcore-log: 
,07-27 09:40:36.468 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 09:40:36.468 11280 11346 I jxcore-log: 
,07-27 09:40:36.928  3597  4974 E Watchdog: !@Sync 5 [07-27 09:40:36.933]
,07-27 09:40:37.688 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 09:40:37.688 11280 11346 I jxcore-log: 
,07-27 09:40:37.693 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 09:40:37.693 11280 11346 I jxcore-log: 
,07-27 09:40:37.698 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 09:40:37.698 11280 11346 I jxcore-log: 
,07-27 09:40:37.793 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 09:40:37.793 11280 11346 I jxcore-log: 
,07-27 09:40:38.293 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 09:40:38.293 11280 11346 I jxcore-log: 
,07-27 09:40:38.328 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 09:40:38.328 11280 11346 I jxcore-log: 
,07-27 09:40:38.333 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 09:40:38.333 11280 11346 I jxcore-log: 
,07-27 09:40:38.448 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 09:40:38.448 11280 11346 I jxcore-log: 
,07-27 09:40:38.463 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 09:40:38.463 11280 11346 I jxcore-log: 
,07-27 09:40:38.463 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 09:40:38.463 11280 11346 I jxcore-log: 
,07-27 09:40:38.468 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 09:40:38.468 11280 11346 I jxcore-log: 
,07-27 09:40:38.478 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 09:40:38.478 11280 11346 I jxcore-log: 
,07-27 09:40:38.488 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 09:40:38.488 11280 11346 I jxcore-log: 
,07-27 09:40:38.538 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 09:40:38.538 11280 11346 I jxcore-log: 
,07-27 09:40:38.543 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 09:40:38.543 11280 11346 I jxcore-log: 
,07-27 09:40:38.558 11280 11346 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 09:40:38.558 11280 11346 I jxcore-log: 
,07-27 09:40:38.563 11280 11346 D BluetoothAdapter: STATE_ON
,07-27 09:40:38.563 11280 11346 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 09:40:38.563 11280 11346 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-27 09:40:38.563 11280 11346 I jxcore-log: 
,07-27 09:40:43.683  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:40:43.683  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:40:44.173  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:40:44.303  3597  6913 D SSRM:n  : SIOP:: AP = 340, PST = 335 (W:10), CUR = -40, LCD = 0
,07-27 09:40:46.103  3597  3615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:40:46.103  3597  3615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:40:46.103  3597  3615 D BatteryService: online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:219
07-27 09:40:46.103  3597  3615 D BatteryService: stay LED for fully charged
,07-27 09:40:46.103  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:40:46.108  3597  3597 I MotionRecognitionService: Plugged
07-27 09:40:46.108  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:40:46.108  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:40:46.108  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:40:46.118  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:46.118  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:46.118  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:40:46.133  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:40:46.138  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:46.148  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:46.148  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:46.148  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:40:52.473  3597  6915 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-27 09:40:52.488  3597  3765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f62bd33 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{89b7cd1 10375:com.samsung.android.sm.provider/1000}
,07-27 09:40:52.583  3597  6915 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-27 09:40:52.598  3597  3765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9725e69 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{89b7cd1 10375:com.samsung.android.sm.provider/1000}
,07-27 09:40:54.333  3597  6913 D SSRM:n  : SIOP:: AP = 330, PST = 335 (W:10), CUR = 66, LCD = 0
,07-27 09:40:56.248  3597  5130 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:40:56.248  3597  5130 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:40:56.248  3597  5130 D BatteryService: online:4, current avg:153, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:211
07-27 09:40:56.248  3597  5130 D BatteryService: stay LED for fully charged
,07-27 09:40:56.248  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:40:56.258  3597  3597 I MotionRecognitionService: Plugged
07-27 09:40:56.258  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:40:56.258  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:40:56.258  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:40:56.263  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:56.263  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:40:56.263  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:40:56.273  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:40:56.273  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:40:56.288  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:56.288  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:40:56.288  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:00.748  5769  6781 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:41:04.173  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:41:04.368  3597  6913 D SSRM:n  : SIOP:: AP = 320, PST = 334 (W:10), CUR = 153, LCD = 0
,07-27 09:41:05.293  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:41:05.293  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:41:06.388  3597  5278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:41:06.388  3597  5278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:41:06.388  3597  5278 D BatteryService: online:4, current avg:181, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:192
07-27 09:41:06.388  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:41:06.388  3597  5278 D BatteryService: stay LED for fully charged
,07-27 09:41:06.393  3597  3597 I MotionRecognitionService: Plugged
07-27 09:41:06.393  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:41:06.393  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:41:06.393  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:06.403  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:06.403  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:06.403  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:06.438  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:06.438  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:06.438  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:06.438  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:41:06.438  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:06.933  3597  4974 E Watchdog: !@Sync 6 [07-27 09:41:06.934]
,07-27 09:41:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:41:07.538  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:41:07.538  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:41:14.403  3597  6913 D SSRM:n  : SIOP:: AP = 310, PST = 333 (W:12), CUR = 181, LCD = 0
,07-27 09:41:16.538  3597  5277 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:41:16.543  3597  5277 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:41:16.543  3597  5277 D BatteryService: online:4, current avg:186, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:201
07-27 09:41:16.543  3597  5277 D BatteryService: stay LED for fully charged
,07-27 09:41:16.543  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:41:16.543  3597  3597 I MotionRecognitionService: Plugged
07-27 09:41:16.543  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:41:16.543  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:41:16.543  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:16.553  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:16.553  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:16.553  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:16.568  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:41:16.568  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:16.578  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:16.578  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:16.578  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:24.183  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:41:24.438  3597  6913 D SSRM:n  : SIOP:: AP = 310, PST = 324 (W:12), CUR = 186, LCD = 0
,07-27 09:41:26.693  3597  5128 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:41:26.693  3597  5128 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:41:26.693  3597  5128 D BatteryService: online:4, current avg:183, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:160
07-27 09:41:26.693  3597  5128 D BatteryService: stay LED for fully charged
,07-27 09:41:26.698  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:41:26.698  3597  3597 I MotionRecognitionService: Plugged
07-27 09:41:26.698  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:41:26.698  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:41:26.703  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:26.708  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:26.708  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:26.708  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:26.728  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:41:26.728  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:41:26.733  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:26.733  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:26.733  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:34.468  3597  6913 D SSRM:n  : SIOP:: AP = 310, PST = 320 (W:12), CUR = 183, LCD = 0
,07-27 09:41:36.833  3597  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:41:36.833  3597  4913 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:41:36.833  3597  4913 D BatteryService: online:4, current avg:179, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:179
07-27 09:41:36.833  3597  4913 D BatteryService: stay LED for fully charged
,07-27 09:41:36.833  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:41:36.838  3597  3597 I MotionRecognitionService: Plugged
07-27 09:41:36.838  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:41:36.838  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:41:36.838  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:36.848  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,07-27 09:41:36.848  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:36.848  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:36.873  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:41:36.873  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:36.878  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-27 09:41:36.878  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:36.878  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:36.938  3597  4974 E Watchdog: !@Sync 7 [07-27 09:41:36.941]
,07-27 09:41:42.978  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:41:42.978  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:41:44.188  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:41:44.498  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 318 (W:12), CUR = 179, LCD = 0
,07-27 09:41:46.973  3597  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:41:46.973  3597  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:41:46.973  3597  4438 D BatteryService: online:4, current avg:174, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:182
07-27 09:41:46.973  3597  4438 D BatteryService: stay LED for fully charged
,07-27 09:41:46.973  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:41:46.978  3597  3597 I MotionRecognitionService: Plugged
07-27 09:41:46.978  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:41:46.978  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:41:46.978  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:46.988  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:46.988  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:46.988  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:46.998  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:41:46.998  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:47.013  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:47.013  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:47.013  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:41:54.528  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 316 (W:14), CUR = 174, LCD = 0
,07-27 09:41:57.113  3597  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:41:57.113  3597  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:41:57.113  3597  5114 D BatteryService: online:4, current avg:171, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:168
07-27 09:41:57.113  3597  5114 D BatteryService: stay LED for fully charged
,07-27 09:41:57.118  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:41:57.123  3597  3597 I MotionRecognitionService: Plugged
07-27 09:41:57.123  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:41:57.123  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:41:57.123  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:41:57.128  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:41:57.128  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:41:57.128  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:41:57.143  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:41:57.143  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:41:57.158  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:57.158  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:41:57.158  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:01.293  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:42:01.293  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:42:04.188  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:42:04.563  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 312 (W:14), CUR = 171, LCD = 0
,07-27 09:42:06.938  3597  4974 E Watchdog: !@Sync 8 [07-27 09:42:06.942]
,07-27 09:42:07.253  3597  4645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:42:07.253  3597  4645 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:42:07.253  3597  4645 D BatteryService: online:4, current avg:166, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:165
07-27 09:42:07.253  3597  4645 D BatteryService: stay LED for fully charged
,07-27 09:42:07.258  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:42:07.263  3597  3597 I MotionRecognitionService: Plugged
07-27 09:42:07.263  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:42:07.263  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:42:07.263  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:07.273  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:07.273  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:07.273  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:07.283  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:42:07.283  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:07.298  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:07.298  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:07.298  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:42:07.633  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:42:07.633  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:42:07.733  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 96ms lastUpdatedAfter : 146318ms
,07-27 09:42:14.598  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CUR = 166, LCD = 0
,07-27 09:42:17.398  3597  5848 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:42:17.398  3597  5848 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:42:17.398  3597  5848 D BatteryService: online:4, current avg:163, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:170
07-27 09:42:17.398  3597  5848 D BatteryService: stay LED for fully charged
,07-27 09:42:17.398  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:42:17.403  3597  3597 I MotionRecognitionService: Plugged
07-27 09:42:17.403  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:42:17.403  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:42:17.403  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:17.413  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:17.413  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:17.413  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:17.438  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:42:17.438  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:17.443  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:17.443  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-27 09:42:17.443  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:24.193  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:42:24.628  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CUR = 163, LCD = 0
,07-27 09:42:27.518  3597  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:42:27.518  3597  5011 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:42:27.518  3597  5011 D BatteryService: online:4, current avg:159, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:160
07-27 09:42:27.523  3597  5011 D BatteryService: stay LED for fully charged
,07-27 09:42:27.523  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:42:27.528  3597  3597 I MotionRecognitionService: Plugged
07-27 09:42:27.528  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:42:27.528  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:42:27.528  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:27.533  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:27.533  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:27.538  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:27.553  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:42:27.553  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:27.563  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:27.563  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:27.563  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:34.658  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:16), CUR = 159, LCD = 0
,07-27 09:42:36.948  3597  4974 E Watchdog: !@Sync 9 [07-27 09:42:36.949]
,07-27 09:42:37.663  3597  4911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:42:37.663  3597  4911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:42:37.663  3597  4911 D BatteryService: online:4, current avg:156, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:146
07-27 09:42:37.663  3597  4911 D BatteryService: stay LED for fully charged
,07-27 09:42:37.668  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:42:37.673  3597  3597 I MotionRecognitionService: Plugged
07-27 09:42:37.673  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:42:37.673  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:42:37.673  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:37.678  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:37.683  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:42:37.683  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:37.698  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:42:37.698  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:37.708  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:37.708  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:37.708  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:44.193  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:42:44.688  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 303 (W:16), CUR = 156, LCD = 0
,07-27 09:42:47.798  3597  3615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:42:47.803  3597  3615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:42:47.803  3597  3615 D BatteryService: online:4, current avg:154, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:154
07-27 09:42:47.803  3597  3615 D BatteryService: stay LED for fully charged
,07-27 09:42:47.803  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:42:47.808  3597  3597 I MotionRecognitionService: Plugged
07-27 09:42:47.808  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:42:47.808  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:42:47.808  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:47.813  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:47.813  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:47.813  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:47.833  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:42:47.833  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:47.843  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:47.843  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:47.843  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:54.723  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:16), CUR = 154, LCD = 0
,07-27 09:42:57.938  3597  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:42:57.938  3597  4913 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:42:57.938  3597  4913 D BatteryService: online:4, current avg:152, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:158
07-27 09:42:57.938  3597  4913 D BatteryService: stay LED for fully charged
07-27 09:42:57.943  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:42:57.948  3597  3597 I MotionRecognitionService: Plugged
07-27 09:42:57.948  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:42:57.948  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:42:57.948  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:42:57.958  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:57.958  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:42:57.958  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:42:57.978  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:42:57.978  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:42:57.983  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:57.983  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:42:57.983  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:42:59.998  3597  4400 V AlarmManager: Expired Alarm result :8
07-27 09:42:59.998  3597  4400 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=308620 batch.start=319226
,07-27 09:43:00.013  3597  3597 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
07-27 09:43:00.013  3597  3597 V AlarmManagerEXT: <AppSync3 Whitelist>
,07-27 09:43:00.013  3597  3597 V AlarmManagerEXT: (AppSync) ### 0 added ###,
,07-27 09:43:00.028  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 09:43:00.028  4522  4522 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:43:00.028  4522  4522 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:43:00.053  4522  4522 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
07-27 09:43:00.058  4522  4522 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:43:00.068  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.068  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.073  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.073  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:43:00.073  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:43:00.073  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:43:00.073  4522  4522 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:00.158  4522  4522 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:43:01.113  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:43:01.113  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:43:03.533  3597  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-27 09:43:03.538  3597  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:43:03.548  3597  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:43:03.563  3597  4390 I TLC_TIMA_PKM_initialize: initializing...
,07-27 09:43:03.563  3597  4390 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-27 09:43:03.563  3597  4390 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-27 09:43:03.563  3597  4390 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
,07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
,07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: device_id = 0x0
07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: tlc_open() was called
07-27 09:43:03.568  3597  4390 I TZ: mc_tlc_communication: Opening MobiCore device
,07-27 09:43:03.573  3597  4390 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-27 09:43:03.578  3597  4390 I TZ: mc_tlc_communication: Opening the session
,07-27 09:43:03.598  3597  4390 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-27 09:43:03.613  3597  4390 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-27 09:43:04.193  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:43:04.743  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:16), CUR = 152, LCD = 0
,07-27 09:43:06.953  3597  4974 E Watchdog: !@Sync 10 [07-27 09:43:06.954]
,07-27 09:43:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:43:07.853  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:43:07.853  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:43:08.053  3597  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:43:08.053  3597  4913 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:43:08.053  3597  4913 D BatteryService: online:4, current avg:150, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:151
07-27 09:43:08.053  3597  4913 D BatteryService: stay LED for fully charged
07-27 09:43:08.053  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:08.058  3597  3597 I MotionRecognitionService: Plugged
07-27 09:43:08.058  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:43:08.058  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:08.058  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:08.058  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:08.058  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:08.058  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:08.063  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:43:08.063  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:08.078  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:08.078  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:08.078  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:10.308  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 09:43:10.308  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:43:10.323  3597  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 09:43:10.323  3597  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:43:10.603  3597  4400 V AlarmManager: Expired Alarm result :4
,07-27 09:43:10.633  4928  4928 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 09:43:10.633  4928  4928 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-27 09:43:10.678  3597  3765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b819dfa u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a22db83 7749:com.google.android.gms/u0a14}
,07-27 09:43:10.708  3597  4400 I ActivityManager: Start proc 11567:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-27 09:43:10.708 11567 11567 E Zygote  : v2
07-27 09:43:10.713 11567 11567 I libpersona: KNOX_SDCARD checking this for 1000
,07-27 09:43:10.713 11567 11567 I libpersona: KNOX_SDCARD not a persona
,07-27 09:43:10.718 11567 11567 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-27 09:43:10.718 11567 11567 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:43:10.718  4928  4928 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 09:43:10.723 11567 11567 E Zygote  : accessInfo : 0
,07-27 09:43:10.748 11567 11567 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:43:10.748 11567 11567 D ActivityThread: Added TimaKeyStore provider
,07-27 09:43:10.783 11567 11567 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-27 09:43:10.788  7749 11581 I EventLogChimeraService: Aggregate from 1469603590440 (log), 1469603590440 (data)
,07-27 09:43:10.913  3597  3765 I ActivityManager: Start proc 11588:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,07-27 09:43:10.913 11588 11588 E Zygote  : v2
07-27 09:43:10.913 11588 11588 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:43:10.913 11588 11588 I libpersona: KNOX_SDCARD not a persona
,07-27 09:43:10.918 11588 11588 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 09:43:10.918 11588 11588 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:43:10.918 11588 11588 E Zygote  : accessInfo : 0
,07-27 09:43:10.943 11588 11588 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:43:10.943 11588 11588 D ActivityThread: Added TimaKeyStore provider
,07-27 09:43:10.958  3597  5129 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f86dd u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{841f252 11588:com.samsung.android.sm/1000}
,07-27 09:43:10.978  3597  5277 I ActivityManager: Killing 10425:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,07-27 09:43:10.998  3597  5129 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f86dd u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a22db83 7749:com.google.android.gms/u0a14}
,07-27 09:43:11.023  3597  4913 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e91ce20 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{841f252 11588:com.samsung.android.sm/1000}
,07-27 09:43:11.033  3597  5278 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,07-27 09:43:11.063  3597  4645 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e91ce20 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a22db83 7749:com.google.android.gms/u0a14}
,07-27 09:43:11.288  7749 11600 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 09:43:11.343  7749 11600 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 09:43:11.348  3597  5011 I ActivityManager: Killing 10441:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): DHA:empty #31
,07-27 09:43:11.418  3597  3615 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,07-27 09:43:14.503  2913  4368 D Netd    : Iface wlan0 link up
07-27 09:43:14.503  4928  4928 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
,07-27 09:43:14.508  3597  3776 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 09:43:14.508  3597  3776 D Tethering: interfaceStatusChanged wlan0, true
,07-27 09:43:14.508  4928  4928 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-27 09:43:14.518  3597  4444 D WifiP2pService: InactiveState{ what=147461 }
,07-27 09:43:14.518  3597  4444 D WifiP2pService: P2pEnabledState{ what=147461 }
07-27 09:43:14.518  3597  4444 D WifiP2pService: DefaultState{ what=147461 }
,07-27 09:43:14.553  3597  3765 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9fac99b u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{884e745 4522:com.android.systemui/u0a60}
,07-27 09:43:14.768  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:18), CUR = 150, LCD = 0
,07-27 09:43:18.203  3597  3615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:43:18.203  3597  3615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:43:18.203  3597  3615 D BatteryService: online:4, current avg:147, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:141
07-27 09:43:18.203  3597  3615 D BatteryService: stay LED for fully charged
,07-27 09:43:18.203  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:18.213  3597  3597 I MotionRecognitionService: Plugged
07-27 09:43:18.213  3597  3597 D MotionRecognitionService:   cableConnection= 1,
07-27 09:43:18.213  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:18.213  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:18.223  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:43:18.223  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:18.223  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:18.243  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:43:18.243  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:18.248  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-27 09:43:18.248  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:18.248  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:24.198  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:43:24.793  3597  6913 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:18), CUR = 147, LCD = 0
,07-27 09:43:28.053  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:43:28.053  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:43:28.348  3597  5010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:43:28.348  3597  5010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:43:28.348  3597  5010 D BatteryService: online:4, current avg:145, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:141
07-27 09:43:28.348  3597  5010 D BatteryService: stay LED for fully charged
,07-27 09:43:28.348  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:43:28.353  3597  3597 I MotionRecognitionService: Plugged
07-27 09:43:28.353  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:43:28.353  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:28.353  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:28.363  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:43:28.363  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:28.363  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:28.383  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:43:28.383  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:28.388  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:28.388  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:28.388  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:34.823  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 299 (W:18), CUR = 145, LCD = 0
,07-27 09:43:36.953  3597  4974 E Watchdog: !@Sync 11 [07-27 09:43:36.956]
,07-27 09:43:38.478  3597  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:43:38.478  3597  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:43:38.478  3597  4438 D BatteryService: online:4, current avg:143, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:132
07-27 09:43:38.478  3597  4438 D BatteryService: stay LED for fully charged
,07-27 09:43:38.478  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:38.483  3597  3597 I MotionRecognitionService: Plugged
07-27 09:43:38.483  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:43:38.483  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:38.483  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:38.493  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:38.493  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:38.493  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:38.513  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:43:38.513  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:38.518  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:38.518  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:38.518  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:42.293  9878  9893 I PlayCommon: [957] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:43:42.338  5769  5769 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:43:42.358  5769  5769 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:43:42.363  5769  5769 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:43:42.428  9878  9893 I PlayCommon: [957] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 09:43:42.428  9878  9893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 09:43:42.428  9878  9893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:43:42.433  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:43:42.433  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:43:42.438  2913  4371 D EnterpriseController: netId is 0
07-27 09:43:42.438  2913  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10031
,07-27 09:43:42.623  9878  9893 I PlayCommon: [957] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,07-27 09:43:44.203  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:43:44.853  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 298 (W:18), CUR = 143, LCD = 0
,07-27 09:43:48.618  3597  5278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:43:48.623  3597  5278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:43:48.623  3597  5278 D BatteryService: online:4, current avg:140, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:154
07-27 09:43:48.623  3597  5278 D BatteryService: stay LED for fully charged
,07-27 09:43:48.623  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:43:48.628  3597  3597 I MotionRecognitionService: Plugged
07-27 09:43:48.628  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:43:48.628  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:48.628  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:43:48.638  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:48.638  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:48.638  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:48.658  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:43:48.658  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:48.663  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:48.663  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:48.663  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:54.883  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 298 (W:20), CUR = 140, LCD = 0
,07-27 09:43:58.763  3597  5130 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:43:58.763  3597  5130 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:43:58.763  3597  5130 D BatteryService: online:4, current avg:138, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:138
07-27 09:43:58.763  3597  5130 D BatteryService: stay LED for fully charged
07-27 09:43:58.768  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:43:58.773  3597  3597 I MotionRecognitionService: Plugged
07-27 09:43:58.773  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:43:58.773  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:43:58.773  3597  3597 D MotionRecognitionService: skip setTransmitPower. ,
,07-27 09:43:58.783  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:58.783  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:43:58.783  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:43:58.803  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:43:58.803  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:43:58.808  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:43:58.808  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-27 09:43:58.808  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:43:59.998  3597  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:44:04.203  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:44:04.913  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 297 (W:20), CUR = 138, LCD = 0
,07-27 09:44:06.958  3597  4974 E Watchdog: !@Sync 12 [07-27 09:44:06.961]
,07-27 09:44:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:44:07.983  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:44:07.983  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:44:08.908  3597  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:44:08.908  3597  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:44:08.908  3597  5114 D BatteryService: online:4, current avg:136, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:129
07-27 09:44:08.908  3597  5114 D BatteryService: stay LED for fully charged
,07-27 09:44:08.913  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:44:08.918  3597  3597 I MotionRecognitionService: Plugged
07-27 09:44:08.918  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:44:08.918  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:44:08.918  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:08.923  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:08.923  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:08.923  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:08.943  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:44:08.943  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-27 09:44:08.948  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:08.948  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:08.948  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:11.333  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:44:11.333  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:44:14.948  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:20), CUR = 136, LCD = 0
,07-27 09:44:19.048  3597  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:44:24.208  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:44:24.973  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:20), CUR = 136, LCD = 0
,07-27 09:44:29.203  3597  5128 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:44:29.203  3597  5128 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:44:29.203  3597  5128 D BatteryService: online:4, current avg:133, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:128
07-27 09:44:29.203  3597  5128 D BatteryService: stay LED for fully charged
07-27 09:44:29.203  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:44:29.208  3597  3597 I MotionRecognitionService: Plugged
,07-27 09:44:29.208  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:44:29.208  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:44:29.208  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:29.213  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:44:29.213  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:29.213  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:29.228  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:44:29.228  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:29.238  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:29.238  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:29.238  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:35.003  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:22), CUR = 133, LCD = 0
,07-27 09:44:36.963  3597  4974 E Watchdog: !@Sync 13 [07-27 09:44:36.967]
,07-27 09:44:39.338  3597  5278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:44:39.338  3597  5278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:44:39.338  3597  5278 D BatteryService: online:4, current avg:130, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:120
07-27 09:44:39.338  3597  5278 D BatteryService: stay LED for fully charged
,07-27 09:44:39.343  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:44:39.348  3597  3597 I MotionRecognitionService: Plugged
07-27 09:44:39.348  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:44:39.348  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 09:44:39.348  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:39.358  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:44:39.358  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:39.358  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:39.378  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:44:39.378  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:39.383  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,07-27 09:44:39.383  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:39.383  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:42.828  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:44:42.828  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:44:44.208  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:44:45.033  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 294 (W:22), CUR = 130, LCD = 0
,07-27 09:44:48.523 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.523 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.538 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.538 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.538  2913  4371 D EnterpriseController: netId is 0
07-27 09:44:48.538  2913  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10202
,07-27 09:44:48.743 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.743 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.788 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.788 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.843 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:48.853 10862 10972 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 09:44:49.478  3597  4911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:44:49.478  3597  4911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:44:49.478  3597  4911 D BatteryService: online:4, current avg:130, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:134
07-27 09:44:49.483  3597  4911 D BatteryService: stay LED for fully charged
,07-27 09:44:49.483  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:44:49.488  3597  3597 I MotionRecognitionService: Plugged
07-27 09:44:49.488  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:44:49.488  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:44:49.488  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:49.498  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:44:49.498  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:49.498  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:49.518  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:44:49.518  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:49.523  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:49.523  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:49.523  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:44:55.068  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 294 (W:22), CUR = 130, LCD = 0
,07-27 09:44:59.623  3597  5128 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:44:59.623  3597  5128 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:44:59.623  3597  5128 D BatteryService: online:4, current avg:129, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:131
07-27 09:44:59.623  3597  5128 D BatteryService: stay LED for fully charged
,07-27 09:44:59.623  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:44:59.628  3597  3597 I MotionRecognitionService: Plugged
07-27 09:44:59.628  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:44:59.628  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:44:59.628  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:44:59.638  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:59.638  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:44:59.638  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:44:59.653  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:44:59.653  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:44:59.663  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:59.663  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:44:59.663  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:04.213  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:45:05.103  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:22), CUR = 129, LCD = 0
,07-27 09:45:06.978  3597  4974 E Watchdog: !@Sync 14 [07-27 09:45:06.978]
,07-27 09:45:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:45:08.118  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:45:08.118  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:45:08.198  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 72ms lastUpdatedAfter : 180465ms
,07-27 09:45:09.773  3597  5278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:45:09.773  3597  5278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:45:09.773  3597  5278 D BatteryService: online:4, current avg:127, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:130
07-27 09:45:09.773  3597  5278 D BatteryService: stay LED for fully charged
,07-27 09:45:09.773  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:45:09.778  3597  3597 I MotionRecognitionService: Plugged
07-27 09:45:09.778  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:45:09.783  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:45:09.783  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:45:09.788  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:45:09.788  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:45:09.788  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:45:09.808  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:45:09.808  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:45:09.813  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:45:09.813  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:45:09.813  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:10.733  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:45:10.733  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:45:15.138  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:24), CUR = 127, LCD = 0
,07-27 09:45:19.918  3597  3617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:45:19.918  3597  3617 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:45:19.918  3597  3617 D BatteryService: online:4, current avg:126, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:125
07-27 09:45:19.918  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:45:19.918  3597  3617 D BatteryService: stay LED for fully charged
,07-27 09:45:19.923  3597  3597 I MotionRecognitionService: Plugged
07-27 09:45:19.923  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:45:19.928  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:45:19.928  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:45:19.933  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:45:19.933  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:45:19.933  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:45:19.958  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:45:19.958  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:45:19.963  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:45:19.963  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:45:19.963  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:24.213  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:45:25.168  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:24), CUR = 126, LCD = 0
,07-27 09:45:30.068  3597  3615 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:45:30.068  3597  3615 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:45:30.068  3597  3615 D BatteryService: online:4, current avg:123, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:118
07-27 09:45:30.068  3597  3615 D BatteryService: stay LED for fully charged
,07-27 09:45:30.068  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:45:30.073  3597  3597 I MotionRecognitionService: Plugged
07-27 09:45:30.073  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:45:30.073  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:45:30.073  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:45:30.083  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:45:30.083  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:45:30.083  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:45:30.103  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:45:30.103  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:45:30.108  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:45:30.113  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:45:30.113  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:45:35.203  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:24), CUR = 123, LCD = 0
,07-27 09:45:36.983  3597  4974 E Watchdog: !@Sync 15 [07-27 09:45:36.988]
,07-27 09:45:44.218  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:45:45.228  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:24), CUR = 123, LCD = 0
,07-27 09:45:55.258  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 291 (W:26), CUR = 123, LCD = 0
,07-27 09:45:55.928  2976  2976 I bootchecker: bootchecker wake up!!
,07-27 09:46:00.168  3597  4645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:46:00.168  3597  4645 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4379, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:46:00.168  3597  4645 D BatteryService: online:4, current avg:8, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:46:00.168  3597  4645 D BatteryService: stay LED for fully charged
,07-27 09:46:00.168  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:46:00.178  3597  3597 I MotionRecognitionService: Plugged
07-27 09:46:00.178  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:46:00.178  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:46:00.178  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:46:00.183  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:46:00.183  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:46:00.183  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:46:00.208  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:46:00.208  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:46:00.213  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:46:00.213  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:46:00.213  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:46:04.218  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:46:05.293  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:26), CUR = 8, LCD = 0
,07-27 09:46:06.993  3597  4974 E Watchdog: !@Sync 16 [07-27 09:46:06.997]
,07-27 09:46:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:46:08.303  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:46:08.303  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:46:15.318  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:26), CUR = 8, LCD = 0
,07-27 09:46:24.223  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:46:25.343  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:26), CUR = 8, LCD = 0
,07-27 09:46:30.268  3597  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:46:30.268  3597  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:46:30.268  3597  4438 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:46:30.268  3597  4438 D BatteryService: stay LED for fully charged
,07-27 09:46:30.268  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:46:30.273  3597  3597 I MotionRecognitionService: Plugged
07-27 09:46:30.273  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:46:30.273  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:46:30.273  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:46:30.283  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:46:30.283  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:46:30.283  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:46:30.303  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:46:30.303  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:46:30.308  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:46:30.308  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:46:30.308  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:46:35.373  3597  6913 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:28), LCD = 0
,07-27 09:46:36.998  3597  4974 E Watchdog: !@Sync 17 [07-27 09:46:37.003]
,07-27 09:46:44.223  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:46:45.403  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:28), LCD = 0
,07-27 09:46:55.433  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:28), LCD = 0
,07-27 09:46:59.998  3597  4400 V AlarmManager: Expired Alarm result :8
07-27 09:46:59.998  3597  4400 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=548620 batch.start=672546
,07-27 09:47:00.363  3597  3617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:47:00.368  3597  3617 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:47:00.368  3597  3617 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:47:00.368  3597  3617 D BatteryService: stay LED for fully charged
07-27 09:47:00.368  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:47:00.368  3597  3597 I MotionRecognitionService: Plugged
07-27 09:47:00.368  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:47:00.368  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:47:00.368  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:47:00.373  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:47:00.373  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:47:00.378  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:47:00.388  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:47:00.388  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:47:00.398  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:47:00.398  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:47:00.398  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:47:04.228  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:47:05.468  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:28), LCD = 0
,07-27 09:47:07.003  3597  4974 E Watchdog: !@Sync 18 [07-27 09:47:07.006]
,07-27 09:47:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:47:08.438  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:47:08.438  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:47:15.498  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:30), LCD = 0
,07-27 09:47:24.228  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:47:25.528  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), LCD = 0
,07-27 09:47:30.458  3597  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:47:35.553  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), LCD = 0
,07-27 09:47:37.008  3597  4974 E Watchdog: !@Sync 19 [07-27 09:47:37.011]
,07-27 09:47:42.808  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:47:42.808  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:47:44.228  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:47:45.588  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), LCD = 0
,07-27 09:47:55.613  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), LCD = 0
,07-27 09:47:57.893  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:47:57.893  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:48:00.558  3597  4911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:48:00.558  3597  4911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:48:00.558  3597  4911 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
,07-27 09:48:00.558  3597  4911 D BatteryService: stay LED for fully charged
07-27 09:48:00.558  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:48:00.563  3597  3597 I MotionRecognitionService: Plugged
07-27 09:48:00.563  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:48:00.563  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:48:00.563  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:48:00.568  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:48:00.568  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:48:00.573  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:48:00.583  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:48:00.583  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:48:00.593  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:48:00.593  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:48:00.593  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:48:03.533  3597  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 09:48:03.533  3597  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:48:03.538  3597  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:48:04.233  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:48:05.633  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), LCD = 0
,07-27 09:48:07.013  3597  4974 E Watchdog: !@Sync 20 [07-27 09:48:07.017]
,07-27 09:48:07.083  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-27 09:48:07.083  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:48:07.103  3597  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:48:07.103  3597  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:48:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:48:08.538  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:48:08.538  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:48:08.623  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 74ms lastUpdatedAfter : 180426ms
,07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:10.018  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLock,ed: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:48:10.023  3597  3752 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:48:10.173  3597  3837 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-27 09:48:10.173  3597  3837 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-27 09:48:15.658  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), LCD = 0
,07-27 09:48:24.233  3597  6999 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:48:25.688  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), LCD = 0
,07-27 09:48:30.643  3597  5010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:48:30.643  3597  5010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:48:30.643  3597  5010 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:48:30.643  3597  5010 D BatteryService: stay LED for fully charged
,07-27 09:48:30.643  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:48:30.648  3597  3597 I MotionRecognitionService: Plugged
07-27 09:48:30.648  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:48:30.648  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:48:30.648  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:48:30.658  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:48:30.658  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:48:30.658  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:48:30.678  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:48:30.678  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:48:30.683  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:48:30.683  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:48:30.683  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:48:35.723  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), LCD = 0
,07-27 09:48:37.018  3597  4974 E Watchdog: !@Sync 21 [07-27 09:48:37.023]
,07-27 09:48:42.633  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:48:42.633  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:48:45.748  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), LCD = 0
,07-27 09:48:55.778  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), LCD = 0
,07-27 09:49:00.743  3597  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:49:00.743  3597  5011 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:49:00.743  3597  5011 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:49:00.743  3597  5011 D BatteryService: stay LED for fully charged
,07-27 09:49:00.748  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:49:00.753  3597  3597 I MotionRecognitionService: Plugged
07-27 09:49:00.753  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:49:00.753  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:49:00.753  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:49:00.763  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:49:00.763  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:49:00.763  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:49:00.778  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:49:00.778  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:49:00.788  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-27 09:49:00.788  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:49:00.788  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:49:04.173  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:49:04.173  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:49:05.808  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), LCD = 0
,07-27 09:49:07.028  3597  4974 E Watchdog: !@Sync 22 [07-27 09:49:07.031]
,07-27 09:49:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:49:08.738  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:49:08.738  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:49:15.843  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), LCD = 0
,07-27 09:49:25.883  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), LCD = 0
,07-27 09:49:30.838  3597  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:49:30.838  3597  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:49:30.838  3597  5114 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:49:30.838  3597  5114 D BatteryService: stay LED for fully charged
,07-27 09:49:30.843  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:49:30.848  3597  3597 I MotionRecognitionService: Plugged
07-27 09:49:30.848  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:49:30.848  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:49:30.848  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:49:30.858  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:49:30.858  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:49:30.858  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:49:30.878  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:49:30.878  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:49:30.883  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:49:30.883  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:49:30.883  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:49:35.908  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), LCD = 0
,07-27 09:49:37.033  3597  4974 E Watchdog: !@Sync 23 [07-27 09:49:37.035]
,07-27 09:49:45.938  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), LCD = 0
,07-27 09:49:48.898  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:49:48.898  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:49:55.973  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), LCD = 0
,07-27 09:50:00.933  3597  5277 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:50:00.933  3597  5277 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:50:00.933  3597  5277 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:50:00.933  3597  5277 D BatteryService: stay LED for fully charged
,07-27 09:50:00.933  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:50:00.943  3597  3597 I MotionRecognitionService: Plugged
07-27 09:50:00.943  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:50:00.943  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:50:00.943  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:50:00.948  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:50:00.948  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:50:00.948  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:50:00.963  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:50:00.963  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:50:00.973  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:50:00.973  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:50:00.973  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:50:04.013  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:50:04.013  2913  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:50:05.998  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), LCD = 0
,07-27 09:50:07.038  3597  4974 E Watchdog: !@Sync 24 [07-27 09:50:07.042]
,07-27 09:50:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:50:08.883  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:50:08.883  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:50:16.028  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), LCD = 0
,07-27 09:50:26.058  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), LCD = 0
,07-27 09:50:31.048  3597  4911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:50:31.048  3597  4911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:50:31.048  3597  4911 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:50:31.048  3597  4911 D BatteryService: stay LED for fully charged
07-27 09:50:31.053  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:50:31.058  3597  3597 I MotionRecognitionService: Plugged
07-27 09:50:31.058  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:50:31.058  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:50:31.058  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:50:31.068  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:50:31.068  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:50:31.068  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:50:31.078  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:50:31.078  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:50:31.088  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:50:31.088  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:50:31.088  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:50:36.083  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), LCD = 0
,07-27 09:50:37.048  3597  4974 E Watchdog: !@Sync 25 [07-27 09:50:37.049]
,07-27 09:50:46.108  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), LCD = 0
,07-27 09:50:56.138  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:51:01.143  3597  5010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:51:01.143  3597  5010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:51:01.143  3597  5010 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:51:01.143  3597  5010 D BatteryService: stay LED for fully charged
,07-27 09:51:01.143  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:51:01.148  3597  3597 I MotionRecognitionService: Plugged
07-27 09:51:01.153  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:51:01.153  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:51:01.153  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:51:01.158  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:51:01.158  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:51:01.158  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:51:01.178  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:51:01.178  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:51:01.188  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:51:01.188  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:51:01.188  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:06.178  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:51:07.058  3597  4974 E Watchdog: !@Sync 26 [07-27 09:51:07.060]
,07-27 09:51:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:51:08.988  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:51:08.988  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:51:09.068  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 71ms lastUpdatedAfter : 180446ms
,07-27 09:51:10.353  3597  5890 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 09:51:10.363  3597  5890 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-27 09:51:10.368  3597  5890 V MARsPolicyManager: updateSMDBValues
,07-27 09:51:10.378  3597  3832 E MARsDBManager: updateDBAll : begin --size 1
,07-27 09:51:10.413  3597  3832 E MARsDBManager: updateDBAll : end
07-27 09:51:10.413  3597  3832 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-27 09:51:16.208  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:51:26.233  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:51:31.238  3597  5129 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:51:31.238  3597  5129 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
,07-27 09:51:31.243  3597  5129 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:51:31.243  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:51:31.248  3597  5129 D BatteryService: stay LED for fully charged
,07-27 09:51:31.253  3597  3597 I MotionRecognitionService: Plugged
07-27 09:51:31.253  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:51:31.253  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:51:31.253  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:51:31.263  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:51:31.263  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:51:31.263  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:51:31.278  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:51:31.278  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:51:31.288  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:51:31.288  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:31.288  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:51:36.268  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:51:37.063  3597  4974 E Watchdog: !@Sync 27 [07-27 09:51:37.066]
,07-27 09:51:46.303  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:51:56.328  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:52:01.333  3597  5848 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:52:01.338  3597  5848 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:52:01.338  3597  5848 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:52:01.338  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:52:01.338  3597  5848 D BatteryService: stay LED for fully charged
,07-27 09:52:01.343  3597  3597 I MotionRecognitionService: Plugged
07-27 09:52:01.343  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:52:01.343  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:52:01.343  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:52:01.353  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:52:01.353  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:52:01.353  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:52:01.368  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:52:01.373  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-27 09:52:01.378  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:52:01.378  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:52:01.378  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:52:06.358  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:52:07.068  3597  4974 E Watchdog: !@Sync 28 [07-27 09:52:07.072]
,07-27 09:52:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:52:09.178  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:52:09.178  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:52:16.388  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:52:26.408  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:52:31.428  3597  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:52:31.428  3597  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:52:31.428  3597  5114 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:52:31.428  3597  5114 D BatteryService: stay LED for fully charged
,07-27 09:52:31.433  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:52:31.438  3597  3597 I MotionRecognitionService: Plugged
07-27 09:52:31.438  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:52:31.438  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:52:31.438  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:52:31.443  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:52:31.443  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:52:31.448  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:52:31.463  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:52:31.463  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:52:31.473  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:52:31.473  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:52:31.473  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:52:36.443  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:52:37.073  3597  4974 E Watchdog: !@Sync 29 [07-27 09:52:37.077]
,07-27 09:52:46.473  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:52:50.228  3597  4400 V AlarmManager: Expired Alarm result :4
,07-27 09:52:50.253  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 09:52:50.253  4522  4522 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:52:50.253  4522  4522 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:52:50.278  4522  4522 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:52:50.283  4522  4522 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:52:50.293  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.308  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.313  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.318  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.318  3597  3765 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-27 09:52:50.328  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.333  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.333  4522  4522 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.393  3597  3752 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 09:52:50.393  3597  3752 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 09:52:50.418  4522  4522 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:52:50.643  3597  4913 V AlarmManager:  remove PendingIntent] PendingIntent{97edc80: PendingIntentRecord{6bb2f6 com.google.android.apps.plus broadcastIntent}}
,07-27 09:52:50.658  3597  5277 V AlarmManager:  remove PendingIntent] PendingIntent{d3312b9: PendingIntentRecord{28986fe com.google.android.apps.plus broadcastIntent}}
,07-27 09:52:56.503  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:52:59.998  3597  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:53:01.528  3597  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:53:01.528  3597  4913 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:53:01.528  3597  4913 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:53:01.528  3597  4913 D BatteryService: stay LED for fully charged
,07-27 09:53:01.528  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:53:01.533  3597  3597 I MotionRecognitionService: Plugged
07-27 09:53:01.533  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:53:01.533  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:53:01.533  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:53:01.543  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:53:01.543  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:53:01.543  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:53:01.563  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:53:01.563  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:53:01.568  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:53:01.568  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:53:01.568  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:53:03.533  3597  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 09:53:03.533  3597  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:53:03.538  3597  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:53:06.518  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:53:07.083  3597  4974 E Watchdog: !@Sync 30 [07-27 09:53:07.084]
,07-27 09:53:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:53:09.323  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:53:09.323  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:53:10.333  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 09:53:10.333  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:53:10.348  3597  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 09:53:10.348  3597  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:53:12.303  3597  4400 V AlarmManager: Expired Alarm result :4
,07-27 09:53:12.383  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 09:53:12.383  4522  4522 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:53:12.383  4522  4522 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:53:12.388  4522  4522 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:53:12.393  4522  4522 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:53:12.398  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:12.398  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:12.398  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:12.398  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:53:12.398  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:12.403  4522  4522 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:12.403  3597  4913 V AlarmManager:  remove PendingIntent] PendingIntent{973150a: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.403  4522  4522 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:12.423  3597  4438 V AlarmManager:  remove PendingIntent] PendingIntent{625317b: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.423  3597  5852 V AlarmManager:  remove PendingIntent] PendingIntent{30bbb98: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.448  3597  4645 V AlarmManager:  remove PendingIntent] PendingIntent{eb75ff1: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.473  3597  4911 V AlarmManager:  remove PendingIntent] PendingIntent{8b577d6: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.478  4522  4522 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:53:12.503  3597  3617 V AlarmManager:  remove PendingIntent] PendingIntent{54b6a57: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.523  3597  4913 V AlarmManager:  remove PendingIntent] PendingIntent{1ccf944: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.523  3597  5130 V AlarmManager:  remove PendingIntent] PendingIntent{6d10a2d: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.528  3597  3615 V AlarmManager:  remove PendingIntent] PendingIntent{3e93b62: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.533  3597  5852 V AlarmManager:  remove PendingIntent] PendingIntent{a3254f3: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.533  3597  5010 V AlarmManager:  remove PendingIntent] PendingIntent{44265b0: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.538  3597  5128 V AlarmManager:  remove PendingIntent] PendingIntent{1611c29: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.543  3597  4645 V AlarmManager:  remove PendingIntent] PendingIntent{da3abae: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.548  3597  3615 V AlarmManager:  remove PendingIntent] PendingIntent{3934d4f: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.553  3597  3617 V AlarmManager:  remove PendingIntent] PendingIntent{1602cdc: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.558  3597  4911 V AlarmManager:  remove PendingIntent] PendingIntent{1c651e5: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.563  3597  4645 V AlarmManager:  remove PendingIntent] PendingIntent{a82d4ba: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.573  3597  3615 V AlarmManager:  remove PendingIntent] PendingIntent{8616f6b: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.578  3597  3617 V AlarmManager:  remove PendingIntent] PendingIntent{9313ac8: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.583  3597  4911 V AlarmManager:  remove PendingIntent] PendingIntent{88f2761: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.588  3597  4645 V AlarmManager:  remove PendingIntent] PendingIntent{8f98286: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.593  3597  4438 V AlarmManager:  remove PendingIntent] PendingIntent{1a59747: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.598  3597  5848 V AlarmManager:  remove PendingIntent] PendingIntent{f833b74: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.603  3597  5278 V AlarmManager:  remove PendingIntent] PendingIntent{6b5d89d: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.608  3597  4911 V AlarmManager:  remove PendingIntent] PendingIntent{9db4112: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.613  3597  5129 V AlarmManager:  remove PendingIntent] PendingIntent{61a60e3: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.618  3597  5011 V AlarmManager:  remove PendingIntent] PendingIntent{5529ae0: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.618  3597  5114 V AlarmManager:  remove PendingIntent] PendingIntent{89c6199: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.623  3597  3617 V AlarmManager:  remove PendingIntent] PendingIntent{5a85c5e: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.628  3597  5277 V AlarmManager:  remove PendingIntent] PendingIntent{388283f: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.633  3597  4913 V AlarmManager:  remove PendingIntent] PendingIntent{cf6850c: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:12.638  3597  5130 V AlarmManager:  remove PendingIntent] PendingIntent{4c87e55: PendingIntentRecord{b692175 com.android.bluetooth broadcastIntent}}
,07-27 09:53:16.543  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:53:26.568  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:53:31.623  3597  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:53:31.623  3597  4913 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:53:31.623  3597  4913 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:53:31.623  3597  4913 D BatteryService: stay LED for fully charged
,07-27 09:53:31.623  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:53:31.628  3597  3597 I MotionRecognitionService: Plugged
07-27 09:53:31.628  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:53:31.628  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:53:31.628  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:53:31.643  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:53:31.643  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:53:31.643  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:53:31.653  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:53:31.658  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:53:31.668  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:53:31.668  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:53:31.668  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:53:36.603  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:53:37.083  3597  4974 E Watchdog: !@Sync 31 [07-27 09:53:37.086]
,07-27 09:53:46.638  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:53:56.668  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:53:59.998  3597  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:54:01.718  3597  4645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:54:02.708  3597  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:54:02.833  3597  3765 W ProcessCpuTracker: Skipping unknown process pid 12079
,07-27 09:54:06.703  3597  6913 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), LCD = 0
,07-27 09:54:07.088  3597  4974 E Watchdog: !@Sync 32 [07-27 09:54:07.089]
,07-27 09:54:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:54:09.448  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:54:09.448  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:54:09.528  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 71ms lastUpdatedAfter : 180460ms
,07-27 09:54:16.728  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), LCD = 0
,07-27 09:54:26.758  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), LCD = 0
,07-27 09:54:31.823  3597  5128 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:54:31.828  3597  5128 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:54:31.828  3597  5128 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:54:31.828  3597  5128 D BatteryService: stay LED for fully charged
,07-27 09:54:31.828  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:54:31.838  3597  3597 I MotionRecognitionService: Plugged
07-27 09:54:31.838  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:54:31.838  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:54:31.838  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:54:31.843  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:54:31.843  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:54:31.843  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:54:31.863  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:54:31.863  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:54:31.873  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:54:31.873  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:54:31.873  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:54:36.793  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), LCD = 0
,07-27 09:54:37.093  3597  4974 E Watchdog: !@Sync 33 [07-27 09:54:37.097]
,07-27 09:54:46.828  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), LCD = 0
,07-27 09:54:56.848  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), LCD = 0
,07-27 09:55:01.913  3597  4645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:55:01.913  3597  4645 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:55:01.913  3597  4645 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:55:01.913  3597  4645 D BatteryService: stay LED for fully charged
,07-27 09:55:01.913  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:55:01.918  3597  3597 I MotionRecognitionService: Plugged
07-27 09:55:01.918  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:55:01.918  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:55:01.918  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:55:01.923  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:55:01.923  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:55:01.923  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:55:01.943  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:55:01.943  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:55:01.953  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:55:01.953  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:55:01.953  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:55:06.883  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), LCD = 0
,07-27 09:55:07.098  3597  4974 E Watchdog: !@Sync 34 [07-27 09:55:07.102]
,07-27 09:55:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:55:09.633  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:55:09.633  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:55:16.928  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), LCD = 0
,07-27 09:55:26.973  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), LCD = 0
,07-27 09:55:32.018  3597  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:55:37.023  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), LCD = 0
,07-27 09:55:37.103  3597  4974 E Watchdog: !@Sync 35 [07-27 09:55:37.106]
,07-27 09:55:47.068  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-27 09:55:57.118  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-27 09:56:02.113  3597  5129 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:56:02.113  3597  5129 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:56:02.118  3597  5129 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:56:02.118  3597  5129 D BatteryService: stay LED for fully charged
,07-27 09:56:02.118  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:56:02.138  3597  3597 I MotionRecognitionService: Plugged
07-27 09:56:02.138  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:56:02.138  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:56:02.138  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:56:02.143  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:56:02.143  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:56:02.143  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:56:02.163  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:56:02.163  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:56:02.168  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:56:02.168  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:56:02.168  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:56:07.108  3597  4974 E Watchdog: !@Sync 36 [07-27 09:56:07.110]
,07-27 09:56:07.168  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-27 09:56:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:56:09.763  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:56:09.763  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:56:17.193  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-27 09:56:27.243  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-27 09:56:32.218  3597  5130 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:56:32.218  3597  5130 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:56:32.218  3597  5130 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:56:32.218  3597  5130 D BatteryService: stay LED for fully charged
,07-27 09:56:32.218  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:56:32.223  3597  3597 I MotionRecognitionService: Plugged
07-27 09:56:32.223  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:56:32.223  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:56:32.223  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:56:32.228  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:56:32.228  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:56:32.233  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:56:32.248  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:56:32.248  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-27 09:56:32.258  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:56:32.258  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:56:32.258  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:56:37.113  3597  4974 E Watchdog: !@Sync 37 [07-27 09:56:37.116]
,07-27 09:56:37.268  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-27 09:56:47.313  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-27 09:56:57.353  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0,
,07-27 09:57:02.318  3597  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:57:02.318  3597  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:57:02.318  3597  4438 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:57:02.318  3597  4438 D BatteryService: stay LED for fully charged
,07-27 09:57:02.323  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:57:02.328  3597  3597 I MotionRecognitionService: Plugged
07-27 09:57:02.328  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:57:02.328  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:57:02.328  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:57:02.333  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:57:02.333  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:57:02.333  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:57:02.353  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:57:02.353  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:57:02.358  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:57:02.358  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:57:02.358  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:07.118  3597  4974 E Watchdog: !@Sync 38 [07-27 09:57:07.120]
,07-27 09:57:07.418  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-27 09:57:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:57:09.893  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:57:09.893  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:57:09.973  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 75ms lastUpdatedAfter : 180442ms
,07-27 09:57:17.463  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-27 09:57:27.493  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-27 09:57:32.413  3597  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:57:32.413  3597  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:57:32.413  3597  5114 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:57:32.413  3597  5114 D BatteryService: stay LED for fully charged
,07-27 09:57:32.418  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:57:32.423  3597  3597 I MotionRecognitionService: Plugged
07-27 09:57:32.423  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:57:32.423  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:57:32.423  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:57:32.428  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:57:32.428  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:57:32.428  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:57:32.453  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:57:32.453  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:57:32.458  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:57:32.458  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:57:32.463  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:57:37.128  3597  4974 E Watchdog: !@Sync 39 [07-27 09:57:37.128]
,07-27 09:57:37.553  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-27 09:57:47.593  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-27 09:57:57.623  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-27 09:58:02.508  3597  5852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:58:02.508  3597  5852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:58:02.508  3597  5852 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:58:02.508  3597  5852 D BatteryService: stay LED for fully charged
07-27 09:58:02.513  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:58:02.518  3597  3597 I MotionRecognitionService: Plugged
07-27 09:58:02.518  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:58:02.518  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:58:02.518  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:58:02.523  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:58:02.523  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:58:02.523  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:58:02.538  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:58:02.538  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:58:02.548  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:58:02.548  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:58:02.548  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:58:03.533  3597  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 09:58:03.533  3597  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:58:03.538  3597  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:58:03.928  3597  3752 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:58:06.978  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 09:58:06.978  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:58:06.993  3597  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 09:58:06.993  3597  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:58:07.133  3597  4974 E Watchdog: !@Sync 40 [07-27 09:58:07.136]
,07-27 09:58:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:58:07.683  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-27 09:58:10.053  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:58:10.053  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:58:17.733  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-27 09:58:27.768  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-27 09:58:32.608  3597  5278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:58:32.608  3597  5278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:58:32.608  3597  5278 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:58:32.608  3597  5278 D BatteryService: stay LED for fully charged
,07-27 09:58:32.608  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:58:32.613  3597  3597 I MotionRecognitionService: Plugged
07-27 09:58:32.613  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:58:32.618  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:58:32.618  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:58:32.628  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:58:32.628  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:58:32.628  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:58:32.633  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:58:32.633  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-27 09:58:32.648  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:58:32.648  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:58:32.648  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:58:37.138  3597  4974 E Watchdog: !@Sync 41 [07-27 09:58:37.140]
,07-27 09:58:37.798  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-27 09:58:42.718  9878  9893 I PlayCommon: [957] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:58:42.723  9878  9893 I PlayCommon: [957] com.google.android.play.a.al.e(732): No file ready to send
,07-27 09:58:47.823  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:58:57.858  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:59:02.698  3597  5277 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:59:02.698  3597  5277 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:59:02.698  3597  5277 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:59:02.698  3597  5277 D BatteryService: stay LED for fully charged
,07-27 09:59:02.703  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:59:02.708  3597  3597 I MotionRecognitionService: Plugged
07-27 09:59:02.708  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:59:02.708  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:59:02.708  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:59:02.713  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:59:02.713  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:59:02.713  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:59:02.733  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:59:02.733  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:59:02.748  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:02.748  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:59:02.748  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:07.143  3597  4974 E Watchdog: !@Sync 42 [07-27 09:59:07.146]
,07-27 09:59:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:59:07.888  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:59:10.198  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:59:10.198  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:59:17.913  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:59:27.948  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:59:32.798  3597  5128 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:59:32.798  3597  5128 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:59:32.798  3597  5128 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:59:32.798  3597  5128 D BatteryService: stay LED for fully charged
,07-27 09:59:32.803  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:59:32.808  3597  3597 I MotionRecognitionService: Plugged
07-27 09:59:32.808  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 09:59:32.808  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:59:32.808  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:59:32.813  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:59:32.813  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:59:32.813  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:59:32.833  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:59:32.833  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:59:32.838  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:59:32.838  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:59:32.838  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:59:37.148  3597  4974 E Watchdog: !@Sync 43 [07-27 09:59:37.150]
,07-27 09:59:37.973  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:59:48.003  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:59:58.033  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:00:02.893  3597  4645 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 10:00:02.893  3597  4645 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 10:00:02.893  3597  4645 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 10:00:02.893  3597  4645 D BatteryService: stay LED for fully charged
,07-27 10:00:02.898  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 10:00:02.903  3597  3597 I MotionRecognitionService: Plugged
07-27 10:00:02.903  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 10:00:02.903  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 10:00:02.903  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:00:02.908  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 10:00:02.908  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:00:02.908  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:00:02.928  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 10:00:02.928  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:00:02.938  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:02.938  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:00:02.938  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:07.153  3597  4974 E Watchdog: !@Sync 44 [07-27 10:00:07.156],
,07-27 10:00:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 10:00:08.058  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:00:10.293  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 10:00:10.293  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 10:00:10.383  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 76ms lastUpdatedAfter : 180410ms
,07-27 10:00:18.098  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:00:28.128  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:00:32.998  3597  4438 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:00:32.998  3597  4438 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 10:00:32.998  3597  4438 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 10:00:32.998  3597  4438 D BatteryService: stay LED for fully charged
07-27 10:00:32.998  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 10:00:33.008  3597  3597 I MotionRecognitionService: Plugged
07-27 10:00:33.008  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 10:00:33.008  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 10:00:33.008  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:00:33.023  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 10:00:33.023  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:00:33.023  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:00:33.088  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 10:00:33.088  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:00:33.093  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:33.093  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:33.098  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:00:37.158  3597  4974 E Watchdog: !@Sync 45 [07-27 10:00:37.159]
,07-27 10:00:38.158  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:00:48.193  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:00:58.223  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:01:03.093  3597  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 10:01:03.093  3597  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 10:01:03.093  3597  5114 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 10:01:03.093  3597  5114 D BatteryService: stay LED for fully charged
,07-27 10:01:03.098  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 10:01:03.103  3597  3597 I MotionRecognitionService: Plugged
07-27 10:01:03.103  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 10:01:03.103  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 10:01:03.103  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:01:03.108  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:01:03.108  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:01:03.108  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:01:03.128  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 10:01:03.128  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:01:03.133  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:01:03.138  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:01:03.138  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:01:07.163  3597  4974 E Watchdog: !@Sync 46 [07-27 10:01:07.166]
,07-27 10:01:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 10:01:08.253  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:01:10.483  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 10:01:10.483  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 10:01:18.278  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:01:28.318  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:01:33.188  3597  5852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 10:01:33.188  3597  5852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 10:01:33.188  3597  5852 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 10:01:33.193  3597  5852 D BatteryService: stay LED for fully charged
,07-27 10:01:33.193  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 10:01:33.198  3597  3597 I MotionRecognitionService: Plugged
07-27 10:01:33.198  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 10:01:33.198  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 10:01:33.198  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:01:33.208  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:01:33.208  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:01:33.208  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:01:33.228  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 10:01:33.228  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:01:33.233  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:01:33.233  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:01:33.233  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:01:37.168  3597  4974 E Watchdog: !@Sync 47 [07-27 10:01:37.170]
,07-27 10:01:38.348  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:01:48.373  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:01:58.403  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:02:03.288  3597  5278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 10:02:07.173  3597  4974 E Watchdog: !@Sync 48 [07-27 10:02:07.176]
,07-27 10:02:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 10:02:08.428  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:02:10.613  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 10:02:10.613  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 10:02:18.458  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:02:28.493  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:02:33.383  3597  5848 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 10:02:33.383  3597  5848 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 10:02:33.383  3597  5848 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 10:02:33.383  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 10:02:33.383  3597  5848 D BatteryService: stay LED for fully charged
,07-27 10:02:33.388  3597  3597 I MotionRecognitionService: Plugged
07-27 10:02:33.388  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 10:02:33.388  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 10:02:33.388  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:02:33.398  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 10:02:33.398  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:02:33.398  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:02:33.423  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 10:02:33.423  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:02:33.423  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 10:02:33.423  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:02:33.423  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:02:37.178  3597  4974 E Watchdog: !@Sync 49 [07-27 10:02:37.181]
,07-27 10:02:38.523  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:02:48.548  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:02:58.583  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:03:03.473  3597  3617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 10:03:03.478  3597  3617 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 10:03:03.478  3597  3617 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 10:03:03.478  3597  3617 D BatteryService: stay LED for fully charged
,07-27 10:03:03.478  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 10:03:03.483  3597  3597 I MotionRecognitionService: Plugged
07-27 10:03:03.483  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 10:03:03.483  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-27 10:03:03.483  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:03:03.493  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 10:03:03.493  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:03:03.493  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:03:03.513  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 10:03:03.513  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:03:03.518  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:03:03.518  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:03:03.518  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:03:03.533  3597  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 10:03:03.533  3597  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 10:03:03.533  3597  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 10:03:07.188  3597  4974 E Watchdog: !@Sync 50 [07-27 10:03:07.191]
,07-27 10:03:07.518  2952  5182 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 10:03:08.618  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:03:10.263  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 10:03:10.263  3597  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 10:03:10.283  3597  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 10:03:10.283  3597  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 10:03:10.393  3597  5890 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 10:03:10.403  3597  5890 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-27 10:03:10.403  3597  5890 V MARsPolicyManager: updateSMDBValues
,07-27 10:03:10.408  3597  3832 E MARsDBManager: updateDBAll : begin --size 0
07-27 10:03:10.408  3597  3832 E MARsDBManager: updateDBAll : end,
,07-27 10:03:10.728  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 10:03:10.728  5017  5072 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 10:03:10.823  5017  5072 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 86ms lastUpdatedAfter : 180440ms
,07-27 10:03:18.648  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:03:28.683  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:03:33.573  3597  5010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 10:03:33.573  3597  5010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 10:03:33.573  3597  5010 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 10:03:33.573  3597  5010 D BatteryService: stay LED for fully charged
,07-27 10:03:33.578  3597  3597 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 10:03:33.583  3597  3597 I MotionRecognitionService: Plugged
07-27 10:03:33.583  3597  3597 D MotionRecognitionService:   cableConnection= 1
07-27 10:03:33.583  3597  3597 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 10:03:33.583  3597  3597 D MotionRecognitionService: skip setTransmitPower. 
,07-27 10:03:33.588  4522  4522 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 10:03:33.588  4522  4522 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 10:03:33.588  4522  4522 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 10:03:33.608  5752  5752 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 10:03:33.608  5752  6212 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 10:03:33.618  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:03:33.618  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 10:03:33.618  4522  4522 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 10:03:37.188  3597  4974 E Watchdog: !@Sync 51 [07-27 10:03:37.192]
,07-27 10:03:38.718  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 10:03:42.793  9878  9893 I PlayCommon: [957] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 10:03:42.798  9878  9893 I PlayCommon: [957] com.google.android.play.a.al.e(732): No file ready to send
,07-27 10:03:48.748  3597  6913 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,TIME-OUT KILL (timeout was 1400000ms)
```
