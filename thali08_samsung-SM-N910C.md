#### Test 721454317367600_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
06-22 07:47:32.210  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:22), LCD = 0
,06-22 07:47:32.770  3605  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
06-22 07:47:32.935 10534 10534 I FIPS_bssl: FIPS approved mode (1) | 10534 | app_process
06-22 07:47:32.940 10534 10534 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-22 07:47:32.945 10534 10534 D AndroidRuntime: CheckJNI is OFF
06-22 07:47:32.945 10534 10534 D AndroidRuntime: readGMSProperty: start
06-22 07:47:32.945 10534 10534 D AndroidRuntime: readGMSProperty: already setted!!
06-22 07:47:32.945 10534 10534 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-22 07:47:32.945 10534 10534 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-22 07:47:32.945 10534 10534 D AndroidRuntime: readGMSProperty: end
06-22 07:47:32.945 10534 10534 D AndroidRuntime: addProductProperty: start
06-22 07:47:32.970 10534 10534 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-22 07:47:33.000 10534 10534 I Radio-JNI: register_android_hardware_Radio DONE
06-22 07:47:33.005 10534 10534 E AffinityControl: AffinityControl: registerfunction enter
06-22 07:47:33.020 10534 10534 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-22 07:47:33.060  3605  5223 D GameManagerService: identifyGamePackage. com.test.thalitest
06-22 07:47:33.060  3605  5223 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
06-22 07:47:33.065  3605  5223 D ActivityManager: mDVFSHelper.acquire()
06-22 07:47:33.065  3605  5223 V WindowManager: addAppToken: AppWindowToken{579a099 token=Token{87175e0 ActivityRecord{74fc7e3 u0 com.test.thalitest/.MainActivity t69}}} to stack=1 task=69 at 0
06-22 07:47:33.080  3605  3849 D SecWifiDisplayUtil: Metadata value : none
06-22 07:47:33.080  3605  3849 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{fc5c9d1 V.E...... R.....ID 0,0-0,0}
06-22 07:47:33.085  3605  3849 D ISSUE_DEBUG: InputChannelName : fa59737 Starting com.test.thalitest
06-22 07:47:33.085  3605  5223 I ActivityManager: Start proc 10550:com.test.thalitest/u0a7 for activity com.test.thalitest/.MainActivity
06-22 07:47:33.085  3605  5223 D InputDispatcher: Focused application set to: xxxx
06-22 07:47:33.085 10550 10550 E Zygote  : v2
06-22 07:47:33.085 10550 10550 I libpersona: KNOX_SDCARD checking this for 10007
06-22 07:47:33.085 10550 10550 I libpersona: KNOX_SDCARD not a persona
06-22 07:47:33.085  3605  5223 D InputDispatcher: Focus left window: 6767
06-22 07:47:33.090  3605  3764 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2252b5e u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-22 07:47:33.090  3605  4447 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-22 07:47:33.090  4517  4517 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-22 07:47:33.090 10534 10534 D AndroidRuntime: Shutting down VM
06-22 07:47:33.090 10550 10550 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-22 07:47:33.090 10550 10550 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-22 07:47:33.095 10550 10550 E Zygote  : accessInfo : 0
06-22 07:47:33.095 10550 10550 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-22 07:47:33.100  2907  2907 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
06-22 07:47:33.120  3605  3849 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3605 uid:1000
06-22 07:47:33.120  3605  3849 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:47:33.120  3605  3849 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3605 uid:1000
06-22 07:47:33.120  3605  3849 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-22 07:47:33.120  3605  3849 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
06-22 07:47:33.120 10550 10550 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:47:33.120 10550 10550 D ActivityThread: Added TimaKeyStore provider
06-22 07:47:33.125  3605  5785 V WindowOrientationListener: setCurrentAppOrientation :-1
06-22 07:47:33.125  3605  5785 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-22 07:47:33.130  3605  3764 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{fa59737 u0 d0 Starting com.test.thalitest}
06-22 07:47:33.130  4517  4517 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-22 07:47:33.135  3605  5785 D ActivityManager:  Launching com.test.thalitest, updated priority
06-22 07:47:33.145  3605  3605 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
06-22 07:47:33.145  3605  3757 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-22 07:47:33.165  2907  4383 D libEGL  : eglTerminate EGLDisplay = 0xb1ebf624
06-22 07:47:33.165  2907  9358 I SurfaceFlinger: id=17 Removed VSBConnecti (7/11)
06-22 07:47:33.165  2907  3000 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
06-22 07:47:33.170  2907  3000 D libEGL  : eglTerminate EGLDisplay = 0xb65ff624
06-22 07:47:33.170  2907  3000 D libEGL  : eglTerminate EGLDisplay = 0xb65ff624
06-22 07:47:33.175  2907  9358 I SurfaceFlinger: id=9 Removed Mauncher (4/10)
06-22 07:47:33.175  2907  9358 I SurfaceFlinger: id=9 Removed Mauncher (-2/10)
06-22 07:47:33.180  2907  2907 D libEGL  : eglTerminate EGLDisplay = 0xbe8a9474
06-22 07:47:33.180  2907  2907 D libEGL  : eglTerminate EGLDisplay = 0xbe8a9474
06-22 07:47:33.180  2907  9358 I SurfaceFlinger: id=18 Removed VSBConnecti (4/9)
06-22 07:47:33.180  2907  4383 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/9)
06-22 07:47:33.190  6767  6767 V ActivityThread: updateVisibility : ActivityRecord{6138713 token=android.os.BinderProxy@7dfd8b4 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-22 07:47:33.190  5191  5191 V ActivityThread: updateVisibility : ActivityRecord{97afe41 token=android.os.BinderProxy@4c1152a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-22 07:47:33.190  5191  5191 D Launcher: onTrimMemory. Level: 20
06-22 07:47:33.190  3605  3849 V WindowStateAnimator: Finishing drawing window Window{fa59737 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-22 07:47:33.195  2907  2907 D libEGL  : eglTerminate EGLDisplay = 0xbe8a9474
06-22 07:47:33.195  2907  2907 D libEGL  : eglInitialize EGLDisplay = 0xbe8a940c
,06-22 07:47:33.460  3605  5785 I WindowManager: Screenshot max retries 4 of Token{87175e0 ActivityRecord{74fc7e3 u0 com.test.thalitest/.MainActivity t69}} appWin=Window{fa59737 u0 d0 Starting com.test.thalitest} drawState=2
,06-22 07:47:33.465  3605  3757 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-22 07:47:33.475  3605  4447 D NetworkPolicy: isUidForegroundLocked: 10007, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,06-22 07:47:33.500  3605  6651 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-22 07:47:33.510  3605  6651 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-22 07:47:33.555 10550 10550 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,06-22 07:47:33.590 10550 10550 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-22 07:47:33.600 10550 10550 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 2418-2421)
06-22 07:47:33.600 10550 10550 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,06-22 07:47:33.615 10550 10564 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,06-22 07:47:33.620 10550 10550 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13f801b}
06-22 07:47:33.620 10550 10550 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-22 07:47:33.620 10550 10550 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,06-22 07:47:33.630 10550 10550 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,06-22 07:47:33.645 10550 10565 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,06-22 07:47:33.670 10550 10550 D libEGL  : eglInitialize EGLDisplay = 0xbee01e7c
,06-22 07:47:33.700  3605  3631 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10007
,06-22 07:47:33.700  3605  3631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29665 com.android.server.am.ActivityManagerService.registerReceiver:22536 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 ,
,06-22 07:47:33.760 10550 10550 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,06-22 07:47:33.775 10550 10550 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-22 07:47:33.775 10550 10550 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,06-22 07:47:33.775 10550 10550 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,06-22 07:47:33.775 10550 10550 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,06-22 07:47:33.790 10550 10550 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,06-22 07:47:33.795 10550 10550 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-22 07:47:33.865 10550 10550 D SecWifiDisplayUtil: Metadata value : none
,06-22 07:47:33.870 10550 10550 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d5cb018 I.E...... R.....ID 0,0-0,0}
,06-22 07:47:33.875 10550 10601 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-22 07:47:33.880  3605  4913 D ISSUE_DEBUG: InputChannelName : d2b7b58 com.test.thalitest/com.test.thalitest.MainActivity
,06-22 07:47:33.885  3605  5785 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-22 07:47:33.885  3605  5785 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-22 07:47:33.885  3605  3605 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-22 07:47:33.885  3605  3605 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-22 07:47:33.910 10550 10550 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10007, CallingPid : 10550
,06-22 07:47:33.915  3605  5784 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/10550 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-22 07:47:33.930 10550 10564 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,06-22 07:47:33.935 10550 10550 D SecWifiDisplayUtil: Metadata value : none
,06-22 07:47:33.945  2907  2907 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,06-22 07:47:33.965  3605  5286 D InputDispatcher: Focus entered window: 10550
,06-22 07:47:33.970  3605  3849 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3605 uid:1000
06-22 07:47:33.970  3605  3849 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:47:33.970  3605  3849 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3605 uid:1000
06-22 07:47:33.970  3605  3849 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-22 07:47:33.970 10550 10601 D libEGL  : eglInitialize EGLDisplay = 0x9cb7f7c4
06-22 07:47:33.970 10550 10601 I OpenGLRenderer: Initialized EGL, version 1.4
,06-22 07:47:33.975 10550 10601 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,06-22 07:47:33.980 10550 10550 V ActivityThread: updateVisibility : ActivityRecord{55f4cad token=android.os.BinderProxy@90727fb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-22 07:47:33.985 10550 10550 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-22 07:47:34.050  2907  2907 D libEGL  : eglInitialize EGLDisplay = 0xbe8a940c
,06-22 07:47:34.050  3605  5774 V WindowStateAnimator: Finishing drawing window Window{d2b7b58 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,06-22 07:47:34.050 10550 10550 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,06-22 07:47:34.050 10550 10550 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-22 07:47:34.050  3605  5771 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-22 07:47:34.055  3605  3849 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-22 07:47:34.055  3605  3605 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,06-22 07:47:34.055  3605  3849 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +595ms (total +990ms)
,06-22 07:47:34.060  3605  3605 I KnoxTimeoutHandler: SD activityfalse
,06-22 07:47:34.065  3605  3849 D ActivityManager: mDVFSHelper.release()
06-22 07:47:34.065  3605  3849 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{74fc7e3 u0 com.test.thalitest/.MainActivity t69} time:332886
06-22 07:47:34.065  3605  3849 D ViewRootImpl: #3 mView = null
,06-22 07:47:34.065  2907  9358 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
06-22 07:47:34.065  2907  4383 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
06-22 07:47:34.065  2907  2907 D libEGL  : eglTerminate EGLDisplay = 0xbe8a9474
,06-22 07:47:34.070 10550 10550 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,06-22 07:47:34.080 10550 10608 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:47:34.080 10550 10608 D libEGL  : eglInitialize EGLDisplay = 0x99eac3ec
,06-22 07:47:34.100  3605  4913 V WindowStateAnimator: Finishing drawing window Window{d2b7b58 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,06-22 07:47:34.100  2907  2907 D libEGL  : eglInitialize EGLDisplay = 0xbe8a940c
,06-22 07:47:34.100 10550 10550 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@90727fb time:332923
,06-22 07:47:34.135 10550 10550 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10550
,06-22 07:47:34.320 10550 10550 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-22 07:47:34.475 10550 10614 D jxcore_app_log: JniHelper::setJavaVM(0xb48b4000), pthread_self() = -1735132880
,06-22 07:47:34.480 10550 10614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:47:34.480 10550 10614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:47:34.480 10550 10614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:47:34.480 10550 10614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:47:34.480 10550 10614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:47:34.480 10550 10614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ee05eb added. We now have 1 listener(s)
,06-22 07:47:34.485 10550 10614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,06-22 07:47:34.485 10550 10614 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,06-22 07:47:34.485 10550 10614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-22 07:47:34.485 10550 10614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:47:34.485 10550 10614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@365eb06 added. We now have 1 listener(s)
06-22 07:47:34.485 10550 10614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-22 07:47:34.490 10550 10614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:47:34.490 10550 10614 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-22 07:47:34.490 10550 10614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:47:34.490 10550 10614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-22 07:47:34.490 10550 10614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:47:34.490 10550 10614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-22 07:47:34.490 10550 10614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-22 07:47:34.490 10550 10614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
06-22 07:47:34.495 10550 10614 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:47:34.495 10550 10614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:47:34.495 10550 10614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:47:34.495 10550 10614 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:47:34.495 10550 10614 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-22 07:47:34.520 10550 10550 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-22 07:47:34.875 10550 10615 W jxcore-log: Initializing JXcore engine
06-22 07:47:34.875 10550 10615 W jxcore-log: JXcore engine is ready
,06-22 07:47:34.890  4697  4697 D Recents : onTaskStackChanged
,06-22 07:47:34.900  5713  5713 E audit   : type=1400 msg=audit(1466574454.900:260): avc:  denied  { ioctl } for  pid=10615 comm="Thread-1015" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5140 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file
06-22 07:47:34.900  5713  5713 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-22 07:47:34.900  5713  5713 E audit   : type=1300 msg=audit(1466574454.900:260): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=8 a1=5451 a2=1 a3=988103c8 items=0 ppid=2964 ppcomm=main pid=10615 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1015" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-22 07:47:34.900  5713  5713 E audit   : type=1327 msg=audit(1466574454.900:260): proctitle="com.test.thalitest"
06-22 07:47:34.900  5713  5713 E audit   : type=1320 msg=audit(1466574454.900:260): 
,06-22 07:47:34.900  5713  5713 E audit   : type=1400 msg=audit(1466574454.900:261): avc:  denied  { ioctl } for  pid=10615 comm="Thread-1015" path="socket:[37328]" dev="sockfs" ino=37328 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
06-22 07:47:34.900  5713  5713 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-22 07:47:34.900  5713  5713 E audit   : type=1300 msg=audit(1466574454.900:261): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=39 a1=5451 a2=1 a3=988103c8 items=0 ppid=2964 ppcomm=main pid=10615 auid=4294967295 uid=10007 gid=10007 euid=10007 suid=10007 fsuid=10007 egid=10007 sgid=10007 fsgid=10007 ses=4294967295 tty=(none) comm="Thread-1015" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-22 07:47:34.900  5713  5713 E audit   : type=1327 msg=audit(1466574454.900:261): proctitle="com.test.thalitest"
06-22 07:47:34.900  5713  5713 E audit   : type=1320 msg=audit(1466574454.900:261): 
,06-22 07:47:34.905 10550 10615 W jxcore-log: Starting JXcore engine
,06-22 07:47:34.955 10550 10615 W jxcore-log: Platform android
06-22 07:47:34.955 10550 10615 W jxcore-log: 
06-22 07:47:34.955 10550 10615 W jxcore-log: Process ARCH arm
06-22 07:47:34.955 10550 10615 W jxcore-log: 
,06-22 07:47:35.045 10550 10615 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:47:35.045 10550 10615 I jxcore-log: 
06-22 07:47:35.045 10550 10615 W jxcore-log: JXcore engine is started
,06-22 07:47:35.050 10550 10614 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-22 07:47:35.060  3605  5785 D GameManagerService: identifyGamePackage. com.android.packageinstaller
06-22 07:47:35.060  3605  5785 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.android.packageinstaller)
,06-22 07:47:35.065  3605  5785 D ActivityManager: mDVFSHelper.acquire()
,06-22 07:47:35.065  3605  5785 V WindowManager: addAppToken: AppWindowToken{da06a88 token=Token{ad4862b ActivityRecord{88d0e7a u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}}} to stack=1 task=69 at 1
,06-22 07:47:35.070 10616 10616 E Zygote  : v2
,06-22 07:47:35.070 10616 10616 I libpersona: KNOX_SDCARD checking this for 10141
06-22 07:47:35.070 10616 10616 I libpersona: KNOX_SDCARD not a persona
06-22 07:47:35.075 10616 10616 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=51
06-22 07:47:35.075 10616 10616 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-22 07:47:35.075 10616 10616 E Zygote  : accessInfo : 0
06-22 07:47:35.075 10616 10616 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,06-22 07:47:35.075  3605  5785 I ActivityManager: Start proc 10616:com.android.packageinstaller/u0a141 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-22 07:47:35.075  3605  5785 D InputDispatcher: Focused application set to: xxxx
06-22 07:47:35.075  3605  5785 D InputDispatcher: Focus left window: 10550
,06-22 07:47:35.075 10550 10614 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
,06-22 07:47:35.080  3605  3849 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3605 uid:1000
06-22 07:47:35.080  3605  3849 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:47:35.080  3605  3849 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3605 uid:1000
06-22 07:47:35.080  3605  3849 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-22 07:47:35.085 10616 10616 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:47:35.085 10616 10616 D ActivityThread: Added TimaKeyStore provider
,06-22 07:47:35.090  3605  5774 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-22 07:47:35.095  3605  3605 D GameManagerService: NotifyRunnable. pkg: com.android.packageinstaller, type: 4, isMinimized: false, isTunableApp: false
,06-22 07:47:35.095  3605  3757 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-22 07:47:35.395  3605  5774 I WindowManager: Screenshot max retries 4 of Token{ad4862b ActivityRecord{88d0e7a u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69}} appWin=Window{d2b7b58 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-22 07:47:35.395  3605  3757 E MARsPolicyManager: getPackageInfo package org.thaliproject.p2p.btconnectorlib.test not installed!
,06-22 07:47:35.405  3605  6651 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-22 07:47:35.415 10616 10616 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-22 07:47:35.605 10616 10625 I art     : Background partial concurrent mark sweep GC freed 9096(539KB) AllocSpace objects, 0(0B) LOS objects, 77% free, 4MB/20MB, paused 5.456ms total 29.752ms
,06-22 07:47:35.615 10616 10616 D SecWifiDisplayUtil: Metadata value : none
,06-22 07:47:35.615 10616 10616 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{650bdb5 I.E...... R.....I. 0,0-0,0}
,06-22 07:47:35.620 10616 10628 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-22 07:47:35.625  3605  5286 D ISSUE_DEBUG: InputChannelName : 262395d com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-22 07:47:35.625  3605  4932 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-22 07:47:35.625  3605  4932 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-22 07:47:35.625  3605  3605 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-22 07:47:35.625  3605  3605 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-22 07:47:35.625  3605  3605 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-22 07:47:35.650  2907  2907 I SurfaceFlinger: id=21 createSurf (193x193),1 flag=4, HrantPermis
,06-22 07:47:35.650  3605  3764 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{262395d u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-22 07:47:35.650  4517  4517 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-22 07:47:35.670  3605  4781 D InputDispatcher: Focus entered window: 10616
,06-22 07:47:35.675  3605  3849 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3605 uid:1000
,06-22 07:47:35.675  3605  3849 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:47:35.675  3605  3849 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3605 uid:1000
06-22 07:47:35.675  3605  3849 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-22 07:47:35.680 10616 10628 D libEGL  : eglInitialize EGLDisplay = 0xaea137c4
06-22 07:47:35.680 10616 10628 I OpenGLRenderer: Initialized EGL, version 1.4
,06-22 07:47:35.695 10616 10628 D mali_winsys: new_window_surface returns 0x3000,  [1528x2656]-format:1
,06-22 07:47:35.700 10616 10616 V ActivityThread: updateVisibility : ActivityRecord{a53eaa2 token=android.os.BinderProxy@644a5ec {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-22 07:47:35.700 10616 10616 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-22 07:47:35.700  3605  4552 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-22 07:47:35.710  5576  5576 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-22 07:47:35.725 10616 10616 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-22 07:47:35.855  2907  2907 D libEGL  : eglInitialize EGLDisplay = 0xbe8a940c
,06-22 07:47:35.860  3605  4781 V WindowStateAnimator: Finishing drawing window Window{262395d u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
,06-22 07:47:35.865 10616 10616 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@644a5ec time:334685,
,06-22 07:47:35.875  3605  3849 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-22 07:47:35.875  3605  3605 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-22 07:47:35.875  3605  3605 I KnoxTimeoutHandler: SD activityfalse
,06-22 07:47:35.885  3605  3849 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +488ms (total +819ms)
,06-22 07:47:35.885  3605  3849 D ActivityManager: mDVFSHelper.release()
,06-22 07:47:35.885  3605  3849 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{88d0e7a u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t69} time:334707
,06-22 07:47:36.085  3605  4501 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/69_task.xml.bak
,06-22 07:47:36.635  4697  4697 D Recents : onTaskStackChanged
,06-22 07:47:37.165  3605  5215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-22 07:47:37.165  3605  5215 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-22 07:47:37.165  3605  5215 D BatteryService: online:4, current avg:-4, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-22 07:47:37.165  3605  5215 D BatteryService: stay LED for fully charged
,06-22 07:47:37.165  3605  3605 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-22 07:47:37.170  3605  3605 I MotionRecognitionService: Plugged
06-22 07:47:37.170  3605  3605 D MotionRecognitionService:   cableConnection= 1
06-22 07:47:37.170  3605  3605 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-22 07:47:37.170  3605  3605 D MotionRecognitionService: skip setTransmitPower. 
,06-22 07:47:37.180  4517  4517 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-22 07:47:37.180  4517  4517 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-22 07:47:37.180  4517  4517 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-22 07:47:37.205  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-22 07:47:37.205  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-22 07:47:37.205  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-22 07:47:41.450  3605  6651 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-22 07:47:42.245  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:22), CUR = -4, LCD = 0
,06-22 07:47:43.115  3605  3909 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
06-22 07:47:43.155  3605  3909 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-22 07:47:46.710  3605  5004 E Watchdog: !@Sync 11 [06-22 07:47:46.715]
,06-22 07:47:49.190  5705  5705 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:47:49.205  5705  5705 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:47:49.210  5705  5705 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-22 07:47:49.250  9266  9297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-22 07:47:49.250  9266  9297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-22 07:47:49.250  2920  4373 D EnterpriseController: netId is 0
06-22 07:47:49.250  2920  4373 D Netd    : getNetworkForDns: using netid 0 for uid 10031
,06-22 07:47:49.390  3605  3617 I art     : Background partial concurrent mark sweep GC freed 71920(5MB) AllocSpace objects, 112(2MB) LOS objects, 33% free, 30MB/45MB, paused 1.873ms total 245.009ms
,06-22 07:47:52.275  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), CUR = -4, LCD = 0
,06-22 07:47:52.775  3605  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:47:59.995  3605  4404 V AlarmManager: Expired Alarm result :8
06-22 07:48:00.000  3605  4404 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=358819 batch.start=440098
,06-22 07:48:02.310  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), CUR = -4, LCD = 0
,06-22 07:48:07.255  3605  4442 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-22 07:48:07.255  3605  4442 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-22 07:48:07.255  3605  4442 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-22 07:48:07.255  3605  4442 D BatteryService: stay LED for fully charged
,06-22 07:48:07.260  3605  3605 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-22 07:48:07.265  3605  3605 I MotionRecognitionService: Plugged
06-22 07:48:07.265  3605  3605 D MotionRecognitionService:   cableConnection= 1
06-22 07:48:07.265  3605  3605 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-22 07:48:07.265  3605  3605 D MotionRecognitionService: skip setTransmitPower. 
,06-22 07:48:07.270  4517  4517 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-22 07:48:07.270  4517  4517 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
06-22 07:48:07.270  4517  4517 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-22 07:48:07.300  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-22 07:48:07.300  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-22 07:48:07.300  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-22 07:48:12.345  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,06-22 07:48:12.780  3605  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:48:16.720  3605  5004 E Watchdog: !@Sync 12 [06-22 07:48:16.720]
,06-22 07:48:17.210  4893  4963 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
06-22 07:48:17.210  4893  4963 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,06-22 07:48:17.330  2946  5229 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,06-22 07:48:22.375  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), LCD = 0
,06-22 07:48:32.410  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,06-22 07:48:32.780  3605  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:48:37.345  3605  4442 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-22 07:48:37.350  3605  4442 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303590, invalid charger:0, maxChargingCurrent:0
06-22 07:48:37.350  3605  4442 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:322000, batterySWSelfDischarging:false, current_now:0
06-22 07:48:37.350  3605  4442 D BatteryService: stay LED for fully charged
,06-22 07:48:37.350  3605  3605 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-22 07:48:37.355  3605  3605 I MotionRecognitionService: Plugged
06-22 07:48:37.355  3605  3605 D MotionRecognitionService:   cableConnection= 1
06-22 07:48:37.355  3605  3605 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-22 07:48:37.355  3605  3605 D MotionRecognitionService: skip setTransmitPower. 
,06-22 07:48:37.360  4517  4517 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-22 07:48:37.360  4517  4517 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,06-22 07:48:37.365  4517  4517 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-22 07:48:37.390  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-22 07:48:37.390  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-22 07:48:37.390  4517  4517 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-22 07:48:42.445  3605  6651 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:26), LCD = 0
,06-22 07:48:46.725  3605  5004 E Watchdog: !@Sync 13 [06-22 07:48:46.727]
,06-22 07:48:52.480  3605  6651 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:26), LCD = 0
,06-22 07:48:52.785  3605  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,TIME-OUT KILL (timeout was 1400000ms)
```
