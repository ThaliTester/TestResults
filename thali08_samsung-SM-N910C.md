#### Test 72145431aac82a0_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
07-06 08:24:35.656  3524  5858 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:24:35.656  3524  5858 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:24:35.656  3524  5858 D BatteryService: online:4, current avg:126, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:116
07-06 08:24:35.656  3524  5858 D BatteryService: stay LED for fully charged
07-06 08:24:35.661  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
07-06 08:24:35.671  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:24:35.666  3524  3524 I MotionRecognitionService: Plugged
07-06 08:24:35.671  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:24:35.666  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:24:35.671  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 08:24:35.666  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:24:35.666  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
07-06 08:24:35.691  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:24:35.691  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-06 08:24:35.696  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:24:35.696  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:24:35.701  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:24:37.106 11376 11376 I FIPS_bssl: FIPS approved mode (1) | 11376 | app_process
07-06 08:24:37.111 11376 11376 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-06 08:24:37.116 11376 11376 D AndroidRuntime: CheckJNI is OFF
07-06 08:24:37.116 11376 11376 D AndroidRuntime: readGMSProperty: start
07-06 08:24:37.116 11376 11376 D AndroidRuntime: readGMSProperty: already setted!!
07-06 08:24:37.116 11376 11376 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 08:24:37.116 11376 11376 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 08:24:37.116 11376 11376 D AndroidRuntime: readGMSProperty: end
07-06 08:24:37.116 11376 11376 D AndroidRuntime: addProductProperty: start
07-06 08:24:37.141 11376 11376 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-06 08:24:37.171 11376 11376 I Radio-JNI: register_android_hardware_Radio DONE
07-06 08:24:37.176 11376 11376 E AffinityControl: AffinityControl: registerfunction enter
07-06 08:24:37.191 11376 11376 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-06 08:24:37.231  3524  5134 D GameManagerService: identifyGamePackage. com.test.thalitest
07-06 08:24:37.231  3524  5134 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
07-06 08:24:37.236  3524  5134 D ActivityManager: mDVFSHelper.acquire()
07-06 08:24:37.236  3524  5134 V WindowManager: addAppToken: AppWindowToken{48ab15a token=Token{e073d05 ActivityRecord{8f3507c u0 com.test.thalitest/.MainActivity t69}}} to stack=1 task=69 at 0
07-06 08:24:37.251  3524  3765 D SecWifiDisplayUtil: Metadata value : none
07-06 08:24:37.251  3524  3765 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{42e11b2 V.E...... R.....ID 0,0-0,0}
07-06 08:24:37.256  3524  3765 D ISSUE_DEBUG: InputChannelName : 80a6c80 Starting com.test.thalitest
07-06 08:24:37.256 11392 11392 E Zygote  : v2
07-06 08:24:37.256 11392 11392 I libpersona: KNOX_SDCARD checking this for 10007
07-06 08:24:37.256 11392 11392 I libpersona: KNOX_SDCARD not a persona
07-06 08:24:37.261  3524  5134 I ActivityManager: Start proc 11392:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
07-06 08:24:37.261 11392 11392 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-06 08:24:37.261 11392 11392 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:37.261  3524  5134 D InputDispatcher: Focused application set to: xxxx
07-06 08:24:37.261 11392 11392 E Zygote  : accessInfo : 0
07-06 08:24:37.261  3524  5134 D InputDispatcher: Focus left window: 6986
07-06 08:24:37.261 11392 11392 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-06 08:24:37.266 11376 11376 D AndroidRuntime: Shutting down VM
07-06 08:24:37.266  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-06 08:24:37.266  3524  3685 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{e2572ef u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-06 08:24:37.266  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-06 08:24:37.271  2905  2905 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
07-06 08:24:37.291 11392 11392 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:24:37.291 11392 11392 D ActivityThread: Added TimaKeyStore provider
07-06 08:24:37.296  3524  3765 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3524 uid:1000
07-06 08:24:37.296  3524  5858 V WindowOrientationListener: setCurrentAppOrientation :-1
07-06 08:24:37.296  3524  3765 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 08:24:37.296  3524  5858 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-06 08:24:37.296  3524  3765 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3524 uid:1000
07-06 08:24:37.296  3524  3765 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-06 08:24:37.296  3524  3765 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-06 08:24:37.301  3524  3685 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{80a6c80 u0 d0 Starting com.test.thalitest}
07-06 08:24:37.301  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-06 08:24:37.306  3524  5858 D ActivityManager:  Launching com.test.thalitest, updated priority
07-06 08:24:37.321  3524  3524 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-06 08:24:37.321  3524  3678 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-06 08:24:37.346  2905  3009 D libEGL  : eglTerminate EGLDisplay = 0xb6901624
07-06 08:24:37.346  2905  3011 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
07-06 08:24:37.346  2905  3011 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
07-06 08:24:37.351  2905 10182 I SurfaceFlinger: id=18 Removed VSBConnecti (7/11)
07-06 08:24:37.351  2905  4414 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
07-06 08:24:37.356  2905 10182 I SurfaceFlinger: id=9 Removed Mauncher (4/10)
07-06 08:24:37.356  2905  3009 I SurfaceFlinger: id=9 Removed Mauncher (-2/10)
07-06 08:24:37.356  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbe971474
07-06 08:24:37.356  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbe971474
07-06 08:24:37.361  6986  6986 V ActivityThread: updateVisibility : ActivityRecord{d1def68 token=android.os.BinderProxy@a46bf95 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-06 08:24:37.361  3524  3765 V WindowStateAnimator: Finishing drawing window Window{80a6c80 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-06 08:24:37.361  5128  5128 V ActivityThread: updateVisibility : ActivityRecord{6d080d4 token=android.os.BinderProxy@2eab20b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-06 08:24:37.361  5128  5128 D Launcher: onTrimMemory. Level: 20
07-06 08:24:37.376  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
07-06 08:24:37.381  2905  4414 I SurfaceFlinger: id=19 Removed VSBConnecti (4/9)
07-06 08:24:37.381  2905  3009 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/9)
07-06 08:24:37.391  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbe971474
,07-06 08:24:37.631  3524  5858 I WindowManager: Screenshot max retries 4 of Token{e073d05 ActivityRecord{8f3507c u0 com.test.thalitest/.MainActivity t69}} appWin=Window{80a6c80 u0 d0 Starting com.test.thalitest} drawState=4
,07-06 08:24:37.636  3524  3678 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-06 08:24:37.651  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,07-06 08:24:37.671  3524  6867 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:24:37.681  3524  6867 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:24:37.721 11392 11392 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-06 08:24:37.756 11392 11392 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-06 08:24:37.766 11392 11392 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 8388-8391)
07-06 08:24:37.766 11392 11392 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-06 08:24:37.786 11392 11406 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-06 08:24:37.786 11392 11392 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d42ecd0}
07-06 08:24:37.786 11392 11392 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-06 08:24:37.786 11392 11392 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-06 08:24:37.796 11392 11392 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-06 08:24:37.836 11392 11392 D libEGL  : eglInitialize EGLDisplay = 0xbec41e7c
,07-06 08:24:37.866  3524  5858 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,07-06 08:24:37.866  3524  5858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,07-06 08:24:37.921 11392 11392 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-06 08:24:37.936 11392 11392 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-06 08:24:37.936 11392 11392 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-06 08:24:37.936 11392 11392 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-06 08:24:37.941 11392 11392 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-06 08:24:37.956 11392 11392 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-06 08:24:37.961 11392 11392 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-06 08:24:38.046 11392 11392 D SecWifiDisplayUtil: Metadata value : none
,07-06 08:24:38.051 11392 11392 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8e1fba9 I.E...... R.....ID 0,0-0,0}
,07-06 08:24:38.056 11392 11443 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-06 08:24:38.061  3524  4654 D ISSUE_DEBUG: InputChannelName : c5289d com.test.thalitest/com.test.thalitest.MainActivity
,07-06 08:24:38.061  3524  5858 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-06 08:24:38.066  3524  5858 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-06 08:24:38.066  3524  3524 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-06 08:24:38.066  3524  3524 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-06 08:24:38.096 11392 11392 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 11392
,07-06 08:24:38.101  3524  5141 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/11392 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-06 08:24:38.101  3524  4454 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-06 08:24:38.101  3524  4454 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-06 08:24:38.101  3524  4454 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-06 08:24:38.101  3524  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:38.101  3524  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:38.101  3524  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:38.101  3524  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-06 08:24:38.101  3524  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-06 08:24:38.101  3524  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-06 08:24:38.101  3524  4454 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-06 08:24:38.101  3524  4454 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-06 08:24:38.111 11392 11406 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-06 08:24:38.121 11392 11392 D SecWifiDisplayUtil: Metadata value : none
,07-06 08:24:38.131  2905  2905 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,07-06 08:24:38.146  3524  3550 D InputDispatcher: Focus entered window: 11392
,07-06 08:24:38.146  3524  3765 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3524 uid:1000
07-06 08:24:38.146  3524  3765 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 08:24:38.146  3524  3765 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3524 uid:1000
07-06 08:24:38.146  3524  3765 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-06 08:24:38.151 11392 11443 D libEGL  : eglInitialize EGLDisplay = 0x9ceff7c4
07-06 08:24:38.151 11392 11443 I OpenGLRenderer: Initialized EGL, version 1.4
,07-06 08:24:38.156 11392 11443 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,07-06 08:24:38.161 11392 11392 V ActivityThread: updateVisibility : ActivityRecord{cac1848 token=android.os.BinderProxy@ac51330 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-06 08:24:38.166 11392 11392 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,07-06 08:24:38.171 11392 11392 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-06 08:24:38.231 11392 11448 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-06 08:24:38.231 11392 11448 D libEGL  : eglInitialize EGLDisplay = 0x9adff3ec
,07-06 08:24:38.241  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
,07-06 08:24:38.246  3524  4654 V WindowStateAnimator: Finishing drawing window Window{c5289d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-06 08:24:38.251 11392 11392 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-06 08:24:38.251  3524  5054 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-06 08:24:38.256  3524  3765 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-06 08:24:38.256  3524  3524 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-06 08:24:38.256  3524  3524 I KnoxTimeoutHandler: SD activityfalse
,07-06 08:24:38.261  3524  3765 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +626ms (total +1s19ms)
,07-06 08:24:38.266  3524  3765 D ActivityManager: mDVFSHelper.release()
07-06 08:24:38.266  3524  3765 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8f3507c u0 com.test.thalitest/.MainActivity t69} time:278893
07-06 08:24:38.266  3524  3765 D ViewRootImpl: #3 mView = null
,07-06 08:24:38.266  2905 10182 I SurfaceFlinger: id=20 Removed uhalitest (7/9)
07-06 08:24:38.271  2905  4414 I SurfaceFlinger: id=20 Removed uhalitest (-2/9)
,07-06 08:24:38.271 11392 11392 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-06 08:24:38.276  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbe971474
07-06 08:24:38.281 11392 11392 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ac51330 time:278907
,07-06 08:24:38.301 11392 11392 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11392
,07-06 08:24:38.486 11392 11392 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-06 08:24:38.616 11392 11456 D jxcore_app_log: JniHelper::setJavaVM(0xb4874000), pthread_self() = -1747961552
,07-06 08:24:38.621 11392 11456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-06 08:24:38.621 11392 11456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-06 08:24:38.621 11392 11456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-06 08:24:38.621 11392 11456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-06 08:24:38.621 11392 11456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-06 08:24:38.621 11392 11456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bde5de added. We now have 1 listener(s)
,07-06 08:24:38.621 11392 11456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,07-06 08:24:38.621 11392 11456 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
07-06 08:24:38.621 11392 11456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-06 08:24:38.621 11392 11456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7cb5d5 added. We now have 1 listener(s)
07-06 08:24:38.626 11392 11456 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-06 08:24:38.626 11392 11456 D BluetoothAdapter: STATE_ON
,07-06 08:24:38.626 11392 11456 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-06 08:24:38.631 11392 11456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-06 08:24:38.631 11392 11456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-06 08:24:38.631 11392 11456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-06 08:24:38.631 11392 11456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-06 08:24:38.631 11392 11456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-06 08:24:38.631 11392 11456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,07-06 08:24:38.636 11392 11456 D BluetoothAdapter: STATE_ON
,07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 08:24:38.636 11392 11456 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-06 08:24:38.636 11392 11456 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-06 08:24:38.636 11392 11456 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-06 08:24:38.636 11392 11456 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-06 08:24:38.641 11392 11392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-06 08:24:38.641 11392 11392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-06 08:24:38.661 11392 11392 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-06 08:24:39.021 11392 11457 W jxcore-log: Initializing JXcore engine
07-06 08:24:39.021 11392 11457 W jxcore-log: JXcore engine is ready
,07-06 08:24:39.046  5802  5802 E audit   : type=1400 msg=audit(1467786279.046:268): avc:  denied  { ioctl } for  pid=11457 comm="Thread-1127" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
07-06 08:24:39.046  5802  5802 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:39.046  5802  5802 E audit   : type=1300 msg=audit(1467786279.046:268): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=971033c8 items=0 ppid=2961 ppcomm=main pid=11457 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1127" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-06 08:24:39.046  5802  5802 E audit   : type=1327 msg=audit(1467786279.046:268): proctitle="com.test.thalitest"
07-06 08:24:39.046  5802  5802 E audit   : type=1320 msg=audit(1467786279.046:268): 
07-06 08:24:39.046  5802  5802 E audit   : type=1400 msg=audit(1467786279.046:269): avc:  denied  { ioctl } for  pid=11457 comm="Thread-1127" path="socket:[40573]" dev="sockfs" ino=40573 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-06 08:24:39.046  5802  5802 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-06 08:24:39.046  5802  5802 E audit   : type=1300 msg=audit(1467786279.046:269): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=971033c8 items=0 ppid=2961 ppcomm=main pid=11457 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1127" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-06 08:24:39.046  5802  5802 E audit   : type=1327 msg=audit(1467786279.046:269): proctitle="com.test.thalitest"
07-06 08:24:39.046  5802  5802 E audit   : type=1320 msg=audit(1467786279.046:269): 
,07-06 08:24:39.051 11392 11457 W jxcore-log: Starting JXcore engine
,07-06 08:24:39.071  4694  4694 D Recents : onTaskStackChanged
,07-06 08:24:39.096 11392 11457 W jxcore-log: Platform android
07-06 08:24:39.096 11392 11457 W jxcore-log: 
07-06 08:24:39.101 11392 11457 W jxcore-log: Process ARCH arm
07-06 08:24:39.101 11392 11457 W jxcore-log: 
,07-06 08:24:39.196 11392 11457 I jxcore-log: JXcore Cordova bridge is ready!
07-06 08:24:39.196 11392 11457 I jxcore-log: 
07-06 08:24:39.196 11392 11457 W jxcore-log: JXcore engine is started
,07-06 08:24:39.196 11392 11456 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-06 08:24:39.201 11392 11392 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-06 08:24:40.246  3524  4499 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/69_task.xml.bak
,07-06 08:24:42.791  3524  6867 D SSRM:n  : SIOP:: AP = 280, PST = 273 (W:16), CUR = 126, LCD = 0
,07-06 08:24:43.691  3524  6867 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:24:44.871  3524  4972 E Watchdog: !@Sync 9 [07-06 08:24:44.878]
,07-06 08:24:45.316 11392 11457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-06 08:24:45.316 11392 11457 I jxcore-log: 
,07-06 08:24:45.316 11392 11457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-06 08:24:45.316 11392 11457 I jxcore-log: 
,07-06 08:24:45.321 11392 11457 D BluetoothAdapter: STATE_ON
,07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 08:24:45.321 11392 11457 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-06 08:24:45.321 11392 11457 D BluetoothAdapter: STATE_ON
,07-06 08:24:45.321 11392 11457 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-06 08:24:45.321 11392 11457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-06 08:24:45.321 11392 11457 I jxcore-log: 
,07-06 08:24:45.321 11392 11457 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-06 08:24:45.321 11392 11457 I jxcore-log: 
,07-06 08:24:45.556 11392 11457 I jxcore-log: Unit Test app is loaded
07-06 08:24:45.556 11392 11457 I jxcore-log: 
,07-06 08:24:45.561 11392 11457 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-06 08:24:45.561 11392 11457 I jxcore-log: 
,07-06 08:24:45.561 11392 11392 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-06 08:24:45.566 11392 11457 I jxcore-log: My device name is: samsung-SM-N910C
07-06 08:24:45.566 11392 11457 I jxcore-log: 
07-06 08:24:45.566 11392 11457 I jxcore-log: WARN testUtils: myNameCallback not set!
07-06 08:24:45.566 11392 11457 I jxcore-log: 
,07-06 08:24:47.291  3524  3837 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-06 08:24:47.311  3524  3837 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-06 08:24:47.971 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-06 08:24:47.971 11392 11457 I jxcore-log: 
07-06 08:24:47.976  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:24:47.976  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-06 08:24:48.216 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-06 08:24:48.216 11392 11457 I jxcore-log: 
07-06 08:24:48.231 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-06 08:24:48.231 11392 11457 I jxcore-log: 
07-06 08:24:48.231 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-06 08:24:48.231 11392 11457 I jxcore-log: 
07-06 08:24:48.241 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-06 08:24:48.241 11392 11457 I jxcore-log: 
07-06 08:24:48.246 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-06 08:24:48.246 11392 11457 I jxcore-log: 
,07-06 08:24:49.451 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-06 08:24:49.451 11392 11457 I jxcore-log: 
,07-06 08:24:49.456 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-06 08:24:49.456 11392 11457 I jxcore-log: 
,07-06 08:24:49.461 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-06 08:24:49.461 11392 11457 I jxcore-log: 
,07-06 08:24:49.556 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-06 08:24:49.556 11392 11457 I jxcore-log: 
,07-06 08:24:49.606 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-06 08:24:49.606 11392 11457 I jxcore-log: 
,07-06 08:24:49.636 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-06 08:24:49.636 11392 11457 I jxcore-log: 
,07-06 08:24:49.641 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-06 08:24:49.641 11392 11457 I jxcore-log: 
,07-06 08:24:49.756 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-06 08:24:49.756 11392 11457 I jxcore-log: 
,07-06 08:24:49.766 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-06 08:24:49.766 11392 11457 I jxcore-log: 
,07-06 08:24:49.771 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-06 08:24:49.771 11392 11457 I jxcore-log: 
,07-06 08:24:49.771 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-06 08:24:49.771 11392 11457 I jxcore-log: 
,07-06 08:24:49.781 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-06 08:24:49.781 11392 11457 I jxcore-log: 
,07-06 08:24:49.791 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-06 08:24:49.791 11392 11457 I jxcore-log: 
,07-06 08:24:49.841 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-06 08:24:49.841 11392 11457 I jxcore-log: 
,07-06 08:24:49.846 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-06 08:24:49.846 11392 11457 I jxcore-log: 
,07-06 08:24:49.861 11392 11457 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-06 08:24:49.861 11392 11457 I jxcore-log: 
,07-06 08:24:49.866 11392 11457 D BluetoothAdapter: STATE_ON
,07-06 08:24:49.866 11392 11457 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-06 08:24:49.866 11392 11457 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-06 08:24:49.866 11392 11457 I jxcore-log: 
,07-06 08:24:51.686  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:24:52.821  3524  6867 D SSRM:n  : SIOP:: AP = 310, PST = 275 (W:10), CUR = 126, LCD = 0
,07-06 08:25:02.846  3524  6867 D SSRM:n  : SIOP:: AP = 290, PST = 277 (W:14), CUR = 126, LCD = 0
,07-06 08:25:05.756  3524  5518 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:25:05.756  3524  5518 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:25:05.756  3524  5518 D BatteryService: online:4, current avg:-23, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:25:05.756  3524  5518 D BatteryService: stay LED for fully charged
,07-06 08:25:05.761  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:25:05.766  3524  3524 I MotionRecognitionService: Plugged
07-06 08:25:05.766  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:25:05.766  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:25:05.766  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:25:05.771  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:25:05.771  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:25:05.771  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:25:05.791  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:25:05.791  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:25:05.801  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:25:05.801  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:25:05.801  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:25:08.171  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:25:08.171  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:25:11.476  3524  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-06 08:25:11.481  3524  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:25:11.486  3524  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:25:11.496  3524  4390 I TLC_TIMA_PKM_initialize: initializing...,
07-06 08:25:11.496  3524  4390 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-06 08:25:11.496  3524  4390 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-06 08:25:11.496  3524  4390 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-06 08:25:11.496  3524  4390 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-06 08:25:11.496  3524  4390 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-06 08:25:11.501  3524  4390 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-06 08:25:11.501  3524  4390 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-06 08:25:11.501  3524  4390 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
,07-06 08:25:11.501  3524  4390 I TZ: mc_tlc_communication: device_id = 0x0
07-06 08:25:11.501  3524  4390 I TZ: mc_tlc_communication: tlc_open() was called
,07-06 08:25:11.501  3524  4390 I TZ: mc_tlc_communication: Opening MobiCore device
,07-06 08:25:11.506  3524  4390 I TZ: mc_tlc_communication: Allocating message buffer for TCI
07-06 08:25:11.511  3524  4390 I TZ: mc_tlc_communication: Opening the session
,07-06 08:25:11.531  3524  4390 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-06 08:25:11.541  3524  4390 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-06 08:25:11.686  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:25:12.886  3524  6867 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:14), CUR = -23, LCD = 0
,07-06 08:25:14.871  3524  4972 E Watchdog: !@Sync 10 [07-06 08:25:14.879]
,07-06 08:25:14.911  3524  4401 V AlarmManager: Expired Alarm result :4
,07-06 08:25:14.966  3524  4401 I ActivityManager: Start proc 11497:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-06 08:25:14.971  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-06 08:25:14.971  4512  4512 I PERF    : received broadcast android.intent.action.TIME_TICK
07-06 08:25:14.971  4512  4512 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:25:14.986  4512  4512 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:25:14.986  4512  4512 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 08:25:15.016  4896  4896 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-06 08:25:15.016  4896  4896 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-06 08:25:15.041  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:25:15.041  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:25:15.041  4896  4896 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-06 08:25:15.041  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:25:15.041  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:25:15.046  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:25:15.046  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:25:15.046  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:25:15.051 11497 11497 E Zygote  : v2
07-06 08:25:15.051 11497 11497 I libpersona: KNOX_SDCARD checking this for 1000
07-06 08:25:15.051 11497 11497 I libpersona: KNOX_SDCARD not a persona
07-06 08:25:15.051 11497 11497 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-06 08:25:15.051 11497 11497 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-06 08:25:15.056 11497 11497 E Zygote  : accessInfo : 0
,07-06 08:25:15.086 11497 11497 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:25:15.086 11497 11497 D ActivityThread: Added TimaKeyStore provider
,07-06 08:25:15.121 11497 11497 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-06 08:25:15.146  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:25:15.171  3524  4440 I ActivityManager: Killing 10186:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 15): DHA:empty #31
,07-06 08:25:15.221  3524  5868 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,07-06 08:25:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:25:15.836  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:25:15.836  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:25:18.281  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-06 08:25:18.281  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:25:18.296  3524  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:25:18.301  3524  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:25:18.896  2915  4367 D Netd    : Iface wlan0 link up
07-06 08:25:18.896  4896  4896 I wpa_supplicant: nl80211: Received scan results (10 BSSes)
,07-06 08:25:18.896  4896  4896 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
07-06 08:25:18.896  3524  3695 D Tethering: interfaceLinkStateChanged wlan0, true
07-06 08:25:18.896  3524  3695 D Tethering: interfaceStatusChanged wlan0, true
,07-06 08:25:18.906  3524  4446 D WifiP2pService: InactiveState{ what=147461 }
07-06 08:25:18.906  3524  4446 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-06 08:25:18.906  3524  4446 D WifiP2pService: DefaultState{ what=147461 }
,07-06 08:25:18.931  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2d118d3 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fff916 4512:com.android.systemui/u0a60}
,07-06 08:25:22.916  3524  6867 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CUR = -23, LCD = 0
,07-06 08:25:31.691  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:25:32.951  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:14), CUR = -23, LCD = 0
,07-06 08:25:35.856  3524  5815 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:25:35.856  3524  5815 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:25:35.856  3524  5815 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:25:35.856  3524  5815 D BatteryService: stay LED for fully charged
,07-06 08:25:35.861  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:25:35.866  3524  3524 I MotionRecognitionService: Plugged
07-06 08:25:35.866  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:25:35.866  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:25:35.866  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:25:35.871  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:25:35.871  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:25:35.871  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:25:35.896  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:25:35.896  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:25:35.901  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:25:35.901  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:25:35.901  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:25:42.981  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:16), LCD = 0
,07-06 08:25:44.876  3524  4972 E Watchdog: !@Sync 11 [07-06 08:25:44.880]
,07-06 08:25:47.456  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:25:47.456  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:25:50.686  5793  5793 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:25:50.711  5793  5793 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:25:50.711  5793  5793 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:25:50.776  9883  9912 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-06 08:25:50.776  9883  9912 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-06 08:25:50.776  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:25:50.776  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-06 08:25:50.786  2915  4370 D EnterpriseController: netId is 0
07-06 08:25:50.786  2915  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10031
,07-06 08:25:51.696  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:25:53.011  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:16), LCD = 0
,07-06 08:25:59.996  3524  4401 V AlarmManager: Expired Alarm result :8
,07-06 08:26:03.041  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:16), LCD = 0
,07-06 08:26:05.946  3524  4654 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:26:05.951  3524  4654 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:26:05.951  3524  4654 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:26:05.951  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:26:05.951  3524  4654 D BatteryService: stay LED for fully charged
,07-06 08:26:05.956  3524  3524 I MotionRecognitionService: Plugged
07-06 08:26:05.956  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:26:05.956  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:26:05.956  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:26:05.966  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:26:05.966  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:26:05.966  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:26:05.981  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:26:05.981  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:26:05.991  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:26:05.991  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:26:05.991  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:26:11.696  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:26:13.066  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:16), LCD = 0
,07-06 08:26:14.881  3524  4972 E Watchdog: !@Sync 12 [07-06 08:26:14.886]
,07-06 08:26:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:26:15.946  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:26:15.946  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:26:20.736  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:26:20.736  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:26:23.096  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:18), LCD = 0
,07-06 08:26:31.696  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:26:33.121  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:18), LCD = 0
,07-06 08:26:36.046  3524  5518 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:26:36.046  3524  5518 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:26:36.046  3524  5518 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:26:36.046  3524  5518 D BatteryService: stay LED for fully charged
,07-06 08:26:36.046  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:26:36.051  3524  3524 I MotionRecognitionService: Plugged
07-06 08:26:36.051  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:26:36.051  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:26:36.051  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:26:36.061  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:26:36.061  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:26:36.061  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:26:36.081  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:26:36.081  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:26:36.091  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:26:36.091  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:26:36.091  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:26:43.136  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:18), LCD = 0
,07-06 08:26:44.886  3524  4972 E Watchdog: !@Sync 13 [07-06 08:26:44.890]
,07-06 08:26:51.701  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:26:53.186  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:18), LCD = 0
,07-06 08:26:54.736  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:26:54.736  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:27:03.236  3524  6867 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:20), LCD = 0
,07-06 08:27:06.141  3524  5012 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:27:06.141  3524  5012 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:27:06.141  3524  5012 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:27:06.141  3524  5012 D BatteryService: stay LED for fully charged
,07-06 08:27:06.146  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:27:06.151  3524  3524 I MotionRecognitionService: Plugged
07-06 08:27:06.151  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:27:06.151  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:27:06.151  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:27:06.156  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:27:06.156  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:27:06.156  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:27:06.176  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:27:06.176  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:27:06.186  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:27:06.186  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:27:06.186  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:27:11.706  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:27:13.286  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 271 (W:20), LCD = 0
,07-06 08:27:14.886  3524  4972 E Watchdog: !@Sync 14 [07-06 08:27:14.894]
,07-06 08:27:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:27:16.066  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:27:16.066  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:27:16.196  5028  5071 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 120ms lastUpdatedAfter : 180477ms
,07-06 08:27:20.056  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:27:20.056  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:27:23.326  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 270 (W:20), LCD = 0
,07-06 08:27:31.706  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:27:33.361  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:20), LCD = 0
,07-06 08:27:36.241  3524  5134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:27:43.396  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:22), LCD = 0
,07-06 08:27:44.896  3524  4972 E Watchdog: !@Sync 15 [07-06 08:27:44.899]
,07-06 08:27:51.706  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:27:53.431  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:22), LCD = 0
,07-06 08:28:03.461  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:22), LCD = 0
,07-06 08:28:03.946  2985  2985 I bootchecker: bootchecker wake up!!
,07-06 08:28:06.336  3524  5012 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:28:06.341  3524  5012 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:28:06.341  3524  5012 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:28:06.341  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:28:06.341  3524  5012 D BatteryService: stay LED for fully charged
,07-06 08:28:06.346  3524  3524 I MotionRecognitionService: Plugged
07-06 08:28:06.346  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:28:06.346  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:28:06.346  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:28:06.356  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:28:06.356  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:28:06.356  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:28:06.371  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:28:06.371  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:28:06.386  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:28:06.386  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:28:06.386  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:28:11.711  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:28:13.491  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:22), LCD = 0
,07-06 08:28:14.901  3524  4972 E Watchdog: !@Sync 16 [07-06 08:28:14.906]
,07-06 08:28:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:28:16.301  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:28:16.301  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:28:23.521  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:24), LCD = 0
,07-06 08:28:31.711  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:28:33.546  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:24), LCD = 0
,07-06 08:28:36.436  3524  4440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:28:36.436  3524  4440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:28:36.436  3524  4440 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:28:36.436  3524  4440 D BatteryService: stay LED for fully charged
,07-06 08:28:36.436  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:28:36.441  3524  3524 I MotionRecognitionService: Plugged
07-06 08:28:36.441  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:28:36.441  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:28:36.441  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:28:36.451  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:28:36.451  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:28:36.451  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:28:36.466  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:28:36.466  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:28:36.476  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:28:36.476  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:28:36.476  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:28:43.571  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:24), LCD = 0
,07-06 08:28:44.906  3524  4972 E Watchdog: !@Sync 17 [07-06 08:28:44.910]
,07-06 08:28:51.716  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:28:53.601  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:24), LCD = 0
,07-06 08:28:59.996  3524  4401 V AlarmManager: Expired Alarm result :8
07-06 08:28:59.996  3524  4401 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=540620 batch.start=672586
,07-06 08:29:03.636  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:26), LCD = 0
,07-06 08:29:06.516  3524  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:29:06.516  3524  5053 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:29:06.516  3524  5053 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:29:06.516  3524  5053 D BatteryService: stay LED for fully charged
,07-06 08:29:06.521  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:29:06.526  3524  3524 I MotionRecognitionService: Plugged
07-06 08:29:06.526  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:29:06.526  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:29:06.526  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:29:06.531  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:29:06.531  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:29:06.531  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:29:06.546  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:29:06.546  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:29:06.561  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:29:06.561  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:29:06.561  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:29:11.721  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:29:13.666  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:26), LCD = 0
,07-06 08:29:14.911  3524  4972 E Watchdog: !@Sync 18 [07-06 08:29:14.915]
,07-06 08:29:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:29:16.421  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:29:16.421  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:29:23.691  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:26), LCD = 0
,07-06 08:29:31.721  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:29:33.716  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:26), LCD = 0
,07-06 08:29:36.616  3524  5010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:29:36.616  3524  5010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:29:36.616  3524  5010 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:29:36.616  3524  5010 D BatteryService: stay LED for fully charged
,07-06 08:29:36.616  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:29:36.626  3524  3524 I MotionRecognitionService: Plugged
07-06 08:29:36.626  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:29:36.626  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:29:36.626  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:29:36.631  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:29:36.631  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:29:36.631  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:29:36.641  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:29:36.641  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:29:36.656  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:29:36.656  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:29:36.656  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:29:43.751  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:28), LCD = 0
,07-06 08:29:44.911  3524  4972 E Watchdog: !@Sync 19 [07-06 08:29:44.918]
,07-06 08:29:51.721  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:29:51.721  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-06 08:29:51.726  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:29:53.776  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:28), LCD = 0
,07-06 08:30:03.801  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), LCD = 0
,07-06 08:30:06.716  3524  5141 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:30:06.716  3524  5141 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:30:06.716  3524  5141 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:30:06.716  3524  5141 D BatteryService: stay LED for fully charged
,07-06 08:30:06.716  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:30:06.721  3524  3524 I MotionRecognitionService: Plugged
07-06 08:30:06.721  3524  3524 D MotionRecognitionService:   cableConnection= 1
,07-06 08:30:06.721  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:30:06.721  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:30:06.731  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:30:06.731  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,07-06 08:30:06.731  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
07-06 08:30:06.736  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found,
07-06 08:30:06.736  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:30:06.761  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:30:06.761  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-06 08:30:06.761  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:30:06.761  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:30:06.761  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:30:11.476  3524  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-06 08:30:11.476  3524  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:30:11.481  3524  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:30:11.726  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:30:13.821  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), LCD = 0
,07-06 08:30:14.916  3524  4972 E Watchdog: !@Sync 20 [07-06 08:30:14.922]
,07-06 08:30:14.956  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-06 08:30:14.956  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:30:14.971  3524  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-06 08:30:14.971  3524  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:30:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:30:16.516  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:30:16.516  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:30:16.626  5028  5071 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 101ms lastUpdatedAfter : 180427ms
,07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLock,ed: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.036  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-06 08:30:18.041  3524  3661 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-06 08:30:18.156  3524  3765 I ActivityManager: setMaxStartingBackgroundTimer onfinish
07-06 08:30:18.156  3524  3765 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-06 08:30:23.851  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:30:31.731  3524  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 08:30:33.881  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:30:36.811  3524  3550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:30:36.811  3524  3550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:30:36.811  3524  3550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:30:36.811  3524  3550 D BatteryService: stay LED for fully charged
,07-06 08:30:36.811  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:30:36.816  3524  3524 I MotionRecognitionService: Plugged
07-06 08:30:36.816  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:30:36.816  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:30:36.816  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:30:36.826  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:30:36.826  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:30:36.826  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:30:36.846  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:30:36.846  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:30:36.851  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-06 08:30:36.851  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:30:36.851  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:30:43.911  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:30:44.916  3524  4972 E Watchdog: !@Sync 21 [07-06 08:30:44.923]
,07-06 08:30:51.021  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:30:51.021  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:30:53.936  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:31:03.966  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:31:06.096  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:31:06.096  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:31:06.901  3524  5134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:31:06.901  3524  5134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
,07-06 08:31:06.906  3524  5134 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:31:06.906  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:31:06.906  3524  5134 D BatteryService: stay LED for fully charged
,07-06 08:31:06.911  3524  3524 I MotionRecognitionService: Plugged
07-06 08:31:06.911  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:31:06.911  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:31:06.911  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:31:06.921  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:31:06.921  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:31:06.921  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:31:06.946  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:31:06.946  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:31:06.946  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-06 08:31:06.946  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:31:06.946  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:31:13.996  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:31:14.926  3524  4972 E Watchdog: !@Sync 22 [07-06 08:31:14.928]
,07-06 08:31:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:31:16.741  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:31:16.741  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:31:24.021  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:31:34.051  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:31:36.996  3524  4553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:31:44.081  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:31:44.926  3524  4972 E Watchdog: !@Sync 23 [07-06 08:31:44.932]
,07-06 08:31:54.106  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:32:04.151  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:32:04.256  3524  3536 I art     : Background sticky concurrent mark sweep GC freed 85451(8MB) AllocSpace objects, 305(5MB) LOS objects, 32% free, 31MB/46MB, paused 4.112ms total 113.288ms
,07-06 08:32:07.101  3524  4440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:32:07.101  3524  4440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:32:07.101  3524  4440 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
,07-06 08:32:07.101  3524  4440 D BatteryService: stay LED for fully charged
07-06 08:32:07.101  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:32:07.106  3524  3524 I MotionRecognitionService: Plugged
07-06 08:32:07.106  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:32:07.106  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:32:07.106  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:32:07.111  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:32:07.111  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,07-06 08:32:07.111  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:32:07.121  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:32:07.121  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:32:07.131  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:32:07.131  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:32:07.131  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:32:14.176  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:32:14.931  3524  4972 E Watchdog: !@Sync 24 [07-06 08:32:14.936]
,07-06 08:32:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:32:16.856  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:32:16.856  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:32:24.201  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:32:34.231  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:32:37.196  3524  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:32:44.261  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:32:44.936  3524  4972 E Watchdog: !@Sync 25 [07-06 08:32:44.942]
,07-06 08:32:54.286  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:33:04.326  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:33:07.286  3524  5054 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:33:14.346  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:33:14.941  3524  4972 E Watchdog: !@Sync 26 [07-06 08:33:14.948]
,07-06 08:33:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:33:16.971  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:33:16.971  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:33:17.086  5028  5071 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 100ms lastUpdatedAfter : 180461ms
,07-06 08:33:18.246  3524  5885 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
07-06 08:33:18.251  3524  5885 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-06 08:33:18.251  3524  5885 V MARsPolicyManager: updateSMDBValues
,07-06 08:33:18.256  3524  3763 E MARsDBManager: updateDBAll : begin --size 1
,07-06 08:33:18.306  3524  3763 E MARsDBManager: updateDBAll : end
,07-06 08:33:18.306  3524  3763 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-06 08:33:24.376  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:33:34.406  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:33:37.391  3524  5821 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:33:44.431  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:33:44.951  3524  4972 E Watchdog: !@Sync 27 [07-06 08:33:44.955]
,07-06 08:33:54.456  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:34:04.486  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:34:07.491  3524  5868 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:34:07.491  3524  5868 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:34:07.491  3524  5868 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:34:07.491  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:34:07.491  3524  5868 D BatteryService: stay LED for fully charged
,07-06 08:34:07.496  3524  3524 I MotionRecognitionService: Plugged
07-06 08:34:07.496  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:34:07.496  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:34:07.496  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:34:07.506  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:34:07.506  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:34:07.506  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:34:07.531  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:34:07.531  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:34:07.531  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-06 08:34:07.531  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:34:07.531  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:34:14.511  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:34:14.956  3524  4972 E Watchdog: !@Sync 28 [07-06 08:34:14.961]
,07-06 08:34:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:34:17.176  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:34:17.176  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:34:24.541  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:34:34.566  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:34:37.591  3524  3550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:34:37.591  3524  3550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:34:37.591  3524  3550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:34:37.591  3524  3550 D BatteryService: stay LED for fully charged
,07-06 08:34:37.591  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:34:37.596  3524  3524 I MotionRecognitionService: Plugged
07-06 08:34:37.596  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:34:37.596  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:34:37.596  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:34:37.606  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:34:37.606  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:34:37.606  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:34:37.621  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:34:37.621  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:34:37.636  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:34:37.636  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:34:37.636  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:34:44.591  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:34:44.961  3524  4972 E Watchdog: !@Sync 29 [07-06 08:34:44.965]
,07-06 08:34:54.621  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:35:04.651  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:35:07.696  3524  5054 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:35:07.696  3524  5054 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:35:07.696  3524  5054 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:35:07.701  3524  5054 D BatteryService: stay LED for fully charged
,07-06 08:35:07.701  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:35:07.706  3524  3524 I MotionRecognitionService: Plugged
07-06 08:35:07.706  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:35:07.706  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:35:07.706  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:35:07.711  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:35:07.711  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:35:07.711  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:35:07.731  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:35:07.731  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:35:07.741  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:35:07.741  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:35:07.741  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:35:11.481  3524  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-06 08:35:11.481  3524  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:35:11.481  3524  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:35:14.671  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:35:14.966  3524  4972 E Watchdog: !@Sync 30 [07-06 08:35:14.971]
,07-06 08:35:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:35:16.151  3524  4401 V AlarmManager: Expired Alarm result :4
,07-06 08:35:16.221  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-06 08:35:16.221  4512  4512 I PERF    : received broadcast android.intent.action.TIME_TICK
07-06 08:35:16.221  4512  4512 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:35:16.231  4512  4512 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:35:16.236  4512  4512 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 08:35:16.246  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:16.246  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:16.246  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:35:16.246  3524  3678 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
07-06 08:35:16.246  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:35:16.246  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:16.251  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:35:16.251  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:16.261  5277 11878 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-06 08:35:16.286  3524  3524 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-06 08:35:16.291  3524  3524 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:35:16.291  3524  3524 I Sensors : Light old sensor_state 1, new sensor_state : 513 en : 1
,07-06 08:35:16.301  3524  3524 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-06 08:35:16.321  5277 11874 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-06 08:35:16.321  3524  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{88b71be u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcc6713 7701:com.google.android.gms/u0a14}
,07-06 08:35:16.396  3524  3550 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{160213b u0 bg_app_info qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4230cba 7448:tv.peel.smartremote/u0a186}
,07-06 08:35:16.466  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:35:16.476  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:35:16.476  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:35:16.486  7701 11886 I EventLogChimeraService: Aggregate from 1467784981853 (log), 1467784981853 (data)
,07-06 08:35:16.486  5277 11874 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,07-06 08:35:16.491  5277 11874 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-06 08:35:16.501  5277 11874 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-06 08:35:16.501  5277 11874 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-06 08:35:16.546  5277 11874 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
,07-06 08:35:16.551  5277 11874 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-06 08:35:16.571  5277 11874 E ContextCompilationHandl: No recognition context built for APP_NAMES en-US
,07-06 08:35:16.571  5277 11874 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-06 08:35:16.611  3524  4379 I Sensors : #>LightSensor r=0 g=1 b=2 c=3 atime=238 again=64 lux=0.000000
,07-06 08:35:16.611  3524  3804 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-06 08:35:16.611  3524  3804 I Sensors : Light old sensor_state 513, new sensor_state : 1 en : 0
,07-06 08:35:16.611  3524  3804 D SensorManager: unregisterListener ::   
07-06 08:35:16.611  3524  3804 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-06 08:35:16.611  3524  3804 V AlarmManager:  remove PendingIntent] PendingIntent{d65f7fa: PendingIntentRecord{b54f1ab android broadcastIntent}}
,07-06 08:35:16.616  3524  3550 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10014
,07-06 08:35:16.651 11892 11892 E Zygote  : v2
07-06 08:35:16.651 11892 11892 I libpersona: KNOX_SDCARD checking this for 1000
07-06 08:35:16.651 11892 11892 I libpersona: KNOX_SDCARD not a persona
07-06 08:35:16.651  3524  3678 I ActivityManager: Start proc 11892:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,07-06 08:35:16.656 11892 11892 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-06 08:35:16.656 11892 11892 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-06 08:35:16.656 11892 11892 E Zygote  : accessInfo : 0
,07-06 08:35:16.691 11892 11892 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:35:16.691 11892 11892 D ActivityThread: Added TimaKeyStore provider
,07-06 08:35:16.701  7701  8815 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-06 08:35:16.706  3524  5821 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c637cb3 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bccd270 11892:com.samsung.android.sm/1000}
,07-06 08:35:16.776  3524  5053 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c637cb3 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcc6713 7701:com.google.android.gms/u0a14}
,07-06 08:35:16.781  7701  8814 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-06 08:35:16.826  7701  9113 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-06 08:35:16.841  3524  5010 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1bdb7a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bccd270 11892:com.samsung.android.sm/1000}
,07-06 08:35:16.851  7701 11891 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-06 08:35:16.866  3524  5010 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1bdb7a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcc6713 7701:com.google.android.gms/u0a14}
,07-06 08:35:16.871  7701  8815 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-06 08:35:17.056  5277 11874 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
07-06 08:35:17.056  5277 11874 E native  : request_context {
07-06 08:35:17.056  5277 11874 E native  :   type: DYNAMIC_CLASS
07-06 08:35:17.056  5277 11874 E native  :   dynamic_class_context {
07-06 08:35:17.056  5277 11874 E native  :     class_type: SONG_NAME
07-06 08:35:17.056  5277 11874 E native  :     instance {
07-06 08:35:17.056  5277 11874 E native  :       value: "Over the Horizon"
07-06 08:35:17.056  5277 11874 E native  :     }
07-06 08:35:17.056  5277 11874 E native  :   }
07-06 08:35:17.056  5277 11874 E native  : }
07-06 08:35:17.056  5277 11874 E native  : request_context {
07-06 08:35:17.056  5277 11874 E native  :   type: DYNAMIC_CLASS
07-06 08:35:17.056  5277 11874 E native  :   dynamic_class_context {
07-06 08:35:17.056  5277 11874 E native  :     class_type: UNKNOWN_DYNAMIC_CLASS
07-06 08:35:17.056  5277 11874 E native  :     instance {
07-06 08:35:17.056  5277 11874 E native  :       value: "Brand Music"
07-06 08:35:17.056  5277 11874 E native  :     }
07-06 08:35:17.056  5277 11874 E native  :   }
07-06 08:35:17.056  5277 11874 E native  : }
07-06 08:35:17.056  5277 11874 E native  : request_context {
07-06 08:35:17.056  5277 11874 E native  :   type: DYNAMIC_CLASS
07-06 08:35:17.056  5277 11874 E native  :   dynamic_class_context {
07-06 08:35:17.056  5277 11874 E native  :     class_type: ARTIST_NAME
07-06 08:35:17.056  5277 11874 E native  :     instance {
07-06 08:35:17.056  5277 11874 E native  :       value: "Samsung"
07-06 08:35:17.056  5277 11874 E native  :     }
07-06 08:35:17.056  5277 11874 E native  :   }
07-06 08:35:17.056  5277 11874 E native  : }
07-06 08:35:17.056  5277 11874 E native  : 
,07-06 08:35:17.056  5277 11874 E ContextCompilationHandl: Compiling recognition context failed for MUSIC_NAMES en-US
,07-06 08:35:17.096  7701 11904 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-06 08:35:17.106  7448  7492 I System.out: Thread-478(ApacheHTTPLog):isSBSettingEnabled false
07-06 08:35:17.106  7448  7492 I System.out: Thread-478(ApacheHTTPLog):isShipBuild true
07-06 08:35:17.106  7448  7492 I System.out: Thread-478(ApacheHTTPLog):getDebugLevel 0x4f4c
07-06 08:35:17.106  7448  7492 I System.out: Thread-478(ApacheHTTPLog):Smart Bonding Setting is false
07-06 08:35:17.106  7448  7492 I System.out: Thread-478(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-06 08:35:17.106  2915  4370 D EnterpriseController: netId is 0
07-06 08:35:17.106  2915  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10186
,07-06 08:35:17.151  7701 11904 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-06 08:35:17.321  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:35:17.321  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:35:17.836  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-06 08:35:17.836  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:35:17.851  3524  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:35:17.851  3524  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:35:17.976  7448  7492 I System.out: non-ui calls detatch()
,07-06 08:35:20.601  3524  4401 V AlarmManager: Expired Alarm result :4
,07-06 08:35:20.641  5781  5961 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-06 08:35:21.046  3524  5141 V AlarmManager:  remove PendingIntent] PendingIntent{dc4f8a3: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.076  3524  3549 V AlarmManager:  remove PendingIntent] PendingIntent{1b1b7a0: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.096  3524  3550 V AlarmManager:  remove PendingIntent] PendingIntent{45e1f59: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.111  3524  5010 V AlarmManager:  remove PendingIntent] PendingIntent{176a71e: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}},
,07-06 08:35:21.131  3524  5134 V AlarmManager:  remove PendingIntent] PendingIntent{5a47bff: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.146  3524  3549 V AlarmManager:  remove PendingIntent] PendingIntent{b0aadcc: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.166  3524  3550 V AlarmManager:  remove PendingIntent] PendingIntent{c485815: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.196  3524  5010 V AlarmManager:  remove PendingIntent] PendingIntent{ae2172a: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.211  3524  5134 V AlarmManager:  remove PendingIntent] PendingIntent{9ced91b: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.216  3524  3549 V AlarmManager:  remove PendingIntent] PendingIntent{91adab8: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.226  3524  3550 V AlarmManager:  remove PendingIntent] PendingIntent{1636091: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.231  3524  5010 V AlarmManager:  remove PendingIntent] PendingIntent{fe27bf6: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.241  3524  5134 V AlarmManager:  remove PendingIntent] PendingIntent{b77ebf7: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.246  3524  3549 V AlarmManager:  remove PendingIntent] PendingIntent{3feea64: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.251  3524  3550 V AlarmManager:  remove PendingIntent] PendingIntent{c4c74cd: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.256  3524  5010 V AlarmManager:  remove PendingIntent] PendingIntent{bb26182: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.261  3524  5134 V AlarmManager:  remove PendingIntent] PendingIntent{1355093: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.271  3524  3549 V AlarmManager:  remove PendingIntent] PendingIntent{6f248d0: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.281  3524  3550 V AlarmManager:  remove PendingIntent] PendingIntent{83890c9: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.286  3524  5010 V AlarmManager:  remove PendingIntent] PendingIntent{a913ce: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.291  3524  5141 V AlarmManager:  remove PendingIntent] PendingIntent{b5a62ef: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.296  3524  5054 V AlarmManager:  remove PendingIntent] PendingIntent{37b21fc: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.296  3524  4553 V AlarmManager:  remove PendingIntent] PendingIntent{4b07085: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.301  3524  3550 V AlarmManager:  remove PendingIntent] PendingIntent{d469eda: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.306  3524  5858 V AlarmManager:  remove PendingIntent] PendingIntent{2143f0b: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.306  3524  5053 V AlarmManager:  remove PendingIntent] PendingIntent{b5661e8: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.311  3524  5012 V AlarmManager:  remove PendingIntent] PendingIntent{70c9001: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.316  3524  3549 V AlarmManager:  remove PendingIntent] PendingIntent{5ffcea6: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.316  3524  4440 V AlarmManager:  remove PendingIntent] PendingIntent{945c0e7: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.321  3524  5868 V AlarmManager:  remove PendingIntent] PendingIntent{d23b494: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.326  3524  5821 V AlarmManager:  remove PendingIntent] PendingIntent{7b12b3d: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.326  3524  5134 V AlarmManager:  remove PendingIntent] PendingIntent{fca2f32: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.331  3524  4654 V AlarmManager:  remove PendingIntent] PendingIntent{6238483: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}},
,07-06 08:35:21.331  3524  5815 V AlarmManager:  remove PendingIntent] PendingIntent{fd18600: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.336  3524  5518 V AlarmManager:  remove PendingIntent] PendingIntent{70a3e39: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.341  3524  5010 V AlarmManager:  remove PendingIntent] PendingIntent{7680c7e: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.341  3524  5141 V AlarmManager:  remove PendingIntent] PendingIntent{28fe5df: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:35:21.941  3524  3549 I ActivityManager: Killing 10536:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,07-06 08:35:22.006  3524  4553 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,07-06 08:35:24.696  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:35:34.721  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:35:37.801  3524  5010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:35:41.936  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:35:41.936  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:35:44.756  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:35:44.981  3524  4972 E Watchdog: !@Sync 31 [07-06 08:35:44.984]
,07-06 08:35:54.781  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:35:59.996  3524  4401 V AlarmManager: Expired Alarm result :8
,07-06 08:36:04.811  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:36:07.886  3524  5518 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:36:07.886  3524  5518 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:36:07.886  3524  5518 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:36:07.891  3524  5518 D BatteryService: stay LED for fully charged
,07-06 08:36:07.891  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:36:07.896  3524  3524 I MotionRecognitionService: Plugged
07-06 08:36:07.896  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:36:07.896  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:36:07.896  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:36:07.906  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:36:07.906  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:36:07.906  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:36:07.926  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:36:07.926  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:36:07.941  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:36:07.941  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:36:07.941  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:36:10.821  3524  3678 W ProcessCpuTracker: Skipping unknown process pid 11997
,07-06 08:36:14.841  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:36:14.991  3524  4972 E Watchdog: !@Sync 32 [07-06 08:36:14.996]
,07-06 08:36:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:36:17.411  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:36:17.411  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:36:24.871  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:36:34.906  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:36:37.986  3524  5010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:36:37.986  3524  5010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:36:37.986  3524  5010 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:36:37.986  3524  5010 D BatteryService: stay LED for fully charged
,07-06 08:36:37.986  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:36:37.991  3524  3524 I MotionRecognitionService: Plugged
07-06 08:36:37.991  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:36:37.991  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:36:37.991  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:36:38.001  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:36:38.001  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:36:38.001  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-06 08:36:38.021  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,07-06 08:36:38.021  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-06 08:36:38.026  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:36:38.026  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-06 08:36:38.026  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:36:44.931  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:36:44.996  3524  4972 E Watchdog: !@Sync 33 [07-06 08:36:45.000]
,07-06 08:36:54.956  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:37:04.991  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:37:08.081  3524  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:37:14.996  3524  4972 E Watchdog: !@Sync 34 [07-06 08:37:15.004]
,07-06 08:37:15.021  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:37:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:37:17.526  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:37:17.526  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:37:25.051  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:37:35.081  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:37:38.176  3524  5821 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:37:38.176  3524  5821 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:37:38.176  3524  5821 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:37:38.176  3524  5821 D BatteryService: stay LED for fully charged
,07-06 08:37:38.176  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:37:38.181  3524  3524 I MotionRecognitionService: Plugged
07-06 08:37:38.181  3524  3524 D MotionRecognitionService:   cableConnection= 1
,07-06 08:37:38.181  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:37:38.181  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:37:38.191  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:37:38.191  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:37:38.191  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:37:38.211  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:37:38.211  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:37:38.216  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:37:38.216  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:37:38.216  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:37:45.006  3524  4972 E Watchdog: !@Sync 35 [07-06 08:37:45.009]
,07-06 08:37:45.106  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:37:55.136  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:38:05.166  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:38:08.276  3524  5858 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:38:08.276  3524  5858 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:38:08.276  3524  5858 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:38:08.276  3524  5858 D BatteryService: stay LED for fully charged
,07-06 08:38:08.276  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:38:08.281  3524  3524 I MotionRecognitionService: Plugged
07-06 08:38:08.281  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:38:08.281  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:38:08.281  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:38:08.291  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:38:08.291  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:38:08.291  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:38:08.296  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:38:08.296  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:38:08.311  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:38:08.311  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:38:08.311  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:38:15.011  3524  4972 E Watchdog: !@Sync 36 [07-06 08:38:15.016]
,07-06 08:38:15.196  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:38:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:38:17.646  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:38:17.646  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:38:17.736  5028  5071 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 2Kb duration : 76ms lastUpdatedAfter : 180943ms
,07-06 08:38:25.226  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:38:35.256  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:38:38.366  3524  5134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:38:38.371  3524  5134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:38:38.371  3524  5134 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:38:38.371  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:38:38.371  3524  5134 D BatteryService: stay LED for fully charged
,07-06 08:38:38.381  3524  3524 I MotionRecognitionService: Plugged
07-06 08:38:38.381  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:38:38.381  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:38:38.381  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:38:38.391  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:38:38.391  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:38:38.391  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:38:38.411  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:38:38.411  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:38:38.416  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:38:38.416  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:38:38.416  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:38:45.016  3524  4972 E Watchdog: !@Sync 37 [07-06 08:38:45.021]
,07-06 08:38:45.286  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:38:55.311  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:39:05.341  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:39:08.461  3524  5012 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:39:15.021  3524  4972 E Watchdog: !@Sync 38 [07-06 08:39:15.024]
,07-06 08:39:15.371  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:39:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:39:17.836  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:39:17.836  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:39:25.406  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:39:35.441  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:39:38.561  3524  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:39:38.561  3524  5053 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:39:38.561  3524  5053 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:39:38.561  3524  5053 D BatteryService: stay LED for fully charged
,07-06 08:39:38.561  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:39:38.566  3524  3524 I MotionRecognitionService: Plugged
07-06 08:39:38.566  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:39:38.566  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:39:38.566  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:39:38.576  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,07-06 08:39:38.576  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:39:38.576  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:39:38.591  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:39:38.591  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:39:38.606  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:39:38.606  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:39:38.606  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:39:45.021  3524  4972 E Watchdog: !@Sync 39 [07-06 08:39:45.028]
,07-06 08:39:45.466  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:39:55.501  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:40:05.536  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:40:08.656  3524  5141 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:40:11.481  3524  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-06 08:40:11.481  3524  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:40:11.481  3524  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:40:11.856  3524  3661 I UsageStatsService: User[0] Flushing usage stats to disk
,07-06 08:40:15.026  3524  4972 E Watchdog: !@Sync 40 [07-06 08:40:15.030]
,07-06 08:40:15.056  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-06 08:40:15.056  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:40:15.071  3524  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:40:15.076  3524  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:40:15.571  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:40:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:40:17.976  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:40:17.976  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:40:25.596  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:40:35.626  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:40:38.756  3524  5858 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:40:38.756  3524  5858 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:40:38.756  3524  5858 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:40:38.756  3524  5858 D BatteryService: stay LED for fully charged
,07-06 08:40:38.756  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:40:38.761  3524  3524 I MotionRecognitionService: Plugged
07-06 08:40:38.761  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:40:38.761  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:40:38.761  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:40:38.771  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:40:38.771  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:40:38.771  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:40:38.791  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:40:38.791  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:40:38.796  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:40:38.796  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:40:38.796  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:40:45.031  3524  4972 E Watchdog: !@Sync 41 [07-06 08:40:45.032]
,07-06 08:40:45.661  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:40:55.686  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:41:05.721  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0,
,07-06 08:41:08.856  3524  5134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:41:08.856  3524  5134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:41:08.856  3524  5134 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:41:08.856  3524  5134 D BatteryService: stay LED for fully charged
,07-06 08:41:08.861  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:41:08.866  3524  3524 I MotionRecognitionService: Plugged
07-06 08:41:08.866  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:41:08.866  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:41:08.866  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:41:08.871  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:41:08.871  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:41:08.871  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:41:08.891  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:41:08.891  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:41:08.896  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:41:08.896  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:41:08.896  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:41:15.031  3524  4972 E Watchdog: !@Sync 42 [07-06 08:41:15.036]
,07-06 08:41:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:41:15.751  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:41:18.101  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:41:18.101  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:41:18.201  5028  5071 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 91ms lastUpdatedAfter : 180469ms
,07-06 08:41:25.776  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:41:35.801  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:41:38.951  3524  5012 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:41:45.031  3524  4972 E Watchdog: !@Sync 43 [07-06 08:41:45.038]
,07-06 08:41:45.831  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0,
,07-06 08:41:55.861  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-06 08:42:05.886  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:30), LCD = 0
,07-06 08:42:09.036  3524  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:42:09.036  3524  5053 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:42:09.036  3524  5053 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:42:09.036  3524  5053 D BatteryService: stay LED for fully charged
,07-06 08:42:09.036  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:42:09.041  3524  3524 I MotionRecognitionService: Plugged
07-06 08:42:09.041  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:42:09.041  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:42:09.041  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:42:09.056  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:42:09.056  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:42:09.056  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:42:09.061  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:42:09.061  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:42:09.076  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:42:09.076  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:42:09.076  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:42:15.036  3524  4972 E Watchdog: !@Sync 44 [07-06 08:42:15.040]
,07-06 08:42:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:42:15.921  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 259 (W:28), LCD = 0
,07-06 08:42:18.306  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:42:18.306  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:42:25.956  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 259 (W:28), LCD = 0
,07-06 08:42:35.986  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:28), LCD = 0
,07-06 08:42:39.141  3524  5141 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:42:39.141  3524  5141 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:42:39.141  3524  5141 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:42:39.141  3524  5141 D BatteryService: stay LED for fully charged
07-06 08:42:39.141  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:42:39.146  3524  3524 I MotionRecognitionService: Plugged
07-06 08:42:39.146  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:42:39.146  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:42:39.146  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:42:39.146  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:42:39.146  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:42:39.146  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:42:39.151  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:42:39.156  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:42:39.166  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:42:39.166  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:42:39.171  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:42:45.046  3524  4972 E Watchdog: !@Sync 45 [07-06 08:42:45.047]
,07-06 08:42:46.016  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:28), LCD = 0
,07-06 08:42:56.046  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:30), LCD = 0
,07-06 08:43:06.081  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:30), LCD = 0
,07-06 08:43:09.261  3524  5054 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:43:09.261  3524  5054 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:43:09.261  3524  5054 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:43:09.261  3524  5054 D BatteryService: stay LED for fully charged
,07-06 08:43:09.261  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:43:09.271  3524  3524 I MotionRecognitionService: Plugged
,07-06 08:43:09.271  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:43:09.271  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:43:09.271  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:43:09.281  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:43:09.281  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:43:09.281  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:43:09.301  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:43:09.301  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:43:09.306  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:43:09.306  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:43:09.306  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:15.051  3524  4972 E Watchdog: !@Sync 46 [07-06 08:43:15.051]
,07-06 08:43:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:43:16.106  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:30), LCD = 0
,07-06 08:43:18.436  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:43:18.436  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:43:26.136  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:30), LCD = 0
,07-06 08:43:36.166  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:30), LCD = 0
,07-06 08:43:39.356  3524  5815 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:43:39.356  3524  5815 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:43:39.356  3524  5815 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:43:39.356  3524  5815 D BatteryService: stay LED for fully charged
,07-06 08:43:39.361  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:43:39.366  3524  3524 I MotionRecognitionService: Plugged
07-06 08:43:39.366  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:43:39.366  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:43:39.366  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:43:39.371  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:43:39.371  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:43:39.371  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:43:39.386  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:39.386  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:43:39.386  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-06 08:43:39.386  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:39.401  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:43:45.051  3524  4972 E Watchdog: !@Sync 47 [07-06 08:43:45.055]
,07-06 08:43:46.201  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:30), LCD = 0
,07-06 08:43:56.226  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:30), LCD = 0
,07-06 08:44:06.266  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:30), LCD = 0
,07-06 08:44:09.436  3524  4553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:44:09.441  3524  4553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:44:09.441  3524  4553 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:44:09.441  3524  4553 D BatteryService: stay LED for fully charged
,07-06 08:44:09.441  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:44:09.446  3524  3524 I MotionRecognitionService: Plugged
07-06 08:44:09.446  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:44:09.446  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:44:09.446  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:44:09.456  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:44:09.456  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:44:09.456  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:44:09.466  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:44:09.466  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:44:09.481  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:44:09.481  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:44:09.481  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:44:15.051  3524  4972 E Watchdog: !@Sync 48 [07-06 08:44:15.058]
,07-06 08:44:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:44:16.296  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:28), LCD = 0
,07-06 08:44:18.511  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:44:18.511  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:44:18.626  5028  5071 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 99ms lastUpdatedAfter : 180421ms
,07-06 08:44:26.326  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:28), LCD = 0
,07-06 08:44:36.351  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:28), LCD = 0
,07-06 08:44:39.541  3524  5868 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:44:45.056  3524  4972 E Watchdog: !@Sync 49 [07-06 08:44:45.064]
,07-06 08:44:46.381  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:28), LCD = 0
,07-06 08:44:56.411  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:30), LCD = 0
,07-06 08:45:06.446  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:30), LCD = 0
,07-06 08:45:09.636  3524  4440 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:45:09.636  3524  4440 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:45:09.636  3524  4440 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:45:09.636  3524  4440 D BatteryService: stay LED for fully charged
,07-06 08:45:09.641  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:45:09.646  3524  3524 I MotionRecognitionService: Plugged
07-06 08:45:09.646  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:45:09.646  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:45:09.646  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:45:09.651  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:45:09.651  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:45:09.656  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:45:09.671  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:45:09.671  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:45:09.681  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:45:09.681  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:45:09.681  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:45:11.481  3524  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-06 08:45:11.481  3524  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 08:45:11.481  3524  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 08:45:15.066  3524  4972 E Watchdog: !@Sync 50 [07-06 08:45:15.071]
,07-06 08:45:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:45:16.466  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 253 (W:28), LCD = 0
,07-06 08:45:18.271  3524  5885 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
07-06 08:45:18.271  3524  5885 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-06 08:45:18.271  3524  5885 V MARsPolicyManager: updateSMDBValues
,07-06 08:45:18.271  3524  3763 E MARsDBManager: updateDBAll : begin --size 0
07-06 08:45:18.271  3524  3763 E MARsDBManager: updateDBAll : end
,07-06 08:45:18.311  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-06 08:45:18.311  3524  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 08:45:18.326  3524  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-06 08:45:18.326  3524  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 08:45:18.736  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:45:18.736  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:45:26.496  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:28), LCD = 0
,07-06 08:45:36.526  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:28), LCD = 0
,07-06 08:45:39.731  3524  3550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:45:39.731  3524  3550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:45:39.731  3524  3550 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:45:39.731  3524  3550 D BatteryService: stay LED for fully charged
,07-06 08:45:39.731  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:45:39.736  3524  3524 I MotionRecognitionService: Plugged
07-06 08:45:39.736  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:45:39.736  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:45:39.736  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:45:39.746  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:45:39.746  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:45:39.746  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:45:39.766  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:45:39.766  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:45:39.771  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:45:39.776  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:45:39.776  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:45:45.071  3524  4972 E Watchdog: !@Sync 51 [07-06 08:45:45.076]
,07-06 08:45:46.556  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:28), LCD = 0
,07-06 08:45:56.591  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:30), LCD = 0
,07-06 08:46:06.621  3524  6867 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:30), LCD = 0
,07-06 08:46:09.821  3524  5518 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:46:14.791  3524  4416 D InputReader: Input event(10): value=1 when=1575415319000
07-06 08:46:14.791  3524  4416 D InputReader: !@notifyKey(172), action=0
,07-06 08:46:14.801  3524  4416 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,07-06 08:46:14.821  3524  4416 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1200000  uid : 1000  pid : 3524  pkgName : WAKEUP_BOOSTER@31,
,07-06 08:46:14.826  3524  4416 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-06 08:46:14.826  3524  4416 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 3524) eventTime = 1575415 event = 1
07-06 08:46:14.826  3524  4416 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 3524) (1)
,07-06 08:46:14.826  3524  4416 I PowerManagerService: Waking up from sleep (uid 1000)...
07-06 08:46:14.826  3524  4416 D InputManager-JNI: setInteractive(true)
07-06 08:46:14.826  3524  4490 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
07-06 08:46:14.826  3524  4490 I WindowManager: Started waking up...
07-06 08:46:14.826  3524  4416 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-06 08:46:14.826  3524  4490 V KeyguardServiceDelegate: onStartedWakingUp()
07-06 08:46:14.826  3524  4416 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-06 08:46:14.826  3524  4416 D PowerManagerService: mDisplayReady: false
07-06 08:46:14.826  3524  4416 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-06 08:46:14.826  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:14.826  3524  4416 D InputManager-JNI: Disable repeat for home key when device wake up
07-06 08:46:14.826  3524  3788 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
07-06 08:46:14.826  3524  3788 I WindowManager: Screen turning on...
,07-06 08:46:14.826  3524  4416 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-06 08:46:14.826  4512  6982 I PERF    : KeyguardViewMediator - onStartedWakingUp() start
07-06 08:46:14.826  3524  3788 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-06 08:46:14.846  3524  3678 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,07-06 08:46:14.866  3524  3788 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@64784f5)
07-06 08:46:14.866  3524  3788 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
07-06 08:46:14.866  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: return as screen on blocked
07-06 08:46:14.866  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:14.866  3524  3788 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-06 08:46:14.866  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:14.866  3524  3811 I libsuspend: !@autosuspend_wakeup_count_disable
07-06 08:46:14.866  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:14.866  3524  3811 I libsuspend: !@autosuspend_wakeup_count_disable done
07-06 08:46:14.866  3524  4492 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
07-06 08:46:14.866  4512  6982 D KeyguardViewMediator: onStartedWakingUp, seq = 2
07-06 08:46:14.866  3524  3811 D DisplayManagerService: !@display_state: OFF -> ON brightness: 0 -> 0
07-06 08:46:14.866  4512  6982 D KeyguardViewMediator: notifyStartedWakingUp
07-06 08:46:14.866  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 2, mProxSensorScreenOff: false
07-06 08:46:14.866  3524  4492 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
07-06 08:46:14.866  3524  3765 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-06 08:46:14.866  2905  2905 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
07-06 08:46:14.866  2905  2905 I hwcomposer: int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(0)
07-06 08:46:14.871  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() start
,07-06 08:46:14.871  4512  4512 D KeyguardViewMediator: handleNotifyWakingUp
07-06 08:46:14.871  3524  4492 I Sensors : Light old sensor_state 1, new sensor_state : 513 en : 1
07-06 08:46:14.871  4512  4512 D PanelView: onScreenTurnedOn 0,1
07-06 08:46:14.871  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() end
07-06 08:46:14.871  4512  4512 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() start
,07-06 08:46:14.886  3524  4492 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 250000, 0,  
,07-06 08:46:14.886 10814 10980 W fb4a(:<default>):QeInternalImpl: The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
07-06 08:46:14.886  3524  4492 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:46:14.886  3524  3524 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-06 08:46:14.886  3524  3678 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-06 08:46:14.886  3524  4492 D SensorManager: registerListener :: 0, ICM20610 Acceleration Sensor, 250000, 0,  
07-06 08:46:14.886  3524  4492 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::registerListener done: 21ms
,07-06 08:46:14.896  4512  4512 D SecKeyguardClockSingleView: onScreenTurnedOn
,07-06 08:46:14.896  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:46:14.896  4512  4512 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() end
,07-06 08:46:14.896 11392 11392 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-06 08:46:14.896 11392 11392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-06 08:46:14.901  4512  6982 I PERF    : KeyguardViewMediator - onStartedWakingUp() end
07-06 08:46:14.901  4512  4512 D KeyguardViewMediator: callback.onShown()
07-06 08:46:14.901 11392 11392 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-06 08:46:14.901 11392 11392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-06 08:46:14.901  4512  6982 D KeyguardViewMediator: notifyScreenOn
07-06 08:46:14.901  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() start
07-06 08:46:14.901  4512  4512 D KeyguardViewMediator: handleNotifyScreenTurningOn
07-06 08:46:14.901  4512  4512 D KeyguardViewMediator: onScreenTurnedOn()
07-06 08:46:14.901  3524  4654 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-06 08:46:14.901  3524  4654 D WindowManager: mKeyguardDelegate.ShowListener.onDrawn.
07-06 08:46:14.901  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() end
,07-06 08:46:14.911  3524  5134 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,07-06 08:46:14.911  5709  5709 D SamsungIME: showDlgMsgBox : false true true
,07-06 08:46:14.916  3524  4379 E Sensors : Sensor : Meta event
,07-06 08:46:14.916  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:46:14.916  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-06 08:46:14.916  5102 12278 D NfcService: call the applyRouting
,07-06 08:46:14.916  6986  6986 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
07-06 08:46:14.916  6986  6986 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
,07-06 08:46:14.921  4512  4512 D BatteryMeterView: onDraw batteryColor : -1107296257
,07-06 08:46:14.926  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{174728a u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bccd270 11892:com.samsung.android.sm/1000}
07-06 08:46:14.926  3524  5053 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-06 08:46:14.926  3524  5053 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-06 08:46:14.926  3524  3685 W WindowManager: Setting mKeyguardDrawComplete
07-06 08:46:14.926  3524  3685 I WindowManager: All windows ready for display!
07-06 08:46:14.926  3524  3685 W WindowManager: Setting mWindowManagerDrawComplete
,07-06 08:46:14.926  3524  3685 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-06 08:46:14.931  3524  3685 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,07-06 08:46:14.931  3524  3685 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,07-06 08:46:14.931  3524  3685 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
07-06 08:46:14.931  3524  3685 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-06 08:46:14.931  3524  3685 V CAE     : start(ContextProvider.java:128)
07-06 08:46:14.936  3524  3524 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN,
07-06 08:46:14.936  3524  3685 V CAE     : clear(AutoRotationRunner.java:182)
07-06 08:46:14.936  3524  3685 V CAE     : enable(AutoRotationRunner.java:158)
07-06 08:46:14.936  3524  5010 V AlarmManager:  remove PendingIntent] PendingIntent{a3700fb: PendingIntentRecord{e753ecc com.google.android.gms broadcastIntent}}
,07-06 08:46:14.936  3524  3524 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
07-06 08:46:14.936  3524  3524 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3524) 
,07-06 08:46:14.936  3524  3524 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
07-06 08:46:14.941  3524  3524 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
07-06 08:46:14.941  3524  3804 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-06 08:46:14.941  3524  3524 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-06 08:46:14.941  3524  3524 D UsbDeviceManager: Keyguard Lock/Unlock
07-06 08:46:14.941  3524  3524 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
07-06 08:46:14.941  3524  3524 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
07-06 08:46:14.941  3524  3804 D SensorManager: unregisterListener ::   
07-06 08:46:14.941  3524  3804 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-06 08:46:14.941  3524  3685 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
07-06 08:46:14.941  3524  3804 V AlarmManager:  remove PendingIntent] PendingIntent{d65f7fa: PendingIntentRecord{b54f1ab android broadcastIntent}}
07-06 08:46:14.941  3524  3685 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
07-06 08:46:14.941  2951  2951 D Sensorhubs: sendContextData: -79, 7, 0, 0,
07-06 08:46:14.941  3524  3524 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0200
07-06 08:46:14.941  3524  3524 D UsbDeviceManager: updateUsbNotification : cancel id = 17040367, title = Connected as a media device
,07-06 08:46:14.951  3524  3524 D UsbDeviceManager: updateUsbNotification : isKeyguardLocked = false, isKeyguardSecure = false, mBootCompleted = true
,07-06 08:46:14.951  3524  3685 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
07-06 08:46:14.951  3524  3685 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:14.951  3524  5054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{174728a u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99e303b 5793:com.google.android.gms.persistent/u0a14}
,07-06 08:46:14.956  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-06 08:46:14.956  4512  4512 I PERF    : received broadcast android.intent.action.TIME_TICK
07-06 08:46:14.956  4512  4512 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:46:14.961  3524  3524 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
07-06 08:46:14.961  3524  3524 D UsbDeviceManager: updateUsbNotification : notify id = 17040367, title = Connected as a media device
,07-06 08:46:14.961  3524  3524 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
07-06 08:46:14.961  3524  3524 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
07-06 08:46:14.961  3524  3524 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
07-06 08:46:14.961  3524  3524 D PalmMotion: [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
07-06 08:46:14.961  3524  3524 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-06 08:46:14.961  3524  3524 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-06 08:46:14.966  3524  3685 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:14.966  3524  3685 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-06 08:46:14.966  3524  3685 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-06 08:46:14.966  3524  3685 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@dd5ea6d, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-06 08:46:14.966  3524  3685 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@f2f2d56, Service : AUTO_ROTATION(1)
07-06 08:46:14.971  3524  3685 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-06 08:46:14.971  3524  3685 D SContextService: 	.registerCallback : 1, client=
07-06 08:46:14.971  3524  3685 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-06 08:46:14.971  3524  3685 D SContextService: ===== SContext Service List =====
07-06 08:46:14.971  3524  3685 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@d6ab1d7, Service : Auto Rotation
07-06 08:46:14.971  3524  3788 I DisplayPowerController: Unblocked screen on after 141 ms
07-06 08:46:14.971  3524  3685 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8b39bf0, service=Auto Rotation
07-06 08:46:14.971  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:14.971  3524  3685 D WindowManager: finishScreenTurningOn: mAwake=true, mScreenOnEarly=true, mScreenOnFully=false, mKeyguardDrawComplete=true, mWindowManagerDrawComplete=true
07-06 08:46:14.971  3524  3788 D ColorFade: prepare: mode=2
07-06 08:46:14.971  3524  3685 I WindowManager: Finished screen turning on...
07-06 08:46:14.971  3524  3788 D ColorFade: ColorFade is already prepared
07-06 08:46:14.971  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:14.971  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:14.971  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:14.971  4512  4512 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:46:14.971  4512  4512 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 08:46:14.976  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:14.976  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:14.981  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:46:14.981  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:14.981  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:46:14.981  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:46:14.981  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:46:14.991  3524  4416 D InputReader: Input event(10): value=0 when=1575615104000
,07-06 08:46:14.991  3524  4416 D InputReader: !@notifyKey(172), action=1
07-06 08:46:14.991  3524  4416 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
,07-06 08:46:14.991  3524  4416 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-06 08:46:14.996  3524  4415 D VoIPInterfaceManager: isVoIPRinging()...,
07-06 08:46:14.996  3524  4415 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-06 08:46:14.996  3524  4415 I WindowManager: Ignoring HOME; down is not pressed.
07-06 08:46:14.996  3524  4415 D VoIPInterfaceManager: Not exist call session
,07-06 08:46:15.006  3524  3524 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-06 08:46:15.006  3524  3524 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-06 08:46:15.006  3524  3524 D UcmService: notifyChangeToPlugin event 16
07-06 08:46:15.006  3524  3524 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-06 08:46:15.006  3524  3524 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-06 08:46:15.006  3524  3524 D UcmService: notifying to unmanaged plugin
07-06 08:46:15.006  5148  5164 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-06 08:46:15.011  3524  3524 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-06 08:46:15.011  3524  3524 D UcmService: agentService status-0
07-06 08:46:15.011  3524  3524 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-06 08:46:15.011  3524  3524 D UcmService: notifying to unmanaged plugin
07-06 08:46:15.011  5158  5170 D BootAgentService: notifyChange eventId-16
07-06 08:46:15.011  3524  3524 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-06 08:46:15.011  3524  3524 D UcmService: agentService status--1
07-06 08:46:15.011  3524  3524 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-06 08:46:15.011  3524  3524 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3524) 
07-06 08:46:15.011  3524  3524 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,07-06 08:46:15.011  3524  3524 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
07-06 08:46:15.011  3524  3804 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-06 08:46:15.011  3524  3524 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-06 08:46:15.011  3524  3524 D EdgeLight: Turning off
,07-06 08:46:15.011  3524  3524 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 3524) 
07-06 08:46:15.011  3524  3804 D SensorManager: unregisterListener ::   
07-06 08:46:15.011  3524  3804 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-06 08:46:15.011  3524  3804 V AlarmManager:  remove PendingIntent] PendingIntent{d65f7fa: PendingIntentRecord{b54f1ab android broadcastIntent}}
07-06 08:46:15.011  3524  3524 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
07-06 08:46:15.011  3524  3524 D BatteryService: turn off LED
,07-06 08:46:15.016  3524  3804 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-06 08:46:15.016  3524  3804 D lights  : led_pattern : 0 +
,07-06 08:46:15.016  3524  3804 D lights  : led_pattern : 0 -
07-06 08:46:15.016  3524  3804 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-06 08:46:15.021  3524  3524 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
,07-06 08:46:15.021  3524  3524 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
,07-06 08:46:15.041  3524  3524 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
07-06 08:46:15.041  3524  3524 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
,07-06 08:46:15.041  3524  3524 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
07-06 08:46:15.041  3524  3524 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
07-06 08:46:15.041  2951  3092 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-06 08:46:15.051  3524  3524 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-06 08:46:15.066  3524  3524 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
,07-06 08:46:15.066  3524  4408 E MotionRecognitionService:  handler : SCREEN_ON end
,07-06 08:46:15.071  3524  3524 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-06 08:46:15.071  3524  3524 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-06 08:46:15.071  3524  3524 D UcmService: notifyChangeToPlugin event 16
07-06 08:46:15.071  3524  3524 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-06 08:46:15.071  3524  3524 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-06 08:46:15.071  3524  3524 D UcmService: notifying to unmanaged plugin
07-06 08:46:15.071  5148  5163 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-06 08:46:15.071  3524  3524 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-06 08:46:15.071  3524  3524 D UcmService: agentService status-0
07-06 08:46:15.071  3524  3524 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-06 08:46:15.071  3524  3524 D UcmService: notifying to unmanaged plugin
07-06 08:46:15.071  5158  5171 D BootAgentService: notifyChange eventId-16
07-06 08:46:15.071  3524  3524 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-06 08:46:15.071  3524  3524 D UcmService: agentService status--1
07-06 08:46:15.071  3524  3524 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-06 08:46:15.076  3524  4972 E Watchdog: !@Sync 52 [07-06 08:46:15.081]
,07-06 08:46:15.076  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
07-06 08:46:15.076  3524  3811 D SurfaceControl: Excessive delay in setPowerMode(): 208ms
07-06 08:46:15.076  3524  3811 D PowerManagerUtil: Excessive delay in !@display_state: ON: 209ms
07-06 08:46:15.076  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:15.076  3524  3788 D ColorFade: prepare: mode=2
07-06 08:46:15.076  3524  3788 D ColorFade: ColorFade is already prepared
07-06 08:46:15.076  3524  3788 D DisplayPowerController: animateScreenStateChange is returned because lux is not yet valid!
,07-06 08:46:15.076  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:15.076  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:15.081  3524 12285 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 1
07-06 08:46:15.076  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-06 08:46:15.081  3524 12285 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 1
07-06 08:46:15.081  3524 12286 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
07-06 08:46:15.081  3524 12287 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 1
,07-06 08:46:15.086  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
,07-06 08:46:15.086  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:15.086  3524  3788 D ColorFade: prepare: mode=2
07-06 08:46:15.086  3524  3788 D ColorFade: ColorFade is already prepared
07-06 08:46:15.086  3524  3788 D DisplayPowerController: animateScreenStateChange is returned because lux is not yet valid!
07-06 08:46:15.086  3524  3524 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-06 08:46:15.086  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:15.086  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:15.086  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-C:4
,07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:15.096  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-06 08:46:15.096  4512  4512 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-C:4
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-06 08:46:15.101  4512  4512 D PhoneStatusBar: animateCollapse(): mExpandedVisible=false flags=0
07-06 08:46:15.101  4512  4512 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
07-06 08:46:15.101  4512  4512 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
07-06 08:46:15.101  4512  4512 D CoverUI : applyHeight h = 96, oc = false, ex = false, fa = false, ac = false, sc = false
07-06 08:46:15.101  4512  4512 V NotificationStackScrollLayout: start: -268.0stackHeight: 268.0
07-06 08:46:15.101  4512  4512 V NotificationStackScrollLayout: start: -268.0stackHeight: 268.0
07-06 08:46:15.101  4512  4512 V NotificationStackScrollLayout: start: -268.0stackHeight: 268.0
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-C:4
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:15.101  3524  4447 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:15.101  3524  4447 D WifiNative-wlan0: callSECApiBoolean - ID [11]
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:15.101  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-V:8
,07-06 08:46:15.101  4896  4896 I wpa_supplicant: STOP_PERIODIC_SCAN command
07-06 08:46:15.101  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:15.101  3524  3788 D ColorFade: prepare: mode=2
07-06 08:46:15.101  3524  3788 D ColorFade: ColorFade is already prepared
07-06 08:46:15.101  3524  3788 D DisplayPowerController: animateScreenStateChange is returned because lux is not yet valid!
07-06 08:46:15.101  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:15.101  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:15.101  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:15.106  3524  3524 D NotificationService: ACTION_SCREEN_ON
,07-06 08:46:15.106  3524  3524 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3524) 
07-06 08:46:15.106  3524  3524 D EdgeLight: Turning off
07-06 08:46:15.106  3524  3524 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
07-06 08:46:15.106  3524  3804 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-06 08:46:15.106  3524  3804 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-06 08:46:15.106  3524  4447 E WifiNative-wlan0: do suspend false
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-C:4
,07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-06 08:46:15.111  4512  4512 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-06 08:46:15.111  4512  4512 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-06 08:46:15.111  2922  4461 I AudioHardwareTinyALSA: setParameters(screen_state=on)
,07-06 08:46:15.116  3524  4447 D WifiStateMachine: analyze kernel wifi wakelock 
,07-06 08:46:15.116  3524  4447 D WifiStateMachine: file not found /proc/wakelocks
07-06 08:46:15.121  3524  3524 V AlarmManager:  remove PendingIntent] PendingIntent{8c2bc31: PendingIntentRecord{f273f16 android broadcastIntent}}
,07-06 08:46:15.121  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:15.121  3524  3788 D ColorFade: prepare: mode=2
07-06 08:46:15.121  3524  3788 D ColorFade: ColorFade is already prepared
07-06 08:46:15.121  3524  3788 D DisplayPowerController: animateScreenStateChange is returned because lux is not yet valid!
07-06 08:46:15.121  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:15.121  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:15.121  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-06 08:46:15.126  4512  4512 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,07-06 08:46:15.131  4512  4512 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,07-06 08:46:15.131  3524  4379 I Sensors : #>LightSensor r=74 g=67 b=55 c=187 atime=238 again=64 lux=34.000000
,07-06 08:46:15.131  3524  4492 D AutomaticBrightnessController: [DAB] onSensorChanged : 1st lux : 34.0
07-06 08:46:15.131  3524  4492 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 72(72.0)    0.0 < 34.0 < 92.0 (0.6)
07-06 08:46:15.131  3524  4492 D AutomaticBrightnessController: mCallbacks.updateBrightness()
07-06 08:46:15.131  3524  4492 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
07-06 08:46:15.131  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:15.131  3524  3788 D ColorFade: prepare: mode=2
07-06 08:46:15.131  3524  3788 D ColorFade: ColorFade is already prepared
07-06 08:46:15.131  3524  3788 D DisplayPowerState: !@ [0] ColorFade exit
07-06 08:46:15.131  3524  3788 D PowerManagerService: [input device light] onColorFadeExit(true)
07-06 08:46:15.131  3524  3788 D DisplayPowerController: ColorFade: onAnimationStart
07-06 08:46:15.131  3524  4492 D PowerManagerUtil: fileWriteInt to /sys/class/lcd/panel/lux, 34
07-06 08:46:15.131  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:15.131  3524  3788 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
,07-06 08:46:15.131  3524  3788 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
07-06 08:46:15.136  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 72 -> 72
07-06 08:46:15.136  3524  3788 D DisplayPowerController: Animating brightness: target=72, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:15.136  3524  3788 D DisplayPowerState: Requesting new screen state: [0] state=ON, backlight (By colorFade)=72
07-06 08:46:15.136  3524  4493 D lights  : lcd : 72 +
07-06 08:46:15.136  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:15.136  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 72 -> 72
07-06 08:46:15.136  3524  3788 D DisplayPowerController: Animating brightness: target=72, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:15.136  3524  4493 D DisplayPowerState: Updating screen state [0]: state=ON, backlight (by ColorFade)=72
,07-06 08:46:15.141  3524  4447 E WifiStateMachine: analyzeKernelWifiWakelocks done - last length : 1
,07-06 08:46:15.141  3524  4493 D lights  : lcd : 72 -
,07-06 08:46:15.146  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:15.146  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 72 -> 72
07-06 08:46:15.146  3524  3524 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-06 08:46:15.146  3524  3788 D DisplayPowerController: Animating brightness: target=72, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:15.146  3524  3524 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
07-06 08:46:15.146  3524  3524 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
,07-06 08:46:15.146  4512  4512 D PanelView: kidsfalse mQsExpansionEnabled:true
07-06 08:46:15.146  3524  4448 V AlarmManager:  remove PendingIntent] PendingIntent{9f2c097: PendingIntentRecord{ed43284 android broadcastIntent}}
07-06 08:46:15.146  3524  3524 V CAE     : start(ContextProvider.java:128)
07-06 08:46:15.146  3524  3524 V CAE     : clear(ActivityTrackerRunner.java:108)
07-06 08:46:15.146  3524  3524 V CAE     : enable(ActivityTrackerRunner.java:84)
,07-06 08:46:15.146  3524  3524 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 46, 15,
07-06 08:46:15.146  3524  3524 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 46, 15
07-06 08:46:15.151  2951  2951 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 46, 15
,07-06 08:46:15.151  4512  4512 D PanelView: kidsfalse mQsExpansionEnabled:true
07-06 08:46:15.151  3524  3524 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
07-06 08:46:15.151  4512  4512 D PanelView: screenCapture for lockscreen preview
,07-06 08:46:15.151  3524  3524 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:15.156  4512  4512 D Recents : handleProxyCall type=3
,07-06 08:46:15.166  3524  3524 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:15.166  3524  3524 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-06 08:46:15.166  3524  5858 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{174728a u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99e303b 5793:com.google.android.gms.persistent/u0a14}
,07-06 08:46:15.166  3524  3524 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-06 08:46:15.166  3524  3524 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@dd5ea6d, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-06 08:46:15.166  3524  3524 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@dd5ea6d, Service : ACTIVITY_TRACKER(1)
07-06 08:46:15.166  3524  3524 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@f2f2d56, Service : AUTO_ROTATION(1)
07-06 08:46:15.171  3524  3524 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-06 08:46:15.171  3524  3524 D SContextService: 	.registerCallback : 2, client=
07-06 08:46:15.171  3524  3524 D SContextService: ===== SContext Service List =====
07-06 08:46:15.171  3524  3524 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@d6ab1d7, Service : Auto Rotation
07-06 08:46:15.171  3524  3524 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@86404cf, Service : Activity Tracker
07-06 08:46:15.171  3524  3524 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@7ee912e, service=Activity Tracker
07-06 08:46:15.171  3524  3524 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
07-06 08:46:15.171  3524  3524 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,07-06 08:46:15.171  3524  3524 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
07-06 08:46:15.171  3524  3524 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-06 08:46:15.171  3524  3524 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
07-06 08:46:15.171  2951  3092 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-06 08:46:15.171  3524  3524 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,07-06 08:46:15.171  3524  3524 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:15.171  4694  4694 D Recents : handleProxyCall type=3
,07-06 08:46:15.181  3524  3524 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
,07-06 08:46:15.181  3524  3524 D SContextService: requestToUpdate() : service = Activity Tracker
07-06 08:46:15.181  3524  3524 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@7ee912e, service=Activity Tracker
,07-06 08:46:15.191  2951  3091 D Sensorhubs: readContextData: 1, 1, 26, 1, 1, 115, -16, -118, 0, 0
,07-06 08:46:15.196  3524  4405 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 1, 115, -16, -118, 0, 0
,07-06 08:46:15.196  3524  4404 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-06 08:46:15.196  3524  4404 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
,07-06 08:46:15.196  3524  4404 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 1, 115, -16, -118, 0, 0,
07-06 08:46:15.196  3524  4404 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-06 08:46:15.196  3524  4404 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467787575202]
,07-06 08:46:15.196  3524  4407 D SContextService: updateSContext() : event = Activity Tracker
,07-06 08:46:15.201  3524  3524 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-06 08:46:15.201  3524  3524 D WifiStateMachine: setWifiScanMove bMove = 0
07-06 08:46:15.201  3524  3524 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-06 08:46:15.201  3524  3524 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
07-06 08:46:15.201  3524  3524 D WifiService: setWifiScanWithSensor bMove = 0
,07-06 08:46:15.201  3524  3765 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-06 08:46:15.201  3524  4447 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
07-06 08:46:15.201  3524  3765 D IpRemoteDisplayController: Bridge Server is not available
07-06 08:46:15.201  4896  4896 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,07-06 08:46:15.226  3524  4445 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
07-06 08:46:15.226  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,07-06 08:46:15.226  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
,07-06 08:46:15.226  5793  5793 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-06 08:46:15.231  3524 12287 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-06 08:46:15.251  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c3/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:15.251  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:15.256  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:15.256  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:15.256  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:15.256  2951  3091 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 1, 115, -16, -56, 0, 0
,07-06 08:46:15.256  3524  4405 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 1, 115, -16, -56, 0, 0
07-06 08:46:15.256  3524  4404 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_WAKEUP
07-06 08:46:15.256  3524  4404 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
,07-06 08:46:15.256  3524  4404 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 1, 115, -16, -56, 0, 0,
07-06 08:46:15.256  3524  4404 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-06 08:46:15.256  3524  4404 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467787575262]
07-06 08:46:15.256  3524  4407 D SContextService: updateSContext() : event = Activity Tracker
07-06 08:46:15.256  3524  3524 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-06 08:46:15.256  3524  3524 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,07-06 08:46:15.256  3524  3549 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{174728a u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99e303b 5793:com.google.android.gms.persistent/u0a14}
,07-06 08:46:15.271  3524 12286 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
07-06 08:46:15.271  5793  5793 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver bqHint=4 }.
,07-06 08:46:15.271  3524  3811 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-06 08:46:15.271  3524  3811 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-06 08:46:15.271  3524  3811 D PowerManagerUtil: Excessive delay in nativeSetInteractive(true): 194ms
07-06 08:46:15.271  3524  3811 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 194ms
07-06 08:46:15.271  3524  3811 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 404ms
07-06 08:46:15.271  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-06 08:46:15.271  3524  4491 D lights  : button : 1 +
,07-06 08:46:15.271  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:15.271  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 72 -> 72
07-06 08:46:15.271  3524  3788 D DisplayPowerController: Animating brightness: target=72, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:15.286  3524  5012 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{fc90c1d u-1 android.intent.action.TIME_TICK qIdx=2}, state= (IDLE) to ReceiverList{86d778d 4512 com.android.systemui/10060/u0 remote:74b4024}: filter unregistered
,07-06 08:46:15.286 11392 11392 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ac51330 time:1575911
,07-06 08:46:15.306  3524  4491 D lights  : button : 1 -
,07-06 08:46:15.316  3524  3788 D DisplayPowerController: ColorFade: onAnimationEnd
,07-06 08:46:15.316  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:15.316  3524  4379 I Sensors : #>LightSensor r=75 g=68 b=56 c=190 atime=238 again=64 lux=34.000000
07-06 08:46:15.316  2905  3011 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
,07-06 08:46:15.316  2905  3011 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
07-06 08:46:15.316  3524  3788 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-06 08:46:15.316  2905  4414 I SurfaceFlinger: id=15 Removed DolorFade (8/8)
07-06 08:46:15.321  2905 10182 I SurfaceFlinger: id=15 Removed DolorFade (-2/8)
,07-06 08:46:15.321  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:15.321  3524  3788 V KeyguardServiceDelegate: onScreenTurnedOn()
07-06 08:46:15.321  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 72 -> 72
07-06 08:46:15.321  4512  6982 D KeyguardViewMediator: notifyScreenTurnedOn
07-06 08:46:15.321  3524  3788 D DisplayPowerController: Animating brightness: target=72, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:15.321  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() start
07-06 08:46:15.321  3524  3788 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
07-06 08:46:15.321  4512  4512 D KeyguardViewMediator: handleNotifyScreenTurnedOn
07-06 08:46:15.321  3524  3788 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
07-06 08:46:15.321  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() end
07-06 08:46:15.321  3524  3788 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-06 08:46:15.321  3524  4490 I WindowManager: Finished waking up...
07-06 08:46:15.321  3524  3788 D PowerManagerService: mDisplayReady: true
,07-06 08:46:15.331  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbe971474
,07-06 08:46:15.366  5793  5793 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:46:15.371  5793  5793 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-06 08:46:15.416  5793 12290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-06 08:46:15.416  5793 12290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-06 08:46:15.416  2915  4370 D EnterpriseController: netId is 0
07-06 08:46:15.416  2915  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-06 08:46:15.456  5793 12290 I qtaguid : Tagging socket 36 with tag 3000040100000000{805307393,0} uid 10014, pid: 5793, getuid(): 10014
,07-06 08:46:15.486  5793 12290 I qtaguid : Tagging socket 46 with tag 3000040100000000{805307393,0} uid 10014, pid: 5793, getuid(): 10014
,07-06 08:46:15.501  3524  4379 I Sensors : #>LightSensor r=76 g=69 b=58 c=195 atime=238 again=64 lux=35.000000
,07-06 08:46:15.566  2951  3091 D Sensorhubs: readContextData: 1, 1, 26, 1, 1, 115, -15, -2, 1, 2
,07-06 08:46:15.566  3524  4405 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 1, 115, -15, -2, 1, 2
07-06 08:46:15.566  3524  4404 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-06 08:46:15.566  3524  4404 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
07-06 08:46:15.566  3524  4404 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 1, 115, -15, -2, 1, 2,
07-06 08:46:15.566  3524  4404 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-06 08:46:15.566  3524  4404 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[1], TimeStamp=[1467787575572]
07-06 08:46:15.566  3524  4407 D SContextService: updateSContext() : event = Activity Tracker
07-06 08:46:15.566  3524  3524 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-06 08:46:15.566  3524  3524 D WifiService: ACTIVITY_STATUS_STATIONARY 
,07-06 08:46:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:46:15.661  5793 12290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-06 08:46:15.661  5793 12290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-06 08:46:15.661  2915  4370 D EnterpriseController: netId is 0
07-06 08:46:15.661  2915  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-06 08:46:15.691  5793 12290 I qtaguid : Tagging socket 48 with tag 3000120300000000{805310979,0} uid -1, pid: 5793, getuid(): 10014
,07-06 08:46:15.721  5793 12290 I qtaguid : Tagging socket 51 with tag 3000120300000000{805310979,0} uid -1, pid: 5793, getuid(): 10014
,07-06 08:46:15.821  3524  3524 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1200000  uid : 1000  pid : 3524  tag : WAKEUP_BOOSTER@31
,07-06 08:46:15.896  5793 12290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-06 08:46:15.896  5793 12290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-06 08:46:15.896  5793 12290 I qtaguid : Tagging socket 48 with tag 3000120300000000{805310979,0} uid -1, pid: 5793, getuid(): 10014
,07-06 08:46:15.976  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1098db u0 com.google.android.gms.phenotype.UPDATE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcc6713 7701:com.google.android.gms/u0a14}
,07-06 08:46:15.991  3524  5141 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1098db u0 com.google.android.gms.phenotype.UPDATE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99e303b 5793:com.google.android.gms.persistent/u0a14}
,07-06 08:46:16.016  3524  5815 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1098db u0 com.google.android.gms.phenotype.UPDATE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcc6713 7701:com.google.android.gms/u0a14}
,07-06 08:46:16.021  3524  3550 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.phenotype.service.PhenotypeCommitChimeraService (has extras) } U=0: not found
,07-06 08:46:16.051  5793 12290 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-06 08:46:16.061  7701  8941 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.ocr
,07-06 08:46:16.066  5793 12298 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-06 08:46:16.066  5793  6142 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
,07-06 08:46:16.076  5793 12290 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
07-06 08:46:16.076  5793 12298 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-06 08:46:16.076  5793  6142 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
,07-06 08:46:16.086  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6a368d u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99e303b 5793:com.google.android.gms.persistent/u0a14}
,07-06 08:46:16.096  5793 12298 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-06 08:46:16.096  5793  6142 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
07-06 08:46:16.096  5793  6142 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.tapandpay
,07-06 08:46:16.101  3524  5518 V AlarmManager:  remove PendingIntent] PendingIntent{ae66042: PendingIntentRecord{e753ecc com.google.android.gms broadcastIntent}}
,07-06 08:46:16.186  3524  3661 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-06 08:46:16.196  3524  3524 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,07-06 08:46:16.196  3524  3853 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
07-06 08:46:16.196  3524  5134 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
07-06 08:46:16.196  5102  5102 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-06 08:46:16.196  5102 12302 D NfcService: call the applyRouting
,07-06 08:46:16.201  4512  4512 D StatusBar.NetworkController: onDataActivity: direction=0
,07-06 08:46:16.206  4512  4512 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-06 08:46:16.211  3524  3524 V AlarmManager:  remove PendingIntent] PendingIntent{a774853: PendingIntentRecord{a0f3008 android broadcastIntent}}
07-06 08:46:16.211  3524  3524 V AlarmManager:  remove PendingIntent] PendingIntent{54590: PendingIntentRecord{332f079 android broadcastIntent}}
,07-06 08:46:16.211  5781  5781 D BtGatt.GattService: LCD turned on
07-06 08:46:16.211  5781  5984 D BtGatt.ScanManager: handleLcdOnIntent
07-06 08:46:16.211  5781  5984 D BtGatt.ScanManager: handleLcdOnIntent
07-06 08:46:16.211  5781  5984 D BtGatt.ScanManager: ClientIf = 0
,07-06 08:46:16.221  5709  5709 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:113 [0:0] getInstance
,07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:113 [0:0] getInstance
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:283 [0:0] direct update clock
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:152 [0:0] make widget 4x1 view!!! 
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:154 [0:0] make widget 4x2 view!!! 
,07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:1492 [0:0] mc sy = 2
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:179 [0:0] get widget 4x2 view!!! wid = 2
,07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> U:884 [0:0] locale = en
07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> U:894 [0:0] Locale format : MMM d, y
,07-06 08:46:16.226  6083  6083 D accuweather: [KK AccuPhone]>>> U:915 [0:0] locale = E, MMMM d
07-06 08:46:16.226  6083  6083 E accuweather: [KK AccuPhone]>>> UIM:1547 [0:0] bTM 08 46
,07-06 08:46:16.241  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 251 (W:28), LCD = 72
,07-06 08:46:16.251  3524  6867 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:46:16.266  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0caa45 u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c5c9bec 4629:com.sec.android.daemonapp/u0a196}
,07-06 08:46:16.271  4629  4629 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,07-06 08:46:16.271  4629  4629 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
07-06 08:46:16.271  4629  4629 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:16.271  4629  4629 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:16.276  4629  4629 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:16.276  4629  4629 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
07-06 08:46:16.276  4629  4629 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:16.276  4629  4629 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-06 08:46:16.276  4629  4629 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-06 08:46:16.276  4629  4629 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-06 08:46:16.276  4629  4629 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
07-06 08:46:16.276  4629  4629 D daemonapp: [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-06 08:46:16.276  4629  4629 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:16.281  4629  4629 D daemonapp: [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
07-06 08:46:16.281  4629  4629 D daemonapp: [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1467807600000
,07-06 08:46:16.281  4629  4629 D daemonapp: [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1467787576286
07-06 08:46:16.281  4629  4629 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-06 08:46:16.281  4629  4629 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,07-06 08:46:16.286  4629  4629 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
07-06 08:46:16.286  4629  4629 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,07-06 08:46:16.286  4629  4629 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
07-06 08:46:16.286  7448  7448 D SensorManager: unregisterListener ::   
07-06 08:46:16.286  4629  4629 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-06 08:46:16.291  4629  4629 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,07-06 08:46:16.306  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c3/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-06 08:46:16.306  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:16.306  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:16.306  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:16.306  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:16.316  3524  4490 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-06 08:46:16.361  3524 12304 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-06 08:46:16.361  3524 12304 D BluetoothAdapter: STATE_ON
,07-06 08:46:16.361  3524  5858 V AlarmManager:  remove PendingIntent] PendingIntent{b256ecb: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:46:16.406  3524 12304 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-06 08:46:16.446  3524 12304 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-06 08:46:16.451  3524 12304 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-06 08:46:16.631  3524 12304 I BatteryStatsDumper: Writing to database completed
,07-06 08:46:16.771  3524  4491 D lights  : button : 0 +
,07-06 08:46:16.811  3524  4491 D lights  : button : 0 -
,07-06 08:46:17.211  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:17.211  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:17.221  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:17.221  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:17.226  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:17.861  3524  3550 V AlarmManager:  remove PendingIntent] PendingIntent{2b436a8: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:46:18.211  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:18.211  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:18.221  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:18.221  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:18.226  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:18.871  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:46:18.871  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:46:20.226  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:20.226  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:20.231  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:20.231  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:20.236  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.226  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:21.226  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.231  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.231  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:21.236  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:26.246  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:26.246  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:26.256  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
07-06 08:46:26.256  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:26.256  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:26.266  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 251 (W:28), LCD = 72
,07-06 08:46:27.256  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:27.256  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:27.261  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:27.261  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:27.261  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.266  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:29.266  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.271  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.271  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:29.271  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:30.271  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:30.271  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:30.276  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:30.281  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:30.281  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.281  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:32.281  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.291  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.291  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:32.296  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.286  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:33.291  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.296  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.296  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:33.296  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.301  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:35.301  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.306  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.311  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:35.311  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:36.286  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 251 (W:28), LCD = 72
,07-06 08:46:36.306  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:36.306  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:36.311  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:36.311  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:36.311  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.316  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:37.316  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.321  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:37.321  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:37.321  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:38.996  3524  3788 D PowerManagerService: [s] UserActivityState : 1 -> 2
07-06 08:46:38.996  3524  3788 D PowerManagerService: mDisplayReady: false
07-06 08:46:38.996  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:38.996  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:38.996  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:38.996  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:38.996  3524  3788 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-06 08:46:38.996  3524  3788 D PowerManagerService: mDisplayReady: true
,07-06 08:46:39.001  3524  4493 D lights  : lcd : 69 +
,07-06 08:46:39.006  3524  4493 D lights  : lcd : 69 -
,07-06 08:46:39.011  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:39.011  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:39.011  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:39.011  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.016  3524  4493 D lights  : lcd : 60 +
,07-06 08:46:39.021  3524  4493 D lights  : lcd : 60 -
,07-06 08:46:39.021  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:39.021  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:39.021  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-06 08:46:39.021  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.036  3524  4493 D lights  : lcd : 52 +
,07-06 08:46:39.036  3524  4493 D lights  : lcd : 52 -,
07-06 08:46:39.041  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:39.041  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:39.041  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:39.041  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.051  3524  4493 D lights  : lcd : 43 +
,07-06 08:46:39.056  3524  4493 D lights  : lcd : 43 -
,07-06 08:46:39.056  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:39.056  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:39.056  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:39.056  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.066  3524  4493 D lights  : lcd : 35 +
,07-06 08:46:39.071  3524  4493 D lights  : lcd : 35 -
,07-06 08:46:39.071  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:39.071  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:39.071  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-06 08:46:39.071  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.086  3524  4493 D lights  : lcd : 27 +
,07-06 08:46:39.091  3524  4493 D lights  : lcd : 27 -
,07-06 08:46:39.091  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:39.091  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:39.091  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-06 08:46:39.091  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.101  3524  4493 D lights  : lcd : 18 +
,07-06 08:46:39.106  3524  4493 D lights  : lcd : 18 -
,07-06 08:46:39.106  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:39.106  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-06 08:46:39.106  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:39.106  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.116  3524  4493 D lights  : lcd : 15 +
,07-06 08:46:39.116  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-06 08:46:39.116  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:39.116  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:39.116  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.121  3524  4493 D lights  : lcd : 15 -
07-06 08:46:39.121  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-06 08:46:39.121  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:39.121  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-06 08:46:39.121  3524  3788 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-06 08:46:39.326  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:39.326  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.331  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.331  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.336  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:39.931  3524  5821 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 08:46:39.931  3524  5821 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:46:39.931  3524  5821 D BatteryService: online:4, current avg:-10, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:46:39.931  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:46:39.931  3524  3524 I MotionRecognitionService: Plugged
07-06 08:46:39.931  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:46:39.936  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:46:39.936  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:46:39.936  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 08:46:39.936  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:46:39.941  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:46:39.946  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-06 08:46:39.946  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:46:39.961  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:46:39.961  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:46:39.961  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:46:41.336  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:41.336  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:41.341  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:41.341  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:41.346  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.341  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:42.346  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.346  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.351  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:42.351  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.356  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:44.356  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.361  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.361  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:44.366  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:45.076  3524  4972 E Watchdog: !@Sync 53 [07-06 08:46:45.083]
,07-06 08:46:45.136  3524  3788 D PowerManagerService: [s] UserActivityState : 2 -> 4
,07-06 08:46:45.136  3524  3788 D InputManager-JNI: setInteractive(false)
,07-06 08:46:45.136  3524  3788 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
07-06 08:46:45.136  3524  4490 I WindowManager: Started going to sleep... (why=3)
07-06 08:46:45.136  3524  3788 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-06 08:46:45.136  4512  4545 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() start
07-06 08:46:45.136  3524  4490 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
,07-06 08:46:45.136  4512  4545 D KeyguardViewMediator: onStartedGoingToSleep(3)
07-06 08:46:45.136  3524  3788 D PowerManagerService: mDisplayReady: false
,07-06 08:46:45.136  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:45.141  2905  2905 I SurfaceFlinger: id=22 createSurf (1440x2560),2 flag=404, DolorFade
07-06 08:46:45.136  3524  3788 D ColorFade: prepare: mode=4
07-06 08:46:45.141 11392 11392 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-06 08:46:45.156  3524  3788 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 20ms
,07-06 08:46:45.161  3524  3788 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,07-06 08:46:45.161  4512  4545 D KeyguardViewMediator: timeout : 5000
,07-06 08:46:45.171  4512  4545 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,07-06 08:46:45.171  4512  4545 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() end
,07-06 08:46:45.196  3524  3788 D libEGL  : eglInitialize EGLDisplay = 0x9b03f0a4
,07-06 08:46:45.196  3524  3788 D libEGL  : eglTerminate EGLDisplay = 0x9b03f1c4
,07-06 08:46:45.201  3524  3788 D ColorFade: ColorFade is ready
,07-06 08:46:45.201  3524  3788 D DisplayPowerController: ColorFade: onAnimationStart
07-06 08:46:45.201  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-06 08:46:45.201  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 72 -> 72
,07-06 08:46:45.221  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c,
,07-06 08:46:45.231  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
,07-06 08:46:45.281  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c,
,07-06 08:46:45.356  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:45.356  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:45.361  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:45.361  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:45.361  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:45.496  3524  3788 D DisplayPowerState: !@ [0] ColorFade entry
07-06 08:46:45.496  3524  3788 D PowerManagerService: [input device light] onColorFadeExit(false)
07-06 08:46:45.496  3524  3788 D DisplayPowerController: ColorFade: onAnimationEnd
,07-06 08:46:45.511  3524  4493 D lights  : lcd : 0 +
07-06 08:46:45.511  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:45.511  3524  3788 I WindowManager: Screen turned off...
07-06 08:46:45.511  3524  3788 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,07-06 08:46:45.511  3524  4493 D lights  : lcd : 0 -
,07-06 08:46:45.571 11392 11392 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-06 08:46:45.571 11392 11392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-06 08:46:45.646  3524  3788 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@d6ab1d7, Service = Auto Rotation, used = 0
,07-06 08:46:45.646  3524  3788 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
07-06 08:46:45.651 11392 11392 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@607f156 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4f74411, 16908290=android.view.AbsSavedState$1@4f74411}, android:focusedViewId=100}]}]
07-06 08:46:45.651 11392 11392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-06 08:46:45.651 11392 11392 V ActivityThread: updateVisibility : ActivityRecord{cac1848 token=android.os.BinderProxy@ac51330 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-06 08:46:45.651 11392 11392 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-06 08:46:45.651 11392 11392 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-06 08:46:45.651  3524  3788 V CAE     : stop(ContextProvider.java:155)
,07-06 08:46:45.651  3524  3788 V CAE     : clear(AutoRotationRunner.java:182)
,07-06 08:46:45.651  3524  3788 V CAE     : disable(AutoRotationRunner.java:171)
,07-06 08:46:45.656  3524  3788 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
07-06 08:46:45.656  3524  3788 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
07-06 08:46:45.656  2951  2951 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-06 08:46:45.661  3524  3788 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true,
07-06 08:46:45.661  3524  3788 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:45.666  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
,07-06 08:46:45.676  3524  3788 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:45.676  3524  3788 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-06 08:46:45.676  3524  3788 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-06 08:46:45.681  3524  3788 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@dd5ea6d, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-06 08:46:45.681  3524  3788 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@dd5ea6d, Service : ACTIVITY_TRACKER(1)
07-06 08:46:45.681  3524  3788 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-06 08:46:45.681  3524  3788 D SContextService: 	.unregisterCallback : 2, client=
07-06 08:46:45.681  3524  3788 D SContextService: ===== SContext Service List =====
07-06 08:46:45.681  3524  3788 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@86404cf, Service : Activity Tracker
07-06 08:46:45.681  3524  3788 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@8b39bf0, service=Auto Rotation
07-06 08:46:45.681  3524  3788 V KeyguardServiceDelegate: onScreenTurnedOff()
07-06 08:46:45.681  4512  6611 D KeyguardViewMediator: notifyScreenTurnedOff
07-06 08:46:45.681  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() start
,07-06 08:46:45.681  4512  4512 D KeyguardViewMediator: handleNotifyScreenTurnedOff
07-06 08:46:45.681  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() end
,07-06 08:46:45.681  3524  3788 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
07-06 08:46:45.681  3524  4492 I Sensors : Light old sensor_state 513, new sensor_state : 1 en : 0
07-06 08:46:45.681  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
,07-06 08:46:45.681  3524 12316 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 0
,07-06 08:46:45.681  3524  3788 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
07-06 08:46:45.681  3524  4492 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
07-06 08:46:45.686  3524 12316 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 0
07-06 08:46:45.681  3524  3788 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
07-06 08:46:45.686  3524 12317 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
,07-06 08:46:45.681  3524  3788 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
07-06 08:46:45.686  3524 12318 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 0,
07-06 08:46:45.681  3524  3788 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-06 08:46:45.686  3524  4492 D SensorManager: unregisterListener ::   
07-06 08:46:45.681  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:45.686  3524  4492 I Sensors : Acc old sensor_state 1, new sensor_state : 0 en : 0
07-06 08:46:45.681  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:45.686  3524 12317 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,07-06 08:46:45.681  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:45.686  3524  4492 D SensorManager: unregisterListener ::   
07-06 08:46:45.681  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-06 08:46:45.691  3524 12318 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 0
07-06 08:46:45.681  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:45.681  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:45.691  3524  3811 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-06 08:46:45.686  3524  4492 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::unregisterListener done: 6ms
07-06 08:46:45.691  3524  3811 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-06 08:46:45.691  2905  2905 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a24000
07-06 08:46:45.691  3524  3811 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
,07-06 08:46:45.691  2905  2905 I hwcomposer: int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
07-06 08:46:45.691  3524  3765 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-06 08:46:45.741  3524  3536 I art     : Background partial concurrent mark sweep GC freed 85280(6MB) AllocSpace objects, 85(1912KB) LOS objects, 33% free, 30MB/46MB, paused 2.214ms total 196.592ms
,07-06 08:46:45.876  3524  3811 D SurfaceControl: Excessive delay in setPowerMode(): 185ms
07-06 08:46:45.876  3524  3811 I libsuspend: !@autosuspend_wakeup_count_enable
07-06 08:46:45.876  3524  3811 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 186ms
07-06 08:46:45.876  3524  3811 I libsuspend: !@autosuspend_wakeup_count_enable done
07-06 08:46:45.876  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:45.876  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-06 08:46:45.876  3524  4490 I WindowManager: Finished going to sleep... (why=3)
07-06 08:46:45.876  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-06 08:46:45.876  3524  4490 D PersonaManagerService: onfinishedGoingToSleep why = 3
07-06 08:46:45.876  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:45.876  4512  4536 D KeyguardViewMediator: onFinishedGoingToSleep(3)
07-06 08:46:45.876  3524  3788 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-06 08:46:45.876  3524  3853 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
07-06 08:46:45.876  3524  3788 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-06 08:46:45.876  4512  4536 D KeyguardViewMediator: onFinishedGoingToSleep: mPendingLock false
07-06 08:46:45.876  3524  3788 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,07-06 08:46:45.876  4512  4536 D KeyguardViewMediator: notifyFinishedGoingToSleep
07-06 08:46:45.876  3524  3788 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-06 08:46:45.876  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() start
07-06 08:46:45.876  3524  3811 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 192ms
,07-06 08:46:45.876  4512  4512 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
07-06 08:46:45.876  3524  3788 I PowerManagerService: [PWL] Off : 0s ago
07-06 08:46:45.876  4512  4512 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() end
07-06 08:46:45.876  3524  3788 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
07-06 08:46:45.876  4512  4512 D vol.SecVolumeDialog: dismissH : false
07-06 08:46:45.876  3524  3788 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
,07-06 08:46:45.876  3524  3788 I PowerManagerService: [PWL]     mDisplayReady : false
07-06 08:46:45.881  4512  4512 D SecKeyguardClockSingleView: onScreenTurnedOff
07-06 08:46:45.876  3524  3788 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-06 08:46:45.881  4512  4512 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOff() end
07-06 08:46:45.876  3524  3788 D PowerManagerService: mDisplayReady: true
,07-06 08:46:45.876  3524  3788 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
07-06 08:46:45.876  3524  3788 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
07-06 08:46:45.876  3524  3788 D PowerManagerService: handleSandman : startDream(true)
07-06 08:46:45.876  3524  3788 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-06 08:46:45.876  3524  3788 I PowerManagerService: Sleeping (uid 1000)...
,07-06 08:46:45.876  3524  3788 D PowerManagerService: [s] UserActivityState : 4 -> 0
07-06 08:46:45.876  3524  3788 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-06 08:46:45.911 10814 10980 W fb4a(:<default>):QeInternalImpl: The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,07-06 08:46:45.966  3524  3524 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3524) 
,07-06 08:46:45.966  3524  3524 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,07-06 08:46:45.971  3524  3524 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
07-06 08:46:45.971  3524  3524 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,07-06 08:46:46.006  3524  3524 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-06 08:46:46.006  3524  3524 D BatteryService: turn on LED for fully charged
,07-06 08:46:46.051  3524  3524 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-06 08:46:46.051  3524  3524 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
07-06 08:46:46.051  3524  3524 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
07-06 08:46:46.051  3524  3524 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-06 08:46:46.051  2951  3092 D Sensorhubs: sendContextData: -76, 13, -46, 0
,07-06 08:46:46.056  3524  3524 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 6, 46, 46,
,07-06 08:46:46.056  3524  3524 D SensorHubManager: SendSensorHubData: send data = -63, 14, 6, 46, 46
07-06 08:46:46.056  2951  2951 D Sensorhubs: sendContextData: -63, 14, 6, 46, 46
,07-06 08:46:46.066  3524  3524 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-06 08:46:46.071  3524  4408 D MotionRecognitionService: Screen off setAccIntStatus 
,07-06 08:46:46.076  3524  4408 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-06 08:46:46.101  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9a2dcfd u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbe0ea1 9065:com.android.settings/1000}
,07-06 08:46:46.106  3524  3524 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF,
,07-06 08:46:46.126  3524  3524 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-06 08:46:46.126  3524  3524 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-06 08:46:46.126  3524  3524 D UcmService: notifyChangeToPlugin event 16
07-06 08:46:46.126  3524  3524 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-06 08:46:46.126  3524  3524 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-06 08:46:46.126  3524  3524 D UcmService: notifying to unmanaged plugin
07-06 08:46:46.126  5148  5163 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-06 08:46:46.126  3524  3524 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-06 08:46:46.126  3524  3524 D UcmService: agentService status-0
,07-06 08:46:46.126  3524  3524 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-06 08:46:46.126  3524  3524 D UcmService: notifying to unmanaged plugin
07-06 08:46:46.126  5158  5171 D BootAgentService: notifyChange eventId-16
07-06 08:46:46.126  3524  3524 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-06 08:46:46.126  3524  3524 D UcmService: agentService status--1
07-06 08:46:46.126  3524  3524 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-06 08:46:46.146  3524  3524 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-06 08:46:46.156  3524  4447 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
,07-06 08:46:46.156  3524  4447 D WifiNative-wlan0: callSECApiVoid - ID [19]
07-06 08:46:46.156  4896  4896 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
,07-06 08:46:46.161  3524  3524 D NotificationService: ACTION_SCREEN_OFF
,07-06 08:46:46.161  3524  3524 D EdgeLight: Turning off
07-06 08:46:46.161  3524  3524 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3524) 
07-06 08:46:46.161  3524  3524 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,07-06 08:46:46.161  3524  4447 E WifiNative-wlan0: do suspend true
,07-06 08:46:46.166  2922  2922 I AudioHardwareTinyALSA: setParameters(screen_state=off)
,07-06 08:46:46.196  3524  3524 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,07-06 08:46:46.201  3524  3524 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-06 08:46:46.211  3524  3524 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
,07-06 08:46:46.211  3524  3524 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@86404cf, Service = Activity Tracker, used = 0
07-06 08:46:46.211  3524  3524 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
07-06 08:46:46.211  3524  3524 V CAE     : stop(ContextProvider.java:155)
,07-06 08:46:46.211  3524  3524 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-06 08:46:46.216  3524  3524 V CAE     : disable(ActivityTrackerRunner.java:96)
,07-06 08:46:46.216  3524  3524 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
07-06 08:46:46.216  3524  3524 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-06 08:46:46.216  2951  3092 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-06 08:46:46.221  3524  4379 I Sensors : #>LightSensor r=77 g=68 b=57 c=192 atime=238 again=64 lux=34.000000
,07-06 08:46:46.221  3524  3804 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
07-06 08:46:46.221  3524  3804 D LightsService: [SvcLED]  onSensorChanged::light value = 34
07-06 08:46:46.221  3524  3524 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
07-06 08:46:46.221  3524  3524 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-06 08:46:46.226  3524  3804 D SensorManager: unregisterListener ::   
,07-06 08:46:46.226  3524  3804 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
07-06 08:46:46.226  3524  3804 D lights  : led_pattern : 5 +
,07-06 08:46:46.231  3524  3804 D lights  : led_pattern : 5 -
,07-06 08:46:46.231  3524  3804 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-06 08:46:46.231  3524  3804 V AlarmManager:  remove PendingIntent] PendingIntent{d65f7fa: PendingIntentRecord{b54f1ab android broadcastIntent}}
,07-06 08:46:46.231  3524  3524 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-06 08:46:46.236  3524  3524 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-06 08:46:46.236  3524  3524 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,07-06 08:46:46.236  3524  3524 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@dd5ea6d, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-06 08:46:46.236  3524  3524 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-06 08:46:46.236  3524  3524 D SContextService: 	.unregisterCallback : 1, client=
07-06 08:46:46.236  3524  3524 D SContextService: ===== SContext Service List =====
07-06 08:46:46.236  3524  3524 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$12@7ee912e, service=Activity Tracker
,07-06 08:46:46.241  3524  3765 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,07-06 08:46:46.241  3524  3765 D IpRemoteDisplayController: Bridge Server is not available
,07-06 08:46:46.266  4512  4512 D vol.SecVolumeDialog: dismissH : false
,07-06 08:46:46.291  3524  3524 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,07-06 08:46:46.291  3524  4445 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
07-06 08:46:46.291  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-06 08:46:46.296  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 252 (W:28), CUR = -10, LCD = 0,
,07-06 08:46:46.651  4694  4694 D Recents : onTaskStackChanged
,07-06 08:46:46.861  3524  3661 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-06 08:46:46.866  5102 12320 D NfcService: call the applyRouting
,07-06 08:46:46.871  4512  4512 D StatusBar.NetworkController: onDataActivity: direction=0
,07-06 08:46:46.876  4512  4512 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-06 08:46:46.891  5781  5781 D BtGatt.GattService: LCD turned off
07-06 08:46:46.891  5781  5984 D BtGatt.ScanManager: handleLcdOffIntent
,07-06 08:46:46.891  5781  5984 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,07-06 08:46:46.906  6083  6083 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,07-06 08:46:46.906  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:113 [0:0] getInstance
,07-06 08:46:46.916  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b2ec43 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_OFF qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b33fdc4 6083:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-06 08:46:46.916  6083  6083 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,07-06 08:46:46.921  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 252 (W:30), CUR = -10, LCD = 0
,07-06 08:46:46.926  6083  6083 D accuweather: [KK AccuPhone]>>> U:4139 [0:0] getPWC : surface = 0, remote = 1
07-06 08:46:46.926  6083  6083 D accuweather: [KK AccuPhone]>>> U:4338 [0:0] Store PWC = 1
,07-06 08:46:46.926  6083  6083 D accuweather: [KK AccuPhone]>>> U:4199 [0:0] addPWC = 1
07-06 08:46:46.926  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,07-06 08:46:46.931  3524  6867 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-06 08:46:46.936  4629  4846 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-06 08:46:46.941  4629  4647 D daemonapp: [MSC_Daemon]>>> WCP:1255 [0:0] cp update : count : 1, pt : 3
,07-06 08:46:46.941  3524  5010 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-06 08:46:46.941  3524  4440 I Sensors : Acc old sensor_state 0, new sensor_state : 1 en : 1
,07-06 08:46:46.951  4629  6774 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-06 08:46:46.951  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:152 [0:0] make widget 4x1 view!!! 
,07-06 08:46:46.951  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:154 [0:0] make widget 4x2 view!!! 
07-06 08:46:46.951  6083  6083 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
07-06 08:46:46.951  6083  6083 D accuweather: [KK AccuPhone]>>> UIM:179 [0:0] get widget 4x2 view!!! wid = 2
,07-06 08:46:46.956  7448  7448 D SensorManager: registerListener :: 0, ICM20610 Acceleration Sensor, 200000, 0,  
,07-06 08:46:46.956  3524  5868 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b2ec43 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_OFF qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b33fdc4 6083:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-06 08:46:46.961  6083  6083 D accuweather: [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,07-06 08:46:46.961  6083  6083 D accuweather: [KK AccuPhone]>>> U:4298 [0:0] Store PWC succeed
,07-06 08:46:46.971  6083  6083 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,07-06 08:46:46.971  6083  6083 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,07-06 08:46:46.976  4512  4512 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-06 08:46:46.976  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:46.976  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:46.976  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-06 08:46:46.976  4512  4512 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-06 08:46:46.986  3524  4490 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-06 08:46:47.031  3524 12321 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-06 08:46:47.031  3524 12321 D BluetoothAdapter: STATE_ON
,07-06 08:46:47.031  3524  5815 V AlarmManager:  remove PendingIntent] PendingIntent{8fd32c0: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:46:47.076  3524 12321 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-06 08:46:47.116  3524 12321 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-06 08:46:47.121  3524 12321 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-06 08:46:47.196  3524 12321 I BatteryStatsDumper: Writing to database completed
,07-06 08:46:48.536  3524  5518 V AlarmManager:  remove PendingIntent] PendingIntent{9c54bf9: PendingIntentRecord{3365fd2 com.android.bluetooth broadcastIntent}}
,07-06 08:46:50.171  3524  4401 V AlarmManager: Expired Alarm result :4
,07-06 08:46:50.181  4512  4512 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-06 08:46:50.186  4512  4512 D KeyguardViewMediator: doKeyguardLocked: started
,07-06 08:46:50.206  4512  4512 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-06 08:46:50.206  4512  4512 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,07-06 08:46:55.926  3524  4401 V AlarmManager: Expired Alarm result :4
,07-06 08:46:56.951  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 253 (W:30), CUR = -10, LCD = 0
,07-06 08:46:58.936  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:46:58.936  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:46:59.206  3524  4401 V AlarmManager: Expired Alarm result :8
,07-06 08:46:59.996  3524  4401 V AlarmManager: Expired Alarm result :8
,07-06 08:47:07.001  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 253 (W:30), CUR = -10, LCD = 0
,07-06 08:47:10.021  3524  4553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:47:10.021  3524  4553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:47:10.021  3524  4553 D BatteryService: online:4, current avg:-1, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:47:10.021  3524  4553 D BatteryService: stay LED for fully charged
,07-06 08:47:10.021  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:47:10.026  3524  3524 I MotionRecognitionService: Plugged
07-06 08:47:10.026  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:47:10.026  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:47:10.026  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:47:10.036  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:47:10.036  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:47:10.036  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:47:10.056  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-06 08:47:10.056  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:47:10.066  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:47:10.066  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:47:10.066  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:15.081  3524  4972 E Watchdog: !@Sync 54 [07-06 08:47:15.085]
,07-06 08:47:15.581  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:47:16.961  3524  4401 V AlarmManager: Expired Alarm result :4
,07-06 08:47:17.006  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-06 08:47:17.006  4512  4512 I PERF    : received broadcast android.intent.action.TIME_TICK
07-06 08:47:17.006  4512  4512 D KeyguardUpdateMonitor: handleTimeUpdate
,07-06 08:47:17.021  4512  4512 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-06 08:47:17.026  4512  4512 D SecKeyguardClockView: HomeTimezone(): 1
,07-06 08:47:17.036  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:17.036  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:17.041  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:17.041  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:17.041  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:17.046  4512  4512 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:17.046  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:17.056  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 254 (W:30), CUR = -1, LCD = 0
,07-06 08:47:17.056  3524  5141 V AlarmManager:  remove PendingIntent] PendingIntent{4b699d8: PendingIntentRecord{c0b99c6 com.google.android.gms broadcastIntent}}
,07-06 08:47:17.066  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:47:17.066  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:47:17.071  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-06 08:47:17.071  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-06 08:47:17.101  3524  3524 I BackgroundCompactionService: onStart. jobID=801
,07-06 08:47:17.101  3524  3524 I BackgroundCompactionService: onStart done. jobID=801
,07-06 08:47:17.101  3524 12369 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-06 08:47:17.106  3524 12369 I BackgroundCompactionService: compact_memory command done
,07-06 08:47:17.196  4512  4512 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-06 08:47:18.951  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:47:18.951  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-06 08:47:19.056  5028  5071 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 101ms lastUpdatedAfter : 180433ms
,07-06 08:47:27.076  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false,
07-06 08:47:27.081  3524  4445 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-06 08:47:27.111  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 254 (W:30), CUR = -1, LCD = 0
,07-06 08:47:32.136  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:47:32.136  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-06 08:47:37.176  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 254 (W:30), CUR = -1, LCD = 0
,07-06 08:47:40.116  3524  5518 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:47:40.121  3524  5518 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:47:40.121  3524  5518 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:47:40.121  3524  5518 D BatteryService: stay LED for fully charged
,07-06 08:47:40.121  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 08:47:40.126  3524  3524 I MotionRecognitionService: Plugged
07-06 08:47:40.126  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:47:40.126  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:47:40.126  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:47:40.136  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:47:40.136  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:47:40.136  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:47:40.156  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:47:40.156  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:47:40.161  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:47:40.161  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:40.161  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:47:45.086  3524  4972 E Watchdog: !@Sync 55 [07-06 08:47:45.092]
,07-06 08:47:47.201  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:30), LCD = 0
,07-06 08:47:57.231  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:30), LCD = 0
,07-06 08:47:59.996  3524  4401 V AlarmManager: Expired Alarm result :8
,07-06 08:48:07.296  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:30), LCD = 0
,07-06 08:48:10.251  3524  3549 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-06 08:48:10.251  3524  3549 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-06 08:48:10.251  3524  3549 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-06 08:48:10.251  3524  3549 D BatteryService: stay LED for fully charged
,07-06 08:48:10.251  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 08:48:10.256  3524  3524 I MotionRecognitionService: Plugged
07-06 08:48:10.256  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-06 08:48:10.256  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-06 08:48:10.256  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-06 08:48:10.266  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-06 08:48:10.266  4512  4512 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-06 08:48:10.266  4512  4512 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 08:48:10.281  5781  5781 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 08:48:10.281  5781  6247 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 08:48:10.291  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:48:10.291  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 08:48:10.291  4512  4512 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 08:48:15.091  3524  4972 E Watchdog: !@Sync 56 [07-06 08:48:15.096]
,07-06 08:48:15.281  5793  6747 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-06 08:48:15.576  2954  5188 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-06 08:48:17.346  3524  6867 D SSRM:n  : SIOP:: AP = 260, PST = 255 (W:30), LCD = 0
,TIME-OUT KILL (timeout was 1400000ms),07-06 08:48:19.181  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-06 08:48:19.181  5028  5071 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-06 08:48:22.721 12406 12406 I FIPS_bssl: FIPS approved mode (1) | 12406 | app_process
07-06 08:48:22.731 12406 12406 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-06 08:48:22.731 12406 12406 D AndroidRuntime: CheckJNI is OFF
07-06 08:48:22.736 12406 12406 D AndroidRuntime: readGMSProperty: start
07-06 08:48:22.736 12406 12406 D AndroidRuntime: readGMSProperty: already setted!!
07-06 08:48:22.736 12406 12406 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 08:48:22.736 12406 12406 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 08:48:22.736 12406 12406 D AndroidRuntime: readGMSProperty: end
07-06 08:48:22.736 12406 12406 D AndroidRuntime: addProductProperty: start
07-06 08:48:22.766 12406 12406 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-06 08:48:22.796 12406 12406 I Radio-JNI: register_android_hardware_Radio DONE
07-06 08:48:22.801 12406 12406 E AffinityControl: AffinityControl: registerfunction enter
07-06 08:48:22.816 12406 12406 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-06 08:48:22.826  3524  4654 D PackageManager: START PACKAGE DELETE: observer{21626733}
07-06 08:48:22.826  3524  4654 D PackageManager: pkg{<packageName>}
07-06 08:48:22.826  3524  4654 D PackageManager: user{0}
07-06 08:48:22.826  3524  4654 D PackageManager: caller{2000}
07-06 08:48:22.826  3524  4654 D PackageManager: flags{2}
07-06 08:48:22.826  3524  4654 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-06 08:48:22.826  3524  4654 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-06 08:48:22.826  3524  4654 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-06 08:48:22.826  3524  4654 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-06 08:48:22.826  3524  4654 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-06 08:48:22.826  3524  3837 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-06 08:48:22.826  3524  3837 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-06 08:48:22.826  3524  3837 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-06 08:48:22.826  3524  3837 D ApplicationPolicy: getApplicationUninstallationEnabled
07-06 08:48:22.826  3524  3837 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-06 08:48:22.826  3524  3837 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-06 08:48:22.831  3524  3837 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-06 08:48:22.831  3524  3678 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=-1: uninstall pkg
07-06 08:48:22.831  3524  3837 D PackageManager: !@killApplicatoin: 10007, uninstall pkg
07-06 08:48:22.831  3524  3837 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-06 08:48:22.831  3524  3678 I ActivityManager: Killing 11392:com.test.thalitest/u0a7 (adj 0): stop com.test.thalitest cause uninstall pkg
07-06 08:48:22.831  3524  3837 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-06 08:48:22.836  3524  3678 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-06 08:48:22.836  3524  3678 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-06 08:48:22.846  3524  3678 D ActivityManager: mDVFSHelper.acquire()
07-06 08:48:22.871  3524  3837 D AASAinstall: there is not AASApackages.xml file
07-06 08:48:22.876  3524  3678 I ActivityManager: Start proc 12422:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
07-06 08:48:22.876 12422 12422 E Zygote  : v2
07-06 08:48:22.876 12422 12422 I libpersona: KNOX_SDCARD checking this for 10007
07-06 08:48:22.876 12422 12422 I libpersona: KNOX_SDCARD not a persona
07-06 08:48:22.881 12422 12422 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-06 08:48:22.881 12422 12422 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-06 08:48:22.886 12422 12422 E Zygote  : accessInfo : 0
07-06 08:48:22.886 12422 12422 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-06 08:48:22.891  3524  3678 I ActivityManager:   Force finishing activity ActivityRecord{8f3507c u0 com.test.thalitest/.MainActivity t69}
07-06 08:48:22.921 12422 12422 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 08:48:22.921 12422 12422 D ActivityThread: Added TimaKeyStore provider
07-06 08:48:22.986  3524  3550 D GraphicsStats: Buffer count: 4
07-06 08:48:22.986  3524  5010 I WindowState: WIN DEATH: Window{c5289d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-06 08:48:22.991  3524  5815 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@140af25)
07-06 08:48:22.991  3524  4454 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:48:22.991  3524  4454 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:48:22.996  2905  3009 D libEGL  : eglTerminate EGLDisplay = 0xb69016fc
07-06 08:48:22.996  3524  4454 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-06 08:48:22.996  2905  3009 D libEGL  : eglTerminate EGLDisplay = 0xb69016fc
07-06 08:48:22.996  2905  3011 I SurfaceFlinger: id=21 Removed NainActivit (6/8)
07-06 08:48:22.996  2905  4414 I SurfaceFlinger: id=21 Removed NainActivit (-2/8)
07-06 08:48:23.001  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbe971474
07-06 08:48:23.006  3524  5010 D InputDispatcher: Focus left window: 11392
07-06 08:48:23.071  3524  3661 E libprocessgroup: failed to kill 1 processes for processgroup 11392
07-06 08:48:23.156  3524  3837 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-06 08:48:23.191  3524  3837 W PackageSettings: Skipping PackageSetting{a46d4af com.example.hello/10691} due to missing metadata
07-06 08:48:23.266  3524  3837 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-06 08:48:23.266  3524  3765 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-06 08:48:23.276  3524  3765 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-06 08:48:23.276  3524  3765 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
07-06 08:48:23.276  3524  3765 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
07-06 08:48:23.276  3524  3765 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4347)
07-06 08:48:23.276  3524  3765 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13476)
07-06 08:48:23.276  3524  3765 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 08:48:23.276  3524  3765 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-06 08:48:23.276  3524  3765 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-06 08:48:23.276  3524  3765 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-06 08:48:23.276  3524  3765 D SecWifiDisplayUtil: Metadata value : none
07-06 08:48:23.276  3524  3765 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{98608fa V.E...... R.....ID 0,0-0,0}
07-06 08:48:23.276  3524  3765 D ISSUE_DEBUG: InputChannelName : f702908 Starting com.test.thalitest
07-06 08:48:23.281  2949  2949 W keystore: ENTER clear_uid from uid 1000 for 10007
07-06 08:48:23.281  3524  3837 I art     : Starting a blocking GC Explicit
07-06 08:48:23.291  3524  3524 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
07-06 08:48:23.301  3524  3678 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
07-06 08:48:23.306  2905  2905 I SurfaceFlinger: id=23 createSurf (1528x2333),1 flag=4, VSBConnecti
07-06 08:48:23.306  3524  5134 I ActivityManager: Killing 10574:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): DHA:empty #31
07-06 08:48:23.316  6986 10321 D mali_winsys: new_window_surface returns 0x3000,  [1528x2333]-format:1
07-06 08:48:23.321  3524  3678 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-06 08:48:23.326  5128  5128 D Launcher: onRestart, Launcher: 51393531
07-06 08:48:23.336  3524  3678 D InputDispatcher: Focus entered window: 6986
07-06 08:48:23.336  3524  3678 D InputDispatcher: Focused application released
07-06 08:48:23.346  5128  5128 D Launcher: onStart, Launcher: 51393531
07-06 08:48:23.346  5128  5128 D Launcher.HomeView: onStart
07-06 08:48:23.351 12422 12422 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
07-06 08:48:23.351  3524  5012 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
07-06 08:48:23.351 12422 12422 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
07-06 08:48:23.351  3524  5012 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:23.351  3524  3524 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:23.356  3524  3524 I KnoxTimeoutHandler: Shared devices show user statefalse
07-06 08:48:23.356  3524  3524 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
07-06 08:48:23.356  3524  3765 W WindowManager: Failed looking up window
07-06 08:48:23.356  3524  3765 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2a2eab does not exist
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14796)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14787)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:5218)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:208)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.ViewRootImpl.relayoutWindow(ViewRootImpl.java:6684)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1994)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1437)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:7397)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:920)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.Choreographer.doCallbacks(Choreographer.java:695)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.Choreographer.doFrame(Choreographer.java:631)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:906)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-06 08:48:23.356  3524  3765 D ViewRootImpl: #3 mView = null
07-06 08:48:23.356  5128  5128 V ActivityThread: updateVisibility : ActivityRecord{6d080d4 token=android.os.BinderProxy@2eab20b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-06 08:48:23.356  3524  3765 W WindowManager: Failed looking up window
07-06 08:48:23.356  3524  3765 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@2a2eab does not exist
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14796)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14787)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4614)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3748)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6887)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4232)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-06 08:48:23.356  3524  3765 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-06 08:48:23.356  3524  3765 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3524 uid:1000
07-06 08:48:23.356  3524  3765 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 08:48:23.356  3524  3765 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3524 uid:1000
07-06 08:48:23.356  3524  3765 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-06 08:48:23.356 12422 12422 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
07-06 08:48:23.356 12422 12422 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
07-06 08:48:23.371  2905  2905 I SurfaceFlinger: id=24 createSurf (1440x2560),1 flag=4, Mauncher
07-06 08:48:23.371  3524  5134 V WindowOrientationListener: setCurrentAppOrientation :1
07-06 08:48:23.371  3524  5134 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-06 08:48:23.381  3524  5054 V WindowStateAnimator: Finishing drawing window Window{5ac2375 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-06 08:48:23.386  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
07-06 08:48:23.386  5128  5450 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
07-06 08:48:23.391 12422 12422 D AndroidRuntime: Shutting down VM
07-06 08:48:23.391 12422 12422 E AndroidRuntime: FATAL EXCEPTION: main
07-06 08:48:23.391 12422 12422 E AndroidRuntime: Process: com.test.thalitest, PID: 12422
07-06 08:48:23.391 12422 12422 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6290)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7225)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
07-06 08:48:23.391 12422 12422 E AndroidRuntime: 	... 9 more
07-06 08:48:23.396  3524  5821 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
07-06 08:48:23.401  3524  6867 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-06 08:48:23.401  2905  2905 I SurfaceFlinger: id=25 createSurf (1592x384),1 flag=4, VSBConnecti
07-06 08:48:23.411  3524  3765 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:23.411  3524  3524 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:23.411  3524  3685 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5ac2375 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
07-06 08:48:23.411  3524  3524 I KnoxTimeoutHandler: SD activityfalse
07-06 08:48:23.411  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
07-06 08:48:23.416  6986 10321 D mali_winsys: new_window_surface returns 0x3000,  [1592x384]-format:1
07-06 08:48:23.421  3524  3685 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5ac2375 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
07-06 08:48:23.421  6986  6986 V ActivityThread: updateVisibility : ActivityRecord{d1def68 token=android.os.BinderProxy@a46bf95 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
07-06 08:48:23.421  4512  4512 D PhoneStatusBar: setSystemUiVisibility vis=40008000 mask=ffffffff oldVal=8000 newVal=40008000 diff=40000000
07-06 08:48:23.421  3524  3765 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a9cb67 u0 com.samsung.android.MtpApplication/.USBConnection t68} time:1704049
07-06 08:48:23.421  3524  3765 D ActivityManager: mDVFSHelper.release()
07-06 08:48:23.431 12422 12422 I Process : Sending signal. PID: 12422 SIG: 9
07-06 08:48:23.431  3524  3837 I art     : Explicit concurrent mark sweep GC freed 129373(7MB) AllocSpace objects, 65(1512KB) LOS objects, 33% free, 31MB/46MB, paused 4.125ms total 149.783ms
07-06 08:48:23.436  3524  6867 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-06 08:48:23.451  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
07-06 08:48:23.456  3524  3678 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{85b0a87 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bccd270 11892:com.samsung.android.sm/1000}
07-06 08:48:23.461  3524  3837 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-06 08:48:23.461  3524  3837 D AASAuninstall: userId = 0, info.removedAppID = 10007, info.uid = 10007, packageName = com.test.thalitest
07-06 08:48:23.461  3524  3837 D AASAinstall: there is not AASApackages.xml file
07-06 08:48:23.461  3524  3837 D PackageManager: result of delete: 1{21626733}
07-06 08:48:23.461  3524  5858 V WindowStateAnimator: Finishing drawing window Window{ed5037b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-06 08:48:23.461  3524  3837 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-06 08:48:23.461  3524  3837 D PackageManager: userId{-1}
07-06 08:48:23.461  3524  3837 D PackageManager: andCode{true}
07-06 08:48:23.466  6986  6986 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a46bf95 time:1704092
07-06 08:48:23.471 12406 12406 I art     : System.exit called, status: 0
07-06 08:48:23.471 12406 12406 I AndroidRuntime: VM exiting with result code 0.
07-06 08:48:23.471 11892 11892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
07-06 08:48:23.486  3524  3837 I ActivityManager: Force stopping com.test.thalitest appid=10007 user=0: pkg removed
07-06 08:48:23.486  3524  3837 I ActivityManager: Killing 12422:com.test.thalitest/u0a7 (adj 9): stop com.test.thalitest cause pkg removed
07-06 08:48:23.486  3524  3837 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-06 08:48:23.486  3524  3837 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-06 08:48:23.501  3524  3765 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:23.501  3524  4553 W ActivityManager: Spurious death for ProcessRecord{cf69ddd 0:com.test.thalitest/u0a7}, curProc for 12422: null
07-06 08:48:23.501  3524  3524 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-06 08:48:23.506  3524  3524 I KnoxTimeoutHandler: SD activityfalse
07-06 08:48:23.526 10418 12437 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
07-06 08:48:23.531 10418 12437 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
07-06 08:48:23.536 10418 12437 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
07-06 08:48:23.541  5128  5450 W OpenGLRenderer: SFEffectCache::get: create texture(0x93d0efbc): name, size, mSize = 11, 578136, 1948784
07-06 08:48:23.551  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbe97140c
07-06 08:48:23.556  3524  5141 V WindowStateAnimator: Finishing drawing window Window{e2572ef u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
07-06 08:48:23.561  5128  5128 D Launcher.HomeView: onStop
07-06 08:48:23.586  4512  4512 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
07-06 08:48:23.586  4512  4512 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
07-06 08:48:23.601  5793  6072 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-06 08:48:23.606  5709  5709 E SamsungIME: mOCRHelper is null
07-06 08:48:23.606  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-06 08:48:23.606  2915  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-06 08:48:23.621  3524  4444 V NetworkStats: removeUidsLocked() for UIDs [10007]
07-06 08:48:23.621  3524  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 08:48:23.621  3524  4444 V NetworkStats: performPollLocked(flags=0x3)
07-06 08:48:23.631  3524  4445 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
07-06 08:48:23.631  3524  4445 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-06 08:48:23.631  3524  4444 V NetworkStats: performPollLocked() took 12ms
07-06 08:48:23.636  3524  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 08:48:23.636  5115  5115 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-06 08:48:23.641  3524  5868 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{85b0a87 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dcc6713 7701:com.google.android.gms/u0a14}
07-06 08:48:23.646  3524  5054 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
07-06 08:48:23.656  3524  3765 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-06 08:48:23.671  3524  4387 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
07-06 08:48:23.671  3524  4387 D UsbHostManager: displayNotification : [02h,02h,01h]
07-06 08:48:23.671  3524  4387 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
07-06 08:48:23.671  3524  4387 D UsbHostManager: displayNotification : [0ah,00h,00h]
07-06 08:48:23.671  3524  4499 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/69_task.xml
07-06 08:48:23.671  3524  4387 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
07-06 08:48:23.671  3524  4387 D UsbHostManager: displayNotification : [02h,0dh,00h]
07-06 08:48:23.671  3524  4387 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
07-06 08:48:23.671  3524  4387 D UsbHostManager: displayNotification : [0ah,00h,01h]
07-06 08:48:23.676  3524  4445 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 08:48:23.676  3524  4445 D NtpTrustedTime: currentTimeMillis() cache hit
07-06 08:48:23.676  3524  4499 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/69_task_thumbnail.png
07-06 08:48:23.681  3524  4387 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
07-06 08:48:23.681  3524  4387 D UsbHostManager: displayNotification : [09h,00h,00h]
07-06 08:48:23.681  3524  4500 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
07-06 08:48:23.681  3524  4500 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
07-06 08:48:23.681  3524  4500 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
07-06 08:48:23.691  3524  5868 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9da2957 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{40813 7935:com.samsung.klmsagent/u0a21}
07-06 08:48:23.691  7935  7935 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Wed Jul 06 08:48:23 GMT+02:00 2016
07-06 08:48:23.701  3524  3765 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2675076 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t67} time:1704327
07-06 08:48:23.711  3524  4416 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-06 08:48:23.711  4908  4908 D MtpClient: onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
07-06 08:48:23.711  4908  4908 D MtpClient: ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
07-06 08:48:23.721  3524  3524 V AlarmManager: Remove alarm for next reason : android.intent.action.PACKAGE_REMOVED : package: com.test.thalitest
07-06 08:48:23.721  3524  3524 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-06 08:48:23.721  3524  3524 D UniversalCredentialManagerService: inside mPkgReciever onReceive : android.intent.action.PACKAGE_REMOVED
07-06 08:48:23.721  3524  3524 D UniversalCredentialManagerService: ACTION_PACKAGE_REMOVED is called....
07-06 08:48:23.721  3524  3524 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-06 08:48:23.721  3524  3524 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-06 08:48:23.721  3524  3524 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10007 container id = 0
07-06 08:48:23.726  3524  3524 I OTPFW   : ProvisionData::getAllEntries Enter
07-06 08:48:23.726  3524  3524 E OTPFW   : ProvisionData::getAllEntries Table is empty
07-06 08:48:23.726  3524  3524 E SDAgentPackageStateReceiver: Not going to handle 'com.test.thalitest'!
07-06 08:48:23.731  3524  4500 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
07-06 08:48:23.731  3524  4500 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
07-06 08:48:23.741  7935  7935 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
07-06 08:48:23.786  3524  4416 I EventHub: Removing device '/dev/input/event10' due to inotify event
07-06 08:48:23.791  3524  4654 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9da2957 u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5036c94 3524:system/1000}
07-06 08:48:23.801  7935  7935 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
07-06 08:48:23.801  7935  7935 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-06 08:48:23.806  7935  7935 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-06 08:48:23.806  7935 12452 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
07-06 08:48:23.806  7935 12452 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
07-06 08:48:23.806  7935 12452 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
07-06 08:48:23.806  7935 12452 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
07-06 08:48:23.806  7935 12452 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
07-06 08:48:23.806  7935 12452 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
07-06 08:48:23.811  7935 12452 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-06 08:48:23.816  7935 12452 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-06 08:48:23.821  7935 12452 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
07-06 08:48:23.831  5102 12450 D RegisteredComponentCache: Collect Tech packages for Knox
07-06 08:48:23.836  7935 12452 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
07-06 08:48:23.836  3524  4416 I EventHub: Removing device '/dev/input/event7' due to inotify event
07-06 08:48:23.841  7935 12452 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: #################################################################
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: #################################################################
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
07-06 08:48:23.851  7935 12452 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: #################################################################
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: #################################################################
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
07-06 08:48:23.851  7935 12452 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-06 08:48:23.851  7935 12452 W SQLiteOpenHelper: Opened klms.db in read-only mode
07-06 08:48:23.856  7935 12452 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
07-06 08:48:23.871  3524  5815 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-06 08:48:23.871  3524  5815 D SettingsProvider: isChangeAllowed() SettingsProvider : name = klm_eula_shown
07-06 08:48:23.871  3524  5815 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-06 08:48:23.871  3524  5815 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-06 08:48:23.871  3524  5815 D SettingsProvider: selectionArgs: false
07-06 08:48:23.871  3524  5815 D SettingsProvider: selectionArgs: 10021
07-06 08:48:23.876  3524  5815 D SettingsProvider: ret = -1
07-06 08:48:23.881  3524  4416 I EventHub: Removing device '/dev/input/event8' due to inotify event
07-06 08:48:23.911  3524  4416 I EventHub: Removing device '/dev/input/event9' due to inotify event
07-06 08:48:23.941  3524  4416 I EventHub: Removing device '/dev/input/event11' due to inotify event
07-06 08:48:23.966  3524  4416 I EventHub: Removing device '/dev/input/event12' due to inotify event
07-06 08:48:23.986  7701 12447 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
07-06 08:48:24.011  3524  4416 I EventHub: Removing device '/dev/input/event13' due to inotify event
07-06 08:48:24.021  3524  3661 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
07-06 08:48:24.021  3524  3661 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-06 08:48:24.041  3524  4416 I EventHub: Removing device '/dev/input/event14' due to inotify event

```
