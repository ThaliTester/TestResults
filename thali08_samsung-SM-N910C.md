#### Test 72145431744cc2c_thali08_samsung-SM-N910C Logs


```
--------- beginning of system,
07-12 11:36:54.810  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
07-12 11:36:55.610 10338 10338 I FIPS_bssl: FIPS approved mode (1) | 10338 | app_process
07-12 11:36:55.615 10338 10338 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 11:36:55.620 10338 10338 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:55.620 10338 10338 D AndroidRuntime: readGMSProperty: start
07-12 11:36:55.620 10338 10338 D AndroidRuntime: readGMSProperty: already setted!!
07-12 11:36:55.620 10338 10338 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-12 11:36:55.620 10338 10338 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-12 11:36:55.620 10338 10338 D AndroidRuntime: readGMSProperty: end
07-12 11:36:55.620 10338 10338 D AndroidRuntime: addProductProperty: start
07-12 11:36:55.645 10338 10338 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 11:36:55.675 10338 10338 I Radio-JNI: register_android_hardware_Radio DONE
07-12 11:36:55.680 10338 10338 E AffinityControl: AffinityControl: registerfunction enter
07-12 11:36:55.695 10338 10338 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 11:36:55.735  3603  5083 D GameManagerService: identifyGamePackage. com.test.thalitest
07-12 11:36:55.735  3603  5083 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
07-12 11:36:55.740  3603  5083 D ActivityManager: mDVFSHelper.acquire()
07-12 11:36:55.740  3603  5083 V WindowManager: addAppToken: AppWindowToken{808d91 token=Token{cec9bb8 ActivityRecord{bafe1b u0 com.test.thalitest/.MainActivity t102}}} to stack=1 task=102 at 0
07-12 11:36:55.755  3603  3829 D SecWifiDisplayUtil: Metadata value : none
07-12 11:36:55.755  3603  3829 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e2e5dc9 V.E...... R.....ID 0,0-0,0}
07-12 11:36:55.760  3603  3829 D ISSUE_DEBUG: InputChannelName : 47d77ef Starting com.test.thalitest
07-12 11:36:55.760 10354 10354 E Zygote  : v2
07-12 11:36:55.765 10354 10354 I libpersona: KNOX_SDCARD checking this for 10007
07-12 11:36:55.765  3603  5083 I ActivityManager: Start proc 10354:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
07-12 11:36:55.765 10354 10354 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:55.765  3603  5083 D InputDispatcher: Focused application set to: xxxx
07-12 11:36:55.765 10354 10354 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:36:55.765 10354 10354 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:55.765  3603  5083 D InputDispatcher: Focus left window: 6753
07-12 11:36:55.765 10338 10338 D AndroidRuntime: Shutting down VM
07-12 11:36:55.765  3603  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-12 11:36:55.765  3603  3756 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7bd92f2 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-12 11:36:55.770 10354 10354 E Zygote  : accessInfo : 0
07-12 11:36:55.770 10354 10354 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-12 11:36:55.770  4513  4513 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-12 11:36:55.775  2905  2905 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
07-12 11:36:55.800 10354 10354 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:55.800  3603  3829 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3603 uid:1000
07-12 11:36:55.800  3603  3829 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 11:36:55.800 10354 10354 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:55.800  3603  3829 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3603 uid:1000
07-12 11:36:55.800  3603  3829 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-12 11:36:55.800  3603  3829 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-12 11:36:55.800  3603  4439 V WindowOrientationListener: setCurrentAppOrientation :-1
07-12 11:36:55.800  3603  4439 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-12 11:36:55.805  3603  3756 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{47d77ef u0 d0 Starting com.test.thalitest}
07-12 11:36:55.805  4513  4513 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-12 11:36:55.810  3603  4439 D ActivityManager:  Launching com.test.thalitest, updated priority
07-12 11:36:55.825  3603  3603 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-12 11:36:55.825  3603  3753 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-12 11:36:55.840  2905  2987 D libEGL  : eglTerminate EGLDisplay = 0xb68c1624
07-12 11:36:55.845  2905  5250 I SurfaceFlinger: id=11 Removed VSBConnecti (7/11)
07-12 11:36:55.845  2905  2987 I SurfaceFlinger: id=11 Removed VSBConnecti (-2/11)
07-12 11:36:55.850  2905  5250 D libEGL  : eglTerminate EGLDisplay = 0xb1b04624
07-12 11:36:55.850  2905  5250 D libEGL  : eglTerminate EGLDisplay = 0xb1b04624
07-12 11:36:55.855  2905  5249 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
07-12 11:36:55.855  6753  6753 V ActivityThread: updateVisibility : ActivityRecord{761b47d token=android.os.BinderProxy@6c45836 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-12 11:36:55.855  2905  5249 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
07-12 11:36:55.860  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbef78474
07-12 11:36:55.860  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbef78474
07-12 11:36:55.865  5099  5099 V ActivityThread: updateVisibility : ActivityRecord{ca59577 token=android.os.BinderProxy@7cd1989 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-12 11:36:55.865  5099  5099 D Launcher: onTrimMemory. Level: 20
07-12 11:36:55.870  3603  3829 V WindowStateAnimator: Finishing drawing window Window{47d77ef u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-12 11:36:55.875  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbef7840c
07-12 11:36:55.890  2905  2987 I SurfaceFlinger: id=12 Removed VSBConnecti (4/9)
07-12 11:36:55.890  2905  2992 I SurfaceFlinger: id=12 Removed VSBConnecti (-2/9)
07-12 11:36:55.895  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbef78474
,07-12 11:36:56.135  3603  4439 I WindowManager: Screenshot max retries 4 of Token{cec9bb8 ActivityRecord{bafe1b u0 com.test.thalitest/.MainActivity t102}} appWin=Window{47d77ef u0 d0 Starting com.test.thalitest} drawState=4
07-12 11:36:56.175  3603  3753 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-12 11:36:56.175  3603  4444 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-12 11:36:56.195  3603  3825 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
07-12 11:36:56.195  3603  6622 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:36:56.205  3603  6622 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:36:56.240 10354 10354 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
07-12 11:36:56.275 10354 10354 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-12 11:36:56.280 10354 10354 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 3125-3128)
07-12 11:36:56.280 10354 10354 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-12 11:36:56.300 10354 10368 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
07-12 11:36:56.305 10354 10354 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ac65e45}
07-12 11:36:56.305 10354 10354 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-12 11:36:56.305 10354 10354 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 11:36:56.315 10354 10354 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-12 11:36:56.330 10354 10369 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
07-12 11:36:56.355 10354 10354 D libEGL  : eglInitialize EGLDisplay = 0xbef29e7c
07-12 11:36:56.385  3603  5114 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
07-12 11:36:56.385  3603  5114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
07-12 11:36:56.445 10354 10354 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
07-12 11:36:56.455 10354 10354 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 11:36:56.455 10354 10354 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-12 11:36:56.455 10354 10354 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
07-12 11:36:56.455 10354 10354 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
07-12 11:36:56.475 10354 10354 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
07-12 11:36:56.480 10354 10354 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-12 11:36:56.560 10354 10354 D SecWifiDisplayUtil: Metadata value : none
07-12 11:36:56.565 10354 10354 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{311acfa I.E...... R.....ID 0,0-0,0}
07-12 11:36:56.570 10354 10405 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-12 11:36:56.585  3603  5015 D ISSUE_DEBUG: InputChannelName : d7fd030 com.test.thalitest/com.test.thalitest.MainActivity
07-12 11:36:56.595  3603  5689 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-12 11:36:56.595  3603  5689 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-12 11:36:56.595  3603  3603 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-12 11:36:56.600  3603  3603 I KnoxTimeoutHandler: Shared devices show user statefalse
07-12 11:36:56.635 10354 10354 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 10354
07-12 11:36:56.640  3603  5011 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/10354 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:56.645 10354 10368 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
07-12 11:36:56.660 10354 10354 D SecWifiDisplayUtil: Metadata value : none
07-12 11:36:56.670  2905  2905 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
07-12 11:36:56.680  3603  3632 D InputDispatcher: Focus entered window: 10354
07-12 11:36:56.685  3603  3829 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3603 uid:1000
07-12 11:36:56.685  3603  3829 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 11:36:56.685  3603  3829 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3603 uid:1000
07-12 11:36:56.685  3603  3829 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-12 11:36:56.685 10354 10405 D libEGL  : eglInitialize EGLDisplay = 0x9cebf7c4
07-12 11:36:56.685 10354 10405 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 11:36:56.690 10354 10405 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
07-12 11:36:56.690 10354 10354 V ActivityThread: updateVisibility : ActivityRecord{8c11e87 token=android.os.BinderProxy@8e46325 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-12 11:36:56.695 10354 10354 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-12 11:36:56.695 10354 10354 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
07-12 11:36:56.750  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbef7840c
07-12 11:36:56.750  3603  5016 V WindowStateAnimator: Finishing drawing window Window{d7fd030 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
07-12 11:36:56.750 10354 10410 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:56.750 10354 10410 D libEGL  : eglInitialize EGLDisplay = 0x9a3ec3ec
07-12 11:36:56.755 10354 10354 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-12 11:36:56.755  3603  7152 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-12 11:36:56.760  3603  3829 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-12 11:36:56.760  3603  3603 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-12 11:36:56.760  3603  3603 I KnoxTimeoutHandler: SD activityfalse
07-12 11:36:56.765  3603  3829 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +627ms (total +1s21ms)
07-12 11:36:56.765 10354 10354 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-12 11:36:56.770  3603  3829 D ActivityManager: mDVFSHelper.release()
07-12 11:36:56.770  3603  3829 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bafe1b u0 com.test.thalitest/.MainActivity t102} time:133617
07-12 11:36:56.770  3603  3829 D ViewRootImpl: #3 mView = null
07-12 11:36:56.775  2905  5249 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
07-12 11:36:56.775  2905  5250 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
07-12 11:36:56.780  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbef78474
07-12 11:36:56.790 10354 10354 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8e46325 time:133637
07-12 11:36:56.805 10354 10354 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10354
07-12 11:36:56.975 10354 10354 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-12 11:36:57.100 10354 10418 D jxcore_app_log: JniHelper::setJavaVM(0xb4834000), pthread_self() = -1744832208
07-12 11:36:57.105 10354 10418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:57.105 10354 10418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:57.105 10354 10418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:57.105 10354 10418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:57.105 10354 10418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 11:36:57.105 10354 10418 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92d5f95 added. We now have 1 listener(s)
07-12 11:36:57.105 10354 10418 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
07-12 11:36:57.105 10354 10418 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
07-12 11:36:57.110 10354 10418 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:36:57.110 10354 10418 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:36:57.110 10354 10418 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b2838 added. We now have 1 listener(s)
07-12 11:36:57.110 10354 10418 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 11:36:57.110 10354 10418 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:57.110 10354 10418 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 11:36:57.115 10354 10418 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:57.115 10354 10418 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:57.115 10354 10418 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:57.115 10354 10418 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 11:36:57.115 10354 10418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 11:36:57.115 10354 10418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
07-12 11:36:57.115 10354 10418 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:57.115 10354 10418 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:57.120 10354 10418 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:36:57.120 10354 10418 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:36:57.120 10354 10418 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 11:36:57.145 10354 10354 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:57.500 10354 10419 W jxcore-log: Initializing JXcore engine
07-12 11:36:57.500 10354 10419 W jxcore-log: JXcore engine is ready
,07-12 11:36:57.525  5632  5632 E audit   : type=1400 msg=audit(1468316217.525:260): avc:  denied  { ioctl } for  pid=10419 comm="Thread-1011" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3097 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
07-12 11:36:57.525  5632  5632 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.525  5632  5632 E audit   : type=1300 msg=audit(1468316217.525:260): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=2 a3=973ff3c8 items=0 ppid=2956 ppcomm=main pid=10419 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1011" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-12 11:36:57.525  5632  5632 E audit   : type=1327 msg=audit(1468316217.525:260): proctitle="com.test.thalitest"
,07-12 11:36:57.530  5632  5632 E audit   : type=1320 msg=audit(1468316217.525:260): 
07-12 11:36:57.530  5632  5632 E audit   : type=1400 msg=audit(1468316217.530:261): avc:  denied  { ioctl } for  pid=10419 comm="Thread-1011" path="socket:[38927]" dev="sockfs" ino=38927 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-12 11:36:57.530  5632  5632 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-12 11:36:57.530  5632  5632 E audit   : type=1300 msg=audit(1468316217.530:261): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=2 a3=973ff3c8 items=0 ppid=2956 ppcomm=main pid=10419 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1011" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-12 11:36:57.530  5632  5632 E audit   : type=1327 msg=audit(1468316217.530:261): proctitle="com.test.thalitest"
07-12 11:36:57.530  5632  5632 E audit   : type=1320 msg=audit(1468316217.530:261): 
,07-12 11:36:57.535 10354 10419 W jxcore-log: Starting JXcore engine
,07-12 11:36:57.580  3603  5015 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:36:57.580 10354 10419 W jxcore-log: Platform android
07-12 11:36:57.580 10354 10419 W jxcore-log: 
07-12 11:36:57.580 10354 10419 W jxcore-log: Process ARCH arm
07-12 11:36:57.580 10354 10419 W jxcore-log: 
07-12 11:36:57.580  3603  5015 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:36:57.580  3603  5015 D BatteryService: online:4, current avg:126, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:-29
07-12 11:36:57.580  3603  5015 D BatteryService: stay LED for fully charged
07-12 11:36:57.580  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:36:57.585  3603  3603 I MotionRecognitionService: Plugged
07-12 11:36:57.585  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:36:57.585  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:36:57.585  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:36:57.585  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:36:57.585  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:36:57.585  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:36:57.590  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:57.605  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:36:57.605  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:57.610  4687  4687 D Recents : onTaskStackChanged
,07-12 11:36:57.675 10354 10419 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:57.675 10354 10419 I jxcore-log: 
07-12 11:36:57.675 10354 10419 W jxcore-log: JXcore engine is started
,07-12 11:36:57.680 10354 10418 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:36:57.685 10354 10354 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:36:58.750  3603  4498 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/102_task.xml.bak
,07-12 11:36:58.790  3603  4962 E Watchdog: !@Sync 4 [07-12 11:36:58.793]
,07-12 11:36:59.205  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:36:59.205  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:36:59.330  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:36:59.995  3603  4401 V AlarmManager: Expired Alarm result :8
,07-12 11:37:02.210  3603  6622 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:03.480  3603  6622 D SSRM:n  : SIOP:: AP = 320, PST = 317 (W:10), CUR = 126, LCD = 0
,07-12 11:37:03.960 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:37:03.960 10354 10419 I jxcore-log: 
,07-12 11:37:03.960 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:37:03.960 10354 10419 I jxcore-log: 
,07-12 11:37:03.965 10354 10419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:03.965 10354 10419 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:37:03.965 10354 10419 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:03.965 10354 10419 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:37:03.965 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:37:03.965 10354 10419 I jxcore-log: 
,07-12 11:37:03.965 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:37:03.965 10354 10419 I jxcore-log: 
,07-12 11:37:04.175 10354 10419 I jxcore-log: Unit Test app is loaded
07-12 11:37:04.175 10354 10419 I jxcore-log: 
,07-12 11:37:04.175 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:37:04.175 10354 10419 I jxcore-log: 
,07-12 11:37:04.180 10354 10354 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 11:37:04.180 10354 10419 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-12 11:37:04.185  3603  5689 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-12 11:37:04.185  3603  5689 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-12 11:37:04.185  3603  5689 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-12 11:37:04.190  3603  5689 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-12 11:37:04.190  3603  5689 V CAE     : start(ContextProvider.java:128)
,07-12 11:37:04.190  3603  5689 V CAE     : clear(ActivityTrackerRunner.java:108)
07-12 11:37:04.190  3603  5689 V CAE     : enable(ActivityTrackerRunner.java:84)
07-12 11:37:04.190  3603  5689 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 9, 37, 4,
07-12 11:37:04.190  3603  5689 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 9, 37, 4
,07-12 11:37:04.190  2941  3115 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 9, 37, 4
,07-12 11:37:04.205  3603  5689 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-12 11:37:04.205  3603  5689 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-12 11:37:04.215  3603  5689 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-12 11:37:04.215  3603  5689 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-12 11:37:04.215  3603  5689 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-12 11:37:04.215  3603  5689 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@ba5a792, Service : ACTIVITY_TRACKER(1)
,07-12 11:37:04.215  3603  5689 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-12 11:37:04.215  3603  5689 D SContextService: 	.registerCallback : 1, client=
07-12 11:37:04.215  3603  5689 D SContextService: ===== SContext Service List =====
07-12 11:37:04.215  3603  5689 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@fffa560, Service : Activity Tracker
07-12 11:37:04.215  3603  5689 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@b830563, service=Activity Tracker
07-12 11:37:04.215  3603  5689 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,07-12 11:37:04.215  3603  5689 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
07-12 11:37:04.215  3603  5689 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
07-12 11:37:04.215  3603  5689 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-12 11:37:04.215  3603  5689 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
,07-12 11:37:04.215  2941  2941 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-12 11:37:04.215  3603  5689 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
07-12 11:37:04.215  3603  5689 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-12 11:37:04.230  3603  5689 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
07-12 11:37:04.230  3603  5689 D SContextService: requestToUpdate() : service = Activity Tracker
,07-12 11:37:04.230  3603  5689 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
07-12 11:37:04.230  3603  5689 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@b830563, service=Activity Tracker
07-12 11:37:04.230  3603  5689 D WifiService: setWifiEnabled: true pid=10354, uid=10007
07-12 11:37:04.230  3603  5689 W ActivityManager: Permission Denial: getCurrentUser() from pid=10354, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:37:04.230  3603  5689 W WifiService: Failed getting userId using ActivityManagerNative
07-12 11:37:04.230  3603  5689 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10354, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:37:04.230  3603  5689 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28178)
07-12 11:37:04.230  3603  5689 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2490)
07-12 11:37:04.230  3603  5689 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2478)
07-12 11:37:04.230  3603  5689 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-12 11:37:04.230  3603  5689 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-12 11:37:04.230  3603  4446 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-12 11:37:04.230  3603  5689 D SettingsProvider: isChangeAllowed() SettingsProvider : name = wifi_on
,07-12 11:37:04.230  3603  4447 D WifiStateMachine: setFccChannel: channel = 0
07-12 11:37:04.230  3603  4447 D WifiController: [FCC]setFccChannel() is called !!!
07-12 11:37:04.230  3603  3632 I WifiService: disconnect: pid=10354, uid=10007
,07-12 11:37:04.230  3603  4447 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-12 11:37:04.230  3603  4447 D SecContentProvider: insert(), uri = 2
,07-12 11:37:04.230  3603  4446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18718 com.android.server.wifi.WifiStateMachine.access$3900:292 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8636 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-12 11:37:04.235 10354 10419 D BluetoothAdapter: enable()
,07-12 11:37:04.235  3603  4446 D WifiBigDataLog: init : 
,07-12 11:37:04.235  3603  4446 E WifiHW  : ##################### set firmware type 0 #####################
,07-12 11:37:04.240  2916  4375 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-12 11:37:04.240  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3f2aade u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d83a6f 5652:com.samsung.android.providers.context/u0a11}
,07-12 11:37:04.240  3603  5112 W ActivityManager: Permission Denial: getCurrentUser() from pid=10354, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
,07-12 11:37:04.240  2916  4375 I WifiHW  : module is murata
07-12 11:37:04.240  2916  4375 E WifiHW  : ==========[WIFI] MURATA MODULE ===========
07-12 11:37:04.240  2916  4375 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_murata
,07-12 11:37:04.240  2916  4375 E WifiHW  : TEMP_FAILURE_RETRY complete
07-12 11:37:04.240  2916  4375 D SoftapController: Softap fwReload - Ok
,07-12 11:37:04.245  3603  5112 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-12 11:37:04.245  3603  5112 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10354, uid=10007 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:37:04.245  3603  5112 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28178)
07-12 11:37:04.245  3603  5112 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2843)
07-12 11:37:04.245  3603  5112 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2833)
07-12 11:37:04.245  3603  5112 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1213)
07-12 11:37:04.245  3603  5112 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:262)
07-12 11:37:04.245  3603  5112 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
07-12 11:37:04.245  3603  5112 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-12 11:37:04.250  3603  5112 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-12 11:37:04.250  3603  5112 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bluetooth_on
,07-12 11:37:04.255  2916  4375 D CommandListener: Setting iface cfg
07-12 11:37:04.255  2916  4375 D CommandListener: Trying to bring down wlan0
,07-12 11:37:04.255  2916  4375 D CommandListener: Clearing all IP addresses on wlan0
,07-12 11:37:04.260  3603  4446 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 11:37:04.265 10354 10419 I jxcore-log: My device name is: samsung-SM-N910C
07-12 11:37:04.265 10354 10419 I jxcore-log: 
,07-12 11:37:04.275 10423 10423 E Zygote  : v2
07-12 11:37:04.275 10423 10423 I libpersona: KNOX_SDCARD checking this for 1002
07-12 11:37:04.275 10423 10423 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:04.275 10423 10423 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:04.275 10423 10423 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:04.275 10423 10423 E Zygote  : accessInfo : 0
,07-12 11:37:04.275  3603  3828 I ActivityManager: Start proc 10423:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 11:37:04.295 10423 10423 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:04.295 10423 10423 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:04.305  2941  3111 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 2, 16, 84, 2, 0, 0
,07-12 11:37:04.305  3603  4405 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 2, 16, 84, 2, 0, 0
,07-12 11:37:04.310  3603  4404 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 9, 37, 4,
07-12 11:37:04.310  3603  4404 D SensorHubManager: SendSensorHubData: send data = -63, 14, 9, 37, 4
,07-12 11:37:04.310  2941  3115 D Sensorhubs: sendContextData: -63, 14, 9, 37, 4
,07-12 11:37:04.310  3603  4404 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_SLEEP
,07-12 11:37:04.315  3603  4404 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
,07-12 11:37:04.315  3603  4404 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 2, 16, 84, 2, 0, 0,
,07-12 11:37:04.315  3603  4404 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-12 11:37:04.315  3603  4404 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1468316224318]
,07-12 11:37:04.320  3603  4407 D SContextService: updateSContext() : event = Activity Tracker
,07-12 11:37:04.320  3603  3603 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-12 11:37:04.320  3603  3603 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-12 11:37:04.320  3603  3603 D WifiStateMachine: setWifiScanMove bMove = 0
07-12 11:37:04.320  3603  3603 D WifiService: setWifiScanWithSensor bMove = 0
07-12 11:37:04.320  3603  3603 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,07-12 11:37:04.350 10423 10423 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-12 11:37:04.360  3603  4446 D wifi    : Can not initialize the vendor function pointer table
07-12 11:37:04.360  3603  4446 E WifiNative-HAL: Could not start hal
07-12 11:37:04.360  3603  4446 E WifiStateMachine: Failed to start HAL
,07-12 11:37:04.365  3603  4446 E WifiHW  : supplicant_name : p2p_supplicant
,07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding GattService
,07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding HeadsetService
07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding A2dpService
07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding HidService
,07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding HealthService
07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding PanService
07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding SapService
07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-12 11:37:04.385 10423 10423 D BtSettings.ProfileConfig: Adding A2dpSinkService
,07-12 11:37:04.385 10423 10423 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-12 11:37:04.390  3603  4553 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.gatt.GattService
07-12 11:37:04.390  3603  4553 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:04.390  3603  4553 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.390  3603  4553 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.390  3603  4553 D SettingsProvider: selectionArgs: false
07-12 11:37:04.390  3603  4553 D SettingsProvider: selectionArgs: 1002
,07-12 11:37:04.390  3603  4553 D SettingsProvider: ret = -1
,07-12 11:37:04.390  3603  7152 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-12 11:37:04.390  3603  7152 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.390  3603  7152 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.390  3603  7152 D SettingsProvider: selectionArgs: false
07-12 11:37:04.390  3603  7152 D SettingsProvider: selectionArgs: 1002
,07-12 11:37:04.395  3603  7152 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-12 11:37:04.395  3603  7152 D SettingsProvider: ret = -1
,07-12 11:37:04.395  3603  5011 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-12 11:37:04.395  3603  5011 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.395  3603  5011 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.395  3603  5011 D SettingsProvider: selectionArgs: false
07-12 11:37:04.395  3603  5011 D SettingsProvider: selectionArgs: 1002
07-12 11:37:04.395  3603  5011 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-12 11:37:04.395  3603  5011 D SettingsProvider: ret = -1
,07-12 11:37:04.395  3603  5084 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hid.HidService
07-12 11:37:04.395  3603  5084 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.395  3603  5084 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.395  3603  5084 D SettingsProvider: selectionArgs: false
07-12 11:37:04.395  3603  5084 D SettingsProvider: selectionArgs: 1002
,07-12 11:37:04.395  3603  5084 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:04.395  3603  5084 D SettingsProvider: ret = -1
07-12 11:37:04.395  3603  5114 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-12 11:37:04.395  3603  5114 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-12 11:37:04.395  3603  5114 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:04.395  3603  5114 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.395  3603  5114 D SettingsProvider: selectionArgs: false
07-12 11:37:04.395  3603  5114 D SettingsProvider: selectionArgs: 1002
07-12 11:37:04.400  3603  5114 D SettingsProvider: ret = -1
,07-12 11:37:04.400  3603  4709 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.pan.PanService
07-12 11:37:04.400  3603  4709 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-12 11:37:04.400  3603  4709 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.400  3603  4709 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-12 11:37:04.400  3603  4709 D SettingsProvider: selectionArgs: false
07-12 11:37:04.400  3603  4709 D SettingsProvider: selectionArgs: 1002
07-12 11:37:04.400  3603  4709 D SettingsProvider: ret = -1
,07-12 11:37:04.400  3603  5015 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-12 11:37:04.400  3603  5015 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:04.400  3603  5015 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-12 11:37:04.400  3603  5689 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:04.400  3603  5015 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.400  3603  3632 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-12 11:37:04.400  3603  5015 D SettingsProvider: selectionArgs: false
07-12 11:37:04.400  3603  5015 D SettingsProvider: selectionArgs: 1002
07-12 11:37:04.405  3603  3631 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:04.400  3603  5015 D SettingsProvider: ret = -1
07-12 11:37:04.400  3603  5689 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.sap.SapService
07-12 11:37:04.400  3603  5689 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.400  3603  5689 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.400  3603  5689 D SettingsProvider: selectionArgs: false
07-12 11:37:04.400  3603  5689 D SettingsProvider: selectionArgs: 1002
07-12 11:37:04.400  3603  5689 D SettingsProvider: ret = -1
07-12 11:37:04.400  3603  3632 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:04.400  3603  3632 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.400  3603  3632 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.400  3603  3632 D SettingsProvider: selectionArgs: false
07-12 11:37:04.400  3603  3632 D SettingsProvider: selectionArgs: 1002
07-12 11:37:04.400  3603  3632 D SettingsProvider: ret = -1
07-12 11:37:04.405  3603  3631 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService,
07-12 11:37:04.405  3603  3631 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:04.405  3603  3631 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:04.405  3603  3631 D SettingsProvider: selectionArgs: false
07-12 11:37:04.405  3603  3631 D SettingsProvider: selectionArgs: 1002
07-12 11:37:04.405  3603  3631 D SettingsProvider: ret = -1
,07-12 11:37:04.440 10423 10423 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 11:37:04.440 10423 10439 I BluetoothAdapterState: Entering OffState
,07-12 11:37:04.445 10423 10423 I bt_bluedroid: init
,07-12 11:37:04.455 10423 10440 E bt_core_counter: counter_init unable to open counter port
07-12 11:37:04.455 10423 10440 E bt_core_module: module_init failed to initialize "counter_module"
,07-12 11:37:04.455 10423 10440 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 11:37:04.455 10423 10440 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 11:37:04.455 10423 10440 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 11:37:04.455 10423 10440 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 11:37:04.465 10423 10423 I bt_bluedroid: get_profile_interface socket
07-12 11:37:04.465 10423 10423 W bt_btif : btif_get_adapter_property 2
07-12 11:37:04.465 10423 10423 W bt_btif : btif_get_adapter_property 1
,07-12 11:37:04.465  3603  4446 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 11:37:04.470  3603  3603 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:37:04.470  3603  3603 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:04.470  3603  4451 I WifiHs20Service: Message received 5011
,07-12 11:37:04.470  3603  3603 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-12 11:37:04.475  3603  4454 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:04.475 10423 10423 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
07-12 11:37:04.475  5085  5444 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-12 11:37:04.475  4513  4513 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:04.475  4513  4513 D STATUSBAR-WifiTile: Wifi onReceive(2)
,07-12 11:37:04.475  4513  4513 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=2
07-12 11:37:04.475 10423 10443 D BluetoothAdapterProperties: Address is:E0:DB:10:14:E2:C0
,07-12 11:37:04.475 10423 10443 E BluetoothServiceJni: populateRssiValuesNative
,07-12 11:37:04.475  4513  6385 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-12 11:37:04.475 10423 10443 I bt_bluedroid: getModelRssiValues
07-12 11:37:04.475 10423 10443 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-12 11:37:04.475 10423 10443 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,07-12 11:37:04.475  5085  5444 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-12 11:37:04.475  4513  4513 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:37:04.475  3603  4454 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
07-12 11:37:04.475  4513  4513 D HotspotTile: onReceive : 2, 0
,07-12 11:37:04.480 10354 10354 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:37:04.480  4513  4513 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-12 11:37:04.485 10423 10423 I bt_bluedroid: get_profile_interface sdp
,07-12 11:37:04.485  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e337b6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97c5cb7 10354:com.test.thalitest/u0a7}
,07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:04.490 10423 10443 D BluetoothAdapterProperties: Name is: Note4-1
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  3603 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bluetooth_name
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.490  3603  4709 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:04.500 10435 10435 I FIPS_bssl: FIPS approved mode (1) | 10435 | /system/bin/wpa_supplicant
,07-12 11:37:04.500 10423 10434 I bt_bluedroid: config_hci_snoop_log
,07-12 11:37:04.505  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e337b6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db78b37 7238:tv.peel.smartremote/u0a186}
,07-12 11:37:04.530 10444 10444 E Zygote  : v2
07-12 11:37:04.530 10444 10444 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:04.530 10444 10444 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:04.530 10444 10444 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:04.530 10444 10444 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:04.530 10444 10444 E Zygote  : accessInfo : 0
,07-12 11:37:04.530  3603  3828 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
07-12 11:37:04.530  3603  3753 I ActivityManager: Start proc 10444:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,07-12 11:37:04.540 10435 10435 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-12 11:37:04.540 10435 10435 I wpa_supplicant: Successfully initialized wpa_supplicant
07-12 11:37:04.540 10435 10435 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
07-12 11:37:04.540 10435 10435 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-12 11:37:04.540 10423 10439 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-12 11:37:04.540 10423 10439 D BluetoothAdapterProperties: Setting state to 14
07-12 11:37:04.540 10423 10439 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-12 11:37:04.540 10423 10439 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:37:04.540 10423 10439 D BluetoothAdapterService: updateAdapterState state is 14
,07-12 11:37:04.545  3603  3828 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
,07-12 11:37:04.545 10423 10439 D BluetoothAdapterService: Autoconnection is available 
07-12 11:37:04.545 10423 10439 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,07-12 11:37:04.545 10423 10439 D BluetoothSecureManager: getInstant: null
,07-12 11:37:04.545 10423 10439 D BluetoothSecureManager: calling getMethod for getService
07-12 11:37:04.550 10423 10439 D BluetoothSecureManager: calling getService
,07-12 11:37:04.550 10423 10439 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@96640a7
,07-12 11:37:04.550  3603  5105 D BluetoothSecureManagerService: isSecureModeEnabled
,07-12 11:37:04.550  3603  5105 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-12 11:37:04.550 10423 10439 D BtConfig.SecureMode: isSecureModeOn:false
07-12 11:37:04.550 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-12 11:37:04.555 10444 10444 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:04.555 10444 10444 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:04.555 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-12 11:37:04.555 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-12 11:37:04.555 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-12 11:37:04.555 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-12 11:37:04.555 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-12 11:37:04.555 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-12 11:37:04.555 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-12 11:37:04.555 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-12 11:37:04.555 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-12 11:37:04.555 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-12 11:37:04.555 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService,
07-12 11:37:04.555 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-12 11:37:04.565  3603  4709 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e337b6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b774745 10444:com.samsung.android.securitylogagent/1000}
07-12 11:37:04.560 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-12 11:37:04.560 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
07-12 11:37:04.560 10423 10439 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
07-12 11:37:04.560 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:04.560 10423 10439 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:04.560 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:04.560 10423 10439 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:04.560 10423 10439 D BluetoothBondStateMachine: make
,07-12 11:37:04.565 10423 10461 I BluetoothBondStateMachine: StableState(): Entering Off State
07-12 11:37:04.565 10435 10435 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-12 11:37:04.570  2994  2994 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10435
07-12 11:37:04.570  2994  2994 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-12 11:37:04.570 10435 10435 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-12 11:37:04.570 10435 10435 I wpa_supplicant: ssSupport state is = 1
07-12 11:37:04.570 10435 10435 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-12 11:37:04.570 10435 10435 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-12 11:37:04.570  2994  2994 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10435
07-12 11:37:04.570  2994  2994 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-12 11:37:04.570 10423 10439 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:37:04.575  4513  4513 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No network connection wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-12 11:37:04.575  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:04.575  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:04.575  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:04.575  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:04.575 10423 10423 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,07-12 11:37:04.580 10444 10444 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm
07-12 11:37:04.580 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,07-12 11:37:04.580 10423 10423 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 11:37:04.585 10423 10423 D BtGatt.GattService: Received start request. Starting profile...
07-12 11:37:04.585 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
07-12 11:37:04.585 10423 10423 D BtGatt.GattService: start()
07-12 11:37:04.585 10423 10423 I bt_bluedroid: get_profile_interface gatt
,07-12 11:37:04.585 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
07-12 11:37:04.585 10423 10423 D BtGatt.AdvertiseManager: advertise manager created
07-12 11:37:04.585 10423 10423 D BtGatt.AdvertiseManager: start
,07-12 11:37:04.585  3603  5011 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:04.585 10444 10444 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-12 11:37:04.585 10444 10444 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:37:04.585 10444 10444 D SecurityLogAgent: StateMachine : Current State = 1
,07-12 11:37:04.590 10444 10444 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-12 11:37:04.600 10464 10464 E Zygote  : v2
07-12 11:37:04.600 10464 10464 I libpersona: KNOX_SDCARD checking this for 10127
07-12 11:37:04.600 10464 10464 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:04.600 10464 10464 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:04.600 10464 10464 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:04.600 10464 10464 E Zygote  : accessInfo : 0
07-12 11:37:04.600 10464 10464 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.keyguardwallpaperupdator 
07-12 11:37:04.600  3603  5084 I ActivityManager: Start proc 10464:com.samsung.android.keyguardwallpaperupdator/u0a127 for broadcast-5 com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver
,07-12 11:37:04.605  3603  5084 I ActivityManager: Killing 9329:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 15): DHA:empty #31
,07-12 11:37:04.610 10423 10423 D BtGatt.ScanManager: start
,07-12 11:37:04.610 10423 10423 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,07-12 11:37:04.625 10464 10464 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:04.625 10464 10464 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:04.630  3603  3632 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e337b6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e86fa66 10464:com.samsung.android.keyguardwallpaperupdator/u0a127}
,07-12 11:37:04.640 10423 10423 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,07-12 11:37:04.640 10464 10464 W System  : ClassLoader referenced unknown path: /system/priv-app/KeyguardWallpaperUpdator/lib/arm
07-12 11:37:04.640 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
,07-12 11:37:04.640 10423 10423 E BtGatt.GattService: notifyProfileServiceStateChanged
07-12 11:37:04.640 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:04.640 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
07-12 11:37:04.645 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:04.645 10423 10423 V BluetoothAdapterState: isTurningOn()=false
07-12 11:37:04.645 10423 10423 V BluetoothAdapterState: isBleTurningOn()=true
07-12 11:37:04.645 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:04.645 10423 10439 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-12 11:37:04.645 10423 10439 I bt_bluedroid: enable
07-12 11:37:04.645 10423 10440 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 11:37:04.645 10423 10440 I bt_hci  : start_up
,07-12 11:37:04.650 10464 10464 D KeyguardWallpaperUpdator: cancelUpdateWallpaper
,07-12 11:37:04.650 10423 10440 I bt_vendor: alloc value 0xb340ca11
07-12 11:37:04.650 10423 10440 I bt_vendor: init
07-12 11:37:04.650 10423 10440 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 11:37:04.650 10423 10440 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-12 11:37:04.650 10423 10440 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-12 11:37:04.655 10423 10440 I bt_upio : upio_set_bluetooth_power(on: 1)
,07-12 11:37:04.655  3603  3632 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,07-12 11:37:04.660  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{666f143: PendingIntentRecord{42953c0 com.samsung.android.keyguardwallpaperupdator broadcastIntent}}
,07-12 11:37:04.665 10490 10490 E Zygote  : v2
07-12 11:37:04.665 10490 10490 I libpersona: KNOX_SDCARD checking this for 10022
07-12 11:37:04.665 10490 10490 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:04.670 10490 10490 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:04.670 10490 10490 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:04.670 10490 10490 E Zygote  : accessInfo : 0
07-12 11:37:04.670 10490 10490 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.locationwidget 
,07-12 11:37:04.670  3603  4553 I ActivityManager: Start proc 10490:com.sec.android.widgetapp.locationwidget/u0a22 for broadcast-5 com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider
,07-12 11:37:04.670  3603  4553 I ActivityManager: Killing 9452:com.google.android.gms:car/u0a14 (adj 15): DHA:empty #31
,07-12 11:37:04.685 10490 10490 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:04.685 10490 10490 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:04.690  3603  4709 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e337b6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d58f9 10490:com.sec.android.widgetapp.locationwidget/u0a22}
,07-12 11:37:04.700 10490 10490 W System  : ClassLoader referenced unknown path: /system/priv-app/LocationWidget_M/lib/arm
,07-12 11:37:04.705 10490 10490 I LocationWidgetApplication: onCreate() : start
,07-12 11:37:04.705 10490 10490 D LocationWidgetApplication: countryCode = POLAND
,07-12 11:37:04.720 10503 10503 E Zygote  : v2
07-12 11:37:04.720 10503 10503 I libpersona: KNOX_SDCARD checking this for 10160
07-12 11:37:04.720 10503 10503 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:04.720 10503 10503 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:04.720 10503 10503 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:04.725 10503 10503 E Zygote  : accessInfo : 0
,07-12 11:37:04.725 10503 10503 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.snote:sync 
,07-12 11:37:04.725  3603  5112 I ActivityManager: Start proc 10503:com.samsung.android.snote:sync/u0a160 for broadcast-5 com.samsung.android.snote/.control.core.sync.scloud.ReceiverWifiStateChanged
,07-12 11:37:04.725  3603  5112 I ActivityManager: Killing 9809:com.google.android.partnersetup/u0a17 (adj 15): DHA:empty #31
,07-12 11:37:04.740 10503 10503 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:04.740 10503 10503 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:04.740  3603  7152 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,07-12 11:37:04.750  3603  5016 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5e337b6 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d18bb5 10503:com.samsung.android.snote:sync/u0a160}
,07-12 11:37:04.760 10423 10440 D bt_hci  : start_up starting async portion
07-12 11:37:04.760 10423 10489 I bt_hci  : event_finish_startup
07-12 11:37:04.760 10423 10489 I bt_hci_h4: hal_open
07-12 11:37:04.760 10423 10489 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC3
,07-12 11:37:04.760 10423 10489 I bt_userial_vendor: userial_vendor_open():UART is setup
07-12 11:37:04.760 10423 10489 I bt_userial_vendor: device fd = 60 open
,07-12 11:37:04.760 10423 10489 E bt_hwcfg: Start CFG HW, HCI reset
,07-12 11:37:04.765 10503 10503 W System  : ClassLoader referenced unknown path: /system/app/SNote5.0Preload/lib/arm
,07-12 11:37:04.770 10423 10489 E bt_hwcfg: Read Local Name after HCI reset
,07-12 11:37:04.770  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{2c7d24a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:04.770  3603  4709 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,07-12 11:37:04.775  2994  2994 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-12 11:37:04.775 10503 10503 D SNoteApp: process name: com.samsung.android.snote:sync
,07-12 11:37:04.780  3603  5016 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:04.780 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,07-12 11:37:04.785  3603  4553 I ActivityManager: Killing 9824:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): DHA:empty #31
,07-12 11:37:04.790 10423 10489 D bt_hwcfg: Chipset BCM43569A1
07-12 11:37:04.790 10423 10489 D bt_hwcfg: Target name = [BCM4358A1]
,07-12 11:37:04.790 10423 10489 I bt_hwcfg: module_type[murata].
,07-12 11:37:04.790 10423 10489 I bt_hwcfg: module_type[murata] is invalid.
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG . BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG .. BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG bcm4358A0_V0033.0000.hcd BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG companion_default_coef.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG companion_default_lsc.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG companion_fw_imx240_evt1.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG companion_imx240_master_setfile.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG companion_imx240_mode_setfile.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx240.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG fimc_is_ois_63A.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG fimc_is_ois_63B.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG hevc_fw.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG sec_s3fwrn5_firmware.bin BCM4358A1
,07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG setfile_6d1.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG setfile_imx240.bin BCM4358A1
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG BCM4358A1_V0054.0094_wisol.hcd BCM4358A1
07-12 11:37:04.795 10423 10489 I bt_hwcfg: patch(org) : BCM4358A1_V0054.0094_wisol.hcd
07-12 11:37:04.795 10423 10489 E bt_hwcfg: Module type exists. Skip
07-12 11:37:04.795 10423 10489 E bt_hwcfg: patchram path ORG BCM4358A1_V0054.0094.hcd BCM4358A1
07-12 11:37:04.795 10423 10489 I bt_hwcfg: patch(org) : BCM4358A1_V0054.0094.hcd
07-12 11:37:04.795 10423 10489 I bt_hwcfg: Found patchfile: /vendor/firmware/BCM4358A1_V0054.0094.hcd
07-12 11:37:04.795 10423 10489 E bt_hwcfg: ORG patchram base 0054
07-12 11:37:04.795 10423 10489 E bt_hwcfg: ORG patchram minor 0094
07-12 11:37:04.795 10423 10489 E bt_hwcfg: fw ver (org)54.94
07-12 11:37:04.795 10423 10489 E bt_hwcfg: Final Patchram is /vendor/firmware/BCM4358A1_V0054.0094.hcd
,07-12 11:37:04.795 10435 10435 I wpa_supplicant: Ctrl_iface: loading system cred
,07-12 11:37:04.795 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-12 11:37:04.800 10423 10489 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-12 11:37:04.800  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{6345bb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:04.800  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{325dad8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:04.800 10423 10489 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-12 11:37:04.815 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-12 11:37:04.815  2994  2994 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10435
07-12 11:37:04.815  2994  2994 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-12 11:37:04.815 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-12 11:37:04.815 10435 10435 I wpa_supplicant: ssSupport state is = 1
07-12 11:37:04.815 10435 10435 E wpa_supplicant: SIM READ ERROR
07-12 11:37:04.815 10435 10435 E wpa_supplicant: SIM READ ERROR
07-12 11:37:04.815 10435 10435 I wpa_supplicant: Blacklist: Clear (all) 
,07-12 11:37:04.815 10435 10435 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-12 11:37:04.820 10435 10435 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:37:04.840  3603  4709 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,07-12 11:37:04.900  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{adc2e31: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.905  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{b8c916: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.955  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{8f68297: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.955  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{489cc84: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.955  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{d147c6d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.955  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{8f060a2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.960  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{b16b133: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.960  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{3192cf0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.960  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{f097269: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.960  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{e17e4ee: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.965  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{6012d8f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.965  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{5fc281c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.965  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{23dcc25: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.965  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{22161fa: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.970  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{56d13ab: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.970  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{cb1aa08: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.970  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{3a405a1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.970  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{213a3c6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.975  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{f673f87: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.975  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{dbb5eb4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.975  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{2da5add: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.980  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{2963652: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.980  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{3ee4d23: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.980  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{409b220: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.980  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{126c7d9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.980  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{93d659e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.985  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a4e987f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.985  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{727d04c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.985  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{4330895: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.985  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{e963daa: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}},
,07-12 11:37:04.990  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{83e3d9b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.990  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{a27a538: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.990  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{8889911: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.990  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{4f28a76: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.995  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{eb91877: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.995  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{d4ddce4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.995  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{fccb54d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:04.995  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{ff4d802: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.000  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{89cc513: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.000  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{e7de350: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.000  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{6bc5949: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.000  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{8dc724e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.005  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{7049f6f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.005  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{465e47c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.005  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{ee84105: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.010  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{b91655a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.010  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{765c38b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.010  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{6acc68: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.010  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{830e881: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.015  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{8707d26: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.015  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{f6b0d67: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.015  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{3544714: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.015  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{6028bbd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.020  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{6d745b2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.020  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{a911903: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.020  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{b8c080: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.020  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{c5126b9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.025  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{4700afe: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.025  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{582425f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.025  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{d2964ac: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.030  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{547575: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.030  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{d3dd90a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.030  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{332a57b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.030  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{31e1f98: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.030  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{903f3f1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.035  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{8687bd6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.035  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{7bc1e57: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.035  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{aa19d44: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.040  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{b52de2d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.040  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{5c87f62: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.040  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{4fa48f3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.040  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{fbd49b0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.045  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{e2c3029: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.045  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{8332fae: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.045  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{4e6814f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.045  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{3a550dc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.050  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{22ea5e5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.050  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{88698ba: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.050  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{db3e36b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.050  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{4a49ec8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.055  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{928bb61: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.055  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{d758686: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.055  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{bab4b47: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.060  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{8c8df74: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.060  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{954ac9d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.060  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{4138512: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.060  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{cc754e3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.065  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{74e7ee0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.065  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{8547599: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.065  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{520e05e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.065  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a105c3f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.070  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{ccca90c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.070  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{9edd255: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.070  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{316a46a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.070  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{ab87d5b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.075  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{62149f8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.075  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{e863ed1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}},
,07-12 11:37:05.075  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{cf29d36: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.075  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{cf79437: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.080  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{e1d0da4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.080  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{d5ef70d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.080  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{1c356c2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.080  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{a73cd3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.085  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{9ef6010: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.085  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{690f709: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.085  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{f41d0e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.090  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{f9ed32f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.090  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{526d3c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.090  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{8c8fac5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.090  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{358fc1a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}},
,07-12 11:37:05.095  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{fcf734b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.095  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{7772128: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.095  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{6c37e41: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.100  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{8fabfe6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.100  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{b1ff927: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.100  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{5b127d4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.100  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{888bd7d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.105  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{7a2f472: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.105  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{90900c3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.105  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{e2ed40: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.105  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{468b479: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.110  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{627e5be: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.110  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{5f0e61f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.110  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{8a99d6c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.115  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{bb71f35: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.115  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{789fca: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.115  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{447c53b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.115  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{7492458: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.120  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{74779b1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.125  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{68ee96: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.125  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{3637a17: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.130  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{5582e04: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.130  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{fa8ffed: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.135  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{73d5e22: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.135  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{81ba0b3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.135  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{c2c2670: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.140  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{d22ade9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.140  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{3f73a6e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.145  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{325950f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.145  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{305399c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.145  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{b6f3fa5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.150  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{2608f7a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.150  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{130732b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.155  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{2fa5388: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.155  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{d393121: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.160  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{ed82946: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.160  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{c11707: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.165  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{da52034: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.165  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{b56be5d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.165  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{add93d2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.170  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{9ce1ca3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.170  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{28e0ba0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.175  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{bc5e359: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.175  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{e5d1b1e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.180  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{31bdfff: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.180  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{f5841cc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.180  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{c685c15: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.185  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{1bbcb2a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.185  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{1587d1b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.190  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{6adaeb8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.190  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{d7fa491: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.195  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{ca36ff6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.195  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{bf7cff7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.200  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{9eafe64: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.200  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{7e8f8cd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.200  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{58e9582: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.205  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{3cf7493: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.205  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{18b9cd0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.210  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{b1954c9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.210  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{e1487ce: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.215  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{772c6ef: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.215  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{55b5fc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.215  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{ed97485: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.220  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{7f552da: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.220  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{14ee30b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.225  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{d4635e8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.225  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{4c1d401: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.225  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{ee5c2a6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.230  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{b86a4e7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}},
,07-12 11:37:05.230  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{3cc894: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.235  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{576af3d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.235  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{31b6332: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.240  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{58ea883: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.240  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{d67da00: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.240  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{5a40239: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.240  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{98807e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.245  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{78949df: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.245  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{b70962c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.245  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{eb988f5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.250  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{f38268a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.250  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{f62a4fb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.250  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{66e918: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.250  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{766bf71: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.255  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{77a2156: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.255  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{3ac95d7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.255  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{16d7ec4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.255  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{7d6e1ad: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.260  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{80efce2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.260  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{83ab873: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.260  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{125c330: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.265  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{5aceba9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.265  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{824052e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.265  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{7e68cf: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.270  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{8dbe25c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.270  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{3bf9965: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.270  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{26f463a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.270  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{ba2c2eb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.275  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{872c848: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.275  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{19566e1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.275  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{4fb8c06: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.280  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{668a2c7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.280  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{91020f4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.280  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{6a0901d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.280  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{1b46292: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.285  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{ec2a463: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.285  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{e885860: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.285  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{53b1119: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.290  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{bb215de: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.290  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{53123bf: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.290  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{38a9a8c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.295  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{162a5d5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.295  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{d45b1ea: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.295  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{7de3cdb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.300  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{c8cd378: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.300  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{734ca51: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.300  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{2c502b6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.300  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{379cbb7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.300  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{d77af24: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.305  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{d2aba8d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.305  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{6169442: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.305  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{5d56c53: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.310  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{e129990: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.310  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{e157289: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.310  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{6fdb28e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.310  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{e407aaf: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.315 10423 10489 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 11:37:05.315 10423 10489 I bt_hwcfg: FW Download delta = 545453
07-12 11:37:05.315 10423 10489 D bt_hwcfg: Settlement delay -- 100 ms
07-12 11:37:05.315 10423 10489 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 11:37:05.315  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{92fbebc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.315  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{6d9ae45: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.315  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{c26699a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.320  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{7a412cb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.320  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{2980aa8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.320  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{3ebe9c1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.325  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{8f18566: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.325  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{85f10a7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.325  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{fb72954: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.325  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{a8c60fd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.330  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{40091f2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.330  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{3e21043: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.330  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{f0786c0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.335  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{9c30ff9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.335  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{a81db3e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.335  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a0b6d9f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.335  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{a3e4eec: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.340  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{f1bb2b5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.340  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{c3c6d4a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.340  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{4344bb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.345  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{f376dd8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.345  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{b21c531: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.345  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{c5c1416: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.345  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{577197: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.350  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{ba18f84: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.350  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{19c836d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.350  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{2fd5ba2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.355  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{9179033: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.355  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{76a1ff0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.355  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{18ae969: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.360  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{b798fee: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}},
,07-12 11:37:05.360  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{cb0fc8f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.360  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{9e94b1c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.360  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{dfb325: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.365  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{b72bcfa: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.365  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{8cad2ab: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.365  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{5cdfd08: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.365  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{7fd5ca1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.370  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{e9faec6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.370  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{461ee87: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.370  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{7c9e1b4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.370  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{8f221dd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.375  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{357f152: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.375  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{f64ec23: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.375  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{3fd6520: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.375  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{e73fed9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.375  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{3dfd09e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.380  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{10277f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.380  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{e23b34c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.380  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{e9caf95: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.385  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{87458aa: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.385  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{a09bc9b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.385  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{87eb838: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.385  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{d65b011: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.390  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{e175576: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}},
,07-12 11:37:05.390  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{b3d8777: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.390  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{5831fe4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.390  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{ae43c4d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.395  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{e1b5302: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.395  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{a792413: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.395  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{8445650: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.400  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{9455049: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.400  2916  4368 D Netd    : Iface wlan0 link up
07-12 11:37:05.400  2916  4368 D Netd    : Iface wlan0 link up
,07-12 11:37:05.400 10435 10435 I wpa_supplicant: nl80211: Could not re-add multicast membership for vendor events: -2 (No such file or directory)
07-12 11:37:05.400  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:05.400  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:05.405  3603  3828 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
07-12 11:37:05.405  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:05.405  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
07-12 11:37:05.405  3603  3828 D Tethering: NAP Supported and not Wifi Model
,07-12 11:37:05.405  3603  3828 E Tethering: No numeric data
,07-12 11:37:05.405  3603  3828 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 11:37:05.405  3603  4443 D NtpTrustedTime: forceRefresh: no connectivity
,07-12 11:37:05.410  3603  4443 V NetworkStats: performPollLocked(flags=0x1)
,07-12 11:37:05.410  4513  4513 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-12 11:37:05.410  4513  4513 D HotspotTile: updateTetherState():false, false
,07-12 11:37:05.410  3603  4443 V NetworkStats: performPollLocked() took 3ms
,07-12 11:37:05.415  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82c9f68 u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{758c3f9 3603:system/1000}
,07-12 11:37:05.415  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{601bf81: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.415  3603  4444 D NtpTrustedTime: forceRefresh: no connectivity
07-12 11:37:05.415 10423 10489 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-12 11:37:05.420  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{5de0826: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.420  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{9693c67: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.425  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{e04a14: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.425  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{589d2bd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.425  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{51280b2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.425  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{7c33803: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.430  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{e81f380: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.430  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{a85ddb9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.430  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{aa3f5fe: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.430  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{d37515f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.435  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{9d2c7ac: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.435  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{29d9c75: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.435  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{a45740a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.435  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{2a9a47b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.440  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{47ab298: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.440  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{4388af1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.440  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{dcec6d6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.445  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{1240d57: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.445  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{b46044: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.445  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{ab9e52d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.445  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{2c87a62: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.450  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{e7227f3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.450  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{7b93cb0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.450  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{a7ca729: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.450  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{4b7daae: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.455  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{77d504f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.455  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{aed73dc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.455  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{88f8ce5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.455  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{2af3ba: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.460  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{468a26b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.460 10435 10435 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-12 11:37:05.460 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-12 11:37:05.460  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{bcbf1c8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.465  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{2311261: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.470  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{a849186: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.470  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{26cfa47: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.470  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{6926274: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.470  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{b739d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.475  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{a884012: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.475  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{f74f3e3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.475  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{bad31e0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.480  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{130ac99: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.480 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-12 11:37:05.480  2994  2994 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10435
07-12 11:37:05.480  2994  2994 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-12 11:37:05.480 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-12 11:37:05.480 10435 10435 I wpa_supplicant: ssSupport state is = 1
,07-12 11:37:05.485  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{da64b5e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.485  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{378eb3f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.485  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{3e38c0c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.490  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{9d67955: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.490 10435 10435 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-12 11:37:05.490 10435 10435 E wpa_supplicant: nl80211: Could not configure driver mode
07-12 11:37:05.490 10435 10435 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-12 11:37:05.490 10435 10435 E wpa_supplicant: p2p0: Failed to initialize driver interface
07-12 11:37:05.490 10435 10435 I wpa_supplicant: Blacklist: Clear (all) 
07-12 11:37:05.490  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{607bf6a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.490 10435 10435 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-12 11:37:05.490 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-12 11:37:05.490  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{39afc5b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.495  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{b435cf8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.495  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{1d255d1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.495  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{d5a6836: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.495  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{b030337: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.500  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{ecd50a4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.505  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{ed57e0d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.510  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{85cd1c2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.510 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-12 11:37:05.510  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{57a9bd3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.510  2994  2994 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10435
07-12 11:37:05.510  2994  2994 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-12 11:37:05.510 10435 10435 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-12 11:37:05.510 10435 10435 I wpa_supplicant: ssSupport state is = 1
07-12 11:37:05.510 10435 10435 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:37:05.510  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{8e0d310: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.510  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{668ee09: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.515  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{72a480e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.515 10435 10435 I wpa_supplicant: nl80211: Could not re-add multicast membership for vendor events: -2 (No such file or directory)
,07-12 11:37:05.515 10435 10435 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-12 11:37:05.515 10423 10489 I bt_userial_vendor: userial_change_2stopbit: opening /dev/ttySAC3
07-12 11:37:05.515 10423 10489 I bt_userial_vendor: device fd = 60 open
,07-12 11:37:05.520  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{868103c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.520  3603  4446 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
07-12 11:37:05.520  3603  4446 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
07-12 11:37:05.520  3603  4446 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-12 11:37:05.520 10435 10435 I wpa_supplicant: HOTSPOT20_ENABLE called ON
07-12 11:37:05.520 10435 10435 E wpa_supplicant: SIM READ ERROR
07-12 11:37:05.520 10435 10435 I wpa_supplicant: Blacklist: Clear (all) 
,07-12 11:37:05.520  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{3a961c5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.525  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{e46d71a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.525  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{1cfb24b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.525 10435 10435 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-12 11:37:05.525  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{ec3f428: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.530  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{cc35541: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.530  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{46b4ae6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.530 10435 10435 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,07-12 11:37:05.530  3603  4446 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-12 11:37:05.530  3603  3603 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:05.530  3603  3603 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:05.530  3603  4448 D HS20StateMachine: WIFI_STATE_ENABLED
07-12 11:37:05.530  3603  4451 I WifiHs20Service: Message received 5011
07-12 11:37:05.530  3603  3603 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-12 11:37:05.530  3603  4448 D HS20StateMachine: reloadCredentialsToSupplicant
07-12 11:37:05.530  3603  5036 W SLocation: No Active Data Connection
,07-12 11:37:05.535  3603  4454 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:05.535  4513  4513 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:05.535  4513  4513 D STATUSBAR-WifiTile: Wifi onReceive(3)
07-12 11:37:05.535  4513  4513 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=3
07-12 11:37:05.535  5085  5097 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-12 11:37:05.535  5085  5097 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-12 11:37:05.535  4513  4513 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:37:05.535  3603  4454 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
,07-12 11:37:05.535  4513  6385 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-12 11:37:05.535  4513  4513 D HotspotTile: onReceive : 3, 0
,07-12 11:37:05.535  4513  4513 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
07-12 11:37:05.540 10354 10354 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:05.540 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:37:05.540 10354 10354 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:05.540 10354 10354 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:37:05.540  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6652827 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97c5cb7 10354:com.test.thalitest/u0a7}
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.540  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{782ad4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.545  3603  4448 D HotspotDBHandler: getCredentialIds
07-12 11:37:05.550  3603  5015 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6652827 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b774745 10444:com.samsung.android.securitylogagent/1000}
07-12 11:37:05.550  3603  3632 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.550 10444 10444 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-12 11:37:05.550 10444 10444 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:37:05.550 10444 10444 D SecurityLogAgent: StateMachine : Current State = 1
07-12 11:37:05.550 10444 10444 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-12 11:37:05.550 10435 10435 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
07-12 11:37:05.550  3603  4446 D WifiConfigStore: Loading config and enabling all networks 
07-12 11:37:05.555  3603  4446 E WifiConfigStore: Failed to look-up a string: WPA_PSK_SHA256
07-12 11:37:05.560  3603  4446 I WifiConfigStore: "NG700" is a verified password AP: true
07-12 11:37:05.560  3603  4446 E WifiConfigStore: Not a HS20
07-12 11:37:05.560 10540 10540 E Zygote  : v2
07-12 11:37:05.560 10540 10540 I libpersona: KNOX_SDCARD checking this for 10211
07-12 11:37:05.560 10540 10540 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:05.560  3603  4446 D WifiConfigStore: loaded 0 passpoint configs
07-12 11:37:05.560  3603  4446 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-12 11:37:05.560 10540 10540 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:05.560 10540 10540 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:05.560  3603  4446 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 11:37:05.560 10540 10540 E Zygote  : accessInfo : 0
07-12 11:37:05.560 10540 10540 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-12 11:37:05.560  3603  4446 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
07-12 11:37:05.565  3603  4446 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-12 11:37:05.565  3603  4448 I ActivityManager: Start proc 10540:com.samsung.hs20provider/u0a211 for content provider com.samsung.hs20provider/.Hs20Provider
07-12 11:37:05.570  3603  5015 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6652827 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e86fa66 10464:com.samsung.android.keyguardwallpaperupdator/u0a127}
07-12 11:37:05.570 10464 10464 D KeyguardWallpaperUpdator: cancelUpdateWallpaper
07-12 11:37:05.575  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{42f047d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.575  3603  3603 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-12 11:37:05.575  3603  3603 D WifiHs20Service: reason: 2
07-12 11:37:05.575  3603  4451 I WifiHs20Service: Message received 5014
07-12 11:37:05.575  3603  4451 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-12 11:37:05.575  3603  4451 E WifiHs20Service: The changed config is NULL
07-12 11:37:05.575  3603  4446 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
07-12 11:37:05.575  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{1112f72: PendingIntentRecord{42953c0 com.samsung.android.keyguardwallpaperupdator broadcastIntent}}
07-12 11:37:05.575  3603  4446 D WifiNative-wlan0: callSECApiInt - ID [65]
07-12 11:37:05.580 10540 10540 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:05.580 10540 10540 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:05.580  3603  4446 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-12 11:37:05.580 10435 10435 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,07-12 11:37:05.580 10435 10435 I wpa_supplicant: resume autoscan
07-12 11:37:05.580 10435 10435 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-12 11:37:05.580 10435 10435 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-12 11:37:05.580  3603  5105 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6652827 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d58f9 10490:com.sec.android.widgetapp.locationwidget/u0a22}
07-12 11:37:05.580 10435 10435 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-12 11:37:05.580 10435 10435 I wpa_supplicant: reset timer : RESET_TIMER 0
07-12 11:37:05.580 10435 10435 I wpa_supplicant: P2P: Current p2p state = IDLE
07-12 11:37:05.580 10435 10435 I wpa_supplicant: First Scan Start
07-12 11:37:05.585 10435 10435 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-12 11:37:05.590  3603  4446 D WifiNative-wlan0: Setting external_sim to 1
07-12 11:37:05.590  3603  4446 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
07-12 11:37:05.590  3603  4446 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:37:05.590 10435 10435 I wpa_supplicant: bt_status is set be DISCONNECTED
07-12 11:37:05.595  3603  5105 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6652827 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d18bb5 10503:com.samsung.android.snote:sync/u0a160}
07-12 11:37:05.595  3603  4446 E WifiNative-wlan0: do suspend true
07-12 11:37:05.600 10540 10540 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm
07-12 11:37:05.600  3603  4445 D WifiP2pService: P2pDisabledState{ what=131203 }
07-12 11:37:05.600  3603  4446 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
07-12 11:37:05.600  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{4f21fc3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.600  2916  4375 D CommandListener: Setting iface cfg
07-12 11:37:05.600  2916  4375 D CommandListener: Trying to bring up p2p0
07-12 11:37:05.600  2916  4368 D Netd    : Iface p2p0 link up
07-12 11:37:05.605  3603  4472 E WifiScanningService: could not start HAL
07-12 11:37:05.605  3603  3762 D Tethering: interfaceLinkStateChanged p2p0, true
07-12 11:37:05.605  3603  3762 D Tethering: interfaceStatusChanged p2p0, true
07-12 11:37:05.605  3603  4445 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-12 11:37:05.605  3603  4445 D SecContentProvider: insert(), uri = 2
07-12 11:37:05.605  3603  3603 D RttService: SCAN_AVAILABLE : 3
07-12 11:37:05.605  3603  4445 D WifiP2pService: P2pEnablingState
07-12 11:37:05.605  3603  4473 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:05.605  3603  4445 D WifiP2pService: P2pEnablingState{ what=147457 }
07-12 11:37:05.605  3603  4445 D WifiP2pService: P2p socket connection successful
07-12 11:37:05.605  3603  4445 D WifiP2pService: P2pEnabledState
07-12 11:37:05.605  3603  4445 D SecContentProvider: insert(), uri = 2
07-12 11:37:05.610  3603  4446 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-12 11:37:05.610  3603  4446 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
07-12 11:37:05.610  3603  4446 D WifiStateMachine: setFccChannelNative: channel = 0
07-12 11:37:05.610  3603  4446 D WifiNative-wlan0: callSECApiInt - ID [230]
07-12 11:37:05.610  3603  5105 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6652827 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db78b37 7238:tv.peel.smartremote/u0a186}
07-12 11:37:05.615  3603  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-12 11:37:05.615 10423 10489 I bt_hwcfg: UART_2STOPBITS_CHANGE: setting 2 stop bits
07-12 11:37:05.615 10423 10489 I bt_hwcfg: vendor lib fwcfg completed
07-12 11:37:05.615 10423 10489 I bt_vendor: firmware callback
07-12 11:37:05.615  3603  4445 D WifiP2pService: sending p2p connection changed broadcast: IDLE
07-12 11:37:05.615 10423 10489 I bt_hci  : firmware_config_callback
07-12 11:37:05.615  3603  3829 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-12 11:37:05.615  3603  3603 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-12 11:37:05.615  3603  3829 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-12 11:37:05.620  3603  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-12 11:37:05.620  3603  3829 D WifiDisplayController: disconnect
07-12 11:37:05.620  3603  3829 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-12 11:37:05.620 10423 10553 I bt_btu_task: Bluetooth chip preload is complete
07-12 11:37:05.620  4513  4513 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-12 11:37:05.620  3603  3632 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-12 11:37:05.620  3603  4445 D WifiP2pService: create mNetworkAgent
,07-12 11:37:05.620  3603  4445 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
07-12 11:37:05.620  4513  4513 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-12 11:37:05.620  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{7bed0be: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_HCI
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_BTIF
07-12 11:37:05.625 10423 10553 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-12 11:37:05.625  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{ccf51f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.625  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{eee006c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.630  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{eff4635: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.630  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{c133aca: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.630  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{255c43b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.630  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{f0b758: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.635  4513  4513 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No network connection wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020704/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f0201d9/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-12 11:37:05.635  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:05.635  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:05.635  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:05.635  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:05.635  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{46b10b1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.635  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{d65f104: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.635  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{a3640f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.635  3603  4445 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:05.635  3603  4453 D ConnectivityService: Got NetworkAgent Messenger
07-12 11:37:05.635  3603  4453 E ConnectivityService: updateNetworkInfo()
,07-12 11:37:05.640  3603  4453 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-12 11:37:05.640 10435 10435 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
07-12 11:37:05.640  3603  3829 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.640  3603  4453 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
07-12 11:37:05.640  3603  4453 D ConnectivityService: NetworkAgent connected
07-12 11:37:05.640 10435 10435 I wpa_supplicant: P2P: Set Samsung Discovery name = 
07-12 11:37:05.640  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f26a5 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
07-12 11:37:05.640  5085  5096 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
07-12 11:37:05.645  8639  8639 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
07-12 11:37:05.645  8639  8639 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
07-12 11:37:05.645  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{357ea7a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.645 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:05.645 10540 10551 D HotspotProvider: CREDENTIAL
07-12 11:37:05.645 10540 10551 D HotspotProvider: No prepend tags
07-12 11:37:05.645  8639  8639 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,07-12 11:37:05.645  8639  8639 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-12 11:37:05.650  8639  8639 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-12 11:37:05.650  3603  4439 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:05.650  8639  8639 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-12 11:37:05.650  3603  4448 D HotspotDBHandler: getMethodType
07-12 11:37:05.650  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{b2ca688: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.650 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:05.650 10540 10551 D HotspotProvider: CREDENTIAL
07-12 11:37:05.650 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.655  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{1f08821: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.655  3603  5114 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:05.655  8639  8639 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-12 11:37:05.655  3603  4448 D HS20StateMachine: credential_id 0method_type2
07-12 11:37:05.655  3603  4448 D HotspotDBHandler: getPPSMONode
,07-12 11:37:05.655  8639  8639 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-12 11:37:05.655  8639  8639 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-12 11:37:05.655  8639 10556 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-12 11:37:05.670  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{76a3446: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.670 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:05.670 10540 10551 D HotspotProvider: CREDENTIAL
07-12 11:37:05.670 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.680 10559 10559 E Zygote  : v2
07-12 11:37:05.680 10559 10559 I libpersona: KNOX_SDCARD checking this for 5005
07-12 11:37:05.680 10559 10559 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:05.680 10559 10559 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:05.680 10559 10559 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:05.680 10559 10559 E Zygote  : accessInfo : 0
,07-12 11:37:05.680 10559 10559 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,07-12 11:37:05.685  3603  3753 I ActivityManager: Start proc 10559:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,07-12 11:37:05.685  3603  4445 E WifiP2pService: Failed to set my phone number info into probe response
,07-12 11:37:05.690  3603  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
,07-12 11:37:05.690  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{849c607: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.690  3603  4445 D WifiNative-p2p0: p2pGetDeviceAddress
,07-12 11:37:05.690  3603  4445 D WifiNative-p2p0: p2pGetDeviceAddress returning 92:b6:86:43:73:1c
,07-12 11:37:05.690  3603  3603 I ActivityManager: Killing 9846:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): DHA:empty #31
,07-12 11:37:05.700 10559 10559 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:05.700 10559 10559 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:05.700  3603  4445 D WifiP2pService: DeviceAddress: 92:73:1c
07-12 11:37:05.700 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:05.700 10540 10551 D HotspotProvider: HOTSPOT
07-12 11:37:05.700 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.705  3603  3829 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Note4-1
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  deviceAddress: 92:b6:86:43:73:1c
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  primary type: 10-0050F204-5
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  secondary type: null
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  wps: 0
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  grpcapab: 0
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  devcapab: 0
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  status: 3
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  wfdInfo: null
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  groupownerAddress: null
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  GOdeviceName: null
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  interfaceAddress: 
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  SConnectInfo : null
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  contactInfoHash : null
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  ssDevInfo : 0
07-12 11:37:05.705  3603  3829 D WifiDisplayController:  iconIdx : 0
,07-12 11:37:05.710  3603  7152 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8f26a5 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{229a334 10559:com.samsung.android.app.FileShareClient/5005}
,07-12 11:37:05.710  3603  4448 D HotspotDBHandler: getPpsMoID
,07-12 11:37:05.710  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{9ac855d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.710 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
07-12 11:37:05.710 10540 10550 D HotspotProvider: FQDN
07-12 11:37:05.710 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:05.710  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{2054ed2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.715 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
07-12 11:37:05.715 10540 10550 D HotspotProvider: FQDN
07-12 11:37:05.715 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:05.715  3603  4445 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-12 11:37:05.715  3603  4445 D WifiP2pService: InactiveState
07-12 11:37:05.715  3603  4445 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
07-12 11:37:05.715  3603  4453 E ConnectivityService: updateNetworkInfo()
07-12 11:37:05.715  3603  4453 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
07-12 11:37:05.715  3603  4445 D WifiP2pService: InactiveState{ what=143376 }
07-12 11:37:05.715  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{2b2bba3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.715  3603  4445 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-12 11:37:05.715  3603  4445 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-12 11:37:05.715 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_aaaserver_trustroot
07-12 11:37:05.715 10540 10550 D HotspotProvider: AAASERVER_TRUST_ROOT
07-12 11:37:05.715 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:05.715  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{e57bea0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.720  3603  4448 D HotspotDBHandler: getAAATrustRoot: Corresponding entry doesnt exist
,07-12 11:37:05.720 10559 10559 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm
,07-12 11:37:05.730 10559 10559 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-12 11:37:05.730 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:05.730  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{7311a59: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.730 10540 10550 D HotspotProvider: CREDENTIAL
07-12 11:37:05.730 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:05.730 10559 10559 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,07-12 11:37:05.730  3603  5011 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,07-12 11:37:05.730 10423 10553 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,07-12 11:37:05.735 10423 10553 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb33602ed
07-12 11:37:05.735 10423 10553 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb33602ed 
07-12 11:37:05.735 10423 10553 E bt_btm  : btm_ble_set_search_if search_if=4
,07-12 11:37:05.735  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{fc5861e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.740  3603  4448 D HotspotDBHandler: getHomeSPInfo
07-12 11:37:05.740 10423 10443 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false mAobleSupported = 0
,07-12 11:37:05.745 10423 10443 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,07-12 11:37:05.745 10423 10443 D bt_hci  : do_postload posting postload work item
07-12 11:37:05.745 10423 10489 I bt_hci  : event_postload
,07-12 11:37:05.745 10423 10489 D bt_hwcfg: hw_sco_config
07-12 11:37:05.745 10423 10443 E bt_btif_sock: btif_sock_init: !vhci_init
07-12 11:37:05.745 10423 10489 I bt_vendor: sco_config_cb
07-12 11:37:05.745 10423 10489 I bt_hci  : sco_config_callback postload finished.
07-12 11:37:05.745 10423 10443 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
07-12 11:37:05.750 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:05.750 10540 10550 D HotspotProvider: HOTSPOT
07-12 11:37:05.750 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:05.750  3603  4448 D HotspotDBHandler: getHomeOInfo
,07-12 11:37:05.750  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{f2b6eff: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.750 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homeoilist
,07-12 11:37:05.750 10540 10551 D HotspotProvider: HOMEOILIST
07-12 11:37:05.750 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.750  3603  4448 D HotspotDBHandler: getHomeOInfo :Corresponding entry doesnt exist
07-12 11:37:05.750  3603  4448 D HotspotDBHandler: getNetworkIDInfo
07-12 11:37:05.750 10423 10443 D bt_bte_conf: Device ID record 1 : primary
07-12 11:37:05.750 10423 10443 D bt_bte_conf:   vendorId            = 0075
,07-12 11:37:05.750 10423 10443 D bt_bte_conf:   vendorIdSource      = 0001
07-12 11:37:05.750 10423 10443 D bt_bte_conf:   product             = 0100
07-12 11:37:05.750 10423 10443 D bt_bte_conf:   version             = 0200
07-12 11:37:05.750 10423 10443 D bt_bte_conf:   clientExecutableURL = 
07-12 11:37:05.750 10423 10443 D bt_bte_conf:   serviceDescription  = 
07-12 11:37:05.750 10423 10443 D bt_bte_conf:   documentationURL    = 
07-12 11:37:05.750 10423 10443 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 11:37:05.750 10423 10489 I bt_vendor: low_power_mode_cb
07-12 11:37:05.750 10423 10440 D bt_stack_manager: event_start_up_stack finished
07-12 11:37:05.750 10423 10443 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-12 11:37:05.750 10423 10443 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 7
07-12 11:37:05.750 10423 10443 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 8709
,07-12 11:37:05.750 10423 10443 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4358A1 Samsung TR TRE TB with Seattle WAR Core1 2STOPBITS cfg54-0054
07-12 11:37:05.750 10423 10443 D BluetoothDataManager: firmwareVersion from Property : BCM4358A1_V0054.0094.hcd
07-12 11:37:05.755 10423 10443 E BluetoothAdapterState: stateChangeCallback : 1
07-12 11:37:05.755 10423 10439 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,07-12 11:37:05.755 10559 10559 D FileShare-Client: Outbound.stopDelayTimer - 
,07-12 11:37:05.760 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homesp_network
,07-12 11:37:05.760 10540 10551 D HotspotProvider: HOMESP_NETWORK
07-12 11:37:05.760 10540 10551 D HotspotProvider: No prepend tags
07-12 11:37:05.760 10423 10439 D BluetoothAdapterProperties: Setting state to 15
07-12 11:37:05.760 10423 10439 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-12 11:37:05.760 10423 10439 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-12 11:37:05.760 10423 10439 D BluetoothAdapterService: updateAdapterState state is 15
07-12 11:37:05.760 10423 10439 D BluetoothAdapterService: Autoconnection is available 
07-12 11:37:05.760 10423 10439 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-12 11:37:05.760 10423 10439 I BluetoothAdapterState: Entering BleOnState
,07-12 11:37:05.770 10572 10572 E Zygote  : v2
07-12 11:37:05.770 10572 10572 I libpersona: KNOX_SDCARD checking this for 5005
07-12 11:37:05.770 10572 10572 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:05.770 10572 10572 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:05.770 10572 10572 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:05.770 10572 10572 E Zygote  : accessInfo : 0
07-12 11:37:05.770 10572 10572 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,07-12 11:37:05.770  3603  5016 I ActivityManager: Start proc 10572:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
,07-12 11:37:05.775  3603  4448 D HotspotDBHandler: getNetworkIDInfo: Corresponding entry doesnt exist
,07-12 11:37:05.780  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{8d00315: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.780  3603  4448 D HotspotDBHandler: getOtherHomePartner
,07-12 11:37:05.780 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_otherhome_partner
07-12 11:37:05.780 10540 10551 D HotspotProvider: HOMESP_OTHERHOME_PARTNER
07-12 11:37:05.780 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.780  3603  3828 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-12 11:37:05.780  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{8bfe62a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.785  3603  4448 D HotspotDBHandler: getOtherHomePartner: Corresponding entry doesnt exist
,07-12 11:37:05.785  3603  3603 I ActivityManager: Killing 9875:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #31
,07-12 11:37:05.785  3603  3828 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-12 11:37:05.790 10572 10572 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:05.790 10572 10572 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:05.790 10423 10439 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-12 11:37:05.790  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{51fc1b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.795 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:05.795 10540 10551 D HotspotProvider: HOTSPOT
07-12 11:37:05.795 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.795  3603  3887 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-12 11:37:05.825  3603  3887 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-12 11:37:05.825  3603  3632 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8f26a5 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{59ac1b8 10572:com.samsung.android.app.FileShareServer/5005}
07-12 11:37:05.825 10423 10439 D BluetoothAdapterProperties: Setting state to 11
07-12 11:37:05.825 10423 10439 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 11:37:05.825 10423 10439 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:37:05.825 10423 10439 D BluetoothAdapterService: updateAdapterState state is 11
,07-12 11:37:05.825 10423 10439 D BluetoothAdapterService: Autoconnection is available 
07-12 11:37:05.825 10423 10439 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-12 11:37:05.825  3603  3828 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
07-12 11:37:05.825 10423 10439 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:05.825 10423 10439 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-12 11:37:05.825 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-12 11:37:05.830  3603  5105 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,07-12 11:37:05.835 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hostspot_backhaul_bandwidth_threshold
07-12 11:37:05.835 10540 10584 D HotspotProvider: BACKHAUL_THRESHOLD
07-12 11:37:05.835 10540 10584 D HotspotProvider: No prepend tags
,07-12 11:37:05.835  3603  3603 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:05.835  3603  3603 I InputMethodManagerService: [BT Setting State] State =11
,07-12 11:37:05.835  5131  5131 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:37:05.835 10572 10572 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareServer/lib/arm
,07-12 11:37:05.840  5553  5553 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
07-12 11:37:05.840  3603  3603 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-12 11:37:05.840  3603  3603 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:05.840  3603  5011 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) visible user=0 )
07-12 11:37:05.840  3603  3603 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-12 11:37:05.840  3603  3632 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-12 11:37:05.840  4513  4513 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:05.840  4513  4513 D BluetoothTile:  getBluetoothState : 11
07-12 11:37:05.840  4513  4513 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) user=0 )
,07-12 11:37:05.845  4513  6385 D BluetoothTile:  handleUpdatestate:false name:null
07-12 11:37:05.845  4513  6385 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-12 11:37:05.845  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
,07-12 11:37:05.845  4513  4513 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,07-12 11:37:05.850 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-12 11:37:05.855 10572 10572 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-12 11:37:05.855 10572 10572 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-12 11:37:05.855 10423 10423 D HeadsetService: Received start request. Starting profile...
07-12 11:37:05.855 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
,07-12 11:37:05.855 10423 10423 D HeadsetProvider: make
07-12 11:37:05.855 10423 10423 D HeadsetProvider: HeadsetProvider
07-12 11:37:05.855 10423 10423 I HeadsetProvider: clearAllHeadsetSettings(0)
,07-12 11:37:05.855  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{6164164: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.860 10572 10572 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,07-12 11:37:05.860 10572 10572 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
,07-12 11:37:05.860 10572 10572 W System.err: 	at com.samsung.android.app.FileShareServer.ServerBroadcastReceiver.onReceive(ServerBroadcastReceiver.java:34)
07-12 11:37:05.860 10572 10572 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3634)
07-12 11:37:05.860 10572 10572 W System.err: 	,at android.app.ActivityThread.access$2000(ActivityThread.java:221)
07-12 11:37:05.860  3603  3631 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d83a6f 5652:com.samsung.android.providers.context/u0a11}
07-12 11:37:05.860 10572 10572 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1876)
,07-12 11:37:05.860 10572 10572 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:05.860 10572 10572 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:37:05.860 10572 10572 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7225)
07-12 11:37:05.860 10572 10572 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,07-12 11:37:05.860 10572 10572 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:37:05.860 10572 10572 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,07-12 11:37:05.865  3603  4448 D HotspotDBHandler: getMinBackHaulThresholdInfo: Corresponding entry doesnt exist
,07-12 11:37:05.865 10423 10423 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:37:05.870 10423 10423 D HeadsetStateMachine: make
,07-12 11:37:05.870 10423 10423 E HeadsetStateMachine: # of Max HF connection is 2
,07-12 11:37:05.875 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-12 11:37:05.875 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_preferredroaming_partnerlist
,07-12 11:37:05.875 10540 10551 D HotspotProvider: PREFERRED_ROAMING
07-12 11:37:05.875 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.885 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-12 11:37:05.885  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{a0415ef: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.890  3603  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
,07-12 11:37:05.890  8639  8639 D BluetoothNotiBroadcastReceiver: onReceive
,07-12 11:37:05.900 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-12 11:37:05.900 10423 10423 I bt_bluedroid: get_profile_interface handsfree
07-12 11:37:05.900  3603  4448 D HotspotDBHandler: getPreferredRoamingPartnerInfo: Corresponding entry doesnt exist
,07-12 11:37:05.905  3603  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5e19b0 4513:com.android.systemui/u0a60}
,07-12 11:37:05.910  4513  4513 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:05.910  4513  4513 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-12 11:37:05.915 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-12 11:37:05.925  3603  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d58f9 10490:com.sec.android.widgetapp.locationwidget/u0a22}
,07-12 11:37:05.930 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_tupple
07-12 11:37:05.930 10540 10584 D HotspotProvider: TUPPLE
07-12 11:37:05.930 10540 10584 D HotspotProvider: No prepend tags
,07-12 11:37:05.935 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-12 11:37:05.935  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{3594da6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.940 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:05.940 10423 10439 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:37:05.940 10423 10439 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:05.940 10423 10439 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:37:05.940 10423 10439 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:37:05.945  3603  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ec9e94 5142:com.sec.android.app.shealth:remote/u0a36}
,07-12 11:37:05.955  3603  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a80fd0 10423:com.android.bluetooth/1002}
,07-12 11:37:05.960 10423 10423 I DualScoManager: Instantiating Dual Sco Manager
07-12 11:37:05.960 10423 10423 I DualScoManager: Set HeadsetServiceHelper
07-12 11:37:05.960  3603  4448 D HotspotDBHandler: getProtoPortTupple: Corresponding entry doesnt exist
,07-12 11:37:05.960  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{712d3e7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.960 10423 10423 D BluetoothAtMessage: createCMTIContentObservers
,07-12 11:37:05.970  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{b3ecb94: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.970 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-12 11:37:05.970 10540 10550 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-12 11:37:05.970 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:05.970  3603  4448 D HotspotDBHandler: getPolicyUpdateInfo: Corresponding entry doesnt exist
,07-12 11:37:05.975 10423 10423 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@31a2c8f
,07-12 11:37:05.975 10423 10423 D HeadsetProvider: setHeadsetDB - Can't find 300 for E0:DB:10:14:E2:XX
,07-12 11:37:05.980  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{43bf63d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.980 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_spexclusion_list
07-12 11:37:05.980 10540 10551 D HotspotProvider: SPEXCLUSION_LIST
07-12 11:37:05.980 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.980  3603  4448 D HotspotDBHandler: getSPExclusionList: Corresponding entry doesnt exist
,07-12 11:37:05.985  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{2bc9e32: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:05.985 10423 10423 I HeadsetProvider: setHeadsetDB - E0:DB:10:14:E2:XX, 300, 1, true
,07-12 11:37:05.990 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:05.990 10540 10550 D HotspotProvider: HOTSPOT
07-12 11:37:05.990 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:05.995  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{f2ec783: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:05.995  3603  4448 D HotspotDBHandler: getRemediationInfo
,07-12 11:37:05.995 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:05.995 10540 10584 D HotspotProvider: HOTSPOT
07-12 11:37:05.995 10540 10584 D HotspotProvider: No prepend tags
,07-12 11:37:05.995 10423 10423 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@311acfa
07-12 11:37:05.995 10423 10423 D HeadsetProvider: setHeadsetDB - Can't find 400 for E0:DB:10:14:E2:XX
,07-12 11:37:05.995 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-12 11:37:05.995 10540 10551 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-12 11:37:05.995 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:05.995  3603  4448 D HotspotDBHandler: getSubscriptionUpdateInfo: Corresponding entry doesnt exist
,07-12 11:37:06.000  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{a070d00: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.000  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [206]
,07-12 11:37:06.000  3603  4446 D WifiNative-wlan0: callSECApiInt - ID [307]
07-12 11:37:06.000 10435 10435 I wpa_supplicant: wlan0: CRED-REMOVED 0
07-12 11:37:06.000  3603  4448 D HotspotDBHandler: setUserPriority credid: 0 userPriority:1
,07-12 11:37:06.005 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:06.005 10540 10550 D HotspotProvider: CREDENTIAL
07-12 11:37:06.005 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:06.005  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{8f6b939: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.005  3603  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
,07-12 11:37:06.010 10423 10423 I HeadsetProvider: setHeadsetDB - E0:DB:10:14:E2:XX, 400, 1, true
07-12 11:37:06.010 10423 10586 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-12 11:37:06.020 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-12 11:37:06.020 10540 10551 D HotspotProvider: Inside  update methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:06.020 10540 10551 D HotspotProvider: HOTSPOT
07-12 11:37:06.020 10423 10423 E HeadsetService: notifyProfileServiceStateChanged
,07-12 11:37:06.020  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{a00aff5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.020  5652  5652 D BluetoothA2dp: Proxy object connected
07-12 11:37:06.020  3603  3603 D BluetoothA2dp: Proxy object connected
07-12 11:37:06.020 10423 10423 D A2dpService: Received start request. Starting profile...
07-12 11:37:06.020 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
,07-12 11:37:06.020  3603  4448 D HotspotDBHandler: getPPSMONode
07-12 11:37:06.020 10423 10586 D HeadsetStateMachine: Clear mHeadsetBrsf
07-12 11:37:06.020 10423 10586 D HeadsetStateMachine: map size, before remove : 0
07-12 11:37:06.020 10423 10586 D HeadsetStateMachine: map size, after remove: 0
07-12 11:37:06.020 10423 10423 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-12 11:37:06.020  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{465c18a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.020 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:06.025 10540 10584 D HotspotProvider: CREDENTIAL
07-12 11:37:06.025 10540 10584 D HotspotProvider: No prepend tags
07-12 11:37:06.025  3603  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
07-12 11:37:06.025  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{b07a3fb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.025 10423 10423 I bt_bluedroid: get_profile_interface avrcp
,07-12 11:37:06.025 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:06.025 10540 10551 D HotspotProvider: HOTSPOT
07-12 11:37:06.025 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:06.030  3603  4448 D HotspotDBHandler: getPpsMoID
07-12 11:37:06.030  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{5597c18: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.030 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
07-12 11:37:06.030 10540 10584 D HotspotProvider: FQDN
,07-12 11:37:06.030 10540 10584 D HotspotProvider: No prepend tags
,07-12 11:37:06.030  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{1fbe8ad: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.030 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_fqdn
,07-12 11:37:06.030 10540 10551 D HotspotProvider: FQDN
07-12 11:37:06.030 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:06.035 10423 10423 I Avrcp   : No of Audio players :: 2
07-12 11:37:06.035 10423 10423 I Avrcp   : App Package name is GM
07-12 11:37:06.035  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{bf4f7e2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.035 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_aaaserver_trustroot
,07-12 11:37:06.035 10540 10550 D HotspotProvider: AAASERVER_TRUST_ROOT
07-12 11:37:06.035 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:06.040 10423 10423 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-12 11:37:06.040 10423 10423 I Avrcp   : App Package name is SM
,07-12 11:37:06.040 10423 10423 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-12 11:37:06.045 10423 10423 I Avrcp   : No of Video players :: 2
07-12 11:37:06.045 10423 10423 I Avrcp   : Video App Package name is others
,07-12 11:37:06.045  3603  4448 D HotspotDBHandler: getAAATrustRoot: Corresponding entry doesnt exist
,07-12 11:37:06.045 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:06.045 10540 10584 D HotspotProvider: CREDENTIAL
07-12 11:37:06.045 10540 10584 D HotspotProvider: No prepend tags
,07-12 11:37:06.045  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{5a09773: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.045 10423 10423 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-12 11:37:06.045 10423 10423 I Avrcp   : Video App Package name is others
,07-12 11:37:06.050  3603  4448 D HotspotDBHandler: getHomeSPInfo
,07-12 11:37:06.050 10423 10423 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-12 11:37:06.050 10423 10423 I Avrcp   : Add tempPlayer
07-12 11:37:06.050 10423 10423 V Avrcp   : MediaPlayerInfo: mPlayerId=5
07-12 11:37:06.050 10423 10423 V Avrcp   : no_of_players : 5
07-12 11:37:06.050 10423 10423 I Avrcp   : Total no of players: 5
07-12 11:37:06.050 10423 10423 V Avrcp   : swapping the samsung player with 1st player
07-12 11:37:06.050 10423 10423 D Avrcp   : Compose Browsing Service Candidate
,07-12 11:37:06.050 10423 10423 D Avrcp   : ResolveInfo info ResolveInfo{8c11e87 com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-12 11:37:06.050 10423 10423 D Avrcp   : Initialize Media Controller
,07-12 11:37:06.055 10423 10423 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-12 11:37:06.055  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{977b630: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.055 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:06.055 10540 10551 D HotspotProvider: HOTSPOT
07-12 11:37:06.055 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:06.055 10423 10423 E Avrcp   : getActiveSessions
07-12 11:37:06.055 10423 10423 D Avrcp   : pick active media Controller
07-12 11:37:06.055 10423 10423 D Avrcp   : Get the active Media Controller 
07-12 11:37:06.055 10423 10423 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:37:06.055 10423 10423 D A2dpStateMachine: make
,07-12 11:37:06.055 10423 10423 I bt_bluedroid: get_profile_interface a2dp
,07-12 11:37:06.055 10423 10423 E bt_btif : warning : media task started media_task_refcnt 1 
07-12 11:37:06.055 10423 10423 E bt_btif : warning : no command pending, ignore ack
,07-12 11:37:06.060 10423 10592 D A2dpStateMachine: Enter Disconnected: -2
,07-12 11:37:06.065  3603  4448 D HotspotDBHandler: getHomeOInfo
,07-12 11:37:06.065 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-12 11:37:06.065 10423 10423 E A2dpService: notifyProfileServiceStateChanged
,07-12 11:37:06.065 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homeoilist
07-12 11:37:06.065 10540 10584 D HotspotProvider: HOMEOILIST
07-12 11:37:06.065 10540 10584 D HotspotProvider: No prepend tags
,07-12 11:37:06.065  3603  4448 D HotspotDBHandler: getHomeOInfo :Corresponding entry doesnt exist
,07-12 11:37:06.070  3603  4448 D HotspotDBHandler: getNetworkIDInfo
,07-12 11:37:06.070  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{fda055c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.070 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_homesp_network
07-12 11:37:06.070 10540 10551 D HotspotProvider: HOMESP_NETWORK
07-12 11:37:06.070 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:06.070  3603  4448 D HotspotDBHandler: getNetworkIDInfo: Corresponding entry doesnt exist
,07-12 11:37:06.080  3603  4448 D HotspotDBHandler: getOtherHomePartner
,07-12 11:37:06.080 10423 10423 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 11:37:06.080  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{e9e8065: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.080 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_otherhome_partner
07-12 11:37:06.080 10540 10550 D HotspotProvider: HOMESP_OTHERHOME_PARTNER
07-12 11:37:06.080 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:06.080  3603  4448 D HotspotDBHandler: getOtherHomePartner: Corresponding entry doesnt exist
,07-12 11:37:06.085  3603  3603 I ActivityManager: Killing 9888:com.sec.android.app.myfiles/u0a53 (adj 15): DHA:empty #31
,07-12 11:37:06.085 10423 10423 D HidService: Received start request. Starting profile...
07-12 11:37:06.085 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
07-12 11:37:06.085 10423 10423 I bt_bluedroid: get_profile_interface hidhost
07-12 11:37:06.085 10423 10423 D HidService: setHidService(): set to: null
07-12 11:37:06.085 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-12 11:37:06.085 10423 10423 E HidService: notifyProfileServiceStateChanged
,07-12 11:37:06.085 10423 10423 D HeadsetStateMachine: Try to query the phonestate on bind
07-12 11:37:06.085  3603  5083 I Telecom : BluetoothPhoneService: queryPhoneState
,07-12 11:37:06.085  3603  5083 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
07-12 11:37:06.085 10423 10423 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 11:37:06.090 10423 10423 D HealthService: Received start request. Starting profile...
07-12 11:37:06.090 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
,07-12 11:37:06.090 10423 10423 I bt_bluedroid: get_profile_interface health
07-12 11:37:06.090 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
,07-12 11:37:06.090 10423 10423 E HealthService: notifyProfileServiceStateChanged
07-12 11:37:06.090 10423 10423 D HeadsetStateMachine: Proxy object connected
07-12 11:37:06.090 10423 10423 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-12 11:37:06.090 10423 10586 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:37:06.090 10423 10586 E HeadsetStateMachine: Unknown message: 11
07-12 11:37:06.090 10423 10423 I BluetoothPanServiceJni: classInitNative(L113): succeeds
07-12 11:37:06.090  3603  3603 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:37:06.090 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:06.090 10540 10584 D HotspotProvider: HOTSPOT
07-12 11:37:06.090 10540 10584 D HotspotProvider: No prepend tags
07-12 11:37:06.090 10423 10423 D PanService: Received start request. Starting profile...
07-12 11:37:06.090 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
07-12 11:37:06.090 10423 10423 D BluetoothPanServiceJni: initializeNative(L118): pan
07-12 11:37:06.090 10423 10423 I bt_bluedroid: get_profile_interface pan
,07-12 11:37:06.095 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-12 11:37:06.095 10423 10423 E PanService: notifyProfileServiceStateChanged
,07-12 11:37:06.095  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{7b9a13a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.095 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hostspot_backhaul_bandwidth_threshold
07-12 11:37:06.095 10540 10550 D HotspotProvider: BACKHAUL_THRESHOLD
07-12 11:37:06.095 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:06.095  3603  4448 D HotspotDBHandler: getMinBackHaulThresholdInfo: Corresponding entry doesnt exist
,07-12 11:37:06.095 10423 10423 D BluetoothMapService: Received start request. Starting profile...
07-12 11:37:06.095 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
,07-12 11:37:06.095 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_preferredroaming_partnerlist
07-12 11:37:06.095 10540 10584 D HotspotProvider: PREFERRED_ROAMING
07-12 11:37:06.095 10540 10584 D HotspotProvider: No prepend tags
07-12 11:37:06.095  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{4109706: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.095 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-12 11:37:06.095 10423 10423 E BluetoothMapService: notifyProfileServiceStateChanged
,07-12 11:37:06.100  3603  4448 D HotspotDBHandler: getPreferredRoamingPartnerInfo: Corresponding entry doesnt exist
,07-12 11:37:06.100 10423 10423 V SapService: SapBinder()
,07-12 11:37:06.100 10423 10423 D SapService: Received start request. Starting profile...
07-12 11:37:06.100 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
07-12 11:37:06.100 10423 10423 V SapService: start()
07-12 11:37:06.100  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{74fa3f4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.100 10423 10423 D SapService: Disable sap : false
,07-12 11:37:06.100 10423 10423 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-12 11:37:06.100 10423 10423 E SapService: notifyProfileServiceStateChanged
07-12 11:37:06.100 10423 10423 D HeadsetPhoneState: sendDeviceDataStateChanged
07-12 11:37:06.100 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_tupple
07-12 11:37:06.100 10423 10423 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-12 11:37:06.100 10540 10551 D HotspotProvider: TUPPLE
07-12 11:37:06.100 10540 10551 D HotspotProvider: No prepend tags
07-12 11:37:06.100 10423 10586 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-12 11:37:06.100 10423 10586 E HeadsetStateMachine: Unknown message: 19
,07-12 11:37:06.100 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:06.100 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:06.100 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:37:06.100 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:06.100 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
07-12 11:37:06.100 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-12 11:37:06.100 10423 10586 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:37:06.100 10423 10586 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:37:06.100 10423 10586 E HeadsetStateMachine: Unknown message: 11
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:06.100 10423 10423 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:37:06.100 10423 10423 D HeadsetPhoneState: sendDeviceDataStateChanged
07-12 11:37:06.100 10423 10586 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-12 11:37:06.100 10423 10586 E HeadsetStateMachine: Unknown message: 11
07-12 11:37:06.100 10423 10586 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-12 11:37:06.100 10423 10586 E HeadsetStateMachine: Unknown message: 19
07-12 11:37:06.100 10423 10423 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-12 11:37:06.100 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:06.100 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:06.100 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:06.100 10423 10423 D BluetoothAdapterService: HID Host service started
,07-12 11:37:06.110 10597 10597 E Zygote  : v2
07-12 11:37:06.110 10597 10597 I libpersona: KNOX_SDCARD checking this for 10131
07-12 11:37:06.110 10597 10597 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:06.110 10597 10597 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:06.110 10597 10597 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:06.110  3603  4553 I ActivityManager: Start proc 10597:com.google.android.apps.maps/u0a131 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-12 11:37:06.115 10597 10597 E Zygote  : accessInfo : 0
,07-12 11:37:06.115 10597 10597 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,07-12 11:37:06.115  3603  4448 D HotspotDBHandler: getProtoPortTupple: Corresponding entry doesnt exist
07-12 11:37:06.115  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{4bd0b60: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.120 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-12 11:37:06.120 10540 10550 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-12 11:37:06.120 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:06.120 10423 10423 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: handleMessage() - Message: 1
07-12 11:37:06.120 10423 10423 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:06.120 10423 10423 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:06.120 10423 10439 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-12 11:37:06.125  3603  5016 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.myfiles, Auto Run ON
,07-12 11:37:06.130  3603  4448 D HotspotDBHandler: getPolicyUpdateInfo: Corresponding entry doesnt exist
07-12 11:37:06.130  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{a354819: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.130 10423 10439 E BluetoothServiceJni: enableBrEdrNative:
07-12 11:37:06.130 10423 10439 I bt_bluedroid: enable_bredr
,07-12 11:37:06.130 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_spexclusion_list
07-12 11:37:06.130 10540 10584 D HotspotProvider: SPEXCLUSION_LIST
07-12 11:37:06.130 10540 10584 D HotspotProvider: No prepend tags
,07-12 11:37:06.135  3603  4448 D HotspotDBHandler: getSPExclusionList: Corresponding entry doesnt exist
07-12 11:37:06.135 10597 10597 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:06.135 10423 10443 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xb33359ad
07-12 11:37:06.135  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{fd80de: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.135 10597 10597 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:06.135 10423 10443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
07-12 11:37:06.135 10423 10443 D BluetoothAdapterProperties: Address is:E0:DB:10:14:E2:C0
07-12 11:37:06.135 10423 10443 E BluetoothServiceJni: populateRssiValuesNative
07-12 11:37:06.135 10423 10443 I bt_bluedroid: getModelRssiValues
07-12 11:37:06.135 10423 10443 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-12 11:37:06.135 10423 10443 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
07-12 11:37:06.135 10423 10553 D         : Codec ==> copy capability info [bta_av_co_audio_init:584]
,07-12 11:37:06.145 10423 10443 D BluetoothAdapterProperties: Name is: Note4-1
,07-12 11:37:06.145 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:06.145 10540 10551 D HotspotProvider: HOTSPOT
07-12 11:37:06.145 10540 10551 D HotspotProvider: No prepend tags
,07-12 11:37:06.150 10435 10435 I wpa_supplicant: nl80211: Received scan results (7 BSSes)
07-12 11:37:06.150  2916  4368 D Netd    : Iface wlan0 link up
07-12 11:37:06.150 10435 10435 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-12 11:37:06.150 10435 10435 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-12 11:37:06.150 10435 10435 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-12 11:37:06.150 10435 10435 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
07-12 11:37:06.150  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2e7b2bf 10597:com.google.android.apps.maps/u0a131}
07-12 11:37:06.150 10435 10435 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
07-12 11:37:06.150 10435 10435 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
,07-12 11:37:06.150 10435 10435 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz level=-43) 
07-12 11:37:06.150  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:06.150  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:06.150 10423 10443 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-12 11:37:06.150 10423 10443 D BluetoothAdapterProperties: Scan Mode:20
07-12 11:37:06.150 10423 10443 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:37:06.150 10423 10443 E bt_btif : btif_handle_bluetooth_enable_evt
07-12 11:37:06.150 10423 10443 E bt_btif : ANT+ socket does not initialize.
07-12 11:37:06.150  3603  3603 D SettingsProvider: isChangeAllowed() SettingsProvider : name = bluetooth_name
,07-12 11:37:06.150 10423 10443 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-12 11:37:06.155  3603  4448 D HotspotDBHandler: getRemediationInfo
07-12 11:37:06.155 10354 10354 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:37:06.155 10540 10550 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot
07-12 11:37:06.155 10540 10550 D HotspotProvider: HOTSPOT
07-12 11:37:06.155 10540 10550 D HotspotProvider: No prepend tags
,07-12 11:37:06.155 10423 10443 D IOP_DB_BT: db_open: db_open : handle 3006074896l, read 17911 bytes onto local cache
07-12 11:37:06.155 10423 10443 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-12 11:37:06.155 10423 10443 D IOP_DB_BT: db_query: result 1
07-12 11:37:06.155 10423 10443 I         : iop_db_open: iop_db_open status 0
07-12 11:37:06.155 10423 10443 E BluetoothAdapterState: stateChangeCallback : 17
07-12 11:37:06.155 10423 10443 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-12 11:37:06.160  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{3d77d8c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.160 10540 10584 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_policy_subsription_update
07-12 11:37:06.160 10540 10584 D HotspotProvider: POLICY_SUBSCRIPTION_UPDATE
07-12 11:37:06.160 10540 10584 D HotspotProvider: No prepend tags
07-12 11:37:06.160  3603  4448 D HotspotDBHandler: getSubscriptionUpdateInfo: Corresponding entry doesnt exist
07-12 11:37:06.160  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{1494cd5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.165 10423 10439 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,07-12 11:37:06.170 10423 10439 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:37:06.170 10423 10439 D BluetoothAdapterProperties: State =  11
,07-12 11:37:06.175  3603  5112 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-12 11:37:06.175  3603  5011 D SecContentProvider: insert(), uri = 2
07-12 11:37:06.175  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [206]
07-12 11:37:06.175  3603  4446 D WifiNative-wlan0: callSECApiInt - ID [307]
,07-12 11:37:06.175  3603  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:06.175  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{35cccea: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.180 10423 10439 D BluetoothAdapterProperties: Setting state to 12
07-12 11:37:06.180 10423 10439 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 11:37:06.180  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [210]
07-12 11:37:06.180  3603  4446 D WifiNative-wlan0: callSECApiVoid - ID [310]
07-12 11:37:06.180 10423 10443 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-12 11:37:06.180 10423 10443 D BluetoothAdapterProperties: Scan Mode:21
07-12 11:37:06.180 10423 10443 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:37:06.180 10435 10435 I wpa_supplicant: wlan0: CRED-ADDED 0
07-12 11:37:06.180  3603  4448 I HS20StateMachine: credID(0) returned from supplicant,
07-12 11:37:06.180 10597 10597 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
07-12 11:37:06.180  3603  4448 I HS20StateMachine: credential ID 0
07-12 11:37:06.180  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-12 11:37:06.180  3603  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-12 11:37:06.180 10435 10435 I wpa_supplicant: wlan0: CRED-MODIFIED 0 id
07-12 11:37:06.185  3603  4448 I HS20StateMachine: usernamePasswordObj is not nullnull
,07-12 11:37:06.185 10354 10354 D BluetoothAdapter: STATE_ON
07-12 11:37:06.185 10423 10439 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-12 11:37:06.185 10423 10439 D BluetoothAdapterService: updateAdapterState state is 12
07-12 11:37:06.185 10354 10354 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-12 11:37:06.190 10354 10354 D BluetoothAdapter: STATE_ON,
07-12 11:37:06.190 10423 10439 V BluetoothAdapterService: start opp service
07-12 11:37:06.190  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-12 11:37:06.190  3603  4446 D WifiNative-wlan0: callSECApiString - ID [309]
,07-12 11:37:06.190 10435 10435 E wpa_supplicant: SIM READ ERROR
07-12 11:37:06.190 10435 10435 I wpa_supplicant: wlan0: CRED-MODIFIED 0 imsi,
,07-12 11:37:06.190 10435 10435 I wpa_supplicant: Blacklist: Clear (all) 
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:06.195 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:37:06.195 10354 10354 D BluetoothAdapter: STATE_ON,
07-12 11:37:06.195 10354 10354 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:37:06.200  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{c5ee151: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.195 10423 10423 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-12 11:37:06.195 10423 10423 I BluetoothPbapService: Handler(): got msg=1
07-12 11:37:06.195  3603  5083 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-12 11:37:06.200  9944  9954 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.200  9944  9954 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.200 10423 10439 D BluetoothAdapterService: Autoconnection is available 
07-12 11:37:06.200 10423 10439 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,07-12 11:37:06.200 10423 10439 D BluetoothAdapterService: starting service from this receiver
07-12 11:37:06.200 10423 10433 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.200 10423 10433 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.200  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-12 11:37:06.200  3603  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-12 11:37:06.200  5621  6372 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.200  5621  6372 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.200 10435 10435 I wpa_supplicant: wlan0: CRED-MODIFIED 0 update_identifier
07-12 11:37:06.200  7238  7662 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.200  7238  7662 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.200 10354 10365 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.200 10354 10365 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-12 11:37:06.200  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-12 11:37:06.200  3603  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-12 11:37:06.200 10435 10435 I wpa_supplicant: wlan0: CRED-MODIFIED 0 max_bss_load
,07-12 11:37:06.200  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-12 11:37:06.200  3603  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-12 11:37:06.200 10435 10435 I wpa_supplicant: wlan0: CRED-MODIFIED 0 country
,07-12 11:37:06.205  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-12 11:37:06.205  3603  4446 D WifiNative-wlan0: callSECApiString - ID [309]
,07-12 11:37:06.205 10435 10435 I wpa_supplicant: wlan0: CRED-MODIFIED 0 temporary
,07-12 11:37:06.205  3603  4446 D WifiStateMachine: DriverStatedState::CMD_SEC_API - inner msg [209]
07-12 11:37:06.205  3603  4446 D WifiNative-wlan0: callSECApiString - ID [309]
07-12 11:37:06.205 10435 10435 I wpa_supplicant: wlan0: CRED-MODIFIED 0 priority
,07-12 11:37:06.210 10423 10612 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-12 11:37:06.210  3603  4448 D HotspotDBHandler: setCredentials:credentialType-1credentialID0methodType2old_cred_id0
,07-12 11:37:06.210 10423 10439 D BluetoothAdapterService: BT on, init HID DEV count : 0
07-12 11:37:06.210 10423 10439 I BluetoothAdapterState: Entering OnState
,07-12 11:37:06.210  3603  3828 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:37:06.210  5652  5665 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-12 11:37:06.210  5652  5665 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.215  5085  5444 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.215  5085  5444 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.215  3603  3828 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.215  3603  3828 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.220 10423 10423 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
07-12 11:37:06.220 10423 10423 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 11:37:06.220 10423 10423 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-12 11:37:06.220 10423 10423 W System.err: 	at com.android.bluetooth.opp.BluetoothOppService.onCreate(BluetoothOppService.java:195)
07-12 11:37:06.220 10423 10423 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3807)
07-12 11:37:06.220 10423 10423 W System.err: 	at android.app.ActivityThread.access$2100(ActivityThread.java:221)
07-12 11:37:06.220  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{e960f42: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.220 10423 10423 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1882)
07-12 11:37:06.220 10423 10423 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:06.220 10423 10423 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:37:06.220 10423 10423 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7225)
,07-12 11:37:06.220 10423 10423 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:06.220 10423 10423 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:37:06.220 10423 10423 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-12 11:37:06.220 10540 10551 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:06.220 10540 10551 D HotspotProvider: CREDENTIAL
07-12 11:37:06.220 10540 10551 D HotspotProvider: No prepend tags
07-12 11:37:06.220  5652  5665 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:37:06.220  4513  4542 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.220  4513  4542 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.220  3603  4448 D HotspotDBHandler: getHotspotId: Hotspot ID1
07-12 11:37:06.220 10423 10612 D BluetoothSocket: bindListen(): myUserId = 0
07-12 11:37:06.220 10423 10612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:06.220  5142  5167 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.220  5142  5167 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.220 10423 10423 V BtOppService: isOwner == true
07-12 11:37:06.220  5072  6602 D BluetoothAdapter: onBluetoothStateChange: up=true
07-12 11:37:06.220  5072  6602 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-12 11:37:06.220  3603  3828 D BluetoothPan: onBluetoothStateChange on: true
,07-12 11:37:06.220 10540 10550 D HotspotProvider: Inside  update methodcontent://com.samsung.passpoint/hotspot_credentials
07-12 11:37:06.220  3603  3603 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:06.220 10540 10550 D HotspotProvider: CREDENTIAL
07-12 11:37:06.220  3603  3603 I InputMethodManagerService: [BT Setting State] State =12
07-12 11:37:06.220  3603  3603 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-12 11:37:06.225  5131  5131 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:06.225  3603  3603 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 11:37:06.225  3603  3603 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,07-12 11:37:06.225  5553  5553 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-12 11:37:06.225  3603  3603 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-12 11:37:06.225  3603  3603 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:06.225  3603  3603 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-12 11:37:06.230  3603  7152 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) visible user=0 )
,07-12 11:37:06.230  3603  5105 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-12 11:37:06.230  4513  4513 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:06.230  4513  4513 D BluetoothTile:  getBluetoothState : 12
07-12 11:37:06.230  4513  4513 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0204b0) visible user=0 )
07-12 11:37:06.230  3603  4448 D HotspotDBHandler: setCredentials: Updation of credential info successful.status:1
07-12 11:37:06.230  3603  4448 D HS20StateMachine: new_credential_id 0
07-12 11:37:06.230  3603  4448 I HS20StateMachine: came to save config
,07-12 11:37:06.235  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{a38c9af: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.235  4513  6385 D BluetoothTile:  handleUpdatestate:false name:null
,07-12 11:37:06.235  3603  4448 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-12 11:37:06.235  3603  4448 D HS20StateMachine: enter : DiscoveringState
,07-12 11:37:06.240 10423 10612 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-12 11:37:06.250  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{370a7fd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.255  3603  6622 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:06.255  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{a24c6f9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.255  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{3dec63e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.260  3603  6622 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:06.260  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{8357c9f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.260 10423 10617 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,07-12 11:37:06.265 10423 10617 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 11:37:06.265 10423 10617 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-12 11:37:06.265 10423 10617 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:252)
,07-12 11:37:06.270 10618 10618 E Zygote  : v2
07-12 11:37:06.270 10618 10618 I libpersona: KNOX_SDCARD checking this for 10178
07-12 11:37:06.270 10618 10618 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:06.275 10618 10618 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:06.275 10618 10618 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:06.275 10618 10618 E Zygote  : accessInfo : 0
07-12 11:37:06.275 10618 10618 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,07-12 11:37:06.275  3603  5114 I ActivityManager: Start proc 10618:com.android.email/u0a178 for content provider com.android.email/.provider.EmailProvider
07-12 11:37:06.275  3603  4444 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-12 11:37:06.275  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{cb8b1ec: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.280  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{961d9b5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.280  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{5fd084a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.285 10435 10435 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
07-12 11:37:06.285  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{87f43bb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.285  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{27500d8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.290  2916  4368 D Netd    : Iface wlan0 link up
07-12 11:37:06.290  2916  4368 D Netd    : Iface wlan0 link up
,07-12 11:37:06.290  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{1235c31: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.290  2916  4368 D Netd    : Iface wlan0 link up
07-12 11:37:06.290  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:06.290  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
07-12 11:37:06.290  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:06.290  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
07-12 11:37:06.290  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:06.290  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:06.290 10435 10435 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-12 11:37:06.290 10435 10435 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
07-12 11:37:06.290 10435 10435 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,07-12 11:37:06.295  3603  4444 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:37:06.300 10435 10435 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,07-12 11:37:06.300  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{10b5f16: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.300 10435 10435 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
07-12 11:37:06.300 10618 10618 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:06.300 10618 10618 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:06.305 10435 10435 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 11:37:06.305 10435 10435 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-12 11:37:06.305  2916  4368 D Netd    : Iface wlan0 link up
07-12 11:37:06.305 10435 10435 I wpa_supplicant: Blacklist: Clear (temp) 
,07-12 11:37:06.305  3603  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-12 11:37:06.305  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:06.305  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
,07-12 11:37:06.310 10597 10631 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
07-12 11:37:06.310 10597 10631 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,07-12 11:37:06.320 10597 10631 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
07-12 11:37:06.320  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{ef46f33: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.325  3603  4446 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-12 11:37:06.325  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{7673aee: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.330  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{cfccb8f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.335  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{d426e1c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.335 10423 10434 D A2dpStateMachine: getConnectedDevices : size=0
,07-12 11:37:06.335  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{1017fa: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.340  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{38491ab: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.340  3603  3603 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@9165008
07-12 11:37:06.340  3603  3603 D BluetoothHeadset: registerMessageListener
,07-12 11:37:06.340 10423 10587 D HeadsetService: registerMessageListener
,07-12 11:37:06.340  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{912b3a1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.340 10423 10587 D HeadsetService: registerMessageListener
07-12 11:37:06.340 10423 10586 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-12 11:37:06.340  3603  3603 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
07-12 11:37:06.340  3603  3603 I Telecom : BluetoothManager : register MessageListener
07-12 11:37:06.340 10423 10586 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@b396f81
,07-12 11:37:06.340  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{f37b9c6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.345  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{a789d87: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.345  3603  4446 V AlarmManager:  remove PendingIntent] PendingIntent{2c464b4: PendingIntentRecord{b85e8dd android broadcastIntent}}
,07-12 11:37:06.345  3603  4446 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-12 11:37:06.345  3603  3603 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-12 11:37:06.345  3603  3603 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:06.345  3603  3603 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-12 11:37:06.345  3603  4451 I WifiHs20Service: Message received 5007
,07-12 11:37:06.350  3603  4446 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:06.350  3603  4453 D ConnectivityService: Got NetworkAgent Messenger
07-12 11:37:06.350  3603  4453 E ConnectivityService: updateNetworkInfo()
07-12 11:37:06.350  3603  4453 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:06.350  3603  4453 D ConnectivityService: NetworkAgent connected
,07-12 11:37:06.350  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{2313b9b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.350  2916  4375 D CommandListener: Setting iface cfg
,07-12 11:37:06.350  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{401cb38: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.355  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{1a462e4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.355  3603  4446 D WifiStateMachine: Start Dhcp Watchdog 1
,07-12 11:37:06.355  3603  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-12 11:37:06.355  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{b131b5a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.355  3603  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-12 11:37:06.355 10597 10606 W art     : Suspending all threads took: 11.534ms
07-12 11:37:06.355  3603  5084 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:06.355  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{b14418b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.360  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{1a7268: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}},
07-12 11:37:06.360  3603  4446 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-12 11:37:06.360  3603  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
,07-12 11:37:06.365  3603  4446 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-12 11:37:06.365  3603  4453 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:06.365  3603  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:37:06.365  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{e8e9681: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.370  3603  5112 D RCPManagerService: exchangeData() failure , invalid userId
07-12 11:37:06.370  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{d579326: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.370  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{2836b67: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.375  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{5584d14: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.375  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{f8d19bd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.380  3603  3632 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:06.380  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{ef694b9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.380  3603  5105 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:06.385  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{63e0fe: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.385  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{b88605f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.390  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{ee82aac: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.395  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{2e2c375: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.400  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{3990f0a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.405  3603  3632 I ActivityManager: Killing 9902:com.google.android.apps.docs/u0a101 (adj 15): DHA:empty #31
,07-12 11:37:06.410  3603  3632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435cdf2 5621:com.google.android.gms.persistent/u0a14}
,07-12 11:37:06.410  5621  5621 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-12 11:37:06.420  3603  5015 D RCPManagerService: exchangeData() failure , invalid userId
07-12 11:37:06.420  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{9034598: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.425  3603  3632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{63abb91 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435cdf2 5621:com.google.android.gms.persistent/u0a14}
,07-12 11:37:06.425  3603  5016 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-12 11:37:06.430  5621  5621 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
07-12 11:37:06.430  3603  5083 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:06.435  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12921f1 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5e19b0 4513:com.android.systemui/u0a60}
,07-12 11:37:06.445  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
,07-12 11:37:06.450  5099  5099 D Launcher.Model: reloadBadges entered.
,07-12 11:37:06.450 10255 10265 D MethodReflector: notifyChange is called
,07-12 11:37:06.455  5099  5099 D Launcher.Model: reloadBadges entered.
07-12 11:37:06.455 10255 10265 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-12 11:37:06.455 10255 10265 D BadgeProvider: sendNotify, [notify] : null
,07-12 11:37:06.455 10255 10265 D BadgeProvider: update, getCallingPackage() : com.android.email
07-12 11:37:06.455 10255 10265 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-12 11:37:06.455 10255 10265 D BadgeProvider: update, [uri.query] : null
07-12 11:37:06.455 10255 10265 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-12 11:37:06.455 10255 10265 D BadgeProvider: update, [UpdateCount] : 1
,07-12 11:37:06.455  8639  8639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 11:37:06.455 10597 10635 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 11:37:06.460 10423 10658 D BluetoothSocket: bindListen(): myUserId = 0
07-12 11:37:06.460 10423 10658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:37:06.460 10423 10423 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-12 11:37:06.465  4513  4513 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No network connection wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020704/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f0201d9/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-12 11:37:06.465  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:06.465  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:06.465  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:06.465  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:06.465 10618 10649 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:06.465 10618 10649 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:06.470 10618 10649 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:06.470 10255 10265 D BadgeProvider: query, [selection] : null
,07-12 11:37:06.475  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{b9cec2d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.480  3603  5114 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,07-12 11:37:06.480 10618 10649 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:06.480  8639  8639 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-12 11:37:06.485  8639  8639 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-12 11:37:06.485 10423 10658 I BtOppRfcommListener: Accept thread started.
07-12 11:37:06.485  8639  8639 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-12 11:37:06.490 10423 10660 D BluetoothSocket: bindListen(): myUserId = 0
07-12 11:37:06.490 10423 10660 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:06.490 10423 10423 D BluetoothSocket: bindListen(): myUserId = 0
07-12 11:37:06.490 10423 10423 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:06.495  3603  7152 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d83a6f 5652:com.samsung.android.providers.context/u0a11}
,07-12 11:37:06.505  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
,07-12 11:37:06.510 10423 10660 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-12 11:37:06.510 10423 10660 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-12 11:37:06.515 10423 10423 D BluetoothSocket: bindListen(): myUserId = 0
07-12 11:37:06.515 10423 10423 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:37:06.515  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{64aa947: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.520 10255 10266 D BadgeProvider: query, [selection] : null
07-12 11:37:06.520  8639  8639 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 11:37:06.520 10423 10423 D ObexServerSockets: Succeed to create listening sockets 
07-12 11:37:06.520 10423 10423 D ObexServerSockets: startAccept()
,07-12 11:37:06.520 10423 10666 D ObexServerSockets: Accepting socket connection for masId0
,07-12 11:37:06.525 10423 10667 D ObexServerSockets: Accepting socket connection for masId0
,07-12 11:37:06.525  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{f3e3a9d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.525  8639  8639 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-12 11:37:06.530 10423 10423 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-12 11:37:06.530 10423 10423 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-12 11:37:06.530 10423 10423 D BluetoothSdpJni: SDP Create record success - handle: 1
07-12 11:37:06.530  8639  8639 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 11:37:06.530  8639  8639 E BluetoothHeadset: BTStateChangeCB is registed
,07-12 11:37:06.530  8639  8639 D BluetoothMap: Create BluetoothMap proxy object
,07-12 11:37:06.540  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{9666f0c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.545  3603  5689 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10178
,07-12 11:37:06.545  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{9916ff8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.545  8639  8639 D BluetoothSap: Create BluetoothSap proxy object
,07-12 11:37:06.550  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{8ce3336: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.550  3603  4439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10178
,07-12 11:37:06.550  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{ec24cc2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.555  3603  3631 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10178
,07-12 11:37:06.555  8639  8639 D LocalBluetoothProfileManager: PANU : true
07-12 11:37:06.555  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{dec730e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.555  3603  5113 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10178
07-12 11:37:06.555  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{1e9b33c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.560  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{5e7d5e6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.560  3603  4709 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-12 11:37:06.560  8639  8639 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
07-12 11:37:06.560  8639  8639 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-12 11:37:06.560  8639  8639 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-12 11:37:06.570  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{cc65727: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.570  8639  8639 D DockEventReceiver: finishStartingService: stopping service
,07-12 11:37:06.570  8639  8639 D BluetoothNotiBroadcastReceiver: onReceive
,07-12 11:37:06.570  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{e2b2dd4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.575  8639  8639 D BluetoothA2dp: Proxy object connected
07-12 11:37:06.575  8639  8639 D A2dpProfile: Bluetooth service connected
,07-12 11:37:06.580  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5e19b0 4513:com.android.systemui/u0a60}
,07-12 11:37:06.580  4513  4513 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:37:06.580  4513  4513 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-12 11:37:06.585 10423 10433 D A2dpStateMachine: getConnectedDevices : size=0
,07-12 11:37:06.585  8639  8639 D BluetoothMap: Proxy object connected
,07-12 11:37:06.585  8639  8639 D MapProfile: Bluetooth service connected
07-12 11:37:06.585  8639  8639 D BluetoothMap: getConnectedDevices()
,07-12 11:37:06.590  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d58f9 10490:com.sec.android.widgetapp.locationwidget/u0a22}
,07-12 11:37:06.595  8639  8639 D BluetoothPbap: Proxy object connected
,07-12 11:37:06.595  8639  8639 D PbapServerProfile: Bluetooth service connected
07-12 11:37:06.595  8639  8639 D BluetoothSap: Proxy object connected
07-12 11:37:06.595  8639  8639 D SapProfile: Bluetooth service connected
07-12 11:37:06.595  8639  8639 D BluetoothInputDevice: Proxy object connected
07-12 11:37:06.595  8639  8639 D HidProfile: Bluetooth service connected
,07-12 11:37:06.595  3603  3614 I art     : Background partial concurrent mark sweep GC freed 106279(7MB) AllocSpace objects, 28(560KB) LOS objects, 33% free, 31MB/47MB, paused 2.095ms total 130.814ms
,07-12 11:37:06.600  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ec9e94 5142:com.sec.android.app.shealth:remote/u0a36}
,07-12 11:37:06.605  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{6514b7d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.610  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8a80fd0 10423:com.android.bluetooth/1002}
,07-12 11:37:06.610 10423 10423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@58d599a
07-12 11:37:06.610 10423 10423 D BtConfig.SecureMode: isSecureModeOn:false
,07-12 11:37:06.615  8639  8639 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:37:06.615  8639  8639 D PanProfile: Bluetooth service connected
,07-12 11:37:06.620  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2e7b2bf 10597:com.google.android.apps.maps/u0a131}
,07-12 11:37:06.630  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435cdf2 5621:com.google.android.gms.persistent/u0a14}
07-12 11:37:06.630  8639  8639 D HeadsetProfile: Bluetooth service connected
,07-12 11:37:06.635  5621  5621 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,07-12 11:37:06.635  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{df75340: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.635  3603  5083 I ActivityManager: Killing 9928:com.sec.android.automotive.drivelink/u0a102 (adj 15): DHA:empty #31
,07-12 11:37:06.640  3603  4446 E WifiNative-wlan0: do suspend false
,07-12 11:37:06.645  3603  4445 D WifiP2pService: InactiveState{ what=143375 }
07-12 11:37:06.645  3603  4445 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-12 11:37:06.650  5621 10676 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 11:37:06.650  3603  3631 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.automotive.drivelink, Auto Run ON
,07-12 11:37:06.660  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84111d6 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435cdf2 5621:com.google.android.gms.persistent/u0a14}
,07-12 11:37:06.665  5621  5621 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,07-12 11:37:06.675 10677 10677 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-12 11:37:06.675 10677 10677 I dhcpcd  : version 5.5.6 starting
,07-12 11:37:06.680 10677 10677 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-12 11:37:06.680  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{c436d35: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.685  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5e19b0 4513:com.android.systemui/u0a60}
,07-12 11:37:06.690  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
,07-12 11:37:06.690  8639  8639 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-12 11:37:06.690  8639  8639 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-12 11:37:06.690  3603  3631 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:06.690  8639  8639 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-12 11:37:06.690  3603  5015 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:06.695  8639  8639 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-12 11:37:06.695  8639  8639 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-12 11:37:06.695  8639  8639 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-12 11:37:06.695  8639 10556 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-12 11:37:06.705  5621 10676 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 11:37:06.715  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d18bb5 10503:com.samsung.android.snote:sync/u0a160}
,07-12 11:37:06.715 10503 10503 I ReceiverWifiStateChanged: NETWORK_STATE_CHANGED_ACTION
,07-12 11:37:06.715  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{9c44a58: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.720  3603  7152 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db78b37 7238:tv.peel.smartremote/u0a186}
,07-12 11:37:06.725  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{f4aa7b1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.730  3603  7152 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d230710 9222:com.enhance.gameservice/u0a224}
,07-12 11:37:06.745 10699 10699 E Zygote  : v2
07-12 11:37:06.745 10699 10699 I libpersona: KNOX_SDCARD checking this for 10179
07-12 11:37:06.745 10699 10699 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:06.745 10699 10699 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:06.745 10699 10699 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:06.745 10699 10699 E Zygote  : accessInfo : 0
07-12 11:37:06.745 10699 10699 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
,07-12 11:37:06.745  3603  7152 I ActivityManager: Start proc 10699:com.android.exchange/u0a179 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
,07-12 11:37:06.765 10699 10699 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:06.765 10699 10699 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:06.765  3603  3753 I ActivityManager: Start proc 10714:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
07-12 11:37:06.765 10714 10714 E Zygote  : v2
07-12 11:37:06.765 10714 10714 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:06.765 10714 10714 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:06.765 10714 10714 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:06.765 10714 10714 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:06.770 10714 10714 E Zygote  : accessInfo : 0
,07-12 11:37:06.770  3603  5113 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c78496 u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{25d5817 10699:com.android.exchange/u0a179}
,07-12 11:37:06.775  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{b5fb404: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.775 10677 10677 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:37:06.775 10677 10677 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-12 11:37:06.780 10677 10677 I dhcpcd  : bssid match
,07-12 11:37:06.780 10677 10677 I dhcpcd  : wlan0: rebinding lease of 192.168.1.113
07-12 11:37:06.780  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{fb10ded: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.780  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{2ef5422: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.785 10699 10699 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
,07-12 11:37:06.785  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{fd55eb3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.790  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{2260c70: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.795  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{9d9be9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.795 10714 10714 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:06.795 10714 10714 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:06.795  3603  5011 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:06.800  3603  5112 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2906e 10714:com.sec.android.diagmonagent/1000}
,07-12 11:37:06.810  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{5b77f9c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.815 10714 10714 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm
,07-12 11:37:06.815  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{6ab0da5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.820 10677 10677 I dhcpcd  : wlan0: acknowledged 192.168.1.113 from 192.168.1.1
,07-12 11:37:06.820  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{79b457a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.825  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{2a3f12b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.825  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{58af988: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.825  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{b63df21: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.830  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{c083f46: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.830  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{8ee7507: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.830 10714 10714 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-12 11:37:06.830  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{f9a2634: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.835  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{c7e4c5d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.835  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{9f909d2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.840  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{a735aa3: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.840  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{5cd71a0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.840  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{2d85159: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.845  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{2b9f11e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.845  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{bd6fdff: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.845  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{e2807cc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.845  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{d33aa15: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.850  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{e10012a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.850  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{da77b1b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.855  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{9b3d4b8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.855  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{ab1d291: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.855  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{90505f6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.860  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{138adf7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.860  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{e2d8464: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.860  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{11006cd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.865  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{5738b82: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.865  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{f403293: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.865  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{e7082d0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.865  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{aa342c9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.870 10677 10677 I dhcpcd  : wlan0: leased 192.168.1.113 for 172800 seconds
,07-12 11:37:06.870  3603  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
07-12 11:37:06.870  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{652ddce: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.875  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{c3164ef: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.880  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{da2fbfc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.880  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{8144285: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.885  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{4c308da: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.890  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{659610b: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.895  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{921dbe8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.900  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{1db8201: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.900  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{9d8d8a6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.905  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{9bb02e7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.905 10714 10714 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,07-12 11:37:06.905  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{52cce94: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.910  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{57d3d3d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.910  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{929d932: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
07-12 11:37:06.910 10714 10714 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,07-12 11:37:06.910 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-12 11:37:06.910 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-12 11:37:06.910 10714 10714 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
07-12 11:37:06.910 10714 10714 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything,
07-12 11:37:06.915  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{5aae683: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.920 10742 10742 E Zygote  : v2
,07-12 11:37:06.920 10742 10742 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:06.920 10742 10742 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:06.920 10742 10742 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:06.920 10742 10742 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:06.925 10742 10742 E Zygote  : accessInfo : 0
,07-12 11:37:06.925  3603  5689 I ActivityManager: Start proc 10742:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,07-12 11:37:06.925  3603  5689 I ActivityManager: Killing 9944:com.vlingo.midas/u0a34 (adj 15): DHA:empty #31
,07-12 11:37:06.935  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{8524000: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.935  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{a857039: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.945  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{818567e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.945  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{2b67df: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.950 10742 10742 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:06.950 10742 10742 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:06.950  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{19b5c2c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.955  3603  5011 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b43d6f5 10742:com.sec.knox.switcher/1000}
,07-12 11:37:06.960  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{ddf5c8a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.960  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{308a2fb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.965  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{5780f18: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.965  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{d47ed71: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.970 10742 10742 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm
,07-12 11:37:06.970  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{85eb756: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.970 10742 10742 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
07-12 11:37:06.970 10742 10742 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,07-12 11:37:06.975 10742 10742 I usagelog: received in receiver
07-12 11:37:06.975 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-12 11:37:06.975 10742 10742 I KnoxUsageLogPro: premStatus:2
07-12 11:37:06.975  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{eb473d7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.975  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{d6b04c4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:06.975 10742 10742 I KnoxUsageLogPro: isEulaShown : false
,07-12 11:37:06.975 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-12 11:37:06.985 10769 10769 E Zygote  : v2
07-12 11:37:06.985 10769 10769 I libpersona: KNOX_SDCARD checking this for 10217
,07-12 11:37:06.985 10769 10769 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:06.990 10769 10769 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-12 11:37:06.990 10769 10769 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:06.990 10769 10769 E Zygote  : accessInfo : 0
,07-12 11:37:06.990 10769 10769 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-12 11:37:06.990  3603  5084 I ActivityManager: Start proc 10769:com.samsung.android.sm.policy/u0a217 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
07-12 11:37:06.990  3603  5084 I ActivityManager: Killing 9958:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #31
,07-12 11:37:07.000  3603  3631 D ActivityManager: isAutoRunBlockedApp:: com.vlingo.midas, Auto Run ON
,07-12 11:37:07.010  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{59cefad: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.010  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{1a6f2e2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.015 10769 10769 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:07.015 10769 10769 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:07.015  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{ee27673: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.025  3603  5112 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ff9d5ca u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{675a930 10769:com.samsung.android.sm.policy/u0a217}
,07-12 11:37:07.025  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{4c5d9a9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.030  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{2455b2e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.035  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{ce406cf: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.035  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{a44285c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.040 10769 10769 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm
,07-12 11:37:07.045  3603  5016 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,07-12 11:37:07.050  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{6796765: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.055  3603  5112 I ActivityManager: Killing 9974:com.samsung.helphub/1000 (adj 15): DHA:empty #31
,07-12 11:37:07.060  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{c4ffc3a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.065  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{bc440eb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.065  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{f196e48: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.070  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{11e14e1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.070  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{b31a206: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.070  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{a2400c7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.075  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a7b26f4: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.075  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{1061e1d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.080  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{435d892: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.080  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{5d5e263: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.080  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{29dbe60: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.080  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{b6b7f19: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.085  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{3d4ebde: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.085  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{d3a41bf: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.085  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{a90608c: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.090  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{52bf3d5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.090  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{3bfe7ea: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.095  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{a5b3adb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.100  3603  5689 D ActivityManager: isAutoRunBlockedApp:: com.samsung.helphub, Auto Run ON
,07-12 11:37:07.105  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{528f978: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.105  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{944f851: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.110  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{5ac98b6: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.115  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{3c8a9b7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.115  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{ab03524: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.115  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{b0fc88d: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.120  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{ee18a42: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.120  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{f342a53: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.125  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{d4d7f90: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.125  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{3d6089: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.125  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{82088e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.130  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{1cd18af: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.135  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{83304bc: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.135  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{e927c45: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.140  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{89a1f9a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.140  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{a5c90cb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.140  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{589b0a8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.145  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{96397c1: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.145  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{7ea9b66: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.145  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{1216ea7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.150  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{71d2f54: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.150  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{ad0eefd: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.150  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{87507f2: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.155  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{96c4e43: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.155  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{dc7ecc0: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.160  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{4c27df9: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.160  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{c7b13e: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.160  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{fb8b9f: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.165  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{b9f14ec: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.165  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{5a400b5: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.170  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{9a34a: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.170  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{91742bb: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.170  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{cde93d8: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.170  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{ce0f331: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.175  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{ec6aa16: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:07.245  3603  4446 E WifiNative-wlan0: do suspend true
,07-12 11:37:07.255  3603  4445 D WifiP2pService: InactiveState{ what=143375 }
07-12 11:37:07.255  3603  4445 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-12 11:37:07.255  3603  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:37:07.255  3603  4446 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-12 11:37:07.255  3603  4446 D WifiStateMachine: VerifyingLinkState enter
07-12 11:37:07.255  3603  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
,07-12 11:37:07.260  3603  4453 E ConnectivityService: updateNetworkInfo()
,07-12 11:37:07.260  3603  4453 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,07-12 11:37:07.260  3603  3603 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-12 11:37:07.260  3603  3603 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:07.265  3603  3603 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-12 11:37:07.265  3603  4451 I WifiHs20Service: Message received 5007
07-12 11:37:07.265  3603  4466 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-12 11:37:07.265  3603  4466 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:07.265  3603  4466 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:07.265  3603  4466 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:07.265  3603  4466 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:07.265 10423 10821 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
07-12 11:37:07.265 10423 10821 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-12 11:37:07.265 10423 10821 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
07-12 11:37:07.265 10423 10821 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:252)
,07-12 11:37:07.270  3603  4446 D WifiNative-wlan0: callSECApiInt - ID [210]
07-12 11:37:07.270  3603  4453 D ConnectivityService: Adding iface wlan0 to network 502
,07-12 11:37:07.275  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2906e 10714:com.sec.android.diagmonagent/1000}
,07-12 11:37:07.275  3603  4466 I WifiManager: isCaptivePortalException
07-12 11:37:07.275 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-12 11:37:07.275  3603  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-12 11:37:07.275  3603  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-12 11:37:07.275  3603  4466 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
07-12 11:37:07.275 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-12 11:37:07.275 10714 10714 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
07-12 11:37:07.275  3603  4466 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {b20916d}
07-12 11:37:07.275  3603  4466 I WifiManager: isCaptivePortalException
07-12 11:37:07.275  3603  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-12 11:37:07.275  3603  4466 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
07-12 11:37:07.275 10714 10714 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
07-12 11:37:07.275  3603  4446 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,07-12 11:37:07.280  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5e19b0 4513:com.android.systemui/u0a60}
,07-12 11:37:07.290  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
,07-12 11:37:07.290  8639  8639 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-12 11:37:07.290  8639  8639 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-12 11:37:07.295  3603  4446 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-12 11:37:07.295  3603  4446 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:37:07.295  3603  3603 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-12 11:37:07.295  3603  3603 D WifiNative-wlan0: callSECApiVoid - ID [212]
07-12 11:37:07.295 10435 10435 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-12 11:37:07.295 10435 10435 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-12 11:37:07.300  3603  3603 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-12 11:37:07.300  3603  3603 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:07.300  3603  3603 D HS20StateMachine: SSID : "NG700"
07-12 11:37:07.300  3603  3603 D HS20StateMachine: NetId : 0
07-12 11:37:07.300  3603  3603 D HS20StateMachine: checkifOSUAP  null
07-12 11:37:07.300  3603  3603 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-12 11:37:07.300  3603  4451 I WifiHs20Service: Message received 5007
,07-12 11:37:07.305 10435 10435 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-12 11:37:07.310  3603  4453 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
07-12 11:37:07.310  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b43d6f5 10742:com.sec.knox.switcher/1000}
,07-12 11:37:07.310 10742 10742 I usagelog: received in receiver
07-12 11:37:07.310 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-12 11:37:07.310 10742 10742 I KnoxUsageLogPro: premStatus:2
07-12 11:37:07.310 10742 10742 I KnoxUsageLogPro: isEulaShown : false
07-12 11:37:07.310 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-12 11:37:07.310  3603  4453 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,07-12 11:37:07.310  3603  4453 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,07-12 11:37:07.310  3603  4453 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 11:37:07.310  3603  4453 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,07-12 11:37:07.315  3603  4453 V NetworkStats: updateIfacesLocked()
07-12 11:37:07.315  3603  4453 V NetworkStats: performPollLocked(flags=0x1)
,07-12 11:37:07.315  3603  4453 V NetworkStats: performPollLocked() took 3ms
07-12 11:37:07.315  3603  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.315  3603  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
,07-12 11:37:07.315  3603  4444 D NtpTrustedTime: forceRefresh: no connectivity
07-12 11:37:07.315  3603  4453 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.315  3603  4453 D ConnectivityService: Not required to send intent.
07-12 11:37:07.315  3603  4453 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-12 11:37:07.315  3603  4453 E ConnectivityService: updateNetworkInfo()
07-12 11:37:07.315  3603  4453 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-12 11:37:07.315  3603  4453 V NetworkStats: updateIfacesLocked()
07-12 11:37:07.315  3603  4453 V NetworkStats: performPollLocked(flags=0x1)
,07-12 11:37:07.320  3603  4453 V NetworkStats: performPollLocked() took 2ms
,07-12 11:37:07.320  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{675a930 10769:com.samsung.android.sm.policy/u0a217}
,07-12 11:37:07.325  3603  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.325  3603  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
,07-12 11:37:07.325  3603  4444 D NtpTrustedTime: forceRefresh: no connectivity
07-12 11:37:07.325  3603  4453 D ConnectivityService: scheduleUnvalidatedPrompt 502
07-12 11:37:07.325  3603  4453 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.325  3603  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-12 11:37:07.325  3603  4446 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-12 11:37:07.325  3603  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:07.325  3603  4446 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 11:37:07.325  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,07-12 11:37:07.330  3603  4453 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:07.330  5085  5097 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-12 11:37:07.330  5085  5097 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
,07-12 11:37:07.330  3603  4453 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
07-12 11:37:07.330  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d18bb5 10503:com.samsung.android.snote:sync/u0a160}
07-12 11:37:07.330 10503 10503 I ReceiverWifiStateChanged: NETWORK_STATE_CHANGED_ACTION
,07-12 11:37:07.330  3603  4453 D ConnectivityService: currentScore = 0, newScore = 20
07-12 11:37:07.330  3603  4453 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.330  3603  4453 D ConnectivityService:    accepting network in place of null
07-12 11:37:07.330  3603  4453 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.330  3603  4446 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.330  3603  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.330  3603  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:07.330  3603  4446 D WIFI    : evalRequest
07-12 11:37:07.330  3603  4446 D WIFI    :   done
07-12 11:37:07.330  3603  4446 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.330  3603  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.330  3603  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:07.330  3603  4446 D WIFI    : evalRequest
07-12 11:37:07.330  3603  4446 D WIFI    :   done
07-12 11:37:07.330  3603  4446 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.330  3603  4446 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.330  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:07.330  3603  4446 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:07.330  3603  4446 D WIFI_UT : evalRequest
07-12 11:37:07.330  3603  4446 D WIFI_UT :   done
07-12 11:37:07.330  3603  4474 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.330  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:07.330  3603  4474 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-12 11:37:07.330  3603  4474 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:07.330  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-12 11:37:07.330  3603  4474 D Ethernet: evalRequest
07-12 11:37:07.330  3603  4474 D Ethernet:   done
07-12 11:37:07.330  3603  4445 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.330  3603  4445 D WIFI_P2P:   my score=60, my filter=[ Transpo,rts: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.330  3603  4445 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:07.330  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:07.330  3603  4445 D WIFI_P2P: evalRequest
07-12 11:37:07.330  3603  4445 D WIFI_P2P:   done
07-12 11:37:07.330  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:07.330  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-12 11:37:07.335  3603  4453 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:07.340  3603 10645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:07.340  3603 10645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Connected
07-12 11:37:07.340  3603 10645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:37:07.340  3603 10645 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
,07-12 11:37:07.345  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2906e 10714:com.sec.android.diagmonagent/1000}
,07-12 11:37:07.345 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-12 11:37:07.345 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-12 11:37:07.345 10714 10714 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,07-12 11:37:07.345 10714 10714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3634 
,07-12 11:37:07.350  3603  3753 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db78b37 7238:tv.peel.smartremote/u0a186}
,07-12 11:37:07.355  2916  4375 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:37:07.355  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5e19b0 4513:com.android.systemui/u0a60}
,07-12 11:37:07.360  3603  3603 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:07.360  3603  5112 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-12 11:37:07.365  3603  5083 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{3951584 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d230710 9222:com.enhance.gameservice/u0a224}
,07-12 11:37:07.370  3603  3631 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,07-12 11:37:07.375  2916  4375 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:37:07.375  3603  4453 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,07-12 11:37:07.375  3603  5113 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,07-12 11:37:07.375  3603  3828 D EntConnectivity: Not allowed due to - mEnabled false
,07-12 11:37:07.380  3603  4553 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,07-12 11:37:07.385  4513  4513 D ViewRootImpl: #1 mView = android.widget.LinearLayout{b7a1e61 V.E...... ......I. 0,0-0,0 #10203b0 android:id/toast_layout_root}
,07-12 11:37:07.385  3603  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:07.385  3603  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.385  3603  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.385  3603  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.385  3603  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:07.390  3603  4453 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
07-12 11:37:07.390  3603  4453 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
07-12 11:37:07.390  3603  4453 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:07.390  3603  5016 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e7e37c7 8639:com.android.settings/1000}
,07-12 11:37:07.390  3603  5689 D ConnectivityService: getVpnConfig > userId : 0
07-12 11:37:07.390  8639  8639 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-12 11:37:07.390  3603  5015 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
07-12 11:37:07.390  8639  8639 I NearbySettings: MountReceiver.onReceive - Keep current state
07-12 11:37:07.390  3603  3828 D EntConnectivity: Not allowed due to - mEnabled false
07-12 11:37:07.390  3603  5015 D ISSUE_DEBUG: InputChannelName : a41d769 Toast
,07-12 11:37:07.395  3603  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:07.395  3603  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:07.395  3603  4453 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3603 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  4453 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.395  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:07.395  3603  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:07.395  3603  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-12 11:37:07.395  3603  3603 D Tethering: Tethering got CONNECTIVITY_ACTION
,07-12 11:37:07.395  3603  3828 D Tethering: MasterInitialState.processMessage what=3
07-12 11:37:07.395  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  3603 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:07.395  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  4444 D NtpTrustedTime: forceRefresh() from cache miss
07-12 11:37:07.395  3603  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.395  3603  4453 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:07.395  3603  4453 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-12 11:37:07.395  3603  4453 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] validation  passed
07-12 11:37:07.395  3603  4453 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-12 11:37:07.395  3603  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.395  3603  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:07.395  3603  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-12 11:37:07.395  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-12 11:37:07.395  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:07.395  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-12 11:37:07.400  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:07.400  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:07.400  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-12 11:37:07.400  3603  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:07.400  3603  4454 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-12 11:37:07.400  3603  4453 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:07.400  3603  5037 D NtpTrustedTime: forceRefresh() from cache miss
07-12 11:37:07.400  3603  4453 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3603 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4453 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.400  3603  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.400  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:07.400  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI    : evalRequest
07-12 11:37:07.400  3603  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI    :   done
07-12 11:37:07.400  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:07.400  3603  4446 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:07.400  3603  4446 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.400  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:07.400  3603  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI    : evalRequest
07-12 11:37:07.400  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI    :   done
07-12 11:37:07.400  3603  4453 D ConnectivityService: sending notification, CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4474 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4453 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.400  3603  4453 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  3603  4446 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-12 11:37:07.400  3603  4453 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-12 11:37:07.400  3603  4446 D WIFI_UT : evalRequest
07-12 11:37:07.405  3603  3603 V MARsPolicyManager: DataConnection: true
07-12 11:37:07.400  3603  4446 D WIFI_UT :   done
07-12 11:37:07.405  3603  5036 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:07.400  3603  4474 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-12 11:37:07.400  3603  4474 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:07.400  3603  4474 D Ethernet: evalRequest
07-12 11:37:07.400  3603  4474 D Ethernet:   done
07-12 11:37:07.400  3603  4445 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.400  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:07.400  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 1000
07-12 11:37:07.400  3603  4445 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.400  3603  4445 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-12 11:37:07.400  3603  4445 D WIFI_P2P: evalRequest
07-12 11:37:07.400  3603  4445 D WIFI_P2P:   done
07-12 11:37:07.400  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:07.400  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 1000
07-12 11:37:07.400  5085  5444 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-12 11:37:07.400  5085  5444 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-12 11:37:07.405  3603  4454 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=false
,07-12 11:37:07.410  8496  8496 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5b50f68 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 (has extras) }
,07-12 11:37:07.415  8496  8496 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
07-12 11:37:07.415  3603  5016 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b43d6f5 10742:com.sec.knox.switcher/1000}
,07-12 11:37:07.415  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:07.415  2905  2905 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
07-12 11:37:07.415 10742 10742 I usagelog: received in receiver
07-12 11:37:07.415 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-12 11:37:07.415 10742 10742 I KnoxUsageLogPro: premStatus:2
,07-12 11:37:07.420 10742 10742 I KnoxUsageLogPro: isEulaShown : false
07-12 11:37:07.420  3603  4453 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
07-12 11:37:07.420 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-12 11:37:07.420  3603  4453 D ConnectivityService: identical MTU - not setting
07-12 11:37:07.420  3603  4446 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
07-12 11:37:07.420  3603  4453 V NetworkStats: updateIfacesLocked()
07-12 11:37:07.420  3603  4446 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
07-12 11:37:07.420  3603  4453 V NetworkStats: performPollLocked(flags=0x1)
07-12 11:37:07.420  3603  4453 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:37:07.420 10354 10354 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-12 11:37:07.420 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:37:07.420 10354 10419 I jxcore-log: 
,07-12 11:37:07.425  7238  7238 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-12 11:37:07.425  3603  4453 V NetworkStats: performPollLocked() took 2ms
,07-12 11:37:07.425  3603  5083 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3603
,07-12 11:37:07.425 10354 10354 D BluetoothAdapter: STATE_ON
,07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:37:07.430 10354 10354 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 11:37:07.430 10354 10354 D BluetoothAdapter: STATE_ON
,07-12 11:37:07.430 10354 10354 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 11:37:07.435  3603  5016 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{675a930 10769:com.samsung.android.sm.policy/u0a217}
,07-12 11:37:07.435  4513  4961 D mali_winsys: new_window_surface returns 0x3000,  [1120x201]-format:1
,07-12 11:37:07.440  3603  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:07.440  3603  4453 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
,07-12 11:37:07.440  3603  4453 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.440  4513  4513 D StatusBar.NetworkController: EthernetConnected: false
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  4513  4513 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  4513  4513 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  4513  4513 D StatusBar.NetworkController: updateDataNetType()
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:07.440  4513  4513 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:07.440  4513  4513 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: Not required to send intent.
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest ,[ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.440  3603  4453 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.445  3603  4453 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:37:07.445  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{7911c: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: EthernetConnected: false
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: updateDataNetType()
07-12 11:37:07.445  4513  4513 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-12 11:37:07.445  4513  4513 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-12 11:37:07.450 10044 10846 W fb4a(:<default>):UserScope: Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
07-12 11:37:07.450 10044 10846 W fb4a(:<default>):UserScope: Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,07-12 11:37:07.450 10044 10846 W fb4a(:<default>):QeInternalImpl: The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,07-12 11:37:07.450  4513  4513 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-12 11:37:07.450  4513  4513 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
07-12 11:37:07.450  4513  4513 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-12 11:37:07.450  4513  4513 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-12 11:37:07.450  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{9178125: PendingIntentRecord{98f24e2 com.facebook.katana broadcastIntent}}
,07-12 11:37:07.455  3603  3632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6d18bb5 10503:com.samsung.android.snote:sync/u0a160}
,07-12 11:37:07.455 10503 10503 I ReceiverWifiStateChanged: NETWORK_STATE_CHANGED_ACTION
,07-12 11:37:07.455  4513  4513 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-12 11:37:07.465  3603  5114 V WindowStateAnimator: Finishing drawing window Window{a41d769 u0 d0 Toast}: mDrawState=DRAW_PENDING
,07-12 11:37:07.470  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff972fa u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d2906e 10714:com.sec.android.diagmonagent/1000}
,07-12 11:37:07.470 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
07-12 11:37:07.470 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,07-12 11:37:07.470 10714 10714 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-12 11:37:07.475 10714 10714 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(18/llllIIIllIlIIIIllllI)] timeToActivate is not set. Do not anything.
,07-12 11:37:07.475  2905  2905 D libEGL  : eglInitialize EGLDisplay = 0xbef7840c
,07-12 11:37:07.475  3603  3753 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db78b37 7238:tv.peel.smartremote/u0a186}
,07-12 11:37:07.510  3603  5016 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{cad4e33 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d230710 9222:com.enhance.gameservice/u0a224}
,07-12 11:37:07.525  3603  5037 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1468316228684 mCachedNtpElapsedRealtime : 144372 mCachedNtpCertainty : 46
07-12 11:37:07.525  3603  5037 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 11:37:07.525  3603  5037 D AlarmManager: setTime : 1468316228685 calling from uid: 1000 pid :3603
,07-12 11:37:07.525  3603  4444 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1468316228684 mCachedNtpElapsedRealtime : 144373 mCachedNtpCertainty : 46
07-12 11:37:07.525  3603  5037 D AlarmManagerService: Setting time of day to sec=1468316228
07-12 11:37:07.525  3603  5037 D AlarmManagerService: Trying to open a file
07-12 11:37:07.525  3603  5037 E AlarmManagerService: File Open Failed
,07-12 11:37:08.685  3603  5037 V AlarmManager:  remove PendingIntent] PendingIntent{d93584a: PendingIntentRecord{fdf53bb android broadcastIntent}}
07-12 11:37:08.685  3603  4401 V AlarmManager: Expired Alarm result :65536
,07-12 11:37:08.685  3603  4401 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=144376 batch.start=147021
,07-12 11:37:08.685  3603  3746 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-12 11:37:08.690  3603  3603 I CAE     : handleMessage(CaTimeChangeManager.java:159) - Time Change, auto old:true new:true
07-12 11:37:08.690  3603  3603 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1468316228694
,07-12 11:37:08.690  3603  3603 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
07-12 11:37:08.695  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
07-12 11:37:08.695  4513  4513 I PERF    : received broadcast android.intent.action.TIME_SET
07-12 11:37:08.695  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:08.695  3603  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:08.695  3603  4444 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:37:08.695  3603  4444 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-12 11:37:08.695  3603  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:08.695  3603  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:08.695  3603  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:08.695  3603  4444 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 11:37:08.695  3603  4444 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:37:08.695  3603  4444 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-12 11:37:08.700  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:37:08.700  3603  3603 V MARsPolicyManager: updateDBResetTimeForTimeChanged -- SystemTime Changed : 1154
07-12 11:37:08.700  3603  3603 V MARsPolicyManager: SystemTime Changed Less than 30 min, didn't care!!
,07-12 11:37:08.700  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:37:08.700  3603  3603 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:37:08.705  3603  3603 W System.err: java.io.FileNotFoundException: /data/drm/beforeTime.ini: open failed: EACCES (Permission denied)
,07-12 11:37:08.705  3603  3603 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 11:37:08.705  3603  3603 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:37:08.705  3603  3603 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
07-12 11:37:08.705  3603  3603 W System.err: 	at java.io.FileReader.<init>(FileReader.java:66)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.server.DrmEventService.getBeforeTime(DrmEventService.java:280)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.server.DrmEventService.handleUserUpdatedTimeUpdation(DrmEventService.java:372)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.server.DrmEventService.userUpdateHandler(DrmEventService.java:262)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.server.DrmEventService.access$200(DrmEventService.java:49)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.server.DrmEventService$3.onReceive(DrmEventService.java:413)
07-12 11:37:08.705  3603  3603 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
07-12 11:37:08.705  3603  3603 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:37:08.705  3603  3603 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:37:08.705  3603  3603 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:508)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:363)
07-12 11:37:08.705  3603  3603 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
07-12 11:37:08.705  3603  3603 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
07-12 11:37:08.705  3603  3603 W System.err: Caused by: android.system.ErrnoException: open failed: EACCES (Permission denied)
07-12 11:37:08.705  3603  3603 W System.err: 	at libcore.io.Posix.open(Native Method)
07-12 11:37:08.705  3603  3603 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 11:37:08.705  3603  3603 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 11:37:08.705  3603  3603 W System.err: 	... 17 more
07-12 11:37:08.705  3603  3603 I DrmEventService: handleUserUpdatedTimeUpdation beforeTime -100
07-12 11:37:08.705  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:08.705  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:08.705  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:08.705  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:08.705  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:08.705  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:08.705  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:08.725  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:08.725  4513  4513 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020710/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f0203cb/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0206c6/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f0206ec/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-12 11:37:08.725  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:08.730  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:08.730  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-12 11:37:08.730  4513  4513 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-12 11:37:08.740  3603  3746 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:08.740  3603  3746 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:08.740  3603  4470 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,07-12 11:37:08.765  3603  5084 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{97c5cb7 10354:com.test.thalitest/u0a7}
,07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.765  3603  7152 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:08.770  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{4228c6f: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
,07-12 11:37:08.770  3603  5084 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{758c3f9 3603:system/1000}
,07-12 11:37:08.790  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435cdf2 5621:com.google.android.gms.persistent/u0a14}
,07-12 11:37:08.795  3603  3746 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:08.795  5085  5446 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-12 11:37:08.795  5085  5446 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
07-12 11:37:08.795  3603  3746 D TelephonyManager: getDataEnabled: retVal=false
,07-12 11:37:08.805  7500 10858 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:37:08.805  5085  5445 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@5e2380e, selection=nullselectionArgs=null, sort=name ASC
,07-12 11:37:08.810  5085  5445 D TelephonyProvider: query: match = 5
,07-12 11:37:08.820  5085  5445 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,07-12 11:37:08.830  3603  3746 E GpsLocationProvider: No APN found to select.
,07-12 11:37:08.835  7500 10857 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
07-12 11:37:08.835  2953  2953 D gpsd    : WakeLock(Acquire,GPSD)
,07-12 11:37:08.840  3603  5449 D GpsLocationProvider: xtraDownloadRequest
,07-12 11:37:08.845  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:08.845  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 1021
,07-12 11:37:08.845  3603  3746 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 21244, reason: UserStart, SyncResult: databaseError: true stats []
,07-12 11:37:08.850  3603  3746 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 176528, reason: UserStart
,07-12 11:37:08.850  3603 10868 D NtpTrustedTime: getCachedNtpTime() cache hit
07-12 11:37:08.850  3603 10868 D GpsLocationProvider: NTP server returned: 1468316228684 (Tue Jul 12 11:37:08 GMT+02:00 2016) reference: 144373 certainty: 46 system time offset: -171
,07-12 11:37:08.865  7500 10861 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-12 11:37:08.865  7500 10861 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-12 11:37:08.870  3603  3631 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:08.870  3603  3631 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4195, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:37:08.870  3603  3631 D BatteryService: online:4, current avg:-292, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:-1342
07-12 11:37:08.870  3603  3631 D BatteryService: stay LED for fully charged
07-12 11:37:08.870  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:08.870  3603  3603 I MotionRecognitionService: Plugged
07-12 11:37:08.870  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:08.870  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:08.870  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:08.875 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:37:08.875 10354 10419 I jxcore-log: 
07-12 11:37:08.875  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:08.875  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:08.875  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:08.875 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:37:08.875 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:08.880  3603  5689 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-12 11:37:08.890 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:37:08.890 10354 10419 I jxcore-log: 
,07-12 11:37:08.890  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:08.890  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:08.890  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:08.895 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:37:08.895 10354 10419 I jxcore-log: 
,07-12 11:37:08.905 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:37:08.905 10354 10419 I jxcore-log: 
,07-12 11:37:08.905 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:37:08.905 10354 10419 I jxcore-log: 
,07-12 11:37:08.930  5621  5621 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:08.935  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5638dee 7500:com.google.android.gms/u0a14}
,07-12 11:37:08.935  7500 10875 I iu.SyncManager: SYNC; picasa accounts
,07-12 11:37:08.945  3603  4470 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,07-12 11:37:08.950  7500  7500 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-12 11:37:08.950  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:08.950  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-12 11:37:08.955  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{756f5f: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
,07-12 11:37:08.960  7500  7500 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:37:08.960  7500 10875 I iu.UploadsManager: num queued entries: 0
,07-12 11:37:08.960  7500 10875 I iu.UploadsManager: num updated entries: 0
,07-12 11:37:08.965  7500 10875 I iu.SyncManager: NEXT; no task
,07-12 11:37:08.975  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{c698dac: PendingIntentRecord{94902f4 com.google.android.apps.plus broadcastIntent}}
,07-12 11:37:08.975  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{123ea75: PendingIntentRecord{938aa0a com.google.android.apps.plus broadcastIntent}}
,07-12 11:37:08.985  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{eaba27b: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
,07-12 11:37:08.995  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5638dee 7500:com.google.android.gms/u0a14}
,07-12 11:37:09.010  3603  4439 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.AccountsChangedReceiver newState = 2 callingPackage = 10014
,07-12 11:37:09.020  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e86fa66 10464:com.samsung.android.keyguardwallpaperupdator/u0a127}
07-12 11:37:09.020 10464 10464 D KeyguardWallpaperUpdator: cancelUpdateWallpaper
,07-12 11:37:09.025  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{fd5b8f1: PendingIntentRecord{42953c0 com.samsung.android.keyguardwallpaperupdator broadcastIntent}}
,07-12 11:37:09.055  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{758c3f9 3603:system/1000}
,07-12 11:37:09.065 10881 10881 E Zygote  : v2
07-12 11:37:09.065 10881 10881 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:09.065 10881 10881 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:09.065 10881 10881 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.065 10881 10881 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.065 10881 10881 E Zygote  : accessInfo : 0
,07-12 11:37:09.065  3603  3753 I ActivityManager: Start proc 10881:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,07-12 11:37:09.070  3603  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d32587 7698:com.samsung.klmsagent/u0a21}
,07-12 11:37:09.075  7698  7698 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 } | timestamp: Tue Jul 12 11:37:09 GMT+02:00 2016
,07-12 11:37:09.080  3603  5015 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:09.080  4850 10893 D PicasaService: start picasa sync
,07-12 11:37:09.085  4850 10893 D PicasaService: end picasa sync
,07-12 11:37:09.085 10881 10881 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.085 10881 10881 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:09.090  7698  7698 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,07-12 11:37:09.090  7698  7698 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
07-12 11:37:09.090  7698  7698 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-12 11:37:09.095  7698  7698 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-12 11:37:09.095  7698 10895 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 }
07-12 11:37:09.095  7698 10895 D KLMS-2.6.032: : KLMSIntentService(): TIME_CHANGED
,07-12 11:37:09.095  7698 10895 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().START : Tue Jul 12 11:37:09 GMT+02:00 2016
,07-12 11:37:09.095  3603  4709 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc1b9dc 10881:com.policydm/1000}
,07-12 11:37:09.100  7698 10895 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
07-12 11:37:09.100  7698 10895 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().START
07-12 11:37:09.100  7698 10895 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,07-12 11:37:09.100  7698 10895 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().END
07-12 11:37:09.100  7698 10895 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().END
,07-12 11:37:09.105  7698  7698 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
,07-12 11:37:09.110  3603  5112 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc1b9dc 10881:com.policydm/1000}
,07-12 11:37:09.115 10881 10881 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm
,07-12 11:37:09.150 10881 10881 I FOTA    : [com.policydm.db.XDB(1493/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-12 11:37:09.185  5621  5621 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:09.185  5621  5621 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:37:09.195 10881 10881 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(54/<init>)] 
,07-12 11:37:09.195 10881 10881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:58 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:14 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:20 
,07-12 11:37:09.210 10901 10901 E Zygote  : v2
07-12 11:37:09.210 10901 10901 I libpersona: KNOX_SDCARD checking this for 10215
07-12 11:37:09.210 10901 10901 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:09.210 10901 10901 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.210 10901 10901 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.210 10901 10901 E Zygote  : accessInfo : 0
07-12 11:37:09.210 10901 10901 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,07-12 11:37:09.215  3603  5016 I ActivityManager: Start proc 10901:com.samsung.aasaservice/u0a215 for service com.samsung.aasaservice/.AASAService
,07-12 11:37:09.215 10881 10881 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-12 11:37:09.230 10881 10881 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(236/llIIIIlllllIIllIIllI)] try read dbString
,07-12 11:37:09.230  3603  5449 D GpsLocationProvider: Fail to getting Ref Locatoin. USE Ref location from listener!!!
,07-12 11:37:09.235 10881 10881 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:09.235 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-12 11:37:09.240 10881 10881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.PolicyApplication.onCreate:61 android.app.Instrumentation.callApplicationOnCreate:1036 android.app.ActivityThread.handleBindApplication:6317 
,07-12 11:37:09.240  5621 10876 I qtaguid : Tagging socket 33 with tag 1000040700000000{268436487,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:09.245 10881 10881 I DBG_POLICYDM: [com.sec.android.policyagent.PolicyApplication(64/onCreate)] PolicyApplication onCreated!
,07-12 11:37:09.245 10901 10901 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.245 10901 10901 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:09.260  5621 10876 I GCM     : GCM config loaded
,07-12 11:37:09.270 10881 10881 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:09.280 10881 10881 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:09.280 10901 10901 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-12 11:37:09.280 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-12 11:37:09.285 10901 10901 D AASAservice: onCreate()
,07-12 11:37:09.290 10881 10881 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.intent.action.TIME_SET
,07-12 11:37:09.300  3603  4553 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc1b9dc 10881:com.policydm/1000}
,07-12 11:37:09.300  3603  5011 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:09.300 10881 10922 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-12 11:37:09.305 10881 10922 I DBG_POLICYDM: [com.policydm.XDMService(382/lllIlIlIIIllIIlIllIl)] a previous network is 0, current network is 2
,07-12 11:37:09.305 10881 10922 E DBG_POLICYDM: [com.policydm.XDMService(384/lllIlIlIIIllIIlIllIl)] network changed.... 
,07-12 11:37:09.305 10881 10922 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : true
,07-12 11:37:09.305 10881 10922 I DBG_POLICYDM: [com.policydm.lllIlIlIIIllIIlIllIl(93/run)] SPD SERVICE Start!!
,07-12 11:37:09.305 10881 10922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.policydm.lllIlIlIIIllIIlIllIl.run:94 java.lang.Thread.run:818 
07-12 11:37:09.305 10881 10881 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
07-12 11:37:09.305 10881 10922 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(196/llIIIIlllllIIllIIllI)] DM Not Init
,07-12 11:37:09.310 10881 10881 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-12 11:37:09.310 10881 10881 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
07-12 11:37:09.310 10881 10922 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:09.320 10881 10881 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/07/21/06:19:17
,07-12 11:37:09.325 10881 10881 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-12 11:37:09.325 10881 10922 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:09.325 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(122/onCreate)] 
07-12 11:37:09.325 10881 10922 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : false
,07-12 11:37:09.325 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(171/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-12 11:37:09.325 10881 10881 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-12 11:37:09.330 10925 10925 E Zygote  : v2
07-12 11:37:09.330 10925 10925 I libpersona: KNOX_SDCARD checking this for 10014
07-12 11:37:09.330 10925 10925 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:09.330 10925 10925 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.330 10925 10925 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.330  3603  5011 I ActivityManager: Start proc 10925:com.google.android.gms.unstable/u0a14 for service com.google.android.gms/.droidguard.DroidGuardService
,07-12 11:37:09.330 10925 10925 E Zygote  : accessInfo : 0
07-12 11:37:09.335 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(515/IIIIllIlIIlIIIIlllIl)] 
07-12 11:37:09.335 10925 10925 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,07-12 11:37:09.335  3603  5689 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd05bdd 6386:com.android.mms/u0a52}
,07-12 11:37:09.345 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(520/IIIIllIlIIlIIIIlllIl)] m_WakeLock is acquire!!
,07-12 11:37:09.355  3603  5689 I ActivityManager: Start proc 10941:com.osp.app.signin/u0a45 for broadcast-3 com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver
,07-12 11:37:09.355 10941 10941 E Zygote  : v2
,07-12 11:37:09.355 10941 10941 I libpersona: KNOX_SDCARD checking this for 10045
07-12 11:37:09.355 10941 10941 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:09.360 10941 10941 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.360 10941 10941 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.360  9199 10867 I art     : Note: end time exceeds epoch: 
07-12 11:37:09.360 10881 10928 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-12 11:37:09.360 10881 10928 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(191/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,07-12 11:37:09.360 10941 10941 E Zygote  : accessInfo : 0
07-12 11:37:09.360 10881 10928 I DBG_POLICYDM: [IIlIlIIIlIIlIlIIIIII(146/llIIIIlllllIIllIIllI)] nSync = 0
,07-12 11:37:09.360 10941 10941 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-12 11:37:09.360 10881 10928 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-12 11:37:09.365 10881 10928 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(200/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,07-12 11:37:09.365 10881 10881 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(126/IlIIIllllIIlIIIIIlII)] 
07-12 11:37:09.365  3603  3632 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:09.365 10881 10928 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-12 11:37:09.365 10881 10928 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-12 11:37:09.365 10925 10925 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.365 10925 10925 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:09.365 10881 10928 I DBG_POLICYDM: [com.policydm.ui.IllIIIIIIlIIlIIIlIII(49/llIIIIlllllIIllIIllI)] Indicator id : 7
,07-12 11:37:09.380 10881 10881 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(160/IlIIIllllIIlIIIIIlII)] bExternalStorageAvailable [true]
,07-12 11:37:09.385 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(541/llllllIllIlIlllIIlIl)] 
07-12 11:37:09.385  9199  9199 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10147, CallingPid : 9199
,07-12 11:37:09.385 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(546/llllllIllIlIlllIIlIl)] m_WakeLock is release!!
07-12 11:37:09.385 10881 10928 I DBG_POLICYDM: [com.policydm.XDMService(572/llllIIIllIlIIIIllllI)] set NotibarState : 7
,07-12 11:37:09.385 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,07-12 11:37:09.385 10881 10928 I DBG_POLICYDM: [com.policydm.adapter.llllIIIllIlIIIIllllI(98/lllIlIlIIIllIIlIllIl)] 
,07-12 11:37:09.390  3603  3631 D ConnectivityService: listenForNetwork for Listen from uid/pid:10147/9199 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:09.390  3603  4453 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-12 11:37:09.390  3603  4453 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:37:09.390  3603  4453 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-12 11:37:09.390  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:09.390  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:09.390  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-12 11:37:09.390  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:09.390  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:09.390  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-12 11:37:09.390  3603  4453 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-12 11:37:09.390  3603  4453 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:09.390 10941 10941 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.390 10941 10941 D ActivityThread: Added TimaKeyStore provider
07-12 11:37:09.390 10881 10881 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,07-12 11:37:09.405  3603  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b559d3 10941:com.osp.app.signin/u0a45}
,07-12 11:37:09.410  3603  4709 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10147
,07-12 11:37:09.410  3603  4709 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,07-12 11:37:09.410 10881 10881 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:09.415 10881 10881 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
07-12 11:37:09.415 10881 10928 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:09.415 10881 10881 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-12 11:37:09.425 10925 10925 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:37:09.425 10925 10925 I MultiDex: install
07-12 11:37:09.425 10925 10925 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:37:09.430 10881 10881 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,07-12 11:37:09.430 10881 10881 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/07/21/06:19:17
,07-12 11:37:09.430 10881 10881 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-12 11:37:09.435 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
07-12 11:37:09.435  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:09.435  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10147
,07-12 11:37:09.435 10941 10941 W System  : ClassLoader referenced unknown path: /system/priv-app/Samsungservice2_xxxhdpi_zero/lib/arm
,07-12 11:37:09.440  3603  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b559d3 10941:com.osp.app.signin/u0a45}
,07-12 11:37:09.440 10881 10928 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:09.445 10881 10928 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(232/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,07-12 11:37:09.445 10941 10941 I SA      : [SSP] onCreated
,07-12 11:37:09.450 10881 10929 I DBG_POLICYDM: [llllIlIIIllllIIlIlll(208/llllIIIllIlIIIIllllI)] XUI_DM_IDLE_STATE :true
,07-12 11:37:09.450  3603  3632 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:09.450 10881 10929 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
07-12 11:37:09.450 10941 10941 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@6cd0990
,07-12 11:37:09.465 10925 10925 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:37:09.470 10881 10929 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-12 11:37:09.470 10881 10929 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/IIIlIIllIlIIllIlllII)] nSessionSaveState:0
,07-12 11:37:09.470 10941 10941 I SA      : [TPM] There is no property file
,07-12 11:37:09.475 10941 10941 I SA      : [SCU] isHaveSA() - false
07-12 11:37:09.475 10881 10929 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/IIIlIIllIlIIllIlllII)] nNotiUiEvent:0
,07-12 11:37:09.475 10941 10941 I SA      : [TPM] getModelProperty : null
07-12 11:37:09.475 10941 10941 I SA      : [TPM] getCSCProperty : null
,07-12 11:37:09.475 10941 10941 I SA      : [DM] FLOATING AMOLED FEATURE: true
07-12 11:37:09.475 10941 10941 I SA      : [DM] PRODUCT AMOLED FEATURE: false
07-12 11:37:09.475 10941 10941 I SA      : [DM] TFT FEATURE: false
,07-12 11:37:09.480 10881 10929 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/IIIlIIllIlIIllIlllII)] nNotiRetryCount:0
07-12 11:37:09.480 10941 10941 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
07-12 11:37:09.480 10941 10941 I SA      : [DM] init START
,07-12 11:37:09.480 10881 10929 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/IIIlIIllIlIIllIlllII)] Current NOTI NOT SAVED State. EXIT.
,07-12 11:37:09.480 10881 10929 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/IIIIlllIIIlIlIlllIII)] 
,07-12 11:37:09.480 10881 10929 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(39/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-12 11:37:09.485 10881 10929 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(453/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus : 0
07-12 11:37:09.485 10925 10925 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-12 11:37:09.485 10925 10925 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
07-12 11:37:09.485 10941 10941 I SA      : [DM] This device is not a Vodafone
,07-12 11:37:09.490 10881 10928 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(211/lllIlIlIIIllIIlIllIl)] 
,07-12 11:37:09.490 10925 10925 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:37:09.490 10881 10928 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/sepolicy
,07-12 11:37:09.490 10881 10929 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(552/llllIIIllIlIIIIllllI)] Initiated Type: 0
,07-12 11:37:09.495 10881 10928 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/seapp_contexts
,07-12 11:37:09.495 10881 10928 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/property_contexts
,07-12 11:37:09.495 10881 10928 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/file_contexts
,07-12 11:37:09.495 10881 10928 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/service_contexts
,07-12 11:37:09.495 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f060000 (t=5 e=0) (error -75)
07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f060004 (t=5 e=4) (error -75)
,07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10881 10928 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/mac_permissions.xml
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:09.500 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f06000e (t=5 e=14) (error -75)
07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
07-12 11:37:09.500 10941 10941 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,07-12 11:37:09.505 10941 10941 W ResourceType: Failure getting entry for 0x7f060012 (t=5 e=18) (error -75)
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
07-12 11:37:09.505 10941 10941 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
07-12 11:37:09.505 10941 10941 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10941 10941 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-12 11:37:09.505 10881 10928 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(235/lllIlIlIIIllIIlIllIl)] Start resumecase for INIT
,07-12 11:37:09.510 10941 10941 I SA      : [SCU] isHaveSA() - false
,07-12 11:37:09.510 10941 10941 I SA      : support phone number id : false
07-12 11:37:09.510 10941 10941 I SA      : [DM] Supports Ref Jpn : true
07-12 11:37:09.510 10941 10941 I SA      : [DM] init END
,07-12 11:37:09.510 10925 10925 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:37:09.520  3603  3631 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:09.520 10881 10929 I DBG_POLICYDM: [com.policydm.db.XDB(1781/IIIlIIllIlIIllIlllII)] 
,07-12 11:37:09.525 10881 10928 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-12 11:37:09.530 10925 10925 D ChimeraCfgMgr: Reading stored module config
,07-12 11:37:09.540  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{d7060e6: PendingIntentRecord{cd7563c com.google.android.gms broadcastIntent}}
,07-12 11:37:09.565 10941 10941 I SA      : [OR] onReceive log=[SA = 2.1.0306 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = MMB29K M = SM-N910C OKLEFT false DIS MMB29K.N910CXXU2DPE6 PSS = 5.701614807006056  ]
,07-12 11:37:09.565 10941 10941 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,07-12 11:37:09.565 10941 10941 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-12 11:37:09.565 10941 10941 I SA      : [SLFUCHKMGR] constructor called
,07-12 11:37:09.570 10881 10928 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-12 11:37:09.570 10881 10928 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-12 11:37:09.575 10881 10928 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(316/llIIllllIIlllIIIIlll)] SPD SERVICE Stop!!
,07-12 11:37:09.575 10881 10928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1311 android.content.ContextWrapper.stopService:611 com.policydm.XDMBroadcastReceiver.llIIllllIIlllIIIIlll:317 com.policydm.XDMService.llllIIIllIlIIIIllllI:288 com.policydm.XDMBroadcastReceiver.lllIlIlIIIllIIlIllIl:256 
,07-12 11:37:09.580 10973 10973 E Zygote  : v2
07-12 11:37:09.580 10973 10973 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:09.580 10973 10973 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:09.580 10973 10973 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.580 10973 10973 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.580  3603  5689 I ActivityManager: Start proc 10973:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.service.ContextAgentReceiver
07-12 11:37:09.580 10973 10973 E Zygote  : accessInfo : 0
,07-12 11:37:09.585 10941 10941 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-12 11:37:09.585 10941 10941 I SA      : [OR] == isSIMCardReady false ==
,07-12 11:37:09.590 10941 10941 I SA      : [SCU] == networkStateCheck == true
,07-12 11:37:09.595 10925 10969 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-12 11:37:09.595 10941 10941 I SA      : [DM] getCountryCodeFromCSC : PL
07-12 11:37:09.595 10881 10881 I DBG_POLICYDM: [com.policydm.XDMService(105/onDestroy)] 
07-12 11:37:09.595 10941 10941 I SA      : isChinaCountryCode : false
07-12 11:37:09.600 10941 10941 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-12 11:37:09.600 10941 10941 I SA      : [OR] == networkStateCheck true ==
,07-12 11:37:09.610 10941 10941 I SA      : [OR] GetMyCountryZoneTask
,07-12 11:37:09.610 10941 10941 I SA      : [OR] onReceive END
,07-12 11:37:09.610 10973 10973 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.610 10973 10973 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:09.615 10941 10985 I SA      : [SRS] prepareGetMyCountryZone
,07-12 11:37:09.615 10881 10929 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-12 11:37:09.620 10986 10986 E Zygote  : v2
07-12 11:37:09.620 10986 10986 I libpersona: KNOX_SDCARD checking this for 10002
07-12 11:37:09.620 10986 10986 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:09.620 10986 10986 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.620 10986 10986 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.620 10941 10985 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-12 11:37:09.620 10986 10986 E Zygote  : accessInfo : 0
07-12 11:37:09.620 10986 10986 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.cloudagent 
07-12 11:37:09.625 10941 10985 I SA      : [SSP] query invoked
,07-12 11:37:09.625  3603  3632 I ActivityManager: Start proc 10986:com.sec.android.cloudagent/u0a2 for broadcast-5 com.sec.android.cloudagent/.detector.DetectorReceiver
,07-12 11:37:09.630 10941 10985 I SA      : [TPMU] GetMccFromDB : null
07-12 11:37:09.630 10941 10985 I SA      : [SCU] getMccFromPreferece mcc = 260
07-12 11:37:09.630 10941 10985 I SA      : [LBE] isSupportCheckDomainRegion : true
07-12 11:37:09.630 10941 10985 I SA      : [TPM] isNoProxy(default) : true
,07-12 11:37:09.630  3603  3632 I ActivityManager: Killing 9987:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #31
,07-12 11:37:09.630 10881 10929 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(37/llllIIIllIlIIIIllllI)] Noti Exist : false
,07-12 11:37:09.645 10986 10986 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.645 10986 10986 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:09.645  3603  7152 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f457704 10973:com.samsung.android.sm/1000}
,07-12 11:37:09.655  3603  5015 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bef14ed 10986:com.sec.android.cloudagent/u0a2}
,07-12 11:37:09.670  5621  5621 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=e44e53b0-2aa7-4402-9850-fdeb2b7c034c
,07-12 11:37:09.685 11001 11001 E Zygote  : v2
07-12 11:37:09.685 11001 11001 I libpersona: KNOX_SDCARD checking this for 5009
07-12 11:37:09.685 11001 11001 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:09.685 11001 11001 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.685 10986 10986 W System  : ClassLoader referenced unknown path: /system/priv-app/CloudAgent/lib/arm
07-12 11:37:09.685 11001 11001 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.685  3603  3631 I ActivityManager: Start proc 11001:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
07-12 11:37:09.685 11001 11001 E Zygote  : accessInfo : 0
,07-12 11:37:09.685 11001 11001 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
,07-12 11:37:09.690  3603  3631 I ActivityManager: Killing 9999:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #31
,07-12 11:37:09.705  3603  3631 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,07-12 11:37:09.710 11001 11001 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.710 11001 11001 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:09.710  3603  6640 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-12 11:37:09.720  3603  6640 I System.out: Thread-176(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-12 11:37:09.720  3603  6640 I System.out: Thread-176(ApacheHTTPLog):isSBSettingEnabled false
07-12 11:37:09.720  3603  6640 I System.out: Thread-176(ApacheHTTPLog):isShipBuild true
07-12 11:37:09.720  3603  6640 I System.out: Thread-176(ApacheHTTPLog):getDebugLevel 0x4f4c
07-12 11:37:09.720  3603  6640 I System.out: Thread-176(ApacheHTTPLog):Smart Bonding Setting is false
07-12 11:37:09.720  3603  6640 I System.out: Thread-176(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-12 11:37:09.725  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:09.725  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-12 11:37:09.725  3603  5084 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{73020f 11001:com.samsung.android.scloud/5009}
,07-12 11:37:09.735  3603  5105 I ActivityManager: Killing 10014:com.sec.android.widgetapp.tapandpay/u0a190 (adj 15): DHA:empty #31
,07-12 11:37:09.740  3603  5105 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39e46c3 7970:com.sec.spp.push/u0a39}
,07-12 11:37:09.740  7970  7970 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:09.740 11001 11001 W System  : ClassLoader referenced unknown path: /system/priv-app/SCloudService/lib/arm
07-12 11:37:09.740  7970  7970 E SPPClientService: [SystemStateMoniter] Current Time : 145432
,07-12 11:37:09.745  2930  4380 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:10925)
,07-12 11:37:09.745  7970  7970 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-12 11:37:09.755  3603  5689 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3480a02 5855:android.process.media/u0a48}
,07-12 11:37:09.755  5855  5855 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:09.760  9199 10867 I art     : Note: end time exceeds epoch: 
,07-12 11:37:09.765  3603  5016 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,07-12 11:37:09.770  2930  4460 D WVCdm   : Instantiating CDM.
,07-12 11:37:09.775 11001 11001 I ExternalOEMControlProvider: onCreate
,07-12 11:37:09.775  2930  3934 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:10925)
07-12 11:37:09.775  2930  3934 I WVCdm   : CdmEngine::OpenSession
07-12 11:37:09.775  2930  3934 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-12 11:37:09.780  3603  5105 I ActivityManager: Killing 10028:com.sec.android.app.sbrowser/u0a156 (adj 15): DHA:empty #31
,07-12 11:37:09.785  2930  3934 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-12 11:37:09.785  2930  3934 E wv_dash : No saved usage table. Creating new table.
,07-12 11:37:09.785  3603  5083 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,07-12 11:37:09.795  3603  5113 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{598f498 6442:com.android.contacts/u0a23}
,07-12 11:37:09.805  3603  4709 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.tapandpay, Auto Run ON
,07-12 11:37:09.810  2930  3934 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,07-12 11:37:09.815  3603  7152 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sbrowser, Auto Run ON
,07-12 11:37:09.820 11001 11001 I SCloudService: onCreate
,07-12 11:37:09.840  2930  3934 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 11:37:09.840 11023 11023 E Zygote  : v2
07-12 11:37:09.840 11023 11023 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:09.840 11023 11023 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:09.840  3603  5113 I ActivityManager: Start proc 11023:com.wssyncmldm/1000 for broadcast-5 com.wssyncmldm/com.samsung.android.app.fotaclient.NetworkReceiver
07-12 11:37:09.840  2930  2930 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-12 11:37:09.840  2930  2930 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-12 11:37:09.840  2930  2930 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-12 11:37:09.840 11023 11023 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:09.840 11023 11023 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:09.840 11023 11023 E Zygote  : accessInfo : 0
,07-12 11:37:09.845  2930  2930 D WVCdm   : PrepareKeyRequest: nonce=861746234
,07-12 11:37:09.865 11023 11023 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:09.865 11023 11023 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:09.875  3603  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc2f4a5 11023:com.wssyncmldm/1000}
,07-12 11:37:09.885 11001 11001 I SCloudService: SCloudService Version Info : 1.5.06
07-12 11:37:09.885 11001 11001 I SCloudReceiver: onReceive : android.intent.action.TIME_SET
,07-12 11:37:09.895 11023 11023 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm
07-12 11:37:09.895  3603  5015 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c45c83b 9291:com.sec.android.app.shealth/u0a36}
,07-12 11:37:09.905  3603  5015 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ec9e94 5142:com.sec.android.app.shealth:remote/u0a36}
,07-12 11:37:09.915 11023 11023 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
07-12 11:37:09.915 11001 11036 E SCLOUD_ERR- Time Manager : Time Difference not stored. 
07-12 11:37:09.915 11001 11036 E SCLOUD_ERR- Time Manager : android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
07-12 11:37:09.915 11001 11036 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLongForUser(Settings.java:2031)
07-12 11:37:09.915 11001 11036 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLong(Settings.java:2021)
07-12 11:37:09.915 11001 11036 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.utils.TimeManager.updateTimeSettings(TimeManager.java:89)
07-12 11:37:09.915 11001 11036 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.receivers.SCloudReceiver$6.run(SCloudReceiver.java:202)
07-12 11:37:09.915 11001 11036 E SCLOUD_ERR- Time Manager : 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:09.915  3603  5083 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4ec9e94 5142:com.sec.android.app.shealth:remote/u0a36}
,07-12 11:37:09.930  3603  5084 I ActivityManager: Killing 10091:com.facebook.system/u0a10 (adj 15): DHA:empty #31
,07-12 11:37:09.975  5621  5875 W GCoreFlp: No location to return for getLastLocation()
,07-12 11:37:09.975 10925 10940 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:09.975 10925 10940 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:09.980  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:09.980  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-12 11:37:09.985 10925 10940 I qtaguid : Tagging socket 23 with tag 1000180300000000{268441603,0} uid -1, pid: 10925, getuid(): 10014
,07-12 11:37:09.985  3603  7152 D ActivityManager: isAutoRunBlockedApp:: com.facebook.system, Auto Run ON
,07-12 11:37:09.995  5142  5142 D HealthDataStore: Service for HealthDataStore is connected
,07-12 11:37:10.000  5142  5142 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-12 11:37:10.005  3603  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b43d6f5 10742:com.sec.knox.switcher/1000}
07-12 11:37:10.005 10742 10742 I usagelog: received in receiver
07-12 11:37:10.005 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.TIME_SET myUserId=0
07-12 11:37:10.005 10742 10742 I KnoxUsageLogPro: premStatus:2
,07-12 11:37:10.005 10742 10742 I KnoxUsageLogPro: isEulaShown : false
07-12 11:37:10.005 10742 10742 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-12 11:37:10.010 11023 11023 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(2007/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-12 11:37:10.010  5142  5142 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
07-12 11:37:10.010  5142  5142 E HealthDataStore: disconnectService: Context instance is invalid
,07-12 11:37:10.020  3603  3614 I art     : Background partial concurrent mark sweep GC freed 105270(6MB) AllocSpace objects, 15(440KB) LOS objects, 33% free, 31MB/47MB, paused 2.821ms total 119.954ms
,07-12 11:37:10.020 11047 11047 E Zygote  : v2
07-12 11:37:10.020 11047 11047 I libpersona: KNOX_SDCARD checking this for 10163
07-12 11:37:10.020 11047 11047 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:10.020 11047 11047 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:10.020 11047 11047 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.025  3603  4439 I ActivityManager: Start proc 11047:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 for broadcast-3 com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider
07-12 11:37:10.025 11047 11047 E Zygote  : accessInfo : 0
07-12 11:37:10.025 11047 11047 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.SPlannerAppWidget 
,07-12 11:37:10.055 11047 11047 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.055 11047 11047 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.065 11023 11023 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(271/llIlIIIIlIIIIIlIlIII)] Voice : true
,07-12 11:37:10.065 11023 11023 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(272/llIlIIIIlIIIIIlIlIII)] SMS : true
,07-12 11:37:10.065 11023 11023 I FOTA_AGENT: [lIIIIllIIlllIIIlIIll(273/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,07-12 11:37:10.065  3603  5113 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a502739 11047:com.sec.android.widgetapp.SPlannerAppWidget/u0a163}
,07-12 11:37:10.075 11047 11047 W System  : ClassLoader referenced unknown path: /system/app/SPlannerWidget_M_OS_UPG_Transparent/lib/arm
,07-12 11:37:10.090 11023 11023 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3203/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-12 11:37:10.090 11023 11023 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3255/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-12 11:37:10.095 11063 11063 E Zygote  : v2
07-12 11:37:10.095 11063 11063 I libpersona: KNOX_SDCARD checking this for 10164
07-12 11:37:10.095 11063 11063 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:10.095  3603  4439 I ActivityManager: Start proc 11063:com.android.calendar/u0a164 for broadcast-3 com.android.calendar/.alerts.AlertReceiver
,07-12 11:37:10.095 11063 11063 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:10.095 11063 11063 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.095 11063 11063 E Zygote  : accessInfo : 0
,07-12 11:37:10.095 11063 11063 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.calendar 
,07-12 11:37:10.100 11023 11023 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(102/onCreate)] DMApplication NOT Start !
,07-12 11:37:10.105  3603  5112 I ActivityManager: Killing 10126:com.sec.android.app.samsungapps/u0a13 (adj 15): DHA:empty #31
,07-12 11:37:10.115 11063 11063 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.115 11063 11063 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.120  2930  4460 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:10925)
07-12 11:37:10.120  2930  4460 I WVCdm   : CdmEngine::CloseSession
,07-12 11:37:10.120  5621  5898 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 11:37:10.125  7500 10894 D UdcContextInitService: registered all accounts: true
,07-12 11:37:10.125  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6676df 11063:com.android.calendar/u0a164}
,07-12 11:37:10.130 11023 11078 I FOTA_AGENT: [com.samsung.android.app.fotaclient.lllIlIlIIIllIIlIllIl(92/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:37:10.145 11063 11063 W System  : ClassLoader referenced unknown path: /system/app/SPlanner_M_OS_UPG/lib/arm
,07-12 11:37:10.145 11079 11079 E Zygote  : v2
07-12 11:37:10.145  3603  4439 I ActivityManager: Start proc 11079:com.google.android.apps.photos/u0a4 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
07-12 11:37:10.145 11079 11079 I libpersona: KNOX_SDCARD checking this for 10004
07-12 11:37:10.145 11079 11079 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:10.145 11079 11079 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-12 11:37:10.150 11079 11079 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.150 11079 11079 E Zygote  : accessInfo : 0
,07-12 11:37:10.150 11079 11079 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,07-12 11:37:10.155  9199 10867 I art     : Note: end time exceeds epoch: 
,07-12 11:37:10.160  9199 10867 I art     : Note: end time exceeds epoch: 
,07-12 11:37:10.160  3603  5114 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.samsungapps, Auto Run ON
,07-12 11:37:10.165 11079 11079 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.165 11079 11079 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.170  5621  5960 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-12 11:37:10.175  3603  5083 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{552bf2c 11079:com.google.android.apps.photos/u0a4}
,07-12 11:37:10.195 11079 11079 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 11:37:10.195  3603  4439 I ActivityManager: Killing 10108:com.facebook.appmanager/u0a110 (adj 15): DHA:empty #31
,07-12 11:37:10.205  4622  4640 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:10.235  3603  5105 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6676df 11063:com.android.calendar/u0a164}
,07-12 11:37:10.260 11099 11099 E Zygote  : v2
07-12 11:37:10.260 11099 11099 I libpersona: KNOX_SDCARD checking this for 10047
07-12 11:37:10.260 11099 11099 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:10.260  3603  4709 I ActivityManager: Start proc 11099:com.android.providers.calendar/u0a47 for content provider com.android.providers.calendar/.CalendarProvider2
,07-12 11:37:10.260 11099 11099 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:10.260 11099 11099 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.260 11099 11099 E Zygote  : accessInfo : 0
,07-12 11:37:10.260 11099 11099 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.providers.calendar 
,07-12 11:37:10.270 11110 11110 E Zygote  : v2
07-12 11:37:10.270 11110 11110 I libpersona: KNOX_SDCARD checking this for 10139
07-12 11:37:10.270 11110 11110 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:10.275 11110 11110 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:10.275 11110 11110 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.275  3603  5105 I ActivityManager: Start proc 11110:com.sec.penup/u0a139 for broadcast-3 com.sec.penup/.ui.notification.TimeFormatChangedReceiver
,07-12 11:37:10.275 11110 11110 E Zygote  : accessInfo : 0
,07-12 11:37:10.275 11110 11110 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.sec.penup 
,07-12 11:37:10.285 11099 11099 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.285 11099 11099 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.295  3603  5011 D ActivityManager: isAutoRunBlockedApp:: com.facebook.appmanager, Auto Run ON
,07-12 11:37:10.295 11110 11110 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.295 11110 11110 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.300  3603  6640 I System.out: Category Thread calls detatch()
,07-12 11:37:10.320 11099 11099 W System  : ClassLoader referenced unknown path: /system/priv-app/SecCalendarProvider/lib/arm
,07-12 11:37:10.330  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{765a1fb 11110:com.sec.penup/u0a139}
,07-12 11:37:10.335 10941 10985 I SA      : [RC New] Execute method=[GET] start
,07-12 11:37:10.335  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{56262d7: PendingIntentRecord{5f856f2 com.android.bluetooth broadcastIntent}}
,07-12 11:37:10.345 11110 11110 W System  : ClassLoader referenced unknown path: /system/app/PENUP/lib/arm
,07-12 11:37:10.360 10941 10985 I SA      : [RC New] Security=[true]
,07-12 11:37:10.360 10941 10985 I System.out: Thread-1063(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-12 11:37:10.360 10941 10985 I System.out: Thread-1063(ApacheHTTPLog):isSBSettingEnabled false
07-12 11:37:10.360 10941 10985 I System.out: Thread-1063(ApacheHTTPLog):isShipBuild true
07-12 11:37:10.360 10941 10985 I System.out: Thread-1063(ApacheHTTPLog):getDebugLevel 0x4f4c
07-12 11:37:10.360 10941 10985 I System.out: Thread-1063(ApacheHTTPLog):Smart Bonding Setting is false
07-12 11:37:10.360 10941 10985 I System.out: Thread-1063(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-12 11:37:10.360  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:10.360  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10045
,07-12 11:37:10.365  3603  5011 I ActivityManager: Killing 9688:com.android.defcontainer/u0a5 (adj 15): DHA:empty #31
,07-12 11:37:10.420  9199 10867 I art     : Note: end time exceeds epoch: 
,07-12 11:37:10.420  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:10.420  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10147
,07-12 11:37:10.445  3603  3631 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,07-12 11:37:10.455 11079 11079 W Primes  : Memory instrumentations are turned off.
,07-12 11:37:10.455 11079 11079 W Primes  : Timer instrumentations are turned off.
,07-12 11:37:10.465 11079 11079 W Primes  : Crash monitoring is turned off.
,07-12 11:37:10.465 11079 11079 W Primes  : Network monitoring is turned off.
07-12 11:37:10.465 11079 11079 W Primes  : Package metrics are turned off by default
,07-12 11:37:10.470  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{7aec148: PendingIntentRecord{9fc6be1 com.sec.penup broadcastIntent}}
,07-12 11:37:10.475 11110 11143 I GMPM    : App measurement is starting up
,07-12 11:37:10.480  3603  5015 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{552bf2c 11079:com.google.android.apps.photos/u0a4}
,07-12 11:37:10.485  3603  7152 I ActivityManager: Killing 9234:com.android.vending/u0a31 (adj 15): DHA:empty #31
,07-12 11:37:10.495 11110 11143 E GMPM    : getGoogleAppId failed with status: 10
07-12 11:37:10.495  3603  5105 I ActivityManager: Killing 9762:com.samsung.android.sm.provider/1000 (adj 15): DHA:empty #31
,07-12 11:37:10.500  3603  5105 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74f4445 8236:com.sec.android.app.SmartClipService/u0a185}
,07-12 11:37:10.500 11110 11143 E GMPM    : Uploading is not possible. App measurement disabled
,07-12 11:37:10.500  3603  3631 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:10.500  3603  5113 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:10.505  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{292a9f4: PendingIntentRecord{9fc6be1 com.sec.penup broadcastIntent}}
,07-12 11:37:10.510 10925 10940 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 10925, getuid(): 10014
,07-12 11:37:10.510 11110 11150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:10.510 11110 11150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:10.520 11156 11156 E Zygote  : v2
07-12 11:37:10.520 11156 11156 I libpersona: KNOX_SDCARD checking this for 10136
07-12 11:37:10.520  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:10.520 11156 11156 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:10.520  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10139
,07-12 11:37:10.520  3603  5105 I ActivityManager: Start proc 11156:com.google.android.apps.magazines/u0a136 for broadcast-5 com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 11:37:10.520 11156 11156 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:10.520 11156 11156 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.520 11156 11156 E Zygote  : accessInfo : 0
,07-12 11:37:10.525 11156 11156 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.magazines 
,07-12 11:37:10.525 11110 11110 D Utility : [PENUP] version : 2.0.21, code : 202100000, commit : 0000000000000000000000000000000000000000, branch : master
07-12 11:37:10.525 11110 11110 D Utility : [PENUP] density level : XXXHIGH, xdpi : 515.154, ydpi : 520.192
,07-12 11:37:10.540 11156 11156 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.540 11156 11156 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.545  3603  5113 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.provider, Auto Run ON
,07-12 11:37:10.550  3603  4439 D ActivityManager: isAutoRunBlockedApp:: com.android.vending, Auto Run ON
,07-12 11:37:10.560 11110 11110 E NotiManager: [PENUP][SERVER][Integer.java][invalidInt][138] [Invalid int: ""] [java.lang.NumberFormatException: Invalid int: ""]
,07-12 11:37:10.565  3603  3631 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{82a7160 11156:com.google.android.apps.magazines/u0a136}
,07-12 11:37:10.570  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b774745 10444:com.samsung.android.securitylogagent/1000}
,07-12 11:37:10.570 10444 10444 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-12 11:37:10.570 10444 10444 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:37:10.570 10444 10444 D SecurityLogAgent: StateMachine : Current State = 1
,07-12 11:37:10.570  3603  5011 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:10.570  3603  3632 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:10.575 11156 11156 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-12 11:37:10.580 11180 11180 E Zygote  : v2
07-12 11:37:10.580 11180 11180 I libpersona: KNOX_SDCARD checking this for 10191
07-12 11:37:10.580 11180 11180 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:10.580 11180 11180 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:10.580 11180 11180 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.585 11180 11180 E Zygote  : accessInfo : 0
,07-12 11:37:10.585 11180 11180 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.taskmanager 
,07-12 11:37:10.585  3603  5114 I ActivityManager: Start proc 11180:com.sec.android.app.taskmanager/u0a191 for broadcast-3 com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver
07-12 11:37:10.585  3603  5114 I ActivityManager: Killing 10559:com.samsung.android.app.FileShareClient/5005 (adj 15): DHA:empty #31
,07-12 11:37:10.600 11180 11180 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.600 11180 11180 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.605  3603  5084 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ddb619 11180:com.sec.android.app.taskmanager/u0a191}
,07-12 11:37:10.615 11180 11180 W System  : ClassLoader referenced unknown path: /system/app/TaskManager/lib/arm
,07-12 11:37:10.625 11193 11193 E Zygote  : v2
07-12 11:37:10.625 11193 11193 I libpersona: KNOX_SDCARD checking this for 10094
07-12 11:37:10.625 11193 11193 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:10.625 11193 11193 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:10.625 11193 11193 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:10.625 11193 11193 E Zygote  : accessInfo : 0
,07-12 11:37:10.625 11193 11193 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.clockpackage 
,07-12 11:37:10.630  3603  5105 I ActivityManager: Start proc 11193:com.sec.android.app.clockpackage/u0a94 for broadcast-3 com.sec.android.app.clockpackage/.alarm.AlarmReceiver
,07-12 11:37:10.630  3603  5105 I ActivityManager: Killing 10572:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #31
,07-12 11:37:10.635 11156 11156 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:37:10.635 11156 11156 I MultiDex: install
07-12 11:37:10.635 11156 11156 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:37:10.640  3603  5016 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareClient, Auto Run ON
,07-12 11:37:10.645 11193 11193 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:10.645 11193 11193 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:10.650  3603  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43856de 11193:com.sec.android.app.clockpackage/u0a94}
,07-12 11:37:10.665 11193 11193 W System  : ClassLoader referenced unknown path: /system/app/ClockPackage_MUPG_T/lib/arm
,07-12 11:37:10.670  9199 10867 I art     : Note: end time exceeds epoch: 
,07-12 11:37:10.675  3603  5112 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,07-12 11:37:10.695  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{428d0bf: PendingIntentRecord{7b5438c com.sec.android.app.clockpackage broadcastIntent}}
,07-12 11:37:10.700  3603  5011 D SettingsProvider: isChangeAllowed() SettingsProvider : name = next_alarm_formatted
07-12 11:37:10.700  3603  5011 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:10.700  3603  5011 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:10.700  3603  5011 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:10.700  3603  5011 D SettingsProvider: selectionArgs: false
07-12 11:37:10.700  3603  5011 D SettingsProvider: selectionArgs: 10094
,07-12 11:37:10.700  3603  5011 D SettingsProvider: ret = -1
,07-12 11:37:10.710 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:37:10.710 10354 10419 I jxcore-log: 
,07-12 11:37:10.720 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:37:10.720 10354 10419 I jxcore-log: 
,07-12 11:37:10.725 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:37:10.725 10354 10419 I jxcore-log: 
,07-12 11:37:10.745  3603  5105 I ActivityManager: Killing 10540:com.samsung.hs20provider/u0a211 (adj 15): DHA:empty #31
,07-12 11:37:10.750  3603  5105 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1622ca4 5919:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-12 11:37:10.755  5919  5919 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,07-12 11:37:10.755  5919  5919 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,07-12 11:37:10.760  3603  5105 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{524290a 4622:com.sec.android.daemonapp/u0a196}
,07-12 11:37:10.765  4622  4622 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
07-12 11:37:10.765  4622  4622 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,07-12 11:37:10.765  4622  4622 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:10.765  4622  4622 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:10.770  4622  4622 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-12 11:37:10.770  4622  4622 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,07-12 11:37:10.770  4622  4622 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:37:10.770  4622  4622 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-12 11:37:10.770  4622  4622 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:37:10.770  4622  4622 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-12 11:37:10.770  4622  4622 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
07-12 11:37:10.770  4622  4622 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:37:10.775  4622  4622 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,07-12 11:37:10.775  4622  4622 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,07-12 11:37:10.775  4622  4622 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
07-12 11:37:10.775  4622  4622 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,07-12 11:37:10.775  4622  4622 D daemonapp: [MSC_Daemon]>>> WCP:1143 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:37:10.780  4622  4622 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,07-12 11:37:10.785  3603  5689 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{524290a 4622:com.sec.android.daemonapp/u0a196}
,07-12 11:37:10.785  4622  4622 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
07-12 11:37:10.785  4622  4622 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,07-12 11:37:10.790  3603  3632 D ActivityManager: isAutoRunBlockedApp:: com.samsung.hs20provider, Auto Run ON
,07-12 11:37:10.795 11156 11156 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
07-12 11:37:10.795 11156 11156 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:37:10.795 11156 11156 I GAv4    :   adb logcat -s GAv4
,07-12 11:37:10.800  3603  4553 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5638dee 7500:com.google.android.gms/u0a14}
,07-12 11:37:10.805  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{de70f51: PendingIntentRecord{bb263b6 com.google.android.apps.magazines broadcastIntent}}
,07-12 11:37:10.810 11156 11156 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:10.810  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435cdf2 5621:com.google.android.gms.persistent/u0a14}
,07-12 11:37:10.815 11156 11156 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:10.820 11156 11213 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:10.850 10925 10940 I qtaguid : Untagging socket 23
,07-12 11:37:10.850  9199 10867 I art     : Note: end time exceeds epoch: 
,07-12 11:37:10.850  9199 10867 I art     : Note: end time exceeds epoch: 
,07-12 11:37:10.860 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:37:10.860 10354 10419 I jxcore-log: 
,07-12 11:37:10.880  3603  5084 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10147
,07-12 11:37:10.880  3603  5084 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,07-12 11:37:11.000  3603  5113 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad19529 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5638dee 7500:com.google.android.gms/u0a14}
,07-12 11:37:11.015  3603  5016 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad35fd u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{435cdf2 5621:com.google.android.gms.persistent/u0a14}
,07-12 11:37:11.025  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{ee142f2: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
,07-12 11:37:11.040 11242 11242 E Zygote  : v2
07-12 11:37:11.040 11242 11242 I libpersona: KNOX_SDCARD checking this for 10125
07-12 11:37:11.040 11242 11242 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.040 11242 11242 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.040 11242 11242 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:11.040  3603  5016 I ActivityManager: Start proc 11242:com.google.android.talk/u0a125 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
07-12 11:37:11.040 11242 11242 E Zygote  : accessInfo : 0
07-12 11:37:11.040 11242 11242 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-12 11:37:11.065 11156 11156 I NSApplication: Starting up...
,07-12 11:37:11.065 11242 11242 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.065 11242 11242 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.075  3603  5105 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{13c9c3e u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45d9a9f 11242:com.google.android.talk/u0a125}
,07-12 11:37:11.080  3603  5112 I ActivityManager: Killing 10618:com.android.email/u0a178 (adj 15): DHA:empty #31
,07-12 11:37:11.085  3603  5112 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e033c36 9199:com.google.android.apps.plus/u0a147}
,07-12 11:37:11.095 11242 11242 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-12 11:37:11.125 11265 11265 E Zygote  : v2
,07-12 11:37:11.125 11265 11265 I libpersona: KNOX_SDCARD checking this for 5011
07-12 11:37:11.125 11265 11265 I libpersona: KNOX_SDCARD not a persona
07-12 11:37:11.130 11265 11265 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.130 11265 11265 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.130  3603  5114 I ActivityManager: Start proc 11265:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,07-12 11:37:11.130 11265 11265 E Zygote  : accessInfo : 0
07-12 11:37:11.130 11265 11265 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,07-12 11:37:11.145 11265 11265 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.145 11265 11265 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.155  3603  5113 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58df516 11265:com.samsung.android.coreapps/5011}
,07-12 11:37:11.160  3603  5016 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,07-12 11:37:11.170  3603  5016 I ActivityManager: Killing 10255:com.sec.android.provider.badge/u0a82 (adj 15): DHA:empty #31
,07-12 11:37:11.175 11265 11265 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm
,07-12 11:37:11.185 11265 11265 D CoreApps: SEC_LOG - true
,07-12 11:37:11.200 11278 11278 I dex2oat : /system/bin/dex2oat --compiler-filter=speed --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-12 11:37:11.220  2953  2953 D gpsd    : WakeLock(Release,GPSD)
,07-12 11:37:11.240 11265 11265 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,07-12 11:37:11.245 11278 11278 I dex2oat : ----------------------------------------------------
07-12 11:37:11.245 11278 11278 I dex2oat : <SS>: S T A R T I N G . . .
07-12 11:37:11.245 11278 11278 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
07-12 11:37:11.245 11278 11278 I dex2oat : dex2oat took 45.174ms (threads: 4) arena alloc=285KB java alloc=55KB native alloc=1547KB free=1524KB
,07-12 11:37:11.250 10925 10940 W System  : ClassLoader referenced unknown path: 
,07-12 11:37:11.250 10925 10940 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,07-12 11:37:11.265 10925 10940 D libEGL  : eglInitialize EGLDisplay = 0xb37b4264
,07-12 11:37:11.265  3603  5084 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
,07-12 11:37:11.270 11242 11242 I Babel_telephony: TeleModule.onApplicationCreate
,07-12 11:37:11.300 10925 10940 D libEGL  : eglTerminate EGLDisplay = 0xb37b42bc
,07-12 11:37:11.310 11242 11321 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-12 11:37:11.310 11242 11321 I Babel_SMS: MmsConfig.loadMmsSettings
,07-12 11:37:11.310 11242 11321 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
07-12 11:37:11.310 11242 11321 I Babel_SMS: MmsConfig.loadFromDatabase
,07-12 11:37:11.320 10925 10940 D libEGL  : eglInitialize EGLDisplay = 0xb37b4264
,07-12 11:37:11.335 10925 10940 D libEGL  : eglTerminate EGLDisplay = 0xb37b42bc
,07-12 11:37:11.340 10925 10940 D libEGL  : eglInitialize EGLDisplay = 0xb37b4264
,07-12 11:37:11.355 10925 10940 D libEGL  : eglTerminate EGLDisplay = 0xb37b42bc
,07-12 11:37:11.370 11242 11321 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-12 11:37:11.370 11242 11321 I Babel_SMS: MmsConfig.loadFromResources
,07-12 11:37:11.370 11242 11321 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-12 11:37:11.370 11242 11321 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
,07-12 11:37:11.385 11242 11242 I Babel_Crash: Startup - clean
,07-12 11:37:11.390  3603  5114 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10125
,07-12 11:37:11.390  3603  5015 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10125
07-12 11:37:11.390 10941 10985 I SA      : [RC New] [v2liruge] api execute + 1035
07-12 11:37:11.390 10941 10985 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,07-12 11:37:11.395 10941 10985 I System.out: AsyncTask #1 calls detatch()
,07-12 11:37:11.395  3603  5689 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10125
,07-12 11:37:11.400  3603  5084 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10125
,07-12 11:37:11.400 10941 10985 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,07-12 11:37:11.400  3603  5112 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58df516 11265:com.samsung.android.coreapps/5011}
,07-12 11:37:11.405  3603  7152 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10125
,07-12 11:37:11.425 10941 10985 I SA      : [OCP] update openData : PL
,07-12 11:37:11.435  3603  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58df516 11265:com.samsung.android.coreapps/5011}
,07-12 11:37:11.435 10941 10985 I SA      : [TPMU] getNetworkMcc : 
,07-12 11:37:11.440 10941 10985 I SA      : [SCU] saveMccToPreferece Start
07-12 11:37:11.440 10941 10985 I SA      : [SCU] RegionMCC : 260
07-12 11:37:11.440 10941 10985 I SA      : [SSP] query invoked
,07-12 11:37:11.440 10941 10985 I SA      : [TPMU] GetMccFromDB : null
07-12 11:37:11.440 10941 10985 I SA      : [SCU] getMccFromPreferece mcc = 260
07-12 11:37:11.440 10941 10985 I SA      : [SCU] saveMccToPreferece End
,07-12 11:37:11.440 10941 10985 I SA      : [RC New] executeRequest [v2liruge] end. 1108
07-12 11:37:11.440 10941 10985 I SA      : [RC New] Execute end
07-12 11:37:11.440 10941 10941 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,07-12 11:37:11.440 10941 10941 I SA      : [OR] GetMyCountryZoneTask Success
,07-12 11:37:11.450 11335 11335 E Zygote  : v2
07-12 11:37:11.450 11335 11335 I libpersona: KNOX_SDCARD checking this for 10178
07-12 11:37:11.450 11335 11335 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.450 11335 11335 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.450 11335 11335 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.455  3603  4439 I ActivityManager: Start proc 11335:com.android.email/u0a178 for broadcast-5 com.android.email/.EmailConnectivityManager
07-12 11:37:11.455 11335 11335 E Zygote  : accessInfo : 0
07-12 11:37:11.455 11335 11335 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,07-12 11:37:11.460  3603  5689 I ActivityManager: Killing 10490:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): DHA:empty #31
,07-12 11:37:11.470 11335 11335 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.470 11335 11335 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.480  3603  5011 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ec4ca2 11335:com.android.email/u0a178}
,07-12 11:37:11.485 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:37:11.485 10354 10419 I jxcore-log: 
,07-12 11:37:11.485  3603  5084 I ActivityManager: Killing 10699:com.android.exchange/u0a179 (adj 15): DHA:empty #31
07-12 11:37:11.485  3603  5084 I ActivityManager: Killing 10597:com.google.android.apps.maps/u0a131 (adj 15): DHA:empty #31
,07-12 11:37:11.495  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2422d33 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{552bf2c 11079:com.google.android.apps.photos/u0a4}
,07-12 11:37:11.515  3603  5689 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.515  3603  5105 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.locationwidget, Auto Run ON
,07-12 11:37:11.525  3603  7152 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{238b41c u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{552bf2c 11079:com.google.android.apps.photos/u0a4}
,07-12 11:37:11.530 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:37:11.530 10354 10419 I jxcore-log: 
,07-12 11:37:11.535  3603  4709 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.535 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:37:11.535 10354 10419 I jxcore-log: 
,07-12 11:37:11.535  3603  3631 D ActivityManager: isAutoRunBlockedApp:: com.android.exchange, Auto Run ON
,07-12 11:37:11.540  3603  5114 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.545  3603  4553 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.maps, Auto Run ON
,07-12 11:37:11.560  3603  5083 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.570  3603  4439 I ActivityManager: Start proc 11362:com.sec.android.widgetapp.locationwidget/u0a22 for broadcast-3 com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider
,07-12 11:37:11.575 11362 11362 E Zygote  : v2
07-12 11:37:11.575 11362 11362 I libpersona: KNOX_SDCARD checking this for 10022
07-12 11:37:11.575 11362 11362 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.575 11362 11362 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.575 11362 11362 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.575 11362 11362 E Zygote  : accessInfo : 0
,07-12 11:37:11.575 11362 11362 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.locationwidget 
,07-12 11:37:11.585  5621 10899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:11.590  5621 10899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:11.590  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:11.590  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-12 11:37:11.595 11362 11362 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.595 11362 11362 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.600 11378 11378 E Zygote  : v2
07-12 11:37:11.600 11378 11378 I libpersona: KNOX_SDCARD checking this for 10082
07-12 11:37:11.600 11378 11378 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.600  3603  4553 I ActivityManager: Start proc 11378:com.sec.android.provider.badge/u0a82 for content provider com.sec.android.provider.badge/.BadgeProvider
07-12 11:37:11.600 11378 11378 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.600 11378 11378 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.605 11378 11378 E Zygote  : accessInfo : 0
,07-12 11:37:11.605 11378 11378 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,07-12 11:37:11.615  3603  3631 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c8bcfc6 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9fb87 11362:com.sec.android.widgetapp.locationwidget/u0a22}
,07-12 11:37:11.615  3603  5011 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.625  3603  5083 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.625  3603  5114 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:11.625  3603  5105 D RCPManagerService: exchangeData() failure , invalid userId
07-12 11:37:11.625 11378 11378 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.625 11378 11378 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.625  3603  5011 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.630 11362 11362 W System  : ClassLoader referenced unknown path: /system/priv-app/LocationWidget_M/lib/arm
,07-12 11:37:11.630  3603  5112 I ActivityManager: Killing 8639:com.android.settings/1000 (adj 15): DHA:empty #31
,07-12 11:37:11.635  3603  5112 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db78b37 7238:tv.peel.smartremote/u0a186}
,07-12 11:37:11.635 11335 11355 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:11.640 11362 11362 I LocationWidgetApplication: onCreate() : start
,07-12 11:37:11.640 11362 11362 D LocationWidgetApplication: countryCode = POLAND
,07-12 11:37:11.645  3603  5016 I ActivityManager: Killing 10044:com.facebook.katana/u0a114 (adj 15): DHA:empty #31
,07-12 11:37:11.645 11335 11355 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:11.645 11335 11355 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:11.655 11362 11393 D LocationWidgetUtils: getUpcommingInstances() start: 1468316231659, end: 1468879199999
07-12 11:37:11.660 11362 11393 D LocationWidgetUtils: getUpcommingInstances() DB begin time >= start:1468316231659, DB begin time <= end:1468879199999
,07-12 11:37:11.660 11378 11378 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm
,07-12 11:37:11.665  3603  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c8bcfc6 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a502739 11047:com.sec.android.widgetapp.SPlannerAppWidget/u0a163}
07-12 11:37:11.665 11378 11378 D BadgeProvider: onCreate
,07-12 11:37:11.665 11378 11378 D BadgeProvider: DatabaseHelper
,07-12 11:37:11.670 11335 11355 D skia    : ---- fAsset->read(0) returned 0
,07-12 11:37:11.680  3603  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c8bcfc6 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6676df 11063:com.android.calendar/u0a164}
,07-12 11:37:11.680  7238  7294 I System.out: Thread-480(ApacheHTTPLog):isSBSettingEnabled false
,07-12 11:37:11.680  7238  7294 I System.out: Thread-480(ApacheHTTPLog):isShipBuild true
07-12 11:37:11.680  7238  7294 I System.out: Thread-480(ApacheHTTPLog):getDebugLevel 0x4f4c
07-12 11:37:11.680  7238  7294 I System.out: Thread-480(ApacheHTTPLog):Smart Bonding Setting is false
07-12 11:37:11.680  7238  7294 I System.out: Thread-480(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-12 11:37:11.680  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:11.680  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10186
,07-12 11:37:11.690 11378 11389 D BaseReflect: null getOwnClass TEST
07-12 11:37:11.690 11378 11389 D MethodReflector: android.content.ContentResolver getClass TEST
07-12 11:37:11.690 11378 11389 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
07-12 11:37:11.690 11378 11389 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-12 11:37:11.695  3603  4709 D ActivityManager: isAutoRunBlockedApp:: com.android.settings, Auto Run ON
,07-12 11:37:11.710  3603  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1622ca4 5919:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-12 11:37:11.710  5919  5919 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-12 11:37:11.720 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:37:11.720 10354 10419 I jxcore-log: 
,07-12 11:37:11.730 11378 11389 D MethodReflector: notifyChange is called
,07-12 11:37:11.730  5099  5099 D Launcher.Model: reloadBadges entered.
07-12 11:37:11.730 11378 11389 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-12 11:37:11.735  5099  5099 D Launcher.Model: reloadBadges entered.
07-12 11:37:11.735 11378 11389 D BadgeProvider: sendNotify, [notify] : null
,07-12 11:37:11.735 11378 11389 D BadgeProvider: update, getCallingPackage() : com.android.email
07-12 11:37:11.735 11378 11389 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-12 11:37:11.735  3603  5015 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c8bcfc6 u0 android.intent.action.PROVIDER_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a6676df 11063:com.android.calendar/u0a164}
07-12 11:37:11.735 11378 11389 D BadgeProvider: update, [uri.query] : null
07-12 11:37:11.735 11378 11389 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-12 11:37:11.735 11378 11389 D BadgeProvider: update, [UpdateCount] : 1
,07-12 11:37:11.735  3603  5011 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10178
,07-12 11:37:11.740  3603  5114 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10178
,07-12 11:37:11.740 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:37:11.740 10354 10419 I jxcore-log: 
,07-12 11:37:11.740  3603  5689 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10178
,07-12 11:37:11.740 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:37:11.740 10354 10419 I jxcore-log: 
07-12 11:37:11.740  3603  5016 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10178
,07-12 11:37:11.745 11378 11389 D BadgeProvider: query, [selection] : null
,07-12 11:37:11.745 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:37:11.745 10354 10419 I jxcore-log: 
,07-12 11:37:11.750  3603  3631 D ActivityManager: isAutoRunBlockedApp:: com.facebook.katana, Auto Run ON
,07-12 11:37:11.755  5621 10899 I qtaguid : Tagging socket 43 with tag 1000040100000000{268436481,0} uid 10014, pid: 5621, getuid(): 10014
,07-12 11:37:11.760 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:37:11.760 10354 10419 I jxcore-log: 
,07-12 11:37:11.765  3603  5105 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-12 11:37:11.765  5919  5919 D accuweather: [KK AccuPhone]>>> U:4139 [0:0] getPWC : surface = 0, remote = 1
07-12 11:37:11.765  5919  5919 D accuweather: [KK AccuPhone]>>> U:4338 [0:0] Store PWC = 1
07-12 11:37:11.765  5919  5919 D accuweather: [KK AccuPhone]>>> U:4199 [0:0] addPWC = 1
07-12 11:37:11.765  5919  5919 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,07-12 11:37:11.775 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:37:11.775 10354 10419 I jxcore-log: 
,07-12 11:37:11.775  4622  4640 D daemonapp: [MSC_Daemon]>>> WCP:1255 [0:0] cp update : count : 1, pt : 1
,07-12 11:37:11.780 11406 11406 E Zygote  : v2
07-12 11:37:11.780 11406 11406 I libpersona: KNOX_SDCARD checking this for 10179
07-12 11:37:11.780 11406 11406 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.785 11406 11406 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.785 11406 11406 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.785 11406 11406 E Zygote  : accessInfo : 0
,07-12 11:37:11.785 11406 11406 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
07-12 11:37:11.785  3603  5015 I ActivityManager: Start proc 11406:com.android.exchange/u0a179 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
,07-12 11:37:11.795  5621 10899 I qtaguid : Tagging socket 48 with tag 1000040100000000{268436481,0} uid 10014, pid: 5621, getuid(): 10014
,07-12 11:37:11.800 11378 11389 D BadgeProvider: query, [selection] : null
,07-12 11:37:11.805 11406 11406 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.805 11406 11406 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.805  5919  5919 D accuweather: [KK AccuPhone]>>> U:4298 [0:0] Store PWC succeed
,07-12 11:37:11.810  3603  5015 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1622ca4 5919:com.sec.android.widgetapp.ap.hero.accuweather/u0a74}
,07-12 11:37:11.810  5919  5919 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,07-12 11:37:11.810  5919  5919 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,07-12 11:37:11.820  3603  5016 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7c3a3d9 u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0f119e 11406:com.android.exchange/u0a179}
,07-12 11:37:11.830 11422 11422 E Zygote  : v2
07-12 11:37:11.830 11422 11422 I libpersona: KNOX_SDCARD checking this for 10013
07-12 11:37:11.830 11422 11422 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.830 11422 11422 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.830 11422 11422 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-12 11:37:11.830 11406 11406 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
07-12 11:37:11.830  3603  5015 I ActivityManager: Start proc 11422:com.sec.android.app.samsungapps/u0a13 for broadcast-5 com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver
,07-12 11:37:11.830 11422 11422 E Zygote  : accessInfo : 0
07-12 11:37:11.830 11422 11422 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.android.app.samsungapps 
,07-12 11:37:11.845 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:37:11.845 10354 10419 I jxcore-log: 
,07-12 11:37:11.845  3603  5105 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:37:11.845 11422 11422 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.845 11422 11422 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.850 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:37:11.850 10354 10419 I jxcore-log: 
,07-12 11:37:11.850  3603  4709 I ActivityManager: Killing 10769:com.samsung.android.sm.policy/u0a217 (adj 15): DHA:empty #31
,07-12 11:37:11.860  3603  4553 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{339f34e u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4fcd47f 11422:com.sec.android.app.samsungapps/u0a13}
,07-12 11:37:11.870 10354 10419 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:37:11.870 10354 10419 I jxcore-log: 
,07-12 11:37:11.870  3603  3632 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc1a495 u0 com.android.widgetapp.locationwidget.cocktail.action.COCKTAIL_UPDATE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f9fb87 11362:com.sec.android.widgetapp.locationwidget/u0a22}
,07-12 11:37:11.875 11422 11422 W System  : ClassLoader referenced unknown path: /data/app/com.sec.android.app.samsungapps-2/lib/arm
,07-12 11:37:11.880 10354 10419 D BluetoothAdapter: STATE_ON
,07-12 11:37:11.880 10354 10419 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-12 11:37:11.880 10354 10419 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-12 11:37:11.880 10354 10419 I jxcore-log: 
,07-12 11:37:11.885 11362 11362 D LWLocationManager: mPrivacy is null
,07-12 11:37:11.890  3603  5016 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.policy, Auto Run ON
,07-12 11:37:11.895 11422 11422 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-12 11:37:11.900  3603  5015 I ActivityManager: Killing 10503:com.samsung.android.snote:sync/u0a160 (adj 15): DHA:empty #31
,07-12 11:37:11.905 11362 11362 D ContextFramework:PrivacyManager: Service for PrivacyManager is connected
,07-12 11:37:11.905 11362 11362 D LWLocationManager: Privacy service : STATUS_PLACE
07-12 11:37:11.905 11362 11362 D LWLocationManager: updateLocationStatus()
,07-12 11:37:11.910 11362 11362 I LocationWidgetFuctionData: readDB
,07-12 11:37:11.915 11362 11362 I LocationWidgetFuctionData: selectedAppSize: 3
07-12 11:37:11.915 11362 11362 I LocationWidgetFuctionData: configPlaceList aroundMeItems
,07-12 11:37:11.920 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 11:37:11.920 10354 10419 I jxcore-log: 
,07-12 11:37:11.920 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 11:37:11.920 10354 10419 I jxcore-log: 
,07-12 11:37:11.920 10354 10419 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:37:11.920 10354 10419 I jxcore-log: 
07-12 11:37:11.925 11443 11443 E Zygote  : v2
07-12 11:37:11.925 11443 11443 I libpersona: KNOX_SDCARD checking this for 5010
07-12 11:37:11.925 11443 11443 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:11.925 11443 11443 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:11.925 11443 11443 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:11.925 11443 11443 E Zygote  : accessInfo : 0
07-12 11:37:11.925 11443 11443 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.intelligenceservice2 
,07-12 11:37:11.925  3603  3632 I ActivityManager: Start proc 11443:com.samsung.android.intelligenceservice2/5010 for content provider com.samsung.android.intelligenceservice2/com.samsung.android.intelligenceservice.useranalysis.PlaceProvider
,07-12 11:37:11.940 11443 11443 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:11.940 11443 11443 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:11.940  3603  5083 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.snote, Auto Run ON
,07-12 11:37:11.950  3603  7152 I ActivityManager: Killing 10714:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #31
,07-12 11:37:11.965 11443 11443 W System  : ClassLoader referenced unknown path: /system/priv-app/intelligenceservice2/lib/arm
,07-12 11:37:11.965 11443 11443 D UserAnalysis.Provider: PlaceProvider onCreate()
,07-12 11:37:11.990 11443 11443 D UserAnalysis.Secu: Key for secure DB is newly created
,07-12 11:37:11.990 11443 11443 D UserAnalysis.SDBH: SecurePlaceDbHelper() 
07-12 11:37:11.990 11443 11443 D UserAnalysis: Create SecureDbHelper
,07-12 11:37:11.990  3603  5105 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,07-12 11:37:11.995 11443 11443 D UserAnalysis.App: onCreate()
,07-12 11:37:12.000 11443 11443 D UserAnalysis.App: no applications having user consent for prediction
,07-12 11:37:12.000 11443 11443 V PlaceDetection v1.0.29 : [PlaceDetection::stopService] Service stopped.
,07-12 11:37:12.005 11443 11443 V PlaceDetection v1.0.29 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-12 11:37:12.005  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{264f511: PendingIntentRecord{3cdb676 com.samsung.android.intelligenceservice2 broadcastIntent}}
,07-12 11:37:12.020 11362 11362 I LocationWidgetFuctionData: selectedAppSize: 3
,07-12 11:37:12.020 11362 11362 I LocationWidgetFuctionData: selectedAppSize: 3
,07-12 11:37:12.020 11362 11362 I LocationWidgetFuctionData: selectedAppSize: 3
07-12 11:37:12.020 11422 11422 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-12 11:37:12.020 11422 11422 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: exit::IDLE
07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: entry::NETWORK_CHECK
07-12 11:37:12.020 11362 11362 I LocationWidgetFuctionData: selectedAppSize: 3
07-12 11:37:12.020  3603  3632 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.020  3603  5114 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-12 11:37:12.020 11422 11422 D InitializeManagerStateMachine: entry::SUCCESS
07-12 11:37:12.020 11422 11422 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-12 11:37:12.025 11422 11422 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,07-12 11:37:12.025 11422 11422 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-12 11:37:12.025 11422 11422 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
07-12 11:37:12.025  3603  5084 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.025 11422 11422 D InitializeManagerStateMachine: exit::SUCCESS
07-12 11:37:12.025 11422 11422 D InitializeManagerStateMachine: entry::IDLE
,07-12 11:37:12.040  3603  5105 I ActivityManager: Killing 9222:com.enhance.gameservice/u0a224 (adj 15): DHA:empty #31
,07-12 11:37:12.045  4513  4513 D ViewRootImpl: #3 mView = null
,07-12 11:37:12.045  2905  2987 I SurfaceFlinger: id=15 Removed Uoast (8/9)
,07-12 11:37:12.045  2905  2992 I SurfaceFlinger: id=15 Removed Uoast (-2/9)
,07-12 11:37:12.045 11362 11362 E LWLocationManager: findLocationType() : cursor_location.moveToFirst() return false!!
,07-12 11:37:12.050 11362 11362 D LWLocationManager: Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
07-12 11:37:12.050 11362 11362 D LWLocationManager: setShouldUpdateLocationId
07-12 11:37:12.050 11362 11362 D LWLocationManager: setShouldUpdateLocationId return false
07-12 11:37:12.050 11362 11362 D LWLocationManager: setShouldUpdateLocationId
07-12 11:37:12.050 11362 11362 D LWLocationManager: setShouldUpdateLocationId return false
07-12 11:37:12.050 11362 11362 D LWLocationManager: setShouldUpdateLocationId
07-12 11:37:12.050 11362 11362 D LWLocationManager: setShouldUpdateLocationId return false
07-12 11:37:12.050 11362 11362 D LWLocationManager: updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,07-12 11:37:12.050  3603  5114 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3603) eventTime = 147741
,07-12 11:37:12.050  3603  5114 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3603 (0x0)
,07-12 11:37:12.050  3603  5114 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3603, ws=WorkSource{10060}) (elapsedTime=3469)
07-12 11:37:12.050  2905  2905 D libEGL  : eglTerminate EGLDisplay = 0xbef78474
,07-12 11:37:12.085  3603  5083 D ActivityManager: isAutoRunBlockedApp:: com.enhance.gameservice, Auto Run ON
,07-12 11:37:12.235 10677 10677 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:37:12.310  2916  4368 D Netd    : Iface wlan0 link up
,07-12 11:37:12.310  3603  3762 D Tethering: interfaceLinkStateChanged wlan0, true
07-12 11:37:12.310  3603  3762 D Tethering: interfaceStatusChanged wlan0, true
07-12 11:37:12.310 10435 10435 I wpa_supplicant: nl80211: Received scan results (13 BSSes)
,07-12 11:37:12.315  3603  4445 D WifiP2pService: InactiveState{ what=147461 }
07-12 11:37:12.315  3603  4445 D WifiP2pService: P2pEnabledState{ what=147461 }
07-12 11:37:12.315  3603  4445 D WifiP2pService: DefaultState{ what=147461 }
,07-12 11:37:12.325  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{112d14d: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
,07-12 11:37:12.340  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f56c402 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b5e19b0 4513:com.android.systemui/u0a60}
,07-12 11:37:12.380  5621  5960 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:12.380  5621  5960 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-12 11:37:12.385  5621  5960 V BaseAppContext: GmsRequestQueue started.
,07-12 11:37:12.390  5621  5960 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-07-12 11:37:10.264+0200, stopTime=2016-07-12 11:37:12.391+0200, duration=2127ms
,07-12 11:37:12.395  5621 11464 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:12.395  5621 11464 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:12.395  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:12.395  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-12 11:37:12.400  5621 11464 I qtaguid : Tagging socket 49 with tag 1000310500000000{268448005,0} uid 10014, pid: 5621, getuid(): 10014
,07-12 11:37:12.435  5621 11464 I qtaguid : Tagging socket 52 with tag 1000310500000000{268448005,0} uid 10014, pid: 5621, getuid(): 10014
,07-12 11:37:12.450  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{c483549: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
,07-12 11:37:12.455  3603  6622 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-12 11:37:12.610  5621 11475 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:37:12.615  5621 11473 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:37:12.625  5621 11475 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-12 11:37:12.625  5621 11473 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:37:12.640  5621 11475 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-12 11:37:12.640  5621 11473 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-12 11:37:12.640  5621 11473 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-12 11:37:12.650  5621 11473 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:12.670  7238  7294 I System.out: tr calls detatch()
,07-12 11:37:12.695  5621 11464 I qtaguid : Untagging socket 49
,07-12 11:37:12.705  5621  5960 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-12 11:37:12.770  5621 11473 W Uploader: UNKNOWN no longer exists, so no auth token.
,07-12 11:37:12.815  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:12.815  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:12.815  2916  4371 D EnterpriseController: netId is 0
07-12 11:37:12.815  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,07-12 11:37:12.845  5621 11473 I qtaguid : Tagging socket 61 with tag fffff65b00000000{4294964827,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:12.885  5621 11473 I qtaguid : Tagging socket 64 with tag fffff65b00000000{4294964827,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:13.130  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:13.130  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:13.130  5621 11473 I qtaguid : Tagging socket 61 with tag 11065c9100000000{285629585,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:13.210  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:13.210  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:13.210  5621 11473 I qtaguid : Tagging socket 61 with tag 11065c0800000000{285629448,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:13.310  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:13.310  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:13.310  5621 11473 I qtaguid : Tagging socket 61 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:13.440  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:13.440  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:13.440  5621 11473 I qtaguid : Tagging socket 61 with tag 11065fff00000000{285630463,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:13.540  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:13.540  5621 11473 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:13.540  5621 11473 I qtaguid : Tagging socket 61 with tag fffffca200000000{4294966434,0} uid -1, pid: 5621, getuid(): 10014
,07-12 11:37:13.725  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{20bc967: PendingIntentRecord{b02ead7 com.google.android.gms broadcastIntent}}
,07-12 11:37:14.545  5621 11465 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-12 11:37:14.545  5621 11465 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:37:14.545  5621 11465 I qtaguid : Tagging socket 49 with tag 1000310200000000{268448002,0} uid 10014, pid: 5621, getuid(): 10014
,07-12 11:37:14.655  3603  6622 D SSRM:n  : SIOP:: AP = 370, PST = 315 (W:10), CUR = -292, LCD = 0
,07-12 11:37:14.735  5621 11465 I qtaguid : Untagging socket 49
,07-12 11:37:14.740  5621  5960 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-12 11:37:14.780  7500  8574 V UdcCtxListenerSrv: handle intent
,07-12 11:37:15.970  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:16.240 10677 10677 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:37:16.490  3603  4453 D ConnectivityService: handlePromptUnvalidated 502
,07-12 11:37:16.495  3603  5011 I ActivityManager: Killing 10464:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 15): DHA:empty #31
,07-12 11:37:16.545  3603  3632 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.keyguardwallpaperupdator, Auto Run ON
,07-12 11:37:17.440  3603  4401 V AlarmManager: Expired Alarm result :4
,07-12 11:37:17.480  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c819503 u0 com.android.providers.calendar.intent.CalendarProvider2 qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1e58c80 11099:com.android.providers.calendar/u0a47}
,07-12 11:37:17.485 11099 11099 D CalendarProvider: [CalendarProviderBroadcastReceiver] acquire wl for com.android.providers.calendar.intent.CalendarProvider2
,07-12 11:37:17.495  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-12 11:37:17.495  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
07-12 11:37:17.495  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:17.500  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:37:17.505  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:37:17.510  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:17.510  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:17.515  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:17.515  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:17.515  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:17.515  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:37:17.515  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:37:17.545 11099 11592 D CalendarProvider: [CalendarProviderIntentService] release wl for com.android.providers.calendar.intent.CalendarProvider2
,07-12 11:37:17.615  4513  4513 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,07-12 11:37:17.975  7500  7508 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-12 11:37:19.025  3603  3631 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:37:19.025  3603  3631 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:37:19.025  3603  3631 D BatteryService: online:4, current avg:-185, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:226
07-12 11:37:19.025  3603  3631 D BatteryService: stay LED for fully charged
,07-12 11:37:19.030  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:37:19.030  3603  3603 I MotionRecognitionService: Plugged
07-12 11:37:19.030  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:19.030  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:19.030  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:19.040  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:19.040  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:19.040  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:19.055 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-12 11:37:19.055 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:19.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:19.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:19.065  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:20.245 10677 10677 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:37:20.255 10677 10677 I dhcpcd  : wlan0: no IPv6 Routers available
,07-12 11:37:21.905  5621  6501 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:37:22.060 11422 11422 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-12 11:37:22.060 11422 11422 D PreloadUpdateManagerStateMachine: exit::IDLE
,07-12 11:37:22.065 11422 11422 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-12 11:37:22.070 11422 11422 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,07-12 11:37:22.075 11422 11422 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-12 11:37:22.075 11422 11422 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-12 11:37:22.075 11422 11422 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-12 11:37:22.075 11422 11422 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-12 11:37:24.685  3603  6622 D SSRM:n  : SIOP:: AP = 330, PST = 316 (W:18), CUR = -185, LCD = 0
,07-12 11:37:26.265 11242 11304 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,07-12 11:37:26.310 11242 11318 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,07-12 11:37:26.320  3603  4709 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10125
,07-12 11:37:26.340  3603  3631 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-12 11:37:26.350 11242 11242 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-12 11:37:26.370 11242 11242 W Babel   : BAM#gBA: invalid account id: -1
07-12 11:37:26.370 11242 11242 W Babel   : BAM#gBA: invalid account id: -1
07-12 11:37:26.370 11242 11242 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-12 11:37:26.380  3603  5113 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-12 11:37:26.475 11242 11349 W Babel   : aye TOOK TOO LONG! (15001ms > 10000ms)
,07-12 11:37:29.160  3603  5016 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:37:29.160  3603  5016 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:37:29.160  3603  5016 D BatteryService: online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:212
07-12 11:37:29.160  3603  5016 D BatteryService: stay LED for fully charged
,07-12 11:37:29.165  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:37:29.170  3603  3603 I MotionRecognitionService: Plugged
,07-12 11:37:29.170  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:29.170  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:37:29.170  3603  3603 D MotionRecognitionService: skip setTransmitPower. ,
,07-12 11:37:29.175  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:29.175  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:29.180  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:29.195 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:29.195 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:29.205  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:29.205  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:29.205  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:29.945  3603  4962 E Watchdog: !@Sync 5 [07-12 11:37:29.948]
,07-12 11:37:34.715  3603  6622 D SSRM:n  : SIOP:: AP = 310, PST = 322 (W:22), CUR = 55, LCD = 0
,07-12 11:37:35.970  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:36.665  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:37:36.665  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:37:39.300  3603  3631 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:37:39.300  3603  3631 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:37:39.300  3603  3631 D BatteryService: online:4, current avg:137, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:176
07-12 11:37:39.300  3603  3631 D BatteryService: stay LED for fully charged
,07-12 11:37:39.300  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:37:39.305  3603  3603 I MotionRecognitionService: Plugged
07-12 11:37:39.305  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:39.310  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:39.310  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:39.315  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:39.315  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:39.315  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:39.335 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:37:39.335 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:39.340  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:39.340  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:39.345  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:41.170  3603  4401 V AlarmManager: Expired Alarm result :4
,07-12 11:37:41.660  7500 11687 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:37:41.660  3603  3746 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 176528, reason: UserStart, SyncResult: databaseError: true stats []
07-12 11:37:41.660  3603  3746 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 241333, reason: UserStart
,07-12 11:37:41.715  3603  5113 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-12 11:37:44.745  3603  6622 D SSRM:n  : SIOP:: AP = 300, PST = 320 (W:22), CUR = 137, LCD = 0
,07-12 11:37:45.385  3603  6623 I ActivityManager: Start proc 11694:com.samsung.android.sm.provider/1000 for content provider com.samsung.android.sm.provider/com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider
,07-12 11:37:45.395 11694 11694 E Zygote  : v2
,07-12 11:37:45.395 11694 11694 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:45.395 11694 11694 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:45.400 11694 11694 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-12 11:37:45.400 11694 11694 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:45.400 11694 11694 E Zygote  : accessInfo : 0
,07-12 11:37:45.440 11694 11694 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:45.440 11694 11694 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:45.480 11694 11694 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManagerProvider/lib/arm
,07-12 11:37:45.525  3603  3603 I ActivityManager: Killing 10901:com.samsung.aasaservice/u0a215 (adj 15): DHA:empty #31
,07-12 11:37:45.530  3603  6623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-12 11:37:45.540  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed60c29 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98ddbae 11694:com.samsung.android.sm.provider/1000}
,07-12 11:37:45.570 10881 10881 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
,07-12 11:37:45.585  3603  7152 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
07-12 11:37:45.585  3603  7152 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,07-12 11:37:45.650  3603  6623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-12 11:37:45.665  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{54ddcdc u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{98ddbae 11694:com.samsung.android.sm.provider/1000}
,07-12 11:37:46.640 11724 11724 E Zygote  : v2
07-12 11:37:46.640 11724 11724 I libpersona: KNOX_SDCARD checking this for 10215
07-12 11:37:46.640 11724 11724 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:46.645 11724 11724 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
07-12 11:37:46.645 11724 11724 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:37:46.645 11724 11724 E Zygote  : accessInfo : 0
07-12 11:37:46.645 11724 11724 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
07-12 11:37:46.645  3603  3753 I ActivityManager: Start proc 11724:com.samsung.aasaservice/u0a215 for service com.samsung.aasaservice/.AASAService
,07-12 11:37:46.690 11724 11724 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:37:46.690 11724 11724 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:46.735 11724 11724 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-12 11:37:46.740 11724 11724 D AASAservice: onCreate()
,07-12 11:37:46.745 10881 10881 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,07-12 11:37:46.745  3603  7152 I ActivityManager: Killing 10881:com.policydm/1000 (adj 15): DHA:empty #31
,07-12 11:37:46.795 11724 11724 D AASAservice: onDestroy()
07-12 11:37:46.795  3603  5105 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,07-12 11:37:46.795 11724 11724 I art     : System.exit called, status: 80
07-12 11:37:46.795 11724 11724 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,07-12 11:37:46.825  2956  2956 I Zygote  : Process 11724 exited cleanly (80)
,07-12 11:37:46.830  3603  5112 I ActivityManager: Process com.samsung.aasaservice (pid 11724)(adj 0) has died(114,1425)
,07-12 11:37:46.830  3603  5112 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,07-12 11:37:49.420  3603  3632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:37:49.420  3603  3632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:37:49.420  3603  3632 D BatteryService: online:4, current avg:160, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:175
07-12 11:37:49.420  3603  3632 D BatteryService: stay LED for fully charged
07-12 11:37:49.425  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:37:49.425  3603  3603 I MotionRecognitionService: Plugged
07-12 11:37:49.425  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:49.430  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:49.430  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:49.435  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:49.435  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:49.435  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:49.460 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:37:49.460 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:49.465  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:49.465  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:49.465  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:54.780  3603  6622 D SSRM:n  : SIOP:: AP = 300, PST = 320 (W:22), CUR = 160, LCD = 0
,07-12 11:37:55.975  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:59.565  3603  4553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:37:59.565  3603  4553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:37:59.565  3603  4553 D BatteryService: online:4, current avg:163, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:159
07-12 11:37:59.565  3603  4553 D BatteryService: stay LED for fully charged
,07-12 11:37:59.570  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:37:59.575  3603  3603 I MotionRecognitionService: Plugged
07-12 11:37:59.575  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:37:59.575  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:37:59.575  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:37:59.580  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:59.580  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:37:59.580  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:59.590  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:59.595 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:37:59.595 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:37:59.610  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:59.610  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:59.955  3603  4962 E Watchdog: !@Sync 6 [07-12 11:37:59.954]
,07-12 11:38:00.000  3603  4401 V AlarmManager: Expired Alarm result :8
,07-12 11:38:00.450  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:38:00.450  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:38:00.485  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:38:04.805  3603  6622 D SSRM:n  : SIOP:: AP = 290, PST = 320 (W:22), CUR = 163, LCD = 0
,07-12 11:38:09.695  3603  5084 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:38:09.695  3603  5084 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:38:09.695  3603  5084 D BatteryService: online:4, current avg:161, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:165
07-12 11:38:09.700  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:09.705  3603  3603 I MotionRecognitionService: Plugged
07-12 11:38:09.705  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:38:09.705  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:38:09.705  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:09.705  3603  5084 D BatteryService: stay LED for fully charged
,07-12 11:38:09.715  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:09.715  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:09.715  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:09.740 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:38:09.740 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:09.745  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:09.745  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:09.745  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:14.835  3603  6622 D SSRM:n  : SIOP:: AP = 290, PST = 318 (W:24), CUR = 161, LCD = 0
,07-12 11:38:15.260  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:38:15.260  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:38:15.975  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:19.845  3603  7152 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:38:19.845  3603  7152 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:38:19.845  3603  7152 D BatteryService: online:4, current avg:155, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:155
07-12 11:38:19.845  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:38:19.845  3603  7152 D BatteryService: stay LED for fully charged
,07-12 11:38:19.850  3603  3603 I MotionRecognitionService: Plugged
07-12 11:38:19.850  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:38:19.850  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:38:19.850  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:19.860  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:19.860  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:38:19.860  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:19.880 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:38:19.880 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:19.885  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:19.885  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:19.885  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:24.870  3603  6622 D SSRM:n  : SIOP:: AP = 290, PST = 315 (W:24), CUR = 155, LCD = 0
,07-12 11:38:29.955  3603  4962 E Watchdog: !@Sync 7 [07-12 11:38:29.958]
,07-12 11:38:29.985  3603  5112 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:38:29.985  3603  5112 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:38:29.985  3603  5112 D BatteryService: online:4, current avg:149, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:146
07-12 11:38:29.985  3603  5112 D BatteryService: stay LED for fully charged
,07-12 11:38:29.990  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:29.995  3603  3603 I MotionRecognitionService: Plugged
07-12 11:38:29.995  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:38:29.995  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:38:29.995  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:30.005  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:30.005  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:38:30.005  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:30.025 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:38:30.025 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:30.035  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:30.035  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:30.035  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:34.895  3603  6622 D SSRM:n  : SIOP:: AP = 290, PST = 314 (W:24), CUR = 149, LCD = 0
,07-12 11:38:35.980  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:40.125  3603  5689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:40.130  3603  5689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:38:40.130  3603  5689 D BatteryService: online:4, current avg:144, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:150
07-12 11:38:40.130  3603  5689 D BatteryService: stay LED for fully charged
07-12 11:38:40.130  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:40.140  3603  3603 I MotionRecognitionService: Plugged
07-12 11:38:40.140  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:38:40.140  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:38:40.140  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:40.150  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:38:40.150  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:40.150  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:40.160  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:40.165 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:40.165 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:40.175  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:40.180  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:44.305  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:38:44.305  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:38:44.930  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 312 (W:24), CUR = 144, LCD = 0
,07-12 11:38:50.265  3603  5084 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:38:50.265  3603  5084 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:38:50.265  3603  5084 D BatteryService: online:4, current avg:139, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:132
07-12 11:38:50.265  3603  5084 D BatteryService: stay LED for fully charged
,07-12 11:38:50.270  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:38:50.275  3603  3603 I MotionRecognitionService: Plugged
07-12 11:38:50.275  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:38:50.275  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:38:50.275  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:38:50.280  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:50.280  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:38:50.280  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:50.300 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:50.300 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:38:50.310  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:50.310  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:50.310  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:54.965  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 309 (W:26), CUR = 139, LCD = 0
,07-12 11:38:55.980  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:59.960  3603  4962 E Watchdog: !@Sync 8 [07-12 11:38:59.959]
,07-12 11:39:00.405  3603  7152 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:39:00.410  3603  7152 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:39:00.410  3603  7152 D BatteryService: online:4, current avg:135, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:136
07-12 11:39:00.410  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:39:00.410  3603  7152 D BatteryService: stay LED for fully charged
,07-12 11:39:00.415  3603  3603 I MotionRecognitionService: Plugged,
07-12 11:39:00.415  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:39:00.415  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:39:00.415  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:00.425  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:00.425  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:00.425  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:00.445 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:39:00.445 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:00.455  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:00.455  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:00.455  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:00.485  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:39:00.575  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:39:00.575  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:39:04.990  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 305 (W:26), CUR = 135, LCD = 0
,07-12 11:39:10.550  3603  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:39:10.550  3603  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:39:10.550  3603  5114 D BatteryService: online:4, current avg:132, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:139
07-12 11:39:10.550  3603  5114 D BatteryService: stay LED for fully charged
,07-12 11:39:10.555  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:39:10.560  3603  3603 I MotionRecognitionService: Plugged
07-12 11:39:10.560  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:39:10.560  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:39:10.560  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:10.565  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:10.565  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:10.565  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:10.585 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:39:10.585 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:10.590  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:10.590  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:10.590  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:15.035  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 303 (W:26), CUR = 132, LCD = 0
,07-12 11:39:15.985  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:20.690  3603  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:39:20.690  3603  5113 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:39:20.690  3603  5113 D BatteryService: online:4, current avg:130, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:126
07-12 11:39:20.690  3603  5113 D BatteryService: stay LED for fully charged
,07-12 11:39:20.695  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:39:20.700  3603  3603 I MotionRecognitionService: Plugged
07-12 11:39:20.700  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:39:20.700  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:39:20.700  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:20.705  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:39:20.705  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:20.705  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:20.725 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:39:20.725 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:20.735  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:20.735  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:20.735  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:25.060  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 301 (W:26), CUR = 130, LCD = 0
,07-12 11:39:29.965  3603  4962 E Watchdog: !@Sync 9 [07-12 11:39:29.966]
,07-12 11:39:30.835  3603  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:39:30.835  3603  5011 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:39:30.835  3603  5011 D BatteryService: online:4, current avg:128, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:116
07-12 11:39:30.835  3603  5011 D BatteryService: stay LED for fully charged
,07-12 11:39:30.835  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:39:30.840  3603  3603 I MotionRecognitionService: Plugged
07-12 11:39:30.840  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:39:30.840  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:39:30.840  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:30.850  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:30.850  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:30.850  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:30.870 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-12 11:39:30.870 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:30.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:30.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:30.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:35.100  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 299 (W:28), CUR = 128, LCD = 0
,07-12 11:39:35.990  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:40.970  3603  3632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:39:40.970  3603  3632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:39:40.970  3603  3632 D BatteryService: online:4, current avg:125, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:124
07-12 11:39:40.970  3603  3632 D BatteryService: stay LED for fully charged
,07-12 11:39:40.975  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:39:40.980  3603  3603 I MotionRecognitionService: Plugged
07-12 11:39:40.980  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:39:40.980  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:39:40.980  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:40.990  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:40.990  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:39:40.990  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:41.010 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:39:41.010 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:41.015  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:41.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:41.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:45.130  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 296 (W:28), CUR = 125, LCD = 0
,07-12 11:39:51.115  3603  5689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:39:51.120  3603  5689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:39:51.120  3603  5689 D BatteryService: online:4, current avg:123, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:128
07-12 11:39:51.120  3603  5689 D BatteryService: stay LED for fully charged
,07-12 11:39:51.120  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:39:51.125  3603  3603 I MotionRecognitionService: Plugged
07-12 11:39:51.125  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:39:51.125  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:39:51.125  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:39:51.135  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:51.135  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:39:51.135  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:51.150 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:39:51.150 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:39:51.160  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:51.160  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:51.160  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:55.160  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 294 (W:28), CUR = 123, LCD = 0
,07-12 11:39:55.995  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:56.550  3603  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:39:56.555  3603  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:39:56.570  3603  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:39:56.575  3603  4391 I TLC_TIMA_PKM_initialize: initializing...,
07-12 11:39:56.575  3603  4391 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-12 11:39:56.575  3603  4391 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
,07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: device_id = 0x0
07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: tlc_open() was called
,07-12 11:39:56.575  3603  4391 I TZ: mc_tlc_communication: Opening MobiCore device
07-12 11:39:56.580  3603  4391 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-12 11:39:56.585  3603  4391 I TZ: mc_tlc_communication: Opening the session,
,07-12 11:39:56.610  3603  4391 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-12 11:39:56.625  3603  4391 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-12 11:39:59.975  3603  4962 E Watchdog: !@Sync 10 [07-12 11:39:59.976]
,07-12 11:40:00.485  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:40:00.705  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:40:00.705  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:40:00.810  4978  5039 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 103ms lastUpdatedAfter : 139065ms
,07-12 11:40:03.340  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-12 11:40:03.340  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:40:03.355  3603  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-12 11:40:03.355  3603  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:40:05.190  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 292 (W:28), CUR = 123, LCD = 0
,07-12 11:40:15.220  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 290 (W:30), CUR = 123, LCD = 0
,07-12 11:40:15.995  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:21.210  3603  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:40:21.210  3603  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4379, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:40:21.210  3603  5114 D BatteryService: online:4, current avg:8, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:40:21.210  3603  5114 D BatteryService: stay LED for fully charged
07-12 11:40:21.215  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:40:21.220  3603  3603 I MotionRecognitionService: Plugged
07-12 11:40:21.220  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:40:21.220  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:40:21.220  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:40:21.225  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:40:21.225  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:40:21.230  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:40:21.250 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:40:21.250 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:40:21.260  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:40:21.260  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:40:21.260  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:25.250  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:30), CUR = 8, LCD = 0
,07-12 11:40:29.975  3603  4962 E Watchdog: !@Sync 11 [07-12 11:40:29.977]
,07-12 11:40:32.275  3603  4401 V AlarmManager: Expired Alarm result :4
,07-12 11:40:32.320 11891 11891 E Zygote  : v2
07-12 11:40:32.320 11891 11891 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:40:32.320 11891 11891 I libpersona: KNOX_SDCARD not a persona
,07-12 11:40:32.325  3603  4401 I ActivityManager: Start proc 11891:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-12 11:40:32.325 11891 11891 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
,07-12 11:40:32.325 11891 11891 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-12 11:40:32.330 11891 11891 E Zygote  : accessInfo : 0
,07-12 11:40:32.335  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-12 11:40:32.335  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
07-12 11:40:32.335  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:40:32.350  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:40:32.355  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:40:32.360  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:32.360  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:32.365  3603  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{55a0747 u0 com.google.android.apps.plus.checkandengagesync qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e033c36 9199:com.google.android.apps.plus/u0a147}
,07-12 11:40:32.365  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:32.370  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:32.370  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:32.375  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:32.375  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:32.380 11891 11891 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:40:32.380 11891 11891 D ActivityThread: Added TimaKeyStore provider
,07-12 11:40:32.420 11891 11891 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-12 11:40:32.490  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:40:35.285  3603  6622 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), CUR = 8, LCD = 0
,07-12 11:40:36.000  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:45.320  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 286 (W:30), CUR = 8, LCD = 0
,07-12 11:40:51.310  3603  5112 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:40:51.310  3603  5112 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:40:51.310  3603  5112 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:40:51.310  3603  5112 D BatteryService: stay LED for fully charged
,07-12 11:40:51.310  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:40:51.320  3603  3603 I MotionRecognitionService: Plugged
07-12 11:40:51.320  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:40:51.320  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:40:51.320  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:40:51.325  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:40:51.325  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:40:51.325  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:40:51.345 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:40:51.345 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:40:51.355  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:40:51.355  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:40:51.355  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:55.355  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 284 (W:30), LCD = 0
,07-12 11:40:56.000  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:59.980  3603  4962 E Watchdog: !@Sync 12 [07-12 11:40:59.980]
,07-12 11:41:00.000  3603  4401 V AlarmManager: Expired Alarm result :8
,07-12 11:41:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:41:00.905  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:41:00.905  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:41:05.385  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:30), LCD = 0
,07-12 11:41:10.365  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:41:10.365  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:41:15.415  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:30), LCD = 0
,07-12 11:41:16.005  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:21.405  3603  5016 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:41:21.405  3603  5016 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:41:21.405  3603  5016 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:41:21.405  3603  5016 D BatteryService: stay LED for fully charged
,07-12 11:41:21.405  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:41:21.415  3603  3603 I MotionRecognitionService: Plugged
07-12 11:41:21.415  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:41:21.415  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:41:21.415  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:41:21.420  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:41:21.420  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:41:21.420  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:41:21.440 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:41:21.440 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:41:21.445  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:41:21.450  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:21.450  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:25.445  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 281 (W:30), LCD = 0
,07-12 11:41:29.985  3603  4962 E Watchdog: !@Sync 13 [07-12 11:41:29.984]
,07-12 11:41:30.105  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:41:30.105  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:41:35.475  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:30), LCD = 0
,07-12 11:41:36.005  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:45.505  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), LCD = 0
,07-12 11:41:51.495  3603  5689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:55.535  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), LCD = 0
,07-12 11:41:56.005  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:59.990  3603  4962 E Watchdog: !@Sync 14 [07-12 11:41:59.992]
,07-12 11:42:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:42:01.025  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:42:01.025  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:42:05.565  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), LCD = 0
,07-12 11:42:10.855  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:42:10.855  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:42:15.595  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), LCD = 0
,07-12 11:42:16.010  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:42:21.595  3603  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:25.630  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-12 11:42:29.825  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:42:29.825  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:42:29.995  3603  4962 E Watchdog: !@Sync 15 [07-12 11:42:29.997]
,07-12 11:42:35.660  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), LCD = 0
,07-12 11:42:36.010  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:42:45.685  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-12 11:42:48.965  2980  2980 I bootchecker: bootchecker wake up!!
,07-12 11:42:51.695  3603  5016 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:55.715  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-12 11:42:56.015  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:00.000  3603  4962 E Watchdog: !@Sync 16 [07-12 11:43:00.002]
,07-12 11:43:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:43:01.140  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:43:01.140  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:43:01.215  4978  5039 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 67ms lastUpdatedAfter : 180405ms
,07-12 11:43:05.755  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), LCD = 0
,07-12 11:43:15.785  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-12 11:43:16.015  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:21.790  3603  3631 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:43:21.790  3603  3631 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:43:21.790  3603  3631 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:43:21.790  3603  3631 D BatteryService: stay LED for fully charged
,07-12 11:43:21.790  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:43:21.805  3603  3603 I MotionRecognitionService: Plugged
07-12 11:43:21.805  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:43:21.805  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:43:21.805  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:43:21.810  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:43:21.810  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:43:21.810  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:43:21.820  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:21.825 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:43:21.825 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:43:21.835  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:43:21.835  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:25.815  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-12 11:43:30.005  3603  4962 E Watchdog: !@Sync 17 [07-12 11:43:30.006]
,07-12 11:43:35.845  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), LCD = 0
,07-12 11:43:36.020  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:45.870  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-12 11:43:51.875  3603  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:43:51.875  3603  5114 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:43:51.875  3603  5114 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:43:51.875  3603  5114 D BatteryService: stay LED for fully charged
,07-12 11:43:51.875  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:43:51.880  3603  3603 I MotionRecognitionService: Plugged
07-12 11:43:51.880  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:43:51.880  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:43:51.880  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:43:51.890  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:43:51.890  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:43:51.890  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:43:51.910 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:43:51.910 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:43:51.915  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:43:51.915  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:43:51.915  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:55.905  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-12 11:43:56.020  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:00.010  3603  4962 E Watchdog: !@Sync 18 [07-12 11:44:00.010]
,07-12 11:44:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:44:01.325  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:44:01.325  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:44:05.935  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), LCD = 0
,07-12 11:44:15.960  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-12 11:44:16.025  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:21.965  3603  3632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:44:21.970  3603  3632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:44:21.970  3603  3632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:44:21.970  3603  3632 D BatteryService: stay LED for fully charged
,07-12 11:44:21.970  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:44:21.975  3603  3603 I MotionRecognitionService: Plugged
07-12 11:44:21.975  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:44:21.975  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-12 11:44:21.975  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:44:21.985  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:44:21.985  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:44:21.990  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:44:21.990  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:22.000 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:44:22.000 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:44:22.010  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:44:22.010  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:25.995  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-12 11:44:30.020  3603  4962 E Watchdog: !@Sync 19 [07-12 11:44:30.019]
,07-12 11:44:36.020  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), LCD = 0
,07-12 11:44:36.025  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:46.050  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-12 11:44:52.065  3603  5015 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:56.030  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:56.080  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-12 11:44:56.550  3603  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
07-12 11:44:56.550  3603  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:44:56.555  3603  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:45:00.025  3603  4962 E Watchdog: !@Sync 20 [07-12 11:45:00.026]
,07-12 11:45:00.055  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-12 11:45:00.055  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:45:00.070  3603  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-12 11:45:00.075  3603  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:45:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:45:01.470  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:45:01.470  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLock,ed: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10064, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10073, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10080, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10094, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10120, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10131, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10133, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10156, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.515  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10206, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10217, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10218, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10219, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10220, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10222, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-12 11:45:02.520  3603  3746 D NetworkPolicy: isUidForegroundLocked: 10224, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-12 11:45:02.820  3603  3829 I ActivityManager: setMaxStartingBackgroundTimer onfinish
07-12 11:45:02.820  3603  3829 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-12 11:45:06.115  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:30), LCD = 0
,07-12 11:45:16.030  3603  6685 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:45:16.140  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:45:22.165  3603  5084 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:45:22.165  3603  5084 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:45:22.165  3603  5084 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:45:22.165  3603  5084 D BatteryService: stay LED for fully charged
,07-12 11:45:22.165  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:45:22.175  3603  3603 I MotionRecognitionService: Plugged
07-12 11:45:22.175  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:45:22.175  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:45:22.175  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:45:22.180  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:45:22.180  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:45:22.185  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:45:22.205 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-12 11:45:22.205 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:45:22.210  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:45:22.210  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:45:22.210  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:26.175  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:45:30.035  3603  4962 E Watchdog: !@Sync 21 [07-12 11:45:30.035]
,07-12 11:45:33.090  3603  4401 V AlarmManager: Expired Alarm result :8
,07-12 11:45:36.210  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:45:46.240  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:45:52.255  3603  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:45:52.255  3603  4439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:45:52.255  3603  4439 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:45:52.255  3603  4439 D BatteryService: stay LED for fully charged
,07-12 11:45:52.260  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:45:52.260  3603  3603 I MotionRecognitionService: Plugged
07-12 11:45:52.260  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:45:52.260  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:45:52.260  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:45:52.270  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:45:52.270  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:45:52.270  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:45:52.290 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:45:52.290 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:45:52.300  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:45:52.300  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:45:52.300  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:56.270  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:46:00.040  3603  4962 E Watchdog: !@Sync 22 [07-12 11:46:00.043]
,07-12 11:46:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:46:01.600  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:46:01.600  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:46:01.680  4978  5039 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 73ms lastUpdatedAfter : 180465ms
,07-12 11:46:06.305  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:46:16.330  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:46:22.350  3603  5105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:46:22.355  3603  5105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:46:22.355  3603  5105 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:46:22.355  3603  5105 D BatteryService: stay LED for fully charged
,07-12 11:46:22.355  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:46:22.360  3603  3603 I MotionRecognitionService: Plugged
07-12 11:46:22.360  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:46:22.360  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:46:22.360  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:46:22.370  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:46:22.370  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:46:22.370  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:46:22.390 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-12 11:46:22.390 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:46:22.395  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:46:22.395  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:46:22.400  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:26.360  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:46:30.045  3603  4962 E Watchdog: !@Sync 23 [07-12 11:46:30.048]
,07-12 11:46:36.390  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:46:46.415  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:46:52.445  3603  5114 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:56.440  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:47:00.050  3603  4962 E Watchdog: !@Sync 24 [07-12 11:47:00.053]
,07-12 11:47:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:47:01.800  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:47:01.800  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:47:06.475  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:47:16.505  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:47:22.540  3603  5105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:47:22.540  3603  5105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:47:22.540  3603  5105 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:47:22.540  3603  5105 D BatteryService: stay LED for fully charged
,07-12 11:47:22.545  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:47:22.550  3603  3603 I MotionRecognitionService: Plugged
07-12 11:47:22.550  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:47:22.550  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:47:22.550  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:47:22.555  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:47:22.555  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:47:22.555  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:47:22.580 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:47:22.580 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:47:22.585  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:47:22.585  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:47:22.585  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:26.535  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:30), LCD = 0
,07-12 11:47:30.055  3603  4962 E Watchdog: !@Sync 25 [07-12 11:47:30.057]
,07-12 11:47:36.560  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), LCD = 0
,07-12 11:47:46.590  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), LCD = 0
,07-12 11:47:52.640  3603  5113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:47:52.640  3603  5113 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:47:52.640  3603  5113 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:47:52.640  3603  5113 D BatteryService: stay LED for fully charged
,07-12 11:47:52.640  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:47:52.645  3603  3603 I MotionRecognitionService: Plugged
07-12 11:47:52.645  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:47:52.650  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:47:52.650  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:47:52.655  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:47:52.655  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:47:52.655  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:47:52.680 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:47:52.685  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:47:52.680 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-12 11:47:52.685  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:47:52.685  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:53.270  3603  3614 I art     : Background sticky concurrent mark sweep GC freed 79528(8MB) AllocSpace objects, 327(6MB) LOS objects, 32% free, 31MB/46MB, paused 3.467ms total 101.073ms
,07-12 11:47:56.630  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:30), LCD = 0
,07-12 11:48:00.060  3603  4962 E Watchdog: !@Sync 26 [07-12 11:48:00.061]
,07-12 11:48:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:48:01.910  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:48:01.910  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:48:02.780  3603  5694 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
07-12 11:48:02.780  3603  5694 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
07-12 11:48:02.780  3603  5694 V MARsPolicyManager: updateSMDBValues
,07-12 11:48:02.785  3603  3825 E MARsDBManager: updateDBAll : begin --size 0,
,07-12 11:48:02.785  3603  3825 E MARsDBManager: updateDBAll : end
,07-12 11:48:06.655  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), LCD = 0
,07-12 11:48:16.690  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), LCD = 0
,07-12 11:48:22.785  3603  3632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:48:22.790  3603  3632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:48:22.790  3603  3632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:48:22.790  3603  3632 D BatteryService: stay LED for fully charged
,07-12 11:48:22.790  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:48:22.795  3603  3603 I MotionRecognitionService: Plugged
07-12 11:48:22.795  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:48:22.795  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:48:22.795  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:48:22.805  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:48:22.805  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:48:22.805  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:48:22.810  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:22.815 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:48:22.815 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:48:22.830  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:48:22.830  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:26.725  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:30), LCD = 0
,07-12 11:48:30.065  3603  4962 E Watchdog: !@Sync 27 [07-12 11:48:30.068]
,07-12 11:48:36.750  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), LCD = 0
,07-12 11:48:46.780  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), LCD = 0
,07-12 11:48:52.880  3603  5084 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:48:52.880  3603  5084 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:48:52.880  3603  5084 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:48:52.880  3603  5084 D BatteryService: stay LED for fully charged
,07-12 11:48:52.885  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:48:52.885  3603  3603 I MotionRecognitionService: Plugged
07-12 11:48:52.885  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:48:52.885  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:48:52.885  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:48:52.895  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:48:52.895  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:48:52.895  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:48:52.920 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:48:52.920 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:48:52.925  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:48:52.925  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:48:52.925  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:56.795  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:30), LCD = 0
,07-12 11:49:00.075  3603  4962 E Watchdog: !@Sync 28 [07-12 11:49:00.075]
,07-12 11:49:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:49:02.035  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:49:02.035  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:49:02.110  4978  5039 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 70ms lastUpdatedAfter : 180431ms
,07-12 11:49:06.840  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,07-12 11:49:16.890  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,07-12 11:49:22.975  3603  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:49:22.975  3603  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:49:22.975  3603  4709 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:49:22.975  3603  4709 D BatteryService: stay LED for fully charged
,07-12 11:49:22.980  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:49:22.985  3603  3603 I MotionRecognitionService: Plugged
07-12 11:49:22.985  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:49:22.985  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:49:22.985  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:49:22.990  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:49:22.990  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:49:22.990  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:49:23.010 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:49:23.010 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:49:23.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:49:23.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:49:23.020  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:26.930  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:30), LCD = 0
,07-12 11:49:30.080  3603  4962 E Watchdog: !@Sync 29 [07-12 11:49:30.079]
,07-12 11:49:36.980  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,07-12 11:49:47.030  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,07-12 11:49:53.060  3603  3631 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:49:53.060  3603  3631 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:49:53.060  3603  3631 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:49:53.060  3603  3631 D BatteryService: stay LED for fully charged
,07-12 11:49:53.060  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:49:53.070  3603  3603 I MotionRecognitionService: Plugged
07-12 11:49:53.070  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:49:53.070  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:49:53.070  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:49:53.075  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:49:53.075  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:49:53.075  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:49:53.095 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:49:53.095 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:49:53.100  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:49:53.100  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:49:53.100  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:56.550  3603  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
07-12 11:49:56.550  3603  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:49:56.555  3603  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:49:57.070  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:30), LCD = 0
,07-12 11:50:00.085  3603  4962 E Watchdog: !@Sync 30 [07-12 11:50:00.088]
,07-12 11:50:00.485  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:50:02.210  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:50:02.210  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:50:03.250  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-12 11:50:03.250  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:50:03.265  3603  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-12 11:50:03.265  3603  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:50:07.095  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,07-12 11:50:17.145  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,07-12 11:50:23.155  3603  5016 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:50:23.160  3603  5016 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:50:23.160  3603  5016 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:50:23.160  3603  5016 D BatteryService: stay LED for fully charged
,07-12 11:50:23.160  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:50:23.165  3603  3603 I MotionRecognitionService: Plugged
07-12 11:50:23.165  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:50:23.165  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:50:23.165  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:50:23.170  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:50:23.170  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:50:23.170  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-12 11:50:23.195 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:50:23.195 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-12 11:50:23.200  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:50:23.200  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:23.200  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:27.195  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), LCD = 0
,07-12 11:50:30.095  3603  4962 E Watchdog: !@Sync 31 [07-12 11:50:30.095]
,07-12 11:50:31.815  3603  4401 V AlarmManager: Expired Alarm result :4
,07-12 11:50:31.875  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-12 11:50:31.875  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
07-12 11:50:31.875  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:50:31.885  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:50:31.895  3603  3753 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-12 11:50:31.895  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:50:31.905  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:50:31.905  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:50:31.905  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-12 11:50:31.905  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:50:31.905  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:50:31.905  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:50:31.910  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:50:31.910  5279 12221 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-12 11:50:31.925  3603  3603 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-12 11:50:31.925  3603  3603 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-12 11:50:31.925  3603  3603 I Sensors : Light old sensor_state 1, new sensor_state : 513 en : 1
,07-12 11:50:31.940  3603  3603 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-12 11:50:31.955  3603  3603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1786e55 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5638dee 7500:com.google.android.gms/u0a14}
,07-12 11:50:31.960  5279 12219 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-12 11:50:32.010  3603  4709 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c6a795b u0 bg_app_info qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{db78b37 7238:tv.peel.smartremote/u0a186}
,07-12 11:50:32.100  7500 12228 I EventLogChimeraService: Aggregate from 1468314926470 (log), 1468314926470 (data)
,07-12 11:50:32.115  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:50:32.115  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:50:32.135  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:50:32.145  5279 12219 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-12 11:50:32.145  5279 12219 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-12 11:50:32.150  3603  4379 I Sensors : #>LightSensor r=117 g=106 b=87 c=297 atime=238 again=64 lux=54.000000
,07-12 11:50:32.150  3603  3855 D LightsService: [SvcLED]  onSensorChanged::light value = 54
07-12 11:50:32.150  3603  3855 I Sensors : Light old sensor_state 513, new sensor_state : 1 en : 0
,07-12 11:50:32.150  3603  3855 D SensorManager: unregisterListener ::   
07-12 11:50:32.150  3603  3855 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-12 11:50:32.155  3603  3855 V AlarmManager:  remove PendingIntent] PendingIntent{fd106ce: PendingIntentRecord{d66d9ef android broadcastIntent}}
07-12 11:50:32.160  5279 12219 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-12 11:50:32.160  5279 12219 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-12 11:50:32.250  5279 12219 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-12 11:50:32.250  5279 12219 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-12 11:50:32.295  5279 12219 W ThreadPoolDumper: Queue length for executor IcingConnectionExecutor with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,07-12 11:50:32.305  3603  5112 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10014
,07-12 11:50:32.330  3603  3753 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{930f93c u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f457704 10973:com.samsung.android.sm/1000}
,07-12 11:50:32.355  3603  3631 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{930f93c u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5638dee 7500:com.google.android.gms/u0a14}
,07-12 11:50:32.410  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff86f4b u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f457704 10973:com.samsung.android.sm/1000}
,07-12 11:50:32.445  3603  5114 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ff86f4b u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5638dee 7500:com.google.android.gms/u0a14}
,07-12 11:50:32.505  7500  9307 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-12 11:50:32.510  7500 12234 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-12 11:50:32.625  5279 12219 I ContextCompilationHandl: Recognition context unchanged for APP_NAMES en-US
07-12 11:50:32.625  5279 12219 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-12 11:50:32.670  7500  8520 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-12 11:50:32.710  7500 12235 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-12 11:50:32.725  7500  9303 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 11:50:32.760  7238  7292 I System.out: Thread-478(ApacheHTTPLog):isSBSettingEnabled false
07-12 11:50:32.760  7238  7292 I System.out: Thread-478(ApacheHTTPLog):isShipBuild true
07-12 11:50:32.760  7238  7292 I System.out: Thread-478(ApacheHTTPLog):getDebugLevel 0x4f4c
07-12 11:50:32.760  7238  7292 I System.out: Thread-478(ApacheHTTPLog):Smart Bonding Setting is false
07-12 11:50:32.760  7238  7292 I System.out: Thread-478(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,07-12 11:50:32.760  2916  4371 D EnterpriseController: netId is 0
07-12 11:50:32.760  2916  4371 D Netd    : getNetworkForDns: using netid 502 for uid 10186
,07-12 11:50:32.775  7500 12235 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
07-12 11:50:32.775  7500  9303 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 11:50:32.800  7500  9303 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-12 11:50:32.820  5279 12219 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US
,07-12 11:50:33.095  3603  3753 W ProcessCpuTracker: Skipping unknown process pid 12245
,07-12 11:50:34.315  7238  7292 I System.out: non-ui calls detatch()
,07-12 11:50:37.260  3603  6622 D SSRM:n  : SIOP:: AP = 270, PST = 264 (W:28), LCD = 0
,07-12 11:50:47.305  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:28), LCD = 0
,07-12 11:50:53.265  3603  5084 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:57.330  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:28), LCD = 0
,07-12 11:50:57.825  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-12 11:50:57.825  2916  4367 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-12 11:51:00.000  3603  4401 V AlarmManager: Expired Alarm result :8
,07-12 11:51:00.095  3603  4962 E Watchdog: !@Sync 32 [07-12 11:51:00.098]
,07-12 11:51:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:51:02.335  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:51:02.335  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:51:07.405  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:28), LCD = 0
,07-12 11:51:17.445  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), LCD = 0
,07-12 11:51:23.350  3603  5016 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:51:23.350  3603  5016 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:51:23.350  3603  5016 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:51:23.350  3603  5016 D BatteryService: stay LED for fully charged
,07-12 11:51:23.350  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:51:23.355  3603  3603 I MotionRecognitionService: Plugged
07-12 11:51:23.355  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:51:23.355  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:51:23.355  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:51:23.365  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:51:23.365  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:51:23.365  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:51:23.395 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:51:23.395 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:51:23.400  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:51:23.400  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:51:23.400  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:27.470  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,07-12 11:51:30.100  3603  4962 E Watchdog: !@Sync 33 [07-12 11:51:30.102]
,07-12 11:51:37.505  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,07-12 11:51:47.540  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), LCD = 0
,07-12 11:51:53.445  3603  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:51:57.575  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:52:00.110  3603  4962 E Watchdog: !@Sync 34 [07-12 11:52:00.108]
,07-12 11:52:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:52:02.455  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:52:02.455  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:52:06.905  3603  4401 V AlarmManager: Expired Alarm result :4
,07-12 11:52:07.060  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-12 11:52:07.060  4513  4513 I PERF    : received broadcast android.intent.action.TIME_TICK
07-12 11:52:07.060  4513  4513 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:52:07.075  4513  4513 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-12 11:52:07.075  4513  4513 D SecKeyguardClockView: HomeTimezone(): 1
,07-12 11:52:07.085  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.085  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{ab0bca: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.085  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.090  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.090  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.090  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.090  4513  4513 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.095  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.105  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{ea7c13b: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.110  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{8ef7058: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.115  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{e3dd5b1: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.140  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{f561a96: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.165  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{9c73617: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.170  4513  4513 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-12 11:52:07.195  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{9173a04: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.210  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{5a91bed: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.215  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{5d14a22: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.215  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{6ff1cb3: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.220  3603  3631 V AlarmManager:  remove PendingIntent] PendingIntent{acff270: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.225  3603  7152 V AlarmManager:  remove PendingIntent] PendingIntent{90889e9: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}},
,07-12 11:52:07.225  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{5dde66e: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.230  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{2c4d10f: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.235  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{619c59c: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.240  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{5d6dba5: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.240  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{a05fb7a: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.245  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{1876f2b: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.250  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{cb9f88: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.255  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{c7e8d21: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.255  3603  5011 V AlarmManager:  remove PendingIntent] PendingIntent{9685546: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.260  3603  5689 V AlarmManager:  remove PendingIntent] PendingIntent{58bd307: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.265  3603  5105 V AlarmManager:  remove PendingIntent] PendingIntent{53f2c34: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.270  3603  5112 V AlarmManager:  remove PendingIntent] PendingIntent{f95da5d: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.270  3603  5113 V AlarmManager:  remove PendingIntent] PendingIntent{c447fd2: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.275  3603  4553 V AlarmManager:  remove PendingIntent] PendingIntent{68898a3: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.280  3603  4439 V AlarmManager:  remove PendingIntent] PendingIntent{7bcd7a0: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.280  3603  5084 V AlarmManager:  remove PendingIntent] PendingIntent{adabf59: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.285  3603  5114 V AlarmManager:  remove PendingIntent] PendingIntent{d46c71e: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.290  3603  5016 V AlarmManager:  remove PendingIntent] PendingIntent{7021bff: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.290  3603  4709 V AlarmManager:  remove PendingIntent] PendingIntent{6a7cdcc: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.295  3603  3632 V AlarmManager:  remove PendingIntent] PendingIntent{deef815: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.300  3603  5015 V AlarmManager:  remove PendingIntent] PendingIntent{394372a: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.305  3603  5083 V AlarmManager:  remove PendingIntent] PendingIntent{366791b: PendingIntentRecord{4bfbb35 com.android.bluetooth broadcastIntent}}
,07-12 11:52:07.610  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:52:17.645  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:52:23.540  3603  5015 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:27.670  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:52:30.115  3603  4962 E Watchdog: !@Sync 35 [07-12 11:52:30.117]
,07-12 11:52:37.695  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:52:47.720  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:52:53.640  3603  3632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:57.750  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:52:59.995  3603  4401 V AlarmManager: Expired Alarm result :8
,07-12 11:53:00.120  3603  4962 E Watchdog: !@Sync 36 [07-12 11:53:00.119]
,07-12 11:53:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:53:02.575  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:53:02.575  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:53:02.660  4978  5039 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 76ms lastUpdatedAfter : 150190ms
,07-12 11:53:07.780  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:53:17.815  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:53:23.735  3603  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:53:23.735  3603  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:53:23.735  3603  4709 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:53:23.735  3603  4709 D BatteryService: stay LED for fully charged
,07-12 11:53:23.735  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:53:23.745  3603  3603 I MotionRecognitionService: Plugged
07-12 11:53:23.745  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:53:23.745  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:53:23.745  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:53:23.750  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:53:23.750  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:53:23.750  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-12 11:53:23.770 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:53:23.770 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:53:23.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:53:23.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:53:23.780  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:27.850  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:53:30.120  3603  4962 E Watchdog: !@Sync 37 [07-12 11:53:30.123]
,07-12 11:53:37.875  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:53:47.910  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:53:53.835  3603  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:53:53.835  3603  5011 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:53:53.835  3603  5011 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:53:53.835  3603  5011 D BatteryService: stay LED for fully charged
,07-12 11:53:53.835  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:53:53.840  3603  3603 I MotionRecognitionService: Plugged
07-12 11:53:53.840  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:53:53.840  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:53:53.840  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:53:53.850  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-12 11:53:53.850  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:53:53.850  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:53:53.870 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-12 11:53:53.870 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:53:53.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:53:53.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:53:53.875  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:57.940  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:54:00.125  3603  4962 E Watchdog: !@Sync 38 [07-12 11:54:00.127]
,07-12 11:54:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:54:02.775  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:54:02.775  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:54:07.965  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:54:18.000  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:54:23.930  3603  5015 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:23.935  3603  5015 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:54:23.935  3603  5015 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:54:23.935  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:54:23.935  3603  5015 D BatteryService: stay LED for fully charged
,07-12 11:54:23.945  3603  3603 I MotionRecognitionService: Plugged
07-12 11:54:23.945  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:54:23.945  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:54:23.945  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:54:23.950  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:54:23.950  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:54:23.950  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-12 11:54:23.975 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:54:23.975 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:54:23.980  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:54:23.980  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:54:23.980  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:28.025  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:54:30.130  3603  4962 E Watchdog: !@Sync 39 [07-12 11:54:30.129]
,07-12 11:54:38.055  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:54:48.090  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:54:54.030  3603  5105 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:54:54.030  3603  5105 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:54:54.030  3603  5105 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:54:54.035  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:54:54.040  3603  3603 I MotionRecognitionService: Plugged
07-12 11:54:54.040  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:54:54.040  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:54:54.040  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:54:54.045  3603  5105 D BatteryService: stay LED for fully charged
,07-12 11:54:54.050  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:54:54.050  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:54:54.050  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:54:54.070 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:54:54.070 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:54:54.080  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:54:54.080  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:54:54.080  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:56.550  3603  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
07-12 11:54:56.550  3603  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:54:56.555  3603  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:54:56.940  3603  3746 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 11:54:58.110  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:54:59.980  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-12 11:54:59.980  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:55:00.000  3603  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-12 11:55:00.000  3603  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:55:00.130  3603  4962 E Watchdog: !@Sync 40 [07-12 11:55:00.133]
,07-12 11:55:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:55:02.895  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:55:02.895  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:55:08.150  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:55:18.175  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:55:24.125  3603  5112 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:55:24.125  3603  5112 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:55:24.125  3603  5112 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:55:24.125  3603  5112 D BatteryService: stay LED for fully charged
,07-12 11:55:24.125  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:55:24.130  3603  3603 I MotionRecognitionService: Plugged
07-12 11:55:24.130  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:55:24.130  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:55:24.130  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:55:24.140  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:55:24.140  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:55:24.140  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:55:24.155 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:55:24.155 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:55:24.165  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:55:24.165  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:55:24.165  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:28.205  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:55:30.140  3603  4962 E Watchdog: !@Sync 41 [07-12 11:55:30.140]
,07-12 11:55:38.230  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:55:48.260  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:55:54.225  3603  7152 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:55:54.225  3603  7152 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:55:54.225  3603  7152 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:55:54.225  3603  7152 D BatteryService: stay LED for fully charged
,07-12 11:55:54.225  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:55:54.230  3603  3603 I MotionRecognitionService: Plugged
07-12 11:55:54.230  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:55:54.230  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:55:54.230  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:55:54.240  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:55:54.240  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:55:54.240  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:55:54.265 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:55:54.265 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:55:54.270  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:55:54.270  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:55:54.270  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:58.290  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:56:00.140  3603  4962 E Watchdog: !@Sync 42 [07-12 11:56:00.143]
,07-12 11:56:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:56:02.965  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:56:02.965  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:56:03.045  4978  5039 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 71ms lastUpdatedAfter : 180387ms
,07-12 11:56:08.325  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:56:18.355  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:56:24.330  3603  3632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:28.380  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:56:30.150  3603  4962 E Watchdog: !@Sync 43 [07-12 11:56:30.150]
,07-12 11:56:38.410  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:56:48.440  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:56:54.450  3603  7152 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:56:54.450  3603  7152 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:56:54.450  3603  7152 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:56:54.450  3603  7152 D BatteryService: stay LED for fully charged
,07-12 11:56:54.450  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:56:54.455  3603  3603 I MotionRecognitionService: Plugged
07-12 11:56:54.455  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:56:54.455  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:56:54.455  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:56:54.460  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:56:54.460  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:56:54.460  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:56:54.470  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:56:54.470  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:56:54.470  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:54.475 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:56:54.475 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:56:58.460  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:57:00.160  3603  4962 E Watchdog: !@Sync 44 [07-12 11:57:00.154]
,07-12 11:57:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:57:03.160  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:57:03.160  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:57:08.485  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:57:18.515  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:57:24.550  3603  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:28.540  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:57:30.165  3603  4962 E Watchdog: !@Sync 45 [07-12 11:57:30.165]
,07-12 11:57:38.575  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:57:48.600  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:57:54.645  3603  4709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:57:54.645  3603  4709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:57:54.645  3603  4709 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:57:54.645  3603  4709 D BatteryService: stay LED for fully charged
,07-12 11:57:54.645  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:57:54.655  3603  3603 I MotionRecognitionService: Plugged
07-12 11:57:54.655  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:57:54.655  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:57:54.655  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:57:54.665  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:57:54.665  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:57:54.665  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:57:54.670  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:54.675 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:57:54.675 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:57:54.685  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:57:54.685  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:58.635  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:58:00.170  3603  4962 E Watchdog: !@Sync 46 [07-12 11:58:00.172]
,07-12 11:58:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:58:03.305  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:58:03.305  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:58:08.660  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:58:18.685  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:58:24.740  3603  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:28.715  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:58:30.175  3603  4962 E Watchdog: !@Sync 47 [07-12 11:58:30.177]
,07-12 11:58:38.745  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:58:48.775  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:58:54.840  3603  5011 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:58:54.840  3603  5011 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:58:54.840  3603  5011 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:58:54.840  3603  5011 D BatteryService: stay LED for fully charged
,07-12 11:58:54.845  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:58:54.850  3603  3603 I MotionRecognitionService: Plugged
07-12 11:58:54.850  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:58:54.850  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:58:54.850  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:58:54.855  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:58:54.855  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:58:54.855  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:58:54.870  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,07-12 11:58:54.870 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:58:54.870 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:58:54.885  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:58:54.885  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:58.805  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:59:00.180  3603  4962 E Watchdog: !@Sync 48 [07-12 11:59:00.179]
,07-12 11:59:00.490  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 11:59:03.430  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 11:59:03.430  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 11:59:03.510  4978  5039 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 71ms lastUpdatedAfter : 180463ms
,07-12 11:59:08.835  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:59:18.865  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:59:24.940  3603  5015 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:28.890  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:59:30.180  3603  4962 E Watchdog: !@Sync 49 [07-12 11:59:30.183]
,07-12 11:59:38.920  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:59:48.950  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:59:55.035  3603  3632 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:59:55.035  3603  3632 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 11:59:55.035  3603  3632 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 11:59:55.035  3603  3632 D BatteryService: stay LED for fully charged
,07-12 11:59:55.040  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:59:55.045  3603  3603 I MotionRecognitionService: Plugged
07-12 11:59:55.045  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 11:59:55.045  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 11:59:55.045  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 11:59:55.050  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:59:55.050  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:59:55.050  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-12 11:59:55.075 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:59:55.075 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 11:59:55.080  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:59:55.080  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:59:55.080  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:56.555  3603  4391 D TimaService: TIMA: TimaService scheduler is intialized. 
07-12 11:59:56.555  3603  4391 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:59:56.555  3603  4390 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:59:58.995  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 11:59:59.070  3603  3614 I art     : Background sticky concurrent mark sweep GC freed 55623(7MB) AllocSpace objects, 368(7MB) LOS objects, 32% free, 31MB/46MB, paused 3.353ms total 113.605ms
,07-12 12:00:00.185  3603  4962 E Watchdog: !@Sync 50 [07-12 12:00:00.187]
,07-12 12:00:00.485  2944  5169 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,07-12 12:00:02.795  3603  5694 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-12 12:00:02.805  3603  5694 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,07-12 12:00:02.805  3603  5694 V MARsPolicyManager: updateSMDBValues
,07-12 12:00:02.820  3603  3825 E MARsDBManager: updateDBAll : begin --size 0
07-12 12:00:02.820  3603  3825 E MARsDBManager: updateDBAll : end
,07-12 12:00:03.275  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-12 12:00:03.275  3603  4391 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 12:00:03.290  3603  4391 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-12 12:00:03.290  3603  4391 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 12:00:03.605  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-12 12:00:03.605  4978  5039 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-12 12:00:09.025  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 12:00:19.050  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 12:00:25.130  3603  5015 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 12:00:25.130  3603  5015 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4374, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
07-12 12:00:25.130  3603  5015 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
07-12 12:00:25.130  3603  5015 D BatteryService: stay LED for fully charged
,07-12 12:00:25.135  3603  3603 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 12:00:25.140  3603  3603 I MotionRecognitionService: Plugged
07-12 12:00:25.140  3603  3603 D MotionRecognitionService:   cableConnection= 1
07-12 12:00:25.140  3603  3603 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-12 12:00:25.140  3603  3603 D MotionRecognitionService: skip setTransmitPower. 
,07-12 12:00:25.150  4513  4513 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 12:00:25.150  4513  4513 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-12 12:00:25.150  4513  4513 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 12:00:25.170 10423 10423 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 12:00:25.170 10423 10586 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-12 12:00:25.175  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 12:00:25.175  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 12:00:25.175  4513  4513 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 12:00:29.075  3603  6622 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), LCD = 0
,07-12 12:00:30.190  3603  4962 E Watchdog: !@Sync 51 [07-12 12:00:30.190]
,TIME-OUT KILL (timeout was 1400000ms)
```
