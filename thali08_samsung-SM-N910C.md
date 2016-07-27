#### Test 78968685da35147_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
07-27 08:56:50.015  3531  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 08:56:50.020  3531  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 08:56:50.020  3531  5116 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 08:56:50.020  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 08:56:50.020  3531  5116 D BatteryService: stay LED for fully charged
07-27 08:56:50.025  3531  3531 I MotionRecognitionService: Plugged
07-27 08:56:50.025  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 08:56:50.025  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:56:50.025  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
07-27 08:56:50.035  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:56:50.035  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:56:50.035  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:56:50.045  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:50.065  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:50.065  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:56:50.820 10610 10610 I FIPS_bssl: FIPS approved mode (1) | 10610 | app_process
07-27 08:56:50.830 10610 10610 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 08:56:50.830 10610 10610 D AndroidRuntime: CheckJNI is OFF
07-27 08:56:50.830 10610 10610 D AndroidRuntime: readGMSProperty: start
07-27 08:56:50.830 10610 10610 D AndroidRuntime: readGMSProperty: already setted!!
07-27 08:56:50.830 10610 10610 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-27 08:56:50.830 10610 10610 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-27 08:56:50.830 10610 10610 D AndroidRuntime: readGMSProperty: end
07-27 08:56:50.830 10610 10610 D AndroidRuntime: addProductProperty: start
07-27 08:56:50.860 10610 10610 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 08:56:50.885 10610 10610 I Radio-JNI: register_android_hardware_Radio DONE
07-27 08:56:50.890 10610 10610 E AffinityControl: AffinityControl: registerfunction enter
07-27 08:56:50.905 10610 10610 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 08:56:50.950  3531  4439 D GameManagerService: identifyGamePackage. com.test.thalitest
07-27 08:56:50.950  3531  4439 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
07-27 08:56:50.955  3531  4439 D ActivityManager: mDVFSHelper.acquire()
07-27 08:56:50.955  3531  4439 V WindowManager: addAppToken: AppWindowToken{b4c52ac token=Token{7c4285f ActivityRecord{c91c8fe u0 com.test.thalitest/.MainActivity t108}}} to stack=1 task=108 at 0
07-27 08:56:50.970  3531  3802 D SecWifiDisplayUtil: Metadata value : none
07-27 08:56:50.970  3531  3802 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{744b44 V.E...... R.....ID 0,0-0,0}
07-27 08:56:50.975  3531  3802 D ISSUE_DEBUG: InputChannelName : 1dddd62 Starting com.test.thalitest
07-27 08:56:50.975 10628 10628 E Zygote  : v2
07-27 08:56:50.975 10628 10628 I libpersona: KNOX_SDCARD checking this for 10007
07-27 08:56:50.975 10628 10628 I libpersona: KNOX_SDCARD not a persona
07-27 08:56:50.975  3531  4439 I ActivityManager: Start proc 10628:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
07-27 08:56:50.975 10628 10628 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:56:50.975  3531  4439 D InputDispatcher: Focused application set to: xxxx
07-27 08:56:50.975 10628 10628 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:50.980  3531  4439 D InputDispatcher: Focus left window: 6764
07-27 08:56:50.980 10628 10628 E Zygote  : accessInfo : 0
07-27 08:56:50.980  3531  3692 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{56c31b6 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-27 08:56:50.980 10610 10610 D AndroidRuntime: Shutting down VM
07-27 08:56:50.980  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-27 08:56:50.980  4515  4515 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-27 08:56:50.980 10628 10628 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-27 08:56:50.990  2906  2906 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
07-27 08:56:51.005  3531  3802 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3531 uid:1000
07-27 08:56:51.005  3531  3802 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:56:51.005  3531  3802 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3531 uid:1000
07-27 08:56:51.005  3531  3802 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 08:56:51.005  3531  3802 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-27 08:56:51.010 10628 10628 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:56:51.010 10628 10628 D ActivityThread: Added TimaKeyStore provider
07-27 08:56:51.015  3531  5022 V WindowOrientationListener: setCurrentAppOrientation :-1
07-27 08:56:51.015  3531  5022 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-27 08:56:51.015  3531  3692 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1dddd62 u0 d0 Starting com.test.thalitest}
07-27 08:56:51.020  4515  4515 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-27 08:56:51.025  3531  5022 D ActivityManager:  Launching com.test.thalitest, updated priority
07-27 08:56:51.035  3531  3531 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-27 08:56:51.035  3531  3685 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-27 08:56:51.055  2906  4429 D libEGL  : eglTerminate EGLDisplay = 0xb1f7f624
07-27 08:56:51.055  2906  3008 I SurfaceFlinger: id=16 Removed VSBConnecti (7/11)
07-27 08:56:51.055  2906  3010 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/11)
07-27 08:56:51.060  2906  3010 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
07-27 08:56:51.060  2906  3010 D libEGL  : eglTerminate EGLDisplay = 0xb66bf624
07-27 08:56:51.060  2906  3008 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
07-27 08:56:51.060  2906  4429 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
07-27 08:56:51.065  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbed03474
07-27 08:56:51.065  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbed03474
07-27 08:56:51.065  2906  3008 I SurfaceFlinger: id=17 Removed VSBConnecti (4/9)
07-27 08:56:51.070  2906  3008 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/9)
07-27 08:56:51.070  5101  5101 V ActivityThread: updateVisibility : ActivityRecord{9de768b token=android.os.BinderProxy@aa7b99d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 08:56:51.070  5101  5101 D Launcher: onTrimMemory. Level: 20
07-27 08:56:51.075  6764  6764 V ActivityThread: updateVisibility : ActivityRecord{3081178 token=android.os.BinderProxy@8851f65 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-27 08:56:51.075  3531  3802 V WindowStateAnimator: Finishing drawing window Window{1dddd62 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-27 08:56:51.085  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbed03474
07-27 08:56:51.085  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c
,07-27 08:56:51.345  3531  5022 I WindowManager: Screenshot max retries 4 of Token{7c4285f ActivityRecord{c91c8fe u0 com.test.thalitest/.MainActivity t108}} appWin=Window{1dddd62 u0 d0 Starting com.test.thalitest} drawState=2
,07-27 08:56:51.350  3531  3685 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-27 08:56:51.365  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,07-27 08:56:51.390  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:56:51.395  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:56:51.440 10628 10628 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-27 08:56:51.475 10628 10628 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 08:56:51.480 10628 10628 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 7310-7313)
07-27 08:56:51.480 10628 10628 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 08:56:51.495 10628 10642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-27 08:56:51.500 10628 10628 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27bfce0}
07-27 08:56:51.500 10628 10628 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-27 08:56:51.500 10628 10628 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:56:51.510 10628 10628 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-27 08:56:51.525 10628 10643 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,07-27 08:56:51.545 10628 10628 D libEGL  : eglInitialize EGLDisplay = 0xbefb9e7c
,07-27 08:56:51.575  3531  5022 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,07-27 08:56:51.575  3531  5022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,07-27 08:56:51.630 10628 10628 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-27 08:56:51.645 10628 10628 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:56:51.645 10628 10628 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-27 08:56:51.645 10628 10628 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-27 08:56:51.650 10628 10628 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-27 08:56:51.665 10628 10628 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-27 08:56:51.680 10628 10628 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-27 08:56:51.800 10628 10628 D SecWifiDisplayUtil: Metadata value : none
,07-27 08:56:51.810 10628 10628 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{1765a79 I.E...... R.....ID 0,0-0,0}
,07-27 08:56:51.825 10628 10679 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 08:56:51.840  3531  5112 D ISSUE_DEBUG: InputChannelName : a1b3a37 com.test.thalitest/com.test.thalitest.MainActivity
,07-27 08:56:51.845  3531  5110 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-27 08:56:51.845  3531  5110 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 08:56:51.845  3531  3531 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 08:56:51.850  3531  3531 I KnoxTimeoutHandler: Shared devices show user statefalse
07-27 08:56:51.850  3531  3685 W ActivityManager: Activity pause timeout for ActivityRecord{c91c8fe u0 com.test.thalitest/.MainActivity t108}
,07-27 08:56:51.885 10628 10628 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 10628
,07-27 08:56:51.890  3531  5116 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/10628 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:56:51.900 10628 10642 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-27 08:56:51.915 10628 10628 D SecWifiDisplayUtil: Metadata value : none
,07-27 08:56:51.930  2906  2906 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,07-27 08:56:51.955  3531  3557 D InputDispatcher: Focus entered window: 10628
,07-27 08:56:51.965  3531  3802 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3531 uid:1000
07-27 08:56:51.965  3531  3802 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 08:56:51.965  3531  3802 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3531 uid:1000
07-27 08:56:51.965  3531  3802 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 08:56:51.965 10628 10679 D libEGL  : eglInitialize EGLDisplay = 0x9c8ff7c4
07-27 08:56:51.965 10628 10679 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 08:56:51.980 10628 10679 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,07-27 08:56:51.985 10628 10628 V ActivityThread: updateVisibility : ActivityRecord{9692dca token=android.os.BinderProxy@4a76b40 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-27 08:56:51.990 10628 10628 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView),
,07-27 08:56:52.050 10628 10684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:56:52.050 10628 10684 D libEGL  : eglInitialize EGLDisplay = 0x9a17f3ec
,07-27 08:56:52.065  3531  4879 V WindowStateAnimator: Finishing drawing window Window{a1b3a37 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
07-27 08:56:52.065 10628 10628 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,07-27 08:56:52.070 10628 10628 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-27 08:56:52.070  3531  5022 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-27 08:56:52.070  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c
,07-27 08:56:52.070  3531  3802 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 08:56:52.070  3531  3531 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-27 08:56:52.075  3531  3531 I KnoxTimeoutHandler: SD activityfalse
07-27 08:56:52.075  3531  3802 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +726ms (total +1s117ms)
,07-27 08:56:52.075  3531  3802 D ActivityManager: mDVFSHelper.release()
,07-27 08:56:52.075  3531  3802 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c91c8fe u0 com.test.thalitest/.MainActivity t108} time:277908
,07-27 08:56:52.080  3531  3802 D ViewRootImpl: #3 mView = null
,07-27 08:56:52.080  2906  3008 I SurfaceFlinger: id=18 Removed uhalitest (7/9)
,07-27 08:56:52.080  2906  3010 I SurfaceFlinger: id=18 Removed uhalitest (-2/9)
,07-27 08:56:52.085  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbed03474
,07-27 08:56:52.100  3531  5110 V WindowStateAnimator: Finishing drawing window Window{a1b3a37 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,07-27 08:56:52.100 10628 10628 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-27 08:56:52.100 10628 10628 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4a76b40 time:277934
,07-27 08:56:52.105  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c
,07-27 08:56:52.125 10628 10628 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10628
,07-27 08:56:52.300 10628 10628 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:56:52.425 10628 10692 D jxcore_app_log: JniHelper::setJavaVM(0xb4874000), pthread_self() = -1751123664
,07-27 08:56:52.430 10628 10692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:56:52.430 10628 10692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:56:52.430 10628 10692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:56:52.430 10628 10692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:56:52.430 10628 10692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:56:52.430 10628 10692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10c2470 added. We now have 1 listener(s)
,07-27 08:56:52.430 10628 10692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,07-27 08:56:52.435 10628 10692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
07-27 08:56:52.435 10628 10692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:56:52.435 10628 10692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 08:56:52.435 10628 10692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0c2b0f added. We now have 1 listener(s)
07-27 08:56:52.435 10628 10692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 08:56:52.435 10628 10692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:56:52.435 10628 10692 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:56:52.440 10628 10692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 08:56:52.440 10628 10692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:56:52.440 10628 10692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:56:52.440 10628 10692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:56:52.440 10628 10692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:56:52.440 10628 10692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
07-27 08:56:52.445 10628 10692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:56:52.445 10628 10692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:56:52.445 10628 10692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:56:52.445 10628 10692 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:56:52.445 10628 10692 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 08:56:52.470 10628 10628 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:56:52.775 10628 10693 W jxcore-log: Initializing JXcore engine
07-27 08:56:52.775 10628 10693 W jxcore-log: JXcore engine is ready
,07-27 08:56:52.800  5630  5630 E audit   : type=1400 msg=audit(1469602612.800:260): avc:  denied  { ioctl } for  pid=10693 comm="Thread-1015" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3230 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 08:56:52.800  5630  5630 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:52.800  5630  5630 E audit   : type=1300 msg=audit(1469602612.800:260): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=9737f3c8 items=0 ppid=2960 ppcomm=main pid=10693 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1015" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:56:52.800  5630  5630 E audit   : type=1327 msg=audit(1469602612.800:260): proctitle="com.test.thalitest"
07-27 08:56:52.800  5630  5630 E audit   : type=1320 msg=audit(1469602612.800:260): 
,07-27 08:56:52.800  5630  5630 E audit   : type=1400 msg=audit(1469602612.800:261): avc:  denied  { ioctl } for  pid=10693 comm="Thread-1015" path="socket:[35410]" dev="sockfs" ino=35410 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-27 08:56:52.800  5630  5630 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:52.800  5630  5630 E audit   : type=1300 msg=audit(1469602612.800:261): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=9737f3c8 items=0 ppid=2960 ppcomm=main pid=10693 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1015" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:56:52.800  5630  5630 E audit   : type=1327 msg=audit(1469602612.800:261): proctitle="com.test.thalitest"
07-27 08:56:52.800  5630  5630 E audit   : type=1320 msg=audit(1469602612.800:261): 
,07-27 08:56:52.805 10628 10693 W jxcore-log: Starting JXcore engine
,07-27 08:56:52.850  4689  4689 D Recents : onTaskStackChanged
,07-27 08:56:52.855 10628 10693 W jxcore-log: Platform android
07-27 08:56:52.855 10628 10693 W jxcore-log: 
07-27 08:56:52.855 10628 10693 W jxcore-log: Process ARCH arm
07-27 08:56:52.855 10628 10693 W jxcore-log: 
,07-27 08:56:52.930 10628 10693 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:56:52.930 10628 10693 I jxcore-log: 
07-27 08:56:52.930 10628 10693 W jxcore-log: JXcore engine is started
,07-27 08:56:52.935 10628 10692 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:56:52.940 10628 10628 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:56:53.965  3531  4498 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/108_task.xml.bak
,07-27 08:56:54.930  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:18), LCD = 0
,07-27 08:56:57.400  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:56:59.200 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:56:59.200 10628 10693 I jxcore-log: 
,07-27 08:56:59.200 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:56:59.200 10628 10693 I jxcore-log: 
,07-27 08:56:59.205 10628 10693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:56:59.205 10628 10693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:56:59.205 10628 10693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:56:59.205 10628 10693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:56:59.205 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:56:59.205 10628 10693 I jxcore-log: 
07-27 08:56:59.205 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:56:59.205 10628 10693 I jxcore-log: 
,07-27 08:56:59.415 10628 10693 I jxcore-log: Unit Test app is loaded
07-27 08:56:59.415 10628 10693 I jxcore-log: 
,07-27 08:56:59.420 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:56:59.420 10628 10693 I jxcore-log: 
,07-27 08:56:59.420 10628 10628 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:56:59.420 10628 10693 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-27 08:56:59.425  3531  5261 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-27 08:56:59.425  3531  5261 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-27 08:56:59.425  3531  5261 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-27 08:56:59.430  3531  5261 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-27 08:56:59.430  3531  5261 V CAE     : start(ContextProvider.java:128)
,07-27 08:56:59.430  3531  5261 V CAE     : clear(ActivityTrackerRunner.java:108)
07-27 08:56:59.430  3531  5261 V CAE     : enable(ActivityTrackerRunner.java:84)
07-27 08:56:59.430  3531  5261 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 56, 59,
07-27 08:56:59.430  3531  5261 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 56, 59
,07-27 08:56:59.430  2933  3101 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 6, 56, 59
,07-27 08:56:59.445  3531  5261 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-27 08:56:59.445  3531  5261 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 08:56:59.455  3531  5261 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-27 08:56:59.455  3531  5261 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-27 08:56:59.455  3531  5261 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-27 08:56:59.455  3531  5261 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@572b441, Service : ACTIVITY_TRACKER(1)
07-27 08:56:59.455  3531  5261 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
,07-27 08:56:59.455  3531  5261 D SContextService: 	.registerCallback : 1, client=
07-27 08:56:59.455  3531  5261 D SContextService: ===== SContext Service List =====
07-27 08:56:59.455  3531  5261 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@3791f27, Service : Activity Tracker
07-27 08:56:59.455  3531  5261 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@8bde6, service=Activity Tracker
07-27 08:56:59.455  3531  5261 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
07-27 08:56:59.455  3531  5261 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,07-27 08:56:59.455  3531  5261 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
07-27 08:56:59.455  3531  5261 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-27 08:56:59.455  3531  5261 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
07-27 08:56:59.455  2933  2933 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-27 08:56:59.460  3531  5261 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
07-27 08:56:59.460  3531  5261 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 08:56:59.470  3531  5261 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
07-27 08:56:59.470  3531  5261 D SContextService: requestToUpdate() : service = Activity Tracker
,07-27 08:56:59.470  3531  5261 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
07-27 08:56:59.470  3531  5261 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@8bde6, service=Activity Tracker
07-27 08:56:59.470  3531  5261 D WifiService: setWifiEnabled: true pid=10628, uid=10007
07-27 08:56:59.470  3531  5261 W ActivityManager: Permission Denial: getCurrentUser() from pid=10628, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:56:59.470  3531  5261 W WifiService: Failed getting userId using ActivityManagerNative
07-27 08:56:59.470  3531  5261 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10628, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:56:59.470  3531  5261 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28178)
07-27 08:56:59.470  3531  5261 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2490)
07-27 08:56:59.470  3531  5261 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2478)
07-27 08:56:59.470  3531  5261 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-27 08:56:59.470  3531  5261 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 08:56:59.470  3531  4446 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-27 08:56:59.470  3531  5261 D SettingsProvider: isChangeAllowed() SettingsProvider : name = wifi_on
,07-27 08:56:59.470  3531  4447 D WifiController: [FCC]setFccChannel() is called !!!
07-27 08:56:59.470  3531  4447 D WifiStateMachine: setFccChannel: channel = 0
07-27 08:56:59.470  3531  4447 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-27 08:56:59.470  3531  5112 I WifiService: disconnect: pid=10628, uid=10007
,07-27 08:56:59.470  3531  4447 D SecContentProvider: insert(), uri = 2
,07-27 08:56:59.475  3531  4446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18718 com.android.server.wifi.WifiStateMachine.access$3900:292 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8636 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-27 08:56:59.475  3531  4446 D WifiBigDataLog: init : 
,07-27 08:56:59.475  3531  4446 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 08:56:59.480 10628 10693 D BluetoothAdapter: enable()
,07-27 08:56:59.480  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13a55d4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bcb8226 5647:com.samsung.android.providers.context/u0a11}
,07-27 08:56:59.480  2916  4374 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-27 08:56:59.485  3531  4546 W ActivityManager: Permission Denial: getCurrentUser() from pid=10628, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
,07-27 08:56:59.490  3531  4546 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 08:56:59.490  3531  4546 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10628, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
07-27 08:56:59.490  3531  4546 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28178)
07-27 08:56:59.490  3531  4546 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2843)
07-27 08:56:59.490  3531  4546 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2833)
07-27 08:56:59.490  3531  4546 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1213)
07-27 08:56:59.490  3531  4546 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:262)
07-27 08:56:59.490  3531  4546 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 08:56:59.490  3531  4546 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:56:59.490  3531  4546 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-27 08:56:59.490  3531  4546 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bluetooth_on
,07-27 08:56:59.495  2916  4374 I WifiHW  : module is murata
07-27 08:56:59.495  2916  4374 E WifiHW  : ==========[WIFI] MURATA MODULE ===========
07-27 08:56:59.495  2916  4374 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
07-27 08:56:59.495  2916  4374 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 08:56:59.495  2916  4374 D SoftapController: Softap fwReload - Ok
,07-27 08:56:59.500  2916  4374 D CommandListener: Setting iface cfg
07-27 08:56:59.500  2916  4374 D CommandListener: Trying to bring down wlan0
,07-27 08:56:59.500  2916  4374 D CommandListener: Clearing all IP addresses on wlan0
,07-27 08:56:59.505  3531  4446 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-27 08:56:59.510 10628 10693 I jxcore-log: My device name is: samsung-SM-N910C
07-27 08:56:59.510 10628 10693 I jxcore-log: 
,07-27 08:56:59.520 10696 10696 E Zygote  : v2
07-27 08:56:59.520 10696 10696 I libpersona: KNOX_SDCARD checking this for 1002
07-27 08:56:59.520 10696 10696 I libpersona: KNOX_SDCARD not a persona
,07-27 08:56:59.520  3531  3801 I ActivityManager: Start proc 10696:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 08:56:59.525 10696 10696 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:56:59.525 10696 10696 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:56:59.525 10696 10696 E Zygote  : accessInfo : 0
,07-27 08:56:59.550 10696 10696 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:56:59.550 10696 10696 D ActivityThread: Added TimaKeyStore provider
,07-27 08:56:59.580  2933  3100 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 1, 125, -60, 63, 0, 0
,07-27 08:56:59.580  3531  4404 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 1, 125, -60, 63, 0, 0
,07-27 08:56:59.600 10696 10696 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-27 08:56:59.610  3531  4446 D wifi    : Can not initialize the vendor function pointer table
07-27 08:56:59.610  3531  4446 E WifiNative-HAL: Could not start hal
07-27 08:56:59.610  3531  4446 E WifiStateMachine: Failed to start HAL
,07-27 08:56:59.610  3531  4446 E WifiHW  : supplicant_name : p2p_supplicant
,07-27 08:56:59.615  3531  4403 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 6, 56, 59,
07-27 08:56:59.615  3531  4403 D SensorHubManager: SendSensorHubData: send data = -63, 14, 6, 56, 59
07-27 08:56:59.615  2933  3101 D Sensorhubs: sendContextData: -63, 14, 6, 56, 59
,07-27 08:56:59.625  3531  4403 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_SLEEP
07-27 08:56:59.625  3531  4403 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
07-27 08:56:59.625  3531  4403 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 1, 125, -60, 63, 0, 0,
,07-27 08:56:59.625  3531  4403 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-27 08:56:59.625  3531  4403 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1469602619455]
,07-27 08:56:59.635  3531  4406 D SContextService: updateSContext() : event = Activity Tracker
07-27 08:56:59.635  3531  3531 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-27 08:56:59.635  3531  3531 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-27 08:56:59.635  3531  3531 D WifiService: setWifiScanWithSensor bMove = 0
07-27 08:56:59.635  3531  3531 D WifiStateMachine: setWifiScanMove bMove = 0
07-27 08:56:59.635  3531  3531 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,07-27 08:56:59.650 10696 10696 D BtSettings.ProfileConfig: Adding GattService
,07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding HeadsetService
,07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding A2dpService
07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding HidService
07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding HealthService
07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding PanService
07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding SapService
07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-27 08:56:59.655 10696 10696 D BtSettings.ProfileConfig: Adding A2dpSinkService
,07-27 08:56:59.655 10696 10696 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-27 08:56:59.655  3531  4879 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.gatt.GattService
07-27 08:56:59.655  3531  4879 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.655  3531  4879 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.655  3531  4879 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.655  3531  4879 D SettingsProvider: selectionArgs: false
07-27 08:56:59.655  3531  4879 D SettingsProvider: selectionArgs: 1002
,07-27 08:56:59.655  3531  4879 D SettingsProvider: ret = -1
,07-27 08:56:59.660  3531  4898 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 08:56:59.660  3531  4898 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  4898 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.660  3531  4898 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.660  3531  4898 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  4898 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.660  3531  4898 D SettingsProvider: ret = -1
,07-27 08:56:59.660  3531  7135 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-27 08:56:59.660  3531  7135 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  7135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.660  3531  7135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.660  3531  7135 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  7135 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.660  3531  7135 D SettingsProvider: ret = -1
,07-27 08:56:59.660  3531  5022 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hid.HidService
07-27 08:56:59.660  3531  5022 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  5022 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.660  3531  5022 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.660  3531  5022 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  5022 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.660  3531  5022 D SettingsProvider: ret = -1
,07-27 08:56:59.660  3531  5116 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-27 08:56:59.660  3531  5116 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  5116 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.660  3531  5116 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.660  3531  5116 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  5116 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.660  3531  5116 D SettingsProvider: ret = -1
07-27 08:56:59.660  3531  5115 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.pan.PanService
07-27 08:56:59.660  3531  5115 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  5115 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 08:56:59.660  3531  5115 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.660  3531  5115 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  5115 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.660  3531  5115 D SettingsProvider: ret = -1
07-27 08:56:59.660  3531  5686 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-27 08:56:59.660  3531  5686 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.660  3531  5686 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  5686 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.660  3531  5686 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  5686 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.660  3531  5686 D SettingsProvider: ret = -1
07-27 08:56:59.660  3531  3557 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.sap.SapService
07-27 08:56:59.660  3531  3557 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 08:56:59.660  3531  3557 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  3557 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.660  3531  3557 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  3557 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.660  3531  3557 D SettingsProvider: ret = -1
07-27 08:56:59.660  3531  5261 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:56:59.660  3531  5261 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.660  3531  5261 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.660  3531  5261 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 08:56:59.660  3531  5261 D SettingsProvider: selectionArgs: false
07-27 08:56:59.660  3531  5261 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.665  3531  5261 D SettingsProvider: ret = -1
,07-27 08:56:59.665  3531  5112 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:56:59.665  3531  5112 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:56:59.665  3531  5112 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:56:59.665  3531  5112 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:56:59.665  3531  5112 D SettingsProvider: selectionArgs: false
07-27 08:56:59.665  3531  5112 D SettingsProvider: selectionArgs: 1002
07-27 08:56:59.665  3531  5112 D SettingsProvider: ret = -1
,07-27 08:56:59.700 10696 10696 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 08:56:59.700 10696 10712 I BluetoothAdapterState: Entering OffState
,07-27 08:56:59.705 10696 10696 I bt_bluedroid: init
,07-27 08:56:59.710  3531  4446 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 08:56:59.715  3531  3531 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:56:59.715  3531  3531 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:56:59.715  3531  4451 I WifiHs20Service: Message received 5011
07-27 08:56:59.715  3531  3531 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-27 08:56:59.715  3531  4454 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-27 08:56:59.720  5087  7512 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-27 08:56:59.720  4515  4515 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:56:59.720  4515  4515 D STATUSBAR-WifiTile: Wifi onReceive(2)
07-27 08:56:59.720  4515  4515 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=2
07-27 08:56:59.720 10696 10713 E bt_core_counter: counter_init unable to open counter port
07-27 08:56:59.720  4515  6523 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 08:56:59.720 10696 10713 E bt_core_module: module_init failed to initialize "counter_module"
07-27 08:56:59.720  5087  7512 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-27 08:56:59.720  3531  4454 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
,07-27 08:56:59.720 10696 10713 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 08:56:59.720  4515  4515 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
07-27 08:56:59.720  4515  4515 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:56:59.720 10628 10628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:56:59.720  4515  4515 D HotspotTile: onReceive : 2, 0
,07-27 08:56:59.725 10696 10713 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 08:56:59.725 10696 10713 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 08:56:59.725 10696 10713 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 08:56:59.725  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a6a8b6c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7607535 10628:com.test.thalitest/u0a7}
,07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730 10696 10696 I bt_bluedroid: get_profile_interface socket
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:56:59.730  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:56:59.730 10696 10696 W bt_btif : btif_get_adapter_property 2
07-27 08:56:59.730 10696 10696 W bt_btif : btif_get_adapter_property 1
07-27 08:56:59.735 10696 10696 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
07-27 08:56:59.735 10696 10716 D BluetoothAdapterProperties: Address is:E0:DB:10:14:E2:C0
07-27 08:56:59.735 10696 10716 E BluetoothServiceJni: populateRssiValuesNative
07-27 08:56:59.735 10696 10716 I bt_bluedroid: getModelRssiValues
07-27 08:56:59.735 10696 10716 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-27 08:56:59.735 10696 10716 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
07-27 08:56:59.735 10696 10716 D BluetoothAdapterProperties: Name is: Note4-1
07-27 08:56:59.735  3531  3531 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bluetooth_name
07-27 08:56:59.740 10696 10696 I bt_bluedroid: get_profile_interface sdp
07-27 08:56:59.740  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a6a8b6c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2653b57 7198:tv.peel.smartremote/u0a186}
07-27 08:56:59.750 10696 10706 I bt_bluedroid: config_hci_snoop_log
07-27 08:56:59.755  3531  3801 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,07-27 08:56:59.760 10696 10712 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-27 08:56:59.770 10717 10717 E Zygote  : v2
07-27 08:56:59.770 10717 10717 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:56:59.770 10717 10717 I libpersona: KNOX_SDCARD not a persona
,07-27 08:56:59.770 10717 10717 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:56:59.770 10717 10717 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:56:59.770 10717 10717 E Zygote  : accessInfo : 0
,07-27 08:56:59.770  3531  3685 I ActivityManager: Start proc 10717:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,07-27 08:56:59.770 10696 10712 D BluetoothAdapterProperties: Setting state to 14
07-27 08:56:59.770 10696 10712 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 08:56:59.770 10696 10712 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:56:59.770 10696 10712 D BluetoothAdapterService: updateAdapterState state is 14
,07-27 08:56:59.775  3531  3801 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
07-27 08:56:59.775 10696 10712 D BluetoothAdapterService: Autoconnection is available 
07-27 08:56:59.775 10696 10712 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,07-27 08:56:59.775 10696 10712 D BluetoothSecureManager: getInstant: null
,07-27 08:56:59.780 10696 10712 D BluetoothSecureManager: calling getMethod for getService
07-27 08:56:59.780 10696 10712 D BluetoothSecureManager: calling getService
07-27 08:56:59.780 10696 10712 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@28326a
,07-27 08:56:59.780  3531  4898 D BluetoothSecureManagerService: isSecureModeEnabled
,07-27 08:56:59.780  3531  4898 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-27 08:56:59.780 10696 10712 D BtConfig.SecureMode: isSecureModeOn:false
07-27 08:56:59.780 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 08:56:59.785 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-27 08:56:59.785 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 08:56:59.785 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-27 08:56:59.785 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 08:56:59.785 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-27 08:56:59.785 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 08:56:59.785 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-27 08:56:59.785 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 08:56:59.785 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-27 08:56:59.785 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 08:56:59.785 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 08:56:59.785 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 08:56:59.785 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-27 08:56:59.785 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-27 08:56:59.790 10696 10712 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
07-27 08:56:59.790 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 08:56:59.790 10696 10712 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:56:59.790 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:56:59.790 10696 10712 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:56:59.790 10717 10717 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:56:59.790 10717 10717 D ActivityThread: Added TimaKeyStore provider
,07-27 08:56:59.790 10696 10712 D BluetoothBondStateMachine: make
,07-27 08:56:59.795 10696 10729 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 08:56:59.800 10708 10708 I FIPS_bssl: FIPS approved mode (1) | 10708 | /system/bin/wpa_supplicant
,07-27 08:56:59.800  3531  4546 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a6a8b6c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b4ea6b3 10717:com.samsung.android.securitylogagent/1000}
,07-27 08:56:59.805 10696 10712 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:56:59.805 10696 10696 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,07-27 08:56:59.810 10696 10696 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 08:56:59.810 10696 10696 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:56:59.810 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
07-27 08:56:59.810 10696 10696 D BtGatt.GattService: start()
07-27 08:56:59.810 10696 10696 I bt_bluedroid: get_profile_interface gatt
07-27 08:56:59.810 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
07-27 08:56:59.810 10696 10696 D BtGatt.AdvertiseManager: advertise manager created
07-27 08:56:59.810 10696 10696 D BtGatt.AdvertiseManager: start
07-27 08:56:59.810 10717 10717 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm
,07-27 08:56:59.815 10708 10708 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-27 08:56:59.815 10708 10708 I wpa_supplicant: Successfully initialized wpa_supplicant
07-27 08:56:59.815 10708 10708 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,07-27 08:56:59.815 10708 10708 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-27 08:56:59.820  3531  4439 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:56:59.820 10717 10717 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:56:59.820 10717 10717 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:56:59.820 10717 10717 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:56:59.820  4515  4515 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No network connection wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:56:59.820  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:56:59.820  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:56:59.820  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:56:59.820  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:56:59.820 10696 10696 D BtGatt.ScanManager: start
07-27 08:56:59.820 10717 10717 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:56:59.825 10696 10696 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,07-27 08:56:59.835  3531  4898 I ActivityManager: Start proc 10738:com.samsung.android.keyguardwallpaperupdator/u0a127 for broadcast-5 com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver
07-27 08:56:59.835  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:56:59.835  3531  4898 I ActivityManager: Killing 9513:com.google.android.gms:car/u0a14 (adj 15): DHA:empty #31
,07-27 08:56:59.835 10738 10738 E Zygote  : v2
07-27 08:56:59.835 10738 10738 I libpersona: KNOX_SDCARD checking this for 10127
07-27 08:56:59.835 10738 10738 I libpersona: KNOX_SDCARD not a persona
,07-27 08:56:59.840 10738 10738 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:56:59.840 10738 10738 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:56:59.840 10738 10738 E Zygote  : accessInfo : 0
07-27 08:56:59.840 10738 10738 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.keyguardwallpaperupdator 
,07-27 08:56:59.840 10708 10708 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 08:56:59.845  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 08:56:59.845  2985  2985 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10708
07-27 08:56:59.845  2985  2985 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-27 08:56:59.845 10708 10708 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 08:56:59.845 10708 10708 I wpa_supplicant: ssSupport state is = 1
07-27 08:56:59.845 10708 10708 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-27 08:56:59.845 10708 10708 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-27 08:56:59.845  2985  2985 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10708
07-27 08:56:59.845  2985  2985 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-27 08:56:59.855 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,07-27 08:56:59.860 10738 10738 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:56:59.860 10738 10738 D ActivityThread: Added TimaKeyStore provider
,07-27 08:56:59.865 10696 10696 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,07-27 08:56:59.870  3531  5116 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a6a8b6c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5dda79c 10738:com.samsung.android.keyguardwallpaperupdator/u0a127}
,07-27 08:56:59.870 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
07-27 08:56:59.870 10696 10696 E BtGatt.GattService: notifyProfileServiceStateChanged
,07-27 08:56:59.870 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:56:59.870 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
07-27 08:56:59.870 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:56:59.870 10696 10696 V BluetoothAdapterState: isTurningOn()=false
07-27 08:56:59.870 10696 10696 V BluetoothAdapterState: isBleTurningOn()=true
07-27 08:56:59.870 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:56:59.870 10696 10712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-27 08:56:59.875 10696 10712 I bt_bluedroid: enable
07-27 08:56:59.875 10696 10713 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-27 08:56:59.880 10696 10713 I bt_hci  : start_up
,07-27 08:56:59.880  3531  4546 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,07-27 08:56:59.885 10696 10713 I bt_vendor: alloc value 0xb3422a11
07-27 08:56:59.885 10696 10713 I bt_vendor: init
07-27 08:56:59.885 10696 10713 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 08:56:59.885 10696 10713 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 08:56:59.885 10696 10713 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-27 08:56:59.885 10696 10713 I bt_upio : upio_set_bluetooth_power(on: 1)
,07-27 08:56:59.885 10738 10738 W System  : ClassLoader referenced unknown path: /system/priv-app/KeyguardWallpaperUpdator/lib/arm
,07-27 08:56:59.895 10738 10738 D KeyguardWallpaperUpdator: cancelUpdateWallpaper
,07-27 08:56:59.895  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{7bb6721: PendingIntentRecord{8bd2746 com.samsung.android.keyguardwallpaperupdator broadcastIntent}}
,07-27 08:56:59.900 10763 10763 E Zygote  : v2
07-27 08:56:59.900 10763 10763 I libpersona: KNOX_SDCARD checking this for 10022
07-27 08:56:59.900 10763 10763 I libpersona: KNOX_SDCARD not a persona
,07-27 08:56:59.905 10763 10763 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:56:59.905 10763 10763 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:59.905 10763 10763 E Zygote  : accessInfo : 0
07-27 08:56:59.905 10763 10763 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.locationwidget 
,07-27 08:56:59.905  3531  7135 I ActivityManager: Start proc 10763:com.sec.android.widgetapp.locationwidget/u0a22 for broadcast-5 com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider
,07-27 08:56:59.905  3531  7135 I ActivityManager: Killing 9903:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,07-27 08:56:59.920 10763 10763 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:56:59.920 10763 10763 D ActivityThread: Added TimaKeyStore provider
,07-27 08:56:59.930  3531  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a6a8b6c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53d07 10763:com.sec.android.widgetapp.locationwidget/u0a22}
,07-27 08:56:59.940 10763 10763 W System  : ClassLoader referenced unknown path: /system/priv-app/LocationWidget_M/lib/arm
,07-27 08:56:59.945 10763 10763 I LocationWidgetApplication: onCreate() : start
,07-27 08:56:59.945 10763 10763 D LocationWidgetApplication: countryCode = POLAND
,07-27 08:56:59.945  3531  4968 E Watchdog: !@Sync 9 [07-27 08:56:59.949]
,07-27 08:56:59.945  3531  5261 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,07-27 08:56:59.965 10776 10776 E Zygote  : v2
,07-27 08:56:59.965 10776 10776 I libpersona: KNOX_SDCARD checking this for 10160
07-27 08:56:59.965 10776 10776 I libpersona: KNOX_SDCARD not a persona
07-27 08:56:59.965 10776 10776 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:56:59.965 10776 10776 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:56:59.965 10776 10776 E Zygote  : accessInfo : 0
07-27 08:56:59.965 10776 10776 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.snote:sync 
07-27 08:56:59.965  3531  4879 I ActivityManager: Start proc 10776:com.samsung.android.snote:sync/u0a160 for broadcast-5 com.samsung.android.snote/.control.core.sync.scloud.ReceiverWifiStateChanged
07-27 08:56:59.970  3531  4879 I ActivityManager: Killing 9918:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): DHA:empty #31
,07-27 08:56:59.980 10776 10776 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:56:59.980 10776 10776 D ActivityThread: Added TimaKeyStore provider
,07-27 08:56:59.985  3531  3557 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{a6a8b6c u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acea2a3 10776:com.samsung.android.snote:sync/u0a160}
,07-27 08:56:59.990 10696 10713 D bt_hci  : start_up starting async portion
07-27 08:56:59.990 10696 10761 I bt_hci  : event_finish_startup
07-27 08:56:59.990 10696 10761 I bt_hci_h4: hal_open
07-27 08:56:59.990 10696 10761 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC3
07-27 08:56:59.990 10696 10761 I bt_userial_vendor: userial_vendor_open():UART is setup
07-27 08:56:59.990 10696 10761 I bt_userial_vendor: device fd = 60 open
07-27 08:56:59.990 10696 10761 E bt_hwcfg: Start CFG HW, HCI reset
07-27 08:57:00.000 10696 10761 E bt_hwcfg: Read Local Name after HCI reset
07-27 08:57:00.000  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{c9b19a0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.000 10776 10776 W System  : ClassLoader referenced unknown path: /system/app/SNote5.0Preload/lib/arm
07-27 08:57:00.005 10776 10776 D SNoteApp: process name: com.samsung.android.snote:sync
07-27 08:57:00.010  3531  5116 D RCPManagerService: exchangeData() failure , invalid userId
07-27 08:57:00.020  3531  3557 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
07-27 08:57:00.020 10696 10761 D bt_hwcfg: Chipset BCM43569A1
07-27 08:57:00.020 10696 10761 D bt_hwcfg: Target name = [BCM4358A1]
07-27 08:57:00.020 10696 10761 I bt_hwcfg: module_type[murata].
07-27 08:57:00.025 10696 10761 I bt_hwcfg: module_type[murata] is invalid.
,07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG . BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG .. BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG companion_default_coef.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG companion_default_lsc.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG companion_fw_imx240_evt1.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG companion_imx240_master_setfile.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG companion_imx240_mode_setfile.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx240.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG fimc_is_ois_63A.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG fimc_is_ois_63B.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG hevc_fw.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG sec_s3fwrn5_firmware.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG setfile_6d1.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG setfile_imx240.bin BCM4358A1
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG BCM4358A1_V0054.0094_wisol.hcd BCM4358A1
07-27 08:57:00.025 10696 10761 I bt_hwcfg: patch(org) : BCM4358A1_V0054.0094_wisol.hcd
07-27 08:57:00.025 10696 10761 E bt_hwcfg: Module type exists. Skip
07-27 08:57:00.025 10696 10761 E bt_hwcfg: patchram path ORG BCM4358A1_V0054.0094.hcd BCM4358A1
07-27 08:57:00.025  3531  4898 I ActivityManager: Killing 9940:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): DHA:empty #31
07-27 08:57:00.025 10696 10761 I bt_hwcfg: patch(org) : BCM4358A1_V0054.0094.hcd
07-27 08:57:00.025 10696 10761 I bt_hwcfg: Found patchfile: /vendor/firmware/BCM4358A1_V0054.0094.hcd
07-27 08:57:00.025 10696 10761 E bt_hwcfg: ORG patchram base 0054
07-27 08:57:00.025 10696 10761 E bt_hwcfg: ORG patchram minor 0094
07-27 08:57:00.025 10696 10761 E bt_hwcfg: fw ver (org)54.94
07-27 08:57:00.025 10696 10761 E bt_hwcfg: Final Patchram is /vendor/firmware/BCM4358A1_V0054.0094.hcd
,07-27 08:57:00.030 10696 10761 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-27 08:57:00.030  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{198d959: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.035 10696 10761 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-27 08:57:00.035  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{423d91e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.050  2985  2985 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-27 08:57:00.055 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,07-27 08:57:00.070 10708 10708 I wpa_supplicant: Ctrl_iface: loading system cred
,07-27 08:57:00.070 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-27 08:57:00.080  3531  4879 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,07-27 08:57:00.090 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-27 08:57:00.090  2985  2985 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10708
07-27 08:57:00.090  2985  2985 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 08:57:00.090 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-27 08:57:00.090 10708 10708 I wpa_supplicant: ssSupport state is = 1
,07-27 08:57:00.095 10708 10708 E wpa_supplicant: SIM READ ERROR
07-27 08:57:00.095 10708 10708 E wpa_supplicant: SIM READ ERROR
07-27 08:57:00.095 10708 10708 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:57:00.095 10708 10708 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-27 08:57:00.095 10708 10708 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:57:00.135  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{a9ec5ff: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.135  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{8282fcc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.190  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{b74b215: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.190  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{30692a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.190  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{523c31b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.190  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{78e7cb8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.195  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{ffb5a91: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.195  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{c3edf6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.195  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{83175f7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.200  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{30aac64: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.200  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{56a0ecd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.200  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{e38f382: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.205  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{fd7a93: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.205  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{7f82ad0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.205  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{e95cac9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.210  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a06c5ce: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.210  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{7b2cef: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.210  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{bfd23fc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.210  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{ca74a85: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.215  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{3cd70da: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.215  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{977a90b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.215  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{6f683e8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.220  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{970a01: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.220  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{321c0a6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.220  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{475cae7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.220  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{fa3f694: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.225  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{869453d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.225  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{2194132: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.230  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{54a2e83: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.230  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{713e800: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.230  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{429f839: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.230  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{4963e7e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.230  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{e772fdf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.235  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{ecf842c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.235  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{ea8def5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.235  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{853c48a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.240  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{e48eafb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.240  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{5c6b718: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.240  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{5f57571: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.240  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{9b19f56: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.245  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{1b13bd7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.245  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{7fc2cc4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.245  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{f9af7ad: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.250  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{9405ae2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.250  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{8e3be73: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.250  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{cf15130: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}},
,07-27 08:57:00.250  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{49c61a9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.255  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{e0d432e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.255  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{9b1cecf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.255  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{d2505c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.260  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{1306f65: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.260  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{ae643a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.260  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{ba688eb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.260  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{4621648: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.265  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{43d9ce1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.265  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{b0e8a06: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.265  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{9e2c8c7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.270  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{fa64ef4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.270  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{a96261d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.270  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{8f94092: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.270  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{6b92a63: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.275  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{3536660: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}},
,07-27 08:57:00.275  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{1f40719: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.280  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{566d3de: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.280  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{d0a09bf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.280  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{4f8888c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.280  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{fb4fbd5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.285  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{884fea: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.285  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{b5f82db: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.285  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{1eba178: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.285  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{7568051: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.290  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{a9380b6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.290  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{4c971b7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.290  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{4f55d24: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.290  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{cb1d08d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.295  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{f4ef242: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.295  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{3797253: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.295  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{abd2790: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.295  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{df7e889: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.300  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{e5df08e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.300  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{91ee0af: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.300  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{f52cbc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.300  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{16d8445: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.300  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{c4c879a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.305  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{902d8cb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.305  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{c4658a8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.305  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{2e71fc1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.305  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{85b8366: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.310  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{7e436a7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.310  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{fc5754: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.310  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{d04f6fd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.310  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{30c6ff2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.315  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{d939643: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.315  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{a7194c0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.315  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{a2f05f9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.315  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{16d993e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.320  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{44f539f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.320  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{d3b3cec: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.320  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{95108b5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.320  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{9260b4a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.325  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{1df8abb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.325  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{153bd8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.325  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{2567b31: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.330  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{1419216: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.330  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{6721797: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.330  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{78e3d84: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.330  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{666996d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.335  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{3bcb9a2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.335  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{d369633: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.335  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{73adf0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.340  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{7e05f69: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.340  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{bd0cdee: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.340  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{aba628f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.340  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{4fdb91c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.345  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{6168925: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.345  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{cffdafa: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.345  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{50498ab: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.345  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{8bb4b08: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.350  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{8cb92a1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.350  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{ee0acc6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.350  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{1721487: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.355  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{73e0fb4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.355  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{76db7dd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.355  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{9aacf52: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.355  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{4517223: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.360  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{1867320: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.360  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{812f4d9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.360  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{f828e9e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.360  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{e3f0d7f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.365  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{62fa14c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}},
,07-27 08:57:00.365  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{2350595: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.365  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{e84f6aa: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.365  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{341029b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.370  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{5b8638: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.370  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{12d6611: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.370  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{793d376: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.370  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{7a32d77: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}},
,07-27 08:57:00.375  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{95ecde4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}},
,07-27 08:57:00.375  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{271524d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.375  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{5e1b102: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.375  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{e932a13: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.380  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{92ce450: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.380  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{b8dc649: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.380  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{33ddb4e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.380  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{67c546f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.385  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{183f57c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.385  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{3e37e05: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.385  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{5205e5a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.385  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{f23c88b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.390  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{fd8ed68: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.390  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{e22f581: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.390  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{e760626: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.395  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{5846267: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.395  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{2037814: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.395  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{d8868bd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.400  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{22c5eb2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.400  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{16abe03: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.400  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{9aa0180: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.405  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{2d7d3b9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.405  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{27db3fe: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.405  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{d1375f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.410  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{a6db5ac: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.410  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{d18f275: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.415  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{8fd120a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.415  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{cfbea7b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.420  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{ed68098: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.420  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{a1340f1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.425  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{36244d6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.425  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{554b357: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.425  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{fff0e44: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.430  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{289fb2d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.430  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{115d862: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.430  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{c072df3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.435  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{c00cab0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.435  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{e381d29: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.440  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{d7d18ae: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.440  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{5cb64f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.445  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{71fe1dc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.445  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{b8c62e5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.450  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{30611ba: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.450  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{2d8686b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.450  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{3b73fc8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.455  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{7254861: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.455  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{2f38f86: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.455  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{f132047: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.460  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{ce49074: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.460  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{f0d099d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.465  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{de91e12: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.465  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{75779e3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.470  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{ff43fe0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.470  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{db5a299: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.470  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{937095e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.475  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{dfdd13f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.475  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{8d7a0c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.480  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{8b4cf55: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.480  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{ce65d6a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.485  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{888425b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.485  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{39e2af8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.490  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{f400bd1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.490  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{684e636: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.495  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{87ea937: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.495  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{d06fea4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.495  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{468940d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.500  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{cb12fc2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.500  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{60aa1d3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.505  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{c076110: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.505  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{1176409: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.510  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{f66860e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.510  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{853882f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.510  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{2697e3c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.515  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{9c937c5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.515  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{108f51a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.515  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{79a784b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.520  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{26e4228: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.520  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{40a8b41: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.520  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{43148e6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.520  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{5164e27: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.525  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{f7958d4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.525  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{7b39a7d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.525  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{a390d72: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.530  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{48fa5c3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.530  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{d7d2e40: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.530  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{7e46179: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.535  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{e868ebe: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.535  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{3bcdb1f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.535  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{b26ee6c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.535  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{fc09c35: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.540  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{a98d8ca: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.540  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{b5e0a3b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.540  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{2ca8558: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.540  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{eebc6b1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.540  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{ed3b796: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.545  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{6190f17: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.545  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{e0e9f04: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.545  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{1c51ced: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.545  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{c0bb722: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.550  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{91585b3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.550  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{858a770: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.555  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{1639ae9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.555  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{9d2236e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.555  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{a58ca0f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.555  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{bf8ca9c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.560  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{751fca5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.560  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{581087a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.560 10696 10761 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 08:57:00.560 10696 10761 I bt_hwcfg: FW Download delta = 562879
07-27 08:57:00.560 10696 10761 D bt_hwcfg: Settlement delay -- 100 ms
07-27 08:57:00.560  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{e1f82b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.560 10696 10761 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 08:57:00.560  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{615f488: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.565  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{10abe21: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.565  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{6073246: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.565  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{a85ec07: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.565  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{d59d134: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.570  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{f341b5d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.570  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{742cd2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.570  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{38b41a3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.570  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{75ccca0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.575  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{c9c1059: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.575  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{944441e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.575  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{c0654ff: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.575  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{8d212cc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.580  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{8f45915: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.580  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{e6c842a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.580  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{6f5421b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.580  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{c738fb8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.585  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{34e7191: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.585  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{626b8f6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.585  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{f1be4f7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.585  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{cadef64: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.590  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{5795cd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.590  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{e7d6e82: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.590  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{d9fd993: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.590  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{c0c9dd0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.590  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{854c1c9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.595  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{997f0ce: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.595  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{e647bef: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.595  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{865c6fc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.600  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{8deb185: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.600  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{2c64bda: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.600  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{e26e80b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.605  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{4c656e8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.605  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{65de101: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.605  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{84d4ba6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.610  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{e59f9e7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.610  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{61df994: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.610  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{9468c3d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.610  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{5f27c32: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.615  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{ac24d83: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.615  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{eab1b00: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.615  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{314af39: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.620  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{c48297e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.620  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{cd23edf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.620  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{426e72c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.620  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{70805f5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.625  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{b95f8a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.625  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{8c5e9fb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.625  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{cb14a18: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.625  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{2a00c71: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.630  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{255ea56: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.630  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{7f2ad7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.630  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{e7cefc4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.630  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{1d7fead: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.635  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{f5e55e2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.635  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{8219d73: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.635  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{e3b4430: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.640  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{b22d8a9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.640  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{78fee2e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.640  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{86e9dcf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.645  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{848735c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.645  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{f275665: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.645  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{730bf3a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.645  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{ae147eb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.645  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{976948: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.650  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{83bf3e1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.650  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{6db9506: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.650  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{b8a77c7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.650  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{55dd1f4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.655  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{5a2ed1d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.655  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{c0bfb92: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.655  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{cacc963: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.655  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{801960: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.660  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{e863e19: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.660  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{66a3ede: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.660  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{81898bf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.660  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{3bd6b8c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.665 10696 10761 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-27 08:57:00.665  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{8b3a2d5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.665  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{5d76aea: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.665  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{a4801db: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.670  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{b9bb478: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.670  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{f189751: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.670  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{5394bb6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.675  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{33ae0b7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.675  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{513a024: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.675  2916  4367 D Netd    : Iface wlan0 link up
07-27 08:57:00.675 10708 10708 I wpa_supplicant: nl80211: Could not re-add multicast membership for vendor events: -2 (No such file or directory)
,07-27 08:57:00.675  2916  4367 D Netd    : Iface wlan0 link up
07-27 08:57:00.675  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{3fe578d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.675  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:00.675  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:00.680  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:00.680  3531  3801 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
07-27 08:57:00.680  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:00.680  3531  3801 D Tethering: NAP Supported and not Wifi Model
07-27 08:57:00.680  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{838cfbc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.680  3531  3801 E Tethering: No numeric data
,07-27 08:57:00.680  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{6e3eb45: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.680  3531  3801 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 08:57:00.685  3531  4443 D NtpTrustedTime: forceRefresh: no connectivity
07-27 08:57:00.685  3531  4443 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:57:00.685  4515  4515 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 08:57:00.685  4515  4515 D HotspotTile: updateTetherState():false, false
,07-27 08:57:00.685  3531  4443 V NetworkStats: performPollLocked() took 3ms
,07-27 08:57:00.690  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d18629a u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{94e8e37 3531:system/1000}
,07-27 08:57:00.690  3531  4444 D NtpTrustedTime: forceRefresh: no connectivity
,07-27 08:57:00.695  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{e8917cb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.695  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{7a12ba8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.695  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{6dcf6c1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.700  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{98a0e66: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.700  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{90f65a7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.700  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{2b15a54: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.700  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{13dfd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.705  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{18aaf2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.705  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{7c2b543: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.705  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{5f3c7c0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.705  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{e28bcf9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.705  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{282843e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.710  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{bd1629f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.710  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{a2d9fec: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.710  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{8af2fb5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.715  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{e1ea64a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.715  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{f389bb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.715  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{d4aced8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.715  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{6f01231: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.715  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{ca8dd16: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.720  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{c470697: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.720  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{e0a0084: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.720  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{82a06d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.720  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{5cdb4a2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.725  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{ceb7533: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.725  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{668a0f0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.725  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{535d669: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.725  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{d7678ee: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.730  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{a5e318f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.730  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{cedc1c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.730  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{8cc7025: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.735  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{ad535fa: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.735  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{c9657ab: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.735  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{3fb9e08: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.735  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{e78e9a1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.740  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{430b7c6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.740  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{9e0c387: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.740  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{1b092b4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.740  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{197edd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.745  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{b708a52: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.745  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{67c1123: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.745  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{41e2620: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.745  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{d342bd9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.750  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{768f99e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.750  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{1f49c7f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.750  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{60f844c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.755 10708 10708 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-27 08:57:00.755 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-27 08:57:00.755  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{5e711aa: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.760  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{e40819b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.760  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{1d69938: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.760  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{45e7d11: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.765  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{27c9e76: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.765 10696 10761 I bt_userial_vendor: userial_change_2stopbit: opening /dev/ttySAC3
07-27 08:57:00.765 10696 10761 I bt_userial_vendor: device fd = 60 open
,07-27 08:57:00.765  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{c9b9c77: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.765  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{2f810e4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.770  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{d1cd94d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.770  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{e0c2c02: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.770  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{c238913: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.770  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{6975750: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.775  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{2eabd49: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.775 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-27 08:57:00.775  2985  2985 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10708
07-27 08:57:00.775  2985  2985 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 08:57:00.775 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-27 08:57:00.775 10708 10708 I wpa_supplicant: ssSupport state is = 1
,07-27 08:57:00.775  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{315064e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.775 10708 10708 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 08:57:00.775 10708 10708 E wpa_supplicant: nl80211: Could not configure driver mode
07-27 08:57:00.775 10708 10708 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-27 08:57:00.775 10708 10708 E wpa_supplicant: p2p0: Failed to initialize driver interface
07-27 08:57:00.775 10708 10708 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:57:00.775 10708 10708 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-27 08:57:00.775 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-27 08:57:00.780  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{633a36f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.785  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{6a2987c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.785  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{998e505: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.785  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{2bf395a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.790  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{481078b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.790  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{bbec068: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.790  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{747cc81: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.795  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{6a79126: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.795  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{cf69167: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.795  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{1f37b14: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.795 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-27 08:57:00.795  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{9a3afbd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.795  2985  2985 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10708
07-27 08:57:00.795  2985  2985 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 08:57:00.795 10708 10708 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-27 08:57:00.795 10708 10708 I wpa_supplicant: ssSupport state is = 1
,07-27 08:57:00.795 10708 10708 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:57:00.800  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{36b99b2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.800  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{f50dd03: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.800 10708 10708 I wpa_supplicant: nl80211: Could not re-add multicast membership for vendor events: -2 (No such file or directory)
07-27 08:57:00.800  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{c173480: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.800 10708 10708 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-27 08:57:00.805  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{2e08ab9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.805  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{7f59efe: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.805  3531  4446 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
07-27 08:57:00.805  3531  4446 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
07-27 08:57:00.805  3531  4446 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-27 08:57:00.805 10708 10708 I wpa_supplicant: HOTSPOT20_ENABLE called ON
07-27 08:57:00.805 10708 10708 E wpa_supplicant: SIM READ ERROR
07-27 08:57:00.805 10708 10708 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:57:00.810  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{7a465f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.810  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{1fb18ac: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}},
,07-27 08:57:00.810 10708 10708 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-27 08:57:00.810  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a761975: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.815 10708 10708 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,07-27 08:57:00.815  3531  4446 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-27 08:57:00.815  3531  3531 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:00.815  3531  3531 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:00.815  3531  4448 D HS20StateMachine: WIFI_STATE_ENABLED
07-27 08:57:00.815  3531  4451 I WifiHs20Service: Message received 5011
,07-27 08:57:00.815  3531  4448 D HS20StateMachine: reloadCredentialsToSupplicant
,07-27 08:57:00.815  3531  3531 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-27 08:57:00.815  3531  4454 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-27 08:57:00.820  4515  4515 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:00.820  4515  4515 D STATUSBAR-WifiTile: Wifi onReceive(3)
07-27 08:57:00.820  4515  4515 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=3
07-27 08:57:00.820  5087  7513 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-27 08:57:00.820  5087  7513 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-27 08:57:00.820  4515  4515 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 08:57:00.820  4515  6523 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 08:57:00.820  3531  4454 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
07-27 08:57:00.820  4515  4515 D HotspotTile: onReceive : 3, 0
07-27 08:57:00.820  3531  5039 W SLocation: No Active Data Connection
07-27 08:57:00.820  3531  4448 D HotspotDBHandler: getCredentialIds
,07-27 08:57:00.820  4515  4515 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-27 08:57:00.820 10628 10628 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:00.820 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:57:00.820 10628 10628 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:00.820 10628 10628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:57:00.825  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{588ad0a u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7607535 10628:com.test.thalitest/u0a7}
,07-27 08:57:00.825  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.825  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{fa6e97b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.830  3531  7135 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:00.840 10813 10813 E Zygote  : v2
07-27 08:57:00.840 10813 10813 I libpersona: KNOX_SDCARD checking this for 10211
07-27 08:57:00.840 10813 10813 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:00.840 10708 10708 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-27 08:57:00.840  3531  4448 I ActivityManager: Start proc 10813:com.samsung.hs20provider/u0a211 for content provider com.samsung.hs20provider/.Hs20Provider
,07-27 08:57:00.840  3531  4446 D WifiConfigStore: Loading config and enabling all networks 
07-27 08:57:00.840 10813 10813 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:00.840 10813 10813 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:00.840 10813 10813 E Zygote  : accessInfo : 0
07-27 08:57:00.840 10813 10813 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-27 08:57:00.845  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{588ad0a u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b4ea6b3 10717:com.samsung.android.securitylogagent/1000}
07-27 08:57:00.845  3531  4446 E WifiConfigStore: Failed to look-up a string: WPA_PSK_SHA256
,07-27 08:57:00.850  3531  5115 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.850 10717 10717 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:57:00.850 10717 10717 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:57:00.850 10717 10717 D SecurityLogAgent: StateMachine : Current State = 1
07-27 08:57:00.850 10717 10717 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 08:57:00.850  3531  4446 I WifiConfigStore: "NG700" is a verified password AP: true
07-27 08:57:00.850  3531  4446 E WifiConfigStore: Not a HS20
,07-27 08:57:00.850  3531  4446 D WifiConfigStore: loaded 0 passpoint configs
,07-27 08:57:00.850  3531  4446 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 08:57:00.850  3531  4446 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-27 08:57:00.855  3531  4446 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-27 08:57:00.855  3531  4446 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 08:57:00.855 10738 10738 D KeyguardWallpaperUpdator: cancelUpdateWallpaper
07-27 08:57:00.855  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{588ad0a u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5dda79c 10738:com.samsung.android.keyguardwallpaperupdator/u0a127}
,07-27 08:57:00.860 10813 10813 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:00.860 10813 10813 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:00.860  3531  3531 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-27 08:57:00.860  3531  3531 D WifiHs20Service: reason: 2
07-27 08:57:00.860  3531  4451 I WifiHs20Service: Message received 5014
07-27 08:57:00.860  3531  4451 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-27 08:57:00.860  3531  4451 E WifiHs20Service: The changed config is NULL
07-27 08:57:00.860  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{5571398: PendingIntentRecord{8bd2746 com.samsung.android.keyguardwallpaperupdator broadcastIntent}}
,07-27 08:57:00.860  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{d9bd7f1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.860  3531  4446 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
07-27 08:57:00.860  3531  4446 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-27 08:57:00.865 10696 10761 I bt_hwcfg: UART_2STOPBITS_CHANGE: setting 2 stop bits
,07-27 08:57:00.865 10696 10761 I bt_hwcfg: vendor lib fwcfg completed
07-27 08:57:00.865 10696 10761 I bt_vendor: firmware callback
07-27 08:57:00.865 10696 10761 I bt_hci  : firmware_config_callback
,07-27 08:57:00.865  3531  4446 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-27 08:57:00.865 10708 10708 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 08:57:00.865 10708 10708 I wpa_supplicant: resume autoscan
07-27 08:57:00.865 10708 10708 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-27 08:57:00.865 10708 10708 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-27 08:57:00.865 10708 10708 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 08:57:00.865 10708 10708 I wpa_supplicant: reset timer : RESET_TIMER 0
,07-27 08:57:00.865 10708 10708 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 08:57:00.865 10708 10708 I wpa_supplicant: First Scan Start
,07-27 08:57:00.870 10696 10825 I bt_btu_task: Bluetooth chip preload is complete
,07-27 08:57:00.870  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{c8c8fd6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.870 10708 10708 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 08:57:00.870 10696 10825 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-27 08:57:00.875  3531  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{588ad0a u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53d07 10763:com.sec.android.widgetapp.locationwidget/u0a22}
,07-27 08:57:00.880 10813 10813 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm
,07-27 08:57:00.880  3531  4446 D WifiNative-wlan0: Setting external_sim to 1
,07-27 08:57:00.880  3531  4446 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
07-27 08:57:00.880  3531  4446 D WifiStateMachine: Setting OUI to DA-A1-19
,07-27 08:57:00.885 10708 10708 I wpa_supplicant: bt_status is set be DISCONNECTED
,07-27 08:57:00.885  3531  4446 E WifiNative-wlan0: do suspend true
,07-27 08:57:00.885  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{588ad0a u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acea2a3 10776:com.samsung.android.snote:sync/u0a160}
,07-27 08:57:00.890  3531  4445 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 08:57:00.890  2916  4374 D CommandListener: Setting iface cfg
07-27 08:57:00.890  2916  4374 D CommandListener: Trying to bring up p2p0
07-27 08:57:00.890  3531  4445 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 08:57:00.890  2916  4367 D Netd    : Iface p2p0 link up
,07-27 08:57:00.890  3531  4445 D SecContentProvider: insert(), uri = 2
07-27 08:57:00.890  3531  3699 D Tethering: interfaceLinkStateChanged p2p0, true
07-27 08:57:00.890  3531  3699 D Tethering: interfaceStatusChanged p2p0, true
07-27 08:57:00.890  3531  4445 D WifiP2pService: P2pEnablingState
,07-27 08:57:00.895  3531  4445 D WifiP2pService: P2pEnablingState{ what=147457 }
07-27 08:57:00.895  3531  4445 D WifiP2pService: P2p socket connection successful
07-27 08:57:00.895  3531  4445 D WifiP2pService: P2pEnabledState
,07-27 08:57:00.895  3531  4445 D SecContentProvider: insert(), uri = 2
,07-27 08:57:00.895  3531  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{588ad0a u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2653b57 7198:tv.peel.smartremote/u0a186}
,07-27 08:57:00.900 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:00.900 10813 10824 D HotspotProvider: CREDENTIAL
07-27 08:57:00.900 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:00.905  3531  4446 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
,07-27 08:57:00.905  3531  3531 D RttService: SCAN_AVAILABLE : 3
07-27 08:57:00.905  3531  4472 E WifiScanningService: could not start HAL
,07-27 08:57:00.905  3531  4445 D WifiP2pService: sending p2p connection changed broadcast: IDLE
07-27 08:57:00.905  3531  4473 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:57:00.905  3531  3531 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-27 08:57:00.905  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{b85022d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.905  3531  3802 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-27 08:57:00.905  3531  4445 D WifiP2pService: create mNetworkAgent
,07-27 08:57:00.905  3531  3802 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-27 08:57:00.905  3531  3802 D WifiDisplayController: disconnect
07-27 08:57:00.905  3531  4445 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
07-27 08:57:00.905  3531  3802 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 08:57:00.905  3531  4446 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-27 08:57:00.905  3531  4446 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
07-27 08:57:00.905  3531  4446 D WifiStateMachine: setFccChannelNative: channel = 0
07-27 08:57:00.905  3531  4446 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-27 08:57:00.910  3531  4448 D HotspotDBHandler: getMethodType
,07-27 08:57:00.910  3531  3531 I ActivityManager: Killing 9969:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #31
,07-27 08:57:00.915  3531  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:00.915  3531  4445 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:00.915  3531  4453 D ConnectivityService: Got NetworkAgent Messenger
07-27 08:57:00.915  3531  4453 E ConnectivityService: updateNetworkInfo()
07-27 08:57:00.915  4515  4515 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No network connection wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020704/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f0201d9/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:00.915  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:00.915  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:00.915  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:00.915  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:00.920  4515  4515 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-27 08:57:00.920  3531  3557 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 08:57:00.920  3531  4453 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:00.920  3531  4453 D ConnectivityService: NetworkAgent connected
07-27 08:57:00.920  3531  4453 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
07-27 08:57:00.920  4515  4515 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 08:57:00.920  3531  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-27 08:57:00.925 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:00.925 10813 10824 D HotspotProvider: CREDENTIAL
07-27 08:57:00.925 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:00.925  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{10292c8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.925 10708 10708 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
07-27 08:57:00.925  3531  3802 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.925 10708 10708 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-27 08:57:00.930  5087  5099 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-27 08:57:00.930  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5819f61 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
,07-27 08:57:00.930  8686  8686 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
07-27 08:57:00.930  8686  8686 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
,07-27 08:57:00.930  8686  8686 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,07-27 08:57:00.930  8686  8686 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 08:57:00.935  8686  8686 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:57:00.935  3531  4448 D HS20StateMachine: credential_id 0method_type2
07-27 08:57:00.935  3531  4448 D HotspotDBHandler: getPPSMONode
,07-27 08:57:00.935  3531  5115 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:00.940  8686  8686 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 08:57:00.940  3531  5679 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:00.940  8686  8686 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,07-27 08:57:00.940  8686  8686 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 08:57:00.940  8686  8686 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 08:57:00.940  8686 10829 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 08:57:00.950  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{d48cf47: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:00.955 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:00.955 10813 10824 D HotspotProvider: CREDENTIAL
07-27 08:57:00.955 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:00.965 10832 10832 E Zygote  : v2
07-27 08:57:00.965 10832 10832 I libpersona: KNOX_SDCARD checking this for 5005
07-27 08:57:00.965 10832 10832 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:00.965 10832 10832 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:00.965 10832 10832 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:00.965 10832 10832 E Zygote  : accessInfo : 0
,07-27 08:57:00.965 10832 10832 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,07-27 08:57:00.965  3531  3685 I ActivityManager: Start proc 10832:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,07-27 08:57:00.970  3531  5112 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,07-27 08:57:00.975  3531  4445 E WifiP2pService: Failed to set my phone number info into probe response
,07-27 08:57:00.980  3531  4445 D WifiNative-p2p0: p2pGetDeviceAddress
,07-27 08:57:00.980  3531  4445 D WifiNative-p2p0: p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,07-27 08:57:00.980  3531  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
,07-27 08:57:00.980  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{f121374: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.980  3531  4445 D WifiP2pService: DeviceAddress: 92:73:1c
,07-27 08:57:00.980  3531  3802 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Note4-1
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  deviceAddress: 92:b6:86:43:73:1c
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  secondary type: null
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  wps: 0
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  grpcapab: 0
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  devcapab: 0
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  status: 3
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  wfdInfo: null
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  groupownerAddress: null
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  GOdeviceName: null
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  interfaceAddress: 
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  SConnectInfo : null
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  contactInfoHash : null
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  ssDevInfo : 0
07-27 08:57:00.980  3531  3802 D WifiDisplayController:  iconIdx : 0
,07-27 08:57:00.985 10832 10832 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:00.985 10832 10832 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:00.985 10696 10825 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
07-27 08:57:00.985 10696 10825 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb33762ed
07-27 08:57:00.985 10696 10825 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb33762ed 
07-27 08:57:00.985 10696 10825 E bt_btm  : btm_ble_set_search_if search_if=4
,07-27 08:57:00.990 10696 10716 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false mAobleSupported = 0
,07-27 08:57:00.990 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:00.990 10813 10824 D HotspotProvider: HOTSPOT
07-27 08:57:00.990 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:00.995 10696 10716 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,07-27 08:57:00.995  3531  4448 D HotspotDBHandler: getPpsMoID
07-27 08:57:00.995  3531  5116 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5819f61 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c57d09d 10832:com.samsung.android.app.FileShareClient/5005}
07-27 08:57:00.995 10696 10716 D bt_hci  : do_postload posting postload work item
07-27 08:57:00.995 10696 10761 I bt_hci  : event_postload
07-27 08:57:00.995 10696 10761 D bt_hwcfg: hw_sco_config
07-27 08:57:00.995 10696 10716 E bt_btif_sock: btif_sock_init: !vhci_init
07-27 08:57:00.995 10696 10761 I bt_vendor: sco_config_cb
07-27 08:57:00.995  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{961d912: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:00.995 10696 10761 I bt_hci  : sco_config_callback postload finished.
07-27 08:57:00.995 10696 10716 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
07-27 08:57:00.995 10696 10716 D bt_bte_conf: Device ID record 1 : primary
07-27 08:57:00.995 10696 10716 D bt_bte_conf:   vendorId            = 0075
07-27 08:57:00.995  3531  4445 D WifiP2pService: sending p2p persistent groups changed broadcast
07-27 08:57:00.995 10696 10716 D bt_bte_conf:   vendorIdSource      = 0001
07-27 08:57:00.995 10696 10716 D bt_bte_conf:   product             = 0100
,07-27 08:57:00.995  3531  4445 D WifiP2pService: InactiveState
07-27 08:57:00.995 10696 10716 D bt_bte_conf:   version             = 0200
07-27 08:57:01.000  3531  4445 D WifiP2pService: InactiveState{ what=143376 }
07-27 08:57:00.995 10696 10716 D bt_bte_conf:   clientExecutableURL = 
07-27 08:57:01.000  3531  4453 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
07-27 08:57:00.995 10696 10716 D bt_bte_conf:   serviceDescription  = 
07-27 08:57:01.000  3531  4445 D WifiP2pService: P2pEnabledState{ what=143376 }
07-27 08:57:00.995 10696 10716 D bt_bte_conf:   documentationURL    = 
,07-27 08:57:00.995 10696 10716 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 08:57:00.995 10696 10716 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-27 08:57:00.995 10696 10716 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 7
07-27 08:57:00.995 10696 10716 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 8709
07-27 08:57:00.995  3531  4445 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
07-27 08:57:01.000 10696 10716 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4358A1 Samsung TR TRE TB with Seattle WAR Core1 2STOPBITS cfg54-0054
07-27 08:57:01.000 10696 10716 D BluetoothDataManager: firmwareVersion from Property : BCM4358A1_V0054.0094.hcd
07-27 08:57:01.000  3531  4453 E ConnectivityService: updateNetworkInfo()
,07-27 08:57:01.000 10696 10713 D bt_stack_manager: event_start_up_stack finished
07-27 08:57:01.000  3531  4445 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
07-27 08:57:01.000 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
07-27 08:57:01.000 10813 10823 D HotspotProvider: FQDN
07-27 08:57:01.000 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.000  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{4b918e3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.000 10696 10716 E BluetoothAdapterState: stateChangeCallback : 1
07-27 08:57:01.000 10696 10712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
07-27 08:57:01.000 10696 10712 D BluetoothAdapterProperties: Setting state to 15
07-27 08:57:01.000 10696 10712 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 08:57:01.000 10696 10712 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:57:01.000 10696 10712 D BluetoothAdapterService: updateAdapterState state is 15
,07-27 08:57:01.000 10696 10712 D BluetoothAdapterService: Autoconnection is available 
07-27 08:57:01.000 10696 10761 I bt_vendor: low_power_mode_cb
07-27 08:57:01.000 10696 10712 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-27 08:57:01.000 10696 10712 I BluetoothAdapterState: Entering BleOnState
,07-27 08:57:01.005  3531  3874 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 08:57:01.005  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{265d999: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.005 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
07-27 08:57:01.005 10813 10823 D HotspotProvider: FQDN
07-27 08:57:01.005 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.030  3531  3874 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-27 08:57:01.030  3531  3801 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 08:57:01.030  3531  3801 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-27 08:57:01.030  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{95a603f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.030 10696 10712 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
07-27 08:57:01.030 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_aaaserver_trustroot
,07-27 08:57:01.030 10813 10823 D HotspotProvider: AAASERVER_TRUST_ROOT
07-27 08:57:01.030 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.035 10696 10712 D BluetoothAdapterProperties: Setting state to 11
07-27 08:57:01.035 10696 10712 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-27 08:57:01.035 10696 10712 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:57:01.035 10696 10712 D BluetoothAdapterService: updateAdapterState state is 11
,07-27 08:57:01.035  3531  3801 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
07-27 08:57:01.035 10696 10712 D BluetoothAdapterService: Autoconnection is available 
07-27 08:57:01.035 10696 10712 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-27 08:57:01.035  3531  4448 D HotspotDBHandler: getAAATrustRoot: Corresponding entry doesnt exist
07-27 08:57:01.035 10696 10712 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:01.035 10696 10712 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 08:57:01.035 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 08:57:01.035  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{4885d0c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.035  3531  3531 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.035  3531  3531 I InputMethodManagerService: [BT Setting State] State =11
,07-27 08:57:01.035 10832 10832 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm
,07-27 08:57:01.035  5133  5133 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:57:01.040  4515  4515 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 08:57:01.040  5570  5570 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:57:01.040  3531  5116 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) visible user=0 )
,07-27 08:57:01.040  3531  7135 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-27 08:57:01.040  3531  3531 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-27 08:57:01.040  3531  3531 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.040  3531  3531 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-27 08:57:01.040  4515  4515 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.040  4515  4515 D BluetoothTile:  getBluetoothState : 11
,07-27 08:57:01.040  4515  4515 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) user=0 )
,07-27 08:57:01.040  4515  6523 D BluetoothTile:  handleUpdatestate:false name:null
07-27 08:57:01.040  4515  6523 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 08:57:01.045  4515  4515 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-27 08:57:01.045 10832 10832 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 08:57:01.045  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
,07-27 08:57:01.050 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 08:57:01.050 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:01.050 10813 10823 D HotspotProvider: CREDENTIAL
07-27 08:57:01.050 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.050 10832 10832 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,07-27 08:57:01.050 10696 10696 D HeadsetService: Received start request. Starting profile...
07-27 08:57:01.050 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
,07-27 08:57:01.050 10696 10696 D HeadsetProvider: make
07-27 08:57:01.055 10696 10696 D HeadsetProvider: HeadsetProvider
07-27 08:57:01.055 10696 10696 I HeadsetProvider: clearAllHeadsetSettings(0)
,07-27 08:57:01.060  3531  5686 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bcb8226 5647:com.samsung.android.providers.context/u0a11}
,07-27 08:57:01.065 10832 10832 D FileShare-Client: Outbound.stopDelayTimer - 
,07-27 08:57:01.070 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 08:57:01.070 10696 10696 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 08:57:01.075 10696 10696 D HeadsetStateMachine: make
,07-27 08:57:01.075  3531  4448 D HotspotDBHandler: getHomeSPInfo
,07-27 08:57:01.075 10696 10696 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 08:57:01.080 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 08:57:01.080  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{cb0b136: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.085  3531  5021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
,07-27 08:57:01.085  8686  8686 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:57:01.095 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 08:57:01.100 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.100 10813 10823 D HotspotProvider: HOTSPOT
07-27 08:57:01.100 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.105 10847 10847 E Zygote  : v2
07-27 08:57:01.105 10847 10847 I libpersona: KNOX_SDCARD checking this for 5005
07-27 08:57:01.105 10847 10847 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:01.105 10847 10847 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:01.105 10847 10847 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:01.110 10847 10847 E Zygote  : accessInfo : 0
07-27 08:57:01.110 10847 10847 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,07-27 08:57:01.110  3531  5021 I ActivityManager: Start proc 10847:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,07-27 08:57:01.115 10696 10696 I bt_bluedroid: get_profile_interface handsfree
,07-27 08:57:01.120 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 08:57:01.125 10847 10847 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:01.125 10847 10847 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:01.125  3531  5021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b2e5da 4515:com.android.systemui/u0a60}
,07-27 08:57:01.130  4515  4515 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.130  4515  4515 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-27 08:57:01.130  3531  4448 D HotspotDBHandler: getHomeOInfo
,07-27 08:57:01.130  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{771d72f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.135  3531  5021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53d07 10763:com.sec.android.widgetapp.locationwidget/u0a22}
,07-27 08:57:01.145  3531  5021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb1703f 5158:com.sec.android.app.shealth:remote/u0a36}
,07-27 08:57:01.155  3531  5110 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5819f61 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{863213c 10847:com.samsung.android.app.FileShareServer/5005}
,07-27 08:57:01.160 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
07-27 08:57:01.160 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homeoilist
07-27 08:57:01.160 10813 10824 D HotspotProvider: HOMEOILIST
,07-27 08:57:01.160 10813 10824 D HotspotProvider: No prepend tags
07-27 08:57:01.160 10696 10696 I DualScoManager: Instantiating Dual Sco Manager
07-27 08:57:01.160 10696 10696 I DualScoManager: Set HeadsetServiceHelper
,07-27 08:57:01.160 10696 10696 D BluetoothAtMessage: createCMTIContentObservers
,07-27 08:57:01.165 10847 10847 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareServer/lib/arm
,07-27 08:57:01.165  3531  5021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9731b0d 10696:com.android.bluetooth/1002}
,07-27 08:57:01.170  3531  4448 D HotspotDBHandler: getHomeOInfo :Corresponding entry doesnt exist
,07-27 08:57:01.170 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:01.170 10696 10712 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 08:57:01.170 10696 10712 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:57:01.170 10696 10712 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 08:57:01.170 10696 10712 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:57:01.170  3531  4448 D HotspotDBHandler: getNetworkIDInfo
07-27 08:57:01.175  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{bceb74b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.175 10847 10847 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 08:57:01.175 10847 10847 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-27 08:57:01.175 10847 10847 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:57:01.175 10847 10847 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:57:01.175 10847 10847 W System.err: 	at com.samsung.android.app.FileShareServer.ServerBroadcastReceiver.onReceive(ServerBroadcastReceiver.java:34)
07-27 08:57:01.175 10847 10847 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3634)
07-27 08:57:01.175 10847 10847 W System.err: 	at android.app.ActivityThread.access$2000(ActivityThread.java:221)
07-27 08:57:01.175 10847 10847 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1876)
07-27 08:57:01.175 10847 10847 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:01.175 10847 10847 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:57:01.175 10847 10847 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7225)
07-27 08:57:01.175 10847 10847 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:01.175 10847 10847 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:57:01.175 10847 10847 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,07-27 08:57:01.185 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homesp_network
,07-27 08:57:01.185 10813 10824 D HotspotProvider: HOMESP_NETWORK
07-27 08:57:01.185 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.185 10696 10696 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@e87c272
,07-27 08:57:01.185  3531  4448 D HotspotDBHandler: getNetworkIDInfo: Corresponding entry doesnt exist
,07-27 08:57:01.185  3531  4448 D HotspotDBHandler: getOtherHomePartner
07-27 08:57:01.190 10696 10696 D HeadsetProvider: setHeadsetDB - Can't find 300 for E0:DB:10:14:E2:XX
,07-27 08:57:01.190  3531  3531 I ActivityManager: Killing 9982:com.sec.android.app.myfiles/u0a53 (adj 15): DHA:empty #31
,07-27 08:57:01.190  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{1df1528: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.195 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_otherhome_partner
07-27 08:57:01.195 10813 10824 D HotspotProvider: HOMESP_OTHERHOME_PARTNER
07-27 08:57:01.195 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.200  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{95e6241: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.200 10696 10696 I HeadsetProvider: setHeadsetDB - E0:DB:10:14:E2:XX, 300, 1, true
07-27 08:57:01.200  3531  4448 D HotspotDBHandler: getOtherHomePartner: Corresponding entry doesnt exist
,07-27 08:57:01.210  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{e65d3e6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.210 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.210 10813 10823 D HotspotProvider: HOTSPOT
07-27 08:57:01.210 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.210  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{1cf7d27: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.210 10696 10696 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@1765a79
07-27 08:57:01.210 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hostspot_backhaul_bandwidth_threshold
07-27 08:57:01.210 10813 10824 D HotspotProvider: BACKHAUL_THRESHOLD
07-27 08:57:01.210 10813 10824 D HotspotProvider: No prepend tags
07-27 08:57:01.210 10696 10696 D HeadsetProvider: setHeadsetDB - Can't find 400 for E0:DB:10:14:E2:XX
,07-27 08:57:01.210  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{a45bd4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.215  3531  4448 D HotspotDBHandler: getMinBackHaulThresholdInfo: Corresponding entry doesnt exist
,07-27 08:57:01.220 10696 10696 I HeadsetProvider: setHeadsetDB - E0:DB:10:14:E2:XX, 400, 1, true
,07-27 08:57:01.220 10696 10846 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-27 08:57:01.225 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_preferredroaming_partnerlist
07-27 08:57:01.225 10813 10824 D HotspotProvider: PREFERRED_ROAMING
07-27 08:57:01.225  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{afc1879: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.225 10813 10824 D HotspotProvider: No prepend tags
07-27 08:57:01.225 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-27 08:57:01.225 10696 10696 E HeadsetService: notifyProfileServiceStateChanged
,07-27 08:57:01.225  3531  4448 D HotspotDBHandler: getPreferredRoamingPartnerInfo: Corresponding entry doesnt exist
,07-27 08:57:01.225  5647  5647 D BluetoothA2dp: Proxy object connected
07-27 08:57:01.225 10696 10696 D A2dpService: Received start request. Starting profile...
07-27 08:57:01.225 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
,07-27 08:57:01.225 10696 10696 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-27 08:57:01.230 10696 10696 I bt_bluedroid: get_profile_interface avrcp
,07-27 08:57:01.230  3531  3531 D BluetoothA2dp: Proxy object connected
,07-27 08:57:01.235 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_tupple
07-27 08:57:01.235 10813 10824 D HotspotProvider: TUPPLE
07-27 08:57:01.235 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.235 10696 10846 D HeadsetStateMachine: Clear mHeadsetBrsf
07-27 08:57:01.235 10696 10846 D HeadsetStateMachine: map size, before remove : 0
07-27 08:57:01.235 10696 10846 D HeadsetStateMachine: map size, after remove: 0
,07-27 08:57:01.240  3531  5022 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.myfiles, Auto Run ON
,07-27 08:57:01.245  3531  4448 D HotspotDBHandler: getProtoPortTupple: Corresponding entry doesnt exist
,07-27 08:57:01.245  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{21cc335: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.245 10696 10696 I Avrcp   : No of Audio players :: 2
07-27 08:57:01.245 10696 10696 I Avrcp   : App Package name is GM
,07-27 08:57:01.250 10696 10696 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-27 08:57:01.250 10696 10696 I Avrcp   : App Package name is SM
,07-27 08:57:01.255 10696 10696 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-27 08:57:01.255 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-27 08:57:01.255 10813 10824 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-27 08:57:01.255 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.255 10696 10696 I Avrcp   : No of Video players :: 2
07-27 08:57:01.255  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{9b773ca: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.255 10696 10696 I Avrcp   : Video App Package name is others
,07-27 08:57:01.255  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{a0093b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.255  3531  4448 D HotspotDBHandler: getPolicyUpdateInfo: Corresponding entry doesnt exist
,07-27 08:57:01.260  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{5961858: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.265 10696 10696 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-27 08:57:01.265 10696 10696 I Avrcp   : Video App Package name is others
,07-27 08:57:01.265 10696 10696 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-27 08:57:01.265 10696 10696 I Avrcp   : Add tempPlayer
07-27 08:57:01.265 10696 10696 V Avrcp   : MediaPlayerInfo: mPlayerId=5
07-27 08:57:01.265 10696 10696 V Avrcp   : no_of_players : 5
07-27 08:57:01.265 10696 10696 I Avrcp   : Total no of players: 5
07-27 08:57:01.265 10696 10696 V Avrcp   : swapping the samsung player with 1st player
,07-27 08:57:01.265 10696 10696 D Avrcp   : Compose Browsing Service Candidate
07-27 08:57:01.265 10696 10696 D Avrcp   : ResolveInfo info ResolveInfo{9692dca com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-27 08:57:01.265 10696 10696 D Avrcp   : Initialize Media Controller
,07-27 08:57:01.265 10696 10696 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-27 08:57:01.270 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_spexclusion_list
07-27 08:57:01.270 10813 10824 D HotspotProvider: SPEXCLUSION_LIST
07-27 08:57:01.270 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.270 10696 10696 E Avrcp   : getActiveSessions
07-27 08:57:01.270  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{8635db1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.270 10696 10696 D Avrcp   : pick active media Controller
07-27 08:57:01.270 10696 10696 D Avrcp   : Get the active Media Controller 
07-27 08:57:01.270 10696 10696 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:57:01.270 10696 10696 D A2dpStateMachine: make
07-27 08:57:01.270  3531  4448 D HotspotDBHandler: getSPExclusionList: Corresponding entry doesnt exist
,07-27 08:57:01.270 10696 10696 I bt_bluedroid: get_profile_interface a2dp
07-27 08:57:01.270 10696 10696 E bt_btif : warning : media task started media_task_refcnt 1 
07-27 08:57:01.270 10696 10696 E bt_btif : warning : no command pending, ignore ack
,07-27 08:57:01.270 10696 10863 D A2dpStateMachine: Enter Disconnected: -2
,07-27 08:57:01.280 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.280 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-27 08:57:01.280 10813 10823 D HotspotProvider: HOTSPOT
07-27 08:57:01.280 10696 10696 E A2dpService: notifyProfileServiceStateChanged
07-27 08:57:01.280 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.280 10696 10696 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 08:57:01.280  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{9f23ed: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.280  3531  4448 D HotspotDBHandler: getRemediationInfo
,07-27 08:57:01.285 10696 10696 D HidService: Received start request. Starting profile...
07-27 08:57:01.285 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
07-27 08:57:01.285 10696 10696 I bt_bluedroid: get_profile_interface hidhost
07-27 08:57:01.285 10696 10696 D HidService: setHidService(): set to: null
07-27 08:57:01.285 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-27 08:57:01.285 10696 10696 E HidService: notifyProfileServiceStateChanged
,07-27 08:57:01.290 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
,07-27 08:57:01.290 10813 10823 D HotspotProvider: HOTSPOT
07-27 08:57:01.290 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.295 10696 10696 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 08:57:01.295  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{702b222: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.295 10696 10696 D HealthService: Received start request. Starting profile...
07-27 08:57:01.295 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
07-27 08:57:01.295 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-27 08:57:01.295 10813 10823 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-27 08:57:01.295 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.295  3531  4448 D HotspotDBHandler: getSubscriptionUpdateInfo: Corresponding entry doesnt exist
,07-27 08:57:01.300 10696 10696 I bt_bluedroid: get_profile_interface health
07-27 08:57:01.300 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-27 08:57:01.300 10696 10696 E HealthService: notifyProfileServiceStateChanged
07-27 08:57:01.300 10696 10696 D HeadsetStateMachine: Try to query the phonestate on bind
07-27 08:57:01.300  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{6b864b3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.300  3531  5110 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 08:57:01.300  3531  5110 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
07-27 08:57:01.300 10696 10696 D HeadsetStateMachine: Proxy object connected
07-27 08:57:01.300  3531  3531 I ActivityManager: Killing 9995:com.google.android.apps.docs/u0a101 (adj 15): DHA:empty #31
07-27 08:57:01.300 10696 10696 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,07-27 08:57:01.305  3531  3531 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:57:01.305 10696 10696 D PanService: Received start request. Starting profile...
07-27 08:57:01.305 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
07-27 08:57:01.305 10696 10696 D BluetoothPanServiceJni: initializeNative(L118): pan
07-27 08:57:01.305 10696 10696 I bt_bluedroid: get_profile_interface pan
,07-27 08:57:01.305 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-27 08:57:01.305 10696 10696 E PanService: notifyProfileServiceStateChanged
07-27 08:57:01.305 10696 10696 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-27 08:57:01.305  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [206]
07-27 08:57:01.305 10696 10696 D HeadsetPhoneState: sendDeviceDataStateChanged
07-27 08:57:01.305  3531  4446 D WifiNative-wlan0: callSECApiInt - ID [307]
07-27 08:57:01.305 10696 10696 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 08:57:01.305 10696 10846 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:57:01.305 10696 10846 E HeadsetStateMachine: Unknown message: 11
07-27 08:57:01.305 10708 10708 I wpa_supplicant: wlan0: CRED-REMOVED 0
07-27 08:57:01.305 10696 10846 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-27 08:57:01.305 10696 10846 E HeadsetStateMachine: Unknown message: 19
07-27 08:57:01.305  3531  4448 D HotspotDBHandler: setUserPriority credid: 0 userPriority:1
,07-27 08:57:01.310 10696 10696 D BluetoothMapService: Received start request. Starting profile...
,07-27 08:57:01.310 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
,07-27 08:57:01.310  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{8ca990f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.310 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,07-27 08:57:01.310 10696 10696 E BluetoothMapService: notifyProfileServiceStateChanged
07-27 08:57:01.310 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:01.310 10813 10824 D HotspotProvider: CREDENTIAL
07-27 08:57:01.310 10813 10824 D HotspotProvider: No prepend tags
07-27 08:57:01.315 10696 10696 V SapService: SapBinder()
,07-27 08:57:01.315 10696 10696 D SapService: Received start request. Starting profile...
07-27 08:57:01.315 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
07-27 08:57:01.315 10696 10696 V SapService: start()
07-27 08:57:01.315 10696 10696 D SapService: Disable sap : false
,07-27 08:57:01.320 10869 10869 E Zygote  : v2
,07-27 08:57:01.320 10869 10869 I libpersona: KNOX_SDCARD checking this for 10131
07-27 08:57:01.320 10869 10869 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-27 08:57:01.320 10869 10869 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:01.320 10869 10869 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:01.320 10869 10869 E Zygote  : accessInfo : 0
07-27 08:57:01.320 10869 10869 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
07-27 08:57:01.325  3531  5686 I ActivityManager: Start proc 10869:com.google.android.apps.maps/u0a131 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-27 08:57:01.330  3531  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
,07-27 08:57:01.330 10696 10696 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,07-27 08:57:01.330 10696 10696 E SapService: notifyProfileServiceStateChanged
,07-27 08:57:01.330  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{86c4788: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.330 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:01.330 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:01.330 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:01.330 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:01.330 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
07-27 08:57:01.330 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:57:01.330 10696 10846 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:57:01.330 10696 10846 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:57:01.330 10696 10846 E HeadsetStateMachine: Unknown message: 11
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:01.330 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:01.330 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:01.330 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:01.330 10696 10696 D BluetoothAdapterService: HID Host service started
,07-27 08:57:01.340 10869 10869 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:01.340 10869 10869 D ActivityThread: Added TimaKeyStore provider
07-27 08:57:01.340  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{f161521: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.340 10813 10868 D HotspotProvider: Inside  update methodcontent://com.samsung.passpoint/hotspot
,07-27 08:57:01.340 10813 10868 D HotspotProvider: HOTSPOT
07-27 08:57:01.340 10696 10696 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:57:01.340 10696 10696 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:57:01.340 10696 10696 D HeadsetPhoneState: sendDeviceDataStateChanged
07-27 08:57:01.340 10696 10696 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 08:57:01.340 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:01.340 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,07-27 08:57:01.340 10696 10846 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:57:01.340 10696 10846 E HeadsetStateMachine: Unknown message: 11
07-27 08:57:01.340 10696 10846 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-27 08:57:01.340 10696 10846 E HeadsetStateMachine: Unknown message: 19
,07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:01.345 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:01.345 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:01.345 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:01.345 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:01.345 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:01.350 10696 10696 E BluetoothAdapterService: handleMessage() - Message: 1
07-27 08:57:01.350 10696 10696 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,07-27 08:57:01.350  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5d3d46 10869:com.google.android.apps.maps/u0a131}
07-27 08:57:01.350 10696 10696 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:01.350 10696 10696 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:01.350 10696 10696 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:01.350 10696 10696 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:01.350  3531  4448 D HotspotDBHandler: getPPSMONode
07-27 08:57:01.350 10696 10712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-27 08:57:01.350 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:01.350 10813 10823 D HotspotProvider: CREDENTIAL
07-27 08:57:01.350 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.355  3531  5112 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,07-27 08:57:01.355  3531  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
07-27 08:57:01.355  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{d829b07: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.355 10696 10712 E BluetoothServiceJni: enableBrEdrNative:
07-27 08:57:01.355 10696 10712 I bt_bluedroid: enable_bredr
07-27 08:57:01.360 10813 10868 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.360 10813 10868 D HotspotProvider: HOTSPOT
07-27 08:57:01.360 10813 10868 D HotspotProvider: No prepend tags
,07-27 08:57:01.360 10869 10869 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
07-27 08:57:01.360  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{a425434: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.360  3531  4448 D HotspotDBHandler: getPpsMoID
,07-27 08:57:01.360 10696 10716 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xb334b9ad
07-27 08:57:01.360 10696 10825 D         : Codec ==> copy capability info [bta_av_co_audio_init:584]
07-27 08:57:01.360 10696 10716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
07-27 08:57:01.360 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
07-27 08:57:01.360 10813 10823 D HotspotProvider: FQDN
07-27 08:57:01.360 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.360 10696 10716 D BluetoothAdapterProperties: Address is:E0:DB:10:14:E2:C0
07-27 08:57:01.360 10696 10716 E BluetoothServiceJni: populateRssiValuesNative
07-27 08:57:01.360 10696 10716 I bt_bluedroid: getModelRssiValues
07-27 08:57:01.360 10696 10716 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-27 08:57:01.360 10696 10716 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,07-27 08:57:01.365  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{81de25d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.365 10813 10868 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
07-27 08:57:01.365 10813 10868 D HotspotProvider: FQDN
07-27 08:57:01.365 10813 10868 D HotspotProvider: No prepend tags
07-27 08:57:01.365  3531  3531 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bluetooth_name
,07-27 08:57:01.365 10696 10716 D BluetoothAdapterProperties: Name is: Note4-1
07-27 08:57:01.365 10696 10716 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:57:01.365 10696 10716 D BluetoothAdapterProperties: Scan Mode:20
07-27 08:57:01.365 10696 10716 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:57:01.365 10696 10716 E bt_btif : btif_handle_bluetooth_enable_evt
07-27 08:57:01.365 10696 10716 E bt_btif : ANT+ socket does not initialize.
07-27 08:57:01.365 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_aaaserver_trustroot
07-27 08:57:01.365 10813 10824 D HotspotProvider: AAASERVER_TRUST_ROOT
07-27 08:57:01.365 10813 10824 D HotspotProvider: No prepend tags
07-27 08:57:01.370 10628 10628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:57:01.370 10696 10716 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-27 08:57:01.370  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{9fe7d2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.370  3531  4448 D HotspotDBHandler: getAAATrustRoot: Corresponding entry doesnt exist
07-27 08:57:01.370 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:01.370 10813 10823 D HotspotProvider: CREDENTIAL
07-27 08:57:01.370 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.370 10696 10716 D IOP_DB_BT: db_open: db_open : handle 3006165008l, read 17911 bytes onto local cache
07-27 08:57:01.370 10696 10716 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-27 08:57:01.370  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{b23e0a3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.370 10696 10716 D IOP_DB_BT: db_query: result 1
07-27 08:57:01.370 10696 10716 I         : iop_db_open: iop_db_open status 0
07-27 08:57:01.370 10696 10716 E BluetoothAdapterState: stateChangeCallback : 17
07-27 08:57:01.370 10696 10712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,07-27 08:57:01.370 10696 10716 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 08:57:01.375 10696 10712 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:57:01.375  3531  4448 D HotspotDBHandler: getHomeSPInfo
07-27 08:57:01.375 10696 10712 D BluetoothAdapterProperties: State =  11
07-27 08:57:01.375 10813 10868 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.375 10813 10868 D HotspotProvider: HOTSPOT
07-27 08:57:01.375 10813 10868 D HotspotProvider: No prepend tags
,07-27 08:57:01.375  3531  4448 D HotspotDBHandler: getHomeOInfo
,07-27 08:57:01.375 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homeoilist
07-27 08:57:01.375 10813 10824 D HotspotProvider: HOMEOILIST
07-27 08:57:01.380  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{dca7fa0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.375 10813 10824 D HotspotProvider: No prepend tags
07-27 08:57:01.375  3531  4879 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-27 08:57:01.380  3531  4448 D HotspotDBHandler: getHomeOInfo :Corresponding entry doesnt exist
07-27 08:57:01.380  3531  4448 D HotspotDBHandler: getNetworkIDInfo
07-27 08:57:01.380  3531  5021 D SecContentProvider: insert(), uri = 2
07-27 08:57:01.380 10813 10868 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homesp_network
07-27 08:57:01.380 10813 10868 D HotspotProvider: HOMESP_NETWORK
07-27 08:57:01.380 10813 10868 D HotspotProvider: No prepend tags
,07-27 08:57:01.380 10696 10716 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-27 08:57:01.380 10696 10716 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:57:01.380 10696 10712 D BluetoothAdapterProperties: Setting state to 12
,07-27 08:57:01.380 10696 10712 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:57:01.380  3531  4448 D HotspotDBHandler: getNetworkIDInfo: Corresponding entry doesnt exist
07-27 08:57:01.380 10696 10716 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 08:57:01.385  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{7db4759: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.385  3531  4448 D HotspotDBHandler: getOtherHomePartner
07-27 08:57:01.385 10628 10628 D BluetoothAdapter: STATE_ON
,07-27 08:57:01.385 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_otherhome_partner
07-27 08:57:01.385 10813 10823 D HotspotProvider: HOMESP_OTHERHOME_PARTNER
07-27 08:57:01.385 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.385  3531  4448 D HotspotDBHandler: getOtherHomePartner: Corresponding entry doesnt exist
07-27 08:57:01.385  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{ff0af1e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.390 10628 10628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-27 08:57:01.390 10696 10712 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 08:57:01.390 10696 10712 D BluetoothAdapterService: updateAdapterState state is 12
07-27 08:57:01.390 10628 10628 D BluetoothAdapter: STATE_ON
,07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:01.390 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:57:01.395 10628 10628 D BluetoothAdapter: STATE_ON
,07-27 08:57:01.395 10628 10628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:57:01.400 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.400 10813 10824 D HotspotProvider: HOTSPOT
07-27 08:57:01.400 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.400 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hostspot_backhaul_bandwidth_threshold
07-27 08:57:01.400 10813 10823 D HotspotProvider: BACKHAUL_THRESHOLD
07-27 08:57:01.400 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.405  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{3e7f5cc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.405  3531  4448 D HotspotDBHandler: getMinBackHaulThresholdInfo: Corresponding entry doesnt exist
07-27 08:57:01.405 10696 10712 V BluetoothAdapterService: start opp service
,07-27 08:57:01.405 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_preferredroaming_partnerlist
,07-27 08:57:01.405 10813 10824 D HotspotProvider: PREFERRED_ROAMING
07-27 08:57:01.405 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.410 10696 10696 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-27 08:57:01.410 10696 10696 I BluetoothPbapService: Handler(): got msg=1
,07-27 08:57:01.410  3531  4448 D HotspotDBHandler: getPreferredRoamingPartnerInfo: Corresponding entry doesnt exist
,07-27 08:57:01.410  3531  7135 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-27 08:57:01.410 10696 10712 D BluetoothAdapterService: Autoconnection is available 
07-27 08:57:01.410 10696 10712 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-27 08:57:01.410 10696 10712 D BluetoothAdapterService: starting service from this receiver
07-27 08:57:01.410  5647  5658 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.410  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{af49f2a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.410  5647  5658 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:57:01.410  5158  5502 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.410  5158  5502 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:01.415 10696 10712 D BluetoothAdapterService: BT on, init HID DEV count : 0
07-27 08:57:01.415 10696 10712 I BluetoothAdapterState: Entering OnState
07-27 08:57:01.415  3531  3801 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.415  3531  3801 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:01.420 10813 10868 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_tupple
07-27 08:57:01.420 10813 10868 D HotspotProvider: TUPPLE
07-27 08:57:01.420 10813 10868 D HotspotProvider: No prepend tags
,07-27 08:57:01.420 10696 10884 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-27 08:57:01.420  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{e2253f7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.420  3531  4448 D HotspotDBHandler: getProtoPortTupple: Corresponding entry doesnt exist
07-27 08:57:01.420  5075  5086 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.420  5075  5086 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:01.420 10696 10707 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.420 10696 10707 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:01.425  5647  5733 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:57:01.425 10628 10639 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.425 10628 10639 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:01.425  3531  3801 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:57:01.425  3531  3801 D BluetoothPan: onBluetoothStateChange on: true
07-27 08:57:01.425  7198  7527 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.425  7198  7527 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:57:01.425  5087  6453 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.425  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{23d3264: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.425  5087  6453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:57:01.425 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-27 08:57:01.425 10813 10823 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-27 08:57:01.425 10813 10823 D HotspotProvider: No prepend tags
,07-27 08:57:01.425 10051 10062 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.425 10051 10062 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:01.425 10696 10884 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:01.425 10696 10884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:57:01.425  3531  4448 D HotspotDBHandler: getPolicyUpdateInfo: Corresponding entry doesnt exist
,07-27 08:57:01.425  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{6c11ccd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.430  4515  5403 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.430  4515  5403 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-27 08:57:01.430  5618  5634 D BluetoothAdapter: onBluetoothStateChange: up=true
07-27 08:57:01.430  5618  5634 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-27 08:57:01.430 10696 10884 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-27 08:57:01.430  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{a8de982: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.430 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_spexclusion_list
07-27 08:57:01.430 10813 10824 D HotspotProvider: SPEXCLUSION_LIST
07-27 08:57:01.430 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.430 10696 10696 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-27 08:57:01.430  3531  3531 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.430  3531  3531 I InputMethodManagerService: [BT Setting State] State =12
07-27 08:57:01.430  3531  3531 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-27 08:57:01.430 10696 10696 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:57:01.430 10696 10696 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:57:01.430 10696 10696 W System.err: 	at com.android.bluetooth.opp.BluetoothOppService.onCreate(BluetoothOppService.java:195)
07-27 08:57:01.430 10696 10696 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3807)
07-27 08:57:01.430 10696 10696 W System.err: 	at android.app.ActivityThread.access$2100(ActivityThread.java:221)
07-27 08:57:01.430 10696 10696 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1882)
07-27 08:57:01.430 10696 10696 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:01.430 10696 10696 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:57:01.430 10696 10696 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7225)
07-27 08:57:01.430 10696 10696 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:01.430 10696 10696 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:57:01.430 10696 10696 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-27 08:57:01.430 10708 10708 I wpa_supplicant: nl80211: Received scan results (13 BSSes)
07-27 08:57:01.435  2916  4367 D Netd    : Iface wlan0 link up
07-27 08:57:01.435 10696 10696 V BtOppService: isOwner == true
07-27 08:57:01.435  4515  4515 D BluetoothTile:  onBluetoothStateChange:
07-27 08:57:01.435  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:01.435  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:01.435 10708 10708 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-27 08:57:01.435 10708 10708 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-27 08:57:01.435 10708 10708 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-27 08:57:01.435  5133  5133 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.435 10708 10708 I wpa_supplicant:    allow  - level is under -85dBm [-34] or selected nid [-1] [0]
,07-27 08:57:01.435  3531  3531 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 08:57:01.435  3531  3531 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
07-27 08:57:01.435 10708 10708 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
07-27 08:57:01.435 10708 10708 I wpa_supplicant:    allow  - level is under -85dBm [-34] or selected nid [-1] [0]
07-27 08:57:01.435 10708 10708 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz level=-34) 
07-27 08:57:01.435  5570  5570 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 08:57:01.440  3531  3531 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-27 08:57:01.440  3531  3531 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.440  3531  3531 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-27 08:57:01.440  3531  4448 D HotspotDBHandler: getSPExclusionList: Corresponding entry doesnt exist
07-27 08:57:01.440  4515  4515 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 08:57:01.445  4515  6523 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:57:01.445  3531  5112 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) visible user=0 )
,07-27 08:57:01.445  3531  7135 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-27 08:57:01.445  4515  4515 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.445  4515  4515 D BluetoothTile:  getBluetoothState : 12
,07-27 08:57:01.450  4515  4515 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) visible user=0 )
07-27 08:57:01.450  4515  6523 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:57:01.450  4515  6523 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 08:57:01.460  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{be9caef: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.465 10813 10868 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.465 10813 10868 D HotspotProvider: HOTSPOT
07-27 08:57:01.465 10813 10868 D HotspotProvider: No prepend tags
,07-27 08:57:01.470  3531  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:01.470  3531  4448 D HotspotDBHandler: getRemediationInfo
,07-27 08:57:01.470 10813 10823 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-27 08:57:01.470 10813 10823 D HotspotProvider: HOTSPOT
07-27 08:57:01.470 10813 10823 D HotspotProvider: No prepend tags
07-27 08:57:01.470  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{7ee4e00: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.475  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{3b6639: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.475 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-27 08:57:01.475 10813 10824 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-27 08:57:01.475 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.490 10900 10900 E Zygote  : v2
07-27 08:57:01.490 10900 10900 I libpersona: KNOX_SDCARD checking this for 10178
07-27 08:57:01.490 10900 10900 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:01.490 10900 10900 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:01.490 10900 10900 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:01.490  3531  3557 I ActivityManager: Start proc 10900:com.android.email/u0a178 for content provider com.android.email/.provider.EmailProvider
,07-27 08:57:01.490  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-27 08:57:01.490  3531  4448 D HotspotDBHandler: getSubscriptionUpdateInfo: Corresponding entry doesnt exist
07-27 08:57:01.490 10900 10900 E Zygote  : accessInfo : 0
,07-27 08:57:01.490 10900 10900 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,07-27 08:57:01.495  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [206]
07-27 08:57:01.495  3531  4446 D WifiNative-wlan0: callSECApiInt - ID [307]
,07-27 08:57:01.495  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [210]
07-27 08:57:01.495  3531  4446 D WifiNative-wlan0: callSECApiVoid - ID [310]
,07-27 08:57:01.495  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 08:57:01.500 10708 10708 I wpa_supplicant: wlan0: CRED-ADDED 0
,07-27 08:57:01.500  3531  4448 I HS20StateMachine: credID(0) returned from supplicant
07-27 08:57:01.500  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{b86147e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.500  3531  4448 I HS20StateMachine: credential ID 0
,07-27 08:57:01.500  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-27 08:57:01.500  3531  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-27 08:57:01.500 10708 10708 I wpa_supplicant: wlan0: CRED-MODIFIED 0 id
,07-27 08:57:01.500  3531  4448 I HS20StateMachine: usernamePasswordObj is not nullnull
,07-27 08:57:01.500  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{9c94ddf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.500  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-27 08:57:01.500  3531  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-27 08:57:01.500 10708 10708 E wpa_supplicant: SIM READ ERROR
07-27 08:57:01.500 10708 10708 I wpa_supplicant: wlan0: CRED-MODIFIED 0 imsi
07-27 08:57:01.500 10708 10708 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 08:57:01.505 10869 10891 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
07-27 08:57:01.505  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-27 08:57:01.505  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{9ea4a2c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.505  3531  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-27 08:57:01.505 10869 10891 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
07-27 08:57:01.505 10708 10708 I wpa_supplicant: wlan0: CRED-MODIFIED 0 update_identifier
07-27 08:57:01.505  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-27 08:57:01.505  3531  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-27 08:57:01.505 10708 10708 I wpa_supplicant: wlan0: CRED-MODIFIED 0 max_bss_load
,07-27 08:57:01.505  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-27 08:57:01.505  3531  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-27 08:57:01.505 10708 10708 I wpa_supplicant: wlan0: CRED-MODIFIED 0 country
,07-27 08:57:01.510  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-27 08:57:01.510  3531  4446 D WifiNative-wlan0: callSECApiString - ID [309]
,07-27 08:57:01.510 10708 10708 I wpa_supplicant: wlan0: CRED-MODIFIED 0 temporary
,07-27 08:57:01.510  3531  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
,07-27 08:57:01.510  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{5632cf5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.510  3531  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-27 08:57:01.510 10708 10708 I wpa_supplicant: wlan0: CRED-MODIFIED 0 priority
,07-27 08:57:01.515  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{d6afa8a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.515 10869 10891 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
07-27 08:57:01.515  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{f9ee8fb: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.515  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{906a371: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.520  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{8063556: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.520 10900 10900 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:01.520 10900 10900 D ActivityThread: Added TimaKeyStore provider
07-27 08:57:01.520  3531  4448 D HotspotDBHandler: setCredentials:credentialType-1credentialID0methodType2old_cred_id0
,07-27 08:57:01.525  3531  3531 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@33b7c73
07-27 08:57:01.525  3531  3531 D BluetoothHeadset: registerMessageListener
,07-27 08:57:01.525  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{6e54fa9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.525 10813 10824 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:01.525 10813 10824 D HotspotProvider: CREDENTIAL
07-27 08:57:01.525 10813 10824 D HotspotProvider: No prepend tags
,07-27 08:57:01.535 10708 10708 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,07-27 08:57:01.535  2916  4367 D Netd    : Iface wlan0 link up
07-27 08:57:01.535  2916  4367 D Netd    : Iface wlan0 link up
07-27 08:57:01.535  2916  4367 D Netd    : Iface wlan0 link up
07-27 08:57:01.535  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:01.535  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:01.540  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:01.540  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
07-27 08:57:01.540  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:01.540  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:01.540 10708 10708 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 08:57:01.540 10708 10708 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,07-27 08:57:01.540 10696 10885 D HeadsetService: registerMessageListener
07-27 08:57:01.540 10708 10708 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
07-27 08:57:01.540  3531  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
07-27 08:57:01.540 10696 10885 D HeadsetService: registerMessageListener
07-27 08:57:01.545  3531  3531 I Telecom : BluetoothManager : register MessageListener
07-27 08:57:01.545  3531  3531 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
07-27 08:57:01.545 10696 10846 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-27 08:57:01.545  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{4c76ccf: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.545 10696 10846 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@86d9fcc
,07-27 08:57:01.545 10813 10823 D HotspotProvider: Inside  update methodcontent://com.samsung.passpoint/hotspot_credentials
07-27 08:57:01.545 10813 10823 D HotspotProvider: CREDENTIAL
07-27 08:57:01.550 10708 10708 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,07-27 08:57:01.550 10708 10708 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
07-27 08:57:01.550 10696 10885 D A2dpStateMachine: getConnectedDevices : size=0
,07-27 08:57:01.550 10708 10708 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 08:57:01.550 10708 10708 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 08:57:01.550 10708 10708 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 08:57:01.550  2916  4367 D Netd    : Iface wlan0 link up
,07-27 08:57:01.555  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:01.555  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:01.560  3531  5116 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:01.565  3531  4448 D HotspotDBHandler: setCredentials: Updation of credential info successful.status:1
07-27 08:57:01.565  3531  4448 D HS20StateMachine: new_credential_id 0
07-27 08:57:01.565  3531  4448 I HS20StateMachine: came to save config
07-27 08:57:01.565  3531  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:01.570  5618  5618 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:57:01.570  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{32a965c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.575  3531  5021 I ActivityManager: Killing 10035:com.sec.android.automotive.drivelink/u0a102 (adj 15): DHA:empty #31
,07-27 08:57:01.575 10869 10896 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 08:57:01.580  3531  4879 D RCPManagerService: exchangeData() failure , invalid userId
07-27 08:57:01.580  3531  4446 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-27 08:57:01.590  3531  5261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db17655 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:01.595  5618  5618 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:57:01.605  3531  5110 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:01.605  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
,07-27 08:57:01.610  3531  4446 V AlarmManager:  remove PendingIntent] PendingIntent{beab692: PendingIntentRecord{d7c6863 android broadcastIntent}}
,07-27 08:57:01.610  3531  4546 D RCPManagerService: exchangeData() failure , invalid userId
07-27 08:57:01.615  3531  3531 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-27 08:57:01.615  3531  3531 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:01.615  3531  3531 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-27 08:57:01.615  3531  4451 I WifiHs20Service: Message received 5007
07-27 08:57:01.615  8686  8686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 08:57:01.620  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{7547519: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.620  3531  4446 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-27 08:57:01.620  3531  4446 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:01.620  3531  4453 E ConnectivityService: updateNetworkInfo()
07-27 08:57:01.620  3531  4453 D ConnectivityService: Got NetworkAgent Messenger
07-27 08:57:01.620  3531  4453 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:01.620  3531  4453 D ConnectivityService: NetworkAgent connected
,07-27 08:57:01.625  2916  4374 D CommandListener: Setting iface cfg
,07-27 08:57:01.635  3531  5110 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.automotive.drivelink, Auto Run ON
,07-27 08:57:01.635  8686  8686 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-27 08:57:01.640  8686  8686 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-27 08:57:01.645  8686  8686 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-27 08:57:01.645  3531  4546 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:01.650  3531  5679 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 08:57:01.655 10696 10927 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-27 08:57:01.655 10696 10927 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:57:01.655 10696 10927 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:57:01.655 10696 10927 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:252)
,07-27 08:57:01.655  3531  5116 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bcb8226 5647:com.samsung.android.providers.context/u0a11}
,07-27 08:57:01.665  3531  5116 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
,07-27 08:57:01.670  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:01.670  5101  5101 D Launcher.Model: reloadBadges entered.
,07-27 08:57:01.670  3531  4446 D WifiStateMachine: Start Dhcp Watchdog 1
,07-27 08:57:01.675 10351 10361 D MethodReflector: notifyChange is called
,07-27 08:57:01.680  3531  3556 D RCPManagerService: exchangeData() failure , invalid userId
07-27 08:57:01.680  5101  5101 D Launcher.Model: reloadBadges entered.
,07-27 08:57:01.680  3531  4898 D RCPManagerService: exchangeData() failure , invalid userId
07-27 08:57:01.680 10351 10361 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-27 08:57:01.680 10351 10361 D BadgeProvider: sendNotify, [notify] : null
,07-27 08:57:01.680 10351 10361 D BadgeProvider: update, getCallingPackage() : com.android.email
07-27 08:57:01.680 10351 10361 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-27 08:57:01.680 10351 10361 D BadgeProvider: update, [uri.query] : null
07-27 08:57:01.680 10351 10361 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-27 08:57:01.680 10351 10361 D BadgeProvider: update, [UpdateCount] : 1
,07-27 08:57:01.685 10696 10696 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
07-27 08:57:01.685  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{c5e73f9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.685  8686  8686 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-27 08:57:01.685  3531  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:01.685 10696 10930 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:01.685 10696 10930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:01.690  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:01.695  8686  8686 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-27 08:57:01.695 10696 10696 D BluetoothSocket: bindListen(): myUserId = 0
,07-27 08:57:01.695 10696 10696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:57:01.695 10696 10934 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:01.695 10696 10934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:01.695 10351 10931 D BadgeProvider: query, [selection] : null
,07-27 08:57:01.700  3531  3546 I art     : Background partial concurrent mark sweep GC freed 127746(9MB) AllocSpace objects, 102(2036KB) LOS objects, 33% free, 32MB/48MB, paused 4.821ms total 117.556ms
,07-27 08:57:01.700 10696 10930 I BtOppRfcommListener: Accept thread started.
,07-27 08:57:01.705  8686  8686 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:57:01.705 10696 10934 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-27 08:57:01.705 10696 10934 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-27 08:57:01.705  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{363414a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.705  8686  8686 E BluetoothHeadset: BTStateChangeCB is registed
07-27 08:57:01.705 10696 10696 D BluetoothSocket: bindListen(): myUserId = 0
07-27 08:57:01.705 10696 10696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:57:01.705  8686  8686 D BluetoothMap: Create BluetoothMap proxy object
,07-27 08:57:01.705 10696 10696 D ObexServerSockets: Succeed to create listening sockets 
07-27 08:57:01.705 10696 10696 D ObexServerSockets: startAccept()
,07-27 08:57:01.705  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{145a931: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.710  3531  4448 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-27 08:57:01.710  3531  4448 D HS20StateMachine: enter : DiscoveringState
,07-27 08:57:01.710  3531  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:01.710 10696 10935 D ObexServerSockets: Accepting socket connection for masId0
07-27 08:57:01.710  8686  8686 D BluetoothSap: Create BluetoothSap proxy object
07-27 08:57:01.710 10696 10936 D ObexServerSockets: Accepting socket connection for masId0
,07-27 08:57:01.715 10696 10696 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-27 08:57:01.715 10696 10696 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-27 08:57:01.715  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{d0993f0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.715 10696 10696 D BluetoothSdpJni: SDP Create record success - handle: 1
07-27 08:57:01.715 10351 10361 D BadgeProvider: query, [selection] : null
,07-27 08:57:01.715  4515  4515 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No network connection wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020704/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f0201d9/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:01.715  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{3f690fa: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.715  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:01.715  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:01.715  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:01.715  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:01.720  8686  8686 D LocalBluetoothProfileManager: PANU : true
,07-27 08:57:01.725  3531  4446 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
07-27 08:57:01.725  3531  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
07-27 08:57:01.725  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{36b7287: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.725  3531  4453 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-27 08:57:01.725  3531  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
07-27 08:57:01.725  3531  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-27 08:57:01.725  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{d0f15b4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.730  8686  8686 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
07-27 08:57:01.730  8686  8686 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 08:57:01.730  8686  8686 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-27 08:57:01.735  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{a61d920: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.735  8686  8686 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:57:01.735  8686  8686 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 08:57:01.735  8686  8686 D BluetoothA2dp: Proxy object connected
07-27 08:57:01.735  8686  8686 D A2dpProfile: Bluetooth service connected
,07-27 08:57:01.740  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b2e5da 4515:com.android.systemui/u0a60}
,07-27 08:57:01.740  4515  4515 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:57:01.740  4515  4515 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-27 08:57:01.750  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a53d07 10763:com.sec.android.widgetapp.locationwidget/u0a22}
,07-27 08:57:01.755 10900 10921 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:01.755 10696 10885 D A2dpStateMachine: getConnectedDevices : size=0
07-27 08:57:01.755  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{a9162d9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.755 10900 10921 D skia    : ---- fAsset->read(0) returned 0
07-27 08:57:01.760 10900 10921 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:01.760  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb1703f 5158:com.sec.android.app.shealth:remote/u0a36}
,07-27 08:57:01.765  8686  8686 D BluetoothMap: Proxy object connected
,07-27 08:57:01.765  8686  8686 D MapProfile: Bluetooth service connected
07-27 08:57:01.765  8686  8686 D BluetoothMap: getConnectedDevices()
,07-27 08:57:01.765  8686  8686 D BluetoothPbap: Proxy object connected
,07-27 08:57:01.770  8686  8686 D PbapServerProfile: Bluetooth service connected
07-27 08:57:01.770  8686  8686 D BluetoothSap: Proxy object connected
,07-27 08:57:01.770  8686  8686 D SapProfile: Bluetooth service connected
07-27 08:57:01.770  8686  8686 D BluetoothInputDevice: Proxy object connected
,07-27 08:57:01.770  8686  8686 D HidProfile: Bluetooth service connected
,07-27 08:57:01.770 10900 10921 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:01.770  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9731b0d 10696:com.android.bluetooth/1002}
,07-27 08:57:01.775 10696 10696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b171b99
07-27 08:57:01.775 10696 10696 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 08:57:01.780  8686  8686 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:57:01.780  8686  8686 D PanProfile: Bluetooth service connected
,07-27 08:57:01.780  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5d3d46 10869:com.google.android.apps.maps/u0a131}
,07-27 08:57:01.790  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{8db649e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.795  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:01.795  5618  5618 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:57:01.805  3531  5679 I ActivityManager: Killing 10051:com.vlingo.midas/u0a34 (adj 15): DHA:empty #31
,07-27 08:57:01.805  8686  8686 D HeadsetProfile: Bluetooth service connected
,07-27 08:57:01.810  5618 10944 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 08:57:01.820  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{7dac38: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.825  4515  4515 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No network connection wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020704/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f0201d9/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:01.825  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:01.825  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:01.825  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:01.825  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:01.825  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ab4a006 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:01.825  5618  5618 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,07-27 08:57:01.835  3531  5110 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4b9411 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b2e5da 4515:com.android.systemui/u0a60}
,07-27 08:57:01.840  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{c716976: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.845  3531  3557 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10178
,07-27 08:57:01.845  3531  3556 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10178
,07-27 08:57:01.850  3531  5021 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10178
,07-27 08:57:01.850  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b2e5da 4515:com.android.systemui/u0a60}
,07-27 08:57:01.850  3531  5679 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10178
,07-27 08:57:01.860  5618 10944 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 08:57:01.860  3531  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
,07-27 08:57:01.860  8686  8686 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 08:57:01.860  8686  8686 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 08:57:01.865  3531  5115 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:01.865  8686  8686 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 08:57:01.865  3531  5116 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:01.865  8686  8686 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-27 08:57:01.865  8686  8686 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 08:57:01.865  8686  8686 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 08:57:01.865  8686 10829 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 08:57:01.865  3531  4879 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
07-27 08:57:01.865  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{b44604d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.870  3531  5679 D ActivityManager: isAutoRunBlockedApp:: com.vlingo.midas, Auto Run ON
,07-27 08:57:01.880  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acea2a3 10776:com.samsung.android.snote:sync/u0a160}
,07-27 08:57:01.880 10776 10776 I ReceiverWifiStateChanged: NETWORK_STATE_CHANGED_ACTION
,07-27 08:57:01.885  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{a02a702: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.890  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2653b57 7198:tv.peel.smartremote/u0a186}
,07-27 08:57:01.900  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1166cca 9261:com.enhance.gameservice/u0a224}
,07-27 08:57:01.910 10950 10950 E Zygote  : v2
07-27 08:57:01.910 10950 10950 I libpersona: KNOX_SDCARD checking this for 10179
07-27 08:57:01.910 10950 10950 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:01.915 10950 10950 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:01.915 10950 10950 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:01.915 10950 10950 E Zygote  : accessInfo : 0
07-27 08:57:01.915 10950 10950 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
,07-27 08:57:01.915  3531  4546 I ActivityManager: Start proc 10950:com.android.exchange/u0a179 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
,07-27 08:57:01.930 10962 10962 E Zygote  : v2
07-27 08:57:01.930 10962 10962 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:01.930 10962 10962 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:01.930 10962 10962 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:01.930 10962 10962 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:01.930 10962 10962 E Zygote  : accessInfo : 0
,07-27 08:57:01.935 10950 10950 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:01.935 10950 10950 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:01.935  3531  3685 I ActivityManager: Start proc 10962:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,07-27 08:57:01.935  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{aadca50: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.945  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{983b449 u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{778314e 10950:com.android.exchange/u0a179}
,07-27 08:57:01.950  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{d86f26f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.950  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{12d3b7c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.950  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{64a4c05: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:01.950 10962 10962 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:01.955 10962 10962 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:01.955  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{1aa145a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.960 10950 10950 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
,07-27 08:57:01.960  3531  4446 E WifiNative-wlan0: do suspend false
,07-27 08:57:01.960  3531  5686 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3a468b 10962:com.sec.android.diagmonagent/1000}
,07-27 08:57:01.960  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{7d09368: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.965  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{b28a381: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.970  3531  4445 D WifiP2pService: InactiveState{ what=143375 }
07-27 08:57:01.970  3531  4445 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:57:01.970  3531  4546 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:01.970  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{8e51c26: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.975 10962 10962 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm
,07-27 08:57:01.990  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{8cf7e14: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.995  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{3af6bd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.995 10976 10976 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:57:01.995  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{376d4b2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:01.995 10962 10962 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-27 08:57:02.000 10976 10976 I dhcpcd  : version 5.5.6 starting
,07-27 08:57:02.000  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{212fc03: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.000 10976 10976 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 08:57:02.000  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{8306780: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.005  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{92541b9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.010  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{cf989fe: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.010  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{6bf555f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.015  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{1f47bac: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.015  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{5cf4075: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.020  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{e60480a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.020  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{6ade87b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.025  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{f03a698: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.030  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{2e06ef1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.030  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{ac2dad6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.035  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{b289157: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.035  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{cd89444: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.040  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{5fc092d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.040  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{ce9ce62: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.045  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{e3aebf3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.045  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{3ecb0b0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.050  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{1bd0b29: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.055  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{19a6eae: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.060  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{50e544f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.060  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{8e427dc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.060  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{d7230e5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.065  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{aa2c7ba: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.070  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{405e66b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.070 10962 10962 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,07-27 08:57:02.075  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{479e5c8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.075  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{c99f661: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.080 10962 10962 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
07-27 08:57:02.080  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{6a5a586: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.080 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-27 08:57:02.080 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:57:02.080 10962 10962 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
07-27 08:57:02.080 10962 10962 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-27 08:57:02.090 10998 10998 E Zygote  : v2
07-27 08:57:02.090 10998 10998 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:02.090 10998 10998 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:02.090 10998 10998 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:02.090 10998 10998 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:02.090 10976 10976 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 08:57:02.090  3531  5115 I ActivityManager: Start proc 10998:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
07-27 08:57:02.090 10976 10976 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-27 08:57:02.090 10998 10998 E Zygote  : accessInfo : 0
07-27 08:57:02.090  3531  5115 I ActivityManager: Killing 10065:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #31
,07-27 08:57:02.095 10976 10976 I dhcpcd  : bssid match
,07-27 08:57:02.095 10976 10976 I dhcpcd  : wlan0: rebinding lease of 192.168.1.113
,07-27 08:57:02.100  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{89a7e47: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.100  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{e2b9674: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.105  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{21e979d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.105  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{9a69412: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.105  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{4f6b7e3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.110  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{5a5a5e0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.110 10998 10998 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:02.110 10998 10998 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:02.110  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{b521099: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.115  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{255df5e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.120  3531  4879 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{952ef3f 10998:com.sec.knox.switcher/1000}
,07-27 08:57:02.120  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{6ef400c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.120  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{eaa1d55: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.125  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{81c936a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.125  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{711405b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.125  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{55650f8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.130  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{a3c39d1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.130 10998 10998 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm
,07-27 08:57:02.130  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{de87c36: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.130 10998 10998 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
,07-27 08:57:02.130 10998 10998 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
07-27 08:57:02.130  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{9998737: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.135 10998 10998 I usagelog: received in receiver
,07-27 08:57:02.135 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-27 08:57:02.135  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{91b84a4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.135  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{df9a20d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
07-27 08:57:02.135 10998 10998 I KnoxUsageLogPro: premStatus:2
,07-27 08:57:02.140  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{5b825c2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.140 10998 10998 I KnoxUsageLogPro: isEulaShown : false
07-27 08:57:02.140 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:57:02.140  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{f55fd3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.140 10976 10976 I dhcpcd  : wlan0: acknowledged 192.168.1.113 from 192.168.1.1
,07-27 08:57:02.150 11010 11010 E Zygote  : v2
07-27 08:57:02.150 11010 11010 I libpersona: KNOX_SDCARD checking this for 10217
07-27 08:57:02.150 11010 11010 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:02.150 11010 11010 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:02.150 11010 11010 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:02.150 11010 11010 E Zygote  : accessInfo : 0
07-27 08:57:02.150 11010 11010 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-27 08:57:02.150  3531  5261 I ActivityManager: Start proc 11010:com.samsung.android.sm.policy/u0a217 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,07-27 08:57:02.150  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-27 08:57:02.155  3531  5261 I ActivityManager: Killing 10081:com.samsung.helphub/1000 (adj 15): DHA:empty #31
,07-27 08:57:02.160  3531  5022 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,07-27 08:57:02.165  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 08:57:02.165  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{bde4710: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.170  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{dab5209: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.170  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{e6dc0e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.170 11010 11010 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:02.170 11010 11010 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:02.170  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{a2c262f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.175  3531  5261 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b00b77 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc8c43c 11010:com.samsung.android.sm.policy/u0a217}
,07-27 08:57:02.180  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{6ae05c5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.180  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{938ab1a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.185 10976 10976 I dhcpcd  : wlan0: leased 192.168.1.113 for 172800 seconds
,07-27 08:57:02.185  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{15ef64b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.185  3531  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:57:02.185  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{d7be828: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.190 11010 11010 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm
07-27 08:57:02.190  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{56e3941: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.190  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{ea65ee6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.190  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{9a4ac27: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.195  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{4bb5ed4: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.200  3531  4879 D ActivityManager: isAutoRunBlockedApp:: com.samsung.helphub, Auto Run ON
,07-27 08:57:02.205  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{6a4287d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.205  3531  4898 I ActivityManager: Killing 10093:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #31
,07-27 08:57:02.210  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{5e98372: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.215  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{6a5e3c3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.215  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{bd99440: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.215  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{4fcf79: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.220  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{3c864be: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.220  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{3f8f91f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.225  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{9e3b46c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.225  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{e74ea35: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.230  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{1220eca: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.230  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{63e083b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.230  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{78dab58: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.235  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{f96f4b1: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.235  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{3ba4d96: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.240  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{1faed17: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.240  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{2de2504: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.240  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{cf52aed: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.245  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{7c5ad22: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.250  3531  3557 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,07-27 08:57:02.255  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{43743b3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.255  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{19a8d70: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.260  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{a8688e9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.260  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{635796e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.260  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{8d8680f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.265  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{e73109c: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.265  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{ab5caa5: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.265  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{3c3be7a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.270  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{abd762b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.270  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{cee9a88: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.275  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{1dd6c21: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.275  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{4bf4846: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.275  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{99b4a07: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.280  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{16d734: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.280  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{583a95d: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.285  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{197a2d2: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.285  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{1987fa3: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.285  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{fe432a0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.290  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{3567e59: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.290  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{8291a1e: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.290  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{a972ff: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.295  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{969d8cc: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.300  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{be7a715: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.300  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{5c8ba2a: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.300  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{5ac401b: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.305  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{5c1b5b8: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.305  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{d289f91: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.305  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{6104ef6: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.310  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{544c2f7: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.310  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{3b87564: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.310  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{8a6a3cd: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.315  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{26a6482: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.315  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{789793: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.315  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{3983d0: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.320  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{186afc9: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.320  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{e5e46ce: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:02.570  3531  4446 E WifiNative-wlan0: do suspend true
,07-27 08:57:02.580  3531  4445 D WifiP2pService: InactiveState{ what=143375 }
07-27 08:57:02.580  3531  4445 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 08:57:02.580  3531  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-27 08:57:02.580  3531  4446 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 08:57:02.580  3531  4446 D WifiStateMachine: VerifyingLinkState enter
07-27 08:57:02.580  3531  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
,07-27 08:57:02.585  3531  4453 E ConnectivityService: updateNetworkInfo()
,07-27 08:57:02.585  3531  4453 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
07-27 08:57:02.590  3531  3531 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-27 08:57:02.590  3531  3531 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.590  3531  3531 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-27 08:57:02.590  3531  4451 I WifiHs20Service: Message received 5007
07-27 08:57:02.590  3531  4453 D ConnectivityService: Adding iface wlan0 to network 502
,07-27 08:57:02.590  3531  4466 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-27 08:57:02.590  3531  4466 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:02.590  3531  4466 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:02.590  3531  4466 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:02.590  3531  4466 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 08:57:02.600  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3a468b 10962:com.sec.android.diagmonagent/1000}
,07-27 08:57:02.600  3531  4466 I WifiManager: isCaptivePortalException
07-27 08:57:02.600 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-27 08:57:02.600  3531  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-27 08:57:02.600  3531  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-27 08:57:02.600  3531  4466 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
07-27 08:57:02.600  3531  4466 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {e417f85}
07-27 08:57:02.600  3531  4466 I WifiManager: isCaptivePortalException
07-27 08:57:02.600  3531  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-27 08:57:02.600  3531  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,07-27 08:57:02.600 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:57:02.600 10962 10962 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
07-27 08:57:02.600 10962 10962 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-27 08:57:02.605  3531  4446 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-27 08:57:02.605  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b2e5da 4515:com.android.systemui/u0a60}
,07-27 08:57:02.605  3531  4446 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,07-27 08:57:02.615  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
,07-27 08:57:02.615  8686  8686 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 08:57:02.620  8686  8686 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 08:57:02.620  3531  4453 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
07-27 08:57:02.620  3531  4446 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:57:02.620  3531  4446 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 08:57:02.620  3531  4453 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,07-27 08:57:02.620  3531  3531 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-27 08:57:02.620  3531  3531 D WifiNative-wlan0: callSECApiVoid - ID [212]
07-27 08:57:02.620  3531  4453 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
07-27 08:57:02.620 10708 10708 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 08:57:02.620 10708 10708 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-27 08:57:02.625  3531  3531 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-27 08:57:02.625  3531  3531 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.625  3531  3531 D HS20StateMachine: SSID : "NG700"
07-27 08:57:02.625  3531  3531 D HS20StateMachine: NetId : 0
07-27 08:57:02.625  3531  3531 D HS20StateMachine: checkifOSUAP  null
07-27 08:57:02.625  3531  3531 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-27 08:57:02.625  3531  4451 I WifiHs20Service: Message received 5007
,07-27 08:57:02.625  3531  4453 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 08:57:02.625  3531  4453 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,07-27 08:57:02.630 10708 10708 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 08:57:02.630 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:57:02.630 10628 10693 I jxcore-log: 
,07-27 08:57:02.635  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{952ef3f 10998:com.sec.knox.switcher/1000}
,07-27 08:57:02.635 10998 10998 I usagelog: received in receiver
07-27 08:57:02.635 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-27 08:57:02.635 10998 10998 I KnoxUsageLogPro: premStatus:2
07-27 08:57:02.635 10998 10998 I KnoxUsageLogPro: isEulaShown : false
07-27 08:57:02.635 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:57:02.640  3531  3531 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:02.640  3531  4453 V NetworkStats: updateIfacesLocked()
07-27 08:57:02.640  3531  4453 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:57:02.640  3531  4453 V NetworkStats: performPollLocked() took 2ms
,07-27 08:57:02.645  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc8c43c 11010:com.samsung.android.sm.policy/u0a217}
,07-27 08:57:02.650  3531  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.650  3531  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
,07-27 08:57:02.655  3531  4444 D NtpTrustedTime: forceRefresh: no connectivity
,07-27 08:57:02.655 10696 11093 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
07-27 08:57:02.655 10696 11093 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-27 08:57:02.655 10696 11093 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-27 08:57:02.655 10696 11093 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:252)
,07-27 08:57:02.655  3531  4453 D ConnectivityService: Not required to send intent.
07-27 08:57:02.655  3531  4453 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.655  3531  4453 E ConnectivityService: updateNetworkInfo()
07-27 08:57:02.655  3531  4453 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 08:57:02.655  3531  4453 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
07-27 08:57:02.655  3531  4453 V NetworkStats: updateIfacesLocked()
07-27 08:57:02.655  3531  4453 V NetworkStats: performPollLocked(flags=0x1)
,07-27 08:57:02.660  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acea2a3 10776:com.samsung.android.snote:sync/u0a160}
,07-27 08:57:02.660 10776 10776 I ReceiverWifiStateChanged: NETWORK_STATE_CHANGED_ACTION
,07-27 08:57:02.660  3531  4453 V NetworkStats: performPollLocked() took 5ms
,07-27 08:57:02.665  3531  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.665  3531  4444 D NtpTrustedTime: forceRefresh: no connectivity
07-27 08:57:02.665  3531  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
07-27 08:57:02.665  3531  4446 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-27 08:57:02.665  3531  4453 D ConnectivityService: scheduleUnvalidatedPrompt 502
07-27 08:57:02.665  3531  4453 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.665  3531  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.665  3531  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:02.665  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,07-27 08:57:02.665  3531  4446 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-27 08:57:02.665  3531 10924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:57:02.670  3531 10924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Connected
,07-27 08:57:02.670  3531 10924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:57:02.670  3531 10924 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
,07-27 08:57:02.670  3531  4453 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-27 08:57:02.675  5087  7512 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-27 08:57:02.675  5087  7512 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
,07-27 08:57:02.675  3531  4453 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
07-27 08:57:02.675  3531  4453 D ConnectivityService: currentScore = 0, newScore = 20
07-27 08:57:02.675  3531  4445 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.675  3531  4453 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.675  3531  4445 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.675  3531  4453 D ConnectivityService:    accepting network in place of null
07-27 08:57:02.675  3531  4445 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:02.675  3531  4453 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.675  3531  4445 D WIFI_P2P: evalRequest
07-27 08:57:02.675  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.675  3531  4445 D WIFI_P2P:   done
07-27 08:57:02.675  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.675  3531  4474 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.675  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-27 08:57:02.675  3531  4474 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-27 08:57:02.675  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.675  3531  4446 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.675  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.675  3531  4474 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:02.675  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-27 08:57:02.675  3531  4474 D Ethernet: evalRequest
07-27 08:57:02.675  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.675  3531  4474 D Ethernet:   done
07-27 08:57:02.675  3531  4453 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:02.675  3531  4446 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.675  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3a468b 10962:com.sec.android.diagmonagent/1000}
07-27 08:57:02.675  3531  4446 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:02.675  3531  4446 D WIFI_UT : evalRequest
07-27 08:57:02.675  3531  4446 D WIFI_UT :   done
07-27 08:57:02.675  3531  4446 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.675  3531  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.675 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-27 08:57:02.675 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-27 08:57:02.675 10962 10962 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
07-27 08:57:02.680 10962 10962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3634 
07-27 08:57:02.680  3531  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:02.680  3531  4446 D WIFI    : evalRequest
07-27 08:57:02.680  3531  4446 D WIFI    :   done
07-27 08:57:02.680  3531  4446 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.680  3531  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.680  3531  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:02.680  3531  4446 D WIFI    : evalRequest
07-27 08:57:02.680  3531  4446 D WIFI    :   done
07-27 08:57:02.680  3531  3685 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2653b57 7198:tv.peel.smartremote/u0a186}
07-27 08:57:02.685  3531  4546 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{97b0cfc u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1166cca 9261:com.enhance.gameservice/u0a224}
07-27 08:57:02.695  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b2e5da 4515:com.android.systemui/u0a60}
07-27 08:57:02.695  2916  4374 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-27 08:57:02.700  3531  5116 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-27 08:57:02.715  3531  5686 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
07-27 08:57:02.715  2916  4374 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-27 08:57:02.715  3531  3556 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
07-27 08:57:02.720  3531  5679 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
07-27 08:57:02.720  3531  3801 D EntConnectivity: Not allowed due to - mEnabled false
07-27 08:57:02.720  3531  4453 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
07-27 08:57:02.725  3531  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.725  3531  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.725  3531  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.725  3531  4453 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
07-27 08:57:02.725  3531  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.725  3531  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.725  3531  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.725  3531  4453 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
07-27 08:57:02.725  3531  4453 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 08:57:02.725  3531  5686 D ConnectivityService: getVpnConfig > userId : 0
07-27 08:57:02.730  4515  4515 D ViewRootImpl: #1 mView = android.widget.LinearLayout{5da4bf2 V.E...... ......I. 0,0-0,0 #10203b0 android:id/toast_layout_root}
07-27 08:57:02.730  3531  3801 D EntConnectivity: Not allowed due to - mEnabled false
07-27 08:57:02.730  3531  4879 D ISSUE_DEBUG: InputChannelName : a1f8f01 Toast
07-27 08:57:02.730  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f6fdbc 8686:com.android.settings/1000}
07-27 08:57:02.730  3531  4879 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
07-27 08:57:02.735  8686  8686 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 08:57:02.735  8686  8686 I NearbySettings: MountReceiver.onReceive - Keep current state
07-27 08:57:02.735  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:02.735  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:02.735  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:02.735  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:02.735  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:02.740  3531  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:02.740  3531  4453 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3531 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:02.740  3531  4453 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.740  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.740  3531  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
07-27 08:57:02.740  3531  4453 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 08:57:02.740  3531  4453 D ConnectivityService: identical MTU - not setting
07-27 08:57:02.740  3531  4453 V NetworkStats: updateIfacesLocked()
07-27 08:57:02.740  3531  4453 V NetworkStats: performPollLocked(flags=0x1)
07-27 08:57:02.740  3531  3531 D Tethering: Tethering got CONNECTIVITY_ACTION
07-27 08:57:02.740  3531  3801 D Tethering: MasterInitialState.processMessage what=3
07-27 08:57:02.740  3531  3531 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.740  3531  4453 V NetworkStats: performPollLocked() took 2ms
07-27 08:57:02.740  3531  4444 D NtpTrustedTime: forceRefresh() from cache miss
07-27 08:57:02.745  3531  4454 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-27 08:57:02.745  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:02.745  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 1000
07-27 08:57:02.745  5087  5099 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-27 08:57:02.745  5087  5099 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-27 08:57:02.745  3531  4454 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
07-27 08:57:02.745  3531  5040 D NtpTrustedTime: forceRefresh() from cache miss
07-27 08:57:02.745  3531  3531 V MARsPolicyManager: DataConnection: true
07-27 08:57:02.745  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:02.745  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 1000
07-27 08:57:02.750  8554  8554 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3d3f5ff and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 (has extras) }
07-27 08:57:02.750  2906  2906 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,07-27 08:57:02.755  8554  8554 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
07-27 08:57:02.755  3531  5686 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.760  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{952ef3f 10998:com.sec.knox.switcher/1000}
07-27 08:57:02.760 10998 10998 I usagelog: received in receiver
07-27 08:57:02.760 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-27 08:57:02.760 10998 10998 I KnoxUsageLogPro: premStatus:2
07-27 08:57:02.760 10998 10998 I KnoxUsageLogPro: isEulaShown : false
07-27 08:57:02.760 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-27 08:57:02.765  3531  5039 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.765  3531  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.765  3531  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
07-27 08:57:02.765  3531  4453 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.765  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.765  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.765  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.765  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.765  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.765  5276  5276 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770 10628 10628 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: Not required to send intent.
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.770  3531  5115 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3531
07-27 08:57:02.770  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-27 08:57:02.775  3531  4453 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] validation  passed
07-27 08:57:02.775  3531  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
07-27 08:57:02.775  3531  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.775 10628 10628 D BluetoothAdapter: STATE_ON
07-27 08:57:02.775  3531  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:02.775  3531  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 08:57:02.775  3531  4445 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.775  3531  4445 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.775  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.775  3531  4445 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:02.775  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-27 08:57:02.775  3531  4445 D WIFI_P2P: evalRequest
07-27 08:57:02.775  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.775  3531  4445 D WIFI_P2P:   done
07-27 08:57:02.775  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.775  3531  4474 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-27 08:57:02.775  3531  4474 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-27 08:57:02.775  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:02.775  3531  4474 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-27 08:57:02.775  3531  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:02.775  3531  4474 D Ethernet: evalRequest
07-27 08:57:02.775  3531  4453 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3531 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4474 D Ethernet:   done
07-27 08:57:02.775  3531  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:02.775  3531  4446 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 08:57:02.775  3531  4446 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4446 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4446 D WIFI_UT : evalRequest
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4446 D WIFI_UT :   done
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.775  3531  4446 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 08:57:02.775  3531  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4446 D WIFI    : evalRequest
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4446 D WIFI    :   done
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.780  3531  4446 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.780  3531  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:02.775  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.780  3531  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.780  3531  4446 D WIFI    : evalRequest
07-27 08:57:02.775  3531  4453 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:02.780  3531  4446 D WIFI    :   done
07-27 08:57:02.775  3531  4453 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 08:57:02.780  5630  5630 E audit   : type=1400 msg=audit(1469602622.780:268): avc:  denied  { ioctl } for  pid=7460 comm="ChromiumNet" path="socket:[39165]" dev="sockfs" ino=39165 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket
07-27 08:57:02.780  5630  5630 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:02.785  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fc8c43c 11010:com.samsung.android.sm.policy/u0a217}
07-27 08:57:02.780  5630  5630 E audit   : type=1300 msg=audit(1469602622.780:268): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=18 a1=8b1b a2=9b3e9468 a3=9b3e9460 items=0 ppid=2960 ppcomm=main pid=7460 auid=4294967295 uid=10064 gid=10064 euid=10064 suid=10064 fsuid=10064 egid=10064 sgid=10064 fsgid=10064 ses=4294967295 tty=(none) comm="ChromiumNet" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:57:02.780  5630  5630 E audit   : type=1327 msg=audit(1469602622.780:268): proctitle="com.google.android.googlequicksearchbox:search"
07-27 08:57:02.780  5630  5630 E audit   : type=1320 msg=audit(1469602622.780:268): 
07-27 08:57:02.780  5630  5630 E audit   : type=1400 msg=audit(1469602622.780:269): avc:  denied  { ioctl } for  pid=7460 comm="ChromiumNet" path="socket:[39166]" dev="sockfs" ino=39166 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket
07-27 08:57:02.780  5630  5630 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:02.780  5630  5630 E audit   : type=1300 msg=audit(1469602622.780:269): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=18 a1=8b1b a2=9b3e9468 a3=9b3e9460 items=0 ppid=2960 ppcomm=main pid=7460 auid=4294967295 uid=10064 gid=10064 euid=10064 suid=10064 fsuid=10064 egid=10064 sgid=10064 fsgid=10064 ses=4294967295 tty=(none) comm="ChromiumNet" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-27 08:57:02.780  5630  5630 E audit   : type=1327 msg=audit(1469602622.780:269): proctitle="com.google.android.googlequicksearchbox:search"
07-27 08:57:02.780  5630  5630 E audit   : type=1320 msg=audit(1469602622.780:269): 
07-27 08:57:02.780  7198  7198 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:57:02.780 10628 10628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 08:57:02.785 10628 10628 D BluetoothAdapter: STATE_ON
07-27 08:57:02.785  4515  4967 D mali_winsys: new_window_surface returns 0x3000,  [1120x201]-format:1
07-27 08:57:02.785 10628 10628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 08:57:02.785  4515  4515 D StatusBar.NetworkController: EthernetConnected: false
07-27 08:57:02.785  4515  4515 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 08:57:02.785  4515  4515 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 08:57:02.785  4515  4515 D StatusBar.NetworkController: updateDataNetType()
07-27 08:57:02.790  4515  4515 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 08:57:02.790  4515  4515 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-27 08:57:02.790  4515  4515 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 08:57:02.790  4515  4515 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
07-27 08:57:02.790  4515  4515 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-27 08:57:02.790  4515  4515 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-27 08:57:02.795  3531  4446 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
07-27 08:57:02.795  3531  4446 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
07-27 08:57:02.795  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{fd5ff94: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
07-27 08:57:02.805  4515  4515 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
07-27 08:57:02.805 10162 11113 W fb4a(:<default>):UserScope: Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
07-27 08:57:02.805 10162 11113 W fb4a(:<default>):UserScope: Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
07-27 08:57:02.805 10162 11113 W fb4a(:<default>):QeInternalImpl: The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
07-27 08:57:02.805  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{2751a3d: PendingIntentRecord{35d95f6 com.facebook.katana broadcastIntent}}
07-27 08:57:02.810  3531  5021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{acea2a3 10776:com.samsung.android.snote:sync/u0a160}
07-27 08:57:02.810 10776 10776 I ReceiverWifiStateChanged: NETWORK_STATE_CHANGED_ACTION
07-27 08:57:02.820  3531  5261 V WindowStateAnimator: Finishing drawing window Window{a1f8f01 u0 d0 Toast}: mDrawState=DRAW_PENDING
07-27 08:57:02.820  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c
07-27 08:57:02.820  4515  4515 D StatusBar.NetworkController: EthernetConnected: false
07-27 08:57:02.820  4515  4515 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 08:57:02.820  4515  4515 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 08:57:02.820  4515  4515 D StatusBar.NetworkController: updateDataNetType()
07-27 08:57:02.820  4515  4515 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 08:57:02.820  4515  4515 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-27 08:57:02.825  4515  4515 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 08:57:02.825  4515  4515 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
07-27 08:57:02.825  4515  4515 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-27 08:57:02.835  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c468b83 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3a468b 10962:com.sec.android.diagmonagent/1000}
,07-27 08:57:02.835 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
07-27 08:57:02.835 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,07-27 08:57:02.840 10962 10962 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 08:57:02.840 10962 10962 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(18/llllIIIllIlIIIIllllI)] timeToActivate is not set. Do not anything.
,07-27 08:57:02.850  3531  3685 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2653b57 7198:tv.peel.smartremote/u0a186}
,07-27 08:57:02.870  3531  5261 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f99660b u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1166cca 9261:com.enhance.gameservice/u0a224}
,07-27 08:57:02.910  3531  3673 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-27 08:57:02.925  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 08:57:02.925  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:02.925  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:02.925  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 08:57:02.925  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 08:57:02.930  3531  3673 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 08:57:02.930  3531  3673 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:02.930 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:57:02.930 10628 10693 I jxcore-log: 
,07-27 08:57:02.940  3531  3673 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:02.940  5087  5099 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-27 08:57:02.940  5087  5099 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-27 08:57:02.940  3531  3673 D TelephonyManager: getDataEnabled: retVal=false
,07-27 08:57:02.945  5087  5375 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@311f8c7, selection=nullselectionArgs=null, sort=name ASC
,07-27 08:57:02.945  5087  5375 D TelephonyProvider: query: match = 5
,07-27 08:57:02.950 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:57:02.950 10628 10693 I jxcore-log: 
,07-27 08:57:02.950  5087  5375 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,07-27 08:57:02.950 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:57:02.950 10628 10693 I jxcore-log: 
,07-27 08:57:02.955  3531  3673 E GpsLocationProvider: No APN found to select.
,07-27 08:57:02.960  5618  5618 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:02.960 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:57:02.960 10628 10693 I jxcore-log: 
,07-27 08:57:02.965  3531  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7607535 10628:com.test.thalitest/u0a7}
,07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:02.965  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:02.965 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:57:02.965 10628 10693 I jxcore-log: 
,07-27 08:57:02.970  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{94e8e37 3531:system/1000}
,07-27 08:57:02.975  2957  2957 D gpsd    : WakeLock(Acquire,GPSD)
,07-27 08:57:02.980  3531 11128 D NtpTrustedTime: forceRefresh() from cache miss
,07-27 08:57:02.980  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:02.980  7413 11127 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
07-27 08:57:02.980  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-27 08:57:02.985  3531  3673 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 20968, reason: UserStart, SyncResult: databaseError: true stats []
,07-27 08:57:02.990  3531  3673 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 320317, reason: UserStart
,07-27 08:57:02.990  3531  5551 D GpsLocationProvider: xtraDownloadRequest
,07-27 08:57:02.995  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:02.995  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 1021
,07-27 08:57:02.995  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:03.010  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{6a4f0d5: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:03.020  3531  4439 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:57:03.060  7413 11123 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-27 08:57:03.110  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c151438 7413:com.google.android.gms/u0a14}
,07-27 08:57:03.115  7413 11141 I iu.SyncManager: SYNC; picasa accounts
,07-27 08:57:03.120  3531  4470 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,07-27 08:57:03.130  7413  7413 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-27 08:57:03.130  7413  7413 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 08:57:03.130  7413 11141 I iu.UploadsManager: num queued entries: 0
,07-27 08:57:03.135  7413 11141 I iu.UploadsManager: num updated entries: 0
07-27 08:57:03.135  7413 11141 I iu.SyncManager: NEXT; no task
,07-27 08:57:03.140  5618  5618 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:03.140  3531  5110 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c151438 7413:com.google.android.gms/u0a14}
,07-27 08:57:03.145  3531 11128 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1469602623805 mCachedNtpElapsedRealtime : 288975 mCachedNtpCertainty : 51
07-27 08:57:03.145  3531 11128 D NtpTrustedTime: getCachedNtpTime() cache hit
07-27 08:57:03.145  3531 11128 D GpsLocationProvider: NTP server returned: 1469602623805 (Wed Jul 27 08:57:03 GMT+02:00 2016) reference: 288975 certainty: 51 system time offset: 658
,07-27 08:57:03.145  3531  4444 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1469602623806 mCachedNtpElapsedRealtime : 288976 mCachedNtpCertainty : 52
07-27 08:57:03.145  3531  5040 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1469602623806 mCachedNtpElapsedRealtime : 288976 mCachedNtpCertainty : 52
07-27 08:57:03.145  3531  5040 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:57:03.145  3531  5040 D AlarmManagerService: Setting time of day to sec=1469602623
07-27 08:57:03.145  3531  5040 D AlarmManager: setTime : 1469602623806 calling from uid: 1000 pid :3531
,07-27 08:57:03.145  3531  5040 D AlarmManagerService: Trying to open a file
07-27 08:57:03.806  3531  5040 V AlarmManager:  remove PendingIntent] PendingIntent{f755d72: PendingIntentRecord{f9db5c3 android broadcastIntent}}
,07-27 08:57:03.145  3531  5040 E AlarmManagerService: File Open Failed
07-27 08:57:03.806  3531  4400 V AlarmManager: Expired Alarm result :65536
07-27 08:57:03.806  3531  4470 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,07-27 08:57:03.806  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:03.806  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-27 08:57:03.811  3531  4400 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=288979 batch.start=291153
,07-27 08:57:03.811  3531  3531 I CAE     : handleMessage(CaTimeChangeManager.java:159) - Time Change, auto old:true new:true
07-27 08:57:03.811  3531  3531 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1469602623817
07-27 08:57:03.811  3531  3531 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
07-27 08:57:03.811  3531  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:03.811  3531  4444 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:57:03.811  3531  4444 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]
07-27 08:57:03.816  3531  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:03.816  3531  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:03.816  3531  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:03.816  3531  4444 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 08:57:03.816  3531  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 08:57:03.816  3531  4444 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-27 08:57:03.816  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
07-27 08:57:03.816  4515  4515 I PERF    : received broadcast android.intent.action.TIME_SET
07-27 08:57:03.816  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:57:03.816  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:57:03.821  3531  3531 V MARsPolicyManager: updateDBResetTimeForTimeChanged -- SystemTime Changed : 657
07-27 08:57:03.821  3531  3531 V MARsPolicyManager: SystemTime Changed Less than 30 min, didn't care!!
07-27 08:57:03.821  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:57:03.821  3531  3531 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:57:03.821  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:03.821  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:03.826  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 08:57:03.826  3531  3531 W System.err: java.io.FileNotFoundException: /data/drm/beforeTime.ini: open failed: EACCES (Permission denied)
07-27 08:57:03.826  3531  3531 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 08:57:03.826  3531  3531 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 08:57:03.826  3531  3531 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
07-27 08:57:03.826  3531  3531 W System.err: 	at java.io.FileReader.<init>(FileReader.java:66)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.server.DrmEventService.getBeforeTime(DrmEventService.java:280)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.server.DrmEventService.handleUserUpdatedTimeUpdation(DrmEventService.java:372)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.server.DrmEventService.userUpdateHandler(DrmEventService.java:262)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.server.DrmEventService.access$200(DrmEventService.java:49)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.server.DrmEventService$3.onReceive(DrmEventService.java:413)
07-27 08:57:03.826  3531  3531 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
07-27 08:57:03.826  3531  3531 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:57:03.826  3531  3531 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:57:03.826  3531  3531 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:508)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:363)
07-27 08:57:03.826  3531  3531 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-27 08:57:03.826  3531  3531 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-27 08:57:03.826  3531  3531 W System.err: Caused by: android.system.ErrnoException: open failed: EACCES (Permission denied)
07-27 08:57:03.826  3531  3531 W System.err: 	at libcore.io.Posix.open(Native Method)
07-27 08:57:03.826  3531  3531 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 08:57:03.826  3531  3531 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 08:57:03.826  3531  3531 W System.err: 	... 17 more
07-27 08:57:03.826  3531  3531 I DrmEventService: handleUserUpdatedTimeUpdation beforeTime -100
07-27 08:57:03.826  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:03.826  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:03.831  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:03.831  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:03.836  3531  5686 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.AccountsChangedReceiver newState = 2 callingPackage = 10014
,07-27 08:57:03.841  3531  5115 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:03.841  4856 11149 D PicasaService: start picasa sync
07-27 08:57:03.841  4856 11149 D PicasaService: end picasa sync
,07-27 08:57:03.856  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5dda79c 10738:com.samsung.android.keyguardwallpaperupdator/u0a127}
,07-27 08:57:03.861 10738 10738 D KeyguardWallpaperUpdator: cancelUpdateWallpaper
,07-27 08:57:03.866  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{f505a3e: PendingIntentRecord{8bd2746 com.samsung.android.keyguardwallpaperupdator broadcastIntent}}
,07-27 08:57:03.871  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:03.891  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa9809f u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:03.901 11154 11154 E Zygote  : v2
07-27 08:57:03.901 11154 11154 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:03.901 11154 11154 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:03.906 11154 11154 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-27 08:57:03.906 11154 11154 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:03.906  3531  3685 I ActivityManager: Start proc 11154:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,07-27 08:57:03.906 11154 11154 E Zygote  : accessInfo : 0
,07-27 08:57:03.926 11154 11154 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:03.926 11154 11154 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:03.926  3531  5115 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{94e8e37 3531:system/1000}
,07-27 08:57:03.936  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{d5f7db5: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:03.941  3531  4879 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f3dc4a 11154:com.policydm/1000}
,07-27 08:57:03.946  3531  3531 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{79920ee 7671:com.samsung.klmsagent/u0a21}
,07-27 08:57:03.946  7671  7671 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 } | timestamp: Wed Jul 27 08:57:03 GMT+02:00 2016
,07-27 08:57:03.956 11154 11154 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm
,07-27 08:57:03.956  7671  7671 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,07-27 08:57:03.961  7671  7671 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
07-27 08:57:03.961  7671  7671 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 08:57:03.961  7671  7671 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-27 08:57:03.961  7671 11168 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 }
07-27 08:57:03.961  7671 11168 D KLMS-2.6.032: : KLMSIntentService(): TIME_CHANGED
07-27 08:57:03.961  7671 11168 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().START : Wed Jul 27 08:57:03 GMT+02:00 2016
,07-27 08:57:03.966  3531  5261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f3dc4a 11154:com.policydm/1000}
,07-27 08:57:03.966  7671 11168 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,07-27 08:57:03.966  7671 11168 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().START
07-27 08:57:03.966  7671 11168 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,07-27 08:57:03.971  7671 11168 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().END
07-27 08:57:03.971  7671 11168 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().END
,07-27 08:57:03.971  7671  7671 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
,07-27 08:57:04.011 11154 11154 I FOTA    : [com.policydm.db.XDB(1493/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-27 08:57:04.021  5618  5618 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:04.021  5618  5618 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:57:04.031  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{e44e497: PendingIntentRecord{73860a7 com.google.android.apps.plus broadcastIntent}}
,07-27 08:57:04.036  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{4c58684: PendingIntentRecord{52eae6d com.google.android.apps.plus broadcastIntent}}
,07-27 08:57:04.056 11154 11154 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(54/<init>)] 
,07-27 08:57:04.056 11154 11154 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:58 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:14 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:20 
,07-27 08:57:04.066 11169 11169 E Zygote  : v2
07-27 08:57:04.066 11169 11169 I libpersona: KNOX_SDCARD checking this for 10215
07-27 08:57:04.066 11169 11169 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:04.066 11169 11169 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.066 11169 11169 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.066  3531  5116 I ActivityManager: Start proc 11169:com.samsung.aasaservice/u0a215 for service com.samsung.aasaservice/.AASAService
07-27 08:57:04.066 11169 11169 E Zygote  : accessInfo : 0
07-27 08:57:04.066 11169 11169 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
07-27 08:57:04.066 11154 11154 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-27 08:57:04.081  3531  5551 D GpsLocationProvider: Fail to getting Ref Locatoin. USE Ref location from listener!!!
,07-27 08:57:04.086 11154 11154 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(236/llIIIIlllllIIllIIllI)] try read dbString
,07-27 08:57:04.091 11154 11154 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:04.091 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:57:04.096 11154 11154 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.PolicyApplication.onCreate:61 android.app.Instrumentation.callApplicationOnCreate:1036 android.app.ActivityThread.handleBindApplication:6317 
,07-27 08:57:04.096  5618 11145 I qtaguid : Tagging socket 43 with tag 1000040700000000{268436487,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:04.101 11169 11169 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 08:57:04.101 11169 11169 D ActivityThread: Added TimaKeyStore provider
07-27 08:57:04.101 11154 11154 I DBG_POLICYDM: [com.sec.android.policyagent.PolicyApplication(64/onCreate)] PolicyApplication onCreated!
,07-27 08:57:04.111 11154 11154 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:57:04.116 11154 11154 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:04.121 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-27 08:57:04.121 11154 11154 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.intent.action.TIME_SET
,07-27 08:57:04.121 11169 11169 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-27 08:57:04.126 11169 11169 D AASAservice: onCreate()
,07-27 08:57:04.126  3531  5110 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8f3dc4a 11154:com.policydm/1000}
,07-27 08:57:04.131  3531  4439 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:04.131 11154 11184 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-27 08:57:04.131 11154 11154 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,07-27 08:57:04.131 11154 11184 I DBG_POLICYDM: [com.policydm.XDMService(382/lllIlIlIIIllIIlIllIl)] a previous network is 0, current network is 2
,07-27 08:57:04.136 11154 11184 E DBG_POLICYDM: [com.policydm.XDMService(384/lllIlIlIIIllIIlIllIl)] network changed.... 
07-27 08:57:04.136 11154 11184 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : true
,07-27 08:57:04.136  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{1cdd5ab: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
07-27 08:57:04.136 11154 11154 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-27 08:57:04.136 11154 11184 I DBG_POLICYDM: [com.policydm.lllIlIlIIIllIIlIllIl(93/run)] SPD SERVICE Start!!
,07-27 08:57:04.136 11154 11184 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.policydm.lllIlIlIIIllIIlIllIl.run:94 java.lang.Thread.run:818 
07-27 08:57:04.136 11154 11154 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
07-27 08:57:04.136 11154 11184 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(196/llIIIIlllllIIllIIllI)] DM Not Init
,07-27 08:57:04.141 11154 11154 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/08/05/11:20:51
,07-27 08:57:04.141 11154 11154 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-27 08:57:04.141 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(122/onCreate)] 
,07-27 08:57:04.141 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(171/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-27 08:57:04.146 11154 11154 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-27 08:57:04.146 11154 11184 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:57:04.146 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(515/IIIIllIlIIlIIIIlllIl)] 
07-27 08:57:04.146 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(520/IIIIllIlIIlIIIIlllIl)] m_WakeLock is acquire!!
,07-27 08:57:04.151 11154 11184 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:04.156 11154 11184 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(316/llIIllllIIlllIIIIlll)] SPD SERVICE Stop!!
,07-27 08:57:04.156 11154 11184 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1311 android.content.ContextWrapper.stopService:611 com.policydm.XDMBroadcastReceiver.llIIllllIIlllIIIIlll:317 com.policydm.XDMService.llllIIIllIlIIIIllllI:288 com.policydm.lllIlIlIIIllIIlIllIl.run:98 
,07-27 08:57:04.156  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cca416 6415:com.android.mms/u0a52}
,07-27 08:57:04.166 11154 11154 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(126/IlIIIllllIIlIIIIIlII)] 
,07-27 08:57:04.166 11154 11185 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:57:04.166 11154 11185 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(191/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,07-27 08:57:04.171 11154 11185 I DBG_POLICYDM: [IIlIlIIIlIIlIlIIIIII(146/llIIIIlllllIIllIIllI)] nSync = 0
,07-27 08:57:04.171 11154 11185 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:57:04.171 11154 11185 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(200/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,07-27 08:57:04.171  3531  3556 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:04.176 11154 11185 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-27 08:57:04.176 11154 11185 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
07-27 08:57:04.176 11154 11185 I DBG_POLICYDM: [com.policydm.ui.IllIIIIIIlIIlIIIlIII(49/llIIIIlllllIIllIIllI)] Indicator id : 7
,07-27 08:57:04.176 11154 11185 I DBG_POLICYDM: [com.policydm.XDMService(572/llllIIIllIlIIIIllllI)] set NotibarState : 7
,07-27 08:57:04.181 11154 11185 I DBG_POLICYDM: [com.policydm.adapter.llllIIIllIlIIIIllllI(98/lllIlIlIIIllIIlIllIl)] 
,07-27 08:57:04.186 11190 11190 E Zygote  : v2
07-27 08:57:04.186 11190 11190 I libpersona: KNOX_SDCARD checking this for 10045
07-27 08:57:04.186 11190 11190 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:04.186 11190 11190 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.186 11190 11190 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.186  3531  5112 I ActivityManager: Start proc 11190:com.osp.app.signin/u0a45 for broadcast-3 com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver
,07-27 08:57:04.191 11190 11190 E Zygote  : accessInfo : 0
,07-27 08:57:04.191 11190 11190 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-27 08:57:04.196 11154 11184 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : false
,07-27 08:57:04.201 11154 11154 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(160/IlIIIllllIIlIIIIIlII)] bExternalStorageAvailable [true]
,07-27 08:57:04.201 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(541/llllllIllIlIlllIIlIl)] 
,07-27 08:57:04.201 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(546/llllllIllIlIlllIIlIl)] m_WakeLock is release!!
,07-27 08:57:04.201 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,07-27 08:57:04.201 11154 11154 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:04.206 11154 11154 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,07-27 08:57:04.206 11154 11154 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-27 08:57:04.206 11154 11154 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,07-27 08:57:04.206 11154 11185 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:04.206 11154 11154 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/08/05/11:20:51
,07-27 08:57:04.206 11154 11154 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-27 08:57:04.211 11154 11154 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
07-27 08:57:04.211 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
07-27 08:57:04.211 11154 11185 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
07-27 08:57:04.211 11154 11154 I DBG_POLICYDM: [com.policydm.XDMService(105/onDestroy)] 
,07-27 08:57:04.211 11154 11185 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(232/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
07-27 08:57:04.216 11190 11190 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.216 11190 11190 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:04.226  3531  5022 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{797a1 11190:com.osp.app.signin/u0a45}
,07-27 08:57:04.231  3531  5022 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{797a1 11190:com.osp.app.signin/u0a45}
,07-27 08:57:04.236 11154 11186 I DBG_POLICYDM: [llllIlIIIllllIIlIlll(208/llllIIIllIlIIIIllllI)] XUI_DM_IDLE_STATE :true
,07-27 08:57:04.241  7413 11202 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-27 08:57:04.241  3531  3557 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:04.241  7413 11202 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-27 08:57:04.241 11154 11186 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-27 08:57:04.246 11190 11190 W System  : ClassLoader referenced unknown path: /system/priv-app/Samsungservice2_xxxhdpi_zero/lib/arm
,07-27 08:57:04.251 11154 11186 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:57:04.256 11154 11186 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/IIIlIIllIlIIllIlllII)] nSessionSaveState:0
,07-27 08:57:04.256 11154 11186 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/IIIlIIllIlIIllIlllII)] nNotiUiEvent:0
,07-27 08:57:04.256 11154 11186 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/IIIlIIllIlIIllIlllII)] nNotiRetryCount:0
,07-27 08:57:04.256 11154 11186 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/IIIlIIllIlIIllIlllII)] Current NOTI NOT SAVED State. EXIT.
,07-27 08:57:04.256 11154 11186 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/IIIIlllIIIlIlIlllIII)] 
,07-27 08:57:04.256 11154 11186 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(39/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-27 08:57:04.261 11154 11186 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(453/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus : 0
,07-27 08:57:04.261  9242  9242 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10147, CallingPid : 9242
,07-27 08:57:04.266  3531  4879 D ConnectivityService: listenForNetwork for Listen from uid/pid:10147/9242 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:57:04.266  3531  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-27 08:57:04.266 11154 11185 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(211/lllIlIlIIIllIIlIllIl)] 
07-27 08:57:04.266  3531  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:04.266  3531  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 08:57:04.266  3531  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:04.281  3531  4879 I ActivityManager: Killing 10105:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #31
,07-27 08:57:04.286  3531  5115 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10147
07-27 08:57:04.286  3531  5115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
07-27 08:57:04.286 11190 11190 I SA      : [SSP] onCreated
,07-27 08:57:04.291  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{333ba7f: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:04.296 11190 11190 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1c8a147
,07-27 08:57:04.296 11154 11185 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/sepolicy
,07-27 08:57:04.296 11154 11185 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/seapp_contexts
07-27 08:57:04.296 11154 11186 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(552/llllIIIllIlIIIIllllI)] Initiated Type: 0
07-27 08:57:04.296 11154 11185 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/property_contexts
,07-27 08:57:04.311 11154 11185 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/file_contexts
,07-27 08:57:04.311 11154 11185 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/service_contexts
,07-27 08:57:04.311 11190 11190 I SA      : [TPM] There is no property file
,07-27 08:57:04.311 11154 11185 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/mac_permissions.xml
,07-27 08:57:04.311 11154 11185 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(235/lllIlIlIIIllIIlIllIl)] Start resumecase for INIT
07-27 08:57:04.311 11190 11190 I SA      : [SCU] isHaveSA() - false
,07-27 08:57:04.316 11190 11190 I SA      : [TPM] getModelProperty : null
07-27 08:57:04.316 11190 11190 I SA      : [TPM] getCSCProperty : null
,07-27 08:57:04.316  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:04.316 11190 11190 I SA      : [DM] FLOATING AMOLED FEATURE: true
07-27 08:57:04.316 11190 11190 I SA      : [DM] PRODUCT AMOLED FEATURE: false
07-27 08:57:04.316 11190 11190 I SA      : [DM] TFT FEATURE: false
07-27 08:57:04.316 11154 11185 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-27 08:57:04.321  9242 11153 I art     : Note: end time exceeds epoch: 
,07-27 08:57:04.321 11190 11190 I SA      : [DM] init START
,07-27 08:57:04.321 11190 11190 I SA      : [DM] This device is not a Vodafone
,07-27 08:57:04.326  5618 11142 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:04.326  5618 11142 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:04.326  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:04.326  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-27 08:57:04.326 11154 11186 I DBG_POLICYDM: [com.policydm.db.XDB(1781/IIIlIIllIlIIllIlllII)] 
,07-27 08:57:04.326  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:04.326  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10147
,07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.331 11190 11190 W ResourceType: Failure getting entry for 0x7f060000 (t=5 e=0) (error -75)
07-27 08:57:04.331 11190 11190 W ResourceType: Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
07-27 08:57:04.331 11190 11190 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
07-27 08:57:04.331 11190 11190 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,07-27 08:57:04.331 11190 11190 W ResourceType: Failure getting entry for 0x7f060004 (t=5 e=4) (error -75)
07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.331 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.336 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.336 11190 11190 W ResourceType: Failure getting entry for 0x7f06000e (t=5 e=14) (error -75)
,07-27 08:57:04.341 11154 11185 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-27 08:57:04.341 11154 11185 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-27 08:57:04.341 11190 11190 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
07-27 08:57:04.341 11190 11190 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
07-27 08:57:04.341 11190 11190 W ResourceType: Failure getting entry for 0x7f060012 (t=5 e=18) (error -75)
,07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.341 11190 11190 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
07-27 08:57:04.341 11190 11190 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
07-27 08:57:04.341 11190 11190 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 08:57:04.341 11190 11190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 08:57:04.346  3531  7135 V AlarmManager:  remove PendingIntent] PendingIntent{4a1fa95: PendingIntentRecord{d134a4c com.google.android.gms broadcastIntent}}
,07-27 08:57:04.346 11190 11190 I SA      : [SCU] isHaveSA() - false
07-27 08:57:04.346 11190 11190 I SA      : support phone number id : false
07-27 08:57:04.346 11190 11190 I SA      : [DM] Supports Ref Jpn : true
07-27 08:57:04.346 11190 11190 I SA      : [DM] init END
07-27 08:57:04.346  3531  5112 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
07-27 08:57:04.346 11190 11190 I SA      : [OR] onReceive log=[SA = 2.1.0306 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = MMB29K M = SM-N910C OKLEFT false DIS MMB29K.N910CXXU2DPE6 PSS = 5.701614807006056  ]
,07-27 08:57:04.351  3531  5112 I ActivityManager: Killing 10120:com.sec.android.widgetapp.tapandpay/u0a190 (adj 15): DHA:empty #31
,07-27 08:57:04.351 11190 11190 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-27 08:57:04.351 11190 11190 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 08:57:04.351 11190 11190 I SA      : [SLFUCHKMGR] constructor called
,07-27 08:57:04.356 11190 11190 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-27 08:57:04.356 11190 11190 I SA      : [OR] == isSIMCardReady false ==
,07-27 08:57:04.356 11190 11190 I SA      : [SCU] == networkStateCheck == true
,07-27 08:57:04.361 11190 11190 I SA      : [DM] getCountryCodeFromCSC : PL
07-27 08:57:04.361 11190 11190 I SA      : isChinaCountryCode : false
07-27 08:57:04.361 11190 11190 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-27 08:57:04.361 11190 11190 I SA      : [OR] == networkStateCheck true ==
,07-27 08:57:04.361  3531  5679 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.tapandpay, Auto Run ON
,07-27 08:57:04.361  5618 11142 I qtaguid : Tagging socket 45 with tag 1000040100000000{268436481,0} uid 10014, pid: 5618, getuid(): 10014
,07-27 08:57:04.366  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{78f47aa: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:04.376 11190 11190 I SA      : [OR] GetMyCountryZoneTask
,07-27 08:57:04.376 11190 11190 I SA      : [OR] onReceive END
,07-27 08:57:04.376 11190 11190 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,07-27 08:57:04.381 11190 11219 I SA      : [SRS] prepareGetMyCountryZone
,07-27 08:57:04.386  3531  4546 I ActivityManager: Start proc 11220:com.sec.android.cloudagent/u0a2 for broadcast-5 com.sec.android.cloudagent/.detector.DetectorReceiver
,07-27 08:57:04.391 11220 11220 E Zygote  : v2
07-27 08:57:04.391 11220 11220 I libpersona: KNOX_SDCARD checking this for 10002
07-27 08:57:04.391 11220 11220 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:04.391 11220 11220 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.391 11220 11220 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.396 11220 11220 E Zygote  : accessInfo : 0
,07-27 08:57:04.396 11220 11220 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.cloudagent 
07-27 08:57:04.396 11154 11186 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-27 08:57:04.396 11190 11219 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-27 08:57:04.401 11190 11219 I SA      : [SSP] query invoked
,07-27 08:57:04.401 11190 11219 I SA      : [TPMU] GetMccFromDB : null
,07-27 08:57:04.406 11190 11219 I SA      : [SCU] getMccFromPreferece mcc = 260
07-27 08:57:04.406 11190 11219 I SA      : [LBE] isSupportCheckDomainRegion : true
07-27 08:57:04.406 11190 11219 I SA      : [TPM] isNoProxy(default) : true
,07-27 08:57:04.416 11154 11186 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(37/llllIIIllIlIIIIllllI)] Noti Exist : false
,07-27 08:57:04.416 11220 11220 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.416 11220 11220 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:04.421 11235 11235 E Zygote  : v2
07-27 08:57:04.421 11235 11235 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:04.421 11235 11235 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:04.421 11235 11235 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.421 11235 11235 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.421  3531  5110 I ActivityManager: Start proc 11235:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.service.ContextAgentReceiver
,07-27 08:57:04.421 11235 11235 E Zygote  : accessInfo : 0
,07-27 08:57:04.431  5618 11142 I qtaguid : Tagging socket 49 with tag 1000040100000000{268436481,0} uid 10014, pid: 5618, getuid(): 10014
,07-27 08:57:04.436  3531  5116 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c50bf38 11220:com.sec.android.cloudagent/u0a2}
,07-27 08:57:04.446 11235 11235 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.446 11235 11235 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:04.451 11220 11220 W System  : ClassLoader referenced unknown path: /system/priv-app/CloudAgent/lib/arm
,07-27 08:57:04.456  3531  5115 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f4ab11 11235:com.samsung.android.sm/1000}
,07-27 08:57:04.476  3531  3556 I ActivityManager: Killing 10134:com.sec.android.app.sbrowser/u0a156 (adj 15): DHA:empty #31
,07-27 08:57:04.481  3531  3556 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5b16cb3 7984:com.sec.spp.push/u0a39}
,07-27 08:57:04.481  7984  7984 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-27 08:57:04.481  7984  7984 E SPPClientService: [SystemStateMoniter] Current Time : 289657
,07-27 08:57:04.481  7984  7984 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-27 08:57:04.491  3531  3556 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23163c0 5858:android.process.media/u0a48}
,07-27 08:57:04.496  5858  5858 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:04.506 11249 11249 E Zygote  : v2
07-27 08:57:04.506 11249 11249 I libpersona: KNOX_SDCARD checking this for 5009
07-27 08:57:04.506 11249 11249 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:04.511 11249 11249 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.511 11249 11249 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.511 11249 11249 E Zygote  : accessInfo : 0
07-27 08:57:04.511 11249 11249 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
,07-27 08:57:04.511  3531  3556 I ActivityManager: Start proc 11249:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
,07-27 08:57:04.511  3531  3556 I ActivityManager: Killing 10150:com.facebook.system/u0a10 (adj 15): DHA:empty #31
,07-27 08:57:04.541  9242 11153 I art     : Note: end time exceeds epoch: 
,07-27 08:57:04.541  3531  5679 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sbrowser, Auto Run ON
,07-27 08:57:04.546 11249 11249 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.546 11249 11249 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:04.556  3531  4898 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6a2ca1 6466:com.android.contacts/u0a23}
,07-27 08:57:04.556  3531  5115 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,07-27 08:57:04.566  3531  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9c52202 11249:com.samsung.android.scloud/5009}
,07-27 08:57:04.581 11262 11262 E Zygote  : v2
07-27 08:57:04.581 11249 11249 W System  : ClassLoader referenced unknown path: /system/priv-app/SCloudService/lib/arm
07-27 08:57:04.581 11262 11262 I libpersona: KNOX_SDCARD checking this for 1000
07-27 08:57:04.581 11262 11262 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:04.581 11262 11262 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.581 11262 11262 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.581 11262 11262 E Zygote  : accessInfo : 0
07-27 08:57:04.581  3531  4898 I ActivityManager: Start proc 11262:com.wssyncmldm/1000 for broadcast-5 com.wssyncmldm/com.samsung.android.app.fotaclient.NetworkReceiver
,07-27 08:57:04.591  3531  4546 D ActivityManager: isAutoRunBlockedApp:: com.facebook.system, Auto Run ON
,07-27 08:57:04.601 11262 11262 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.601 11262 11262 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:04.616  3531  5116 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d84713 11262:com.wssyncmldm/1000}
,07-27 08:57:04.616 11249 11249 I ExternalOEMControlProvider: onCreate
,07-27 08:57:04.621  3531  4439 I ActivityManager: Killing 10235:com.sec.android.app.samsungapps/u0a13 (adj 15): DHA:empty #31
,07-27 08:57:04.636 11262 11262 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
07-27 08:57:04.636 11249 11249 I SCloudService: onCreate
,07-27 08:57:04.641 11262 11262 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,07-27 08:57:04.661  3531  4439 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.samsungapps, Auto Run ON
,07-27 08:57:04.691 11249 11249 I SCloudService: SCloudService Version Info : 1.5.06
07-27 08:57:04.691 11249 11249 I SCloudReceiver: onReceive : android.intent.action.TIME_SET
,07-27 08:57:04.696 11262 11262 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2007/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-27 08:57:04.706 11283 11283 E Zygote  : v2
07-27 08:57:04.706 11283 11283 I libpersona: KNOX_SDCARD checking this for 10014
07-27 08:57:04.706 11283 11283 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:04.706 11283 11283 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.706 11283 11283 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.706 11283 11283 E Zygote  : accessInfo : 0
,07-27 08:57:04.706 11283 11283 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
07-27 08:57:04.706  3531  5115 I ActivityManager: Start proc 11283:com.google.android.gms.unstable/u0a14 for service com.google.android.gms/.droidguard.DroidGuardService,
,07-27 08:57:04.716  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{57afc2b 9315:com.sec.android.app.shealth/u0a36}
,07-27 08:57:04.741 11249 11281 E SCLOUD_ERR- Time Manager : Time Difference not stored. 
07-27 08:57:04.741 11249 11281 E SCLOUD_ERR- Time Manager : android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
07-27 08:57:04.741 11249 11281 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLongForUser(Settings.java:2031)
07-27 08:57:04.741 11249 11281 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLong(Settings.java:2021)
07-27 08:57:04.741 11249 11281 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.utils.TimeManager.updateTimeSettings(TimeManager.java:89)
07-27 08:57:04.741 11249 11281 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.receivers.SCloudReceiver$6.run(SCloudReceiver.java:202)
07-27 08:57:04.741 11249 11281 E SCLOUD_ERR- Time Manager : 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:57:04.741  3531  5686 I ActivityManager: Killing 10216:com.facebook.appmanager/u0a110 (adj 15): DHA:empty #31
,07-27 08:57:04.746 11283 11283 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.746 11283 11283 D ActivityThread: Added TimaKeyStore provider
07-27 08:57:04.746 11262 11262 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,07-27 08:57:04.751 11262 11262 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,07-27 08:57:04.751 11262 11262 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,07-27 08:57:04.751  3531  5686 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb1703f 5158:com.sec.android.app.shealth:remote/u0a36}
,07-27 08:57:04.771  3531  5686 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb1703f 5158:com.sec.android.app.shealth:remote/u0a36}
,07-27 08:57:04.786 11262 11262 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3203/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-27 08:57:04.791 11262 11262 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3255/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-27 08:57:04.801 11262 11262 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,07-27 08:57:04.811  3531  5021 D ActivityManager: isAutoRunBlockedApp:: com.facebook.appmanager, Auto Run ON
07-27 08:57:04.811 11283 11283 I MultiDex: VM with version 2.1.0 has multidex support
07-27 08:57:04.811 11283 11283 I MultiDex: install
07-27 08:57:04.811 11283 11283 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:57:04.841 11262 11304 I FOTA_AGENT: [com.samsung.android.app.fotaclient.lllIlIlIIIllIIlIllIl(92/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:04.851  3531  3546 I art     : Background partial concurrent mark sweep GC freed 115060(6MB) AllocSpace objects, 15(300KB) LOS objects, 33% free, 31MB/46MB, paused 3.036ms total 115.524ms
,07-27 08:57:04.856 11305 11305 E Zygote  : v2
07-27 08:57:04.856 11305 11305 I libpersona: KNOX_SDCARD checking this for 10004
07-27 08:57:04.856 11305 11305 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.856 11305 11305 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:04.856 11305 11305 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.856 11305 11305 E Zygote  : accessInfo : 0
07-27 08:57:04.861 11305 11305 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,07-27 08:57:04.861  3531  5110 I ActivityManager: Start proc 11305:com.google.android.apps.photos/u0a4 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-27 08:57:04.886 11305 11305 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.886 11305 11305 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:04.891 11283 11283 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-27 08:57:04.896  3531  7135 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{52ea726 11305:com.google.android.apps.photos/u0a4}
,07-27 08:57:04.906  5158  5158 D HealthDataStore: Service for HealthDataStore is connected
07-27 08:57:04.906  5158  5158 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-27 08:57:04.911 11283 11283 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-27 08:57:04.911 11283 11283 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-27 08:57:04.911  3531  5110 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{952ef3f 10998:com.sec.knox.switcher/1000}
,07-27 08:57:04.911 10998 10998 I usagelog: received in receiver
07-27 08:57:04.911 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.TIME_SET myUserId=0
07-27 08:57:04.911 10998 10998 I KnoxUsageLogPro: premStatus:2
,07-27 08:57:04.911 10998 10998 I KnoxUsageLogPro: isEulaShown : false
07-27 08:57:04.911 10998 10998 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 08:57:04.916 11283 11283 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:57:04.916  5158  5158 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
07-27 08:57:04.916  5158  5158 E HealthDataStore: disconnectService: Context instance is invalid
,07-27 08:57:04.926 11305 11305 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-27 08:57:04.931 11318 11318 E Zygote  : v2
07-27 08:57:04.931 11318 11318 I libpersona: KNOX_SDCARD checking this for 10163
07-27 08:57:04.931 11318 11318 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:04.931 11318 11318 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:04.931  3531  5110 I ActivityManager: Start proc 11318:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 for broadcast-3 com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider
07-27 08:57:04.931 11318 11318 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:04.936 11318 11318 E Zygote  : accessInfo : 0
,07-27 08:57:04.936 11318 11318 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.SPlannerAppWidget 
,07-27 08:57:04.941 11283 11283 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:57:04.961 11283 11283 D ChimeraCfgMgr: Reading stored module config
,07-27 08:57:04.966 11318 11318 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:04.966 11318 11318 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:04.976  3531  3556 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6978114 11318:com.sec.android.widgetapp.SPlannerAppWidget/u0a163}
,07-27 08:57:05.011  3531  5115 I ActivityManager: Killing 9783:com.android.defcontainer/u0a5 (adj 15): DHA:empty #31
,07-27 08:57:05.016 11318 11318 W System  : ClassLoader referenced unknown path: /system/app/SPlannerWidget_M_OS_UPG_Transparent/lib/arm
,07-27 08:57:05.021 11283 11331 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-27 08:57:05.031  5618 11142 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:05.031  5618 11142 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:05.031  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:05.031  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-27 08:57:05.036  5618 11142 I qtaguid : Tagging socket 50 with tag 1000120300000000{268440067,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:05.041  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{3a0645f: PendingIntentRecord{5eba188 com.android.bluetooth broadcastIntent}}
,07-27 08:57:05.041 11337 11337 E Zygote  : v2
07-27 08:57:05.041 11337 11337 I libpersona: KNOX_SDCARD checking this for 10164
07-27 08:57:05.041 11337 11337 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:05.041  3531  3557 I ActivityManager: Start proc 11337:com.android.calendar/u0a164 for broadcast-3 com.android.calendar/.alerts.AlertReceiver
,07-27 08:57:05.041 11337 11337 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:05.046 11337 11337 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:05.046 11337 11337 E Zygote  : accessInfo : 0
,07-27 08:57:05.046 11337 11337 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.calendar 
,07-27 08:57:05.056  3531  5112 I ActivityManager: Killing 10460:com.mobeam.barcodeService/1000 (adj 15): DHA:empty #31
,07-27 08:57:05.056  2923  4379 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:11283)
,07-27 08:57:05.076 11337 11337 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:05.076 11337 11337 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:05.076  9242 11153 I art     : Note: end time exceeds epoch: 
,07-27 08:57:05.081 11190 11219 I SA      : [RC New] Execute method=[GET] start
07-27 08:57:05.081  9242 11153 I art     : Note: end time exceeds epoch: 
,07-27 08:57:05.086  2923  4460 D WVCdm   : Instantiating CDM.
,07-27 08:57:05.091  2923  2923 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:11283)
07-27 08:57:05.091  2923  2923 I WVCdm   : CdmEngine::OpenSession
07-27 08:57:05.091  2923  2923 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-27 08:57:05.091  3531  3556 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,07-27 08:57:05.096  2923  2923 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-27 08:57:05.101  2923  2923 E wv_dash : No saved usage table. Creating new table.
,07-27 08:57:05.101  3531  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{210e77b 11337:com.android.calendar/u0a164}
,07-27 08:57:05.106  3531  3557 D ActivityManager: isAutoRunBlockedApp:: com.mobeam.barcodeService, Auto Run ON
,07-27 08:57:05.116  5618 11142 I qtaguid : Tagging socket 53 with tag 1000120300000000{268440067,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:05.116 11337 11337 W System  : ClassLoader referenced unknown path: /system/app/SPlanner_M_OS_UPG/lib/arm
,07-27 08:57:05.126  2923  2923 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,07-27 08:57:05.141 11190 11219 I SA      : [RC New] Security=[true]
,07-27 08:57:05.146 11190 11219 I System.out: Thread-1063(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
07-27 08:57:05.146 11190 11219 I System.out: Thread-1063(ApacheHTTPLog):isSBSettingEnabled false
07-27 08:57:05.146 11190 11219 I System.out: Thread-1063(ApacheHTTPLog):isShipBuild true
07-27 08:57:05.146 11190 11219 I System.out: Thread-1063(ApacheHTTPLog):getDebugLevel 0x4f4c
07-27 08:57:05.146 11190 11219 I System.out: Thread-1063(ApacheHTTPLog):Smart Bonding Setting is false
07-27 08:57:05.146 11190 11219 I System.out: Thread-1063(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 08:57:05.146  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:05.146  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10045
,07-27 08:57:05.151  2923  2923 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-27 08:57:05.156  2923  3996 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 08:57:05.156  2923  3996 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-27 08:57:05.156  2923  3996 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-27 08:57:05.156  2923  3996 D WVCdm   : PrepareKeyRequest: nonce=2035060742
,07-27 08:57:05.171  4626  6618 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 08:57:05.196  3531  5021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{210e77b 11337:com.android.calendar/u0a164}
,07-27 08:57:05.211 11362 11362 E Zygote  : v2
07-27 08:57:05.211 11362 11362 I libpersona: KNOX_SDCARD checking this for 10047
07-27 08:57:05.211 11362 11362 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:05.211 11362 11362 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:05.211 11362 11362 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:05.211 11362 11362 E Zygote  : accessInfo : 0
,07-27 08:57:05.211 11362 11362 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.providers.calendar 
,07-27 08:57:05.216  3531  4898 I ActivityManager: Start proc 11362:com.android.providers.calendar/u0a47 for content provider com.android.providers.calendar/.CalendarProvider2
,07-27 08:57:05.216  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-27 08:57:05.216 11305 11305 W Primes  : Memory instrumentations are turned off.
,07-27 08:57:05.221  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 08:57:05.231 11362 11362 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:05.231 11362 11362 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:05.231 11375 11375 E Zygote  : v2
07-27 08:57:05.231 11375 11375 I libpersona: KNOX_SDCARD checking this for 10139
07-27 08:57:05.231 11375 11375 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:05.231 11375 11375 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:05.231 11375 11375 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:05.231  3531  5261 I ActivityManager: Start proc 11375:com.sec.penup/u0a139 for broadcast-3 com.sec.penup/.ui.notification.TimeFormatChangedReceiver
07-27 08:57:05.231 11375 11375 E Zygote  : accessInfo : 0
07-27 08:57:05.231 11375 11375 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.sec.penup 
,07-27 08:57:05.241  9242 11153 I art     : Note: end time exceeds epoch: 
,07-27 08:57:05.246  9242 11153 I art     : Note: end time exceeds epoch: 
,07-27 08:57:05.246 11375 11375 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:05.246 11375 11375 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:05.251 11305 11305 W Primes  : Timer instrumentations are turned off.
,07-27 08:57:05.256  3531  5115 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e0525d6 11375:com.sec.penup/u0a139}
,07-27 08:57:05.261 11305 11305 W Primes  : Crash monitoring is turned off.
,07-27 08:57:05.261 11362 11362 W System  : ClassLoader referenced unknown path: /system/priv-app/SecCalendarProvider/lib/arm
,07-27 08:57:05.266 11283 11295 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:05.266 11283 11295 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:05.266 11305 11305 W Primes  : Network monitoring is turned off.
07-27 08:57:05.266 11305 11305 W Primes  : Package metrics are turned off by default
,07-27 08:57:05.271  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:05.271  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
07-27 08:57:05.271 11375 11375 W System  : ClassLoader referenced unknown path: /system/app/PENUP/lib/arm
,07-27 08:57:05.271 11283 11295 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 11283, getuid(): 10014
,07-27 08:57:05.291  3531  7135 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{52ea726 11305:com.google.android.apps.photos/u0a4}
,07-27 08:57:05.306  3531  7135 I ActivityManager: Killing 9274:com.android.vending/u0a31 (adj 15): DHA:empty #31
,07-27 08:57:05.311  3531  7135 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73bb8fa 8332:com.sec.android.app.SmartClipService/u0a185}
,07-27 08:57:05.316  3531  5116 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:05.316  3531  5686 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:05.331  3531  7135 I ActivityManager: Start proc 11393:com.google.android.apps.magazines/u0a136 for broadcast-5 com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-27 08:57:05.336 11393 11393 E Zygote  : v2
07-27 08:57:05.336 11393 11393 I libpersona: KNOX_SDCARD checking this for 10136
07-27 08:57:05.336 11393 11393 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:05.336 11393 11393 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:05.336 11393 11393 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:05.336 11393 11393 E Zygote  : accessInfo : 0
,07-27 08:57:05.336 11393 11393 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.magazines 
,07-27 08:57:05.361 11393 11393 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:05.361 11393 11393 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:05.376  3531  3557 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a6a56b 11393:com.google.android.apps.magazines/u0a136}
,07-27 08:57:05.381  3531  5679 D ActivityManager: isAutoRunBlockedApp:: com.android.vending, Auto Run ON
,07-27 08:57:05.391 11393 11393 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-27 08:57:05.396  3531  5021 I ActivityManager: Killing 9843:com.samsung.android.sm.provider/1000 (adj 15): DHA:empty #31
,07-27 08:57:05.401  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{e1d38c8: PendingIntentRecord{c6e4d61 com.sec.penup broadcastIntent}}
,07-27 08:57:05.401 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:57:05.401 10628 10693 I jxcore-log: 
,07-27 08:57:05.411 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:57:05.411 10628 10693 I jxcore-log: 
07-27 08:57:05.411 11375 11411 I GMPM    : App measurement is starting up
,07-27 08:57:05.416 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:57:05.416 10628 10693 I jxcore-log: 
,07-27 08:57:05.421 11375 11411 E GMPM    : getGoogleAppId failed with status: 10
,07-27 08:57:05.421 11375 11411 E GMPM    : Uploading is not possible. App measurement disabled
,07-27 08:57:05.421  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{90b086: PendingIntentRecord{c6e4d61 com.sec.penup broadcastIntent}}
,07-27 08:57:05.431  9242 11153 I art     : Note: end time exceeds epoch: 
07-27 08:57:05.431  9242 11153 I art     : Note: end time exceeds epoch: 
,07-27 08:57:05.441  2923  4460 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:11283)
07-27 08:57:05.441  2923  4460 I WVCdm   : CdmEngine::CloseSession
,07-27 08:57:05.451  3531  5679 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.provider, Auto Run ON
,07-27 08:57:05.461 11375 11412 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:05.461 11375 11412 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:05.461  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:05.461  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10139
,07-27 08:57:05.471 11375 11375 D Utility : [PENUP] version : 2.0.21, code : 202100000, commit : 0000000000000000000000000000000000000000, branch : master
07-27 08:57:05.471 11375 11375 D Utility : [PENUP] density level : XXXHIGH, xdpi : 515.154, ydpi : 520.192
,07-27 08:57:05.481 11393 11393 I MultiDex: VM with version 2.1.0 has multidex support
07-27 08:57:05.481 11393 11393 I MultiDex: install
07-27 08:57:05.481 11393 11393 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:57:05.541 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:57:05.541 10628 10693 I jxcore-log: 
,07-27 08:57:05.586  3531  4546 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10147
,07-27 08:57:05.586  3531  4546 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,07-27 08:57:05.591  3531  6657 D SSRM:n  : SIOP:: AP = 330, PST = 274 (W:10), LCD = 0
,07-27 08:57:05.596 11375 11375 E NotiManager: [PENUP][SERVER][Integer.java][invalidInt][138] [Invalid int: ""] [java.lang.NumberFormatException: Invalid int: ""]
,07-27 08:57:05.611  5618 11142 I qtaguid : Untagging socket 50
,07-27 08:57:05.621 11393 11393 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-27 08:57:05.621 11393 11393 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:57:05.621 11393 11393 I GAv4    :   adb logcat -s GAv4
,07-27 08:57:05.631  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{b9ec455: PendingIntentRecord{129ae6a com.google.android.apps.magazines broadcastIntent}}
,07-27 08:57:05.631 11393 11393 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:05.636 11393 11393 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:05.641 11283 11295 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 11283, getuid(): 10014
,07-27 08:57:05.651 11393 11437 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:05.706  5618 11142 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:05.706  5618 11142 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:05.706  5618 11142 I qtaguid : Tagging socket 50 with tag 1000120300000000{268440067,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:05.711  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b4ea6b3 10717:com.samsung.android.securitylogagent/1000}
,07-27 08:57:05.711 10717 10717 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 08:57:05.711 10717 10717 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 08:57:05.711 10717 10717 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 08:57:05.711  3531  5021 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:05.716  3531  4546 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:05.726 11447 11447 E Zygote  : v2
07-27 08:57:05.726 11447 11447 I libpersona: KNOX_SDCARD checking this for 10191
07-27 08:57:05.726 11447 11447 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:05.726 11447 11447 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:05.726 11447 11447 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:05.726 11447 11447 E Zygote  : accessInfo : 0
,07-27 08:57:05.726 11447 11447 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.taskmanager 
,07-27 08:57:05.726  3531  7135 I ActivityManager: Start proc 11447:com.sec.android.app.taskmanager/u0a191 for broadcast-3 com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver
,07-27 08:57:05.726  3531  7135 I ActivityManager: Killing 10832:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #31
,07-27 08:57:05.741 11447 11447 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:05.741 11447 11447 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:05.751  3531  5022 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99a6cc5 11447:com.sec.android.app.taskmanager/u0a191}
,07-27 08:57:05.761 11447 11447 W System  : ClassLoader referenced unknown path: /system/app/TaskManager/lib/arm
,07-27 08:57:05.771  3531  3557 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,07-27 08:57:05.796 11472 11472 E Zygote  : v2
07-27 08:57:05.796 11472 11472 I libpersona: KNOX_SDCARD checking this for 10094
07-27 08:57:05.796 11472 11472 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:05.796 11472 11472 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:05.796 11472 11472 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:05.801 11472 11472 E Zygote  : accessInfo : 0
,07-27 08:57:05.801 11472 11472 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.clockpackage 
07-27 08:57:05.801  3531  4879 I ActivityManager: Start proc 11472:com.sec.android.app.clockpackage/u0a94 for broadcast-3 com.sec.android.app.clockpackage/.alarm.AlarmReceiver
,07-27 08:57:05.816 11472 11472 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:05.816 11472 11472 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:05.826  3531  5115 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{942861a 11472:com.sec.android.app.clockpackage/u0a94}
,07-27 08:57:05.826  3531  5686 I ActivityManager: Killing 10847:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #31
,07-27 08:57:05.841 11472 11472 W System  : ClassLoader referenced unknown path: /system/app/ClockPackage_MUPG_T/lib/arm
,07-27 08:57:05.846  5618 11142 I qtaguid : Untagging socket 50
,07-27 08:57:05.876 11393 11393 I NSApplication: Starting up...
,07-27 08:57:05.881  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{389c740: PendingIntentRecord{7df8679 com.sec.android.app.clockpackage broadcastIntent}}
,07-27 08:57:05.886  3531  5112 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,07-27 08:57:05.891  3531  5110 D SettingsProvider: isChangeAllowed() SettingsProvider : name = next_alarm_formatted
07-27 08:57:05.891  3531  5110 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 08:57:05.891  3531  5110 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-27 08:57:05.891  3531  5110 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 08:57:05.891  3531  5110 D SettingsProvider: selectionArgs: false
07-27 08:57:05.891  3531  5110 D SettingsProvider: selectionArgs: 10094
07-27 08:57:05.896  3531  5110 D SettingsProvider: ret = -1
,07-27 08:57:05.916  3531  5022 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4d46240 9242:com.google.android.apps.plus/u0a147}
,07-27 08:57:05.941 11501 11501 E Zygote  : v2
07-27 08:57:05.941 11501 11501 I libpersona: KNOX_SDCARD checking this for 5011
07-27 08:57:05.941 11501 11501 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:05.941 11501 11501 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:05.941 11501 11501 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:05.946  3531  5110 I ActivityManager: Start proc 11501:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
07-27 08:57:05.946 11501 11501 E Zygote  : accessInfo : 0
07-27 08:57:05.946 11501 11501 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,07-27 08:57:05.956  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:05.961 11501 11501 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:05.961 11501 11501 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:05.966  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a5bad34 5921:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-27 08:57:05.966  5921  5921 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,07-27 08:57:05.966  5921  5921 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,07-27 08:57:05.971  3531  5112 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b13e58 11501:com.samsung.android.coreapps/5011}
,07-27 08:57:05.976  3531  4546 I ActivityManager: Killing 10813:com.samsung.hs20provider/u0a211 (adj 15): DHA:empty #31
,07-27 08:57:05.981  5618 11142 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-27 08:57:05.981 11501 11501 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm
,07-27 08:57:05.986 11283 11295 I qtaguid : Untagging socket 21
,07-27 08:57:05.986  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3f3964 4626:com.sec.android.daemonapp/u0a196}
,07-27 08:57:05.991 11501 11501 D CoreApps: SEC_LOG - true
,07-27 08:57:05.996  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
07-27 08:57:05.996  3531  3557 I ActivityManager: Killing 10351:com.sec.android.provider.badge/u0a82 (adj 15): DHA:empty #31
07-27 08:57:05.996  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
07-27 08:57:05.996  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
07-27 08:57:05.996  3531  3557 I ActivityManager: Killing 10900:com.android.email/u0a178 (adj 15): DHA:empty #31
,07-27 08:57:06.001  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 08:57:06.001  5618 11142 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,07-27 08:57:06.001  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 08:57:06.006  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,07-27 08:57:06.006  4626  4626 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 08:57:06.006  4626  4626 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-27 08:57:06.006  4626  4626 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 08:57:06.006  4626  4626 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 08:57:06.011  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,07-27 08:57:06.011  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 08:57:06.011  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,07-27 08:57:06.016  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
07-27 08:57:06.016  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
07-27 08:57:06.016  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,07-27 08:57:06.016  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 08:57:06.016  4626  4626 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,07-27 08:57:06.021  3531  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3f3964 4626:com.sec.android.daemonapp/u0a196}
,07-27 08:57:06.026  4626  4626 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
07-27 08:57:06.026  4626  4626 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,07-27 08:57:06.031  3531  4546 D ActivityManager: isAutoRunBlockedApp:: com.samsung.hs20provider, Auto Run ON
,07-27 08:57:06.041  3531  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c151438 7413:com.google.android.gms/u0a14}
,07-27 08:57:06.041 11501 11501 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,07-27 08:57:06.051  3531  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:06.061  2957  2957 D gpsd    : WakeLock(Release,GPSD)
,07-27 08:57:06.061  3531  3556 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,07-27 08:57:06.066  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{4868bb1: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:06.071  3531  5115 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
,07-27 08:57:06.156  3531  5686 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b13e58 11501:com.samsung.android.coreapps/5011}
,07-27 08:57:06.166 11190 11219 I SA      : [RC New] [v2liruge] api execute + 1025
07-27 08:57:06.166 11190 11219 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,07-27 08:57:06.166  3531  5112 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b13e58 11501:com.samsung.android.coreapps/5011}
07-27 08:57:06.166 11190 11219 I System.out: AsyncTask #1 calls detatch()
,07-27 08:57:06.176 11190 11219 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,07-27 08:57:06.181 11190 11219 I SA      : [OCP] update openData : PL
,07-27 08:57:06.181 11190 11219 I SA      : [TPMU] getNetworkMcc : 
,07-27 08:57:06.181  3531  5112 I ActivityManager: Start proc 11531:com.android.email/u0a178 for broadcast-5 com.android.email/.EmailConnectivityManager
07-27 08:57:06.181 11531 11531 E Zygote  : v2
07-27 08:57:06.181 11531 11531 I libpersona: KNOX_SDCARD checking this for 10178
07-27 08:57:06.181 11531 11531 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:06.181 11531 11531 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:06.181 11531 11531 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:06.186 11531 11531 E Zygote  : accessInfo : 0
,07-27 08:57:06.186 11531 11531 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,07-27 08:57:06.186 11190 11219 I SA      : [SCU] saveMccToPreferece Start
07-27 08:57:06.186 11190 11219 I SA      : [SCU] RegionMCC : 260
07-27 08:57:06.186 11190 11219 I SA      : [SSP] query invoked
,07-27 08:57:06.191 11190 11219 I SA      : [TPMU] GetMccFromDB : null
07-27 08:57:06.191 11190 11219 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 08:57:06.191 11190 11219 I SA      : [SCU] saveMccToPreferece End
,07-27 08:57:06.191 11190 11219 I SA      : [RC New] executeRequest [v2liruge] end. 1112
07-27 08:57:06.191 11190 11219 I SA      : [RC New] Execute end
07-27 08:57:06.191 11190 11190 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,07-27 08:57:06.191 11190 11190 I SA      : [OR] GetMyCountryZoneTask Success
,07-27 08:57:06.191  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{95665ec u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c151438 7413:com.google.android.gms/u0a14}
,07-27 08:57:06.206 11531 11531 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:06.206 11531 11531 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:06.216  3531  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7bf9896 11531:com.android.email/u0a178}
,07-27 08:57:06.231 11543 11543 E Zygote  : v2
07-27 08:57:06.231 11543 11543 I libpersona: KNOX_SDCARD checking this for 10125
07-27 08:57:06.231 11543 11543 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:06.231 11543 11543 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:06.231 11543 11543 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:06.231  3531  4546 I ActivityManager: Start proc 11543:com.google.android.talk/u0a125 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,07-27 08:57:06.236 11543 11543 E Zygote  : accessInfo : 0
,07-27 08:57:06.236 11543 11543 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-27 08:57:06.246 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:57:06.246 10628 10693 I jxcore-log: 
,07-27 08:57:06.251  3531  5022 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.251 11543 11543 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:06.251 11543 11543 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:06.261  3531  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27e804 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6c731ed 11543:com.google.android.talk/u0a125}
,07-27 08:57:06.261  3531  3557 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.276 11543 11543 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-27 08:57:06.281  3531  5679 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.281  3531  5021 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.296 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:57:06.296 10628 10693 I jxcore-log: 
,07-27 08:57:06.301 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:57:06.301 10628 10693 I jxcore-log: 
,07-27 08:57:06.306 11556 11556 I dex2oat : /system/bin/dex2oat --compiler-filter=speed --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-27 08:57:06.336  3531  4898 I ActivityManager: Start proc 11567:com.sec.android.provider.badge/u0a82 for content provider com.sec.android.provider.badge/.BadgeProvider
,07-27 08:57:06.336 11567 11567 E Zygote  : v2
07-27 08:57:06.336 11567 11567 I libpersona: KNOX_SDCARD checking this for 10082
07-27 08:57:06.336 11567 11567 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:06.336  3531  5112 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.336 11567 11567 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:06.336 11567 11567 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:06.341 11567 11567 E Zygote  : accessInfo : 0
,07-27 08:57:06.341 11567 11567 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
07-27 08:57:06.341  3531  5110 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.351  3531  4439 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-27 08:57:06.351  3531  5110 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.356  3531  3556 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.356 11556 11556 I dex2oat : ----------------------------------------------------
07-27 08:57:06.356 11556 11556 I dex2oat : <SS>: S T A R T I N G . . .
07-27 08:57:06.356 11556 11556 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
07-27 08:57:06.356 11556 11556 I dex2oat : dex2oat took 48.420ms (threads: 4) arena alloc=255KB java alloc=63KB native alloc=1553KB free=1518KB
,07-27 08:57:06.356  3531  5679 I ActivityManager: Killing 10763:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): DHA:empty #31
,07-27 08:57:06.361 11283 11295 W System  : ClassLoader referenced unknown path: 
,07-27 08:57:06.361 11567 11567 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:06.361 11567 11567 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:06.361  3531  5679 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2653b57 7198:tv.peel.smartremote/u0a186}
07-27 08:57:06.361 11283 11295 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,07-27 08:57:06.371 11283 11295 D libEGL  : eglInitialize EGLDisplay = 0xb37cb264
,07-27 08:57:06.376  3531  4879 I ActivityManager: Killing 10869:com.google.android.apps.maps/u0a131 (adj 15): DHA:empty #31
,07-27 08:57:06.381  3531  5022 I ActivityManager: Killing 10950:com.android.exchange/u0a179 (adj 15): DHA:empty #31
,07-27 08:57:06.396 11567 11567 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm
,07-27 08:57:06.406 11567 11567 D BadgeProvider: onCreate
,07-27 08:57:06.406 11567 11567 D BadgeProvider: DatabaseHelper
,07-27 08:57:06.406  3531  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a5bad34 5921:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-27 08:57:06.406  5921  5921 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-27 08:57:06.411 11283 11295 D libEGL  : eglTerminate EGLDisplay = 0xb37cb2bc
,07-27 08:57:06.416  7198  7228 I System.out: Thread-464(ApacheHTTPLog):isSBSettingEnabled false
,07-27 08:57:06.416  7198  7228 I System.out: Thread-464(ApacheHTTPLog):isShipBuild true
07-27 08:57:06.416 11283 11295 D libEGL  : eglInitialize EGLDisplay = 0xb37cb264
07-27 08:57:06.416  7198  7228 I System.out: Thread-464(ApacheHTTPLog):getDebugLevel 0x4f4c
07-27 08:57:06.416  7198  7228 I System.out: Thread-464(ApacheHTTPLog):Smart Bonding Setting is false
,07-27 08:57:06.416  7198  7228 I System.out: Thread-464(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 08:57:06.416  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:06.416  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10186
,07-27 08:57:06.426  3531  5261 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.locationwidget, Auto Run ON
,07-27 08:57:06.436 11283 11295 D libEGL  : eglTerminate EGLDisplay = 0xb37cb2bc
,07-27 08:57:06.436 11567 11583 D BaseReflect: null getOwnClass TEST
,07-27 08:57:06.436 11567 11583 D MethodReflector: android.content.ContentResolver getClass TEST
07-27 08:57:06.436 11567 11583 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,07-27 08:57:06.436 11567 11583 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-27 08:57:06.436 11283 11295 D libEGL  : eglInitialize EGLDisplay = 0xb37cb264
07-27 08:57:06.441  5921  5921 D accuweather: [KK AccuPhone]>>> U:4139 [0:0] getPWC : surface = 0, remote = 1
07-27 08:57:06.441  5921  5921 D accuweather: [KK AccuPhone]>>> U:4338 [0:0] Store PWC = 1
,07-27 08:57:06.441  5101  5101 D Launcher.Model: reloadBadges entered.
07-27 08:57:06.441 11567 11583 D MethodReflector: notifyChange is called
,07-27 08:57:06.441  5101  5101 D Launcher.Model: reloadBadges entered.
07-27 08:57:06.441 11567 11583 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-27 08:57:06.441 11567 11583 D BadgeProvider: sendNotify, [notify] : null
07-27 08:57:06.441 11567 11583 D BadgeProvider: update, getCallingPackage() : com.android.email
,07-27 08:57:06.441 11567 11583 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-27 08:57:06.441 11567 11583 D BadgeProvider: update, [uri.query] : null
07-27 08:57:06.441 11567 11583 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-27 08:57:06.441 11567 11583 D BadgeProvider: update, [UpdateCount] : 1
,07-27 08:57:06.446  4626  4853 D daemonapp: [MSC_Daemon]>>> WCP:1255 [0:0] cp update : count : 1, pt : 6
,07-27 08:57:06.446  5921  5921 D accuweather: [KK AccuPhone]>>> U:4199 [0:0] addPWC = 1
,07-27 08:57:06.446  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,07-27 08:57:06.456 11567 11582 D BadgeProvider: query, [selection] : null
,07-27 08:57:06.461  3531  4439 D ActivityManager: isAutoRunBlockedApp:: com.android.exchange, Auto Run ON
,07-27 08:57:06.461 11283 11295 D libEGL  : eglTerminate EGLDisplay = 0xb37cb2bc
,07-27 08:57:06.466 11531 11558 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:06.466 11531 11558 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:06.466 11531 11558 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:06.476  3531  5115 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a5bad34 5921:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-27 08:57:06.476 11531 11558 D skia    : ---- fAsset->read(0) returned 0
,07-27 08:57:06.481  3531  5022 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.maps, Auto Run ON
,07-27 08:57:06.491 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:57:06.491 10628 10693 I jxcore-log: 
,07-27 08:57:06.501  5921  5921 D accuweather: [KK AccuPhone]>>> U:4298 [0:0] Store PWC succeed
,07-27 08:57:06.501  5921  5921 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-27 08:57:06.501  5921  5921 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,07-27 08:57:06.511 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:57:06.511 10628 10693 I jxcore-log: 
,07-27 08:57:06.511 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:57:06.511 10628 10693 I jxcore-log: 
,07-27 08:57:06.516 11607 11607 E Zygote  : v2
07-27 08:57:06.516 11607 11607 I libpersona: KNOX_SDCARD checking this for 10013
07-27 08:57:06.516 11607 11607 I libpersona: KNOX_SDCARD not a persona
07-27 08:57:06.521 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:57:06.521 10628 10693 I jxcore-log: 
,07-27 08:57:06.521 11607 11607 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:06.521 11607 11607 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-27 08:57:06.521  3531  5115 I ActivityManager: Start proc 11607:com.sec.android.app.samsungapps/u0a13 for broadcast-5 com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver
,07-27 08:57:06.521 11607 11607 E Zygote  : accessInfo : 0
,07-27 08:57:06.521 11607 11607 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,07-27 08:57:06.526 11567 11583 D BadgeProvider: query, [selection] : null
,07-27 08:57:06.531 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:57:06.531 10628 10693 I jxcore-log: 
,07-27 08:57:06.541  3531  4898 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10178
,07-27 08:57:06.546 11607 11607 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:06.546 11607 11607 D ActivityThread: Added TimaKeyStore provider
07-27 08:57:06.546 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 08:57:06.546 10628 10693 I jxcore-log: 
,07-27 08:57:06.556  3531  7135 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{409b6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{de1b1a5 11607:com.sec.android.app.samsungapps/u0a13}
,07-27 08:57:06.561  3531  5261 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10178
,07-27 08:57:06.561  3531  5021 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10178
,07-27 08:57:06.566 11543 11543 I Babel_telephony: TeleModule.onApplicationCreate
,07-27 08:57:06.566  3531  4898 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10178
,07-27 08:57:06.571  3531  3557 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-27 08:57:06.571 11607 11607 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-2/lib/arm
,07-27 08:57:06.596 11607 11607 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-27 08:57:06.596 11543 11630 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-27 08:57:06.596 11543 11630 I Babel_SMS: MmsConfig.loadMmsSettings
,07-27 08:57:06.596  5618 11274 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:06.596  5618 11274 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:06.601  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:06.601  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-27 08:57:06.601 11543 11630 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
07-27 08:57:06.601 11543 11630 I Babel_SMS: MmsConfig.loadFromDatabase
07-27 08:57:06.601  5618 11274 I qtaguid : Tagging socket 40 with tag 1000040100000000{268436481,0} uid 10014, pid: 5618, getuid(): 10014
,07-27 08:57:06.621 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:57:06.621 10628 10693 I jxcore-log: 
,07-27 08:57:06.626 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:57:06.626 10628 10693 I jxcore-log: 
,07-27 08:57:06.631 11543 11630 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-27 08:57:06.631 11543 11630 I Babel_SMS: MmsConfig.loadFromResources
,07-27 08:57:06.631 11543 11630 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-27 08:57:06.631 11543 11630 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
,07-27 08:57:06.646 11543 11543 I Babel_Crash: Startup - clean
,07-27 08:57:06.646 10628 10693 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:57:06.646 10628 10693 I jxcore-log: 
,07-27 08:57:06.651  3531  4439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10125
,07-27 08:57:06.656  3531  5110 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10125
,07-27 08:57:06.656 10628 10693 D BluetoothAdapter: STATE_ON
,07-27 08:57:06.656  3531  5022 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10125
,07-27 08:57:06.661 10628 10693 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 08:57:06.661  3531  4898 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10125
07-27 08:57:06.661 10628 10693 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-27 08:57:06.661 10628 10693 I jxcore-log: 
,07-27 08:57:06.661  3531  3557 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10125
,07-27 08:57:06.701 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 08:57:06.701 10628 10693 I jxcore-log: 
,07-27 08:57:06.701 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:57:06.701 10628 10693 I jxcore-log: 
,07-27 08:57:06.701 10628 10693 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:57:06.701 10628 10693 I jxcore-log: 
,07-27 08:57:06.731  3531  4546 I ActivityManager: Killing 8686:com.android.settings/1000 (adj 15): DHA:empty #31
,07-27 08:57:06.736 11607 11607 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-27 08:57:06.736 11607 11607 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: exit::IDLE
07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: entry::NETWORK_CHECK
07-27 08:57:06.736  3531  3556 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-27 08:57:06.736  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eb5352b u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{52ea726 11305:com.google.android.apps.photos/u0a4}
07-27 08:57:06.736  3531  5116 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-27 08:57:06.736 11607 11607 D InitializeManagerStateMachine: entry::SUCCESS
07-27 08:57:06.736 11607 11607 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-27 08:57:06.741  5618 11274 I qtaguid : Tagging socket 56 with tag 1000040100000000{268436481,0} uid 10014, pid: 5618, getuid(): 10014
,07-27 08:57:06.741 11607 11607 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,07-27 08:57:06.746 11607 11607 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-27 08:57:06.746 11607 11607 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-27 08:57:06.746  3531  5022 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-27 08:57:06.746 11607 11607 D InitializeManagerStateMachine: exit::SUCCESS
07-27 08:57:06.746 11607 11607 D InitializeManagerStateMachine: entry::IDLE
,07-27 08:57:06.751  3531  3557 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62d5346 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{52ea726 11305:com.google.android.apps.photos/u0a4}
,07-27 08:57:06.761  3531  4546 I ActivityManager: Killing 10162:com.facebook.katana/u0a114 (adj 15): DHA:empty #31
,07-27 08:57:06.771  3531  5110 D ActivityManager: isAutoRunBlockedApp:: com.android.settings, Auto Run ON
,07-27 08:57:06.776  3531  4546 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed75a34 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 08:57:06.781  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{765705d: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:06.791 11651 11651 E Zygote  : v2
07-27 08:57:06.791 11651 11651 I libpersona: KNOX_SDCARD checking this for 10179
07-27 08:57:06.791 11651 11651 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:06.791 11651 11651 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:06.791 11651 11651 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:06.791 11651 11651 E Zygote  : accessInfo : 0
,07-27 08:57:06.791 11651 11651 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
,07-27 08:57:06.796  3531  5679 I ActivityManager: Start proc 11651:com.android.exchange/u0a179 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
,07-27 08:57:06.801  3531  3556 I ActivityManager: Killing 11010:com.samsung.android.sm.policy/u0a217 (adj 15): DHA:empty #31
,07-27 08:57:06.806 11651 11651 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:06.806 11651 11651 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:06.816  3531  5261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{35b5dd2 u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6e91ea3 11651:com.android.exchange/u0a179}
,07-27 08:57:06.816  3531  5112 D ActivityManager: isAutoRunBlockedApp:: com.facebook.katana, Auto Run ON
,07-27 08:57:06.826 11651 11651 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
,07-27 08:57:06.831  3531  5116 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 08:57:06.846 11665 11665 E Zygote  : v2
07-27 08:57:06.846 11665 11665 I libpersona: KNOX_SDCARD checking this for 10022
07-27 08:57:06.846 11665 11665 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:06.846 11665 11665 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:06.846 11665 11665 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:06.846 11665 11665 E Zygote  : accessInfo : 0
,07-27 08:57:06.846 11665 11665 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.locationwidget 
,07-27 08:57:06.851  3531  5686 I ActivityManager: Start proc 11665:com.sec.android.widgetapp.locationwidget/u0a22 for broadcast-3 com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider
,07-27 08:57:06.856  3531  5686 I ActivityManager: Killing 10776:com.samsung.android.snote:sync/u0a160 (adj 15): DHA:empty #31
,07-27 08:57:06.861 11665 11665 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:06.861 11665 11665 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:06.861  3531  5110 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,07-27 08:57:06.871  3531  5116 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0db559 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ed851e 11665:com.sec.android.widgetapp.locationwidget/u0a22}
,07-27 08:57:06.881 11665 11665 W System  : ClassLoader referenced unknown path: /system/priv-app/LocationWidget_M/lib/arm
,07-27 08:57:06.886 11665 11665 I LocationWidgetApplication: onCreate() : start
,07-27 08:57:06.886 11665 11665 D LocationWidgetApplication: countryCode = POLAND
,07-27 08:57:06.886  4515  4515 D ViewRootImpl: #3 mView = null
,07-27 08:57:06.886  2906  4429 I SurfaceFlinger: id=20 Removed Uoast (8/9)
07-27 08:57:06.886  2906  3008 I SurfaceFlinger: id=20 Removed Uoast (-2/9)
,07-27 08:57:06.891  3531  5679 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3531) eventTime = 292066
07-27 08:57:06.891  3531  5679 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3531 (0x0)
,07-27 08:57:06.891  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbed03474
07-27 08:57:06.891  3531  5679 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3531, ws=WorkSource{10060}) (elapsedTime=3463)
,07-27 08:57:06.896 11665 11678 D LocationWidgetUtils: getUpcommingInstances() start: 1469602626898, end: 1470175199999
07-27 08:57:06.896 11665 11678 D LocationWidgetUtils: getUpcommingInstances() DB begin time >= start:1469602626898, DB begin time <= end:1470175199999
,07-27 08:57:06.896  3531  3556 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0db559 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6978114 11318:com.sec.android.widgetapp.SPlannerAppWidget/u0a163}
,07-27 08:57:06.906  3531  5116 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.snote, Auto Run ON
,07-27 08:57:06.916  3531  3556 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0db559 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{210e77b 11337:com.android.calendar/u0a164}
,07-27 08:57:06.926  3531  7135 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f0db559 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{210e77b 11337:com.android.calendar/u0a164}
,07-27 08:57:06.951  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2ac8b8 u0 com.android.widgetapp.locationwidget.cocktail.action.COCKTAIL_UPDATE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ed851e 11665:com.sec.android.widgetapp.locationwidget/u0a22}
,07-27 08:57:06.961 11665 11665 D LWLocationManager: mPrivacy is null
,07-27 08:57:06.971  3531  5679 I ActivityManager: Killing 10962:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #31
,07-27 08:57:06.976 11665 11665 D ContextFramework:PrivacyManager: Service for PrivacyManager is connected
,07-27 08:57:06.976 11665 11665 D LWLocationManager: Privacy service : STATUS_PLACE
07-27 08:57:06.976 11665 11665 D LWLocationManager: updateLocationStatus()
,07-27 08:57:06.981 11665 11665 I LocationWidgetFuctionData: readDB
,07-27 08:57:06.981 11665 11665 I LocationWidgetFuctionData: selectedAppSize: 3
07-27 08:57:06.981 11665 11665 I LocationWidgetFuctionData: configPlaceList aroundMeItems
,07-27 08:57:06.991 11684 11684 E Zygote  : v2
07-27 08:57:06.991 11684 11684 I libpersona: KNOX_SDCARD checking this for 5010
07-27 08:57:06.991 11684 11684 I libpersona: KNOX_SDCARD not a persona
,07-27 08:57:06.991 11684 11684 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-27 08:57:06.991 11684 11684 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 08:57:06.991 11684 11684 E Zygote  : accessInfo : 0
07-27 08:57:06.991 11684 11684 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
,07-27 08:57:06.991  3531  7135 I ActivityManager: Start proc 11684:com.samsung.android.intelligenceservice2/5010 for content provider com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.PlaceProvider
,07-27 08:57:07.006 11684 11684 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 08:57:07.006 11684 11684 D ActivityThread: Added TimaKeyStore provider
,07-27 08:57:07.006  3531  5022 I ActivityManager: Killing 9261:com.enhance.gameservice/u0a224 (adj 15): DHA:empty #31
,07-27 08:57:07.016 10976 10976 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:57:07.021 11684 11684 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm
,07-27 08:57:07.021 11684 11684 D UserAnalysis.Provider: PlaceProvider onCreate()
,07-27 08:57:07.026  3531  5112 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,07-27 08:57:07.041 11684 11684 D UserAnalysis.Secu: Key for secure DB is newly created
,07-27 08:57:07.041 11684 11684 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
07-27 08:57:07.041 11684 11684 D UserAnalysis: Create SecureDbHelper
,07-27 08:57:07.046 11684 11684 D UserAnalysis.App: onCreate()
,07-27 08:57:07.051 11684 11684 D UserAnalysis.App: no applications having user consent for prediction
,07-27 08:57:07.051 11684 11684 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
,07-27 08:57:07.056 11684 11684 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-27 08:57:07.061  3531  5021 D ActivityManager: isAutoRunBlockedApp:: com.enhance.gameservice, Auto Run ON
,07-27 08:57:07.061  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{11fb864: PendingIntentRecord{6082acd com.samsung.android.intelligenceservice2 broadcastIntent}}
,07-27 08:57:07.066 11665 11665 I LocationWidgetFuctionData: selectedAppSize: 3
,07-27 08:57:07.066 11665 11665 I LocationWidgetFuctionData: selectedAppSize: 3
,07-27 08:57:07.066 11665 11665 I LocationWidgetFuctionData: selectedAppSize: 3
,07-27 08:57:07.071 11665 11665 I LocationWidgetFuctionData: selectedAppSize: 3
,07-27 08:57:07.081  2916  4367 D Netd    : Iface wlan0 link up
07-27 08:57:07.081 10708 10708 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
,07-27 08:57:07.081  3531  3699 D Tethering: interfaceLinkStateChanged wlan0, true
07-27 08:57:07.081  3531  3699 D Tethering: interfaceStatusChanged wlan0, true
,07-27 08:57:07.086  3531  4445 D WifiP2pService: InactiveState{ what=147461 }
07-27 08:57:07.086  3531  4445 D WifiP2pService: P2pEnabledState{ what=147461 }
07-27 08:57:07.086  3531  4445 D WifiP2pService: DefaultState{ what=147461 }
,07-27 08:57:07.091  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{612df82: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:07.096 11665 11665 E LWLocationManager: findLocationType() : cursor_location.moveToFirst() return false!!
,07-27 08:57:07.101  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6aef693 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b2e5da 4515:com.android.systemui/u0a60}
,07-27 08:57:07.106 11665 11665 D LWLocationManager: Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
07-27 08:57:07.106 11665 11665 D LWLocationManager: setShouldUpdateLocationId
07-27 08:57:07.106 11665 11665 D LWLocationManager: setShouldUpdateLocationId return false
07-27 08:57:07.106 11665 11665 D LWLocationManager: setShouldUpdateLocationId
07-27 08:57:07.106 11665 11665 D LWLocationManager: setShouldUpdateLocationId return false
07-27 08:57:07.106 11665 11665 D LWLocationManager: setShouldUpdateLocationId
07-27 08:57:07.106 11665 11665 D LWLocationManager: setShouldUpdateLocationId return false
07-27 08:57:07.106 11665 11665 D LWLocationManager: updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,07-27 08:57:07.151  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{f9a6c9: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:07.216  5618 11701 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 08:57:07.216  5618 11699 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:57:07.221  5618 11701 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:57:07.221  5618 11699 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-27 08:57:07.231  5618 11701 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 08:57:07.231  5618 11699 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-27 08:57:07.231  5618 11699 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-27 08:57:07.231  5618 11699 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:07.261  5618 11699 W Uploader: UNKNOWN no longer exists, so no auth token.
,07-27 08:57:07.291  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:07.291  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:07.291  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:07.291  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-27 08:57:07.326  5618 11699 I qtaguid : Tagging socket 65 with tag fffff65b00000000{4294964827,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:07.326  7198  7228 I System.out: tr calls detatch()
,07-27 08:57:07.361  5618 11699 I qtaguid : Tagging socket 68 with tag fffff65b00000000{4294964827,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:07.376  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 08:57:07.581  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:07.581  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:07.581  5618 11699 I qtaguid : Tagging socket 65 with tag 11065c9100000000{285629585,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:07.651  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:07.651  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:07.651  5618 11699 I qtaguid : Tagging socket 65 with tag 11065c0800000000{285629448,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:07.721  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:07.721  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:07.721  5618 11699 I qtaguid : Tagging socket 65 with tag 11065b5800000000{285629272,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:07.816  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:07.821  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:07.821  5618 11699 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} uid 10014, pid: 5618, getuid(): 10014
,07-27 08:57:07.851  5618 11699 I qtaguid : Tagging socket 71 with tag 1000040100000000{268436481,0} uid 10014, pid: 5618, getuid(): 10014
,07-27 08:57:08.141  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:08.146  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:08.146  5618 11699 I qtaguid : Tagging socket 65 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:08.206  3531  6679 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 08:57:08.216  3531  6679 I System.out: Thread-177(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-27 08:57:08.216  3531  6679 I System.out: Thread-177(ApacheHTTPLog):isSBSettingEnabled false
07-27 08:57:08.216  3531  6679 I System.out: Thread-177(ApacheHTTPLog):isShipBuild true
07-27 08:57:08.216  3531  6679 I System.out: Thread-177(ApacheHTTPLog):getDebugLevel 0x4f4c
07-27 08:57:08.216  3531  6679 I System.out: Thread-177(ApacheHTTPLog):Smart Bonding Setting is false
07-27 08:57:08.216  3531  6679 I System.out: Thread-177(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 08:57:08.221  2916  4370 D EnterpriseController: netId is 0
07-27 08:57:08.221  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-27 08:57:08.256  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:08.256  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:08.256  5618 11699 I qtaguid : Tagging socket 65 with tag 11065e2100000000{285629985,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:08.351  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:08.351  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:08.351  5618 11699 I qtaguid : Tagging socket 65 with tag 11065fff00000000{285630463,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:08.436  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:08.436  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:08.436  5618 11699 I qtaguid : Tagging socket 65 with tag fffffca200000000{4294966434,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:08.571  3531  6679 I System.out: Category Thread calls detatch()
,07-27 08:57:08.596  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:08.596  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:08.596  5618 11699 I qtaguid : Tagging socket 65 with tag 1106541400000000{285627412,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:08.731  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 08:57:08.731  5618 11699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 08:57:08.731  5618 11699 I qtaguid : Tagging socket 65 with tag 11065c9100000000{285629585,0} uid -1, pid: 5618, getuid(): 10014
,07-27 08:57:08.876  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{64d0acf: PendingIntentRecord{bdb0f63 com.google.android.gms broadcastIntent}}
,07-27 08:57:11.021 10976 10976 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-27 08:57:11.326  3531  4453 D ConnectivityService: handlePromptUnvalidated 502
,07-27 08:57:11.636  3531  5116 I ActivityManager: Killing 10738:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 15): DHA:empty #31
,07-27 08:57:11.716  3531  7135 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.keyguardwallpaperupdator, Auto Run ON
,07-27 08:57:15.026 10976 10976 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 08:57:15.031 10976 10976 I dhcpcd  : wlan0: no IPv6 Routers available
,07-27 08:57:15.616  3531  6657 D SSRM:n  : SIOP:: AP = 320, PST = 281 (W:10), LCD = 0
,07-27 08:57:16.741 11607 11607 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
07-27 08:57:16.741 11607 11607 D PreloadUpdateManagerStateMachine: exit::IDLE
07-27 08:57:16.741 11607 11607 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-27 08:57:16.746 11607 11607 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,07-27 08:57:16.751 11607 11607 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-27 08:57:16.751 11607 11607 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-27 08:57:16.751 11607 11607 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
07-27 08:57:16.751 11607 11607 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-27 08:57:20.781  3531  5021 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 08:57:20.781  3531  5021 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 08:57:20.781  3531  5021 D BatteryService: online:4, current avg:-172, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 08:57:20.781  3531  5021 D BatteryService: stay LED for fully charged
,07-27 08:57:20.781  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 08:57:20.786  3531  3531 I MotionRecognitionService: Plugged
07-27 08:57:20.786  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 08:57:20.786  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:57:20.786  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:57:20.791  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:57:20.791  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:57:20.796  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:20.816 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:57:20.821 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:57:20.821  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:57:20.821  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:57:20.821  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:21.561 11543 11621 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,07-27 08:57:21.591 11543 11623 W Babel   : aye TOOK TOO LONG! (15003ms > 10000ms)
,07-27 08:57:21.621  3531  4898 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10125
,07-27 08:57:21.646  3531  5112 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:57:21.661 11543 11543 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-27 08:57:21.696 11543 11543 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:57:21.696 11543 11543 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:57:21.696 11543 11543 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-27 08:57:21.706 11543 11642 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,07-27 08:57:21.711  3531  4546 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:57:25.651  3531  6657 D SSRM:n  : SIOP:: AP = 300, PST = 284 (W:14), CUR = -172, LCD = 0
,07-27 08:57:25.961  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:27.211  3531  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 08:57:27.216  3531  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 08:57:27.221  3531  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 08:57:27.231  3531  4390 I TLC_TIMA_PKM_initialize: initializing...
,07-27 08:57:27.236  3531  4390 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-27 08:57:27.236  3531  4390 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
,07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
,07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: device_id = 0x0
,07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: tlc_open() was called
07-27 08:57:27.236  3531  4390 I TZ: mc_tlc_communication: Opening MobiCore device
,07-27 08:57:27.241  3531  4390 I TZ: mc_tlc_communication: Allocating message buffer for TCI,
,07-27 08:57:27.246  3531  4390 I TZ: mc_tlc_communication: Opening the session
,07-27 08:57:27.266  3531  4390 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-27 08:57:27.281  3531  4390 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-27 08:57:30.546  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:57:30.546  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:57:30.601  3531  4968 E Watchdog: !@Sync 10 [07-27 08:57:30.607]
,07-27 08:57:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 08:57:31.446  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 08:57:31.446  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 08:57:33.871  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 08:57:33.871  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
07-27 08:57:33.886  3531  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 08:57:33.886  3531  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 08:57:35.686  3531  6657 D SSRM:n  : SIOP:: AP = 290, PST = 290 (W:14), CUR = -172, LCD = 0
,07-27 08:57:35.996  3531  4400 V AlarmManager: Expired Alarm result :4
,07-27 08:57:36.016  3531  5040 V AlarmManager:  remove PendingIntent] PendingIntent{f755d72: PendingIntentRecord{f9db5c3 android broadcastIntent}}
,07-27 08:57:36.051  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 08:57:36.051  4515  4515 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 08:57:36.051  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:57:36.056  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:57:36.076  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:57:36.086  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:36.086  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:36.091  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:36.091  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:36.091  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:36.096  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:36.096  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:57:36.166  4515  4515 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,07-27 08:57:36.531  7413 11879 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:57:36.531  3531  3673 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 320317, reason: UserStart, SyncResult: databaseError: true stats []
07-27 08:57:36.531  3531  3673 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 384704, reason: UserStart
,07-27 08:57:36.581  3531  5021 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-27 08:57:45.716  3531  6657 D SSRM:n  : SIOP:: AP = 280, PST = 290 (W:14), CUR = -172, LCD = 0
,07-27 08:57:45.961  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:57:50.876  3531  3556 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 08:57:50.876  3531  3556 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 08:57:50.876  3531  3556 D BatteryService: online:4, current avg:-10, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 08:57:50.876  3531  3556 D BatteryService: stay LED for fully charged
,07-27 08:57:50.876  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 08:57:50.881  3531  3531 I MotionRecognitionService: Plugged
07-27 08:57:50.881  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 08:57:50.881  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:57:50.881  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:57:50.891  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:57:50.891  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 08:57:50.891  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:57:50.916 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:57:50.916 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:57:50.921  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:57:50.921  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:57:50.921  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:57:55.751  3531  6657 D SSRM:n  : SIOP:: AP = 280, PST = 291 (W:14), CUR = -10, LCD = 0
,07-27 08:57:59.996  3531  4400 V AlarmManager: Expired Alarm result :8
,07-27 08:58:00.606  3531  4968 E Watchdog: !@Sync 11 [07-27 08:58:00.608]
,07-27 08:58:03.431  3531  4400 V AlarmManager: Expired Alarm result :4
,07-27 08:58:03.461  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 08:58:03.461  4515  4515 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 08:58:03.461  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 08:58:03.476  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 08:58:03.481  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 08:58:03.491  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:03.491  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:03.496  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:03.496  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:03.496  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:03.496  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:03.501  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:03.591  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 08:58:05.781  3531  6657 D SSRM:n  : SIOP:: AP = 280, PST = 292 (W:16), CUR = -10, LCD = 0
,07-27 08:58:05.966  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:15.806  3531  6657 D SSRM:n  : SIOP:: AP = 280, PST = 291 (W:16), CUR = -10, LCD = 0
,07-27 08:58:20.971  3531  5110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 08:58:20.971  3531  5110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 08:58:20.976  3531  5110 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 08:58:20.976  3531  5110 D BatteryService: stay LED for fully charged
,07-27 08:58:20.976  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 08:58:20.981  3531  3531 I MotionRecognitionService: Plugged
07-27 08:58:20.981  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 08:58:20.981  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:58:20.981  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:20.986  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:58:20.986  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:58:20.986  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:21.001 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 08:58:21.001 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:21.011  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:21.016  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:21.016  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:23.891  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:23.891  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:25.831  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 291 (W:16), LCD = 0
,07-27 08:58:25.971  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:30.611  3531  4968 E Watchdog: !@Sync 12 [07-27 08:58:30.614]
,07-27 08:58:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 08:58:31.566  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 08:58:31.566  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 08:58:35.856  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 291 (W:16), LCD = 0
,07-27 08:58:38.906  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 08:58:38.906  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 08:58:45.886  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 287 (W:18), LCD = 0
,07-27 08:58:45.971  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:58:51.071  3531  4879 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 08:58:51.071  3531  4879 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 08:58:51.071  3531  4879 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 08:58:51.071  3531  4879 D BatteryService: stay LED for fully charged
,07-27 08:58:51.076  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 08:58:51.081  3531  3531 I MotionRecognitionService: Plugged
07-27 08:58:51.081  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 08:58:51.081  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 08:58:51.081  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 08:58:51.086  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 08:58:51.086  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 08:58:51.086  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 08:58:51.116  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:51.116  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 08:58:51.116  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 08:58:51.121 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 08:58:51.121 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:58:55.921  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:18), LCD = 0
,07-27 08:58:59.996  3531  4400 V AlarmManager: Expired Alarm result :8
,07-27 08:59:00.616  3531  4968 E Watchdog: !@Sync 13 [07-27 08:59:00.618]
,07-27 08:59:05.956  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 281 (W:18), LCD = 0
,07-27 08:59:05.971  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:15.991  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:18), LCD = 0
,07-27 08:59:21.166  3531  5686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:25.976  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:26.016  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:20), LCD = 0
,07-27 08:59:30.621  3531  4968 E Watchdog: !@Sync 14 [07-27 08:59:30.622]
,07-27 08:59:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 08:59:31.671  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 08:59:31.671  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 08:59:36.046  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:20), LCD = 0
,07-27 08:59:45.976  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 08:59:46.081  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:20), LCD = 0
,07-27 08:59:51.261  3531  5679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 08:59:56.106  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:20), LCD = 0
,07-27 09:00:00.626  3531  4968 E Watchdog: !@Sync 15 [07-27 09:00:00.629]
,07-27 09:00:05.981  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:06.141  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:22), LCD = 0
,07-27 09:00:16.171  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:22), LCD = 0
,07-27 09:00:19.496  2975  2975 I bootchecker: bootchecker wake up!!
,07-27 09:00:21.361  3531  5261 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:00:21.361  3531  5261 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:00:21.361  3531  5261 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:00:21.361  3531  5261 D BatteryService: stay LED for fully charged
,07-27 09:00:21.366  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:00:21.371  3531  3531 I MotionRecognitionService: Plugged
07-27 09:00:21.371  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:00:21.371  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:00:21.371  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:00:21.376  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:00:21.376  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:00:21.376  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:00:21.401 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:00:21.401 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:00:21.406  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:00:21.406  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:00:21.411  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:25.981  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:26.211  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:22), LCD = 0
,07-27 09:00:30.631  3531  4968 E Watchdog: !@Sync 16 [07-27 09:00:30.633]
,07-27 09:00:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:00:31.796  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:00:31.796  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:00:31.856  5003  5057 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 56ms lastUpdatedAfter : 175236ms
,07-27 09:00:36.246  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), LCD = 0
,07-27 09:00:45.986  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:00:46.281  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,07-27 09:00:51.456  3531  5679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:00:51.461  3531  5679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:00:51.461  3531  5679 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:00:51.461  3531  5679 D BatteryService: stay LED for fully charged
07-27 09:00:51.461  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:00:51.466  3531  3531 I MotionRecognitionService: Plugged
07-27 09:00:51.466  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:00:51.466  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:00:51.466  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:00:51.476  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:00:51.476  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:00:51.476  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-27 09:00:51.496 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,07-27 09:00:51.501 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:00:51.501  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:00:51.501  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:00:51.506  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:00:56.306  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,07-27 09:01:00.636  3531  4968 E Watchdog: !@Sync 17 [07-27 09:01:00.640]
,07-27 09:01:05.486  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:01:05.486  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:01:05.986  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:06.336  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,07-27 09:01:16.366  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,07-27 09:01:21.556  3531  5115 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:01:21.556  3531  5115 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:01:21.556  3531  5115 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:01:21.556  3531  5115 D BatteryService: stay LED for fully charged
,07-27 09:01:21.556  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:01:21.566  3531  3531 I MotionRecognitionService: Plugged
07-27 09:01:21.566  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:01:21.566  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:01:21.566  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:01:21.571  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:01:21.571  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:01:21.571  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:01:21.596  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:01:21.596  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:01:21.596  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:01:21.601 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:01:21.601 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:01:24.506  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:01:24.506  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:01:25.991  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:26.396  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,07-27 09:01:30.646  3531  4968 E Watchdog: !@Sync 18 [07-27 09:01:30.647]
,07-27 09:01:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:01:31.966  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:01:31.966  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:01:36.426  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,07-27 09:01:45.991  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:01:46.451  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,07-27 09:01:51.651  3531  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:01:56.481  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,07-27 09:02:00.651  3531  4968 E Watchdog: !@Sync 19 [07-27 09:02:00.653]
,07-27 09:02:04.956  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:04.956  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:05.996  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:06.511  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), LCD = 0
,07-27 09:02:16.546  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), LCD = 0
,07-27 09:02:21.746  3531  7135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:02:21.746  3531  7135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:02:21.746  3531  7135 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:02:21.746  3531  7135 D BatteryService: stay LED for fully charged
,07-27 09:02:21.751  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:02:21.756  3531  3531 I MotionRecognitionService: Plugged
07-27 09:02:21.756  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:02:21.756  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:02:21.756  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:02:21.761  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:02:21.761  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:02:21.761  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:02:21.791  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:02:21.791  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:02:21.791  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:21.801 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:02:21.801 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:02:23.866  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:02:23.866  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:02:26.001  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:26.576  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), LCD = 0
,07-27 09:02:27.211  3531  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 09:02:27.211  3531  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:02:27.216  3531  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:02:30.656  3531  4968 E Watchdog: !@Sync 20 [07-27 09:02:30.658]
,07-27 09:02:30.736  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 09:02:30.736  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:02:30.751  3531  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:30.751  3531  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:02:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:02:32.116  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:02:32.116  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLock,ed: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-27 09:02:33.401  3531  3673 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-27 09:02:33.576  3531  3802 I ActivityManager: setMaxStartingBackgroundTimer onfinish
07-27 09:02:33.576  3531  3802 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-27 09:02:36.611  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:28), LCD = 0
,07-27 09:02:46.001  3531  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 09:02:46.641  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:02:51.841  3531  3556 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:02:51.846  3531  3556 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:02:51.846  3531  3556 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:02:51.846  3531  3556 D BatteryService: stay LED for fully charged
,07-27 09:02:51.846  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:02:51.851  3531  3531 I MotionRecognitionService: Plugged
07-27 09:02:51.851  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:02:51.851  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:02:51.851  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:02:51.861  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:02:51.861  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:02:51.861  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:02:51.886 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:02:51.886 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:02:51.886  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:02:51.886  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:02:51.886  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:02:56.666  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:03:00.661  3531  4968 E Watchdog: !@Sync 21 [07-27 09:03:00.666]
,07-27 09:03:04.121  3531  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:03:06.696  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:03:16.721  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:03:21.936  3531  5679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:03:21.936  3531  5679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:03:21.936  3531  5679 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:03:21.941  3531  5679 D BatteryService: stay LED for fully charged
,07-27 09:03:21.941  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:03:21.946  3531  3531 I MotionRecognitionService: Plugged
07-27 09:03:21.946  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:03:21.946  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:03:21.946  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:03:21.951  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:03:21.951  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:03:21.951  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:03:21.981 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:03:21.981  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:03:21.981 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:03:21.981  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:03:21.981  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:26.746  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:03:30.671  3531  4968 E Watchdog: !@Sync 22 [07-27 09:03:30.673]
,07-27 09:03:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:03:32.226  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:03:32.226  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:03:32.291  5003  5057 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 57ms lastUpdatedAfter : 180434ms
,07-27 09:03:36.771  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:03:46.801  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:03:52.031  3531  5115 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:03:52.031  3531  5115 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:03:52.031  3531  5115 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:03:52.031  3531  5115 D BatteryService: stay LED for fully charged
07-27 09:03:52.036  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:03:52.041  3531  3531 I MotionRecognitionService: Plugged
07-27 09:03:52.041  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:03:52.041  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:03:52.041  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
07-27 09:03:52.051  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:03:52.051  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:03:52.051  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 09:03:52.071 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:03:52.071 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:03:52.081  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:03:52.081  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:03:52.081  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:03:56.826  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), LCD = 0
,07-27 09:04:00.676  3531  4968 E Watchdog: !@Sync 23 [07-27 09:04:00.681]
,07-27 09:04:06.861  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), LCD = 0
,07-27 09:04:16.891  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), LCD = 0
,07-27 09:04:22.131  3531  7135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:04:22.131  3531  7135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:04:22.131  3531  7135 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:04:22.131  3531  7135 D BatteryService: stay LED for fully charged
,07-27 09:04:22.131  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:04:22.141  3531  3531 I MotionRecognitionService: Plugged
07-27 09:04:22.141  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:04:22.141  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:04:22.141  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:04:22.146  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:04:22.146  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:04:22.146  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:04:22.166 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:04:22.171 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:04:22.171  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:04:22.171  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:04:22.171  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:04:26.931  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), LCD = 0
,07-27 09:04:30.686  3531  4968 E Watchdog: !@Sync 24 [07-27 09:04:30.688]
,07-27 09:04:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:04:32.411  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:04:32.411  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:04:36.961  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), LCD = 0
,07-27 09:04:46.996  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), LCD = 0
,07-27 09:04:52.226  3531  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:04:57.021  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), LCD = 0
,07-27 09:05:00.691  3531  4968 E Watchdog: !@Sync 25 [07-27 09:05:00.694]
,07-27 09:05:07.056  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), LCD = 0
,07-27 09:05:17.081  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), LCD = 0
,07-27 09:05:22.321  3531  7135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:05:22.321  3531  7135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:05:22.321  3531  7135 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:05:22.321  3531  7135 D BatteryService: stay LED for fully charged
,07-27 09:05:22.326  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:05:22.331  3531  3531 I MotionRecognitionService: Plugged
07-27 09:05:22.331  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:05:22.331  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:05:22.331  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:05:22.336  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:05:22.336  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:05:22.341  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:22.361 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:05:22.366 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:05:22.366  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:05:22.366  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:05:22.366  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:27.106  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,07-27 09:05:30.696  3531  4968 E Watchdog: !@Sync 26 [07-27 09:05:30.698]
,07-27 09:05:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:05:32.556  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:05:32.556  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:05:33.621  3531  5698 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
07-27 09:05:33.621  3531  5698 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-27 09:05:33.621  3531  5698 V MARsPolicyManager: updateSMDBValues
,07-27 09:05:33.626  3531  3800 E MARsDBManager: updateDBAll : begin --size 1
,07-27 09:05:33.666  3531  3800 I ActivityManager: Start proc 12123:com.samsung.android.sm.provider/1000 for content provider com.samsung.android.sm.provider/com.samsung.android.sm.database.SmProvider
,07-27 09:05:33.671 12123 12123 E Zygote  : v2
,07-27 09:05:33.671 12123 12123 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:05:33.671 12123 12123 I libpersona: KNOX_SDCARD not a persona
,07-27 09:05:33.676 12123 12123 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-27 09:05:33.681 12123 12123 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:05:33.681 12123 12123 E Zygote  : accessInfo : 0
,07-27 09:05:33.721 12123 12123 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:05:33.726 12123 12123 D ActivityThread: Added TimaKeyStore provider
,07-27 09:05:33.761 12123 12123 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManagerProvider/lib/arm
,07-27 09:05:33.796  3531  3800 E MARsDBManager: updateDBAll : end
07-27 09:05:33.796  3531  3800 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-27 09:05:33.801  3531  3531 I ActivityManager: Killing 11169:com.samsung.aasaservice/u0a215 (adj 15): DHA:empty #31
,07-27 09:05:33.836 11154 11154 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
,07-27 09:05:33.851  3531  5115 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,07-27 09:05:33.851  3531  5115 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,07-27 09:05:34.891  3531  3685 I ActivityManager: Start proc 12145:com.samsung.aasaservice/u0a215 for service com.samsung.aasaservice/.AASAService
,07-27 09:05:34.901 12145 12145 E Zygote  : v2
,07-27 09:05:34.901 12145 12145 I libpersona: KNOX_SDCARD checking this for 10215
,07-27 09:05:34.906 12145 12145 I libpersona: KNOX_SDCARD not a persona
,07-27 09:05:34.906 12145 12145 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-27 09:05:34.906 12145 12145 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:05:34.911 12145 12145 E Zygote  : accessInfo : 0
,07-27 09:05:34.911 12145 12145 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,07-27 09:05:34.951 12145 12145 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 09:05:34.951 12145 12145 D ActivityThread: Added TimaKeyStore provider
,07-27 09:05:34.996 12145 12145 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-27 09:05:35.001 12145 12145 D AASAservice: onCreate()
,07-27 09:05:35.001 11154 11154 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,07-27 09:05:35.001  3531  5021 I ActivityManager: Killing 11154:com.policydm/1000 (adj 15): DHA:empty #31
,07-27 09:05:35.051  3531  5112 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,07-27 09:05:35.051 12145 12145 D AASAservice: onDestroy()
,07-27 09:05:35.056 12145 12145 I art     : System.exit called, status: 80
,07-27 09:05:35.056 12145 12145 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,07-27 09:05:35.111  2960  2960 I Zygote  : Process 12145 exited cleanly (80)
,07-27 09:05:35.116  3531  5261 I ActivityManager: Process com.samsung.aasaservice (pid 12145)(adj 0) has died(122,1409)
,07-27 09:05:35.116  3531  5261 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,07-27 09:05:37.136  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,07-27 09:05:47.166  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,07-27 09:05:52.421  3531  5110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:05:52.421  3531  5110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:05:52.421  3531  5110 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:05:52.421  3531  5110 D BatteryService: stay LED for fully charged
,07-27 09:05:52.421  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:05:52.426  3531  3531 I MotionRecognitionService: Plugged
07-27 09:05:52.426  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:05:52.426  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:05:52.426  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:05:52.436  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:05:52.436  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:05:52.436  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:05:52.466 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:05:52.466 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:05:52.466  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:05:52.466  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:05:52.466  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:05:57.191  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,07-27 09:06:00.706  3531  4968 E Watchdog: !@Sync 27 [07-27 09:06:00.706]
,07-27 09:06:07.226  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,07-27 09:06:17.261  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,07-27 09:06:22.516  3531  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:06:22.516  3531  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:06:22.516  3531  5116 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:06:22.516  3531  5116 D BatteryService: stay LED for fully charged
,07-27 09:06:22.516  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:06:22.526  3531  3531 I MotionRecognitionService: Plugged
07-27 09:06:22.526  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:06:22.526  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:06:22.526  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:06:22.531  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:06:22.531  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:06:22.531  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:22.556 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:06:22.556 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:06:22.556  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:06:22.556  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:06:22.561  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:27.296  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,07-27 09:06:30.711  3531  4968 E Watchdog: !@Sync 28 [07-27 09:06:30.713]
,07-27 09:06:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:06:32.681  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:06:32.681  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:06:32.761  5003  5057 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 68ms lastUpdatedAfter : 180469ms
,07-27 09:06:37.321  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,07-27 09:06:47.356  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,07-27 09:06:52.611  3531  4898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:06:52.611  3531  4898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:06:52.611  3531  4898 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:06:52.611  3531  4898 D BatteryService: stay LED for fully charged
,07-27 09:06:52.611  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:06:52.621  3531  3531 I MotionRecognitionService: Plugged
07-27 09:06:52.621  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:06:52.621  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:06:52.621  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:06:52.631  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:06:52.631  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:06:52.631  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:06:52.641 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:06:52.641 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:06:52.651  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:06:52.651  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:06:52.651  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:06:57.386  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), LCD = 0
,07-27 09:07:00.716  3531  4968 E Watchdog: !@Sync 29 [07-27 09:07:00.718]
,07-27 09:07:07.416  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), LCD = 0
,07-27 09:07:17.461  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), LCD = 0
,07-27 09:07:17.561  3531  3546 I art     : Background sticky concurrent mark sweep GC freed 80085(8MB) AllocSpace objects, 315(6MB) LOS objects, 32% free, 31MB/46MB, paused 4.738ms total 116.337ms
,07-27 09:07:22.706  3531  5261 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:07:22.706  3531  5261 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:07:22.706  3531  5261 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:07:22.706  3531  5261 D BatteryService: stay LED for fully charged
,07-27 09:07:22.706  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:07:22.716  3531  3531 I MotionRecognitionService: Plugged
07-27 09:07:22.716  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:07:22.716  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:07:22.716  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:07:22.721  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:07:22.721  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:07:22.721  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:07:22.751  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:07:22.751  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:07:22.751  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:07:22.751 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:07:22.751 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:07:27.211  3531  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 09:07:27.211  3531  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:07:27.216  3531  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:07:27.506  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,07-27 09:07:30.721  3531  4968 E Watchdog: !@Sync 30 [07-27 09:07:30.722]
,07-27 09:07:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:07:32.866  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:07:32.866  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:07:34.066  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 09:07:34.066  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:07:34.081  3531  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 09:07:34.081  3531  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:07:37.546  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 262 (W:28), LCD = 0
,07-27 09:07:47.571  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:28), LCD = 0
,07-27 09:07:52.801  3531  7135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:07:57.606  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:28), LCD = 0
,07-27 09:08:00.726  3531  4968 E Watchdog: !@Sync 31 [07-27 09:08:00.731]
,07-27 09:08:03.091  3531  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:08:03.906  3531  3685 W ProcessCpuTracker: Skipping unknown process pid 12230
,07-27 09:08:07.631  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:28), LCD = 0
,07-27 09:08:17.656  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:08:22.901  3531  5261 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:27.666  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:08:30.731  3531  4968 E Watchdog: !@Sync 32 [07-27 09:08:30.735]
,07-27 09:08:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:08:32.996  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:08:32.996  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:08:37.696  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:08:47.736  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:08:52.986  3531  5686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:08:57.761  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:09:00.736  3531  4968 E Watchdog: !@Sync 33 [07-27 09:09:00.740]
,07-27 09:09:07.826  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:09:17.856  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:09:23.081  3531  3556 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:09:23.081  3531  3556 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:09:23.081  3531  3556 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:09:23.081  3531  3556 D BatteryService: stay LED for fully charged
,07-27 09:09:23.081  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:09:23.086  3531  3531 I MotionRecognitionService: Plugged
07-27 09:09:23.086  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:09:23.086  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:09:23.086  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:09:23.096  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:09:23.096  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:09:23.096  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:09:23.126 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:09:23.126  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:09:23.126  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:09:23.126  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:09:23.126 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:09:27.891  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:09:30.746  3531  4968 E Watchdog: !@Sync 34 [07-27 09:09:30.747]
,07-27 09:09:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:09:33.121  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:09:33.121  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:09:33.191  5003  5057 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 61ms lastUpdatedAfter : 180429ms
,07-27 09:09:37.921  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:09:47.951  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:09:53.171  3531  5686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:09:57.981  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:10:00.751  3531  4968 E Watchdog: !@Sync 35 [07-27 09:10:00.755]
,07-27 09:10:08.016  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:10:18.046  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:10:23.276  3531  3556 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:10:28.071  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:10:30.761  3531  4968 E Watchdog: !@Sync 36 [07-27 09:10:30.763]
,07-27 09:10:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:10:33.291  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:10:33.291  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:10:38.106  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:10:48.131  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:10:53.406  3531  5116 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:10:53.406  3531  5116 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:10:53.406  3531  5116 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:10:53.406  3531  5116 D BatteryService: stay LED for fully charged
,07-27 09:10:53.406  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:10:53.411  3531  3531 I MotionRecognitionService: Plugged
07-27 09:10:53.411  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:10:53.411  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:10:53.411  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:10:53.411  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:10:53.411  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:10:53.411  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:10:53.421  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:10:53.421  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:53.431 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:10:53.431 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:10:53.441  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:10:58.166  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:11:00.766  3531  4968 E Watchdog: !@Sync 37 [07-27 09:11:00.770]
,07-27 09:11:08.196  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:11:18.226  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:11:23.506  3531  4898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:11:23.506  3531  4898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:11:23.506  3531  4898 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:11:23.506  3531  4898 D BatteryService: stay LED for fully charged
,07-27 09:11:23.506  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:11:23.511  3531  3531 I MotionRecognitionService: Plugged
07-27 09:11:23.511  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:11:23.516  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:11:23.516  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:11:23.526  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,07-27 09:11:23.526  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:11:23.526  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
07-27 09:11:23.536  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-27 09:11:23.536 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:11:23.536  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:11:23.536 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:11:23.536  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:28.256  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:11:30.771  3531  4968 E Watchdog: !@Sync 38 [07-27 09:11:30.774]
,07-27 09:11:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:11:33.426  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:11:33.426  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:11:38.286  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:11:48.311  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-27 09:11:53.606  3531  5022 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:11:53.606  3531  5022 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:11:53.606  3531  5022 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:11:53.606  3531  5022 D BatteryService: stay LED for fully charged
,07-27 09:11:53.606  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:11:53.616  3531  3531 I MotionRecognitionService: Plugged
07-27 09:11:53.616  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:11:53.616  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:11:53.616  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:11:53.621  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:11:53.621  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:11:53.621  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:11:53.626  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:53.631 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:11:53.631 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:11:53.646  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:53.646  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:11:58.336  3531  6657 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0,
,07-27 09:12:00.776  3531  4968 E Watchdog: !@Sync 39 [07-27 09:12:00.777]
,07-27 09:12:01.656  3531  4400 V AlarmManager: Expired Alarm result :4
,07-27 09:12:01.726  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-27 09:12:01.726  4515  4515 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-27 09:12:01.736  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:12:01.751  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:12:01.756  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:12:01.756  3531  3685 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-27 09:12:01.761  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:01.761  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:01.766  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:01.766  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:12:01.766  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:12:01.766  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-27 09:12:01.766  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:01.776  3531  3531 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-27 09:12:01.776  3531  3531 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:12:01.776  3531  3531 I Sensors : Light old sensor_state 1, new sensor_state : 513 en : 1
,07-27 09:12:01.781  5276 12350 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-27 09:12:01.791  3531  3531 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-27 09:12:01.821  3531  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6cbec8d u0 bg_app_info qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2653b57 7198:tv.peel.smartremote/u0a186}
,07-27 09:12:01.831  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{506ee53: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.871  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{7c2f390: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.886  5276 12345 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-27 09:12:01.901  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:12:01.916  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{597c489: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.926  3531  4378 I Sensors : #>LightSensor r=98 g=91 b=73 c=253 atime=238 again=64 lux=47.000000
,07-27 09:12:01.926  3531  3839 D LightsService: [SvcLED]  onSensorChanged::light value = 47
,07-27 09:12:01.926  3531  3839 I Sensors : Light old sensor_state 513, new sensor_state : 1 en : 0
,07-27 09:12:01.926  3531  3839 D SensorManager: unregisterListener ::   
07-27 09:12:01.926  3531  3839 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
,07-27 09:12:01.926  3531  3839 D lights  : led_pattern : 5 +
,07-27 09:12:01.931  3531  3839 D lights  : led_pattern : 5 -
,07-27 09:12:01.931  3531  3839 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-27 09:12:01.931  3531  3839 V AlarmManager:  remove PendingIntent] PendingIntent{cd422e: PendingIntentRecord{f2361cf android broadcastIntent}}
,07-27 09:12:01.936  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{a769c8e: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.946  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:12:01.946  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:12:01.956  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{c081caf: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.971  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{68bb8bc: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.971  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{92f2045: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.976  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{f43f39a: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.981  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{743d4cb: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:01.996  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{2b9a4a8: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
07-27 09:12:01.996  5276 12345 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-27 09:12:01.996  5276 12345 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-27 09:12:02.001  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{b267bc1: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.001  5276 12345 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-27 09:12:02.001  5276 12345 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-27 09:12:02.006  3531  5112 V AlarmManager:  remove PendingIntent] PendingIntent{15daf66: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.011  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{f38f2a7: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.011  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{9586354: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.026  3531  5021 V AlarmManager:  remove PendingIntent] PendingIntent{fde12fd: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.031  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{8055bf2: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.036  3531  5110 V AlarmManager:  remove PendingIntent] PendingIntent{b781243: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.036  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{a8260c0: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.041  5276 12345 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-27 09:12:02.041  5276 12345 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-27 09:12:02.041  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{77de1f9: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.051  3531  4898 V AlarmManager:  remove PendingIntent] PendingIntent{b09453e: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.056  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{1ff8f9f: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.061  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{5786bb: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.076  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{a6dd397: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.081  5276 12345 W ThreadPoolDumper: Queue length for executor IcingConnectionExecutor with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,07-27 09:12:02.086  3531  4879 V AlarmManager:  remove PendingIntent] PendingIntent{fbeb56d: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.086  3531  5110 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10014
,07-27 09:12:02.091  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{ec8a5a2: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.101  3531  5116 V AlarmManager:  remove PendingIntent] PendingIntent{c4f79f0: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.106  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{49e3b69: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.121  3531  5022 V AlarmManager:  remove PendingIntent] PendingIntent{2f19e8f: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.171  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{f7394ab: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.186  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{2c49708: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.201  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{be8eea1: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.211  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{9d4d087: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.216  7413 12362 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-27 09:12:02.221  3531  5679 V AlarmManager:  remove PendingIntent] PendingIntent{6901bb4: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.226  7413  8546 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
07-27 09:12:02.226  3531  4439 V AlarmManager:  remove PendingIntent] PendingIntent{504d3dd: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.231  3531  3556 V AlarmManager:  remove PendingIntent] PendingIntent{589bb52: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.231  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{623ee23: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.236  3531  5261 V AlarmManager:  remove PendingIntent] PendingIntent{1ed3f20: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:02.381  7198  7226 I System.out: Thread-462(ApacheHTTPLog):isSBSettingEnabled false
07-27 09:12:02.381  7198  7226 I System.out: Thread-462(ApacheHTTPLog):isShipBuild true
07-27 09:12:02.381  7198  7226 I System.out: Thread-462(ApacheHTTPLog):getDebugLevel 0x4f4c
07-27 09:12:02.381  7198  7226 I System.out: Thread-462(ApacheHTTPLog):Smart Bonding Setting is false
07-27 09:12:02.381  7198  7226 I System.out: Thread-462(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-27 09:12:02.386  2916  4370 D EnterpriseController: netId is 0
07-27 09:12:02.386  2916  4370 D Netd    : getNetworkForDns: using netid 502 for uid 10186
,07-27 09:12:02.951  5276 12345 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-27 09:12:03.001  7413  8546 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-27 09:12:03.036  7413  8546 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:12:03.086  7413  8546 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:12:03.106  7413  8546 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-27 09:12:03.121  5276 12345 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,07-27 09:12:04.796  7198  7226 I System.out: non-ui calls detatch()
,07-27 09:12:08.366  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 260 (W:28), LCD = 0
,07-27 09:12:18.396  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 260 (W:28), LCD = 0
,07-27 09:12:23.706  3531  5679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:12:23.706  3531  5679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:12:23.706  3531  5679 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:12:23.706  3531  5679 D BatteryService: stay LED for fully charged
,07-27 09:12:23.706  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:12:23.711  3531  3531 I MotionRecognitionService: Plugged
07-27 09:12:23.711  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:12:23.711  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:12:23.711  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:12:23.721  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:12:23.721  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:12:23.721  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:12:23.751 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:12:23.751 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:12:23.756  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:12:23.756  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:12:23.756  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:12:25.871  3531  4414 D InputReader: Input event(10): value=1 when=1211045284000
07-27 09:12:25.871  3531  4414 D InputReader: !@notifyKey(172), action=0
,07-27 09:12:25.881  3531  4414 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
07-27 09:12:25.891  3531  4414 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1200000  uid : 1000  pid : 3531  pkgName : WAKEUP_BOOSTER@31
,07-27 09:12:25.901  3531  4414 E SamsungWindowManager: mCoreNumLockHelper.acquire
07-27 09:12:25.901  3531  4414 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 3531) eventTime = 1211045 event = 1
07-27 09:12:25.901  3531  4414 D InputManager-JNI: setInteractive(true)
07-27 09:12:25.901  3531  4414 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 3531) (1)
07-27 09:12:25.901  3531  4414 I PowerManagerService: Waking up from sleep (uid 1000)...
07-27 09:12:25.906  3531  4492 I WindowManager: Started waking up...
07-27 09:12:25.901  3531  4492 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
07-27 09:12:25.906  3531  4492 V KeyguardServiceDelegate: onStartedWakingUp()
07-27 09:12:25.906  4515  5849 I PERF    : KeyguardViewMediator - onStartedWakingUp() start
07-27 09:12:25.906  3531  4414 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-27 09:12:25.906  4515  5849 D KeyguardViewMediator: onStartedWakingUp, seq = 2
07-27 09:12:25.906  3531  4414 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-27 09:12:25.906  4515  5849 D KeyguardViewMediator: notifyStartedWakingUp
07-27 09:12:25.906  3531  4414 D PowerManagerService: mDisplayReady: false
07-27 09:12:25.906  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:25.911  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() start
07-27 09:12:25.911  4515  4515 D KeyguardViewMediator: handleNotifyWakingUp
07-27 09:12:25.911  3531  3826 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
,07-27 09:12:25.911  4515  4515 D PanelView: onScreenTurnedOn 0,1,
07-27 09:12:25.911  3531  3826 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-27 09:12:25.911  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() end
,07-27 09:12:25.911  3531  4414 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-27 09:12:25.911  4515  4515 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() start
07-27 09:12:25.926  3531  3531 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
,07-27 09:12:25.911  3531  3826 I WindowManager: Screen turning on...
07-27 09:12:25.926  3531  3685 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-27 09:12:25.911  3531  4414 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-27 09:12:25.911  3531  4414 D InputManager-JNI: Disable repeat for home key when device wake up
07-27 09:12:25.941  4515  4515 D SecKeyguardClockSingleView: onScreenTurnedOn
07-27 09:12:25.941  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM,
07-27 09:12:25.941  4515  4515 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() end
,07-27 09:12:25.956  3531  3826 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@4372d4c)
07-27 09:12:25.956  3531  3826 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
07-27 09:12:25.956  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: return as screen on blocked
07-27 09:12:25.956  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:25.956  3531  3826 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-27 09:12:25.956  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-27 09:12:25.956  3531  4494 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
07-27 09:12:25.956  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-27 09:12:25.956  3531  3847 I libsuspend: !@autosuspend_wakeup_count_disable
07-27 09:12:25.956  3531  3685 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-27 09:12:25.956  3531  3847 I libsuspend: !@autosuspend_wakeup_count_disable done
07-27 09:12:25.956  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 2, mProxSensorScreenOff: false
07-27 09:12:25.956  3531  3847 D DisplayManagerService: !@display_state: OFF -> ON brightness: 0 -> 0
07-27 09:12:25.956  2906  2906 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
07-27 09:12:25.956  2906  2906 I hwcomposer: int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(0)
07-27 09:12:25.956  3531  3802 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-27 09:12:25.961  3531  4494 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:12:25.966  3531  4494 I Sensors : Light old sensor_state 1, new sensor_state : 513 en : 1
,07-27 09:12:25.981  3531  4494 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 250000, 0,  
,07-27 09:12:25.981  3531  4494 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:12:25.986  4515  4515 D BatteryMeterView: onDraw batteryColor : -1107296257
07-27 09:12:25.986  3531  3531 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 3531) 
07-27 09:12:25.986  3531  4494 D SensorManager: registerListener :: 0, ICM20610 Acceleration Sensor, 250000, 0,  
07-27 09:12:25.986  4515  5849 I PERF    : KeyguardViewMediator - onStartedWakingUp() end
07-27 09:12:25.986  4515  5849 D KeyguardViewMediator: notifyScreenOn
07-27 09:12:25.986  3531  4494 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::registerListener done: 29ms
07-27 09:12:25.986  3531  3531 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
07-27 09:12:25.986  3531  3531 D BatteryService: turn off LED
,07-27 09:12:25.986 10628 10628 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-27 09:12:25.986 10628 10628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-27 09:12:25.986 10628 10628 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-27 09:12:25.986 10628 10628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-27 09:12:25.986  3531  3839 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-27 09:12:25.991  3531  3839 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 1
07-27 09:12:25.991  3531  3839 D lights  : led_pattern : 0 +
,07-27 09:12:25.991  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() start
07-27 09:12:25.991  4515  4515 D KeyguardViewMediator: handleNotifyScreenTurningOn
07-27 09:12:25.991  4515  4515 D KeyguardViewMediator: onScreenTurnedOn()
07-27 09:12:25.991  4515  4515 D KeyguardViewMediator: callback.onShown()
07-27 09:12:25.991  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() end
07-27 09:12:25.991  3531  5022 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-27 09:12:25.991  3531  5022 D WindowManager: mKeyguardDelegate.ShowListener.onDrawn.
07-27 09:12:25.991  3531  3692 W WindowManager: Setting mKeyguardDrawComplete
,07-27 09:12:25.996  3531  4414 D InputReader: Input event(10): value=0 when=1211170171000
07-27 09:12:25.996  3531  4414 D InputReader: !@notifyKey(172), action=1
07-27 09:12:25.996  3531  4414 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
07-27 09:12:25.996  3531  3692 I WindowManager: All windows ready for display!
07-27 09:12:25.996  3531  3692 W WindowManager: Setting mWindowManagerDrawComplete
07-27 09:12:25.996  3531  3692 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
07-27 09:12:25.996  3531  3692 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
07-27 09:12:25.996  3531  3692 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,07-27 09:12:26.001  3531  7135 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
07-27 09:12:26.001  3531  3692 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,07-27 09:12:26.006  3531  4414 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-27 09:12:26.006  3531  3692 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-27 09:12:26.011  3531  3692 V CAE     : start(ContextProvider.java:128)
07-27 09:12:26.011  3531  3692 V CAE     : clear(AutoRotationRunner.java:182)
,07-27 09:12:26.011  3531  3839 D lights  : led_pattern : 0 -
07-27 09:12:26.011  3531  3839 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-27 09:12:26.011  3531  3692 V CAE     : enable(AutoRotationRunner.java:158)
07-27 09:12:26.011  3531  3692 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
07-27 09:12:26.011  3531  3692 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-27 09:12:26.011  6764  6764 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
07-27 09:12:26.011  6764  6764 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
07-27 09:12:26.011  2933  2933 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-27 09:12:26.016  5570  5570 D SamsungIME: showDlgMsgBox : false true true
,07-27 09:12:26.016  3531  4378 E Sensors : Sensor : Meta event
,07-27 09:12:26.016  3531  3692 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-27 09:12:26.021  3531  3692 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 09:12:26.026  5075 12419 D NfcService: call the applyRouting
07-27 09:12:26.026  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13a195 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f4ab11 11235:com.samsung.android.sm/1000}
,07-27 09:12:26.031  3531  3692 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-27 09:12:26.031  3531  4413 D VoIPInterfaceManager: isVoIPRinging()...
07-27 09:12:26.036  3531  4413 I WindowManager: Ignoring HOME; down is not pressed.
07-27 09:12:26.036  3531  4413 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-27 09:12:26.036  3531  4413 D VoIPInterfaceManager: Not exist call session
,07-27 09:12:26.036  3531  3692 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-27 09:12:26.036  3531  3692 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,07-27 09:12:26.036  3531  3692 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@572b441, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-27 09:12:26.036  3531  3692 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@572b441, Service : ACTIVITY_TRACKER(1)
07-27 09:12:26.036  3531  3692 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1d562aa, Service : AUTO_ROTATION(1)
,07-27 09:12:26.036  3531  3692 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-27 09:12:26.036  3531  3692 D SContextService: 	.registerCallback : 2, client=
07-27 09:12:26.036  3531  3692 D SContextService: ===== SContext Service List =====
07-27 09:12:26.036  3531  3692 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@3791f27, Service : Activity Tracker
07-27 09:12:26.036  3531  3692 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-27 09:12:26.036  3531  3692 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@566fe9b, Service : Auto Rotation
07-27 09:12:26.036  3531  3692 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@d33f30c, service=Auto Rotation
07-27 09:12:26.036  3531  3692 D WindowManager: finishScreenTurningOn: mAwake=true, mScreenOnEarly=true, mScreenOnFully=false, mKeyguardDrawComplete=true, mWindowManagerDrawComplete=true
07-27 09:12:26.036  3531  3826 I DisplayPowerController: Unblocked screen on after 129 ms
07-27 09:12:26.036  3531  3692 I WindowManager: Finished screen turning on...
07-27 09:12:26.036  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:26.036  3531  3826 D ColorFade: prepare: mode=2
07-27 09:12:26.036  3531  3826 D ColorFade: ColorFade is already prepared
07-27 09:12:26.036  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:26.036  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-27 09:12:26.041  3531  5261 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-27 09:12:26.041  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-27 09:12:26.041  3531  5261 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 09:12:26.041  3531  3531 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,07-27 09:12:26.046  3531  3531 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
07-27 09:12:26.046  3531  3531 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3531) 
07-27 09:12:26.046  3531  3531 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
07-27 09:12:26.046  3531  3839 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-27 09:12:26.046  3531  3531 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
07-27 09:12:26.046  3531  3839 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-27 09:12:26.046  3531  3531 D UsbDeviceManager: Keyguard Lock/Unlock
07-27 09:12:26.046  3531  3531 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
07-27 09:12:26.051  3531  3531 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0200
07-27 09:12:26.051  3531  3531 D UsbDeviceManager: updateUsbNotification : cancel id = 17040367, title = Connected as a media device
07-27 09:12:26.051  3531  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13a195 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
07-27 09:12:26.051  3531  3531 D UsbDeviceManager: updateUsbNotification : isKeyguardLocked = false, isKeyguardSecure = false, mBootCompleted = true
07-27 09:12:26.066  3531  3531 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
07-27 09:12:26.066  3531  3531 D UsbDeviceManager: updateUsbNotification : notify id = 17040367, title = Connected as a media device
07-27 09:12:26.066  3531  3531 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
07-27 09:12:26.066  3531  3531 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
07-27 09:12:26.066  3531  3531 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
07-27 09:12:26.066  3531  3531 D PalmMotion: [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
07-27 09:12:26.076  3531  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13a195 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 09:12:26.091  3531  3531 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-27 09:12:26.091  3531  3531 I KnoxTimeoutHandler: Shared devices show user statefalse
07-27 09:12:26.091  3531  3531 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-27 09:12:26.091  3531  3531 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-27 09:12:26.091  3531  3531 D UcmService: notifyChangeToPlugin event 16
07-27 09:12:26.091  3531  3531 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-27 09:12:26.096  3531  3531 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-27 09:12:26.096  3531  3531 D UcmService: notifying to unmanaged plugin
07-27 09:12:26.096  5133  5150 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-27 09:12:26.096  3531  3531 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-27 09:12:26.096  3531  3531 D UcmService: agentService status-0
07-27 09:12:26.096  3531  3531 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-27 09:12:26.096  3531  3531 D UcmService: notifying to unmanaged plugin
07-27 09:12:26.096  5144  5159 D BootAgentService: notifyChange eventId-16
07-27 09:12:26.096  3531  3531 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-27 09:12:26.096  3531  3531 D UcmService: agentService status--1
07-27 09:12:26.096  3531  3531 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
07-27 09:12:26.101  3531  3531 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3531) 
07-27 09:12:26.101  3531  3531 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
07-27 09:12:26.101  3531  3531 D EdgeLight: Turning off
07-27 09:12:26.101  3531  3839 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-27 09:12:26.101  3531  3839 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-27 09:12:26.111  4515  4515 D PanelView: screenCapture for lockscreen preview
07-27 09:12:26.116  3531  3531 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
,07-27 09:12:26.121  3531  3531 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
,07-27 09:12:26.131  3531  5115 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13a195 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6662243 5618:com.google.android.gms.persistent/u0a14}
,07-27 09:12:26.131  5618  5618 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver bqHint=4 }.
,07-27 09:12:26.156  3531  3531 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-27 09:12:26.156  3531  3531 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
07-27 09:12:26.161  3531  3531 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
07-27 09:12:26.161  3531  3531 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
,07-27 09:12:26.161  2933  3101 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-27 09:12:26.166  3531  3531 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-27 09:12:26.171  3531  4407 E MotionRecognitionService:  handler : SCREEN_ON end
,07-27 09:12:26.171  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-C:4
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-27 09:12:26.171  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-27 09:12:26.171  4515  4515 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-27 09:12:26.176  3531  3847 D SurfaceControl: Excessive delay in setPowerMode(): 216ms
07-27 09:12:26.176  3531  3847 D PowerManagerUtil: Excessive delay in !@display_state: ON: 218ms
,07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-C:4
07-27 09:12:26.176  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-27 09:12:26.176  3531  3826 D ColorFade: prepare: mode=2
07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-27 09:12:26.176  3531  3826 D ColorFade: ColorFade is already prepared
07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-27 09:12:26.176  3531  3826 D DisplayPowerController: animateScreenStateChange is returned because lux is not yet valid!
07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-27 09:12:26.176  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-27 09:12:26.176  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-27 09:12:26.176  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-27 09:12:26.181  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:26.176  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-V:8
,07-27 09:12:26.181  3531  3826 D ColorFade: prepare: mode=2
07-27 09:12:26.176  4515  4515 D PhoneStatusBar: animateCollapse(): mExpandedVisible=false flags=0
07-27 09:12:26.181  3531  3826 D ColorFade: ColorFade is already prepared
07-27 09:12:26.176  4515  4515 D StatusBar-Window: fnf=true sanc=false, kni=false, sbf=false
07-27 09:12:26.181  3531  3826 D DisplayPowerController: animateScreenStateChange is returned because lux is not yet valid!
07-27 09:12:26.176  4515  4515 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
07-27 09:12:26.181  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:26.176  4515  4515 D CoverUI : applyHeight h = 96, oc = false, ex = false, fa = false, ac = false, sc = false
07-27 09:12:26.181  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-27 09:12:26.176  4515  4515 V NotificationStackScrollLayout: start: -268.0stackHeight: 268.0
07-27 09:12:26.181  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-27 09:12:26.176  4515  4515 V NotificationStackScrollLayout: start: -268.0stackHeight: 268.0
07-27 09:12:26.176  4515  4515 V NotificationStackScrollLayout: start: -268.0stackHeight: 268.0
,07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-C:4
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-N:false
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-27 09:12:26.181  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-27 09:12:26.181  3531 12428 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 1
,07-27 09:12:26.186  3531 12427 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
,07-27 09:12:26.186  3531 12426 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 1
,07-27 09:12:26.186  3531 12426 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 1
,07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-C:4
07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-N:false
07-27 09:12:26.191  3531  4378 I Sensors : #>LightSensor r=97 g=90 b=72 c=249 atime=238 again=64 lux=46.000000
,07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-0-V:0
07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-N:false,
,07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-1-V:0
07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-N:true
07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-2-V:8
07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-N:false
07-27 09:12:26.191  3531  4494 D AutomaticBrightnessController: [DAB] onSensorChanged : 1st lux : 46.0
07-27 09:12:26.191  4515  4515 D NotificationStackScrollLayout: hasNotification()-3-V:8
07-27 09:12:26.196  3531  4494 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 82(82.0)    2.0 < 46.0 < 129.0 (0.6)
07-27 09:12:26.191  4515  4515 D PanelView: kidsfalse mQsExpansionEnabled:true
07-27 09:12:26.196  3531  4494 D AutomaticBrightnessController: mCallbacks.updateBrightness()
07-27 09:12:26.191 10628 10628 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4a76b40 time:1211369
07-27 09:12:26.196  3531  4494 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
07-27 09:12:26.196  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-27 09:12:26.196  3531  3826 D ColorFade: prepare: mode=2
07-27 09:12:26.196  3531  3826 D ColorFade: ColorFade is already prepared
07-27 09:12:26.196  3531  4494 D PowerManagerUtil: fileWriteInt to /sys/class/lcd/panel/lux, 46
,07-27 09:12:26.196  3531  4495 D lights  : lcd : 82 +
,07-27 09:12:26.196  3531  3826 D DisplayPowerState: !@ [0] ColorFade exit
07-27 09:12:26.196  3531  3826 D PowerManagerService: [input device light] onColorFadeExit(true),
,07-27 09:12:26.201  3531  3531 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
07-27 09:12:26.196  3531  4494 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
07-27 09:12:26.196  3531  3826 D DisplayPowerController: ColorFade: onAnimationStart
07-27 09:12:26.206  3531  4495 D lights  : lcd : 82 -
07-27 09:12:26.196  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:26.196  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 82 -> 82
,07-27 09:12:26.196  3531  3826 D DisplayPowerController: Animating brightness: target=82, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:26.196  3531  3826 D DisplayPowerState: Requesting new screen state: [0] state=ON, backlight (By colorFade)=82
07-27 09:12:26.196  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:26.196  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 82 -> 82
07-27 09:12:26.196  3531  4495 D DisplayPowerState: Updating screen state [0]: state=ON, backlight (by ColorFade)=82
07-27 09:12:26.196  3531  3826 D DisplayPowerController: Animating brightness: target=82, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:26.201  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:26.201  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 82 -> 82
,07-27 09:12:26.201  3531  3826 D DisplayPowerController: Animating brightness: target=82, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:26.206  3531  3531 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-27 09:12:26.206  3531  4494 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
07-27 09:12:26.206  3531  3531 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-27 09:12:26.206  3531  3531 D UcmService: notifyChangeToPlugin event 16
07-27 09:12:26.206  3531  3531 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-27 09:12:26.206  3531  3531 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-27 09:12:26.206  3531  3531 D UcmService: notifying to unmanaged plugin
,07-27 09:12:26.206  5133  5143 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-27 09:12:26.206  3531  3531 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-27 09:12:26.206  3531  3531 D UcmService: agentService status-0
07-27 09:12:26.206  3531  3531 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-27 09:12:26.206  3531  3531 D UcmService: notifying to unmanaged plugin
07-27 09:12:26.206  5144  5165 D BootAgentService: notifyChange eventId-16
07-27 09:12:26.206  3531  3531 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-27 09:12:26.206  3531  3531 D UcmService: agentService status--1
07-27 09:12:26.206  3531  3531 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-27 09:12:26.211  4515  4515 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,07-27 09:12:26.226  4515  4515 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,07-27 09:12:26.241  3531  3531 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 09:12:26.251  4515  4515 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-27 09:12:26.256  3531  4446 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
07-27 09:12:26.256  3531  4446 D WifiNative-wlan0: callSECApiBoolean - ID [11]
,07-27 09:12:26.256  3531  3531 D NotificationService: ACTION_SCREEN_ON
07-27 09:12:26.256  3531  3531 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3531) 
07-27 09:12:26.256 10708 10708 I wpa_supplicant: STOP_PERIODIC_SCAN command
07-27 09:12:26.256  3531  3531 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
07-27 09:12:26.256  3531  3531 D EdgeLight: Turning off
,07-27 09:12:26.261  3531  3839 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-27 09:12:26.261  3531  3839 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-27 09:12:26.261  3531  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -34], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
07-27 09:12:26.261  3531  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-27 09:12:26.266  3531  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 09:12:26.266  3531  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-27 09:12:26.266  3531  4453 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  2923  4379 I AudioHardwareTinyALSA: setParameters(screen_state=on)
07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  4515  4515 D PanelView: kidsfalse mQsExpansionEnabled:true
07-27 09:12:26.266  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 09:12:26.266  3531  4446 E WifiNative-wlan0: do suspend false
07-27 09:12:26.276  3531  4446 D WifiStateMachine: analyze kernel wifi wakelock 
07-27 09:12:26.276  3531  4446 D WifiStateMachine: file not found /proc/wakelocks
07-27 09:12:26.276  3531  3531 V AlarmManager:  remove PendingIntent] PendingIntent{e0cbe56: PendingIntentRecord{9ef6ed7 android broadcastIntent}}
07-27 09:12:26.276  4515  4515 D Recents : handleProxyCall type=3
07-27 09:12:26.286  4689  4689 D Recents : handleProxyCall type=3
07-27 09:12:26.291  3531  4446 E WifiStateMachine: analyzeKernelWifiWakelocks done - last length : 1
07-27 09:12:26.296  3531  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]
,07-27 09:12:26.311  3531  4447 V AlarmManager:  remove PendingIntent] PendingIntent{1e3c4: PendingIntentRecord{1cbe2ad android broadcastIntent}}
,07-27 09:12:26.321  3531  3802 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-27 09:12:26.321  3531  3802 D IpRemoteDisplayController: Bridge Server is not available
,07-27 09:12:26.336  3531  4444 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
,07-27 09:12:26.336  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,07-27 09:12:26.336  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
,07-27 09:12:26.356  3531  3826 D DisplayPowerController: ColorFade: onAnimationEnd
,07-27 09:12:26.356  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:26.361  3531 12428 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-27 09:12:26.361  2906  4429 D libEGL  : eglTerminate EGLDisplay = 0xb1f7f624
07-27 09:12:26.361  2906  4429 D libEGL  : eglTerminate EGLDisplay = 0xb1f7f624
,07-27 09:12:26.361  3531  3826 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-27 09:12:26.361  2906 12431 I SurfaceFlinger: id=13 Removed DolorFade (8/8)
07-27 09:12:26.361  2906 12433 I SurfaceFlinger: id=13 Removed DolorFade (-2/8)
07-27 09:12:26.361  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:26.361  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 82 -> 82
07-27 09:12:26.366  3531  3826 D DisplayPowerController: Animating brightness: target=82, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:26.366  3531  3826 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
07-27 09:12:26.366  3531  3826 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
07-27 09:12:26.366  3531  3826 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-27 09:12:26.366  4515  4542 D KeyguardViewMediator: notifyScreenTurnedOn
07-27 09:12:26.366  3531  3826 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-27 09:12:26.366  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() start
07-27 09:12:26.366  3531  3826 D PowerManagerService: mDisplayReady: true
07-27 09:12:26.366  4515  4515 D KeyguardViewMediator: handleNotifyScreenTurnedOn
07-27 09:12:26.366  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() end
07-27 09:12:26.366  3531  4492 I WindowManager: Finished waking up...
,07-27 09:12:26.376  3531  4378 I Sensors : #>LightSensor r=97 g=90 b=73 c=250 atime=238 again=64 lux=46.000000
,07-27 09:12:26.376  2906  2906 D libEGL  : eglTerminate EGLDisplay = 0xbed03474
,07-27 09:12:26.381  3531 12427 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
,07-27 09:12:26.381  3531  3847 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
,07-27 09:12:26.381  3531  3847 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-27 09:12:26.381  3531  3847 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 206ms
07-27 09:12:26.381  3531  3847 D PowerManagerUtil: Excessive delay in nativeSetInteractive(true): 206ms
07-27 09:12:26.381  3531  4493 D lights  : button : 1 +
07-27 09:12:26.381  3531  3847 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 424ms
07-27 09:12:26.381  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:26.381  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:26.381  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 82 -> 82
07-27 09:12:26.381  3531  3826 D DisplayPowerController: Animating brightness: target=82, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:26.396  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-27 09:12:26.396  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:26.396  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:26.396  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:26.396  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:26.416  3531  4493 D lights  : button : 1 -
,07-27 09:12:26.561  3531  4378 I Sensors : #>LightSensor r=99 g=93 b=76 c=258 atime=238 again=64 lux=48.000000
,07-27 09:12:26.901  3531  3531 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1200000  uid : 1000  pid : 3531  tag : WAKEUP_BOOSTER@31
,07-27 09:12:27.191  3531  3673 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-27 09:12:27.201  3531  3531 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,07-27 09:12:27.201  3531  3894 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
07-27 09:12:27.201  3531  5021 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
07-27 09:12:27.201  5075  5075 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-27 09:12:27.201  5075 12436 D NfcService: call the applyRouting
,07-27 09:12:27.211  4515  4515 D StatusBar.NetworkController: onDataActivity: direction=0
,07-27 09:12:27.211  3531  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 09:12:27.211  3531  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-27 09:12:27.211  3531  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:12:27.216  4515  4515 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-27 09:12:27.216  3531  3531 V AlarmManager:  remove PendingIntent] PendingIntent{469a249: PendingIntentRecord{ef7e75c android broadcastIntent}}
07-27 09:12:27.216  3531  3531 V AlarmManager:  remove PendingIntent] PendingIntent{de2874e: PendingIntentRecord{7372db7 android broadcastIntent}}
,07-27 09:12:27.221  5570  5570 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:113 [0:0] getInstance
,07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:113 [0:0] getInstance
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:283 [0:0] direct update clock
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:152 [0:0] make widget 4x1 view!!! 
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:154 [0:0] make widget 4x2 view!!! 
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:1492 [0:0] mc sy = 2
,07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:179 [0:0] get widget 4x2 view!!! wid = 2
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> U:884 [0:0] locale = en
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> U:894 [0:0] Locale format : MMM d, y
07-27 09:12:27.231  5921  5921 D accuweather: [KK AccuPhone]>>> U:915 [0:0] locale = E, MMMM d
,07-27 09:12:27.231  5921  5921 E accuweather: [KK AccuPhone]>>> UIM:1547 [0:0] bTM 09 12
,07-27 09:12:27.246  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 261 (W:28), CUR = -2, LCD = 82
,07-27 09:12:27.266  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:12:27.276  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4c0c48b u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f3f3964 4626:com.sec.android.daemonapp/u0a196}
,07-27 09:12:27.276  7198  7198 D SensorManager: unregisterListener ::   
,07-27 09:12:27.276  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
07-27 09:12:27.276  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
07-27 09:12:27.276  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
07-27 09:12:27.281  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
07-27 09:12:27.281  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:12:27.286  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
07-27 09:12:27.286  4626  4626 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:12:27.286  4626  4626 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-27 09:12:27.286  4626  4626 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-27 09:12:27.286  4626  4626 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-27 09:12:27.286  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
07-27 09:12:27.286  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-27 09:12:27.286  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1469623920000
,07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1469603547293
07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 09:12:27.291 10696 10696 D BtGatt.GattService: LCD turned on
07-27 09:12:27.291 10696 10735 D BtGatt.ScanManager: handleLcdOnIntent
07-27 09:12:27.291 10696 10735 D BtGatt.ScanManager: handleLcdOnIntent
,07-27 09:12:27.291 10696 10735 D BtGatt.ScanManager: ClientIf = 0
07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
07-27 09:12:27.291  4626  4626 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,07-27 09:12:27.296  4626  4626 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-27 09:12:27.296  3531  4492 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-27 09:12:27.296  4626  4626 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,07-27 09:12:27.361  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c3/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-27 09:12:27.361  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:27.361  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:27.361  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:27.361  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:27.361  3531 12437 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
07-27 09:12:27.361  3531 12437 D BluetoothAdapter: STATE_ON
,07-27 09:12:27.361  3531  5115 V AlarmManager:  remove PendingIntent] PendingIntent{783968: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:27.406  3531 12437 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-27 09:12:27.451  3531 12437 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-27 09:12:27.456  3531 12437 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-27 09:12:27.606  3531  3673 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:12:27.626  3531 12437 I BatteryStatsDumper: Writing to database completed
,07-27 09:12:27.881  3531  4493 D lights  : button : 0 +
,07-27 09:12:27.916  3531  4493 D lights  : button : 0 -
,07-27 09:12:28.366  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:28.366  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:28.381  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:28.381  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:28.391  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,07-27 09:12:28.866  3531  5686 V AlarmManager:  remove PendingIntent] PendingIntent{31e5181: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:29.371  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:29.371  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:29.381  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:29.386  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:29.386  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:30.781  3531  4968 E Watchdog: !@Sync 40 [07-27 09:12:30.785]
,07-27 09:12:30.816  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3,
07-27 09:12:30.816  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:12:30.831  3531  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:12:30.831  3531  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:12:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:12:31.376  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:31.376  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:31.381  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:31.381  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:31.386  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:32.381  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:32.381  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:32.386  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:32.391  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:32.391  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:33.546  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:12:33.546  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:12:34.391  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:34.391  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:34.396  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:34.401  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:34.401  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:35.396  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:35.396  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:35.401  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:35.406  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:35.406  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:37.281  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 261 (W:28), CUR = -2, LCD = 82
,07-27 09:12:37.406  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:37.406  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:37.411  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:37.416  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:37.416  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:38.416  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:38.416  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:38.421  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:38.421  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:38.421  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:40.426  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:40.426  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:40.431  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:40.431  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:40.431  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:41.431  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:41.431  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:41.436  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:41.436  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:41.441  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:43.441  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:43.441  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:43.446  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:43.451  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:43.451  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:44.451  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:44.451  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:44.456  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
07-27 09:12:44.456  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:44.456  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:46.461  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:46.461  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:46.466  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:46.466  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:46.466  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,07-27 09:12:47.306  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 261 (W:30), CUR = -2, LCD = 82
,07-27 09:12:47.466  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:47.466  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:47.471  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:47.471  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:47.471  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:49.476  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:49.476  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:49.481  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:49.481  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:49.481  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:49.996  3531  3826 D PowerManagerService: [s] UserActivityState : 1 -> 2
07-27 09:12:49.996  3531  3826 D PowerManagerService: mDisplayReady: false
07-27 09:12:49.996  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:49.996  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:49.996  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:49.996  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:49.996  3531  3826 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-27 09:12:49.996  3531  3826 D PowerManagerService: mDisplayReady: true
,07-27 09:12:50.016  3531  4495 D lights  : lcd : 74 +
,07-27 09:12:50.021  3531  4495 D lights  : lcd : 74 -
,07-27 09:12:50.026  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:50.026  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.026  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:50.026  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.031  3531  4495 D lights  : lcd : 65 +
,07-27 09:12:50.036  3531  4495 D lights  : lcd : 65 -
,07-27 09:12:50.036  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-27 09:12:50.041  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.041  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:50.041  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.051  3531  4495 D lights  : lcd : 57 +
,07-27 09:12:50.051  3531  4495 D lights  : lcd : 57 -
,07-27 09:12:50.056  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-27 09:12:50.056  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.056  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:50.056  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.066  3531  4495 D lights  : lcd : 48 +
,07-27 09:12:50.071  3531  4495 D lights  : lcd : 48 -
,07-27 09:12:50.071  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-27 09:12:50.071  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.071  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-27 09:12:50.071  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.086  3531  4495 D lights  : lcd : 40 +
,07-27 09:12:50.086  3531  4495 D lights  : lcd : 40 -
,07-27 09:12:50.091  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:50.091  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.091  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:50.091  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.101  3531  4495 D lights  : lcd : 31 +
,07-27 09:12:50.101  3531  4495 D lights  : lcd : 31 -
07-27 09:12:50.106  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-27 09:12:50.106  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.106  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:50.106  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.116  3531  4495 D lights  : lcd : 23 +
,07-27 09:12:50.121  3531  4495 D lights  : lcd : 23 -
,07-27 09:12:50.121  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:50.121  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.121  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-27 09:12:50.121  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.136  3531  4495 D lights  : lcd : 15 +
,07-27 09:12:50.136  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-27 09:12:50.136  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.136  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:50.136  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.136  3531  4495 D lights  : lcd : 15 -
,07-27 09:12:50.141  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-27 09:12:50.141  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:50.141  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-27 09:12:50.141  3531  3826 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-27 09:12:50.481  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-27 09:12:50.481  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:50.486  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:50.491  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:50.491  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:52.491  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:52.491  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:52.496  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:52.496  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:52.501  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:53.496  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:53.496  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:53.501  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:53.501  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:53.506  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:53.796  3531  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:12:53.796  3531  4439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:12:53.796  3531  4439 D BatteryService: online:4, current avg:-4, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:12:53.796  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:12:53.801  3531  3531 I MotionRecognitionService: Plugged
07-27 09:12:53.801  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:12:53.801  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:12:53.801  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:12:53.806  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:12:53.806  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:12:53.806  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:12:53.811  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:12:53.821 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:12:53.821 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:12:53.826  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:12:53.826  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:12:55.506  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c1/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:55.506  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:55.511  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:55.511  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:55.516  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:56.196  3531  3826 D PowerManagerService: [s] UserActivityState : 2 -> 4
07-27 09:12:56.196  3531  3826 D InputManager-JNI: setInteractive(false)
07-27 09:12:56.196  3531  3826 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
07-27 09:12:56.196  3531  3826 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-27 09:12:56.196  3531  4492 I WindowManager: Started going to sleep... (why=3)
,07-27 09:12:56.196  3531  4492 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
,07-27 09:12:56.196  3531  3826 D PowerManagerService: mDisplayReady: false
07-27 09:12:56.201  4515  5403 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() start
07-27 09:12:56.196  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-27 09:12:56.201  4515  5403 D KeyguardViewMediator: onStartedGoingToSleep(3)
07-27 09:12:56.196  3531  3826 D ColorFade: prepare: mode=4
07-27 09:12:56.201 10628 10628 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-27 09:12:56.201  2906  2906 I SurfaceFlinger: id=21 createSurf (1440x2560),2 flag=404, DolorFade
,07-27 09:12:56.216  3531  3826 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 18ms
,07-27 09:12:56.221  3531  3826 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,07-27 09:12:56.226  4515  5403 D KeyguardViewMediator: timeout : 5000
,07-27 09:12:56.236  4515  5403 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
07-27 09:12:56.236  4515  5403 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() end
,07-27 09:12:56.256  3531  3826 D libEGL  : eglInitialize EGLDisplay = 0x9ab7f0a4
,07-27 09:12:56.261  3531  3826 D libEGL  : eglTerminate EGLDisplay = 0x9ab7f1c4
,07-27 09:12:56.266  3531  3826 D ColorFade: ColorFade is ready
07-27 09:12:56.266  3531  3826 D DisplayPowerController: ColorFade: onAnimationStart
07-27 09:12:56.266  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-27 09:12:56.266  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 82 -> 82
,07-27 09:12:56.291  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c
,07-27 09:12:56.301  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c,
,07-27 09:12:56.316  2906  2906 D libEGL  : eglInitialize EGLDisplay = 0xbed0340c
,07-27 09:12:56.511  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:56.511  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:56.511  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:56.511  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:56.511  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:56.571  3531  3826 D DisplayPowerState: !@ [0] ColorFade entry
07-27 09:12:56.571  3531  3826 D PowerManagerService: [input device light] onColorFadeExit(false)
07-27 09:12:56.571  3531  3826 D DisplayPowerController: ColorFade: onAnimationEnd
,07-27 09:12:56.591  3531  4495 D lights  : lcd : 0 +
07-27 09:12:56.591  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-27 09:12:56.591  3531  3826 I WindowManager: Screen turned off...
07-27 09:12:56.591  3531  3826 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
07-27 09:12:56.591  3531  4495 D lights  : lcd : 0 -
,07-27 09:12:56.631 10628 10628 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 09:12:56.631 10628 10628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-27 09:12:56.696  3531  3826 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@566fe9b, Service = Auto Rotation, used = 0
,07-27 09:12:56.696  3531  3826 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
07-27 09:12:56.696 10628 10628 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f8eade6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d4fdb1b, 16908290=android.view.AbsSavedState$1@d4fdb1b}, android:focusedViewId=100}]}]
07-27 09:12:56.696 10628 10628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-27 09:12:56.696 10628 10628 V ActivityThread: updateVisibility : ActivityRecord{9692dca token=android.os.BinderProxy@4a76b40 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-27 09:12:56.696 10628 10628 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 09:12:56.696 10628 10628 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-27 09:12:56.696  3531  3826 V CAE     : stop(ContextProvider.java:155)
,07-27 09:12:56.701  3531  3826 V CAE     : clear(AutoRotationRunner.java:182)
,07-27 09:12:56.701  3531  3826 V CAE     : disable(AutoRotationRunner.java:171)
,07-27 09:12:56.701  3531  3826 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
07-27 09:12:56.701  3531  3826 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
07-27 09:12:56.701  2933  2933 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-27 09:12:56.711  3531  3826 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-27 09:12:56.711  3531  3826 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 09:12:56.716  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
,07-27 09:12:56.726  3531  3826 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-27 09:12:56.726  3531  3826 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-27 09:12:56.731  3531  3826 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-27 09:12:56.731  3531  3826 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@572b441, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-27 09:12:56.731  3531  3826 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@572b441, Service : ACTIVITY_TRACKER(1)
07-27 09:12:56.731  3531  3826 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-27 09:12:56.731  3531  3826 D SContextService: 	.unregisterCallback : 2, client=
07-27 09:12:56.731  3531  3826 D SContextService: ===== SContext Service List =====
07-27 09:12:56.731  3531  3826 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@3791f27, Service : Activity Tracker
07-27 09:12:56.731  3531  3826 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@d33f30c, service=Auto Rotation
07-27 09:12:56.731  3531  3826 V KeyguardServiceDelegate: onScreenTurnedOff()
07-27 09:12:56.731  4515  4542 D KeyguardViewMediator: notifyScreenTurnedOff
07-27 09:12:56.731  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() start
,07-27 09:12:56.731  4515  4515 D KeyguardViewMediator: handleNotifyScreenTurnedOff
07-27 09:12:56.731  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() end
07-27 09:12:56.731  3531  3826 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
07-27 09:12:56.731  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-27 09:12:56.731  3531  3826 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
07-27 09:12:56.731  3531  4494 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
07-27 09:12:56.731  3531  3826 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
07-27 09:12:56.731  3531  4494 I Sensors : Light old sensor_state 513, new sensor_state : 1 en : 0
,07-27 09:12:56.731  3531  3826 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
07-27 09:12:56.731  3531  3826 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-27 09:12:56.731  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-27 09:12:56.731  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:56.731  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-27 09:12:56.731  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-27 09:12:56.731  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,07-27 09:12:56.731  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:56.736  3531  4494 D SensorManager: unregisterListener ::   
,07-27 09:12:56.736  3531 12449 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 0
07-27 09:12:56.736  3531  4494 I Sensors : Acc old sensor_state 1, new sensor_state : 0 en : 0
,07-27 09:12:56.736  3531 12451 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 0
07-27 09:12:56.736  3531 12450 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
07-27 09:12:56.736  3531 12449 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 0
07-27 09:12:56.736  3531 12450 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
07-27 09:12:56.736  3531  4494 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::unregisterListener done: 5ms
07-27 09:12:56.736  3531  4494 D SensorManager: unregisterListener ::   
,07-27 09:12:56.741  3531 12451 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 0,
07-27 09:12:56.741  3531  3847 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-27 09:12:56.741  3531  3847 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-27 09:12:56.741  3531  3847 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
07-27 09:12:56.741  3531  3802 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-27 09:12:56.746  2906  2906 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a24000
,07-27 09:12:56.746  2906  2906 I hwcomposer: int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,07-27 09:12:56.796  3531  3546 I art     : Background partial concurrent mark sweep GC freed 96153(7MB) AllocSpace objects, 177(3MB) LOS objects, 33% free, 31MB/46MB, paused 2.138ms total 181.911ms
,07-27 09:12:56.921  3531  3847 D SurfaceControl: Excessive delay in setPowerMode(): 180ms
07-27 09:12:56.921  3531  3847 I libsuspend: !@autosuspend_wakeup_count_enable
07-27 09:12:56.921  3531  3847 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 180ms
07-27 09:12:56.921  3531  3847 I libsuspend: !@autosuspend_wakeup_count_enable done
07-27 09:12:56.921  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-27 09:12:56.921  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-27 09:12:56.921  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-27 09:12:56.921  3531  4492 I WindowManager: Finished going to sleep... (why=3)
07-27 09:12:56.921  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:56.921  3531  4492 D PersonaManagerService: onfinishedGoingToSleep why = 3
07-27 09:12:56.921  3531  3826 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-27 09:12:56.921  4515  4532 D KeyguardViewMediator: onFinishedGoingToSleep(3)
07-27 09:12:56.921  3531  3826 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-27 09:12:56.921  4515  4532 D KeyguardViewMediator: onFinishedGoingToSleep: mPendingLock false
07-27 09:12:56.921  3531  3826 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-27 09:12:56.921  4515  4532 D KeyguardViewMediator: notifyFinishedGoingToSleep
07-27 09:12:56.921  3531  3826 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-27 09:12:56.921  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() start
,07-27 09:12:56.921  3531  3847 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 188ms
07-27 09:12:56.921  4515  4515 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
07-27 09:12:56.921  3531  3826 I PowerManagerService: [PWL] Off : 0s ago
07-27 09:12:56.921  3531  3894 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
07-27 09:12:56.921  3531  3826 I PowerManagerService: [PWL]   PowerManagerService.Display: ref count=2
07-27 09:12:56.921  4515  4515 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() end
,07-27 09:12:56.921  3531  3826 I PowerManagerService: [PWL]     mUserActivitySummary : 0x4
07-27 09:12:56.921  3531  3826 I PowerManagerService: [PWL]     mDisplayReady : false
07-27 09:12:56.926  4515  4515 D vol.SecVolumeDialog: dismissH : false
07-27 09:12:56.921  3531  3826 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-27 09:12:56.926  4515  4515 D SecKeyguardClockSingleView: onScreenTurnedOff
07-27 09:12:56.921  3531  3826 D PowerManagerService: mDisplayReady: true
,07-27 09:12:56.926  4515  4515 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOff() end
07-27 09:12:56.921  3531  3826 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
07-27 09:12:56.921  3531  3826 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
07-27 09:12:56.921  3531  3826 D PowerManagerService: handleSandman : startDream(true)
07-27 09:12:56.921  3531  3826 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
,07-27 09:12:56.921  3531  3826 I PowerManagerService: Sleeping (uid 1000)...
07-27 09:12:56.921  3531  3826 D PowerManagerService: [s] UserActivityState : 4 -> 0
07-27 09:12:56.921  3531  3826 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-27 09:12:56.966  3531  3531 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3531) 
,07-27 09:12:56.966  3531  3531 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,07-27 09:12:56.966  3531  3531 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:12:56.966  3531  3531 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,07-27 09:12:56.981  3531  3531 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-27 09:12:56.981  3531  3531 D BatteryService: turn on LED for fully charged
,07-27 09:12:57.021  3531  3531 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-27 09:12:57.021  3531  3531 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
07-27 09:12:57.021  3531  3531 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
07-27 09:12:57.026  3531  3531 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-27 09:12:57.026  2933  3101 D Sensorhubs: sendContextData: -76, 13, -46, 0
07-27 09:12:57.026  3531  3531 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 7, 12, 57,
07-27 09:12:57.026  3531  3531 D SensorHubManager: SendSensorHubData: send data = -63, 14, 7, 12, 57
07-27 09:12:57.026  2933  2933 D Sensorhubs: sendContextData: -63, 14, 7, 12, 57
,07-27 09:12:57.036  3531  3531 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-27 09:12:57.046  3531  4407 D MotionRecognitionService: Screen off setAccIntStatus 
,07-27 09:12:57.046  3531  4407 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-27 09:12:57.071  3531  3685 I ActivityManager: Start proc 12453:com.android.settings/1000 for broadcast-3 com.android.settings/.accessibility.directaccess.DirectAccessReceiver
07-27 09:12:57.071 12453 12453 E Zygote  : v2
07-27 09:12:57.071 12453 12453 I libpersona: KNOX_SDCARD checking this for 1000
07-27 09:12:57.071 12453 12453 I libpersona: KNOX_SDCARD not a persona
,07-27 09:12:57.071 12453 12453 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-27 09:12:57.071 12453 12453 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-27 09:12:57.076 12453 12453 E Zygote  : accessInfo : 0
,07-27 09:12:57.086  3531  3531 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,07-27 09:12:57.096  3531  3531 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-27 09:12:57.096  3531  3531 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-27 09:12:57.096  3531  3531 D UcmService: notifyChangeToPlugin event 16
07-27 09:12:57.096  3531  3531 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-27 09:12:57.096  3531  3531 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-27 09:12:57.096  3531  3531 D UcmService: notifying to unmanaged plugin
07-27 09:12:57.101  5133  5143 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-27 09:12:57.101  3531  3531 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-27 09:12:57.101  3531  3531 D UcmService: agentService status-0
07-27 09:12:57.101  3531  3531 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-27 09:12:57.101  3531  3531 D UcmService: notifying to unmanaged plugin
07-27 09:12:57.101  5144  5165 D BootAgentService: notifyChange eventId-16
07-27 09:12:57.101  3531  3531 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-27 09:12:57.101  3531  3531 D UcmService: agentService status--1
07-27 09:12:57.101  3531  3531 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-27 09:12:57.106 12453 12453 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 09:12:57.106 12453 12453 D ActivityThread: Added TimaKeyStore provider
,07-27 09:12:57.111  3531  3531 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 09:12:57.126  3531  5110 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff14ab2 u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{62b3a03 12453:com.android.settings/1000}
,07-27 09:12:57.136  3531  4446 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
07-27 09:12:57.136  3531  4446 D WifiNative-wlan0: callSECApiVoid - ID [19]
07-27 09:12:57.136 10708 10708 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
,07-27 09:12:57.136  3531  3531 D NotificationService: ACTION_SCREEN_OFF
07-27 09:12:57.136  3531  3531 D EdgeLight: Turning off
07-27 09:12:57.136  3531  3531 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3531) 
07-27 09:12:57.136  3531  3531 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,07-27 09:12:57.141  3531  4446 E WifiNative-wlan0: do suspend true
,07-27 09:12:57.146  2923  2923 I AudioHardwareTinyALSA: setParameters(screen_state=off)
,07-27 09:12:57.171  3531  3531 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
07-27 09:12:57.171 12453 12453 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings/lib/arm
,07-27 09:12:57.181  3531  3531 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-27 09:12:57.191  3531  3531 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
07-27 09:12:57.191  3531  3531 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3791f27, Service = Activity Tracker, used = 0
,07-27 09:12:57.191  3531  3531 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
,07-27 09:12:57.191  3531  3531 V CAE     : stop(ContextProvider.java:155)
,07-27 09:12:57.191  3531  3531 V CAE     : clear(ActivityTrackerRunner.java:108)
07-27 09:12:57.191  3531  3531 V CAE     : disable(ActivityTrackerRunner.java:96)
,07-27 09:12:57.196  3531  3531 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
,07-27 09:12:57.196  3531  3531 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
07-27 09:12:57.196  2933  3101 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-27 09:12:57.201 12453 12453 D MySettingsProvider: DatabaseHelper(Context context):DATABASE_VERSION=1
,07-27 09:12:57.206  3531  3531 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-27 09:12:57.206  3531  3531 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-27 09:12:57.206 12453 12453 D MySettingsProvider: onCreate():(mDB == null)? false:true  =true
,07-27 09:12:57.206  3531  4378 I Sensors : #>LightSensor r=98 g=91 b=73 c=252 atime=238 again=64 lux=47.000000
,07-27 09:12:57.211  3531  3839 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
07-27 09:12:57.211  3531  3839 D LightsService: [SvcLED]  onSensorChanged::light value = 47
,07-27 09:12:57.211  3531  3839 D SensorManager: unregisterListener ::   
,07-27 09:12:57.211  3531  3839 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
07-27 09:12:57.211  3531  3839 D lights  : led_pattern : 5 +
,07-27 09:12:57.216  3531  3839 D lights  : led_pattern : 5 -
,07-27 09:12:57.216  3531  3531 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-27 09:12:57.221  3531  3839 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-27 09:12:57.221  3531  3531 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-27 09:12:57.221  3531  3531 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-27 09:12:57.221  3531  3839 V AlarmManager:  remove PendingIntent] PendingIntent{cd422e: PendingIntentRecord{f2361cf android broadcastIntent}}
07-27 09:12:57.221  3531  3531 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@572b441, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-27 09:12:57.221  3531  3531 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-27 09:12:57.221  3531  3531 D SContextService: 	.unregisterCallback : 1, client=
07-27 09:12:57.221  3531  3531 D SContextService: ===== SContext Service List =====
07-27 09:12:57.221  3531  3531 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$12@8bde6, service=Activity Tracker
,07-27 09:12:57.236  3531  3802 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,07-27 09:12:57.236  3531  3802 D IpRemoteDisplayController: Bridge Server is not available
,07-27 09:12:57.256  4515  4515 D vol.SecVolumeDialog: dismissH : false
,07-27 09:12:57.271  3531  3531 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,07-27 09:12:57.276  3531  4444 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
07-27 09:12:57.276  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-27 09:12:57.311  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 262 (W:30), CUR = -4, LCD = 0
,07-27 09:12:57.696  4689  4689 D Recents : onTaskStackChanged
,07-27 09:12:57.916  3531  3673 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-27 09:12:57.926  5075 12466 D NfcService: call the applyRouting
,07-27 09:12:57.931  4515  4515 D StatusBar.NetworkController: onDataActivity: direction=0
,07-27 09:12:57.931  4515  4515 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-27 09:12:57.961  5921  5921 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
07-27 09:12:57.961  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:113 [0:0] getInstance
,07-27 09:12:57.966  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{862afb9 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_OFF qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a5bad34 5921:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-27 09:12:57.966  5921  5921 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,07-27 09:12:57.976  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 263 (W:30), CUR = -4, LCD = 0
,07-27 09:12:57.976  5921  5921 D accuweather: [KK AccuPhone]>>> U:4139 [0:0] getPWC : surface = 0, remote = 1
07-27 09:12:57.976  5921  5921 D accuweather: [KK AccuPhone]>>> U:4338 [0:0] Store PWC = 1
,07-27 09:12:57.976  5921  5921 D accuweather: [KK AccuPhone]>>> U:4199 [0:0] addPWC = 1
07-27 09:12:57.976  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,07-27 09:12:57.986  4626  4853 D daemonapp: [MSC_Daemon]>>> WCP:1255 [0:0] cp update : count : 1, pt : 4
,07-27 09:12:57.986  4626  4639 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-27 09:12:57.991  3531  6657 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-27 09:12:57.991  3531  5679 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-27 09:12:57.991  3531  5110 I Sensors : Acc old sensor_state 0, new sensor_state : 1 en : 1
,07-27 09:12:57.996  4626  6618 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-27 09:12:58.001  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:152 [0:0] make widget 4x1 view!!! 
,07-27 09:12:58.001  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:154 [0:0] make widget 4x2 view!!! 
07-27 09:12:58.001  5921  5921 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
07-27 09:12:58.001  5921  5921 D accuweather: [KK AccuPhone]>>> UIM:179 [0:0] get widget 4x2 view!!! wid = 2
,07-27 09:12:58.006  7198  7198 D SensorManager: registerListener :: 0, ICM20610 Acceleration Sensor, 200000, 0,  
,07-27 09:12:58.006  3531  5022 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{862afb9 u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_OFF qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a5bad34 5921:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-27 09:12:58.011  5921  5921 D accuweather: [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,07-27 09:12:58.011  5921  5921 D accuweather: [KK AccuPhone]>>> U:4298 [0:0] Store PWC succeed
,07-27 09:12:58.021  5921  5921 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,07-27 09:12:58.021  5921  5921 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,07-27 09:12:58.026 10696 10696 D BtGatt.GattService: LCD turned off
07-27 09:12:58.026 10696 10735 D BtGatt.ScanManager: handleLcdOffIntent
07-27 09:12:58.026 10696 10735 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,07-27 09:12:58.031  3531  4492 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-27 09:12:58.031  4515  4515 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-27 09:12:58.031  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:58.031  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:58.031  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-27 09:12:58.031  4515  4515 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-27 09:12:58.081  3531 12467 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-27 09:12:58.081  3531 12467 D BluetoothAdapter: STATE_ON
,07-27 09:12:58.086  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{5a55ffe: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:58.126  3531 12467 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-27 09:12:58.171  3531 12467 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-27 09:12:58.181  3531 12467 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-27 09:12:58.261  3531 12467 I BatteryStatsDumper: Writing to database completed
,07-27 09:12:59.091  3531  6663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-27 09:12:59.101  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b2b41ac u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6758e75 12123:com.samsung.android.sm.provider/1000}
,07-27 09:12:59.586  3531  3557 V AlarmManager:  remove PendingIntent] PendingIntent{1cfe67b: PendingIntentRecord{4f66924 com.android.bluetooth broadcastIntent}}
,07-27 09:12:59.996  3531  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:13:00.786  3531  4968 E Watchdog: !@Sync 41 [07-27 09:13:00.788]
,07-27 09:13:01.231  3531  4400 V AlarmManager: Expired Alarm result :4
,07-27 09:13:01.251  4515  4515 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-27 09:13:01.256  4515  4515 D KeyguardViewMediator: doKeyguardLocked: started
,07-27 09:13:01.281  4515  4515 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-27 09:13:01.286  4515  4515 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
07-27 09:13:01.286  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 09:13:01.286  4515  4515 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:13:01.286  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:13:01.296  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:13:01.306  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:13:01.311  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:01.316  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:01.331  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:01.331  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:01.346  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:01.346  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:01.351  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:01.426  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:13:08.021  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 263 (W:30), CUR = -4, LCD = 0
,07-27 09:13:09.706  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:13:09.706  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:13:10.181  3531  4400 V AlarmManager: Expired Alarm result :4
,07-27 09:13:10.226  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1621a44 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c151438 7413:com.google.android.gms/u0a14}
,07-27 09:13:10.291  3531  3531 I BackgroundCompactionService: onStart. jobID=801
,07-27 09:13:10.291  3531  3531 I BackgroundCompactionService: onStart done. jobID=801
07-27 09:13:10.291  3531 12528 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-27 09:13:10.291  3531 12528 I BackgroundCompactionService: compact_memory command done
,07-27 09:13:10.331  7413 12527 I EventLogChimeraService: Aggregate from 1469601642347 (log), 1469601642347 (data)
,07-27 09:13:10.486  3531  3685 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6f7dba u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f4ab11 11235:com.samsung.android.sm/1000}
,07-27 09:13:10.511  3531  5679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f6f7dba u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c151438 7413:com.google.android.gms/u0a14}
,07-27 09:13:10.546  3531  4879 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dec8bc8 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5f4ab11 11235:com.samsung.android.sm/1000}
,07-27 09:13:10.581  3531  5110 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dec8bc8 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c151438 7413:com.google.android.gms/u0a14}
,07-27 09:13:10.766  7413 12534 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 09:13:10.811  7413 12534 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 09:13:18.071  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 263 (W:30), CUR = -4, LCD = 0
,07-27 09:13:23.896  3531  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:13:23.901  3531  4439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:13:23.901  3531  4439 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:13:23.901  3531  4439 D BatteryService: stay LED for fully charged
,07-27 09:13:23.901  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:13:23.906  3531  3531 I MotionRecognitionService: Plugged
07-27 09:13:23.906  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:13:23.906  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:13:23.906  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:13:23.916  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:13:23.916  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:13:23.916  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:13:23.936  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:23.936 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:13:23.941 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:13:23.951  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:13:23.951  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:28.021  3531  4400 V AlarmManager: Expired Alarm result :4
07-27 09:13:28.041  3531  4546 V AlarmManager:  remove PendingIntent] PendingIntent{a070be0: PendingIntentRecord{8ef533a com.google.android.gms broadcastIntent}}
,07-27 09:13:28.061  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:13:28.061  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:13:28.061  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-27 09:13:28.061  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-27 09:13:28.101  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 264 (W:30), CUR = -2, LCD = 0
,07-27 09:13:30.796  3531  4968 E Watchdog: !@Sync 42 [07-27 09:13:30.798]
,07-27 09:13:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:13:33.636  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:13:33.636  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:13:38.061  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-27 09:13:38.066  3531  4444 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-27 09:13:38.146  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 264 (W:30), CUR = -2, LCD = 0
,07-27 09:13:43.146  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-27 09:13:43.146  2916  4366 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-27 09:13:48.181  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 264 (W:30), CUR = -2, LCD = 0
,07-27 09:13:53.986  3531  4546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:13:53.986  3531  4546 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:13:53.986  3531  4546 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:13:53.986  3531  4546 D BatteryService: stay LED for fully charged
07-27 09:13:53.986  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:13:53.991  3531  3531 I MotionRecognitionService: Plugged
07-27 09:13:53.991  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:13:53.991  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:13:53.991  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:13:53.996  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:13:53.996  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:13:53.996  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:13:54.011 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:13:54.016 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:13:54.026  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:13:54.026  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:13:54.026  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:13:58.236  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 265 (W:30), LCD = 0
,07-27 09:13:59.996  3531  4400 V AlarmManager: Expired Alarm result :8,
,07-27 09:14:00.801  3531  4968 E Watchdog: !@Sync 43 [07-27 09:14:00.805]
,07-27 09:14:08.291  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 265 (W:30), LCD = 0
,07-27 09:14:18.336  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 265 (W:30), LCD = 0
,07-27 09:14:24.081  3531  5110 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:14:24.081  3531  5110 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:14:24.081  3531  5110 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:14:24.081  3531  5110 D BatteryService: stay LED for fully charged
,07-27 09:14:24.081  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:14:24.086  3531  3531 I MotionRecognitionService: Plugged
07-27 09:14:24.086  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:14:24.091  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:14:24.091  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:14:24.101  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:14:24.101  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:14:24.101  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:14:24.106  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:14:24.111 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-27 09:14:24.111 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:14:24.121  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:14:24.121  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:14:26.216  5618  6527 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:14:28.366  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 266 (W:30), LCD = 0
,07-27 09:14:30.806  3531  4968 E Watchdog: !@Sync 44 [07-27 09:14:30.809]
,07-27 09:14:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:14:33.756  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:14:33.756  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:14:33.831  5003  5057 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 61ms lastUpdatedAfter : 151644ms
,07-27 09:14:38.421  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 266 (W:30), LCD = 0
,07-27 09:14:48.456  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 266 (W:30), LCD = 0
,07-27 09:14:54.171  3531  5261 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:14:54.171  3531  5261 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:14:54.171  3531  5261 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:14:54.171  3531  5261 D BatteryService: stay LED for fully charged
07-27 09:14:54.176  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:14:54.181  3531  3531 I MotionRecognitionService: Plugged
07-27 09:14:54.181  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:14:54.181  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:14:54.181  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:14:54.186  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:14:54.186  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:14:54.186  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:14:54.196  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:14:54.201 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:14:54.201 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:14:54.216  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:14:54.216  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:14:58.501  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 267 (W:30), LCD = 0
,07-27 09:15:00.811  3531  4968 E Watchdog: !@Sync 45 [07-27 09:15:00.813]
,07-27 09:15:08.556  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 267 (W:30), LCD = 0
,07-27 09:15:18.611  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 267 (W:30), LCD = 0
,07-27 09:15:24.256  3531  5686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:15:24.256  3531  5686 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:15:24.256  3531  5686 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:15:24.256  3531  5686 D BatteryService: stay LED for fully charged
,07-27 09:15:24.256  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:15:24.266  3531  3531 I MotionRecognitionService: Plugged
07-27 09:15:24.266  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:15:24.266  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:15:24.266  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:15:24.276  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:15:24.276  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:15:24.276  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:15:24.286 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:15:24.286 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:15:24.296  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:15:24.296  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:15:24.296  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:28.651  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 268 (W:30), LCD = 0
,07-27 09:15:30.816  3531  4968 E Watchdog: !@Sync 46 [07-27 09:15:30.817]
,07-27 09:15:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:15:33.941  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:15:33.941  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:15:38.706  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 268 (W:30), LCD = 0
,07-27 09:15:48.751  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 268 (W:30), LCD = 0
,07-27 09:15:54.356  3531  3556 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:15:54.356  3531  3556 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:15:54.356  3531  3556 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:15:54.356  3531  3556 D BatteryService: stay LED for fully charged
,07-27 09:15:54.356  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:15:54.361  3531  3531 I MotionRecognitionService: Plugged
07-27 09:15:54.366  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:15:54.366  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:15:54.366  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:15:54.371  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:15:54.371  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:15:54.371  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:15:54.391 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:15:54.396 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:15:54.396  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:15:54.396  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:15:54.396  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:15:58.786  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 269 (W:30), LCD = 0
,07-27 09:16:00.821  3531  4968 E Watchdog: !@Sync 47 [07-27 09:16:00.823]
,07-27 09:16:08.841  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 269 (W:30), LCD = 0
,07-27 09:16:18.881  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 269 (W:30), LCD = 0
,07-27 09:16:24.451  3531  5112 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:16:28.941  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:16:30.826  3531  4968 E Watchdog: !@Sync 48 [07-27 09:16:30.827]
,07-27 09:16:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:16:34.066  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:16:34.066  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:16:38.981  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:16:49.031  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:16:54.546  3531  3556 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:16:54.546  3531  3556 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:16:54.546  3531  3556 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:16:54.546  3531  3556 D BatteryService: stay LED for fully charged
,07-27 09:16:54.551  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:16:54.556  3531  3531 I MotionRecognitionService: Plugged
07-27 09:16:54.556  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:16:54.556  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:16:54.556  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:16:54.561  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:16:54.561  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:16:54.561  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:16:54.591 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:16:54.591  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:16:54.591  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:16:54.591  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:16:54.591 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:16:59.071  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:16:59.996  3531  4400 V AlarmManager: Expired Alarm result :8
07-27 09:16:59.996  3531  4400 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=1485172 batch.start=1842397
,07-27 09:17:00.021  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 09:17:00.021  4515  4515 I PERF    : received broadcast android.intent.action.TIME_TICK
07-27 09:17:00.021  4515  4515 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 09:17:00.056  4515  4515 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-27 09:17:00.061  4515  4515 D SecKeyguardClockView: HomeTimezone(): 1
,07-27 09:17:00.071  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.071  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.076  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.076  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.076  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.076  4515  4515 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.081  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.156  4515  4515 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-27 09:17:00.831  3531  4968 E Watchdog: !@Sync 49 [07-27 09:17:00.834]
,07-27 09:17:09.121  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:17:19.181  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:17:24.641  3531  4879 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:17:24.646  3531  4879 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:17:24.646  3531  4879 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:17:24.646  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:17:24.646  3531  4879 D BatteryService: stay LED for fully charged
,07-27 09:17:24.656  3531  3531 I MotionRecognitionService: Plugged
07-27 09:17:24.656  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:17:24.656  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:17:24.656  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:17:24.666  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 09:17:24.666  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:17:24.666  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:17:24.691 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:17:24.691 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:17:24.696  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:17:24.696  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:17:24.696  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:17:27.211  3531  4390 D TimaService: TIMA: TimaService scheduler is intialized. 
07-27 09:17:27.216  3531  4390 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-27 09:17:27.216  3531  4389 D TimaService: TimaServiceHandler.handleMessage what =1
,07-27 09:17:29.221  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:17:30.836  3531  4968 E Watchdog: !@Sync 50 [07-27 09:17:30.839]
,07-27 09:17:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:17:33.641  3531  5698 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-27 09:17:33.646  3531  5698 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-27 09:17:33.646  3531  5698 V MARsPolicyManager: updateSMDBValues
07-27 09:17:33.646  3531  3800 E MARsDBManager: updateDBAll : begin --size 1
,07-27 09:17:33.706  3531  3800 E MARsDBManager: updateDBAll : end
,07-27 09:17:33.706  3531  3800 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-27 09:17:34.081  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 09:17:34.081  3531  4390 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-27 09:17:34.096  3531  4390 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 09:17:34.096  3531  4390 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-27 09:17:34.181  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:17:34.181  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:17:34.271  5003  5057 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 77ms lastUpdatedAfter : 180438ms
,07-27 09:17:39.256  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:17:49.316  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:17:54.741  3531  5115 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:17:54.746  3531  5115 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:17:54.746  3531  5115 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:17:54.746  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:17:54.746  3531  5115 D BatteryService: stay LED for fully charged
,07-27 09:17:54.751  3531  3531 I MotionRecognitionService: Plugged
07-27 09:17:54.751  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:17:54.751  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:17:54.751  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:17:54.761  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:17:54.761  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:17:54.761  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:17:54.776 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:17:54.776 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:17:54.786  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:17:54.791  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:17:54.791  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:17:59.351  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:17:59.996  3531  4400 V AlarmManager: Expired Alarm result :8
,07-27 09:18:00.836  3531  4968 E Watchdog: !@Sync 51 [07-27 09:18:00.840]
,07-27 09:18:09.396  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:18:19.451  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:18:24.836  3531  5686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:18:24.836  3531  5686 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:18:24.836  3531  5686 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:18:24.841  3531  5686 D BatteryService: stay LED for fully charged
,07-27 09:18:24.841  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-27 09:18:24.851  3531  3531 I MotionRecognitionService: Plugged
07-27 09:18:24.851  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:18:24.851  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:18:24.851  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:18:24.861  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:18:24.861  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:18:24.861  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:18:24.866  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:24.871 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:18:24.871 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:18:24.881  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:18:24.881  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:29.496  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:18:30.841  3531  4968 E Watchdog: !@Sync 52 [07-27 09:18:30.843]
,07-27 09:18:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:18:34.386  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:18:34.386  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:18:39.536  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:18:49.591  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:18:54.931  3531  3557 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:18:54.936  3531  3557 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:18:54.936  3531  3557 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:18:54.936  3531  3557 D BatteryService: stay LED for fully charged
,07-27 09:18:54.936  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:18:54.941  3531  3531 I MotionRecognitionService: Plugged
07-27 09:18:54.941  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:18:54.941  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:18:54.941  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:18:54.946  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:18:54.946  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:18:54.951  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:18:54.976  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:18:54.976  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:18:54.976  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:18:54.976 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:18:54.976 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:18:59.636  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:19:00.846  3531  4968 E Watchdog: !@Sync 53 [07-27 09:19:00.846]
,07-27 09:19:09.681  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:19:19.741  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:19:25.026  3531  5112 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:19:25.031  3531  5112 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:19:25.031  3531  5112 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:19:25.031  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:19:25.031  3531  5112 D BatteryService: stay LED for fully charged
,07-27 09:19:25.036  3531  3531 I MotionRecognitionService: Plugged
07-27 09:19:25.036  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:19:25.036  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:19:25.036  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:19:25.041  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:19:25.041  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:19:25.046  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:19:25.066 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:19:25.066 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:19:25.071  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:19:25.071  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:19:25.071  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:19:29.766  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:19:30.851  3531  4968 E Watchdog: !@Sync 54 [07-27 09:19:30.853]
,07-27 09:19:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:19:34.526  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:19:34.526  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:19:39.816  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:19:49.866  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:19:55.126  3531  5679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:19:55.126  3531  5679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:19:55.126  3531  5679 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:19:55.126  3531  5679 D BatteryService: stay LED for fully charged
,07-27 09:19:55.126  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
07-27 09:19:55.131  3531  3531 I MotionRecognitionService: Plugged
07-27 09:19:55.131  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:19:55.131  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:19:55.131  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:19:55.141  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:19:55.141  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-27 09:19:55.141  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:19:55.166 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 09:19:55.166 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:19:55.171  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:19:55.171  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:19:55.171  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:19:59.896  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:20:00.856  3531  4968 E Watchdog: !@Sync 55 [07-27 09:20:00.857]
,07-27 09:20:09.956  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:20:20.016  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:20:25.221  3531  5261 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 09:20:25.221  3531  5261 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-27 09:20:25.221  3531  5261 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-27 09:20:25.221  3531  5261 D BatteryService: stay LED for fully charged
,07-27 09:20:25.221  3531  3531 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 09:20:25.231  3531  3531 I MotionRecognitionService: Plugged
07-27 09:20:25.231  3531  3531 D MotionRecognitionService:   cableConnection= 1
07-27 09:20:25.231  3531  3531 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-27 09:20:25.231  3531  3531 D MotionRecognitionService: skip setTransmitPower. 
,07-27 09:20:25.236  4515  4515 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:20:25.236  4515  4515 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-27 09:20:25.236  4515  4515 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 09:20:25.266  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:20:25.266  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 09:20:25.266  4515  4515 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 09:20:25.266 10696 10696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-27 09:20:25.266 10696 10846 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 09:20:30.056  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:20:30.861  3531  4968 E Watchdog: !@Sync 56 [07-27 09:20:30.864]
,07-27 09:20:30.951  2936  5095 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-27 09:20:34.646  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-27 09:20:34.646  5003  5057 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-27 09:20:34.711  5003  5057 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 0Kb duration : 53ms lastUpdatedAfter : 180441ms
,07-27 09:20:40.101  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:20:50.156  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:20:55.316  3531  5021 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 09:21:00.216  3531  6657 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-27 09:21:00.871  3531  4968 E Watchdog: !@Sync 57 [07-27 09:21:00.873]
,TIME-OUT KILL (timeout was 1400000ms)
```
