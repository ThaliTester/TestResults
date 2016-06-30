#### Test 757892682551a10_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
06-30 13:52:46.710  3607  3630 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:52:46.710  3607  3630 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:52:46.710  3607  3630 D BatteryService: online:4, current avg:139, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:166
06-30 13:52:46.710  3607  3630 D BatteryService: stay LED for fully charged
,06-30 13:52:46.710  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:52:46.715  3607  3607 I MotionRecognitionService: Plugged
06-30 13:52:46.715  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:52:46.715  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:52:46.715  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
06-30 13:52:46.725  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:46.725  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:46.725  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:52:46.745  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:46.745  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:46.745  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:47.395 10498 10498 I FIPS_bssl: FIPS approved mode (1) | 10498 | app_process
06-30 13:52:47.405 10498 10498 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:52:47.405 10498 10498 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:47.405 10498 10498 D AndroidRuntime: readGMSProperty: start
06-30 13:52:47.405 10498 10498 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:52:47.405 10498 10498 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:52:47.405 10498 10498 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:52:47.405 10498 10498 D AndroidRuntime: readGMSProperty: end
06-30 13:52:47.405 10498 10498 D AndroidRuntime: addProductProperty: start
06-30 13:52:47.435 10498 10498 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:52:47.460 10498 10498 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:52:47.470 10498 10498 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:52:47.480 10498 10498 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 13:52:47.495  3607  5753 D GameManagerService: identifyGamePackage. com.test.thalitest
06-30 13:52:47.495  3607  5753 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
06-30 13:52:47.495  3607  5753 D ActivityManager: mDVFSHelper.acquire()
06-30 13:52:47.495  3607  5753 V WindowManager: addAppToken: AppWindowToken{f687f3 token=Token{5225a62 ActivityRecord{8cf452d u0 com.test.thalitest/.MainActivity t69}}} to stack=1 task=69 at 0
06-30 13:52:47.500  3607  3850 D SecWifiDisplayUtil: Metadata value : none
06-30 13:52:47.500  3607  3850 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{719026b V.E...... R.....ID 0,0-0,0}
06-30 13:52:47.500  3607  3850 D ISSUE_DEBUG: InputChannelName : 6487261 Starting com.test.thalitest
06-30 13:52:47.505 10513 10513 E Zygote  : v2
06-30 13:52:47.505 10513 10513 I libpersona: KNOX_SDCARD checking this for 10007
06-30 13:52:47.505 10513 10513 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:47.505 10513 10513 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 13:52:47.505 10513 10513 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:47.505 10513 10513 E Zygote  : accessInfo : 0
06-30 13:52:47.505 10513 10513 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 13:52:47.505  3607  5753 I ActivityManager: Start proc 10513:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
06-30 13:52:47.505  3607  5753 D InputDispatcher: Focused application set to: xxxx
06-30 13:52:47.510  3607  5753 D InputDispatcher: Focus left window: 6795
06-30 13:52:47.510 10498 10498 D AndroidRuntime: Shutting down VM
06-30 13:52:47.510  3607  4443 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 13:52:47.510  4505  4505 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-30 13:52:47.510  3607  3777 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2c710fb u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-30 13:52:47.520  2904  2904 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
06-30 13:52:47.520 10513 10513 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:47.520 10513 10513 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:47.535  3607  5761 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 13:52:47.535  3607  5761 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 13:52:47.535  3607  3850 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3607 uid:1000
06-30 13:52:47.535  3607  3850 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:47.535  3607  3850 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3607 uid:1000
06-30 13:52:47.535  3607  3850 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:52:47.535  3607  3850 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-30 13:52:47.535  3607  3777 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{6487261 u0 d0 Starting com.test.thalitest}
06-30 13:52:47.535  4505  4505 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 13:52:47.540  3607  5761 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 13:52:47.545  3607  3607 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
06-30 13:52:47.545  3607  3773 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 13:52:47.565  2904  9511 D libEGL  : eglTerminate EGLDisplay = 0xb1aff624
06-30 13:52:47.565  2904  9511 D libEGL  : eglTerminate EGLDisplay = 0xb1aff624
06-30 13:52:47.565  2904  3013 I SurfaceFlinger: id=7 Removed Mauncher (4/11)
06-30 13:52:47.570  2904  3009 I SurfaceFlinger: id=7 Removed Mauncher (-2/11)
06-30 13:52:47.570  5172  5172 V ActivityThread: updateVisibility : ActivityRecord{1eda0f6 token=android.os.BinderProxy@dadcec3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 13:52:47.570  5172  5172 D Launcher: onTrimMemory. Level: 20
06-30 13:52:47.570  2904  9511 D libEGL  : eglTerminate EGLDisplay = 0xb1aff624
06-30 13:52:47.575  2904  3013 I SurfaceFlinger: id=11 Removed VSBConnecti (6/10)
06-30 13:52:47.575  2904  3009 I SurfaceFlinger: id=11 Removed VSBConnecti (-2/10)
06-30 13:52:47.580  3607  3850 V WindowStateAnimator: Finishing drawing window Window{6487261 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 13:52:47.585  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbe8e8474
06-30 13:52:47.585  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbe8e8474
06-30 13:52:47.585  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbe8e840c
06-30 13:52:47.585  2904  3009 I SurfaceFlinger: id=12 Removed VSBConnecti (4/9)
06-30 13:52:47.585  2904  4428 I SurfaceFlinger: id=12 Removed VSBConnecti (-2/9)
06-30 13:52:47.585  6795  6795 V ActivityThread: updateVisibility : ActivityRecord{4ca50d8 token=android.os.BinderProxy@6362545 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 13:52:47.600  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbe8e8474
,06-30 13:52:47.850  3607  5761 I WindowManager: Screenshot max retries 4 of Token{5225a62 ActivityRecord{8cf452d u0 com.test.thalitest/.MainActivity t69}} appWin=Window{6487261 u0 d0 Starting com.test.thalitest} drawState=4
,06-30 13:52:47.860  3607  3773 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 13:52:47.875  3607  4443 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,06-30 13:52:47.890  3607  6660 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:47.895  3607  6660 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:47.950 10513 10513 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,06-30 13:52:47.980 10513 10513 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-30 13:52:47.990 10513 10513 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 5823-5826)
06-30 13:52:47.990 10513 10513 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-30 13:52:48.005 10513 10527 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,06-30 13:52:48.010 10513 10513 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d327040}
06-30 13:52:48.010 10513 10513 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 13:52:48.010 10513 10513 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 13:52:48.020 10513 10513 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-30 13:52:48.040 10513 10528 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,06-30 13:52:48.060 10513 10513 D libEGL  : eglInitialize EGLDisplay = 0xbee49e7c
,06-30 13:52:48.090  3607  3629 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
06-30 13:52:48.095  3607  3629 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,06-30 13:52:48.155 10513 10513 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,06-30 13:52:48.165 10513 10513 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:52:48.170 10513 10513 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
06-30 13:52:48.170 10513 10513 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,06-30 13:52:48.170 10513 10513 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,06-30 13:52:48.185 10513 10513 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,06-30 13:52:48.190 10513 10513 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-30 13:52:48.280 10513 10513 D SecWifiDisplayUtil: Metadata value : none
,06-30 13:52:48.285 10513 10513 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{97a2a59 I.E...... R.....ID 0,0-0,0}
,06-30 13:52:48.295 10513 10564 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:48.305  3607  5753 D ISSUE_DEBUG: InputChannelName : 66cb71a com.test.thalitest/com.test.thalitest.MainActivity
,06-30 13:52:48.310  3607  4551 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 13:52:48.310  3607  4551 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:48.310  3607  3607 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 13:52:48.310  3607  3607 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 13:52:48.340 10513 10513 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 10513
,06-30 13:52:48.345  3607  5053 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/10513 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 13:52:48.350 10513 10527 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,06-30 13:52:48.365 10513 10513 D SecWifiDisplayUtil: Metadata value : none
,06-30 13:52:48.380  2904  2904 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,06-30 13:52:48.385  3607  5103 D InputDispatcher: Focus entered window: 10513
,06-30 13:52:48.390  3607  3850 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3607 uid:1000
06-30 13:52:48.390  3607  3850 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:48.390  3607  3850 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3607 uid:1000
06-30 13:52:48.390  3607  3850 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 13:52:48.390 10513 10564 D libEGL  : eglInitialize EGLDisplay = 0x9c13f7c4
06-30 13:52:48.390 10513 10564 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 13:52:48.395 10513 10564 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
06-30 13:52:48.400 10513 10513 V ActivityThread: updateVisibility : ActivityRecord{a8b62a token=android.os.BinderProxy@6db0ea0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 13:52:48.400 10513 10513 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-30 13:52:48.405 10513 10513 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 13:52:48.405  3607  5737 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 13:52:48.420 10513 10513 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 13:52:48.465 10513 10572 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:48.465 10513 10572 D libEGL  : eglInitialize EGLDisplay = 0x9a17f3ec
,06-30 13:52:48.485  3607  5053 V WindowStateAnimator: Finishing drawing window Window{66cb71a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-30 13:52:48.485 10513 10513 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-30 13:52:48.485  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbe8e840c
,06-30 13:52:48.490 10513 10513 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6db0ea0 time:146328
,06-30 13:52:48.495  3607  3850 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 13:52:48.495  3607  3607 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-30 13:52:48.505  3607  3607 I KnoxTimeoutHandler: SD activityfalse
,06-30 13:52:48.505  3607  3850 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +654ms (total +1s11ms)
,06-30 13:52:48.510  3607  3850 D ActivityManager: mDVFSHelper.release()
06-30 13:52:48.510  3607  3850 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8cf452d u0 com.test.thalitest/.MainActivity t69} time:146345
,06-30 13:52:48.510  3607  3850 D ViewRootImpl: #3 mView = null
,06-30 13:52:48.515  2904  4428 I SurfaceFlinger: id=13 Removed uhalitest (7/9),
06-30 13:52:48.515  2904  9511 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,06-30 13:52:48.520  2904  2904 D libEGL  : eglTerminate EGLDisplay = 0xbe8e8474,
,06-30 13:52:48.525 10513 10513 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10513
,06-30 13:52:48.705 10513 10513 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 13:52:48.840 10513 10578 D jxcore_app_log: JniHelper::setJavaVM(0xb4834000), pthread_self() = -1732773584
,06-30 13:52:48.840 10513 10578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:48.840 10513 10578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:48.840 10513 10578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:48.840 10513 10578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:48.840 10513 10578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:52:48.845 10513 10578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f5fd0 added. We now have 1 listener(s)
,06-30 13:52:48.845 10513 10578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,06-30 13:52:48.845 10513 10578 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,06-30 13:52:48.850 10513 10578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:48.850 10513 10578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:48.850 10513 10578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9fa5ef added. We now have 1 listener(s)
06-30 13:52:48.850 10513 10578 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:52:48.850 10513 10578 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:48.850 10513 10578 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 13:52:48.850 10513 10578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:48.850 10513 10578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 13:52:48.855 10513 10578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:52:48.855 10513 10578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 13:52:48.855 10513 10578 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:52:48.855 10513 10578 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,06-30 13:52:48.855 10513 10578 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:48.855 10513 10578 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:52:48.855 10513 10578 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:48.855 10513 10578 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:48.855 10513 10578 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 13:52:48.880 10513 10513 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:49.235 10513 10579 W jxcore-log: Initializing JXcore engine
06-30 13:52:49.235 10513 10579 W jxcore-log: JXcore engine is ready
,06-30 13:52:49.260  5678  5678 E audit   : type=1400 msg=audit(1467287569.260:260): avc:  denied  { ioctl } for  pid=10579 comm="Thread-1020" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4252 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 13:52:49.260  5678  5678 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:49.260  5678  5678 E audit   : type=1300 msg=audit(1467287569.260:260): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=2 a3=9843f3c8 items=0 ppid=2961 ppcomm=main pid=10579 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1020" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 13:52:49.260  5678  5678 E audit   : type=1327 msg=audit(1467287569.260:260): proctitle="com.test.thalitest"
06-30 13:52:49.260  5678  5678 E audit   : type=1320 msg=audit(1467287569.260:260): 
06-30 13:52:49.260  5678  5678 E audit   : type=1400 msg=audit(1467287569.260:261): avc:  denied  { ioctl } for  pid=10579 comm="Thread-1020" path="socket:[37294]" dev="sockfs" ino=37294 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
06-30 13:52:49.260  5678  5678 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 13:52:49.260  5678  5678 E audit   : type=1300 msg=audit(1467287569.260:261): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=2 a3=9843f3c8 items=0 ppid=2961 ppcomm=main pid=10579 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1020" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 13:52:49.260  5678  5678 E audit   : type=1327 msg=audit(1467287569.260:261): proctitle="com.test.thalitest"
06-30 13:52:49.260  5678  5678 E audit   : type=1320 msg=audit(1467287569.260:261): 
,06-30 13:52:49.265 10513 10579 W jxcore-log: Starting JXcore engine
,06-30 13:52:49.315 10513 10579 W jxcore-log: Platform android
06-30 13:52:49.315 10513 10579 W jxcore-log: 
06-30 13:52:49.315 10513 10579 W jxcore-log: Process ARCH arm
06-30 13:52:49.315 10513 10579 W jxcore-log: 
,06-30 13:52:49.315  4700  4700 D Recents : onTaskStackChanged
,06-30 13:52:49.405 10513 10579 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:49.405 10513 10579 I jxcore-log: 
,06-30 13:52:49.405 10513 10579 W jxcore-log: JXcore engine is started
,06-30 13:52:49.415 10513 10578 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:49.420  3607  5053 D GameManagerService: identifyGamePackage. com.android.packageinstaller
06-30 13:52:49.420  3607  5053 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.android.packageinstaller)
,06-30 13:52:49.420  3607  5053 D ActivityManager: mDVFSHelper.acquire()
,06-30 13:52:49.420  3607  5053 V WindowManager: addAppToken: AppWindowToken{9711aca token=Token{1a8a635 ActivityRecord{6e0e06c u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}}} to stack=1 task=69 at 1
,06-30 13:52:49.430 10580 10580 E Zygote  : v2
06-30 13:52:49.430 10580 10580 I libpersona: KNOX_SDCARD checking this for 10141
06-30 13:52:49.430 10580 10580 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:49.430 10580 10580 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-30 13:52:49.430 10580 10580 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:52:49.430 10580 10580 E Zygote  : accessInfo : 0
,06-30 13:52:49.430 10580 10580 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,06-30 13:52:49.430  3607  5053 I ActivityManager: Start proc 10580:com.android.packageinstaller/u0a141 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 13:52:49.435  3607  5053 D InputDispatcher: Focused application set to: xxxx
,06-30 13:52:49.435  3607  5053 D InputDispatcher: Focus left window: 10513
06-30 13:52:49.435 10513 10578 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 13:52:49.435  3607  3850 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3607 uid:1000
06-30 13:52:49.435  3607  3850 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:49.435  3607  3850 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3607 uid:1000
06-30 13:52:49.435  3607  3850 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 13:52:49.445 10580 10580 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:49.445 10580 10580 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:49.445  3607  5753 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 13:52:49.450  3607  3607 D GameManagerService: NotifyRunnable. pkg: com.android.packageinstaller, type: 4, isMinimized: false, isTunableApp: false
06-30 13:52:49.450  3607  3773 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 13:52:49.755  3607  5753 I WindowManager: Screenshot max retries 4 of Token{1a8a635 ActivityRecord{6e0e06c u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}} appWin=Window{66cb71a u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 13:52:49.760  3607  3773 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 13:52:49.780  3607  6660 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:49.795 10580 10580 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 13:52:49.955 10580 10580 D SecWifiDisplayUtil: Metadata value : none
,06-30 13:52:49.955 10580 10580 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cbded92 I.E...... R.....I. 0,0-0,0}
,06-30 13:52:49.960 10580 10592 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:49.960  3607  5053 D ISSUE_DEBUG: InputChannelName : 430c917 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-30 13:52:49.960  3607  4551 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 13:52:49.960  3607  4551 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:49.965  3607  3607 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 13:52:49.965  3607  3607 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 13:52:49.965  3607  3607 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 13:52:49.985  2904  2904 I SurfaceFlinger: id=15 createSurf (193x193),1 flag=4, HrantPermis
,06-30 13:52:49.985  3607  3777 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{430c917 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-30 13:52:49.985  4505  4505 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 13:52:49.995  3607  5754 D InputDispatcher: Focus entered window: 10580
,06-30 13:52:50.000  3607  3850 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3607 uid:1000
06-30 13:52:50.000  3607  3850 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:50.000  3607  3850 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3607 uid:1000
06-30 13:52:50.000  3607  3850 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 13:52:50.005 10580 10592 D libEGL  : eglInitialize EGLDisplay = 0xae9897c4
06-30 13:52:50.005 10580 10592 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:50.015 10580 10592 D mali_winsys: new_window_surface returns 0x3000,  [1528x2656]-format:1,
,06-30 13:52:50.020 10580 10580 V ActivityThread: updateVisibility : ActivityRecord{47f4bdb token=android.os.BinderProxy@6fd671d {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 13:52:50.020 10580 10580 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 13:52:50.025  3607  5052 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 13:52:50.030  5588  5588 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 13:52:50.045 10580 10580 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 13:52:50.110  2904  2904 D libEGL  : eglInitialize EGLDisplay = 0xbe8e840c
,06-30 13:52:50.125  3607  5753 V WindowStateAnimator: Finishing drawing window Window{430c917 u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
,06-30 13:52:50.130 10580 10580 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6fd671d time:147967
,06-30 13:52:50.135  3607  3850 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 13:52:50.135  3607  3607 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 13:52:50.140  3607  3607 I KnoxTimeoutHandler: SD activityfalse
,06-30 13:52:50.145  3607  3850 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +389ms (total +723ms)
,06-30 13:52:50.145  3607  3850 D ActivityManager: mDVFSHelper.release()
06-30 13:52:50.145  3607  3850 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6e0e06c u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69} time:147982
,06-30 13:52:50.520  3607  4494 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/69_task.xml.bak
,06-30 13:52:50.965  4700  4700 D Recents : onTaskStackChanged
,06-30 13:52:52.320  3607  6660 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:12), CUR = 139, LCD = 0
,06-30 13:52:54.310  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:52:55.370 10186 10365 V xAnalytics: xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,06-30 13:52:55.830  3607  6660 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 13:52:56.845  3607  5761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:52:56.845  3607  5761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:52:56.845  3607  5761 D BatteryService: online:4, current avg:136, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:155
06-30 13:52:56.845  3607  5761 D BatteryService: stay LED for fully charged
,06-30 13:52:56.845  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:52:56.855  3607  3607 I MotionRecognitionService: Plugged
06-30 13:52:56.855  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:52:56.855  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:52:56.855  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:52:56.860  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:56.860  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:56.865  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:52:56.890  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:56.890  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:56.890  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:52:57.520  3607  3920 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 13:52:57.565  3607  3920 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 13:52:59.995  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 13:53:02.350  3607  6660 D SSRM:n  : SIOP:: AP = 290, PST = 305 (W:12), CUR = 136, LCD = 0
,06-30 13:53:04.840  3607  4400 V AlarmManager: Expired Alarm result :4
,06-30 13:53:04.875  3607  3773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9eedfb3 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f26a11f 5667:com.google.android.gms.persistent/u0a14}
,06-30 13:53:04.895  3607  5052 V AlarmManager:  remove PendingIntent] PendingIntent{ead84e9: PendingIntentRecord{d53804d com.google.android.gms broadcastIntent}}
,06-30 13:53:04.910 10648 10648 E Zygote  : v2
,06-30 13:53:04.910 10648 10648 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:53:04.910 10648 10648 I libpersona: KNOX_SDCARD not a persona
06-30 13:53:04.910  3607  4400 I ActivityManager: Start proc 10648:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,06-30 13:53:04.915 10648 10648 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,06-30 13:53:04.915  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 13:53:04.915  4505  4505 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 13:53:04.915  4505  4505 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:53:04.915 10648 10648 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 13:53:04.920 10648 10648 E Zygote  : accessInfo : 0
,06-30 13:53:04.925  4505  4505 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:53:04.930  4505  4505 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:53:04.935  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:04.935  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:04.935  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
06-30 13:53:04.935  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:04.940  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:04.940  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:04.940  4505  4505 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:04.955 10648 10648 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:53:04.955 10648 10648 D ActivityThread: Added TimaKeyStore provider
,06-30 13:53:04.985 10648 10648 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,06-30 13:53:05.030  4505  4505 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:53:05.035  3607  5052 I ActivityManager: Killing 9533:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 15): DHA:empty #31
,06-30 13:53:05.085  3607  4728 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,06-30 13:53:06.980  3607  5761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:53:06.980  3607  5761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:53:06.980  3607  5761 D BatteryService: online:4, current avg:150, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:155
06-30 13:53:06.980  3607  5761 D BatteryService: stay LED for fully charged
06-30 13:53:06.985  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:53:06.990  3607  3607 I MotionRecognitionService: Plugged
06-30 13:53:06.990  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:53:06.990  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:53:06.990  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:07.000  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:07.000  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:07.000  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:07.025  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:07.025  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:07.025  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:07.725  3607  5001 E Watchdog: !@Sync 5 [06-30 13:53:07.729]
,06-30 13:53:08.440  5667  6539 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:53:12.390  3607  6660 D SSRM:n  : SIOP:: AP = 280, PST = 299 (W:14), CUR = 150, LCD = 0
,06-30 13:53:14.310  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:17.115  3607  5737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:53:17.115  3607  5737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:53:17.115  3607  5737 D BatteryService: online:4, current avg:151, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:148
06-30 13:53:17.115  3607  5737 D BatteryService: stay LED for fully charged
,06-30 13:53:17.120  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:53:17.125  3607  3607 I MotionRecognitionService: Plugged
06-30 13:53:17.125  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:53:17.125  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:53:17.125  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:17.130  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:17.130  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:17.130  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:17.160  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:17.160  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:17.160  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:22.425  3607  6660 D SSRM:n  : SIOP:: AP = 280, PST = 294 (W:14), CUR = 151, LCD = 0
,06-30 13:53:23.260  3607  6661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,06-30 13:53:23.270  3607  3773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c67e821 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{539332f 9913:com.samsung.android.sm.provider/1000}
,06-30 13:53:23.410  3607  6661 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,06-30 13:53:23.420  3607  3773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3002607 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{539332f 9913:com.samsung.android.sm.provider/1000}
,06-30 13:53:27.260  3607  4551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:53:27.260  3607  4551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:53:27.260  3607  4551 D BatteryService: online:4, current avg:148, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:141
06-30 13:53:27.260  3607  4551 D BatteryService: stay LED for fully charged
,06-30 13:53:27.260  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:53:27.270  3607  3607 I MotionRecognitionService: Plugged
06-30 13:53:27.270  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:53:27.270  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:53:27.270  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:27.275  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:53:27.275  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:53:27.275  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:27.305  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:27.305  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:27.305  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:32.455  3607  6660 D SSRM:n  : SIOP:: AP = 280, PST = 292 (W:14), CUR = 148, LCD = 0
,06-30 13:53:34.315  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:34.890  3607  4400 V AlarmManager: Expired Alarm result :4
,06-30 13:53:34.940  3607  3773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3772ed2 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f26a11f 5667:com.google.android.gms.persistent/u0a14}
,06-30 13:53:34.960  3607  5761 V AlarmManager:  remove PendingIntent] PendingIntent{26f1ba3: PendingIntentRecord{d53804d com.google.android.gms broadcastIntent}}
,06-30 13:53:35.675  5667  5667 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=e1f33800-3c39-4cba-938e-4ea6dc59a1e8
,06-30 13:53:35.715  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:53:35.720  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:53:35.885  5667  5899 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 13:53:35.885  5845 10706 D UdcContextInitService: registered all accounts: true
,06-30 13:53:35.900  5667  5962 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 13:53:35.930  3607  3619 I art     : Background partial concurrent mark sweep GC freed 49956(3MB) AllocSpace objects, 46(920KB) LOS objects, 33% free, 30MB/45MB, paused 2.195ms total 167.800ms
,06-30 13:53:36.000  5667  5962 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10014, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 13:53:36.000  3607  4915 V AlarmManager:  remove PendingIntent] PendingIntent{42a1939: PendingIntentRecord{d53804d com.google.android.gms broadcastIntent}}
,06-30 13:53:36.115  5667  5667 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 13:53:36.120  5667 10732 I VacuumService: Vacuum at: now=1467287616124 tag=VacuumService
,06-30 13:53:36.265  3607  4551 V AlarmManager:  remove PendingIntent] PendingIntent{45eb8df: PendingIntentRecord{d53804d com.google.android.gms broadcastIntent}}
,06-30 13:53:37.410  3607  5103 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:53:37.410  3607  5103 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:53:37.410  3607  5103 D BatteryService: online:4, current avg:145, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:149
06-30 13:53:37.410  3607  5103 D BatteryService: stay LED for fully charged
,06-30 13:53:37.410  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:53:37.415  3607  3607 I MotionRecognitionService: Plugged
06-30 13:53:37.415  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:53:37.415  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:53:37.415  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:37.425  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:37.425  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:37.425  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:37.450  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:37.450  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:37.450  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:37.735  3607  5001 E Watchdog: !@Sync 6 [06-30 13:53:37.735]
,06-30 13:53:37.835  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:53:37.835  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:53:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:53:42.195  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 13:53:42.490  3607  6660 D SSRM:n  : SIOP:: AP = 280, PST = 292 (W:14), CUR = 145, LCD = 0
,06-30 13:53:47.550  3607  4915 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:53:47.550  3607  4915 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:53:47.550  3607  4915 D BatteryService: online:4, current avg:142, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:139
06-30 13:53:47.550  3607  4915 D BatteryService: stay LED for fully charged
,06-30 13:53:47.555  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:53:47.560  3607  3607 I MotionRecognitionService: Plugged
06-30 13:53:47.560  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:53:47.560  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:53:47.560  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:47.565  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:47.565  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:47.565  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:47.590  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:47.590  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:47.590  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:53:52.515  3607  6660 D SSRM:n  : SIOP:: AP = 280, PST = 291 (W:16), CUR = 142, LCD = 0
,06-30 13:53:54.315  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:53:57.685  3607  4546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:53:57.685  3607  4546 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
,06-30 13:53:57.685  3607  4546 D BatteryService: online:4, current avg:137, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:136
06-30 13:53:57.685  3607  4546 D BatteryService: stay LED for fully charged
06-30 13:53:57.690  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:53:57.695  3607  3607 I MotionRecognitionService: Plugged
06-30 13:53:57.695  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:53:57.695  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:53:57.695  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:53:57.700  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:57.700  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:53:57.700  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:53:57.730  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:57.730  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:53:57.730  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:00.000  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 13:54:02.550  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 289 (W:16), CUR = 137, LCD = 0
,06-30 13:54:07.740  3607  5001 E Watchdog: !@Sync 7 [06-30 13:54:07.743]
,06-30 13:54:07.825  3607  4915 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:54:07.825  3607  4915 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:54:07.825  3607  4915 D BatteryService: online:4, current avg:134, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:127
06-30 13:54:07.825  3607  4915 D BatteryService: stay LED for fully charged
,06-30 13:54:07.830  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:54:07.835  3607  3607 I MotionRecognitionService: Plugged
06-30 13:54:07.835  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:54:07.835  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:54:07.835  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:07.840  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:54:07.840  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:07.840  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:07.865  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:07.865  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:07.865  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:12.590  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 287 (W:16), CUR = 134, LCD = 0
,06-30 13:54:14.320  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:17.960  3607  4546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:54:17.965  3607  4546 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:54:17.965  3607  4546 D BatteryService: online:4, current avg:131, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:133
06-30 13:54:17.965  3607  4546 D BatteryService: stay LED for fully charged
,06-30 13:54:17.965  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:54:17.970  3607  3607 I MotionRecognitionService: Plugged
06-30 13:54:17.970  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:54:17.970  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:54:17.970  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:17.975  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:17.975  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:54:17.975  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:18.005  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:18.005  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:18.005  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:22.625  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:16), CUR = 131, LCD = 0
,06-30 13:54:28.105  3607  4915 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:54:28.105  3607  4915 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:54:28.105  3607  4915 D BatteryService: online:4, current avg:128, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:125
06-30 13:54:28.105  3607  4915 D BatteryService: stay LED for fully charged
,06-30 13:54:28.110  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:54:28.115  3607  3607 I MotionRecognitionService: Plugged
06-30 13:54:28.115  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:54:28.115  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:54:28.115  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:28.125  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:28.125  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:28.125  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:28.150  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:28.155  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:28.155  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:32.650  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:18), CUR = 128, LCD = 0
,06-30 13:54:34.325  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:36.185  5667  5962 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:36.185  5667  5962 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 13:54:36.185  5667  5962 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 13:54:36.185  5667  5962 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 13:54:36.185  5667  5962 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 13:54:36.210  5667  5962 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 13:54:36.455  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 13:54:37.745  3607  5001 E Watchdog: !@Sync 8 [06-30 13:54:37.744]
,06-30 13:54:37.940  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:54:37.940  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:54:38.030  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 85ms lastUpdatedAfter : 140027ms
,06-30 13:54:38.235  3607  3630 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:54:38.235  3607  3630 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:54:38.235  3607  3630 D BatteryService: online:4, current avg:127, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:123
06-30 13:54:38.235  3607  3630 D BatteryService: stay LED for fully charged
06-30 13:54:38.235  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:38.240  3607  3607 I MotionRecognitionService: Plugged
06-30 13:54:38.240  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:54:38.240  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:54:38.240  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:38.240  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:54:38.240  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:38.240  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:38.265  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:38.265  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:38.265  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:54:42.685  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:18), CUR = 127, LCD = 0
,06-30 13:54:48.350  3607  5098 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:54:48.350  3607  5098 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:54:48.350  3607  5098 D BatteryService: online:4, current avg:126, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:127
06-30 13:54:48.350  3607  5098 D BatteryService: stay LED for fully charged
,06-30 13:54:48.350  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:54:48.360  3607  3607 I MotionRecognitionService: Plugged
06-30 13:54:48.360  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:54:48.360  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:54:48.360  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:48.365  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:48.365  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:48.365  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:48.390  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:48.390  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:48.390  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:54:52.715  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:18), CUR = 126, LCD = 0
,06-30 13:54:54.330  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:54:58.495  3607  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:54:58.495  3607  5053 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:54:58.495  3607  5053 D BatteryService: online:4, current avg:124, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:125
06-30 13:54:58.495  3607  5053 D BatteryService: stay LED for fully charged
,06-30 13:54:58.495  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:54:58.500  3607  3607 I MotionRecognitionService: Plugged
06-30 13:54:58.500  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:54:58.500  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:54:58.500  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:54:58.510  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:54:58.510  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:54:58.510  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:54:58.530  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:58.535  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:54:58.535  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:02.745  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:18), CUR = 124, LCD = 0
,06-30 13:55:07.750  3607  5001 E Watchdog: !@Sync 9 [06-30 13:55:07.751]
,06-30 13:55:12.785  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:20), CUR = 124, LCD = 0
,06-30 13:55:14.330  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:22.820  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:20), CUR = 124, LCD = 0
,06-30 13:55:28.590  3607  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:55:28.590  3607  5053 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4379, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:55:28.590  3607  5053 D BatteryService: online:4, current avg:8, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:55:28.590  3607  5053 D BatteryService: stay LED for fully charged
,06-30 13:55:28.590  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:55:28.595  3607  3607 I MotionRecognitionService: Plugged
06-30 13:55:28.595  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:55:28.595  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:55:28.595  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:28.605  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:55:28.605  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:55:28.605  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:28.630  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:28.630  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:28.630  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:55:32.850  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:20), CUR = 8, LCD = 0
,06-30 13:55:34.320  3607  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 13:55:34.325  3607  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:55:34.335  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:34.340  3607  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:55:34.345  3607  4390 I TLC_TIMA_PKM_initialize: initializing...
06-30 13:55:34.345  3607  4390 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
06-30 13:55:34.345  3607  4390 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: root = 0, root_len = 1
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: device_id = 0x0
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: tlc_open() was called
06-30 13:55:34.345  3607  4390 I TZ: mc_tlc_communication: Opening MobiCore device
,06-30 13:55:34.355  3607  4390 I TZ: mc_tlc_communication: Allocating message buffer for TCI,
,06-30 13:55:34.360  3607  4390 I TZ: mc_tlc_communication: Opening the session
,06-30 13:55:34.380  3607  4390 I TZ: mc_tlc_communication: tlc_open() succeeded
,06-30 13:55:34.395  3607  4390 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 13:55:37.755  3607  5001 E Watchdog: !@Sync 10 [06-30 13:55:37.758]
,06-30 13:55:38.150  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:55:38.150  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:55:38.330  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:55:41.365  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 13:55:41.365  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:55:41.380  3607  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 13:55:41.385  3607  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:55:42.895  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:20), CUR = 8, LCD = 0
,06-30 13:55:52.930  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:22), CUR = 8, LCD = 0
,06-30 13:55:54.335  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:55:58.685  3607  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:55:58.685  3607  5053 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4379, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:55:58.685  3607  5053 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:55:58.685  3607  5053 D BatteryService: stay LED for fully charged
,06-30 13:55:58.685  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:55:58.690  3607  3607 I MotionRecognitionService: Plugged
06-30 13:55:58.690  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:55:58.690  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:55:58.690  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:55:58.700  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:55:58.700  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:55:58.700  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:55:58.725  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:58.725  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:55:58.725  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:02.970  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:22), LCD = 0
,06-30 13:56:04.650  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:56:04.670  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:56:04.675  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:56:04.715  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:56:04.715  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:56:04.720  2915  4369 D EnterpriseController: netId is 0
06-30 13:56:04.720  2915  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 13:56:07.760  3607  5001 E Watchdog: !@Sync 11 [06-30 13:56:07.760]
,06-30 13:56:11.210  3607  4400 V AlarmManager: Expired Alarm result :4
,06-30 13:56:11.230  3607  5082 D NtpTrustedTime: forceRefresh: no connectivity
06-30 13:56:11.230  3607  5082 V AlarmManager:  remove PendingIntent] PendingIntent{92d8be8: PendingIntentRecord{6757201 android broadcastIntent}}
,06-30 13:56:11.255  3607  5082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.NetworkTimeUpdateService.onPollNetworkTimeUnderWakeLock:239 com.android.server.NetworkTimeUpdateService.onPollNetworkTime:177 com.android.server.NetworkTimeUpdateService.access$600:57 com.android.server.NetworkTimeUpdateService$MyHandler.handleMessage:331 
,06-30 13:56:11.255  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 13:56:11.255  4505  4505 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 13:56:11.260  4505  4505 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:56:11.265  4505  4505 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:56:11.270  4505  4505 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:56:11.285  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.285  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.290  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.290  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.290  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.295  4505  4505 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.295  4505  4505 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.315  8672  8672 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
06-30 13:56:11.315  8672  8672 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 13:56:11.315  8672  8672 V GCMBaseIntentService: Acquiring wakelock
,06-30 13:56:11.340  8672  8672 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-10
,06-30 13:56:11.345  8672 10854 V GCMRegistrar: Unregistering app flipboard.app
,06-30 13:56:11.365  8672 10854 V GCMBaseIntentService: Releasing wakelock
,06-30 13:56:11.400  5667  7042 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,06-30 13:56:11.435  5667  7042 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:56:11.435  5667  7042 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 13:56:11.435  2915  4369 D EnterpriseController: netId is 0
06-30 13:56:11.435  2915  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10014
,06-30 13:56:11.455  3607  3773 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ec8fb48 u0 com.google.android.c2dm.intent.REGISTRATION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca793f9 8672:flipboard.app/u0a119}
,06-30 13:56:11.455  8672  8672 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
06-30 13:56:11.455  8672  8672 V GCMBroadcastReceiver: GCM IntentService class: flipboard.gcm.FlipboardGCMIntentService
06-30 13:56:11.455  8672  8672 V GCMBaseIntentService: Acquiring wakelock
,06-30 13:56:11.485  8672  8672 V GCMBaseIntentService: Intent service name: GCMIntentService-334069016917-11
,06-30 13:56:11.485  8672 10858 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
06-30 13:56:11.485  8672 10858 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
06-30 13:56:11.485  8672 10858 D GCMBaseIntentService: Scheduling registration retry, backoff = 250544 (192000)
,06-30 13:56:11.530  4505  4505 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 13:56:11.585  8672 10858 V GCMBaseIntentService: Releasing wakelock
,06-30 13:56:13.005  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), LCD = 0
,06-30 13:56:14.340  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:23.030  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), LCD = 0
,06-30 13:56:28.780  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:56:28.785  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:56:28.785  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:56:28.785  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:56:28.790  3607  4916 D BatteryService: stay LED for fully charged
,06-30 13:56:28.790  3607  3607 I MotionRecognitionService: Plugged
06-30 13:56:28.790  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:56:28.790  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:56:28.790  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:56:28.800  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:56:28.800  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:28.800  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:28.825  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:56:28.825  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:56:28.825  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:33.065  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,06-30 13:56:34.345  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:37.765  3607  5001 E Watchdog: !@Sync 12 [06-30 13:56:37.767]
,06-30 13:56:38.270  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:56:38.270  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:56:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:56:43.090  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,06-30 13:56:53.115  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,06-30 13:56:54.345  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:56:58.875  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:56:58.875  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:56:58.875  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:56:58.875  3607  4916 D BatteryService: stay LED for fully charged
,06-30 13:56:58.875  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:56:58.880  3607  3607 I MotionRecognitionService: Plugged
06-30 13:56:58.880  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:56:58.880  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:56:58.880  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:56:58.890  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:56:58.890  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:56:58.890  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:56:58.915  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:56:58.915  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:56:58.915  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:56:59.995  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 13:57:03.140  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,06-30 13:57:07.770  3607  5001 E Watchdog: !@Sync 13 [06-30 13:57:07.769]
,06-30 13:57:13.175  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,06-30 13:57:14.350  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:23.210  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,06-30 13:57:28.970  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:57:28.970  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:57:28.970  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:57:28.970  3607  4916 D BatteryService: stay LED for fully charged
,06-30 13:57:28.970  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:57:28.980  3607  3607 I MotionRecognitionService: Plugged
06-30 13:57:28.980  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:57:28.980  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:57:28.980  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:57:28.985  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:57:28.990  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:57:28.990  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:29.010  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:29.010  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:29.010  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:57:33.235  3607  6660 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,06-30 13:57:34.350  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:37.775  3607  5001 E Watchdog: !@Sync 14 [06-30 13:57:37.777]
,06-30 13:57:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:57:38.375  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:57:38.375  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:57:38.440  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 57ms lastUpdatedAfter : 180411ms
,06-30 13:57:43.270  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:26), LCD = 0
,06-30 13:57:53.300  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:28), LCD = 0
,06-30 13:57:54.355  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:57:59.070  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:57:59.070  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:57:59.070  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
,06-30 13:57:59.075  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:57:59.080  3607  3607 I MotionRecognitionService: Plugged
06-30 13:57:59.080  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:57:59.080  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:57:59.080  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:57:59.090  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:57:59.090  3607  4916 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 17ms
06-30 13:57:59.090  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:57:59.090  3607  4916 D BatteryService: stay LED for fully charged,
06-30 13:57:59.090  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:57:59.110  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:59.110  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:57:59.110  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:58:03.335  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:28), LCD = 0
,06-30 13:58:07.785  3607  5001 E Watchdog: !@Sync 15 [06-30 13:58:07.784]
,06-30 13:58:13.375  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:28), LCD = 0
,06-30 13:58:14.355  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:23.400  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:28), LCD = 0
,06-30 13:58:26.700  2971  2971 I bootchecker: bootchecker wake up!!
,06-30 13:58:29.170  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:58:33.435  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), LCD = 0
,06-30 13:58:34.360  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:37.790  3607  5001 E Watchdog: !@Sync 16 [06-30 13:58:37.791]
,06-30 13:58:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:58:38.550  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:58:38.550  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:58:43.465  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,06-30 13:58:53.500  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,06-30 13:58:54.360  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:58:59.255  3607  5185 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:58:59.255  3607  5185 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:58:59.255  3607  5185 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:58:59.255  3607  5185 D BatteryService: stay LED for fully charged
,06-30 13:58:59.260  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:58:59.265  3607  3607 I MotionRecognitionService: Plugged
06-30 13:58:59.265  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:58:59.265  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:58:59.265  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:58:59.270  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:58:59.270  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:58:59.270  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:58:59.300  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:59.300  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:58:59.300  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:03.545  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,06-30 13:59:07.800  3607  5001 E Watchdog: !@Sync 17 [06-30 13:59:07.800]
,06-30 13:59:13.585  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,06-30 13:59:14.370  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:23.615  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,06-30 13:59:29.350  3607  5185 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:59:29.350  3607  5185 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 13:59:29.350  3607  5185 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 13:59:29.350  3607  5185 D BatteryService: stay LED for fully charged
06-30 13:59:29.355  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:59:29.360  3607  3607 I MotionRecognitionService: Plugged
06-30 13:59:29.360  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 13:59:29.360  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 13:59:29.360  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 13:59:29.370  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:59:29.370  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:59:29.370  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:59:29.395  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:29.395  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:59:29.395  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:59:33.640  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,06-30 13:59:34.370  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:37.805  3607  5001 E Watchdog: !@Sync 18 [06-30 13:59:37.805]
,06-30 13:59:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 13:59:38.675  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 13:59:38.675  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 13:59:43.675  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,06-30 13:59:53.705  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,06-30 13:59:54.375  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:59:59.445  3607  5185 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:03.735  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), LCD = 0
,06-30 14:00:07.810  3607  5001 E Watchdog: !@Sync 19 [06-30 14:00:07.811]
,06-30 14:00:13.780  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), LCD = 0
,06-30 14:00:14.375  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:22.035  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 14:00:23.805  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), LCD = 0
,06-30 14:00:29.540  3607  4546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:00:29.540  3607  4546 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:00:29.540  3607  4546 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:00:29.540  3607  4546 D BatteryService: stay LED for fully charged
06-30 14:00:29.545  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:00:29.550  3607  3607 I MotionRecognitionService: Plugged
06-30 14:00:29.550  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:00:29.555  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:00:29.555  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:00:29.560  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:00:29.560  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:00:29.560  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:00:29.580  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:00:29.585  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:00:29.585  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:00:33.835  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,06-30 14:00:34.320  3607  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 14:00:34.320  3607  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:00:34.325  3607  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:00:34.375  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:37.815  3607  5001 E Watchdog: !@Sync 20 [06-30 14:00:37.818]
,06-30 14:00:38.075  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 14:00:38.075  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:00:38.090  3607  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 14:00:38.090  3607  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:00:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:00:38.785  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:00:38.785  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:00:38.860  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 62ms lastUpdatedAfter : 180416ms
,06-30 14:00:40.500  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:40.505  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLoc,ked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 14:00:40.510  3607  3763 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 14:00:40.645  3607  3850 I ActivityManager: setMaxStartingBackgroundTimer onfinish
06-30 14:00:40.645  3607  3850 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 14:00:43.880  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,06-30 14:00:53.920  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,06-30 14:00:54.380  3607  6722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 14:00:59.635  3607  4546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:00:59.635  3607  4546 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:00:59.635  3607  4546 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:00:59.635  3607  4546 D BatteryService: stay LED for fully charged
,06-30 14:00:59.640  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:00:59.645  3607  3607 I MotionRecognitionService: Plugged
06-30 14:00:59.645  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:00:59.645  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:00:59.645  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:00:59.655  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:00:59.655  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:00:59.655  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:00:59.675  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:00:59.675  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:00:59.675  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:03.960  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,06-30 14:01:04.840  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:04.860  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:04.865  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:01:04.905  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 14:01:04.905  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:01:04.905  2915  4369 D EnterpriseController: netId is 0
06-30 14:01:04.905  2915  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 14:01:07.830  3607  5001 E Watchdog: !@Sync 21 [06-30 14:01:07.830]
,06-30 14:01:11.980  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 14:01:13.995  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,06-30 14:01:24.035  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,06-30 14:01:29.730  3607  5761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:01:29.730  3607  5761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:01:29.730  3607  5761 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:01:29.730  3607  5761 D BatteryService: stay LED for fully charged
,06-30 14:01:29.730  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:01:29.735  3607  3607 I MotionRecognitionService: Plugged
06-30 14:01:29.735  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:01:29.735  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:01:29.735  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:01:29.745  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:01:29.745  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:01:29.745  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:01:29.775  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:01:29.775  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:01:29.775  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:01:34.080  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:01:37.835  3607  5001 E Watchdog: !@Sync 22 [06-30 14:01:37.837]
,06-30 14:01:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:01:38.965  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:01:38.965  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:01:44.120  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:01:54.145  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:01:59.825  3607  5761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:01:59.825  3607  5761 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:01:59.825  3607  5761 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:01:59.825  3607  5761 D BatteryService: stay LED for fully charged
,06-30 14:01:59.825  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:01:59.830  3607  3607 I MotionRecognitionService: Plugged
06-30 14:01:59.830  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:01:59.830  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:01:59.830  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:01:59.840  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:01:59.840  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:01:59.840  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:01:59.870  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:01:59.870  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:01:59.870  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:02:04.175  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:02:07.840  3607  5001 E Watchdog: !@Sync 23 [06-30 14:02:07.840]
,06-30 14:02:14.200  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:02:24.235  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:02:29.915  3607  5761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:02:34.275  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:02:37.845  3607  5001 E Watchdog: !@Sync 24 [06-30 14:02:37.844]
,06-30 14:02:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:02:39.100  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:02:39.100  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:02:44.310  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:02:54.340  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:03:00.015  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:03:00.015  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:03:00.015  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:03:00.015  3607  4916 D BatteryService: stay LED for fully charged
06-30 14:03:00.020  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:03:00.025  3607  3607 I MotionRecognitionService: Plugged
06-30 14:03:00.025  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:03:00.025  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:03:00.025  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:03:00.035  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:03:00.035  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:03:00.035  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:00.055  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:00.055  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:00.055  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:04.375  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0,
,06-30 14:03:07.850  3607  5001 E Watchdog: !@Sync 25 [06-30 14:03:07.851]
,06-30 14:03:14.405  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:03:24.430  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:03:30.105  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:03:30.105  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:03:30.105  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:03:30.105  3607  4916 D BatteryService: stay LED for fully charged
,06-30 14:03:30.110  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:03:30.110  3607  3607 I MotionRecognitionService: Plugged
06-30 14:03:30.110  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:03:30.110  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:03:30.110  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:03:30.135  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:30.135  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:03:30.145  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:30.145  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:03:30.145  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:03:30.145  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:03:34.475  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:03:37.855  3607  5001 E Watchdog: !@Sync 26 [06-30 14:03:37.857]
,06-30 14:03:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:03:39.195  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:03:39.195  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:03:39.260  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 56ms lastUpdatedAfter : 180401ms
,06-30 14:03:40.695  3607  5760 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 14:03:40.700  3607  5760 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 14:03:40.700  3607  5760 V MARsPolicyManager: updateSMDBValues
,06-30 14:03:40.705  3607  3845 E MARsDBManager: updateDBAll : begin --size 1
,06-30 14:03:40.755  3607  3845 E MARsDBManager: updateDBAll : end
,06-30 14:03:40.755  3607  3845 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 14:03:44.515  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:03:54.545  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:04:00.195  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:04:00.200  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:04:00.200  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:04:00.200  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:04:00.200  3607  4916 D BatteryService: stay LED for fully charged
,06-30 14:04:00.205  3607  3607 I MotionRecognitionService: Plugged
06-30 14:04:00.205  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:04:00.205  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 14:04:00.205  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:04:00.215  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:04:00.215  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:04:00.215  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:04:00.240  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:04:00.240  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:04:00.240  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:04.585  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:04:07.860  3607  5001 E Watchdog: !@Sync 27 [06-30 14:04:07.864]
,06-30 14:04:14.615  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:04:24.645  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:04:30.295  3607  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:04:30.300  3607  4916 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:04:30.300  3607  4916 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:04:30.300  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:04:30.305  3607  4916 D BatteryService: stay LED for fully charged
,06-30 14:04:30.305  3607  3607 I MotionRecognitionService: Plugged
06-30 14:04:30.305  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:04:30.305  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:04:30.305  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:04:30.315  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:04:30.315  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:04:30.315  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:04:30.340  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:04:30.340  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:04:30.340  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:04:34.680  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:04:37.870  3607  5001 E Watchdog: !@Sync 28 [06-30 14:04:37.871]
,06-30 14:04:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:04:39.365  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:04:39.365  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:04:44.710  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:04:54.740  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:05:00.385  3607  5761 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:05:04.780  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:05:07.870  3607  5001 E Watchdog: !@Sync 29 [06-30 14:05:07.873]
,06-30 14:05:14.810  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:05:24.845  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:05:30.480  3607  5098 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:05:30.480  3607  5098 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:05:30.480  3607  5098 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:05:30.480  3607  5098 D BatteryService: stay LED for fully charged
,06-30 14:05:30.485  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:05:30.490  3607  3607 I MotionRecognitionService: Plugged
06-30 14:05:30.490  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:05:30.490  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:05:30.490  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:05:30.500  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:05:30.500  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:05:30.500  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:05:30.525  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:05:30.525  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:05:30.525  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:05:34.320  3607  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 14:05:34.320  3607  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:05:34.325  3607  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:05:34.890  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:05:37.875  3607  5001 E Watchdog: !@Sync 30 [06-30 14:05:37.878]
,06-30 14:05:38.330  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:05:39.510  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:05:39.510  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:05:41.590  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 14:05:41.590  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:05:41.605  3607  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 14:05:41.605  3607  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:05:44.915  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:05:54.975  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:05:55.045  3607  3619 I art     : Background sticky concurrent mark sweep GC freed 52453(7MB) AllocSpace objects, 369(7MB) LOS objects, 32% free, 30MB/45MB, paused 7.070ms total 108.903ms
,06-30 14:06:00.575  3607  5098 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:06:00.580  3607  5098 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:06:00.580  3607  5098 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:06:00.580  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:06:00.580  3607  5098 D BatteryService: stay LED for fully charged
,06-30 14:06:00.585  3607  3607 I MotionRecognitionService: Plugged
06-30 14:06:00.585  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:06:00.590  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:06:00.590  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:06:00.595  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:06:00.595  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:06:00.600  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:06:00.620  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:06:00.620  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:06:00.620  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:05.005  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:06:05.070  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:05.090  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:05.090  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:06:05.145  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 14:06:05.145  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:06:05.145  2915  4369 D EnterpriseController: netId is 0
06-30 14:06:05.145  2915  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 14:06:07.880  3607  5001 E Watchdog: !@Sync 31 [06-30 14:06:07.880]
,06-30 14:06:10.895  3607  4400 V AlarmManager: Expired Alarm result :8
,06-30 14:06:10.995  3607  3773 W ProcessCpuTracker: Skipping unknown process pid 11098
,06-30 14:06:15.035  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:06:25.075  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:06:30.680  3607  5754 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:06:30.680  3607  5754 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:06:30.680  3607  5754 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:06:30.680  3607  5754 D BatteryService: stay LED for fully charged
,06-30 14:06:30.685  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:06:30.690  3607  3607 I MotionRecognitionService: Plugged
06-30 14:06:30.690  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:06:30.690  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:06:30.690  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:06:30.695  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:06:30.695  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:06:30.700  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:06:30.720  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:06:30.720  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:30.725  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:06:35.120  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:06:37.885  3607  5001 E Watchdog: !@Sync 32 [06-30 14:06:37.887]
,06-30 14:06:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:06:39.620  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:06:39.620  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:06:39.680  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 51ms lastUpdatedAfter : 180421ms
,06-30 14:06:45.165  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:06:55.195  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:07:00.770  3607  5754 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:00.770  3607  5754 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:07:00.770  3607  5754 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:07:00.770  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:07:00.770  3607  5754 D BatteryService: stay LED for fully charged
,06-30 14:07:00.780  3607  3607 I MotionRecognitionService: Plugged
06-30 14:07:00.780  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:07:00.780  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:07:00.780  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:07:00.785  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:07:00.785  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:07:00.785  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:07:00.815  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:07:00.815  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:07:00.815  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:07:05.225  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:07:07.890  3607  5001 E Watchdog: !@Sync 33 [06-30 14:07:07.893]
,06-30 14:07:15.255  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:07:25.295  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:07:30.870  3607  5754 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:07:35.325  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:07:37.900  3607  5001 E Watchdog: !@Sync 34 [06-30 14:07:37.900]
,06-30 14:07:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:07:39.785  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:07:39.785  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:07:45.370  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:07:55.400  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:08:00.955  3607  5185 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:08:00.955  3607  5185 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:08:00.955  3607  5185 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:08:00.955  3607  5185 D BatteryService: stay LED for fully charged
06-30 14:08:00.955  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:08:00.960  3607  3607 I MotionRecognitionService: Plugged
06-30 14:08:00.960  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:08:00.965  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:08:00.965  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:08:00.965  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:08:00.965  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:08:00.965  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:00.985  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:00.990  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:00.990  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:05.425  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:08:07.910  3607  5001 E Watchdog: !@Sync 35 [06-30 14:08:07.909]
,06-30 14:08:15.455  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:08:25.500  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:08:31.050  3607  5185 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:08:31.050  3607  5185 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:08:31.050  3607  5185 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:08:31.050  3607  5185 D BatteryService: stay LED for fully charged
,06-30 14:08:31.050  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:08:31.055  3607  3607 I MotionRecognitionService: Plugged
06-30 14:08:31.055  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:08:31.055  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:08:31.055  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:08:31.060  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:08:31.065  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:08:31.065  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:08:31.090  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:31.090  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:08:31.090  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:08:35.540  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:08:37.915  3607  5001 E Watchdog: !@Sync 36 [06-30 14:08:37.917]
,06-30 14:08:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:08:39.925  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:08:39.925  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:08:45.575  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:08:55.625  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:09:01.140  3607  5185 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:09:01.140  3607  5185 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:09:01.140  3607  5185 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:09:01.140  3607  5185 D BatteryService: stay LED for fully charged
,06-30 14:09:01.145  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:09:01.150  3607  3607 I MotionRecognitionService: Plugged
06-30 14:09:01.150  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:09:01.150  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:09:01.150  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:09:01.155  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:09:01.155  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:09:01.155  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:09:01.185  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:01.185  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:09:01.185  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:09:05.665  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:09:07.920  3607  5001 E Watchdog: !@Sync 37 [06-30 14:09:07.922]
,06-30 14:09:15.700  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:09:25.745  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:09:31.235  3607  5185 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:09:35.785  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:09:37.925  3607  5001 E Watchdog: !@Sync 38 [06-30 14:09:37.926]
,06-30 14:09:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:09:40.045  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:09:40.045  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:09:40.110  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 59ms lastUpdatedAfter : 180431ms
,06-30 14:09:45.825  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:09:55.870  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:10:01.330  3607  4546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:10:05.910  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:10:07.930  3607  5001 E Watchdog: !@Sync 39 [06-30 14:10:07.933]
,06-30 14:10:15.955  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:10:25.995  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:10:31.430  3607  4915 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:10:31.430  3607  4915 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:10:31.430  3607  4915 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:10:31.430  3607  4915 D BatteryService: stay LED for fully charged
,06-30 14:10:31.430  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:10:31.435  3607  3607 I MotionRecognitionService: Plugged
06-30 14:10:31.435  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:10:31.435  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:10:31.435  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:10:31.440  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:10:31.445  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:10:31.445  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:10:31.470  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:10:31.470  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:10:31.470  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:10:34.320  3607  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 14:10:34.320  3607  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
06-30 14:10:34.325  3607  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:10:34.730  3607  3763 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:10:36.045  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:10:37.915  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 14:10:37.915  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:10:37.930  3607  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 14:10:37.935  3607  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:10:37.935  3607  5001 E Watchdog: !@Sync 40 [06-30 14:10:37.939]
,06-30 14:10:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:10:40.220  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:10:40.220  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:10:46.090  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:10:56.130  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:11:01.530  3607  4915 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:11:01.530  3607  4915 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:11:01.530  3607  4915 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:11:01.530  3607  4915 D BatteryService: stay LED for fully charged
,06-30 14:11:01.530  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:11:01.535  3607  3607 I MotionRecognitionService: Plugged
06-30 14:11:01.535  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:11:01.535  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:11:01.535  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:11:01.545  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:11:01.545  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:11:01.545  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:11:01.570  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:11:01.570  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:11:01.570  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:05.300  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:11:05.320  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:11:05.320  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:11:05.365  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:11:05.365  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:11:05.365  2915  4369 D EnterpriseController: netId is 0
06-30 14:11:05.365  2915  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 14:11:06.180  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:11:07.940  3607  5001 E Watchdog: !@Sync 41 [06-30 14:11:07.940]
,06-30 14:11:16.220  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:11:26.250  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:11:31.620  3607  3629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:11:31.620  3607  3629 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:11:31.620  3607  3629 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:11:31.620  3607  3629 D BatteryService: stay LED for fully charged
,06-30 14:11:31.625  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:11:31.630  3607  3607 I MotionRecognitionService: Plugged
06-30 14:11:31.630  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:11:31.630  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:11:31.630  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:11:31.635  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:11:31.635  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:11:31.635  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:11:31.660  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:11:31.660  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:11:31.660  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:11:36.295  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:11:37.945  3607  5001 E Watchdog: !@Sync 42 [06-30 14:11:37.947]
,06-30 14:11:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:11:40.330  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:11:40.330  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:11:46.340  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:11:56.380  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:12:01.720  3607  3629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:12:01.720  3607  3629 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:12:01.720  3607  3629 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:12:01.720  3607  3629 D BatteryService: stay LED for fully charged
06-30 14:12:01.720  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:12:01.725  3607  3607 I MotionRecognitionService: Plugged
06-30 14:12:01.725  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:12:01.725  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:12:01.725  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:12:01.730  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:12:01.730  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:12:01.730  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:12:01.755  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:01.755  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:01.755  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:06.430  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:12:07.950  3607  5001 E Watchdog: !@Sync 43 [06-30 14:12:07.951]
,06-30 14:12:16.475  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:12:26.500  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:12:31.810  3607  3629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:12:31.810  3607  3629 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:12:31.810  3607  3629 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:12:31.810  3607  3629 D BatteryService: stay LED for fully charged
,06-30 14:12:31.810  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:12:31.820  3607  3607 I MotionRecognitionService: Plugged
06-30 14:12:31.820  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:12:31.820  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:12:31.820  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:12:31.830  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:12:31.830  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:12:31.830  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:12:31.850  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:31.850  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:12:31.850  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:12:36.545  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:12:37.955  3607  5001 E Watchdog: !@Sync 44 [06-30 14:12:37.955]
,06-30 14:12:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:12:40.450  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:12:40.450  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:12:40.525  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 63ms lastUpdatedAfter : 180412ms
,06-30 14:12:46.595  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:12:56.645  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:13:01.905  3607  3629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:06.695  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:13:07.960  3607  5001 E Watchdog: !@Sync 45 [06-30 14:13:07.959]
,06-30 14:13:16.740  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:13:26.775  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:13:32.005  3607  5053 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:13:36.810  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:13:37.965  3607  5001 E Watchdog: !@Sync 46 [06-30 14:13:37.966]
,06-30 14:13:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:13:40.615  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:13:40.615  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:13:46.850  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:13:56.880  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:14:02.090  3607  4551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:14:02.090  3607  4551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:14:02.090  3607  4551 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:14:02.095  3607  4551 D BatteryService: stay LED for fully charged
,06-30 14:14:02.095  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:14:02.100  3607  3607 I MotionRecognitionService: Plugged
06-30 14:14:02.100  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:14:02.100  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:14:02.100  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:14:02.105  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:14:02.105  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:14:02.110  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate,
,06-30 14:14:02.135  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:14:02.135  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:14:02.135  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:06.925  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:14:07.975  3607  5001 E Watchdog: !@Sync 47 [06-30 14:14:07.977]
,06-30 14:14:16.975  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:14:27.025  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:14:32.185  3607  4551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:14:32.185  3607  4551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
,06-30 14:14:32.185  3607  4551 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:14:32.185  3607  4551 D BatteryService: stay LED for fully charged
06-30 14:14:32.190  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:14:32.195  3607  3607 I MotionRecognitionService: Plugged
06-30 14:14:32.195  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:14:32.195  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:14:32.195  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:14:32.200  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:14:32.205  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:14:32.205  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:14:32.230  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:14:32.230  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:14:32.230  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:14:37.080  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:14:37.980  3607  5001 E Watchdog: !@Sync 48 [06-30 14:14:37.982]
,06-30 14:14:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:14:40.760  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:14:40.760  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:14:47.130  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:14:57.185  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:15:02.285  3607  4551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:15:07.230  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:15:07.990  3607  5001 E Watchdog: !@Sync 49 [06-30 14:15:07.990]
,06-30 14:15:17.280  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:15:27.330  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:15:32.375  3607  3630 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 14:15:32.375  3607  3630 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:15:32.375  3607  3630 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:15:32.375  3607  3630 D BatteryService: stay LED for fully charged
,06-30 14:15:32.375  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 14:15:32.385  3607  3607 I MotionRecognitionService: Plugged
06-30 14:15:32.385  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:15:32.385  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:15:32.385  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:15:32.390  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:15:32.390  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 14:15:32.395  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:15:32.420  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:15:32.420  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:15:32.420  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:15:34.320  3607  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
06-30 14:15:34.320  3607  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 14:15:34.325  3607  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 14:15:37.385  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:15:37.995  3607  5001 E Watchdog: !@Sync 50 [06-30 14:15:37.997]
,06-30 14:15:38.335  2947  5218 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-30 14:15:40.720  3607  5760 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 14:15:40.725  3607  5760 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-30 14:15:40.725  3607  5760 V MARsPolicyManager: updateSMDBValues
,06-30 14:15:40.735  3607  3845 E MARsDBManager: updateDBAll : begin --size 0,
06-30 14:15:40.735  3607  3845 E MARsDBManager: updateDBAll : end,
,06-30 14:15:40.880  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-30 14:15:40.880  4917  4970 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-30 14:15:40.955  4917  4970 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 70ms lastUpdatedAfter : 180430ms
,06-30 14:15:41.385  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
06-30 14:15:41.385  3607  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 14:15:41.400  3607  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
06-30 14:15:41.400  3607  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 14:15:47.430  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:15:57.475  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:16:02.475  3607  3630 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 14:16:02.475  3607  3630 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-30 14:16:02.475  3607  3630 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-30 14:16:02.475  3607  3630 D BatteryService: stay LED for fully charged
06-30 14:16:02.475  3607  3607 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 14:16:02.480  3607  3607 I MotionRecognitionService: Plugged
06-30 14:16:02.480  3607  3607 D MotionRecognitionService:   cableConnection= 1
06-30 14:16:02.480  3607  3607 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 14:16:02.480  3607  3607 D MotionRecognitionService: skip setTransmitPower. 
,06-30 14:16:02.485  4505  4505 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 14:16:02.485  4505  4505 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 14:16:02.485  4505  4505 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 14:16:02.510  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:16:02.510  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 14:16:02.510  4505  4505 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 14:16:05.535  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:16:05.555  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:16:05.555  5667  5667 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 14:16:05.600  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:16:05.600  9215  9247 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 14:16:05.605  2915  4369 D EnterpriseController: netId is 0
06-30 14:16:05.605  2915  4369 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-30 14:16:07.520  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,06-30 14:16:08.005  3607  5001 E Watchdog: !@Sync 51 [06-30 14:16:08.004]
,06-30 14:16:17.570  3607  6660 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,TIME-OUT KILL (timeout was 1400000ms)
```
