#### Test 7214543196063dc_thali04_samsung-SM-G920F Logs


```
--------- beginning of system
07-05 14:04:13.963  3506  4839 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:04:13.963  3506  4839 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
--------- beginning of main
07-05 14:04:13.983  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:04:13.963  3506  4839 D BatteryService: online:4, current avg:127, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:130
07-05 14:04:13.983  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:04:13.973  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:04:13.973  3506  3506 I MotionRecognitionService: Plugged
07-05 14:04:13.973  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:04:13.973  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:04:13.973  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:04:13.973  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:04:13.973  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:04:13.973  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:04:13.973  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:04:13.973  3506  4839 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
07-05 14:04:13.973  3506  4839 D BatteryService: stay LED for fully charged
,07-05 14:04:13.983  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:04:14.003  4676  4676 D CommonServiceConfiguration: getStringValueSetting
07-05 14:04:14.013  4676  4676 D BatteryMonitor: new battery level: 100
07-05 14:04:14.013  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:14.013  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:14.013  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:04:14.013  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:04:14.293  3506  6477 D SSRM:n  : SIOP:: AP = 320, PST = 392 (W:12), CP = 262, CUR = 127, LCD = 0
07-05 14:04:15.093 10798 10798 I FIPS_bssl: FIPS approved mode (1) | 10798 | app_process
07-05 14:04:15.103 10798 10798 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:04:15.113 10798 10798 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:15.113 10798 10798 D AndroidRuntime: readGMSProperty: start
07-05 14:04:15.113 10798 10798 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:04:15.113 10798 10798 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 14:04:15.113 10798 10798 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 14:04:15.113 10798 10798 D AndroidRuntime: readGMSProperty: end
07-05 14:04:15.113 10798 10798 D AndroidRuntime: addProductProperty: start
07-05 14:04:15.173 10798 10798 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:04:15.253 10798 10798 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:04:15.263 10798 10798 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:04:15.293 10798 10798 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:04:15.313  3506  4113 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
07-05 14:04:15.323  3506  4113 D ResourcesManager: For user 0 new overlays fetched Null
07-05 14:04:15.323  3506  4113 D GameManagerService: identifyGamePackage. com.test.thalitest
07-05 14:04:15.323  3506  4113 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
07-05 14:04:15.333  3506  4113 D ActivityManager: mDVFSHelper.acquire()
07-05 14:04:15.333  3506  4113 V WindowManager: addAppToken: AppWindowToken{f2b93a4 token=Token{2b47237 ActivityRecord{e403336 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
07-05 14:04:15.343  3506  3615 I InjectionManager: Inside getClassLibPath caller 
07-05 14:04:15.353  3506  3615 D SecWifiDisplayUtil: Metadata value : SecSettings2
07-05 14:04:15.353  3506  3615 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7ebb33c V.E...... R.....ID 0,0-0,0}
07-05 14:04:15.353 10812 10812 E Zygote  : v2
07-05 14:04:15.353 10812 10812 I libpersona: KNOX_SDCARD checking this for 10004
07-05 14:04:15.353 10812 10812 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:15.353  3506  4113 I ActivityManager: Start proc 10812:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-05 14:04:15.353 10812 10812 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
07-05 14:04:15.353  3506  4113 D InputDispatcher: Focused application set to: xxxx
07-05 14:04:15.353  3506  4113 D InputDispatcher: Focus left window: 6612
07-05 14:04:15.353  3506  3615 D ISSUE_DEBUG: InputChannelName : 152b21a Starting com.test.thalitest
07-05 14:04:15.353 10798 10798 D AndroidRuntime: Shutting down VM
07-05 14:04:15.353  3506  3589 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{4198a40 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
07-05 14:04:15.353  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-05 14:04:15.363  4072  4072 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
07-05 14:04:15.363 10812 10812 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:04:15.363 10812 10812 E Zygote  : accessInfo : 0
07-05 14:04:15.363 10812 10812 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 14:04:15.373  3045  3045 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-05 14:04:15.383 10812 10812 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:15.383 10812 10812 D ActivityThread: Added TimaKeyStore provider
07-05 14:04:15.393  3506  3525 V WindowOrientationListener: setCurrentAppOrientation :-1
07-05 14:04:15.393  3506  3525 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-05 14:04:15.393  3506  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3506 uid:1000
07-05 14:04:15.393  3506  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:15.393  3506  3615 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-05 14:04:15.403  3506  3589 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{152b21a u0 d0 Starting com.test.thalitest}
07-05 14:04:15.403  3506  3525 D ActivityManager:  Launching com.test.thalitest, updated priority
07-05 14:04:15.413  3506  3506 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-05 14:04:15.413  3506  3588 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-05 14:04:15.423  3045  3959 I SurfaceFlinger: id=13 Removed VSBConnecti (7/12)
07-05 14:04:15.423  3045  4505 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/12)
07-05 14:04:15.433  3045  4505 D libEGL  : eglTerminate EGLDisplay = 0x7fa629de78
07-05 14:04:15.433  6612  6612 V ActivityThread: updateVisibility : ActivityRecord{e1e17bf token=android.os.BinderProxy@8e4cb09 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-05 14:04:15.433  3045  3959 D libEGL  : eglTerminate EGLDisplay = 0x7fa83bee78
07-05 14:04:15.433  3045  3959 D libEGL  : eglTerminate EGLDisplay = 0x7fa83bee78
07-05 14:04:15.433  3045  3130 I SurfaceFlinger: id=7 Removed MauncherAct (4/11)
07-05 14:04:15.433  3045  4538 I SurfaceFlinger: id=7 Removed MauncherAct (-2/11)
07-05 14:04:15.443  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fe403c798
07-05 14:04:15.443  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fe403c798
07-05 14:04:15.443  4432  4432 V ActivityThread: updateVisibility : ActivityRecord{6c735bf token=android.os.BinderProxy@cfafa0 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
07-05 14:04:15.443  4432  4432 D Launcher: onTrimMemory. Level: 20
07-05 14:04:15.453  3506  3615 V WindowStateAnimator: Finishing drawing window Window{152b21a u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-05 14:04:15.463  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
07-05 14:04:15.473  3045  3135 I SurfaceFlinger: id=14 Removed VSBConnecti (4/10)
07-05 14:04:15.473  3045  3130 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/10)
07-05 14:04:15.473  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fe403c798
,07-05 14:04:15.733  3506  3525 I WindowManager: Screenshot max retries 4 of Token{2b47237 ActivityRecord{e403336 u0 com.test.thalitest/.MainActivity t19}} appWin=Window{152b21a u0 d0 Starting com.test.thalitest} drawState=4
,07-05 14:04:15.753 10812 10812 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,07-05 14:04:15.763  3506  4445 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
07-05 14:04:15.763 10812 10812 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-05 14:04:15.763  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false,
,07-05 14:04:15.773  3506  3611 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-05 14:04:15.783 10812 10812 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:04:15.793 10812 10812 I InjectionManager: Inside getClassLibPath caller 
,07-05 14:04:15.813 10812 10812 D InjectionManager: InjectionManager
07-05 14:04:15.813 10812 10812 D InjectionManager: fillFeatureStoreMap com.test.thalitest
,07-05 14:04:15.813 10812 10812 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
07-05 14:04:15.813 10812 10812 I InjectionManager: featureStore :{}
,07-05 14:04:15.823  3506  6477 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:04:15.833 10812 10812 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
07-05 14:04:15.833  3506  6477 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:04:15.833 10812 10812 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
,07-05 14:04:15.873 10812 10812 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410650)
,07-05 14:04:15.933 10812 10812 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
,07-05 14:04:15.943 10812 10812 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:04:15.943 10812 10812 I InjectionManager: Inside getClassLibPath caller 
,07-05 14:04:15.943 10812 10812 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-05 14:04:15.973 10812 10812 I cr_LibraryLoader: Time to load native libraries: 13 ms (timestamps 5148-5161)
07-05 14:04:15.973 10812 10812 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-05 14:04:15.983 10812 10827 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-05 14:04:15.993 10812 10812 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f008d0c}
07-05 14:04:15.993 10812 10812 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-05 14:04:16.003 10812 10812 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 14:04:16.003 10812 10812 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-05 14:04:16.193 10812 10812 D libEGL  : loaded /vendor/lib/egl/libGLES_mali.so
,07-05 14:04:16.233 10812 10812 D libEGL  : eglInitialize EGLDisplay = 0xffb2d5dc
,07-05 14:04:16.233 10812 10812 D         : ro.exynos.dss isEnabled: 0
07-05 14:04:16.233  3506  3588 W ActivityManager: Activity pause timeout for ActivityRecord{e403336 u0 com.test.thalitest/.MainActivity t19}
,07-05 14:04:16.283  3506  4445 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,07-05 14:04:16.283  3506  4445 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29624 com.android.server.am.ActivityManagerService.registerReceiver:22495 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3988 
,07-05 14:04:16.343 10812 10812 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-05 14:04:16.363 10812 10812 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 14:04:16.363 10812 10812 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-05 14:04:16.363 10812 10812 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-05 14:04:16.363 10812 10812 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-05 14:04:16.383 10812 10812 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-05 14:04:16.393 10812 10812 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 14:04:16.423 10812 10812 D Activity: performCreate Call Injection manager
,07-05 14:04:16.423 10812 10812 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
,07-05 14:04:16.433 10812 10812 D SecWifiDisplayUtil: Metadata value : SecSettings2
,07-05 14:04:16.443 10812 10812 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a9f816c I.E...... R.....ID 0,0-0,0}
,07-05 14:04:16.443 10812 10864 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 14:04:16.453  3506  3525 D ISSUE_DEBUG: InputChannelName : 187330f com.test.thalitest/com.test.thalitest.MainActivity
,07-05 14:04:16.453  3506  4113 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-05 14:04:16.453  3506  4113 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 14:04:16.453  3506  3506 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 14:04:16.453  3506  3506 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-05 14:04:16.453 10812 10812 V ActivityThread: updateVisibility : ActivityRecord{17b23ca token=android.os.BinderProxy@36508e3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 14:04:16.473 10812 10812 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 10812
,07-05 14:04:16.483  3506  4113 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/10812 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:04:16.483  3506  4000 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-05 14:04:16.483  3506  4000 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fe09:bad2/64,192.168.1.115/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-05 14:04:16.483  3506  4000 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:04:16.483  3506  4000 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-05 14:04:16.483  3506  4000 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:04:16.493 10812 10827 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-05 14:04:16.503 10812 10812 D SecWifiDisplayUtil: Metadata value : SecSettings2
,07-05 14:04:16.523  3045  3045 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-05 14:04:16.533  3506  3987 D InputDispatcher: Focus entered window: 10812
,07-05 14:04:16.533  3506  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3506 uid:1000
07-05 14:04:16.533  3506  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:16.533 10812 10864 D libEGL  : eglInitialize EGLDisplay = 0xdd33f7c4
,07-05 14:04:16.533 10812 10864 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 14:04:16.533 10812 10864 D         : ro.exynos.dss isEnabled: 0
,07-05 14:04:16.543 10812 10864 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,07-05 14:04:16.553 10812 10812 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-05 14:04:16.573  3506  3525 V WindowStateAnimator: Finishing drawing window Window{187330f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
07-05 14:04:16.573 10812 10812 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-05 14:04:16.573 10812 10812 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-05 14:04:16.573  3506  4113 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 14:04:16.573  3506  3615 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 14:04:16.573  3506  3506 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 14:04:16.583  3506  3615 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +844ms (total +1s238ms)
,07-05 14:04:16.583  3506  3615 D ActivityManager: mDVFSHelper.release()
07-05 14:04:16.583  3506  3615 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e403336 u0 com.test.thalitest/.MainActivity t19} time:125771
07-05 14:04:16.583  3506  3615 D ViewRootImpl: #3 mView = null
,07-05 14:04:16.583  3506  3506 I KnoxTimeoutHandler: SD activityfalse
07-05 14:04:16.583  3045  3135 I SurfaceFlinger: id=15 Removed uhalitest (7/10)
,07-05 14:04:16.583  3045  3959 I SurfaceFlinger: id=15 Removed uhalitest (-2/10)
,07-05 14:04:16.583  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fe403c768
,07-05 14:04:16.593  5136  5136 D SamsungIME: IMPL finishInput
07-05 14:04:16.593  5136  5136 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
07-05 14:04:16.593  5136  5136 D SamsungIME: saveAndClear +
07-05 14:04:16.593  5136  5136 D SamsungIME: saveAndClear -
,07-05 14:04:16.603 10812 10869 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:04:16.603 10812 10869 D libEGL  : eglInitialize EGLDisplay = 0xdc9fb3ec
,07-05 14:04:16.613 10812 10869 D         : ro.exynos.dss isEnabled: 0
,07-05 14:04:16.613 10812 10869 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,07-05 14:04:16.643  3506  4804 V WindowStateAnimator: Finishing drawing window Window{187330f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,07-05 14:04:16.643 10812 10812 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 14:04:16.653  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
,07-05 14:04:16.663 10812 10812 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10812
,07-05 14:04:16.663 10812 10812 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36508e3 time:125859
,07-05 14:04:16.763  3506  6478 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,07-05 14:04:16.803 10812 10812 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:04:16.903 10812 10876 D jxcore_app_log: JniHelper::setJavaVM(0xf4974000), pthread_self() = -637011664
,07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4653a5 added. We now have 1 listener(s)
,07-05 14:04:16.903 10812 10876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 10:D3:8A:FB:85:D4
07-05 14:04:16.903 10812 10876 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "10:D3:8A:FB:85:D4"
07-05 14:04:16.903 10812 10876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:04:16.903 10812 10876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 10:D3:8A:FB:85:D4
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:04:16.903 10812 10876 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bb7788 added. We now have 1 listener(s)
07-05 14:04:16.903 10812 10876 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 14:04:16.913 10812 10876 D BluetoothAdapter: STATE_ON
07-05 14:04:16.913 10812 10876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-05 14:04:16.913 10812 10876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 14:04:16.913 10812 10876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 14:04:16.913 10812 10876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 14:04:16.913 10812 10876 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 14:04:16.923 10812 10876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 14:04:16.923 10812 10876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 10:D3:8A:FB:85:D4
,07-05 14:04:16.923 10812 10876 D BluetoothAdapter: STATE_ON
,07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:16.923 10812 10876 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 14:04:16.923 10812 10876 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:16.923 10812 10876 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 14:04:16.923 10812 10876 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:04:16.933 10812 10812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:16.933 10812 10812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:16.943 10812 10812 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:17.223 10812 10877 W jxcore-log: Initializing JXcore engine
07-05 14:04:17.223 10812 10877 W jxcore-log: JXcore engine is ready
,07-05 14:04:17.233  4157  4157 D Recents : onTaskStackChanged
,07-05 14:04:17.243  4157  4157 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,07-05 14:04:17.243  5167  5167 E audit   : type=1400 msg=audit(1467720257.243:276): avc:  denied  { ioctl } for  pid=10877 comm="Thread-135" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4115 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 14:04:17.243  5167  5167 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:04:17.243  5167  5167 E audit   : type=1300 msg=audit(1467720257.243:276): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=3 a3=d9f7a3c8 items=0 ppid=3104 ppcomm=main pid=10877 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 ses=4294967295 tty=(none) comm="Thread-135" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 14:04:17.243  5167  5167 E audit   : type=1327 msg=audit(1467720257.243:276): proctitle="com.test.thalitest"
07-05 14:04:17.243  5167  5167 E audit   : type=1320 msg=audit(1467720257.243:276): 
07-05 14:04:17.243  5167  5167 E audit   : type=1400 msg=audit(1467720257.243:277): avc:  denied  { ioctl } for  pid=10877 comm="Thread-135" path="socket:[40632]" dev="sockfs" ino=40632 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-05 14:04:17.243  5167  5167 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:04:17.243  5167  5167 E audit   : type=1300 msg=audit(1467720257.243:277): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=39 a1=5451 a2=3 a3=d9f7a3c8 items=0 ppid=3104 ppcomm=main pid=10877 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 ses=4294967295 tty=(none) comm="Thread-135" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 14:04:17.243  5167  5167 E audit   : type=1327 msg=audit(1467720257.243:277): proctitle="com.test.thalitest"
07-05 14:04:17.243  5167  5167 E audit   : type=1320 msg=audit(1467720257.243:277): 
,07-05 14:04:17.253 10812 10877 W jxcore-log: Starting JXcore engine
,07-05 14:04:17.253  4157  4157 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:04:17.293 10812 10877 W jxcore-log: Platform android
07-05 14:04:17.293 10812 10877 W jxcore-log: 
07-05 14:04:17.293 10812 10877 W jxcore-log: Process ARCH arm
07-05 14:04:17.293 10812 10877 W jxcore-log: 
,07-05 14:04:17.383 10812 10877 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:17.383 10812 10877 I jxcore-log: 
07-05 14:04:17.383 10812 10877 W jxcore-log: JXcore engine is started
,07-05 14:04:17.383 10812 10876 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:04:17.383 10812 10812 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:04:18.343  3506  4039 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/19_task.xml.bak
,07-05 14:04:21.863  3506  6477 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:04:23.013  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:04:23.133  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:23.143  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:23.143  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:23.153  4355  6920 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:04:23.153  4355  6920 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:04:23.153  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:04:23.153  4355  6920 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:23.153  4355  6920 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:23.153  4355  6920 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:23.163  9496  9496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:04:23.163  9496  9496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:04:23.163  9496  9496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-05 14:04:23.223 10812 10877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:23.223 10812 10877 I jxcore-log: 
,07-05 14:04:23.223 10812 10877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:23.223 10812 10877 I jxcore-log: 
,07-05 14:04:23.223 10812 10877 D BluetoothAdapter: STATE_ON
,07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:23.223 10812 10877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:23.223 10812 10877 D BluetoothAdapter: STATE_ON
,07-05 14:04:23.223 10812 10877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 14:04:23.223 10812 10877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:23.223 10812 10877 I jxcore-log: 
,07-05 14:04:23.223 10812 10877 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:23.223 10812 10877 I jxcore-log: 
,07-05 14:04:23.443 10812 10877 I jxcore-log: Unit Test app is loaded
07-05 14:04:23.443 10812 10877 I jxcore-log: 
,07-05 14:04:23.453 10812 10877 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:23.453 10812 10877 I jxcore-log: 
,07-05 14:04:23.453 10812 10812 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:23.453 10812 10877 I jxcore-log: My device name is: samsung-SM-G920F
07-05 14:04:23.453 10812 10877 I jxcore-log: 
,07-05 14:04:24.003  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:04:24.003  3506  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:04:24.003  3506  3524 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-61
07-05 14:04:24.003  3506  3524 D BatteryService: stay LED for fully charged
07-05 14:04:24.003  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:24.003  3506  3506 I MotionRecognitionService: Plugged
07-05 14:04:24.003  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:04:24.003  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:04:24.003  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:04:24.003  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:04:24.003  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:04:24.003  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:04:24.003  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:04:24.003  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:24.003  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:04:24.003  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:04:24.003  4676  4676 D CommonServiceConfiguration: getStringValueSetting
07-05 14:04:24.003  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:04:24.003  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:04:24.003  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:04:24.023  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:24.023  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:24.303  3506  6477 D SSRM:n  : SIOP:: AP = 380, PST = 385 (W:12), CP = 262, CUR = 34, LCD = 0
,07-05 14:04:24.323  3506  6477 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:04:25.333  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:25.393  3506  3643 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 14:04:25.403  3506  3643 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-05 14:04:25.573  3506  4290 E Watchdog: !@Sync 4 [07-05 14:04:25.588]
,07-05 14:04:25.723 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:25.723 10812 10877 I jxcore-log: 
,07-05 14:04:25.953 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:25.953 10812 10877 I jxcore-log: 
,07-05 14:04:25.963 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:25.963 10812 10877 I jxcore-log: 
,07-05 14:04:25.973 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:25.973 10812 10877 I jxcore-log: 
,07-05 14:04:25.983 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:25.983 10812 10877 I jxcore-log: 
07-05 14:04:25.983 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:25.983 10812 10877 I jxcore-log: 
,07-05 14:04:26.633  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:04:27.123 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:27.123 10812 10877 I jxcore-log: 
,07-05 14:04:27.133 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:27.133 10812 10877 I jxcore-log: 
,07-05 14:04:27.143 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:27.143 10812 10877 I jxcore-log: 
,07-05 14:04:27.223 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:27.223 10812 10877 I jxcore-log: 
,07-05 14:04:27.273 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:27.273 10812 10877 I jxcore-log: 
,07-05 14:04:27.303 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:27.303 10812 10877 I jxcore-log: 
,07-05 14:04:27.303 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:27.303 10812 10877 I jxcore-log: 
,07-05 14:04:27.413 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:27.413 10812 10877 I jxcore-log: 
,07-05 14:04:27.423 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:27.423 10812 10877 I jxcore-log: 
,07-05 14:04:27.433 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:27.433 10812 10877 I jxcore-log: 
,07-05 14:04:27.433 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:27.433 10812 10877 I jxcore-log: 
,07-05 14:04:27.443 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:27.443 10812 10877 I jxcore-log: 
,07-05 14:04:27.453 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:27.453 10812 10877 I jxcore-log: 
,07-05 14:04:27.493 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:27.493 10812 10877 I jxcore-log: 
,07-05 14:04:27.503 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:27.503 10812 10877 I jxcore-log: 
,07-05 14:04:27.513 10812 10877 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:27.513 10812 10877 I jxcore-log: 
,07-05 14:04:27.523 10812 10877 D BluetoothAdapter: STATE_ON
,07-05 14:04:27.523 10812 10877 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-05 14:04:27.523 10812 10877 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-05 14:04:27.523 10812 10877 I jxcore-log: 
,07-05 14:04:34.063  3506  4446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:04:34.083  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:04:34.063  3506  4446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:04:34.083  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:04:34.063  3506  4446 D BatteryService: online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:147
07-05 14:04:34.063  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:04:34.063  3506  4446 D BatteryService: stay LED for fully charged
07-05 14:04:34.073  3506  3506 I MotionRecognitionService: Plugged
07-05 14:04:34.073  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:04:34.073  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:04:34.073  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:04:34.073  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:04:34.073  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:04:34.073  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:04:34.073  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:04:34.083  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:04:34.093  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:04:34.093  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 14:04:34.093  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:04:34.103  4676  4676 D BatteryMonitor: new battery level: 100,
,07-05 14:04:34.103  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:34.103  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:34.343  3506  6477 D SSRM:n  : SIOP:: AP = 350, PST = 371 (W:18), CP = 262, CUR = 63, LCD = 0
,07-05 14:04:36.623  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:04:36.653  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:04:36.653  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false,
,07-05 14:04:36.663  7572  7660 E SPPClientService: [b] SharedConstants.WHAT_TIMEOUT
,07-05 14:04:43.163  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:04:44.053  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:44.123  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:44.133  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:44.223  3506  3525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:04:44.223  3506  3525 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:04:44.223  3506  3525 D BatteryService: online:4, current avg:100, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:135
07-05 14:04:44.223  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:04:44.223  3506  3525 D BatteryService: stay LED for fully charged
,07-05 14:04:44.253  3506  3506 I MotionRecognitionService: Plugged
07-05 14:04:44.253  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:04:44.253  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:04:44.253  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:04:44.253  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:04:44.253  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:04:44.253  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:04:44.253  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:04:44.263  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:04:44.263  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:04:44.263  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:44.273  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:04:44.283  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:04:44.283  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:04:44.293  4676  4676 D BatteryMonitor: new battery level: 100,
07-05 14:04:44.293  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:44.293  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:04:44.303  4355  6535 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:04:44.303  4355  6535 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:04:44.303  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:04:44.303  4355  6535 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:44.303  4355  6535 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:44.303  4355  6535 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:44.353  9496  9496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:04:44.353  9496  9496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:04:44.353  9496  9496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
07-05 14:04:44.363  3506  6477 D SSRM:n  : SIOP:: AP = 330, PST = 358 (W:22), CP = 262, CUR = 100, LCD = 0
,07-05 14:04:45.333  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:46.643  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:04:46.643  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 14:04:50.483  4355  5702 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:04:51.173  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:04:51.383 10551 10949 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:04:51.453  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:51.463  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:51.513  4355  4369 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:04:51.513  4355  4369 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:51.513  4355  4369 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:04:51.513  4355  4369 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:51.563  4355  6920 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:04:51.563  4355  6920 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:51.563  4355  6920 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:04:51.563  4355  6920 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:51.603 10551 10951 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:04:51.603 10551 10949 E BooksSync: Soft error
07-05 14:04:51.603 10551 10949 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:51.603 10551 10949 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:04:51.603 10551 10949 E BooksSync: Sync error
07-05 14:04:51.603 10551 10949 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:51.603 10551 10949 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:04:51.623 10551 10949 I BooksSync: Finished books sync
,07-05 14:04:51.623 10551 10958 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-05 14:04:51.623 10551 10958 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-05 14:04:51.633  3506  3582 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160360, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:04:51.643  3506  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:04:51.653  4355  6917 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:04:51.653  4355  6917 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:51.653  4355  6917 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:04:51.653  4355  6917 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:51.673 10551 10958 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:04:51.683 10551 10958 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:04:54.393  3506  6477 D SSRM:n  : SIOP:: AP = 310, PST = 348 (W:26), CP = 260, CUR = 100, LCD = 0
,07-05 14:04:55.583  3506  4290 E Watchdog: !@Sync 5 [07-05 14:04:55.590]
,07-05 14:04:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:05:03.653  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:03.653  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:03.723  4355 10666 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-05 14:05:03.723  4355 10666 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-05 14:05:03.723  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-05 14:05:03.723  4355 10666 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:05:03.723  4355 10666 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-05 14:05:03.723  4355 10666 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:05:03.763  4355 10666 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-05 14:05:03.873  4355 10666 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:-818113082>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-05 14:05:03.873  4355 10666 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-05 14:05:03.873  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-05 14:05:03.873  4355 10666 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:05:03.873  4355 10666 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-05 14:05:03.873  4355 10666 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:05:03.933  4355 10666 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-05 14:05:03.993  4355 10666 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-05 14:05:03.993  4355 10666 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-05 14:05:03.993  4355 10666 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-05 14:05:03.993  4355 10666 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:05:03.993  4355 10666 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-05 14:05:03.993  4355 10666 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:05:04.023  4355 10666 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-05 14:05:04.043  4355 10666 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
,07-05 14:05:04.063  4355 10666 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=UNKNOWN).  Giving up.
,07-05 14:05:04.073  4355 10666 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-05 14:05:04.353  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:05:04.423  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:05:04.423  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:05:04.443  3506  6477 D SSRM:n  : SIOP:: AP = 310, PST = 338 (W:26), CP = 259, CUR = 100, LCD = 0
,07-05 14:05:04.753  3506  3516 I art     : Background partial concurrent mark sweep GC freed 53310(3MB) AllocSpace objects, 50(1000KB) LOS objects, 31% free, 35MB/51MB, paused 3.324ms total 251.727ms
,07-05 14:05:05.273  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:05.283  4355  4857 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:05:05.283  4355  4857 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:05.283  4355  4857 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:05:05.283  4355  4857 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:05:05.283  4355  4857 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:05:05.283  4355  4857 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:05:05.323  9496  9496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:05:05.323  9496  9496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:05:05.323  9496  9496 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-05 14:05:05.333  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:11.913  3506  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-05 14:05:11.923  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f8707f2 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84858fc 10242:com.samsung.android.sm.provider/1000}
,07-05 14:05:11.963  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in null rsrc of package com.android.bluetooth
,07-05 14:05:11.963  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:11.963  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/bootagent/bootagent.apk / 1.0 running in null rsrc of package com.samsung.ucs.agent.boot
,07-05 14:05:11.963  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:11.963  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/BluetoothTest/BluetoothTest.apk / 1.0 running in null rsrc of package com.sec.android.app.bluetoothtest
,07-05 14:05:11.973  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:11.973  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/callplushybrid_release_v1.6.6_AndroidVFSigned/callplushybrid_release_v1.6.6_AndroidVFSigned.apk / 1.0 running in null rsrc of package com.vodafone.callplushybrid
,07-05 14:05:11.973  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:11.973  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/SamsungIMEv3_SYSTEMUID_SWIFTKEY_VO/SamsungIMEv3_SYSTEMUID_SWIFTKEY_VO.apk / 1.0 running in null rsrc of package com.sec.android.inputmethod
,07-05 14:05:11.983  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:11.983  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in null rsrc of package com.android.systemui
,07-05 14:05:11.993  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:11.993  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/imsservice/imsservice.apk / 1.0 running in null rsrc of package com.sec.imsservice
,07-05 14:05:11.993  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:11.993  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,07-05 14:05:12.003  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.003  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/EdmSimPinService/EdmSimPinService.apk / 1.0 running in null rsrc of package com.sec.enterprise.mdm.services.simpin
,07-05 14:05:12.003  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.003  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/SamsungTTS/SamsungTTS.apk / 1.0 running in null rsrc of package com.samsung.SMT
,07-05 14:05:12.013  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.013  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/AntHalService/AntHalService.apk / 1.0 running in null rsrc of package com.dsi.ant.server
,07-05 14:05:12.013  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in null rsrc of package com.samsung.voiceserviceplatform
,07-05 14:05:12.013  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.023  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/CSC/CSC.apk / 1.0 running in null rsrc of package com.samsung.sec.android.application.csc
,07-05 14:05:12.023  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.023  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/TuiService/TuiService.apk / 1.0 running in null rsrc of package com.trustonic.tuiservice
,07-05 14:05:12.033  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.033  3506  6478 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package android
,07-05 14:05:12.033  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/Telecom/Telecom.apk / 1.0 running in null rsrc of package com.android.server.telecom
,07-05 14:05:12.033  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartcardManager/SmartcardManager.apk / 1.0 running in null rsrc of package com.sec.smartcard.manager
,07-05 14:05:12.033  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.043  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package com.android.stk
,07-05 14:05:12.043  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.043  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package com.android.stk
,07-05 14:05:12.053  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMediaProvider/SecMediaProvider.apk / 1.0 running in null rsrc of package com.android.providers.media
,07-05 14:05:12.053  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.053  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/ContextProvider/ContextProvider.apk / 1.0 running in null rsrc of package com.samsung.android.providers.context
,07-05 14:05:12.053  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.063  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/BeaconManager_40/BeaconManager_40.apk / 1.0 running in null rsrc of package com.samsung.android.beaconmanager
,07-05 14:05:12.063  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.063  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/Stk2/Stk2.apk / 1.0 running in null rsrc of package com.android.stk2
,07-05 14:05:12.063  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.063  3506  6478 W ResourcesManager: getTopLevelResources: /system/app/Stk2/Stk2.apk / 1.0 running in null rsrc of package com.android.stk2
,07-05 14:05:12.073  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in null rsrc of package com.android.phone
,07-05 14:05:12.073  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:12.073  3506  6478 W ResourcesManager: getTopLevelResources: /system/priv-app/UcsPinpad/UcsPinpad.apk / 1.0 running in null rsrc of package com.samsung.ucs.ucspinpad
,07-05 14:05:12.073  3506  6478 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:14.253  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:14.253  3506  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:05:14.253  3506  3524 D BatteryService: online:4, current avg:-4, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-169
07-05 14:05:14.253  3506  3524 D BatteryService: stay LED for fully charged
07-05 14:05:14.253  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:05:14.253  3506  3506 I MotionRecognitionService: Plugged
07-05 14:05:14.253  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:05:14.253  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:05:14.253  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:05:14.253  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:05:14.253  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:05:14.253  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:05:14.253  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:05:14.263  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:05:14.263  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:05:14.263  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:05:14.263  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:05:14.263  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:05:14.263  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:05:14.263  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:05:14.273  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:05:14.273  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:14.483  3506  6477 D SSRM:n  : SIOP:: AP = 320, PST = 336 (W:24), CP = 258, CUR = -4, LCD = 0
,07-05 14:05:14.663  3506  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-05 14:05:14.663  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{829ecc0 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84858fc 10242:com.samsung.android.sm.provider/1000}
,07-05 14:05:15.153 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.vending
,07-05 14:05:15.153 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.163 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.gallery3d
,07-05 14:05:15.163 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.163 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.shealth
,07-05 14:05:15.173 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.173 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SMusic/SMusic.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.music
,07-05 14:05:15.183 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.183 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.settings
,07-05 14:05:15.193 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.193 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera4/SamsungCamera4.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.camera
,07-05 14:05:15.193 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.203 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.contacts
,07-05 14:05:15.203 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.213 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.contacts
,07-05 14:05:15.213 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.email.provider
,07-05 14:05:15.223 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.223 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.mms
,07-05 14:05:15.233 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.233 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/Vodafone_Updates_v5.6.0_Samsung_signed/Vodafone_Updates_v5.6.0_Samsung_signed.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.vodafone.vodafone360updates
,07-05 14:05:15.243 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.243 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.chrome
,07-05 14:05:15.243 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.253 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.docs
,07-05 14:05:15.263 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.273 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.gm
,07-05 14:05:15.273 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.283 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.talk
,07-05 14:05:15.283 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.293 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.music
,07-05 14:05:15.303 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.313 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.magazines
,07-05 14:05:15.313 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.323 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.plus
,07-05 14:05:15.333 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.343 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.android.calendar
,07-05 14:05:15.343 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.353 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.sbrowser
,07-05 14:05:15.363 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.373 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.videos
,07-05 14:05:15.373 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.393 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.youtube
,07-05 14:05:15.403 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.413 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/Excel_SamsungStub/Excel_SamsungStub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.excel
,07-05 14:05:15.413 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.423 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/GearManager/GearManager.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.app.watchmanager
,07-05 14:05:15.423 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.433 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/PowerPoint_SamsungStub/PowerPoint_SamsungStub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.powerpoint
,07-05 14:05:15.433 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.453 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.googlequicksearchbox
,07-05 14:05:15.463 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.473 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SVoice_1.0/SVoice_1.0.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.voiceserviceplatform
,07-05 14:05:15.483 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.483 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.googlequicksearchbox
,07-05 14:05:15.483 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/ZVideo/ZVideo.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.video
,07-05 14:05:15.493 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.493 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator_M/SecCalculator_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.popupcalculator
,07-05 14:05:15.493 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.503 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.myfiles,
,07-05 14:05:15.513 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.513 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.sm,
,07-05 14:05:15.523 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.523 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.voicenote
,07-05 14:05:15.533 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.533 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/Word_SamsungStub/Word_SamsungStub.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.word
,07-05 14:05:15.543 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.543 10242 11015 W ResourcesManager: getTopLevelResources: /system/priv-app/VodafoneStart-4.11.1-prod-release-AndroidVFSigned_zipaligned/VodafoneStart-4.11.1-prod-release-AndroidVFSigned_zipaligned.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.vodafone.smhs
,07-05 14:05:15.553 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.563 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.books
,07-05 14:05:15.573 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.573 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M_Osup/ClockPackage_M_Osup.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.clockpackage
,07-05 14:05:15.583 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.593 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Dropbox_zero/Dropbox_zero.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.dropbox.android
,07-05 14:05:15.603 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.613 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.maps
,07-05 14:05:15.623 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.633 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.app.memo
,07-05 14:05:15.633 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.653 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/PlayGames/PlayGames.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.play.games
,07-05 14:05:15.653 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.663 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.google.android.apps.plus
,07-05 14:05:15.673 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.skydrive
,07-05 14:05:15.683 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.693 10242 11015 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_zero/SmartRemote_zero.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package tv.peel.app
,07-05 14:05:15.773 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.783 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.sec.android.app.samsungapps
,07-05 14:05:15.793 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.803 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.microsoft.office.onenote-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.microsoft.office.onenote
,07-05 14:05:15.803 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.813 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.vodafone.accesorystore-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.vodafone.accesorystore
,07-05 14:05:15.813 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.823 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.vodafone.android.myweb.launcher-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.vodafone.android.myweb.launcher
,07-05 14:05:15.823 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.833 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.appseleration.speedtest-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.appseleration.speedtest
,07-05 14:05:15.843 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.853 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.wsandroid.suite.vodaemea-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.wsandroid.suite.vodaemea
,07-05 14:05:15.893 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.903 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.appseleration.android.selfcare-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.appseleration.android.selfcare
,07-05 14:05:15.913 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:15.913 10242 11015 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.test.thalitest
,07-05 14:05:15.923 10242 11015 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:05:24.503  3506  6477 D SSRM:n  : SIOP:: AP = 310, PST = 332 (W:24), CP = 257, CUR = -4, LCD = 0
,07-05 14:05:25.333  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:25.583  3506  4290 E Watchdog: !@Sync 6 [07-05 14:05:25.596]
,07-05 14:05:26.743  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:05:34.543  3506  6477 D SSRM:n  : SIOP:: AP = 300, PST = 330 (W:24), CP = 256, CUR = -4, LCD = 0
,07-05 14:05:44.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:05:44.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:05:44.343  3506  4839 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:05:44.343  3506  4839 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4324, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:05:44.343  3506  4839 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:05:44.343  3506  4839 D BatteryService: stay LED for fully charged
07-05 14:05:44.343  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:05:44.353  3506  3506 I MotionRecognitionService: Plugged
07-05 14:05:44.353  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:05:44.353  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:05:44.353  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:05:44.353  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:05:44.353  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:05:44.353  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:05:44.353  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:05:44.353  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:05:44.353  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:44.363  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:05:44.383  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:05:44.383  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:05:44.393  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:05:44.393  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:44.393  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:44.393  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:05:44.563  3506  6477 D SSRM:n  : SIOP:: AP = 300, PST = 328 (W:24), CP = 255, LCD = 0
,07-05 14:05:45.333  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:46.183  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:05:46.183  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:05:54.393  3506  4804 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:05:54.403  3506  4804 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:05:54.403  3506  4804 D BatteryService: online:4, current avg:76, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:131
07-05 14:05:54.403  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:05:54.403  3506  3506 I MotionRecognitionService: Plugged
07-05 14:05:54.403  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:05:54.413  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:05:54.413  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:05:54.413  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:05:54.413  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:05:54.413  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:05:54.413  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:05:54.413  3506  4804 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
07-05 14:05:54.413  3506  4804 D BatteryService: stay LED for fully charged
07-05 14:05:54.423  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:05:54.423  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:54.423  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:05:54.433  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:05:54.433  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:54.433  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:05:54.443  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:05:54.443  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:05:54.443  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:54.593  3506  6477 D SSRM:n  : SIOP:: AP = 300, PST = 327 (W:26), CP = 255, CUR = 76, LCD = 0
,07-05 14:05:55.593  3506  4290 E Watchdog: !@Sync 7 [07-05 14:05:55.602]
,07-05 14:05:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:06:01.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:06:01.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:06:02.503  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:06:02.503  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:06:04.453  3506  4340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:06:04.453  3506  4340 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:06:04.453  3506  4340 D BatteryService: online:4, current avg:100, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:110
07-05 14:06:04.453  3506  4340 D BatteryService: stay LED for fully charged
07-05 14:06:04.453  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:06:04.463  3506  3506 I MotionRecognitionService: Plugged
07-05 14:06:04.463  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:06:04.463  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:06:04.463  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:06:04.463  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:04.463  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:06:04.463  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:06:04.463  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:04.473  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:04.473  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:06:04.473  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:04.493  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:06:04.503  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:04.503  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:04.503  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:06:04.503  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:06:04.503  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:04.613  3506  6477 D SSRM:n  : SIOP:: AP = 300, PST = 322 (W:26), CP = 254, CUR = 100, LCD = 0
,07-05 14:06:05.343  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:14.523  3506  4446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:06:14.523  3506  4446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:06:14.523  3506  4446 D BatteryService: online:4, current avg:106, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:93
07-05 14:06:14.523  3506  4446 D BatteryService: stay LED for fully charged
07-05 14:06:14.523  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:06:14.533  3506  3506 I MotionRecognitionService: Plugged
07-05 14:06:14.533  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:06:14.533  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:06:14.533  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:06:14.533  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:14.533  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:06:14.533  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:06:14.533  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:14.533  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:14.533  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:14.543  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:06:14.563  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:06:14.563  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:06:14.563  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:14.563  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:06:14.563  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:14.573  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:14.633  3506  6477 D SSRM:n  : SIOP:: AP = 300, PST = 320 (W:26), CP = 253, CUR = 106, LCD = 0
,07-05 14:06:21.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:06:21.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:06:23.593  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:06:23.593  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:06:24.583  3506  4445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:06:24.583  3506  4445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:06:24.583  3506  4445 D BatteryService: online:4, current avg:104, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:99
07-05 14:06:24.583  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:06:24.583  3506  4445 D BatteryService: stay LED for fully charged
07-05 14:06:24.593  3506  3506 I MotionRecognitionService: Plugged
07-05 14:06:24.593  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:06:24.593  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:06:24.593  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:06:24.593  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:24.593  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:06:24.593  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:06:24.593  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:24.603  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:24.603  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:06:24.603  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:24.623  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:06:24.633  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:24.633  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:24.633  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:06:24.633  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:24.633  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:06:24.653  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 318 (W:26), CP = 252, CUR = 104, LCD = 0
,07-05 14:06:25.343  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:25.603  3506  4290 E Watchdog: !@Sync 8 [07-05 14:06:25.609]
,07-05 14:06:26.863  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:06:26.983  4515  4571 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 2Kb duration : 116ms lastUpdatedAfter : 163501ms
,07-05 14:06:34.633  3506  4444 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:06:34.643  3506  4444 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:06:34.643  3506  4444 D BatteryService: online:4, current avg:102, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:82
07-05 14:06:34.643  3506  4444 D BatteryService: stay LED for fully charged
07-05 14:06:34.643  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:06:34.653  3506  3506 I MotionRecognitionService: Plugged
07-05 14:06:34.653  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:06:34.653  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:06:34.653  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:06:34.653  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:34.653  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:06:34.653  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:06:34.653  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:06:34.663  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:34.663  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:34.663  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:06:34.683  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:06:34.683  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 316 (W:28), CP = 252, CUR = 102, LCD = 0,
07-05 14:06:34.683  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:06:34.683  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:34.683  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:06:34.693  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:34.693  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:41.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:06:41.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:06:42.743  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:06:42.743  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:06:44.713  3506  6519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:06:44.713  3506  6519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:06:44.713  3506  6519 D BatteryService: online:4, current avg:98, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:95
07-05 14:06:44.713  3506  6519 D BatteryService: stay LED for fully charged
07-05 14:06:44.713  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:06:44.713  3506  3506 I MotionRecognitionService: Plugged
07-05 14:06:44.713  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:06:44.713  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:06:44.713  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:06:44.713  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:44.713  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:06:44.713  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:06:44.713  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:06:44.723  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:44.723  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:06:44.723  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:06:44.743  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:06:44.753  4676  4676 D BatteryMonitor: new battery level: 100
07-05 14:06:44.753  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:44.753  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:44.763  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:06:44.763  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:44.763  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 312 (W:28), CP = 252, CUR = 98, LCD = 0
,07-05 14:06:45.353  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:54.803  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 310 (W:28), CP = 251, CUR = 98, LCD = 0
,07-05 14:06:55.603  3506  4290 E Watchdog: !@Sync 9 [07-05 14:06:55.616]
,07-05 14:06:57.293  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:06:57.323  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:06:57.323  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:06:57.503 10551 11156 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:06:57.563  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:57.563  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:57.603  4355  6917 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:06:57.603  4355  6917 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:06:57.603  4355  6917 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:06:57.603  4355  6917 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:06:57.663  4355  4857 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:06:57.663  4355  4857 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:06:57.663  4355  4857 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:06:57.663  4355  4857 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:06:57.703 10551 11162 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:06:57.703 10551 11156 E BooksSync: Soft error
07-05 14:06:57.703 10551 11156 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:57.703 10551 11156 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:06:57.703 10551 11156 E BooksSync: Sync error
07-05 14:06:57.703 10551 11156 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:57.703 10551 11156 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:06:57.713 10551 11156 I BooksSync: Finished books sync
,07-05 14:06:57.713 10551 11163 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER,
07-05 14:06:57.713  3506  3582 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286480, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:06:57.723 10551 11163 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-05 14:06:57.723  3506  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:06:57.743  4355  6917 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:06:57.743  4355  6917 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:06:57.743  4355  6917 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:06:57.743  4355  6917 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:06:57.773 10551 11163 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:06:57.773 10551 11163 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:06:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:07:02.973  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:07:02.973  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:07:03.943  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:07:03.943  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:07:04.833  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 307 (W:28), CP = 251, CUR = 98, LCD = 0
,07-05 14:07:05.353  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:14.763  3506  3987 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:07:14.763  3506  3987 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:07:14.763  3506  3987 D BatteryService: online:4, current avg:6, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:07:14.763  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:07:14.763  3506  3987 D BatteryService: stay LED for fully charged
07-05 14:07:14.773  3506  3506 I MotionRecognitionService: Plugged
07-05 14:07:14.773  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:07:14.773  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:07:14.773  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:07:14.773  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:07:14.773  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:07:14.773  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:07:14.773  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:07:14.783  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:07:14.783  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:07:14.783  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:14.803  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:07:14.803  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:07:14.803  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:07:14.813  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:07:14.813  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:14.813  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:07:14.853  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 305 (W:30), CP = 251, CUR = 6, LCD = 0
,07-05 14:07:21.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found,
07-05 14:07:21.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:07:24.883  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 303 (W:30), CP = 250, CUR = 6, LCD = 0
,07-05 14:07:25.353  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:25.613  3506  4290 E Watchdog: !@Sync 10 [07-05 14:07:25.623]
,07-05 14:07:26.193  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:07:26.193  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:07:26.283  3506  3928 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:07:26.293  3506  3927 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:07:26.303  3506  3928 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
,07-05 14:07:26.323  3506  3928 I TLC_TIMA_PKM_initialize: initializing...
,07-05 14:07:26.323  3506  3928 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-05 14:07:26.323  3506  3928 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
,07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
,07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: device_id = 0x0
07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: tlc_open() was called
,07-05 14:07:26.323  3506  3928 I TZ: mc_tlc_communication: Opening MobiCore device
,07-05 14:07:26.333  3506  3928 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-05 14:07:26.333  3506  3928 I TZ: mc_tlc_communication: Opening the session
,07-05 14:07:26.363  3506  3928 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-05 14:07:26.383  3506  3928 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 14:07:27.083  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:07:30.243  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:07:30.313  3506  3946 I ActivityManager: Start proc 11200:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-05 14:07:30.323  5955  5955 I PedometerService: onStartCommand  true, true
,07-05 14:07:30.333  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:07:30.333  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:07:30.363  4273  4273 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 14:07:30.363  4273  4273 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-05 14:07:30.383  4273  4273 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-05 14:07:30.393 11200 11200 E Zygote  : v2
07-05 14:07:30.393 11200 11200 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:07:30.393 11200 11200 I libpersona: KNOX_SDCARD not a persona
,07-05 14:07:30.403 11200 11200 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
,07-05 14:07:30.403 11200 11200 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:07:30.403 11200 11200 E Zygote  : accessInfo : 0
,07-05 14:07:30.443 11200 11200 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:07:30.443 11200 11200 D ActivityThread: Added TimaKeyStore provider
,07-05 14:07:30.473 11200 11200 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,07-05 14:07:30.473  3506  4340 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-05 14:07:30.473 11200 11200 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-05 14:07:30.483 11200 11200 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:07:30.483 11200 11200 I InjectionManager: Inside getClassLibPath caller 
,07-05 14:07:30.493 11200 11200 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,07-05 14:07:30.503 11200 11200 D InjectionManager: InjectionManager
07-05 14:07:30.503 11200 11200 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,07-05 14:07:30.503 11200 11200 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
07-05 14:07:30.503 11200 11200 I InjectionManager: featureStore :{}
,07-05 14:07:30.543  3506  4445 I ActivityManager: Killing 8974:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #31
,07-05 14:07:30.563  3506  6505 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,07-05 14:07:32.973  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 14:07:32.973  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:07:32.993  3506  3928 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:32.993  3506  3928 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:34.203  3058  3722 D Netd    : Iface wlan0 link up
,07-05 14:07:34.203  3506  3591 D Tethering: interfaceLinkStateChanged wlan0, true
07-05 14:07:34.203  3506  3591 D Tethering: interfaceStatusChanged wlan0, true
,07-05 14:07:34.213  4273  4273 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
07-05 14:07:34.213  4273  4273 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-05 14:07:34.223  4676  4686 D PdnController: Interface Changed wlan0 link up
,07-05 14:07:34.223  3506  3991 D WifiP2pService: InactiveState{ what=147461 }
07-05 14:07:34.223  3506  3991 D WifiP2pService: P2pEnabledState{ what=147461 }
07-05 14:07:34.223  3506  3991 D WifiP2pService: DefaultState{ what=147461 }
,07-05 14:07:34.253  3506  3506 I CLocInfoService: External Intent Received android.net.wifi.SCAN_RESULTS
,07-05 14:07:34.263  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fafafdd u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{579035c 4072:com.android.systemui/u0a55}
,07-05 14:07:34.913  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 302 (W:30), CP = 250, CUR = 6, LCD = 0
,07-05 14:07:44.823  3506  4115 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:07:44.823  3506  4115 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:07:44.823  3506  4115 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:07:44.823  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:07:44.823  3506  4115 D BatteryService: stay LED for fully charged
07-05 14:07:44.833  3506  3506 I MotionRecognitionService: Plugged
07-05 14:07:44.833  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:07:44.833  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:07:44.833  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:07:44.833  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:07:44.833  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:07:44.833  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:07:44.833  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:07:44.843  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:07:44.843  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:07:44.843  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:44.863  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:07:44.863  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:07:44.863  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:07:44.873  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:07:44.873  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:07:44.873  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:44.933  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 300 (W:30), CP = 250, LCD = 0
,07-05 14:07:45.353  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:54.973  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 299 (W:30), CP = 250, LCD = 0
,07-05 14:07:55.623  3506  4290 E Watchdog: !@Sync 11 [07-05 14:07:55.629]
,07-05 14:07:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:08:02.703  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:08:02.753  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{24acb20 u0 com.sec.spp.push.ACTION_SEND_PING_MESSAGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6467d1f 7572:com.sec.spp.push/u0a33}
,07-05 14:08:02.763  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:08:02.763  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:08:02.783  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:08:02.783  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 14:08:02.833 11261 11261 E Zygote  : v2
07-05 14:08:02.833 11261 11261 I libpersona: KNOX_SDCARD checking this for 10033
07-05 14:08:02.833 11261 11261 I libpersona: KNOX_SDCARD not a persona
,07-05 14:08:02.833 11261 11261 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
07-05 14:08:02.833  3506  4445 I ActivityManager: Start proc 11261:com.sec.spp.push:RemoteDlcProcess/u0a33 for broadcast-3 com.sec.spp.push/.dlc.sender.DlcRequestReceiver
07-05 14:08:02.833 11261 11261 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:08:02.843 11261 11261 E Zygote  : accessInfo : 0
,07-05 14:08:02.843 11261 11261 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.sec.spp.push:RemoteDlcProcess 
,07-05 14:08:02.863 11261 11261 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:08:02.863 11261 11261 D ActivityThread: Added TimaKeyStore provider
,07-05 14:08:02.883  7572  7660 E SPPClientService: [b] __PingReply__
,07-05 14:08:02.893  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{ae1794c: PendingIntentRecord{e7c6cd9 com.sec.spp.push broadcastIntent}}
,07-05 14:08:02.903  3506  6505 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1bdfd95 u0 com.sec.dlc.DLC_REQUEST qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7668eaa 11261:com.sec.spp.push:RemoteDlcProcess/u0a33}
,07-05 14:08:02.913 11261 11261 W ResourcesManager: getTopLevelResources: /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk / 1.0 running in com.sec.spp.push rsrc of package com.sec.spp.push
,07-05 14:08:02.913  3506  4839 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-05 14:08:02.913 11261 11261 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-05 14:08:02.913 11261 11261 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:08:02.913 11261 11261 I InjectionManager: Inside getClassLibPath caller 
,07-05 14:08:02.923 11261 11261 W System  : ClassLoader referenced unknown path: /system/priv-app/SPPPushClient_Prod/lib/arm64
,07-05 14:08:02.933 11261 11261 D SPPClientService: Create
,07-05 14:08:02.933 11261 11261 D InjectionManager: InjectionManager
,07-05 14:08:02.933 11261 11261 D InjectionManager: fillFeatureStoreMap com.sec.spp.push
07-05 14:08:02.933 11261 11261 I InjectionManager: Constructor com.sec.spp.push, Feature store :{}
07-05 14:08:02.933 11261 11261 I InjectionManager: featureStore :{}
,07-05 14:08:02.933 11261 11279 D SPPClientService: Create DLC
,07-05 14:08:02.943 11261 11279 E SPPClientService: ShipBuild Binary : True
,07-05 14:08:02.953  3506  4340 V AlarmManager:  remove PendingIntent] PendingIntent{a52de38: PendingIntentRecord{c4dde11 com.sec.spp.push broadcastIntent}}
,07-05 14:08:02.963  3506  4840 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8f6eb76 u0 com.sec.spp.push.ACTION_HANDLE_PING_SUCCESS_EVENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6467d1f 7572:com.sec.spp.push/u0a33}
,07-05 14:08:02.993  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{773a5e4: PendingIntentRecord{a11af5a com.sec.spp.push broadcastIntent}}
,07-05 14:08:03.043  3506  4115 I ActivityManager: Killing 9745:com.google.android.apps.magazines/u0a126 (adj 15): DHA:empty #31
,07-05 14:08:03.073  3506  4446 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,07-05 14:08:05.013  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 298 (W:30), CP = 249, LCD = 0
,07-05 14:08:05.353  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:12.763  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:08:12.763  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 14:08:14.883  3506  4840 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:08:14.883  3506  4840 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:08:14.883  3506  4840 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:08:14.883  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:08:14.883  3506  4840 D BatteryService: stay LED for fully charged
07-05 14:08:14.883  3506  3506 I MotionRecognitionService: Plugged
07-05 14:08:14.883  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:08:14.883  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:08:14.883  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:08:14.883  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:08:14.883  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:08:14.883  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:08:14.883  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:08:14.893  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:08:14.903  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:08:14.893  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:14.913  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:08:14.923  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:14.923  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:14.933  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:08:14.933  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:08:14.933  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:08:15.073  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 297 (W:30), CP = 249, LCD = 0
,07-05 14:08:25.113  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:30), CP = 249, LCD = 0,
,07-05 14:08:25.363  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:25.623  3506  4290 E Watchdog: !@Sync 12 [07-05 14:08:25.636]
,07-05 14:08:27.193  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:08:35.163  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:30), CP = 249, LCD = 0
,07-05 14:08:44.933  3506  4115 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:45.193  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 295 (W:30), CP = 248, LCD = 0
,07-05 14:08:45.363  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:46.783  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:08:55.243  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 294 (W:30), CP = 248, LCD = 0
,07-05 14:08:55.633  3506  4290 E Watchdog: !@Sync 13 [07-05 14:08:55.643]
,07-05 14:08:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:09:05.283  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 294 (W:30), CP = 248, LCD = 0
,07-05 14:09:05.373  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:14.983  3506  4445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:09:14.983  3506  4445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:09:14.983  3506  4445 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:09:14.993  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:09:14.993  3506  4445 D BatteryService: stay LED for fully charged
07-05 14:09:14.993  3506  3506 I MotionRecognitionService: Plugged
07-05 14:09:14.993  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:09:14.993  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:09:14.993  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:09:14.993  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:09:14.993  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:09:14.993  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:09:14.993  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:09:15.003  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:09:15.003  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:09:15.003  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:15.013  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:15.013  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:09:15.023  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:09:15.023  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:09:15.023  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:09:15.033  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:15.323  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 293 (W:30), CP = 248, LCD = 0
,07-05 14:09:25.353  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 292 (W:30), CP = 248, LCD = 0
,07-05 14:09:25.373  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:25.643  3506  4290 E Watchdog: !@Sync 14 [07-05 14:09:25.649]
,07-05 14:09:27.303  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:09:27.383  4515  4571 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 65ms lastUpdatedAfter : 180400ms
,07-05 14:09:35.393  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 291 (W:30), CP = 248, LCD = 0
,07-05 14:09:45.033  3506  3525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:09:45.033  3506  3525 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:09:45.033  3506  3525 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:09:45.033  3506  3525 D BatteryService: stay LED for fully charged
07-05 14:09:45.033  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:09:45.033  3506  3506 I MotionRecognitionService: Plugged
07-05 14:09:45.033  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:09:45.033  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:09:45.033  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:09:45.033  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:09:45.033  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:09:45.033  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:09:45.033  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:09:45.043  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:09:45.043  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:09:45.043  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:09:45.063  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:09:45.073  4676  4676 D BatteryMonitor: new battery level: 100
07-05 14:09:45.073  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:09:45.073  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:45.083  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:09:45.083  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:09:45.373  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:45.443  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 291 (W:30), CP = 247, LCD = 0
,07-05 14:09:55.473  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 290 (W:30), CP = 247, LCD = 0
,07-05 14:09:55.643  3506  4290 E Watchdog: !@Sync 15 [07-05 14:09:55.657]
,07-05 14:10:05.383  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:05.513  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:30), CP = 247, LCD = 0
,07-05 14:10:15.093  3506  6519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:10:15.093  3506  6519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:10:15.093  3506  6519 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:10:15.093  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:10:15.093  3506  6519 D BatteryService: stay LED for fully charged
07-05 14:10:15.103  3506  3506 I MotionRecognitionService: Plugged
07-05 14:10:15.103  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:10:15.103  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:10:15.103  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:10:15.103  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:10:15.103  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:10:15.103  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:10:15.103  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:10:15.113  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:10:15.113  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:10:15.113  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:10:15.133  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:10:15.143  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:10:15.143  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:15.143  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:10:15.143  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:10:15.143  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:10:15.553  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:30), CP = 247, LCD = 0
,07-05 14:10:15.883  3113  3113 I bootchecker: bootchecker wake up!!
,07-05 14:10:25.383  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:25.593  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 288 (W:30), CP = 247, LCD = 0
,07-05 14:10:25.653  3506  4290 E Watchdog: !@Sync 16 [07-05 14:10:25.661]
,07-05 14:10:27.493  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:10:35.633  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), CP = 247, LCD = 0
,07-05 14:10:45.153  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:10:45.153  3506  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4324, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:10:45.153  3506  3524 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:10:45.153  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:10:45.163  3506  3506 I MotionRecognitionService: Plugged
07-05 14:10:45.163  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:10:45.163  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:10:45.163  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:10:45.163  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:10:45.163  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:10:45.163  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:10:45.163  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:10:45.163  3506  3524 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
07-05 14:10:45.163  3506  3524 D BatteryService: stay LED for fully charged
,07-05 14:10:45.183  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:10:45.183  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:10:45.183  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:45.203  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:10:45.203  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:10:45.203  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:10:45.213  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:10:45.213  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:10:45.213  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:45.383  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:45.673  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), CP = 246, LCD = 0
,07-05 14:10:55.653  3506  4290 E Watchdog: !@Sync 17 [07-05 14:10:55.663]
,07-05 14:10:55.703  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 287 (W:30), CP = 246, LCD = 0
,07-05 14:11:05.383  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:05.743  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), CP = 246, LCD = 0
,07-05 14:11:09.033  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:11:09.063  5955  5955 I PedometerService: onStartCommand  true, true
,07-05 14:11:09.083  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:11:09.083  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:11:09.193 10551 11328 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:11:09.253  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:11:09.253  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:11:09.283  4355  6535 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:11:09.283  4355  6535 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:11:09.283  4355  6535 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:11:09.283  4355  6535 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:11:09.333  4355  6920 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:11:09.333  4355  6920 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:11:09.333  4355  6920 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:11:09.333  4355  6920 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:11:09.373 10551 11329 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:11:09.373 10551 11328 E BooksSync: Soft error
07-05 14:11:09.373 10551 11328 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:11:09.373 10551 11328 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:11:09.373 10551 11328 E BooksSync: Sync error
07-05 14:11:09.373 10551 11328 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:11:09.373 10551 11328 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:11:09.383 10551 11328 I BooksSync: Finished books sync
,07-05 14:11:09.383 10551 11335 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-05 14:11:09.393 10551 11335 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-05 14:11:09.393  3506  3582 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 538221, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:11:09.403  3506  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:11:09.413  4355  6535 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:11:09.413  4355  6535 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:11:09.413  4355  6535 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:11:09.413  4355  6535 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:11:09.453 10551 11335 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:11:09.453 10551 11335 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:11:15.213  3506  4113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:11:15.213  3506  4113 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:11:15.213  3506  4113 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:11:15.213  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:11:15.213  3506  4113 D BatteryService: stay LED for fully charged
07-05 14:11:15.223  3506  3506 I MotionRecognitionService: Plugged
07-05 14:11:15.223  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:11:15.223  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:11:15.223  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:11:15.223  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:11:15.223  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:11:15.223  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:11:15.223  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:11:15.233  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:11:15.233  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:11:15.233  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:15.253  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:11:15.263  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:11:15.263  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:15.263  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:11:15.263  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:11:15.273  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:11:15.773  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), CP = 246, LCD = 0
,07-05 14:11:25.393  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:25.663  3506  4290 E Watchdog: !@Sync 18 [07-05 14:11:25.674]
,07-05 14:11:25.813  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:30), CP = 246, LCD = 0
,07-05 14:11:27.633  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:11:35.853  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), CP = 246, LCD = 0
,07-05 14:11:41.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:11:41.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:11:45.263  3506  3987 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:45.393  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:45.903  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), CP = 245, LCD = 0
,07-05 14:11:46.253  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:11:46.253  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:11:46.783  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:11:55.673  3506  4290 E Watchdog: !@Sync 19 [07-05 14:11:55.681]
,07-05 14:11:55.943  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 285 (W:30), CP = 245, LCD = 0
,07-05 14:11:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:12:05.403  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:05.983  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), CP = 245, LCD = 0
,07-05 14:12:15.313  3506  3525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:16.013  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), CP = 245, LCD = 0
,07-05 14:12:25.403  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:25.683  3506  4290 E Watchdog: !@Sync 20 [07-05 14:12:25.688]
,07-05 14:12:26.053  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:30), CP = 245, LCD = 0
,07-05 14:12:26.283  3506  3928 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 14:12:26.283  3506  3928 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:12:26.293  3506  3927 D TimaService: TimaServiceHandler.handleMessage what =1,
,07-05 14:12:27.743  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:12:27.873  4515  4571 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 112ms lastUpdatedAfter : 180490ms
,07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10009, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10017, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10020, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10023, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10024, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10025, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10028, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10030, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10038, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10051, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLock,ed: 10059, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10060, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10062, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10063, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10066, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10071, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10085, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10088, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10096, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10103, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10107, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10109, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10144, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10148, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10157, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10158, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10160, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10168, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.843  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10169, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10183, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10186, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10187, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10191, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10192, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10197, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10198, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10210, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:31.853  3506  3582 D NetworkPolicy: isUidForegroundLocked: 10211, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:31.933  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 14:12:31.933  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:12:31.953  3506  3615 I ActivityManager: setMaxStartingBackgroundTimer onfinish
07-05 14:12:31.953  3506  3615 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-05 14:12:31.953  3506  3928 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 14:12:31.953  3506  3928 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:12:36.083  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 245, LCD = 0
,07-05 14:12:41.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:12:41.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:12:41.853  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:12:41.853  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:12:45.363  3506  4514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:12:45.373  3506  4514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:12:45.373  3506  4514 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:12:45.373  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:12:45.373  3506  4514 D BatteryService: stay LED for fully charged
07-05 14:12:45.373  3506  3506 I MotionRecognitionService: Plugged
07-05 14:12:45.373  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:12:45.383  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:12:45.383  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:12:45.383  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:12:45.383  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:12:45.383  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:12:45.383  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:12:45.393  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:12:45.393  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:12:45.393  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:45.403  3506  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:45.413  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:12:45.423  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:12:45.423  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:45.423  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:12:45.423  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:12:45.433  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:12:46.123  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 245, LCD = 0
,07-05 14:12:55.683  3506  4290 E Watchdog: !@Sync 21 [07-05 14:12:55.696]
,07-05 14:12:56.153  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 244, LCD = 0
,07-05 14:13:01.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:01.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:02.663  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:02.663  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:03.883  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:13:06.193  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), CP = 244, LCD = 0
,07-05 14:13:15.423  3506  4113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:13:15.423  3506  4113 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:13:15.423  3506  4113 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:13:15.423  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:13:15.423  3506  4113 D BatteryService: stay LED for fully charged
07-05 14:13:15.423  3506  3506 I MotionRecognitionService: Plugged
07-05 14:13:15.423  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:13:15.423  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:13:15.423  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:13:15.423  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:13:15.423  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:13:15.423  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:13:15.423  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:13:15.433  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:13:15.433  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:15.443  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:13:15.463  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:13:15.473  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:13:15.473  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:15.473  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:13:15.473  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:13:15.473  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:13:16.233  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), CP = 244, LCD = 0
,07-05 14:13:21.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:21.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:23.733  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:23.743  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:25.693  3506  4290 E Watchdog: !@Sync 22 [07-05 14:13:25.703]
,07-05 14:13:26.273  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), CP = 244, LCD = 0
,07-05 14:13:27.983  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:13:36.303  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), CP = 244, LCD = 0
,07-05 14:13:41.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:41.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:44.323  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:44.323  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:45.473  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:46.343  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), CP = 244, LCD = 0
,07-05 14:13:55.693  3506  4290 E Watchdog: !@Sync 23 [07-05 14:13:55.708]
,07-05 14:13:56.383  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), CP = 244, LCD = 0
,07-05 14:14:01.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:14:01.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:14:05.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:14:05.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:14:06.423  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 244, LCD = 0
,07-05 14:14:15.533  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:16.453  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 243, LCD = 0
,07-05 14:14:25.703  3506  4290 E Watchdog: !@Sync 24 [07-05 14:14:25.716]
,07-05 14:14:25.853  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:14:25.853  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:14:26.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:14:26.293  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:14:26.513  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 243, LCD = 0
,07-05 14:14:26.593  3506  3516 I art     : Background sticky concurrent mark sweep GC freed 84683(8MB) AllocSpace objects, 340(6MB) LOS objects, 30% free, 35MB/51MB, paused 3.552ms total 104.351ms
,07-05 14:14:28.103  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:14:36.543  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 243, LCD = 0
,07-05 14:14:42.453  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:14:42.453  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:14:45.593  3506  4113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:14:45.593  3506  4113 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:14:45.593  3506  4113 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:14:45.593  3506  4113 D BatteryService: stay LED for fully charged
07-05 14:14:45.593  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:14:45.603  3506  3506 I MotionRecognitionService: Plugged
07-05 14:14:45.603  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:14:45.603  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:14:45.603  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:14:45.603  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:14:45.603  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:14:45.603  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:14:45.603  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:14:45.603  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:14:45.613  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:14:45.603  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:45.623  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:14:45.633  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:14:45.633  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:14:45.633  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:14:45.643  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:45.643  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:46.303  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:14:46.303  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:14:46.583  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 243, LCD = 0
,07-05 14:14:46.783  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:14:55.713  3506  4290 E Watchdog: !@Sync 25 [07-05 14:14:55.723]
,07-05 14:14:56.613  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 243, LCD = 0
,07-05 14:15:00.243  3073  3127 D Sensorhubs: readContextData: 1, 1, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0
07-05 14:15:00.243  3506  3949 D SensorHubManager: onGetSensorHubDataLocked: library(18) = 1, 1, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0
,07-05 14:15:00.253  3506  3948 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 12, 15, 0,,
,07-05 14:15:00.253  3506  3948 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 15, 0
,07-05 14:15:00.263  3073  3127 D Sensorhubs: readContextData: 1, 1, 44, 1, 1, 3, 2, -107, -69, 116, 2, 0, 0, 0, 0, 0, 0, 0, 0, 6, -102, 76, 2, 0, 0, 0, 0, 0, 0, 0, 0, 2, -115, 114, 1, 0, 0, 0, 0, 0, 0, 0, 0, 2, 6, -125,
07-05 14:15:00.263  3506  3949 D SensorHubManager: onGetSensorHubDataLocked: library(46) = 1, 1, 44, 1, 1, 3, 2, -107, -69, 116, 2, 0, 0, 0, 0, 0, 0, 0, 0, 6, -102, 76, 2, 0, 0, 0, 0, 0, 0, 0, 0, 2, -115, 114, 1, 0, 0, 0, 0, 0, 0, 0, 0, 2, 6, -125
,07-05 14:15:00.273  3073  3073 D Sensorhubs: sendContextData: -63, 14, 12, 15, 0,
,07-05 14:15:00.283  3506  3948 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :18], AP_SLEEP,
,07-05 14:15:00.283  3506  3948 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 18,
,07-05 14:15:00.283  3506  3948 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0,,
,07-05 14:15:00.293  3506  3948 I CAE     : parse(PedometerRunner.java:353) - parse start:3
,07-05 14:15:00.303  3506  3948 D CAE     : display(PedometerRunner.java:317) - ================= PEDOMETER =================
07-05 14:15:00.303  3506  3948 I CAE     : display(PedometerRunner.java:339) - C=[0.0], WF=[0.0], WUSCD=[0], UDSCD=[0], RSCD=[0], RUSCD=[0], WSC=[0], RUSC=[0], DD=[0.0], WDSC=[0], RDSCD=[0], RDSC=[0], S=[0.0], WUSC=[0], D=[0.0], SS=[0], TSCD=[0], WDSCD=[0], RSC=[0], TSC=[0], UDSC=[0], CD=[0.0], WSCD=[0]
07-05 14:15:00.303  3506  3948 I CAE     : parse(PedometerRunner.java:823) - parse end:18
07-05 14:15:00.303  3506  3948 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 12, 15, 0,
07-05 14:15:00.303  3506  3948 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 15, 0
,07-05 14:15:00.303  3506  3951 D SContext.CaeProvider.PedometerImpl: display() : mode = [normal],  tsc = [0], wsc = [0], rsc = [0]
07-05 14:15:00.303  3506  3951 D SContextService: updateSContext() : event = Pedometer
,07-05 14:15:00.303  3073  3128 D Sensorhubs: sendContextData: -63, 14, 12, 15, 0
,07-05 14:15:00.313  3506  3948 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :46], AP_SLEEP
,07-05 14:15:00.313  3506  3948 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 46
,07-05 14:15:00.313  3506  3948 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 44, 1, 1, 3, 2, -107, -69, 116, 2, 0, 0, 0, 0, 0, 0, 0, 0, 6, -102, 76, 2, 0, 0, 0, 0, 0, 0, 0, 0, 2, -115, 114, 1, 0, 0, 0, 0, 0, 0, 0, 0, 2, 6, -125,
,07-05 14:15:00.313  3506  3948 I CAE     : parse(SLMonitorRunner.java:301) - parse:4
,07-05 14:15:00.313  3506  3948 D CAE     : parse(SLMonitorRunner.java:323) - dataSize:3
,07-05 14:15:00.323  5955  5955 I Sensor[0x06]: [0x01] 2
,07-05 14:15:00.323  3506  3948 D CAE     : display(SLMonitorRunner.java:604) - ================= STEP_LEVEL_MONITOR =================
07-05 14:15:00.323  3506  3948 I CAE     : display(SLMonitorRunner.java:721) - DT=[1], DC=[3], TS=[1467720167284], ST=[SE,SE,ST], SC=[0,0,0], DI=[0.0,0.0,0.0], CA=[0.0,0.0,0.0], DU=[432716,167282,132739]
,07-05 14:15:00.323  3506  3951 D SContextService: updateSContext() : event = Step Level Monitor
,07-05 14:15:00.343  5955  5955 I Sensor[0x06]: [0x01] 33
,07-05 14:15:00.353  5955  5955 I Sensor[0x04]: [0x01] 1467720167284[0x02] 0[0x03] 2[0x04] 432716
07-05 14:15:00.353  5955  5955 I Sensor[0x04]: [0x01] 1467720600000[0x02] 0[0x03] 2[0x04] 167282
07-05 14:15:00.353  5955  5955 I Sensor[0x04]: [0x01] 1467720767282[0x02] 0[0x03] 1[0x04] 132739
,07-05 14:15:02.413  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:15:02.413  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:15:06.303  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:15:06.303  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:15:06.653  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 243, LCD = 0
,07-05 14:15:15.653  3506  4340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:15:15.653  3506  4340 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:15:15.653  3506  4340 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:15:15.653  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:15:15.653  3506  4340 D BatteryService: stay LED for fully charged
07-05 14:15:15.653  3506  3506 I MotionRecognitionService: Plugged
07-05 14:15:15.653  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:15:15.663  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:15:15.663  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:15:15.663  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:15:15.663  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:15:15.663  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:15:15.663  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:15:15.663  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:15:15.663  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:15.673  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:15:15.683  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:15:15.693  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:15.693  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:15:15.693  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:15:15.703  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:15:15.703  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:16.683  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 243, LCD = 0,
,07-05 14:15:24.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:15:24.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:15:25.723  3506  4290 E Watchdog: !@Sync 26 [07-05 14:15:25.730]
,07-05 14:15:26.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:15:26.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:15:26.723  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 242, LCD = 0
,07-05 14:15:27.393  3506  3961 D InputReader: Input event(6): value=1 when=796580430000
,07-05 14:15:27.393  3506  3961 D InputReader: !@notifyKey(172), action=0
,07-05 14:15:27.403  3506  3961 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,07-05 14:15:27.423  3506  3961 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1200000  uid : 1000  pid : 3506  pkgName : WAKEUP_BOOSTER@31
,07-05 14:15:27.433  3506  3961 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-05 14:15:27.443  3506  3961 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 3506) eventTime = 796580 event = 1
07-05 14:15:27.443  3506  3961 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 3506) (1)
07-05 14:15:27.443  3506  3961 I PowerManagerService: Waking up from sleep (uid 1000)...
07-05 14:15:27.443  3506  3961 D InputManager-JNI: setInteractive(true)
07-05 14:15:27.443  3506  4030 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
,07-05 14:15:27.443  3506  4030 V KeyguardServiceDelegate: onStartedWakingUp()
07-05 14:15:27.443  3506  3961 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-05 14:15:27.443  3506  3961 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-05 14:15:27.443  3506  3961 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-05 14:15:27.443  4072  5110 D KeyguardViewMediator: onStartedWakingUp, seq = 4
07-05 14:15:27.443  3506  3961 D PowerManagerService: mDisplayReady: false
07-05 14:15:27.443  3506  3961 D InputManager-JNI: Disable repeat for home key when device wake up
07-05 14:15:27.443  3506  3961 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-05 14:15:27.443  4072  5110 D KeyguardViewMediator: notifyStartedWakingUp
07-05 14:15:27.443  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:27.443  4072  4072 D KeyguardViewMediator: handleNotifyWakingUp
07-05 14:15:27.443  3506  3620 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
07-05 14:15:27.443  4072  4072 D PhoneStatusBar: onUnlockHintStarted isSmartLock = false, isInSecureByLockTimeout=false
07-05 14:15:27.443  3506  3620 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-05 14:15:27.443  4072  4072 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,07-05 14:15:27.443  4072  4072 D KeyguardFingerPrint: shouldListenForFingerprint ( isFingerPrintLockscreen = false , getLockoutAttemptDeadline = false , mIsUnlockingWithFingerprintForced = false
,07-05 14:15:27.443  4072  4072 V KeyguardUpdateMonitor: stopListeningForFingerprint()
07-05 14:15:27.443  5955  5955 I PedometerService: onStartCommand  true, true
,07-05 14:15:27.453  3506  3588 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,07-05 14:15:27.463  3506  3620 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@95fe644)
07-05 14:15:27.463  3506  3620 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
,07-05 14:15:27.463  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: return as screen on blocked
07-05 14:15:27.463  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-05 14:15:27.473 10812 10812 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-05 14:15:27.473  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 2, mProxSensorScreenOff: false
07-05 14:15:27.473 10812 10812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-05 14:15:27.473  4072  5110 D KeyguardViewMediator: notifyScreenOn
07-05 14:15:27.473  4072  4072 D KeyguardViewMediator: handleNotifyScreenTurningOn
07-05 14:15:27.473  4072  4072 D KeyguardEffectViewController: onScreenTurningOn
,07-05 14:15:27.473  3506  4032 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable,
07-05 14:15:27.473  3506  3620 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-05 14:15:27.473  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
07-05 14:15:27.473  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:27.473  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:27.473  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: return as screen on blocked
07-05 14:15:27.473  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:27.473  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
07-05 14:15:27.473  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:27.473  3506  3633 I libsuspend: !@autosuspend_wakeup_count_disable
,07-05 14:15:27.473  3506  4032 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_BRIGHTNESS
07-05 14:15:27.473  3506  3633 D DisplayManagerService: !@display_state: OFF -> ON brightness: 0 -> 0
07-05 14:15:27.473  3506  3633 I libsuspend: !@autosuspend_wakeup_count_disable done
07-05 14:15:27.473  3506  3615 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-05 14:15:27.473  3506  4032 I CAE     : setPropertyValue(AutoBrightnessRunner.java:129) - Mode = 0
07-05 14:15:27.473  3045  3045 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7fad3c3c00
07-05 14:15:27.473  3045  3045 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(2)
,07-05 14:15:27.473  3506  4032 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 48, 1, 0,
07-05 14:15:27.473  3506  4032 D SensorHubManager: SendSensorHubData: send data = -63, 23, 48, 1, 0
,07-05 14:15:27.483 10812 10812 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-05 14:15:27.483 10812 10812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 14:15:27.493  3073  3073 D Sensorhubs: sendContextData: -63, 23, 48, 1, 0
07-05 14:15:27.493  5136  5136 E SamsungIME: invoke(): method is null
07-05 14:15:27.493  5136  5136 D SamsungIME: showDlgMsgBox : false true true
,07-05 14:15:27.493  3506  3987 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,07-05 14:15:27.493  3506  4032 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
07-05 14:15:27.493  3506  4032 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_BRIGHTNESS
07-05 14:15:27.493  3506  4032 D SContext.CaeProvider: setAttribute() : 0
07-05 14:15:27.493  3506  4032 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_BRIGHTNESS
,07-05 14:15:27.493  3506  4032 V CAE     : start(ContextProvider.java:128)
,07-05 14:15:27.503  3506  4032 V CAE     : clear(AutoBrightnessRunner.java:297)
,07-05 14:15:27.503  3506  4032 V CAE     : enable(AutoBrightnessRunner.java:256)
,07-05 14:15:27.503  3506  4032 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 23, 48, 2, 12, 8, 8, 9, 9, 9, 9, 8, 8, 9, 9, 9, 9, 0, 0, 0, 0, 0, 0, 0, 0, 5, 0, 0, 0, 50, 0, 0, 0, -24, 3, 0, 0, -24, 3, 0, 0, 15, 39, 0, 0, 16, 39, 0, 0, 10, 0, 0, 0, 37, 0, 0, 0, 59, 0, 0, 0, -122, 0, 0, 0, -37, 0, 0, 0, -1, 0, 0, 0, -1, 0, 0, 0, 88, 2, 0, 0, 0, 0, 0, 0, 6, 0, 0, 0, 50, 0, 0, 0, -12, 1, 0, 0, -24, 3, 0, 0, -121, 19, 0, 0, -120, 19, 0, 0, 63, -100, 0, 0, 64, -100, 0, 0, 10, 0, 0, 0, 10, 0, 0, 0, 59, 0, 0, 0, -122, 0, 0, 0, -95, 0, 0, 0, -37, 0, 0, 0, -1, 0, 0, 0, -1, 0, 0, 0, 88, 2, 0, 0, 0, 0, 0, 0, 15, 0, 0, 0, 15, 0, 0, 0, -106, 0, 0, 0, -36, 5, 0, 0, -120, 19, 0, 0, 16, 39, 0, 0, 63, -100, 0, 0, 64, -100, 0, 0, 10, 0, 0, 0, 10, 0, 0, 0, 15, 0, 0, 0, 59, 0, 0, 0, -122, 0, 0, 0, -81, 0, 0, 0, -1, 0, 0, 0, -1, 0, 0, 0, 88, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 5, 0, 0, 0, 50, 0, 0, 0, -24, 3, 0, 0, -24, 3, 0, 0, 15, 39, 0, 0, 16, 39, 0, 0, 10, 0, 0, 0, 10, 0, 0, 0, 27, 0, 0, 0, 50, 0, 0, 0, -37, 0, 0, 0, -1, 0, 0, 0, -1, 0, 0, 0, 88, 2, 0, 0, 0, 0, 0, 0, 6, 0, 0, 0, 50, 0, 0, 0, -12, 1, 0, 0, -24, 3, 0, 0, -121, 19, 0, 0, -120, 19, 0, 0, 63, -100, 0, 0, 64, -100, 0, 0, 10, 0, 0, 0, 10, 0, 0, 0, 30, 0, 0, 0, 50, 0, 0, 0, -95, 0, 0, 0, -37, 0, 0, 0, -1, 0, 0, 0, -1, 0, 0, 0, 88, 2, 0, 0, 0, 0, 0, 0, 15, 0, 0, 0, 15, 0, 0, 0, -106, 0, 0, 0, -36, 5, 0, 0, -120, 19, 0, 0, 16, 39, 0, 0, 63, -100, 0, 0, 64, -100, 0, 0, 10, 0, 0, 0, 10, 0, 0, 0, 15, 0, 0, 0, 30, 0, 0, 0, 50, 0, 0, 0, -81, 0, 0, 0, -1, 0, 0, 0, -1, 0, 0, 0, 88, 2, 0, 0,
07-05 14:15:27.503  3506  4032 D SensorHubManager: SendSensorHubData: send data = -63, 23, 48, 2, 12, 8 ..., 0, 0, 88, 2, 0, 0
,07-05 14:15:27.503  3073  3128 D Sensorhubs: sendContextData: -63, 23, 48, 2, 12, 8 ..., 0, 0, 88, 2, 0, 0
,07-05 14:15:27.513  4407 11539 D NfcService: call the applyRouting
,07-05 14:15:27.513  3506  4032 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 48, 0,
07-05 14:15:27.513  3506  4032 D SensorHubManager: SendSensorHubData: send data = -79, 48, 0
07-05 14:15:27.513  3073  3073 D Sensorhubs: sendContextData: -79, 48, 0
,07-05 14:15:27.523  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41fe5f3 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f53787d 4355:com.google.android.gms.persistent/u0a10}
07-05 14:15:27.523  6612  6612 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
07-05 14:15:27.523  6612  6612 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
,07-05 14:15:27.523  3506  4032 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
07-05 14:15:27.523  3506  4032 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:15:27.523  5955  5955 I PedometerService: onStartCommand  true, true
,07-05 14:15:27.523  4072  4072 D KeyguardViewMediator: IKeyguardDrawnCallback.onDrawn()
07-05 14:15:27.523  3506  3524 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-05 14:15:27.533  3506  3506 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-05 14:15:27.533  3506  4520 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,07-05 14:15:27.533  3506  4520 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 14:15:27.533  3506  4032 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:15:27.533  3506  4032 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-05 14:15:27.533  3506  4032 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:15:27.533  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4a5d705, Service : PEDOMETER(1)
07-05 14:15:27.533  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@79dda68, Service : ACTIVITY_TRACKER_BATCH(1)
07-05 14:15:27.533  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@941e3b2, Service : STEP_LEVEL_MONITOR(1)
,07-05 14:15:27.533  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-05 14:15:27.533  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@69722b0, Service : AUTO_BRIGHTNESS(1)
07-05 14:15:27.533  3506  4032 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_BRIGHTNESS
07-05 14:15:27.533  3506  4032 D SContextService: 	.registerCallback : 3, client=
07-05 14:15:27.533  3506  4032 D SContextService: ===== SContext Service List =====
,07-05 14:15:27.533  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Pedometer
07-05 14:15:27.533  3506  4032 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::registerListener done: 63ms
07-05 14:15:27.533  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Step Level Monitor
07-05 14:15:27.533  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b31de81, Service : Activity Batch
07-05 14:15:27.533  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@61730ae, Service : Auto Brightness
07-05 14:15:27.533  3506  4032 D SContextManager:   .registerListener : listener = com.android.server.display.AutomaticBrightnessController$5@f0b9529, service=Auto Brightness
,07-05 14:15:27.543  3506  4444 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41fe5f3 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f53787d 4355:com.google.android.gms.persistent/u0a10}
,07-05 14:15:27.543  4355  4355 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver bqHint=4 }.
,07-05 14:15:27.543  3506  3589 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-05 14:15:27.543  3506  3589 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,07-05 14:15:27.543  3506  3589 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
07-05 14:15:27.543  3506  3589 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:15:27.543  3506  3589 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-05 14:15:27.553  3506  3589 V CAE     : start(ContextProvider.java:128)
,07-05 14:15:27.553  3506  3589 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:15:27.553  3506  3506 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
07-05 14:15:27.553  3506  3589 V CAE     : enable(AutoRotationRunner.java:158)
,07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,07-05 14:15:27.553  3506  3589 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
07-05 14:15:27.553  3506  3506 D ResourcesManager: For user 0 new overlays fetched Null
07-05 14:15:27.553  3506  3589 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera4/SamsungCamera4.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
07-05 14:15:27.553  3506  3506 D ResourcesManager: For user 0 new overlays fetched Null
07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera4/SamsungCamera4.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
07-05 14:15:27.553  3506  3506 D ResourcesManager: For user 0 new overlays fetched Null
07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/app/STalkback/STalkback.apk / 1.0 running in null rsrc of package com.samsung.android.app.talkback
07-05 14:15:27.553  3073  3128 D Sensorhubs: sendContextData: -79, 7, 0, 0
07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
,07-05 14:15:27.553  3506  3506 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /system/app/UniversalSwitch/UniversalSwitch.apk / 1.0 running in null rsrc of package com.samsung.android.universalswitch
07-05 14:15:27.553  3506  3506 W ResourcesManager: getTopLevelResources: /data/app/com.wsandroid.suite.vodaemea-2/base.apk / 1.0 running in null rsrc of package com.wsandroid.suite.vodaemea
07-05 14:15:27.563  3506  3589 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:15:27.563  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:15:27.563  3506  3589 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:15:27.563  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:15:27.573  3506  3589 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
07-05 14:15:27.573  3506  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41fe5f3 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f53787d 4355:com.google.android.gms.persistent/u0a10}
,07-05 14:15:27.573  3506  3589 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-05 14:15:27.583  3506  3589 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====,
07-05 14:15:27.583  3506  3589 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4a5d705, Service : PEDOMETER(1)
07-05 14:15:27.583  3506  3589 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@79dda68, Service : ACTIVITY_TRACKER_BATCH(1)
07-05 14:15:27.583  3506  3589 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@941e3b2, Service : STEP_LEVEL_MONITOR(1)
07-05 14:15:27.583  3506  3589 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-05 14:15:27.583  3506  3589 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@69722b0, Service : AUTO_BRIGHTNESS(1)
07-05 14:15:27.583  3506  3589 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-05 14:15:27.583  3506  3589 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fefc061, Service : AUTO_ROTATION(1)
07-05 14:15:27.583  3506  3620 I DisplayPowerController: Unblocked screen on after 140 ms
07-05 14:15:27.583  3506  3589 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:15:27.583  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:27.583  3506  3589 D SContextService: 	.registerCallback : 4, client=
07-05 14:15:27.583  3506  3620 D ColorFade: prepare: mode=2
07-05 14:15:27.583  3506  3589 D SContextService: ===== SContext Service List =====
07-05 14:15:27.583  3506  3620 D ColorFade: ColorFade is already prepared
07-05 14:15:27.583  3506  3589 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Pedometer
07-05 14:15:27.583  3506  3589 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Step Level Monitor
07-05 14:15:27.583  3506  3589 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b31de81, Service : Activity Batch
07-05 14:15:27.583  3506  3589 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@61730ae, Service : Auto Brightness
07-05 14:15:27.583  3506  3589 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@1b8a786, Service : Auto Rotation
07-05 14:15:27.583  3506  3589 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@f69e671, service=Auto Rotation
,07-05 14:15:27.583  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:27.583  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
,07-05 14:15:27.583  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:27.583  3506  3506 D ResourcesManager: For user 0 new overlays fetched Null
07-05 14:15:27.583  3506  3506 W ResourcesManager: getTopLevelResources: /data/app/com.wsandroid.suite.vodaemea-2/base.apk / 1.0 running in null rsrc of package com.wsandroid.suite.vodaemea
,07-05 14:15:27.583  3506  3506 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
07-05 14:15:27.583  3506  3506 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3506) 
,07-05 14:15:27.593  3506  3506 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 14:15:27.593  3506  3506 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,07-05 14:15:27.593  3506  3506 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 14:15:27.593  3506  3506 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
07-05 14:15:27.593  3506  3506 D UsbDeviceManager: Keyguard Lock/Unlock
07-05 14:15:27.593  3506  3506 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
07-05 14:15:27.593  3506  3506 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
,07-05 14:15:27.593  3506  3506 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0200
07-05 14:15:27.593  3506  3506 D UsbDeviceManager: updateUsbNotification : cancel id = 17040366, title = Connected as a media device
,07-05 14:15:27.593  3506  3506 D UsbDeviceManager: updateUsbNotification : isKeyguardLocked = false, isKeyguardSecure = false, mBootCompleted = true
,07-05 14:15:27.603  3506  3506 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
07-05 14:15:27.603  3506  3506 D UsbDeviceManager: updateUsbNotification : notify id = 17040366, title = Connected as a media device
,07-05 14:15:27.613  3506  3961 D InputReader: Input event(6): value=0 when=796800096000
07-05 14:15:27.613  3506  3961 D InputReader: !@notifyKey(172), action=1
07-05 14:15:27.613  3506  3506 I PalmMotion: [PALM] SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
07-05 14:15:27.613  3506  3961 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
07-05 14:15:27.613  3506  3506 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
07-05 14:15:27.613  3506  3506 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
07-05 14:15:27.613  3506  3506 D PalmMotion: [PALM] ACCEPTED : [zeroflte] PALM_CNT : 3, M_TOUCH : 30.0, M_SWEEP : 25.0, E_SWEEP : 2.2, IGNORE_M_SWEEP : true
07-05 14:15:27.613  3506  3961 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-05 14:15:27.613  4407 11539 D SecNfcJni: RoutingManager::commitRouting
07-05 14:15:27.613  4407  5616 D SecNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,07-05 14:15:27.613  3506  3960 I WindowManager: Ignoring HOME; down is not pressed.
07-05 14:15:27.613  3506  4839 I ActivityManager: Start proc 11544:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.ui.applocking.AppLockingUserReceiver
07-05 14:15:27.613 11544 11544 E Zygote  : v2
07-05 14:15:27.613  3506  3960 D VoIPInterfaceManager: isVoIPRinging()...
07-05 14:15:27.613 11544 11544 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
07-05 14:15:27.613  3506  3960 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-05 14:15:27.613  3506  3960 D VoIPInterfaceManager: Not exist call session
07-05 14:15:27.613 11544 11544 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:15:27.613 11544 11544 I libpersona: KNOX_SDCARD not a persona
,07-05 14:15:27.623 11544 11544 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:15:27.623 11544 11544 E Zygote  : accessInfo : 0
07-05 14:15:27.623  3506  3506 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 14:15:27.623  3506  3506 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-05 14:15:27.623  3506  3506 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-05 14:15:27.623  3506  3506 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 14:15:27.623  3506  3506 D UcmService: notifyChangeToPlugin event 16
07-05 14:15:27.623  3506  3506 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 14:15:27.623  3506  3506 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 14:15:27.623  3506  3506 D UcmService: notifying to unmanaged plugin
07-05 14:15:27.623  4477  4488 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-05 14:15:27.623  3506  3506 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 14:15:27.623  3506  3506 D UcmService: agentService status-0
07-05 14:15:27.623  3506  3506 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 14:15:27.623  3506  3506 D UcmService: notifying to unmanaged plugin
,07-05 14:15:27.623  4490  4502 D BootAgentService: notifyChange eventId-16
,07-05 14:15:27.623  3506  3506 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-05 14:15:27.623  3506  3506 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3506) 
07-05 14:15:27.623  3506  3506 D UcmService: agentService status--1
07-05 14:15:27.623  3506  3506 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
07-05 14:15:27.623  3506  3506 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
07-05 14:15:27.623  3506  3506 D EdgeLight: Turning off
,07-05 14:15:27.633  3506  3506 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 3506) 
07-05 14:15:27.633  3506  3506 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
07-05 14:15:27.633  3506  3506 D BatteryService: turn off LED
,07-05 14:15:27.633  4407 11539 D NfcService: index : 0
07-05 14:15:27.633  4407 11539 D NfcService: index : 1
07-05 14:15:27.633  4407 11539 D NfcService: index : 2
,07-05 14:15:27.633  3506  3629 D LightsService: [SvcLED] handleForcedSvcLEDTask()
,07-05 14:15:27.633  3506  3629 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
07-05 14:15:27.633  3506  3629 D SensorManager: unregisterListener ::   
07-05 14:15:27.633  3506  3629 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-05 14:15:27.633  3506  3629 D lights  : led_pattern : 0 +
07-05 14:15:27.633  3506  3629 D lights  : led_pattern : 0 -
,07-05 14:15:27.633  3506  3506 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
07-05 14:15:27.633  3506  3506 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package android
07-05 14:15:27.633  3506  3506 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
,07-05 14:15:27.643  4072  4072 D PhoneStatusBar: removeNotification key=-1|android|17040366|null|1000 old=StatusBarNotification(pkg=android user=UserHandle{-1} id=17040366 tag=null score=-20 key=-1|android|17040366|null|1000: Notification(pri=-2 contentView=android/0x10900a3 vibrate=null sound=null tick defaults=0x0 flags=0x2 color=0xff7792a9 vis=PUBLIC secFlags=0x0 secPriority=0))
07-05 14:15:27.643  4072  4072 D PhoneStatusBar: setAreThereNotifications: N=2 any=true clearable=true
,07-05 14:15:27.653 11544 11544 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:15:27.653 11544 11544 D ActivityThread: Added TimaKeyStore provider
,07-05 14:15:27.663  3506  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41fe5f3 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe7b612 11544:com.samsung.android.sm/1000}
,07-05 14:15:27.663  3506  3506 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-05 14:15:27.663  3506  3506 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
,07-05 14:15:27.673  3506  3506 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
,07-05 14:15:27.673  3506  3506 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
,07-05 14:15:27.673  3073  3073 D Sensorhubs: sendContextData: -76, 13, -47, 0
07-05 14:15:27.673  3506  3506 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-05 14:15:27.673  3506  3506 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
,07-05 14:15:27.673  3506  3952 E MotionRecognitionService:  handler : SCREEN_ON end
,07-05 14:15:27.683  3506  3506 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-05 14:15:27.683  3506  3506 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 14:15:27.683  3506  3506 D UcmService: notifyChangeToPlugin event 16
07-05 14:15:27.683  3506  3506 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 14:15:27.683  3506  3506 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 14:15:27.683  3506  3506 D UcmService: notifying to unmanaged plugin
07-05 14:15:27.683  4477  4489 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-05 14:15:27.683  3506  3506 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 14:15:27.683  3506  3506 D UcmService: agentService status-0
07-05 14:15:27.683  3506  3506 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 14:15:27.683  3506  3506 D UcmService: notifying to unmanaged plugin
,07-05 14:15:27.683  4490  4504 D BootAgentService: notifyChange eventId-16
07-05 14:15:27.683  3506  3506 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-05 14:15:27.683  3506  3506 D UcmService: agentService status--1
07-05 14:15:27.683  3506  3506 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-05 14:15:27.693  3506  3506 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-05 14:15:27.693  3506  3506 D NotificationService: ACTION_SCREEN_ON
07-05 14:15:27.693  3506  3506 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3506) 
,07-05 14:15:27.693  3506  3506 D EdgeLight: Turning off
07-05 14:15:27.693  3506  3506 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
,07-05 14:15:27.693  3506  3992 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
07-05 14:15:27.693  3506  3629 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-05 14:15:27.693  3506  3629 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-05 14:15:27.703  3506  3992 D WifiNative-wlan0: callSECApiBoolean - ID [11]
07-05 14:15:27.703  4273  4273 I wpa_supplicant: STOP_PERIODIC_SCAN command
,07-05 14:15:27.703  3066  5070 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=on
,07-05 14:15:27.703  3506  3992 E WifiNative-wlan0: do suspend false
,07-05 14:15:27.703  3506  3506 V AlarmManager:  remove PendingIntent] PendingIntent{f6adb03: PendingIntentRecord{68c5a80 android broadcastIntent}}
,07-05 14:15:27.713  3506  3992 D WifiStateMachine: analyze kernel wifi wakelock 
07-05 14:15:27.713  3506  3992 D WifiStateMachine: file not found /proc/wakelocks
,07-05 14:15:27.723  3506  3506 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
,07-05 14:15:27.723  3506  3994 V AlarmManager:  remove PendingIntent] PendingIntent{c55b8b9: PendingIntentRecord{6de34fe android broadcastIntent}}
07-05 14:15:27.723  3506  3506 E SContext.CaeProvider: setAttribute() : attribute is null!
07-05 14:15:27.723  3506  3506 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-05 14:15:27.723  3506  3506 V CAE     : start(ContextProvider.java:128)
,07-05 14:15:27.723  3506  3506 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-05 14:15:27.723  3073  3127 D Sensorhubs: readContextData: 1, 1, 44, 1, 1, 1, 2, -96, -23, -75, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 107, 75
07-05 14:15:27.723  3506  3506 V CAE     : enable(ActivityTrackerRunner.java:84)
,07-05 14:15:27.723  3506  3506 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 12, 15, 27,
07-05 14:15:27.723  3506  3506 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 12, 15, 27
07-05 14:15:27.723 11544 11544 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package com.samsung.android.sm
07-05 14:15:27.723  3506  3949 D SensorHubManager: onGetSensorHubDataLocked: library(22) = 1, 1, 44, 1, 1, 1, 2, -96, -23, -75, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 107, 75
,07-05 14:15:27.723  3506  3948 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :22], AP_WAKEUP
07-05 14:15:27.723  3073  3128 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 12, 15, 27
07-05 14:15:27.723  3506  3948 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 22
07-05 14:15:27.723  3506  3948 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 44, 1, 1, 1, 2, -96, -23, -75, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 107, 75,
,07-05 14:15:27.723  3506  3948 I CAE     : parse(SLMonitorRunner.java:301) - parse:4
07-05 14:15:27.723  3506  4520 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
07-05 14:15:27.723  3506  3948 D CAE     : parse(SLMonitorRunner.java:323) - dataSize:1
07-05 14:15:27.723 11544 11544 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-05 14:15:27.723  3506  3948 D CAE     : display(SLMonitorRunner.java:604) - ================= STEP_LEVEL_MONITOR =================
07-05 14:15:27.723  3506  3633 D SurfaceControl: Excessive delay in setPowerMode(): 250ms
07-05 14:15:27.723  3506  3633 D PowerManagerUtil: Excessive delay in !@display_state: ON: 251ms
07-05 14:15:27.723  3506  3948 I CAE     : display(SLMonitorRunner.java:721) - DT=[1], DC=[1], TS=[1467720900021], ST=[ST], SC=[0], DI=[0.0], CA=[0.0], DU=[27467]
07-05 14:15:27.723  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
,07-05 14:15:27.743  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
,07-05 14:15:27.743 10812 10869 E         : g2d stretchFimgApi_v5 function does not exist
07-05 14:15:27.743 10812 10869 E         : [JM] stretchFimgApi might be v4.
,07-05 14:15:27.743  3506  3506 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-05 14:15:27.743  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:27.743  3506  3620 D ColorFade: prepare: mode=2
07-05 14:15:27.743  3506  3620 D ColorFade: ColorFade is already prepared
,07-05 14:15:27.753  3506  3506 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
07-05 14:15:27.753  3506  3620 D DisplayPowerState: !@ [0] ColorFade exit
07-05 14:15:27.753  3506  3951 D SContextService: updateSContext() : event = Step Level Monitor
07-05 14:15:27.753  3506  3620 D PowerManagerService: [input device light] onColorFadeExit(true)
07-05 14:15:27.753  3506  3620 D DisplayPowerController: ColorFade: onAnimationStart
07-05 14:15:27.753  3506 11558 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 1
07-05 14:15:27.753  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:27.753 11544 11544 D ResourcesManager: For user 0 new overlays fetched Null
,07-05 14:15:27.753  3506 11559 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
,07-05 14:15:27.753  3506  4035 D lights  : lcd : 121 +
07-05 14:15:27.753  3506  3620 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-05 14:15:27.753 11544 11544 I InjectionManager: Inside getClassLibPath caller 
07-05 14:15:27.753  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
07-05 14:15:27.753  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:15:27.753  3506  4032 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
07-05 14:15:27.753  3506  3620 D DisplayPowerState: Requesting new screen state: [0] state=ON, backlight (By colorFade)=121
07-05 14:15:27.753  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:27.753  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
07-05 14:15:27.753  3506  4035 D DisplayPowerState: Updating screen state [0]: state=ON, backlight (by ColorFade)=121
07-05 14:15:27.753  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:27.763  3506  4035 D lights  : lcd : 121 -
07-05 14:15:27.763  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:27.763  3506  3506 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
07-05 14:15:27.763  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
07-05 14:15:27.763  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:27.763  3506  3506 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-05 14:15:27.763  3506  3506 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:15:27.763  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4a5d705, Service : PEDOMETER(1)
07-05 14:15:27.763  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@79dda68, Service : ACTIVITY_TRACKER_BATCH(1)
07-05 14:15:27.763  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@941e3b2, Service : STEP_LEVEL_MONITOR(1)
07-05 14:15:27.763  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-05 14:15:27.763  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER(1)
07-05 14:15:27.763  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@69722b0, Service : AUTO_BRIGHTNESS(1)
07-05 14:15:27.763  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fefc061, Service : AUTO_ROTATION(1)
07-05 14:15:27.763  3506  3506 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-05 14:15:27.763  3506  3506 D SContextService: 	.registerCallback : 5, client=
07-05 14:15:27.763  3506  3506 D SContextService: ===== SContext Service List =====
07-05 14:15:27.763  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Pedometer
07-05 14:15:27.763  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Step Level Monitor
07-05 14:15:27.763  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b31de81, Service : Activity Batch
07-05 14:15:27.763  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@61730ae, Service : Auto Brightness
07-05 14:15:27.763  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@1b8a786, Service : Auto Rotation
07-05 14:15:27.763  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@887215e, Service : Activity Tracker
07-05 14:15:27.763  3506  3506 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@6571a99, service=Activity Tracker
07-05 14:15:27.763  3506  4032 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@61730ae, Service = Auto Brightness, used = 0
07-05 14:15:27.763  3506  4032 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_BRIGHTNESS
07-05 14:15:27.763  3506  4032 V CAE     : stop(ContextProvider.java:155)
,07-05 14:15:27.763  3506  4032 V CAE     : clear(AutoBrightnessRunner.java:297)
07-05 14:15:27.763  3506  4032 V CAE     : disable(AutoBrightnessRunner.java:286)
07-05 14:15:27.763  3506  4032 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 48, 0, 0,
07-05 14:15:27.763  3506  4032 D SensorHubManager: SendSensorHubData: send data = -78, 48, 0, 0
07-05 14:15:27.763  3073  3073 D Sensorhubs: sendContextData: -78, 48, 0, 0
,07-05 14:15:27.773  3073  3127 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, -95, 85, 44, 1, 1, 1, 1, 48, 0, 0, 0, 37, 0, 0, 0, 20
07-05 14:15:27.773  3506  3949 D SensorHubManager: onGetSensorHubDataLocked: library(21) = 1, 1, 26, 1, 2, -95, 85, 44, 1, 1, 1, 1, 48, 0, 0, 0, 37, 0, 0, 0, 20
,07-05 14:15:27.773  3506  3948 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :21], AP_WAKEUP
07-05 14:15:27.773  3506  3948 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 21
07-05 14:15:27.773  3506  3948 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, -95, 85, 44, 1, 1, 1, 1, 48, 0, 0, 0, 37, 0, 0, 0, 20,
,07-05 14:15:27.773 11544 11544 D InjectionManager: InjectionManager
07-05 14:15:27.773 11544 11544 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm
07-05 14:15:27.773  3506  3948 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-05 14:15:27.773  3506  4032 D CAE     : getFaultDetectionResult(AutoBrightnessRunner.java:311) - true
07-05 14:15:27.773  3506  3948 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[1], TimeStamp=[1467720927532]
,07-05 14:15:27.773  3506  4032 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
07-05 14:15:27.773  3506  3951 D SContextService: updateSContext() : event = Activity Tracker
07-05 14:15:27.773 11544 11544 I InjectionManager: Constructor com.samsung.android.sm, Feature store :{}
07-05 14:15:27.773 11544 11544 I InjectionManager: featureStore :{}
07-05 14:15:27.773  3506  3948 D CAE     : display(ContextProvider.java:375) - ================= AUTO_BRIGHTNESS =================
07-05 14:15:27.773  3506  3948 I CAE     : display(ContextProvider.java:391) - Candela=[37], AmbientLux=[20]
,07-05 14:15:27.773  3506  4520 I ActivityManager: Killing 9758:com.samsung.android.SettingsReceiver/1000 (adj 15): DHA:empty #31
,07-05 14:15:27.773  4072  4072 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,07-05 14:15:27.783  3506  4032 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:15:27.783  4072  4072 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,07-05 14:15:27.783  5955  5955 I Sensor[0x06]: [0x01] 33
07-05 14:15:27.783  5955  5955 I Sensor[0x04]: [0x01] 1467720900021[0x02] 0[0x03] 1[0x04] 27467
,07-05 14:15:27.783  3506  4032 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-05 14:15:27.783  3506  4032 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:15:27.783  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4a5d705, Service : PEDOMETER(1)
07-05 14:15:27.783  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@79dda68, Service : ACTIVITY_TRACKER_BATCH(1)
07-05 14:15:27.783  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@941e3b2, Service : STEP_LEVEL_MONITOR(1)
07-05 14:15:27.783  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-05 14:15:27.793  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER(1)
07-05 14:15:27.793  3506  4032 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fefc061, Service : AUTO_ROTATION(1)
07-05 14:15:27.793  3506  4032 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_BRIGHTNESS
07-05 14:15:27.793  3506  4032 D SContextService: 	.unregisterCallback : 5, client=
,07-05 14:15:27.793  3506  4032 D SContextService: ===== SContext Service List =====
07-05 14:15:27.793  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Pedometer
07-05 14:15:27.793  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Step Level Monitor
07-05 14:15:27.793  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b31de81, Service : Activity Batch
07-05 14:15:27.793  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@1b8a786, Service : Auto Rotation
07-05 14:15:27.793  3506  4032 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@887215e, Service : Activity Tracker
07-05 14:15:27.793  4072  4072 D PhoneStatusBar: setAreThereNotifications: N=3 any=true clearable=true
,07-05 14:15:27.793  3506  3506 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
07-05 14:15:27.793  4072  4072 V PanelView: too small height - windowHeight = 0
07-05 14:15:27.793  3506  3506 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
07-05 14:15:27.793  3506  3506 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
07-05 14:15:27.793  3506  3506 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-05 14:15:27.793  3506  3506 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
,07-05 14:15:27.793  3506  4032 D SContextManager:   .unregisterListener : listener = com.android.server.display.AutomaticBrightnessController$5@f0b9529, service=Auto Brightness
07-05 14:15:27.793  3506  4032 D PowerManagerUtil: Excessive delay in SensorHubAutoBrightnessEnabled::unregisterListener done: 39ms
,07-05 14:15:27.793  3073  3128 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-05 14:15:27.793  3506  3506 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,07-05 14:15:27.793  3506  3506 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:15:27.803 10812 10812 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36508e3 time:796991
,07-05 14:15:27.803  3506  3525 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.SettingsReceiver, Auto Run ON
,07-05 14:15:27.803  3506  3506 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
07-05 14:15:27.803  3506  3506 D SContextService: requestToUpdate() : service = Activity Tracker
07-05 14:15:27.803  3506  3506 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@6571a99, service=Activity Tracker
,07-05 14:15:27.813  3073  3127 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, -95, 85, 44, 1, 1
,07-05 14:15:27.813  3506  3949 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, -95, 85, 44, 1, 1
07-05 14:15:27.813  3506  3948 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-05 14:15:27.813  3506  3948 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
07-05 14:15:27.813  3506  3948 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, -95, 85, 44, 1, 1,
,07-05 14:15:27.813  3506  3948 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-05 14:15:27.813  3506  3948 I CAE     : display(ContextProvider.java:391) - Accuracy=[1], OperationMode=[0], ActivityType=[1], TimeStamp=[1467720927532]
07-05 14:15:27.813  3506  3951 D SContextService: updateSContext() : event = Activity Tracker
,07-05 14:15:27.813  3506  3506 D WifiStateMachine: setWifiScanMove bMove = 0
07-05 14:15:27.813  3506  3506 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-05 14:15:27.813  3506  3506 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
07-05 14:15:27.813  3506  3506 D WifiService: ACTIVITY_STATUS_STATIONARY 
07-05 14:15:27.813  3506  3506 D WifiService: setWifiScanWithSensor bMove = 0
07-05 14:15:27.813  3506  3588 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-05 14:15:27.823  3506  3992 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
07-05 14:15:27.823  4273  4273 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,07-05 14:15:27.823  3506  3506 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-05 14:15:27.823  3506  3506 D WifiService: ACTIVITY_STATUS_STATIONARY 
07-05 14:15:27.833  3506  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-05 14:15:27.833  3506  3615 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:15:27.833  3506  3990 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
07-05 14:15:27.833  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,07-05 14:15:27.833  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
07-05 14:15:27.833  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
,07-05 14:15:27.913  3506 11558 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 1
,07-05 14:15:27.943  3506 11559 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
,07-05 14:15:27.943  3506  3633 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-05 14:15:27.943  3506  3633 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-05 14:15:27.943  3506  3633 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 211ms
07-05 14:15:27.943  3506  3633 D PowerManagerUtil: Excessive delay in nativeSetInteractive(true): 211ms
07-05 14:15:27.943  3506  3633 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 463ms
07-05 14:15:27.943  3506  4031 D lights  : button : 1 +
,07-05 14:15:27.943  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:27.943  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
07-05 14:15:27.943  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:27.983  3506  4031 D lights  : button : 1 -
,07-05 14:15:28.203  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:15:28.223  4515  4571 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 19ms lastUpdatedAfter : 180348ms
,07-05 14:15:28.433  3506  3506 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1200000  uid : 1000  pid : 3506  tag : WAKEUP_BOOSTER@31
,07-05 14:15:28.563  3506  3620 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 14:15:28.563  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 14:15:28.563  3045  4538 D libEGL  : eglTerminate EGLDisplay = 0x7fa619ee78
07-05 14:15:28.563  3045  4538 D libEGL  : eglTerminate EGLDisplay = 0x7fa619ee78
,07-05 14:15:28.563  3506  3620 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-05 14:15:28.563  3045  3959 I SurfaceFlinger: id=10 Removed DolorFade (9/9)
07-05 14:15:28.563  3045  4505 I SurfaceFlinger: id=10 Removed DolorFade (-2/9)
07-05 14:15:28.563  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:28.563  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
07-05 14:15:28.563  3506  3620 D DisplayPowerController: Animating brightness: target=121, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:15:28.563  3506  3620 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
07-05 14:15:28.563  3506  3620 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
,07-05 14:15:28.573  3506  3620 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-05 14:15:28.573  3506  3620 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:15:28.573  3506  3620 D PowerManagerService: mDisplayReady: true
07-05 14:15:28.573  4072  5110 D KeyguardViewMediator: notifyScreenTurnedOn
07-05 14:15:28.573  4072  4072 D KeyguardViewMediator: handleNotifyScreenTurnedOn
,07-05 14:15:28.573  4072  4072 D SecKeyguardStatusView: onScreenTurnedOn()
,07-05 14:15:28.583  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fe403c798
,07-05 14:15:28.623  3506  3582 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-05 14:15:28.623  3506  3506 D PersonaManagerService: ACTION_SCREEN_ON onReceive
07-05 14:15:28.633  3506  3654 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,07-05 14:15:28.633  3506  4840 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,07-05 14:15:28.633  4407  4407 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-05 14:15:28.633  4407 11563 D NfcService: call the applyRouting
,07-05 14:15:28.633  4407 11563 D NfcService: Discovery configuration equal, not updating.
07-05 14:15:28.633  4407 11563 D NfcService: index : 0
07-05 14:15:28.633  4407 11563 D NfcService: index : 1
07-05 14:15:28.633  4407 11563 D NfcService: index : 2
,07-05 14:15:28.633  4072  4284 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,07-05 14:15:28.653  5136  5136 E SamsungIME: invoke(): method is null
,07-05 14:15:28.663  3506  3506 V AlarmManager:  remove PendingIntent] PendingIntent{6d7520c: PendingIntentRecord{fc2a804 android broadcastIntent}}
07-05 14:15:28.663  3506  3506 V AlarmManager:  remove PendingIntent] PendingIntent{5f5c755: PendingIntentRecord{a68093f android broadcastIntent}}
,07-05 14:15:28.663  5399  5399 D BtGatt.GattService: LCD turned on
07-05 14:15:28.663  5399  5536 D BtGatt.ScanManager: handleLcdOnIntent
07-05 14:15:28.663  5399  5536 D BtGatt.ScanManager: handleLcdOnIntent
,07-05 14:15:28.673  3506  6477 D SSRM:n  : SIOP:: AP = 300, PST = 280 (W:26), CP = 243, LCD = 121
,07-05 14:15:28.693  3506  3506 I SurveyLogManager: mDeviceInfo.mScreen = true
,07-05 14:15:28.693  8306  8306 I BeaconManager: BeaconManager.onReceive - receive Action : android.intent.action.SCREEN_ON
07-05 14:15:28.693  8306  8306 D BeaconManager: BeaconManager.onReceive - end
07-05 14:15:28.693  8306  8351 I BeaconManager: BeaconManager.BeaconManagerWorkHandler - BroadcastReceiver onReceive start
07-05 14:15:28.693  8306  8351 D BeaconManager: BeaconManager.mScreenObserver - action:android.intent.action.SCREEN_ON
07-05 14:15:28.693  8306  8351 D BeaconManager: AppControlManager.screenOnIntentReceived - start
07-05 14:15:28.693  8306  8351 D BeaconManager: AppControlManager.screenOnIntentReceived - end
07-05 14:15:28.693  8306  8351 D BeaconManager: EasySetupManager.screenOnIntentReceived - start
07-05 14:15:28.693  8306  8351 D BeaconManager: EasySetupManager.screenOnIntentReceived - end
07-05 14:15:28.693  8306  8351 D BeaconManager: BleScanHelper.screenOnIntentReceived - start
,07-05 14:15:28.693  3506  4030 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:15:28.693  8306  8351 D BeaconManager: BleScanHelper.mBroadcastReceiver - Action: android.intent.action.SCREEN_ON, user: 0
07-05 14:15:28.693  8306  8351 V BeaconManager: BleScanHelper.startBleScan - startBleScan
,07-05 14:15:28.693  8306  8351 D BluetoothAdapter: STATE_ON
07-05 14:15:28.693  8306  8351 D BeaconManager: BleScanHelper.screenOnIntentReceived - end
07-05 14:15:28.693  8306  8351 I BeaconManager: BeaconManager.BeaconManagerWorkHandler - BroadcastReceiver onReceive end
,07-05 14:15:28.693  8306  8354 D BeaconManager: BleScanHelper.MSG_CALL_START_LESCAN - ($)
07-05 14:15:28.693  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:28.693  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:28.693  8306  8354 I BeaconManager: BleScanHelper.directStopLeScan - call BleScanner.stopScan()
,07-05 14:15:28.693  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:28.693  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:28.693  8306  8354 D BluetoothLeScanner: Stop Scan
,07-05 14:15:28.703  5399  5410 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager,
07-05 14:15:28.703  5399  5410 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager
07-05 14:15:28.703  5399  5410 D BtGatt.GattService: stopScan() - queue size =1
07-05 14:15:28.703  5399  5563 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.samsung.android.beaconmanager, msg: MESSAGE_STOP_SCAN
07-05 14:15:28.703  5399  5563 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 5, currDate: 5
07-05 14:15:28.703  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 12
,07-05 14:15:28.703  5399  5706 D BtGatt.GattService: unregisterClient() - clientIf=7
07-05 14:15:28.703  5399  5536 D BtGatt.ScanManager: stop scan
07-05 14:15:28.703  5399  5536 D BtGatt.ScanManager: delete FilterIndex - 9
,07-05 14:15:28.703  3506  4340 V AlarmManager:  remove PendingIntent] PendingIntent{d1ff56a: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:28.703  3506  6477 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:15:28.713  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d5dfa5b u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b16ec8 4876:com.sec.android.daemonapp/u0a172}
07-05 14:15:28.713  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{ad82f8: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.713  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=15
,07-05 14:15:28.713  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:28.713  5399  5536 D BtGatt.ScanManager: delete FilterIndex - 10
07-05 14:15:28.713  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{b9883d1: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:28.713  4876  4876 D [Weather Widget]  AutoRefreshReceiver: {[43EB1C024052B99D53E99193017237969D0748A3026577DA009FAAB20B80BF7EB73ED82772D00A3FB36B1CA0A0AE57470020D447AFD9352B61BD55F739C726ED44017ED0EC7C80216D73BA0C808DA20C]}
,07-05 14:15:28.713  4876  4876 D [Weather Widget]  AutoRefresh: {[6C1C865D6DD0B00ECC0A075BD88FDF04CE2F6EB6F3DE44DF4AA116F65F3787A1C3EB151D5EE46B9A67483A76F92A5308]}
07-05 14:15:28.713  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,07-05 14:15:28.713  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:28.713  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-05 14:15:28.713  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=100
07-05 14:15:28.713  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-05 14:15:28.713  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{cbffe36: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.713  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 1 => 13
,07-05 14:15:28.713  3506  4514 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d5dfa5b u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b16ec8 4876:com.sec.android.daemonapp/u0a172}
,07-05 14:15:28.713  4876  4876 D [Weather Widget]  WeatherScreenReceiver: {[AE44B1CAE710C9799F38EE823B33FC6F92A9C19BB921B49D1406D02974E87163A8B0430997E393CFB1B5A95DB10763CD692CFA270B828027C4CE8C7A80781DC8]}
,07-05 14:15:28.713  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 1 => 13
07-05 14:15:28.713  5399  5563 D BtGatt.GattService: [GSIM LOG]: remove : com.samsung.android.beaconmanager at  BLE_SCAN_ACTUAL_DB
07-05 14:15:28.713  5399  5563 D BtGatt.GattService: [GSIM LOG]: remove : com.samsung.android.beaconmanager at  BLE_SCAN_REQUESTED_DB
,07-05 14:15:28.713  4876  4876 D [Weather Widget]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279B9DC63D4CEF53B48C526943E4D500FBC]}
07-05 14:15:28.713  4876  4876 D [Weather Widget]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A3010D9284A6D928381A583BDA90BA7C2F53]}
07-05 14:15:28.723  4876  4876 D [Weather Widget]  WidgetCount: {[6CEC719F0A07787F8C223B192FCD4687C55ED1AD256D01CA79B528F9A8936DA2AEE8FCF34DEAE62C4F0012DD0AEA3C4D450DA911871FFB9B1B25866B258CE216]}
,07-05 14:15:28.723  4876  4876 D [Weather Widget]  WidgetCount: {[29F12EEF03899EE7AFF5C26031AC6881D49E2751002F9BF9065215948B126C8B67A603081AFD7572E245036EFA4646822C52CA5D0A7E6FBB74AF4A20DEEE1ADB]}
,07-05 14:15:28.723  4876  4876 D [Weather Widget]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279B9DC63D4CEF53B48C526943E4D500FBC]}
07-05 14:15:28.723  4876  4876 D [Weather Widget]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A3010D9284A6D928381A583BDA90BA7C2F53]}
,07-05 14:15:28.723  4876  4876 D [Weather Widget]  WidgetCount: {[6CEC719F0A07787F8C223B192FCD4687C55ED1AD256D01CA79B528F9A8936DA2AEE8FCF34DEAE62C4F0012DD0AEA3C4D450DA911871FFB9B1B25866B258CE216]}
,07-05 14:15:28.723  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{7b3d6a4: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.723  4876  4876 D [Weather Widget]  WeatherService: {[F5837F4AEE74F4A0BE2DA219DB8493352EBD627C6D5014E0B61ACE8DC72C6D46]}
,07-05 14:15:28.723  4876  4876 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03E59646CBA355B4C260B75423E37A3701A]}
,07-05 14:15:28.723  3506  4444 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9d08c0d u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b16ec8 4876:com.sec.android.daemonapp/u0a172}
,07-05 14:15:28.733  4876  4876 D [Weather Widget]  WeatherService: {[48CD66D4E33F43394A666804FCDC537EF944CF324D90E3FA4E2B91F4417CC8E31DCDDA779BAC33E6B3019A35271BF14B]}
,07-05 14:15:28.733  4876  4876 D [Weather Widget]  WeatherAppWidget: {[9C41A2EAFAAB2EF4F8363256C22FE8AD6BFA0AAEAD21D6A8D2E306D93A2C471179BD858054930975AE7F2732001BDC1897848C1DC035D0BDAB0B6E4F45C53186940DE2C9F38BA55247718582BFFF72B99FB9EA8904708BE61AAE6415CD7EE1F08D9FBE74A7B8CED5F0F56716BCEE69117D8BE40212E7FED1F626E036FB80A4C7]}
07-05 14:15:28.733  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{106dc09: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.733  4876  4876 D [Weather Widget]  : {[D4373F60448459DD657F41FF185B0D825CA20AA14BAB70A71EEEA345798FCBA8]}
07-05 14:15:28.733  4876  4876 D [Weather Widget]  : {[586A11FBE5AD336D16CF887E4A87159B16F25259F87DC9F1FBCB0D18F0FA341A6F2D8A3E866017333CA966FD417E3DEFFFB7B9C8ABD830453491EAA939A0D881F630B5E66EC5AB18640E329665FCD1980D44FB1964EDF3509194555A303AB121413CF0EC500F43BB313F86F8444DE800]}
,07-05 14:15:28.733  3506  4520 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9d08c0d u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b16ec8 4876:com.sec.android.daemonapp/u0a172}
,07-05 14:15:28.733  4876  4876 D [Weather Widget]  WeatherAppWidget2x1: {[9C41A2EAFAAB2EF4F8363256C22FE8AD3608A88029387EF7BE825543CCF892E0F6202CA317245B4608F7071D6EA2742184C2AE1116927B4B4147C71D7AD5D905D41FCB46C0FBE3D44372635FBCCD318CBA57DEA0C8FD3D4D8FFB45061D367E4DA2E107C617927D64A040DB86AA59D2CD971668D89FAC6DE10AD48A8EDD9F7B77]}
,07-05 14:15:28.733  4876  4876 D [Weather Widget]  : {[6D30B3C87FFD5946D969DA50235AFF715B11B31020247EB91F3BA0FB43A1AC0D72AD2F5C4265F6ACC8A5B63FCC8288D10DCB229FE456595F188EEC051A730B71]}
07-05 14:15:28.733  4876  4876 D [Weather Widget]  WeatherAppWidget2x1: {[9C41A2EAFAAB2EF4F8363256C22FE8AD0F5F0DEF0F18870905D45617D62B6A645DDC59A8F1813C876EB8C18EC23B024CADE43D6D1642270705AFA90C9F9B1F16]}
,07-05 14:15:28.743  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{eec9e0e: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.743  3506  4520 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9d08c0d u0 com.sec.android.widgetapp.ap.hero.accuweather.widget.action.WEATHER_SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4b16ec8 4876:com.sec.android.daemonapp/u0a172}
,07-05 14:15:28.743  4876  4876 D [Weather Widget]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B7747497512CAC38177609B2B6F1F16DB965D7D43410EDA2D444ACBA386E91E1FA6B3C38870128DD346C4D39F4B310AAEB16D5215E65B3E04A593E577F60D76D1932AD9EADD16B356DA517EF1B193C3C2443D58583FF4130EE2B5F5334C0BA0A0CCF7224CD6C07C390FD15A32A436637D0FACABFEA4]}
,07-05 14:15:28.743  4876  4876 D [Weather Widget]  : {[6D30B3C87FFD5946D969DA50235AFF715B11B31020247EB91F3BA0FB43A1AC0D72AD2F5C4265F6ACC8A5B63FCC8288D10DCB229FE456595F188EEC051A730B71]}
07-05 14:15:28.743  4876  4876 D [Weather Widget]  EasyWeatherAppWidget: {[48948B2BE5213A6D5B0C9B7747497512D7646A5A57C4B1820BB1D39DF9F23EA3D05ADA26DF3F5FEC4FA6AFC9EED5963485B3863BE45B906B9F93E60E1BD5AC1F]}
,07-05 14:15:28.753  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{fbbc02f: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.753  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{ad9563c: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.783  3506 11565 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:15:28.793  3506 11565 D BluetoothAdapter: STATE_ON,
,07-05 14:15:28.793  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{5382fc5: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.793  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{ed88d1a: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.793  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{94e304b: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.803  8306  8354 I BeaconManager: BleScanHelper.startBleScan - Start filter Scan(SCREEN_ON)
,07-05 14:15:28.803  8306  8354 D BluetoothLeScanner: Start Scan
,07-05 14:15:28.803  8306  8354 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.803  8306  8354 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.803  8306  8354 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.803  8306  8354 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.813  5399  5411 D BtGatt.GattService: registerClient() - UUID=9282456a-ac63-47a2-83a3-fd5979e661ae
,07-05 14:15:28.833  3506 11565 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:15:28.853  5399  5517 D BtGatt.GattService: onClientRegistered() - UUID=9282456a-ac63-47a2-83a3-fd5979e661ae, clientIf=7
,07-05 14:15:28.853  8306  8318 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,07-05 14:15:28.863  5399  5706 D BtGatt.GattService: start scan with filters
,07-05 14:15:28.863  5399  5706 D BtGatt.GattService: getScanSettings
,07-05 14:15:28.863  5399  5706 D BtGatt.GattService: Is it foreground application = false
,07-05 14:15:28.863  5399  5706 D BtGatt.GattService: Its a background application running with Low Power scan mode
07-05 14:15:28.863  3506 11565 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:15:28.873  5399  5706 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (100/5 vs -2147483648/0)
,07-05 14:15:28.873  3506 11565 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:15:28.873  5399  5706 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager
,07-05 14:15:28.873  5399  5706 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager
07-05 14:15:28.873  5399  5563 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.samsung.android.beaconmanager, msg: MESSAGE_START_SCAN
07-05 14:15:28.873  5399  5563 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 5, currDate: 5
,07-05 14:15:28.883  5399  5536 D BtGatt.ScanManager: handling starting scan
,07-05 14:15:28.883  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.883  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.883  5399  5536 D BluetoothAdapter: STATE_ON
07-05 14:15:28.883  5399  5563 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.samsung.android.beaconmanager : 4
07-05 14:15:28.883  5399  5563 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.samsung.android.beaconmanager, com.samsung.android.beaconmanager
07-05 14:15:28.883  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.883  5399  5536 D BluetoothAdapter: STATE_ON,
07-05 14:15:28.893  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:28.893  5399  5517 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
07-05 14:15:28.893  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-05 14:15:28.893  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{e039a28: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:28.893  5399  5563 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.samsung.android.beaconmanager : 216
07-05 14:15:28.893  5399  5536 D BtGatt.ScanManager: set filter index= 11 for clientIf= 7
07-05 14:15:28.893  5399  5536 D BtGatt.ScanManager: addFilterToController: 5
,07-05 14:15:28.893  5399  5517 D BtGatt.GattService: onScanFilterConfig() - clientIf=7, action = 0 status = 0, filterType=5, availableSpace=47
07-05 14:15:28.893  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:28.893  5399  5536 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-05 14:15:28.893  5399  5536 D BtGatt.ScanManager: Low Rssi Filter value is = -128,
,07-05 14:15:28.893  5399  5536 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =1
,07-05 14:15:28.903  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{3710341: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.903  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
07-05 14:15:28.903  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24462015
,07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.samsung.android.beaconmanager : 100
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: set filter index= 12 for clientIf= 7
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 100
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: addFilterToController: 5
,07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 13 => 13
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 13 => 13
07-05 14:15:28.903  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{b6260e6: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,07-05 14:15:28.903  5399  5517 D BtGatt.GattService: onScanFilterConfig() - clientIf=7, action = 0 status = 0, filterType=5, availableSpace=46
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 13 => 13
07-05 14:15:28.903  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =1
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 13 => 13
,07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 100
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-05 14:15:28.903  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=14
07-05 14:15:28.903  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 13 => 13
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: set filter index= 13 for clientIf= 7
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: addFilterToController: 5
,07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 13 => 13
07-05 14:15:28.903  5399  5563 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24462015
07-05 14:15:28.903  5399  5517 D BtGatt.GattService: onScanFilterConfig() - clientIf=7, action = 0 status = 0, filterType=5, availableSpace=45
07-05 14:15:28.903  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: High Rssi Filter value is = -128
,07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-05 14:15:28.903  5399  5536 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =1
07-05 14:15:28.913  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=13
07-05 14:15:28.913  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: set filter index= 14 for clientIf= 7
,07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: addFilterToController: 5
07-05 14:15:28.913  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{a4d8627: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:28.913  5399  5517 D BtGatt.GattService: onScanFilterConfig() - clientIf=7, action = 0 status = 0, filterType=5, availableSpace=44
07-05 14:15:28.913  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =1
07-05 14:15:28.913  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=12
07-05 14:15:28.913  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-05 14:15:28.913  5399  5536 I BtGatt.ScanManager: custom scan scanMode = 100
07-05 14:15:28.913  5399  5536 I BtGatt.ScanManager: New scan mode custom scan scanInterval = 3120scanWindow = 160
07-05 14:15:28.913  5399  5536 E BtGatt.ScanManager: default value of curScanSetting 0 is choosen
,07-05 14:15:28.913  5399  5536 I BtGatt.ScanManager: newScanMode = 5newcurScanSetting = 0
07-05 14:15:28.913  5399  5536 I BtGatt.ScanManager: comparing = 5 with = 0
07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=100 mLastConfiguredScanSetting=-2147483648
,07-05 14:15:28.913  5399  5536 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 4992configureRegularScanParams - scanWindow = 256
07-05 14:15:28.913  5399  5517 D BtGatt.GattService: onScanParamSetupCompleted() status=0, clientIf=7
07-05 14:15:28.913  5399  5517 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-05 14:15:28.923  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{b0c30d4: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.923  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{309927d: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.923  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{f63a572: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.933  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{2025dc3: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.933  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{b658640: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.943  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{ea1d979: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.943  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{7c2a6be: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.943  3506  4840 V AlarmManager:  remove PendingIntent] PendingIntent{1a3131f: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.953  3506  3524 V AlarmManager:  remove PendingIntent] PendingIntent{b3cc66c: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.953  3506  4340 V AlarmManager:  remove PendingIntent] PendingIntent{dd9435: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.963  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{77e70ca: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.963  3506  4839 V AlarmManager:  remove PendingIntent] PendingIntent{d6fc23b: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.973  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{a65dd58: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.973  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{e03eb1: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}},
,07-05 14:15:28.973  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{7acf96: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.983  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{38e4717: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.983  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{77704: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.993  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{a8914ed: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:28.993  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{d0c4f22: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.003  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{4a63db3: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.003  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{d06ff70: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.013  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{e6f12e9: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.023  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{6443b6e: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.023  3506 11565 I BatteryStatsDumper: Writing to database completed
,07-05 14:15:29.023  3506  4840 V AlarmManager:  remove PendingIntent] PendingIntent{a3d020f: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.033  3506  3524 V AlarmManager:  remove PendingIntent] PendingIntent{934a29c: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.043  3506  4340 V AlarmManager:  remove PendingIntent] PendingIntent{59cf4a5: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.053  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{2fca07a: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.063  3506  4839 V AlarmManager:  remove PendingIntent] PendingIntent{6d1b02b: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.063  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{7374c88: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.073  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{50d3621: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.083  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{ba44a46: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.093  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{bb92407: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}},
,07-05 14:15:29.103  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{b38a934: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.113  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{ce6135d: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.123  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{ecac4d2: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}},
,07-05 14:15:29.133  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{b9f9a3: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.143  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{5124a0: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.153  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{f758859: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:29.443  3506  4031 D lights  : button : 0 +
,07-05 14:15:29.483  3506  4031 D lights  : button : 0 -
,07-05 14:15:31.903  3506  5450 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-05 14:15:31.903  3506  5450 V MARsPolicyManager: updateSMDBValues
,07-05 14:15:31.903  3506  3611 E MARsDBManager: updateDBAll : begin --size 1
,07-05 14:15:31.943  3506  3611 E MARsDBManager: updateDBAll : end
07-05 14:15:31.943  3506  3611 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-05 14:15:38.703  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 281 (W:26), CP = 243, LCD = 121
,07-05 14:15:43.723  3506  3588 I ActivityManager: Waited long enough for: ServiceRecord{f7e137 u0 com.sec.android.daemonapp/.appservice.WeatherService}
,07-05 14:15:45.713  3506  4445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:45.713  3506  4445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:15:45.713  3506  4445 D BatteryService: online:4, current avg:-14, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:15:45.713  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:45.723  3506  3506 I MotionRecognitionService: Plugged
,07-05 14:15:45.723  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:15:45.723  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:15:45.723  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:15:45.723  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:15:45.723  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:15:45.723  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
,07-05 14:15:45.723  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:15:45.723  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:15:45.723  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:45.723  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:15:45.733  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:45.733  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:15:45.743  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:15:45.743  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:15:45.743  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:15:45.753  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:48.733  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 281 (W:26), CP = 243, CUR = -14, LCD = 121
,07-05 14:15:51.613  3506  3620 D PowerManagerService: [s] UserActivityState : 1 -> 2
07-05 14:15:51.613  3506  3620 D PowerManagerService: mDisplayReady: false
07-05 14:15:51.613  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:51.613  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-05 14:15:51.613  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 20 -> 20
07-05 14:15:51.613  3506  3620 D DisplayPowerController: Animating brightness: target=20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:15:51.623  3506  3620 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:15:51.623  3506  3620 D PowerManagerService: mDisplayReady: true
,07-05 14:15:51.623  3506  4035 D lights  : lcd : 107 +
,07-05 14:15:51.633  3506  4035 D lights  : lcd : 107 -,
07-05 14:15:51.633  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 14:15:51.633  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:51.633  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 20 -> 20
07-05 14:15:51.633  3506  3620 D DisplayPowerController: Animating brightness: target=20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:51.643  3506  4035 D lights  : lcd : 74 +
,07-05 14:15:51.643  3506  4035 D lights  : lcd : 74 -
,07-05 14:15:51.643  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:51.643  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:51.643  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 20 -> 20
07-05 14:15:51.653  3506  3620 D DisplayPowerController: Animating brightness: target=20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:51.663  3506  4035 D lights  : lcd : 41 +
,07-05 14:15:51.663  3506  4035 D lights  : lcd : 41 -
,07-05 14:15:51.663  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:51.663  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-05 14:15:51.663  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 20 -> 20
07-05 14:15:51.663  3506  3620 D DisplayPowerController: Animating brightness: target=20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:51.673  3506  4035 D lights  : lcd : 20 +
,07-05 14:15:51.673  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:51.673  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:51.673  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 20 -> 20
07-05 14:15:51.673  3506  3620 D DisplayPowerController: Animating brightness: target=20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:51.683  3506  4035 D lights  : lcd : 20 -
,07-05 14:15:51.683  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:51.683  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:51.683  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 20 -> 20
07-05 14:15:51.683  3506  3620 D DisplayPowerController: Animating brightness: target=20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:55.733  3506  4290 E Watchdog: !@Sync 27 [07-05 14:15:55.738]
,07-05 14:15:55.763  3506  6505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:55.763  3506  6505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:15:55.763  3506  6505 D BatteryService: online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:110
07-05 14:15:55.763  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:55.773  3506  3506 I MotionRecognitionService: Plugged
,07-05 14:15:55.773  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:15:55.773  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:15:55.773  3506  3506 D MotionRecognitionService:  TA connected ,  33792
,07-05 14:15:55.773  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:15:55.773  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:15:55.773  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
,07-05 14:15:55.773  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:15:55.783  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:55.793  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:15:55.793  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:55.803  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:15:55.813  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 14:15:55.813  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-05 14:15:55.813  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:15:55.823  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:15:55.823  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:57.753  3506  3620 D PowerManagerService: [s] UserActivityState : 2 -> 4
07-05 14:15:57.753  3506  3620 D InputManager-JNI: setInteractive(false)
07-05 14:15:57.753  3506  3620 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
07-05 14:15:57.753  3506  3620 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 14:15:57.753  3506  4030 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
07-05 14:15:57.753  3506  3620 D PowerManagerService: mDisplayReady: false
07-05 14:15:57.753  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:15:57.753  3506  3620 D ColorFade: prepare: mode=4
07-05 14:15:57.753  4072  4532 D KeyguardViewMediator: onStartedGoingToSleep(3)
,07-05 14:15:57.753 10812 10812 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 14:15:57.753  3045  3045 I SurfaceFlinger: id=17 createSurf (1440x2560),2 flag=404, DolorFade
,07-05 14:15:57.773  5136  5136 D SamsungIME: IMPL finishInput
,07-05 14:15:57.773  5136  5136 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
07-05 14:15:57.773  5136  5136 D SamsungIME: saveAndClear +
07-05 14:15:57.773  5136  5136 D SamsungIME: saveAndClear -
,07-05 14:15:57.773  4072  4532 E KeyguardViewMediator: lockAfterTimeout = 5000 policyTimeout = 0
,07-05 14:15:57.783  3506  3620 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 28ms
,07-05 14:15:57.783  3506  3620 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1,
,07-05 14:15:57.783  4072  4532 D KeyguardViewMediator: timeout : 5000
,07-05 14:15:57.793  4072  4532 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 4,
07-05 14:15:57.793  4072  4532 D KeyguardViewMediator: notifyStartedGoingToSleep
07-05 14:15:57.793  4072  4072 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,07-05 14:15:57.793  4072  4072 D KeyguardFingerPrint: shouldListenForFingerprint ( isFingerPrintLockscreen = false , getLockoutAttemptDeadline = false , mIsUnlockingWithFingerprintForced = false
,07-05 14:15:57.793  4072  4072 V KeyguardUpdateMonitor: stopListeningForFingerprint()
07-05 14:15:57.793  4072  4072 D KeyguardViewMediator: handleNotifyStartedGoingToSleep
,07-05 14:15:57.813  3506  3620 D libEGL  : eglInitialize EGLDisplay = 0x7f8417e778
,07-05 14:15:57.823  3506  3620 D libEGL  : eglTerminate EGLDisplay = 0x7f8417e8e8
,07-05 14:15:57.823  3506  3620 D ColorFade: ColorFade is ready
,07-05 14:15:57.823  3506  3620 D DisplayPowerController: ColorFade: onAnimationStart
07-05 14:15:57.823  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:57.823  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 121 -> 121
,07-05 14:15:57.843  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
,07-05 14:15:57.863  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
,07-05 14:15:57.873  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
,07-05 14:15:58.113  3506  3620 D DisplayPowerState: !@ [0] ColorFade entry
07-05 14:15:58.113  3506  3620 D PowerManagerService: [input device light] onColorFadeExit(false)
07-05 14:15:58.113  3506  3620 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 14:15:58.123  3506  4035 D lights  : lcd : 0 +
,07-05 14:15:58.123  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:15:58.123  3506  3620 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,07-05 14:15:58.133  3506  4035 D lights  : lcd : 0 -
,07-05 14:15:58.213 10812 10812 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-05 14:15:58.213 10812 10812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:15:58.263  3506  3620 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@1b8a786, Service = Auto Rotation, used = 0
,07-05 14:15:58.263  3506  3620 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
07-05 14:15:58.263 10812 10812 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e68f872 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@eca3ac7, 16908290=android.view.AbsSavedState$1@eca3ac7}, android:focusedViewId=100}]}]
07-05 14:15:58.263 10812 10812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:15:58.263 10812 10812 V ActivityThread: updateVisibility : ActivityRecord{17b23ca token=android.os.BinderProxy@36508e3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:15:58.263 10812 10812 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:15:58.263 10812 10812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:15:58.263  3506  3620 V CAE     : stop(ContextProvider.java:155)
,07-05 14:15:58.273  3506  3620 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:15:58.273  3506  3620 V CAE     : disable(AutoRotationRunner.java:171)
,07-05 14:15:58.273  3506  3620 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
07-05 14:15:58.273  3506  3620 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
07-05 14:15:58.273  3073  3073 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-05 14:15:58.273  3506  3620 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:15:58.273  3506  3620 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:15:58.283  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
,07-05 14:15:58.293  3506  3620 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:15:58.293  3506  3620 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-05 14:15:58.293  3506  3620 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:15:58.293  3506  3620 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4a5d705, Service : PEDOMETER(1)
07-05 14:15:58.293  3506  3620 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@79dda68, Service : ACTIVITY_TRACKER_BATCH(1)
,07-05 14:15:58.303  3506  3620 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@941e3b2, Service : STEP_LEVEL_MONITOR(1)
07-05 14:15:58.303  3506  3620 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-05 14:15:58.303  3506  3620 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER(1)
,07-05 14:15:58.303  3506  3620 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:15:58.303  3506  3620 D SContextService: 	.unregisterCallback : 4, client=
,07-05 14:15:58.303  3506  3620 D SContextService: ===== SContext Service List =====
07-05 14:15:58.303  3506  3620 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Pedometer
07-05 14:15:58.303  3506  3620 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
07-05 14:15:58.303  3506  3620 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Step Level Monitor
07-05 14:15:58.303  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 14:15:58.303  3506  3620 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b31de81, Service : Activity Batch
07-05 14:15:58.303  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:58.303  3506  3620 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@887215e, Service : Activity Tracker
07-05 14:15:58.303  3506  3620 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:15:58.303  3506  3620 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@f69e671, service=Auto Rotation
07-05 14:15:58.303  3506  3620 V KeyguardServiceDelegate: onScreenTurnedOff()
07-05 14:15:58.303  4072  4088 D KeyguardViewMediator: notifyScreenTurnedOff
07-05 14:15:58.303  4072  4072 D KeyguardViewMediator: handleNotifyScreenTurnedOff
07-05 14:15:58.303  4072  4072 D vol.SecVolumeDialog: onScreenTurnedOff()
07-05 14:15:58.303  4072  4072 D vol.SecVolumeDialog: dismissH reason: 4
,07-05 14:15:58.303  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:15:58.303  4072  4072 D vol.SecVolumeDialog: dismissH : false
07-05 14:15:58.303  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 14:15:58.303  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:58.303  3506  3620 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:58.303  3506 11576 D MISC PowerHAL: sysfs_write +: /sys/class/input/event0/device/enabled: 0
07-05 14:15:58.303  3506 11577 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
07-05 14:15:58.303  3506 11576 D MISC PowerHAL: sysfs_write -: /sys/class/input/event0/device/enabled: 0
,07-05 14:15:58.313  3506 11577 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,07-05 14:15:58.313  3506  3633 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-05 14:15:58.313  3506  3633 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-05 14:15:58.313  3506  3633 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
07-05 14:15:58.313  3045  3045 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fad3c3c00
07-05 14:15:58.313  3045  3045 I hwcomposer: int exynos_setPowerMode(hwc_composer_device_1*, int, int):: disp(0), mode(0)
07-05 14:15:58.313  3506  3615 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 14:15:58.403  3506  3516 I art     : Background partial concurrent mark sweep GC freed 90439(6MB) AllocSpace objects, 64(1524KB) LOS objects, 31% free, 34MB/50MB, paused 1.451ms total 235.730ms
,07-05 14:15:58.493  3506  3633 D SurfaceControl: Excessive delay in setPowerMode(): 180ms
07-05 14:15:58.493  3506  3633 I libsuspend: !@autosuspend_wakeup_count_enable
07-05 14:15:58.493  3506  3633 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 181ms
07-05 14:15:58.493  3506  3633 I libsuspend: !@autosuspend_wakeup_count_enable done
07-05 14:15:58.493  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:15:58.493  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 14:15:58.493  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:58.493  3506  3620 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:15:58.493  3506  3620 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:15:58.493  3506  3620 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 14:15:58.493  3506  3620 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:58.493  3506  3620 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:15:58.493  3506  3633 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 188ms
07-05 14:15:58.493  3506  3620 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:15:58.493  3506  3620 D PowerManagerService: mDisplayReady: true
07-05 14:15:58.493  3506  4030 D PersonaManagerService: onfinishedGoingToSleep why = 3
07-05 14:15:58.493  3506  3620 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
07-05 14:15:58.493  4072  4532 D KeyguardViewMediator: onFinishedGoingToSleep(3)
07-05 14:15:58.493  3506  3620 I PowerManagerService: [PWL] Off : 0s ago
07-05 14:15:58.493  4072  4532 D KeyguardViewMediator: notifyFinishedGoingToSleep
07-05 14:15:58.493  3506  3620 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
07-05 14:15:58.493  3506  3654 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
07-05 14:15:58.493  3506  3620 D PowerManagerService: handleSandman : startDream(true)
07-05 14:15:58.493  3506  3620 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-05 14:15:58.493  3506  3620 I PowerManagerService: Sleeping (uid 1000)...
07-05 14:15:58.493  4072  4072 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
07-05 14:15:58.493  3506  3620 D PowerManagerService: [s] UserActivityState : 4 -> 0
07-05 14:15:58.493  3506  3620 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-05 14:15:58.493  4072  4072 D KeyguardEffectViewController: onScreenTurnedOff
,07-05 14:15:58.493  4072  4072 D KeyguardEffectViewController: ## mBackgroundView.onPause()
07-05 14:15:58.493  4072  4072 D KeyguardEffectViewWallpaper: onPause()
07-05 14:15:58.493  4072  4072 D SecKeyguardStatusView: onFinishedGoingToSleep() why=3
,07-05 14:15:58.503  4072  4072 V KeyguardFingerPrint: updateFingerprintListeningState(false)
,07-05 14:15:58.503  4072  4072 D KeyguardFingerPrint: shouldListenForFingerprint ( isFingerPrintLockscreen = false , getLockoutAttemptDeadline = false , mIsUnlockingWithFingerprintForced = false
,07-05 14:15:58.503  4072  4072 V KeyguardUpdateMonitor: stopListeningForFingerprint()
,07-05 14:15:58.523  3506  3506 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3506) 
,07-05 14:15:58.523  3506  3506 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
07-05 14:15:58.523  3506  3506 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 14:15:58.523  3506  3506 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 14:15:58.533  3506  3506 D SensorManager: registerListener :: 6, TMD4093 RGB Sensor, 200000, 0,  
,07-05 14:15:58.533  3506  3506 D BatteryService: turn on LED for fully charged
,07-05 14:15:58.573  3506  3506 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-05 14:15:58.573  3506  3506 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
,07-05 14:15:58.573  3506  3506 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
,07-05 14:15:58.573  3506  3506 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-05 14:15:58.573  3073  3128 D Sensorhubs: sendContextData: -76, 13, -46, 0
07-05 14:15:58.573  3506  3506 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 12, 15, 58,
,07-05 14:15:58.573  3506  3506 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 15, 58
07-05 14:15:58.573  3073  3073 D Sensorhubs: sendContextData: -63, 14, 12, 15, 58
,07-05 14:15:58.583  3506  3506 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-05 14:15:58.603  3506  3506 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,07-05 14:15:58.603  3506  3506 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-05 14:15:58.603  3506  3952 D MotionRecognitionService: Screen off setAccIntStatus 
07-05 14:15:58.603  3506  3506 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 14:15:58.603  3506  3952 E MotionRecognitionService:  handler : SCREEN_OFF end 
07-05 14:15:58.603  3506  3506 D UcmService: notifyChangeToPlugin event 16
07-05 14:15:58.603  3506  3506 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 14:15:58.603  3506  3506 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 14:15:58.603  3506  3506 D UcmService: notifying to unmanaged plugin
07-05 14:15:58.603  4477  4489 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-05 14:15:58.603  3506  3506 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 14:15:58.603  3506  3506 D UcmService: agentService status-0
07-05 14:15:58.603  3506  3506 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 14:15:58.603  3506  3506 D UcmService: notifying to unmanaged plugin
07-05 14:15:58.603  4490  4504 D BootAgentService: notifyChange eventId-16
07-05 14:15:58.603  3506  3506 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
,07-05 14:15:58.603  3506  3506 D UcmService: agentService status--1
07-05 14:15:58.603  3506  3506 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-05 14:15:58.623  3506  3588 I ActivityManager: Start proc 11579:com.samsung.android.SettingsReceiver/1000 for broadcast-3 com.samsung.android.SettingsReceiver/.AccessibilityReceiver
,07-05 14:15:58.623 11579 11579 E Zygote  : v2
07-05 14:15:58.623 11579 11579 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:15:58.623 11579 11579 I libpersona: KNOX_SDCARD not a persona
,07-05 14:15:58.623 11579 11579 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
,07-05 14:15:58.633  3506  3506 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-05 14:15:58.633 11579 11579 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:15:58.633 11579 11579 E Zygote  : accessInfo : 0
,07-05 14:15:58.643  3506  3992 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
,07-05 14:15:58.643  3506  3992 D WifiNative-wlan0: callSECApiVoid - ID [19]
07-05 14:15:58.643  4273  4273 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
07-05 14:15:58.643  3506  3506 D NotificationService: ACTION_SCREEN_OFF
07-05 14:15:58.643  3506  3506 D EdgeLight: Turning off
,07-05 14:15:58.643  3506  3506 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3506) 
07-05 14:15:58.643  3506  3506 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
,07-05 14:15:58.643  3506  3992 E WifiNative-wlan0: do suspend true
,07-05 14:15:58.653  3066  3709 D audio_hw_primary: adev_set_parameters: enter: kvpairs: screen_state=off
,07-05 14:15:58.673  3506  3506 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,07-05 14:15:58.673  3506  3506 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-05 14:15:58.683 11579 11579 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:15:58.683 11579 11579 D ActivityThread: Added TimaKeyStore provider
,07-05 14:15:58.683  3506  3506 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
07-05 14:15:58.683  3506  3506 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@887215e, Service = Activity Tracker, used = 0
,07-05 14:15:58.683  3506  3506 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
07-05 14:15:58.683  3506  3506 V CAE     : stop(ContextProvider.java:155)
,07-05 14:15:58.683  3506  3506 V CAE     : clear(ActivityTrackerRunner.java:108)
07-05 14:15:58.683  3506  3506 V CAE     : disable(ActivityTrackerRunner.java:96)
,07-05 14:15:58.693  3506  3506 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,,
07-05 14:15:58.693  3506  3506 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
07-05 14:15:58.693  3073  3128 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-05 14:15:58.693  3506  3506 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-05 14:15:58.693  3506  3506 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:15:58.693  3506  4520 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8dee991 u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{939d0f6 11579:com.samsung.android.SettingsReceiver/1000}
,07-05 14:15:58.703 11579 11579 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,07-05 14:15:58.703  3506  3506 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:15:58.703  3506  3987 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
07-05 14:15:58.703 11579 11579 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-05 14:15:58.703  3506  3506 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-05 14:15:58.703  3506  3506 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:15:58.713  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@4a5d705, Service : PEDOMETER(1)
07-05 14:15:58.713  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@79dda68, Service : ACTIVITY_TRACKER_BATCH(1)
07-05 14:15:58.713  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@941e3b2, Service : STEP_LEVEL_MONITOR(1)
,07-05 14:15:58.713  3506  3506 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b36245f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-05 14:15:58.713  3506  3506 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-05 14:15:58.713 11579 11579 D ResourcesManager: For user 0 new overlays fetched Null
07-05 14:15:58.713  3506  3506 D SContextService: 	.unregisterCallback : 3, client=
07-05 14:15:58.713  3506  3506 D SContextService: ===== SContext Service List =====
07-05 14:15:58.713  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Pedometer
07-05 14:15:58.713  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@4fe435a, Service : Step Level Monitor
07-05 14:15:58.713  3506  3506 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@b31de81, Service : Activity Batch
,07-05 14:15:58.713  3506  3506 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$12@6571a99, service=Activity Tracker
,07-05 14:15:58.713 11579 11579 I InjectionManager: Inside getClassLibPath caller 
,07-05 14:15:58.713  3506  3615 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,07-05 14:15:58.713  3506  3615 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:15:58.723 11579 11579 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,07-05 14:15:58.723  3506  3506 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
07-05 14:15:58.723  3506  3990 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
,07-05 14:15:58.723  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-05 14:15:58.723  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-05 14:15:58.723 11579 11579 D InjectionManager: InjectionManager
,07-05 14:15:58.723 11579 11579 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
07-05 14:15:58.723 11579 11579 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
07-05 14:15:58.723 11579 11579 I InjectionManager: featureStore :{}
,07-05 14:15:58.753  3506  3916 I Sensors : #>LightSensor r=14 g=10 b=9 c=33 atime=245 again=64 lux=22
,07-05 14:15:58.753  3506  3629 D LightsService: [SvcLED]  onSensorChanged::light value = 22
07-05 14:15:58.753  3506  3629 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 14:15:58.753  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 281 (W:26), CP = 244, CUR = 63, LCD = 0
,07-05 14:15:58.753  3506  3629 D SensorManager: unregisterListener ::   
,07-05 14:15:58.753  3506  3629 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
07-05 14:15:58.753  3506  3629 D lights  : led_pattern : 5 +
,07-05 14:15:58.753  3506  3629 D lights  : led_pattern : 5 -
,07-05 14:15:58.753  3506  3629 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-05 14:15:58.753  3506  3629 V AlarmManager:  remove PendingIntent] PendingIntent{c85ed47: PendingIntentRecord{f3bd974 android broadcastIntent}}
,07-05 14:15:59.183  3506  3582 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-05 14:15:59.183  4407 11591 D NfcService: call the applyRouting
,07-05 14:15:59.193  4072  4284 D NetworkController.MobileSignalController(0/2147483643): onDataActivity: direction=0
,07-05 14:15:59.193  4432  4432 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
,07-05 14:15:59.213  5136  5136 E SamsungIME: invoke(): method is null
,07-05 14:15:59.223  5399  5399 D BtGatt.GattService: LCD turned off
,07-05 14:15:59.223  5399  5536 D BtGatt.ScanManager: handleLcdOffIntent
07-05 14:15:59.223  5399  5536 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =5
,07-05 14:15:59.243  4633 11593 D MdnsClient: Multicast lock held. Releasing
,07-05 14:15:59.263  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 282 (W:28), CP = 244, CUR = 63, LCD = 0
,07-05 14:15:59.273  3506  3506 I SurveyLogManager: mDeviceInfo.mScreen = false
,07-05 14:15:59.283  4157  4157 D Recents : onTaskStackChanged
,07-05 14:15:59.283  8306  8306 I BeaconManager: BeaconManager.onReceive - receive Action : android.intent.action.SCREEN_OFF
07-05 14:15:59.283  8306  8306 D BeaconManager: BeaconManager.onReceive - end
07-05 14:15:59.283  8306  8351 I BeaconManager: BeaconManager.BeaconManagerWorkHandler - BroadcastReceiver onReceive start
07-05 14:15:59.283  8306  8351 D BeaconManager: BeaconManager.mScreenObserver - action:android.intent.action.SCREEN_OFF
07-05 14:15:59.283  8306  8351 D BeaconManager: AppControlManager.screenOnIntentReceived - start
07-05 14:15:59.283  8306  8351 D BeaconManager: AppControlManager.screenOnIntentReceived - end
07-05 14:15:59.283  8306  8351 D BeaconManager: EasySetupManager.screenOnIntentReceived - start
07-05 14:15:59.283  8306  8351 D BeaconManager: EasySetupManager.screenOnIntentReceived - end
07-05 14:15:59.283  8306  8351 D BeaconManager: BleScanHelper.screenOnIntentReceived - start
,07-05 14:15:59.283  4876  4876 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7948E844A51B2F10E7C31A850CCA08F880ABEEF87F6E6A4C1C58A024DF4C59CCBAB058FE760D19BABE2141DC34E7050B2]}
07-05 14:15:59.283  4876  4876 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB73EA894562B46724F5CBB481CE1644E72]}
,07-05 14:15:59.293  8306  8351 D BeaconManager: BleScanHelper.mBroadcastReceiver - Action: android.intent.action.SCREEN_OFF, user: 0
07-05 14:15:59.293  8306  8351 V BeaconManager: BleScanHelper.startBleScan - startBleScan
,07-05 14:15:59.293  8306  8351 D BluetoothAdapter: STATE_ON
07-05 14:15:59.293  3506  4030 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
07-05 14:15:59.293  8306  8351 D BeaconManager: BleScanHelper.screenOnIntentReceived - end
07-05 14:15:59.293  8306  8351 I BeaconManager: BeaconManager.BeaconManagerWorkHandler - BroadcastReceiver onReceive end
07-05 14:15:59.293  8306  8354 D BeaconManager: BleScanHelper.MSG_CALL_START_LESCAN - ($)
07-05 14:15:59.293  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:59.293  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:59.293  8306  8354 I BeaconManager: BleScanHelper.directStopLeScan - call BleScanner.stopScan()
07-05 14:15:59.293  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:59.293  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:59.293  8306  8354 D BluetoothLeScanner: Stop Scan
,07-05 14:15:59.293  4407 11591 D NfcService: index : 0
07-05 14:15:59.293  4407 11591 D NfcService: index : 1
07-05 14:15:59.293  4407 11591 D NfcService: index : 2
07-05 14:15:59.293  4876  4876 D [Weather Widget]  WeatherService: {[CC14338CDEB270B60D640F786827F117157AA4FCA31999F201B607282E8FB824]}
,07-05 14:15:59.293  3506  4446 I ActivityManager: Killing 9812:tv.peel.app/u0a210 (adj 15): DHA:empty #31
07-05 14:15:59.293  5399  5410 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager
07-05 14:15:59.293  5399  5410 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager
07-05 14:15:59.293  5399  5410 D BtGatt.GattService: stopScan() - queue size =1
,07-05 14:15:59.293  5399  5563 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.samsung.android.beaconmanager, msg: MESSAGE_STOP_SCAN
07-05 14:15:59.293  5399  5563 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 5, currDate: 5
07-05 14:15:59.293  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-05 14:15:59.293  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 13 => 13
07-05 14:15:59.293  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 13 => 13
07-05 14:15:59.293  5399  5563 D BtGatt.GattService: [GSIM LOG]: remove : com.samsung.android.beaconmanager at  BLE_SCAN_ACTUAL_DB
07-05 14:15:59.293  5399  5563 D BtGatt.GattService: [GSIM LOG]: remove : com.samsung.android.beaconmanager at  BLE_SCAN_REQUESTED_DB
07-05 14:15:59.303  5399  5411 D BtGatt.GattService: unregisterClient() - clientIf=7
07-05 14:15:59.303  5399  5536 D BtGatt.ScanManager: stop scan
07-05 14:15:59.303  5399  5536 D BtGatt.ScanManager: delete FilterIndex - 11
,07-05 14:15:59.303  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{bf2c764: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.303  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{a778dcd: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.303  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{baa0682: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:59.303  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=13
07-05 14:15:59.303  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:59.303  5399  5536 D BtGatt.ScanManager: delete FilterIndex - 12
,07-05 14:15:59.313  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=14
07-05 14:15:59.313  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:59.313  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{fec9193: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.313  5399  5536 D BtGatt.ScanManager: delete FilterIndex - 13
07-05 14:15:59.313  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=15
07-05 14:15:59.313  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:59.313  5399  5536 D BtGatt.ScanManager: delete FilterIndex - 14
07-05 14:15:59.313  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{6c6f5d0: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.313  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
07-05 14:15:59.313  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:59.313  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-05 14:15:59.313  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=100
07-05 14:15:59.313  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-05 14:15:59.313  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{7c39c9: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.313  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{8f608ce: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.313  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{4c4b3ef: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.313  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{6d9efc: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:59.313  3506  6477 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:15:59.313  3506  4840 V AlarmManager:  remove PendingIntent] PendingIntent{805a985: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:59.313  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{5ede3da: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.313  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{652a00b: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.313  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{173aee8: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.323  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{cfc5901: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.323  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{25663a6: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.363  3506  4444 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@98931e7)
07-05 14:15:59.363  3506  4000 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:15:59.363  3506  4000 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:15:59.363  3506  4000 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:15:59.363  3506  4115 D ActivityManager: isAutoRunBlockedApp:: tv.peel.app, Auto Run ON
,07-05 14:15:59.373  3506 11595 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:15:59.373  3506 11595 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.373  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{c48d194: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.373  3506  4840 V AlarmManager:  remove PendingIntent] PendingIntent{754843d: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.383  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{3751432: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.403  8306  8354 I BeaconManager: BleScanHelper.startBleScan - Start filter Scan(SCREEN_OFF)
,07-05 14:15:59.403  8306  8354 D BluetoothLeScanner: Start Scan
07-05 14:15:59.403  8306  8354 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.403  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:59.403  8306  8354 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.403  8306  8354 D BluetoothAdapter: STATE_ON
07-05 14:15:59.403  5399  5411 D BtGatt.GattService: registerClient() - UUID=11d19df5-df1b-460a-a516-e3934a0c97d0
,07-05 14:15:59.413  3506 11595 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:15:59.433  3506 11595 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:15:59.443  3506 11595 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:15:59.453  5399  5517 D BtGatt.GattService: onClientRegistered() - UUID=11d19df5-df1b-460a-a516-e3934a0c97d0, clientIf=7
,07-05 14:15:59.453  8306  8319 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,07-05 14:15:59.453  5399  5706 D BtGatt.GattService: start scan with filters
,07-05 14:15:59.453  5399  5706 D BtGatt.GattService: getScanSettings
,07-05 14:15:59.463  5399  5706 D BtGatt.GattService: Is it foreground application = false
07-05 14:15:59.463  5399  5706 D BtGatt.GattService: Its a background application running with Low Power scan mode
,07-05 14:15:59.463  5399  5706 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (100/1 vs -2147483648/0)
,07-05 14:15:59.473  5399  5706 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager
,07-05 14:15:59.473  5399  5706 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.samsung.android.beaconmanager
07-05 14:15:59.473  5399  5563 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.samsung.android.beaconmanager, msg: MESSAGE_START_SCAN
07-05 14:15:59.473  5399  5563 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 5, currDate: 5
07-05 14:15:59.473  5399  5536 D BtGatt.ScanManager: handling starting scan
,07-05 14:15:59.473  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.473  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.473  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.483  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.483  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.483  5399  5536 D BluetoothAdapter: STATE_ON
,07-05 14:15:59.483  5399  5517 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,07-05 14:15:59.483  3506  3524 V AlarmManager:  remove PendingIntent] PendingIntent{5ad0583: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.483  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:59.483  5399  5536 D BtGatt.ScanManager: set filter index= 15 for clientIf= 7
,07-05 14:15:59.483  5399  5536 D BtGatt.ScanManager: addFilterToController: 5
07-05 14:15:59.493  5399  5517 D BtGatt.GattService: onScanFilterConfig() - clientIf=7, action = 0 status = 0, filterType=5, availableSpace=47
07-05 14:15:59.493  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-05 14:15:59.493  5399  5536 D BtGatt.ScanManager: High Rssi Filter value is = -128,
07-05 14:15:59.493  5399  5536 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-05 14:15:59.493  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{8ab7300: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:59.493  5399  5536 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =1
07-05 14:15:59.493  5399  5563 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.samsung.android.beaconmanager : 5
,07-05 14:15:59.493  5399  5563 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.samsung.android.beaconmanager, com.samsung.android.beaconmanager
07-05 14:15:59.493  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
07-05 14:15:59.493  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:59.493  5399  5536 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
07-05 14:15:59.493  5399  5536 D BtGatt.ScanManager: addFilterToController: 5
,07-05 14:15:59.503  5399  5517 D BtGatt.GattService: onScanFilterConfig() - clientIf=7, action = 0 status = 0, filterType=5, availableSpace=46
,07-05 14:15:59.503  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-05 14:15:59.503  5399  5536 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-05 14:15:59.503  5399  5536 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,07-05 14:15:59.503  5399  5536 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =1
,07-05 14:15:59.503  5399  5517 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=14
07-05 14:15:59.503  5399  5517 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-05 14:15:59.503  3506  4839 V AlarmManager:  remove PendingIntent] PendingIntent{a2739: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:59.503  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-05 14:15:59.503  5399  5536 I BtGatt.ScanManager: custom scan scanMode = 100
07-05 14:15:59.503  5399  5536 I BtGatt.ScanManager: New scan mode custom scan scanInterval = 3120scanWindow = 55
07-05 14:15:59.503  5399  5536 E BtGatt.ScanManager: default value of curScanSetting 0 is choosen
07-05 14:15:59.503  5399  5536 I BtGatt.ScanManager: newScanMode = 1newcurScanSetting = 0
07-05 14:15:59.503  5399  5536 I BtGatt.ScanManager: comparing = 1 with = 0
07-05 14:15:59.503  5399  5536 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=100 mLastConfiguredScanSetting=-2147483648
07-05 14:15:59.503  5399  5536 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 4992configureRegularScanParams - scanWindow = 88
,07-05 14:15:59.503  5399  5517 D BtGatt.GattService: onScanParamSetupCompleted() status=0, clientIf=7
07-05 14:15:59.503  5399  5517 D BtGatt.GattService: onScanParamSetupCompleted : 0
07-05 14:15:59.513  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{b5c417e: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.samsung.android.beaconmanager : 217
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24462015
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.samsung.android.beaconmanager : 100
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 100
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 13 => 13
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 13 => 13
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 13 => 13
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 13 => 13
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 100
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 13 => 13
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 13 => 13
07-05 14:15:59.513  5399  5563 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24462015
,07-05 14:15:59.513  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{7b076df: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.523  3506  4840 V AlarmManager:  remove PendingIntent] PendingIntent{9d4bf2c: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.523  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{9dcfdf5: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.523  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{8f6f78a: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.533  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{f4fa1fb: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.533  3506 11595 I BatteryStatsDumper: Writing to database completed
,07-05 14:15:59.533  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{b64a218: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.543  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{9cc8471: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.543  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{cd50256: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.553  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{1ec62d7: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.553  3506  4340 V AlarmManager:  remove PendingIntent] PendingIntent{10dc7c4: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.553  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{b53f6ad: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.563  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{eb6ede2: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.573  3506  3524 V AlarmManager:  remove PendingIntent] PendingIntent{f2a5573: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}},
,07-05 14:15:59.573  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{5019c30: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.583  3506  4839 V AlarmManager:  remove PendingIntent] PendingIntent{c6650a9: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.593  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{fda062e: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}},
,07-05 14:15:59.603  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{34ad5cf: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.603  3506  4840 V AlarmManager:  remove PendingIntent] PendingIntent{11c4b5c: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}},
,07-05 14:15:59.613  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{d2a4e65: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.613  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{604573a: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.623  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{348ffeb: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.623  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{ed0c148: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.633  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{f766be1: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.633  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{b50ad06: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.643  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{eb5afc7: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.653  3506  4340 V AlarmManager:  remove PendingIntent] PendingIntent{9d4a9f4: PendingIntentRecord{a2d14c6 com.android.bluetooth broadcastIntent}}
,07-05 14:15:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:16:02.793  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:16:02.813  4072  4072 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 4, mDelayedShowingSequence = 4
,07-05 14:16:02.823  4072  4072 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-05 14:16:02.843  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:16:02.843  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:16:05.793  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:16:05.793  3506  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:16:05.793  3506  3524 D BatteryService: online:4, current avg:81, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:111
07-05 14:16:05.793  3506  3524 D BatteryService: stay LED for fully charged
07-05 14:16:05.793  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:05.803  3506  3506 I MotionRecognitionService: Plugged
07-05 14:16:05.803  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:16:05.803  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:16:05.803  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:16:05.803  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:16:05.803  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:05.803  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:16:05.803  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:05.813  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:05.813  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:05.813  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:16:05.833  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:16:05.843  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:05.843  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:05.843  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:16:05.853  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:16:05.853  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:09.323  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 283 (W:28), CP = 244, CUR = 81, LCD = 0
,07-05 14:16:11.673  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:16:14.413  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:16:14.413  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:16:15.873  3506  6519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:16:15.873  3506  6519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:16:15.873  3506  6519 D BatteryService: online:4, current avg:91, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:100
07-05 14:16:15.873  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:16:15.883  3506  3506 I MotionRecognitionService: Plugged
07-05 14:16:15.883  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:16:15.883  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:16:15.883  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:16:15.883  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:16:15.883  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:15.883  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:16:15.883  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:16:15.883  3506  6519 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
07-05 14:16:15.893  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:15.883  3506  6519 D BatteryService: stay LED for fully charged
07-05 14:16:15.893  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:16:15.893  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:16:15.913  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:16:15.923  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:15.923  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:15.923  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:16:15.933  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:16:15.933  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:19.363  3506  6477 D SSRM:n  : SIOP:: AP = 290, PST = 283 (W:28), CP = 244, CUR = 91, LCD = 0
,07-05 14:16:25.733  3506  4290 E Watchdog: !@Sync 28 [07-05 14:16:25.741]
,07-05 14:16:25.933  3506  4839 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:16:25.933  3506  4839 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:16:25.933  3506  4839 D BatteryService: online:4, current avg:92, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:97
07-05 14:16:25.933  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:16:25.943  3506  3506 I MotionRecognitionService: Plugged
07-05 14:16:25.943  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:16:25.943  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:16:25.943  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:16:25.943  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:16:25.943  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:25.943  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:16:25.943  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:25.943  3506  4839 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
07-05 14:16:25.953  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:25.953  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:16:25.953  3506  4839 D BatteryService: stay LED for fully charged
07-05 14:16:25.963  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:16:25.983  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:16:25.993  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:25.993  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:25.993  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:16:25.993  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:16:25.993  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:28.333  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:16:29.253  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:16:29.273  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{18c7160: PendingIntentRecord{5788321 com.google.android.gms broadcastIntent}}
,07-05 14:16:29.283  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:16:29.283  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:16:29.283  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:16:29.283  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:16:29.333  3506  3506 I BackgroundCompactionService: onStart. jobID=801,
07-05 14:16:29.333  3506  3506 I BackgroundCompactionService: onStart done. jobID=801
07-05 14:16:29.333  3506 11678 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-05 14:16:29.333  3506 11678 I BackgroundCompactionService: compact_memory command done
,07-05 14:16:29.403  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:28), CP = 244, CUR = 92, LCD = 0
,07-05 14:16:36.003  3506  4445 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:16:36.003  3506  4445 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:16:36.003  3506  4445 D BatteryService: online:4, current avg:91, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:80
07-05 14:16:36.003  3506  4445 D BatteryService: stay LED for fully charged
,07-05 14:16:36.003  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:36.013  3506  3506 I MotionRecognitionService: Plugged
07-05 14:16:36.013  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:16:36.013  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:16:36.013  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:16:36.013  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:16:36.013  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:36.013  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:16:36.013  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:36.023  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:36.023  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:16:36.023  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate,
,07-05 14:16:36.043  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:16:36.053  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:36.053  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:36.053  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:16:36.053  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:16:36.053  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:39.293  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:16:39.303  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:16:39.443  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 244, CUR = 91, LCD = 0
,07-05 14:16:44.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:16:44.333  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:16:46.063  3506  4840 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:16:46.063  3506  4840 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:16:46.063  3506  4840 D BatteryService: online:4, current avg:87, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:77
07-05 14:16:46.063  3506  4840 D BatteryService: stay LED for fully charged
07-05 14:16:46.063  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:16:46.073  3506  3506 I MotionRecognitionService: Plugged
07-05 14:16:46.073  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:16:46.073  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:16:46.073  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:16:46.073  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:16:46.073  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:46.073  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:16:46.073  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:46.083  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:46.083  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:16:46.083  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:46.093  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:16:46.103  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:16:46.103  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:46.103  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:16:46.113  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:46.113  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:49.493  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 243, CUR = 87, LCD = 0
,07-05 14:16:55.743  3506  4290 E Watchdog: !@Sync 29 [07-05 14:16:55.748]
,07-05 14:16:59.553  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 243, CUR = 87, LCD = 0
,07-05 14:16:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:17:09.623  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 243, CUR = 87, LCD = 0
,07-05 14:17:16.113  3506  4446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:17:16.113  3506  4446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4329, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:17:16.113  3506  4446 D BatteryService: online:4, current avg:5, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:17:16.113  3506  4446 D BatteryService: stay LED for fully charged
07-05 14:17:16.123  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:16.133  3506  3506 I MotionRecognitionService: Plugged
07-05 14:17:16.133  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:17:16.133  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:17:16.133  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:17:16.133  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:17:16.133  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:17:16.133  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:17:16.133  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:17:16.143  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:16.143  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:17:16.143  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:17:16.163  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:17:16.163  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:17:16.163  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:17:16.173  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:16.173  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:16.173  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:17:19.673  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 242, CUR = 5, LCD = 0
,07-05 14:17:25.743  3506  4290 E Watchdog: !@Sync 30 [07-05 14:17:25.755]
,07-05 14:17:26.283  3506  3928 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 14:17:26.283  3506  3928 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:17:26.293  3506  3927 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:17:27.553  4355  5702 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:17:28.443  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:17:29.753  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 242, CUR = 5, LCD = 0
,07-05 14:17:32.893  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 14:17:32.893  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:17:32.903  3506  3928 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 14:17:32.903  3506  3928 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:17:33.483  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:17:33.563  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:17:33.563  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:17:33.573  3506  4839 V AlarmManager:  remove PendingIntent] PendingIntent{d2463b6: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.583  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{3a418b7: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.593  3506  3524 V AlarmManager:  remove PendingIntent] PendingIntent{f07824: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.603  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{ad64f8d: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.613  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{d8b0542: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.613  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{2d78953: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.633  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{acef290: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.653  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{3655789: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.673  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{fc8338e: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.693  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{5c767af: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.703  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{7d8a7bc: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.723  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{1c2e345: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.723  3506  4839 V AlarmManager:  remove PendingIntent] PendingIntent{d97fa9a: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.723  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{52ccfcb: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.733  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{d6683a8: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.733  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{cb36ec1: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.733  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{e6b2666: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.743  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{2369da7: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.743  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{b743254: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.753  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{8c735fd: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.753  3506  3524 V AlarmManager:  remove PendingIntent] PendingIntent{df342f2: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.753  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{8256d43: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.763  3506  3525 V AlarmManager:  remove PendingIntent] PendingIntent{40c1fc0: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.763  3506  4340 V AlarmManager:  remove PendingIntent] PendingIntent{95634f9: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.763  3506  4115 V AlarmManager:  remove PendingIntent] PendingIntent{f6e9c3e: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.773  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{ba79a9f: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.773  3506  4840 V AlarmManager:  remove PendingIntent] PendingIntent{d7377ec: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.783  3506  4520 V AlarmManager:  remove PendingIntent] PendingIntent{53c27b5: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.783  3506  4839 V AlarmManager:  remove PendingIntent] PendingIntent{9b43e4a: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.793  3506  4514 V AlarmManager:  remove PendingIntent] PendingIntent{3f541bb: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.793  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{b1626d8: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.803  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{b548a31: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.813  3506  4804 V AlarmManager:  remove PendingIntent] PendingIntent{7fff516: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.813  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{9ac3e97: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.823  3506  4444 V AlarmManager:  remove PendingIntent] PendingIntent{932d884: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.833  3506  4446 V AlarmManager:  remove PendingIntent] PendingIntent{2b6986d: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.843  3506  3524 V AlarmManager:  remove PendingIntent] PendingIntent{b7e4ca2: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:33.853  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{76c2d33: PendingIntentRecord{5e10f51 com.android.bluetooth broadcastIntent}}
,07-05 14:17:39.823  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 242, CUR = 5, LCD = 0
,07-05 14:17:46.173  3506  4444 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:46.183  3506  4444 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4329, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,07-05 14:17:46.183  3506  4444 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:17:46.183  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:17:46.193  3506  3506 I MotionRecognitionService: Plugged
07-05 14:17:46.193  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:17:46.193  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:17:46.193  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:17:46.193  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:17:46.193  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:17:46.193  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:17:46.193  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:17:46.193  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:17:46.203  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:17:46.203  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:46.203  3506  4444 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
07-05 14:17:46.203  3506  4444 D BatteryService: stay LED for fully charged
,07-05 14:17:46.223  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:17:46.233  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:17:46.233  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:46.233  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:17:46.233  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:17:46.233  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:17:49.853  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 242, LCD = 0
,07-05 14:17:55.753  3506  4290 E Watchdog: !@Sync 31 [07-05 14:17:55.760]
,07-05 14:17:59.913  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 241, LCD = 0
,07-05 14:17:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:18:02.203  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:18:02.543  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:18:02.983  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:18:03.033  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{832698f u0 com.sec.spp.push.ACTION_CONNECTION_STATE_CHECK qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6467d1f 7572:com.sec.spp.push/u0a33}
,07-05 14:18:03.033  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:18:03.033  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 14:18:03.063  5955  5955 I PedometerService: onStartCommand  true, true
,07-05 14:18:03.093  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:18:03.093  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:18:03.113  3506  4113 V AlarmManager:  remove PendingIntent] PendingIntent{eb61a1: PendingIntentRecord{d410e2a com.sec.spp.push broadcastIntent}}
,07-05 14:18:03.133  4692 11749 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm64
,07-05 14:18:03.133  7572  7572 E SPPClientService: [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,07-05 14:18:03.143  3506  4520 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f7dcfc6 u0 com.sec.spp.push.ACTION_SEND_PING_MESSAGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6467d1f 7572:com.sec.spp.push/u0a33}
,07-05 14:18:03.173  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:18:03.173  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:18:03.173  3506  4520 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4bf6ab4 u0 com.sec.dlc.DLC_REQUEST qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7668eaa 11261:com.sec.spp.push:RemoteDlcProcess/u0a33}
,07-05 14:18:03.213  4692 11748 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-05 14:18:03.223  3506  6505 V AlarmManager:  remove PendingIntent] PendingIntent{e9ac923: PendingIntentRecord{5427e20 com.sec.spp.push broadcastIntent}}
,07-05 14:18:03.233  9313 11759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:18:03.233  9313 11759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:18:03.233  3058  3725 D EnterpriseController: netId is 0
07-05 14:18:03.233  3058  3725 D Netd    : getNetworkForDns: using netid 502 for uid 10028
,07-05 14:18:03.253  7572  7660 E SPPClientService: [b] __PingReply__
,07-05 14:18:03.263  3506  4445 V AlarmManager:  remove PendingIntent] PendingIntent{946d47f: PendingIntentRecord{703fb87 com.sec.spp.push broadcastIntent}}
,07-05 14:18:03.283  3506  3588 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41ba495 u0 com.sec.spp.push.ACTION_HANDLE_PING_SUCCESS_EVENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6467d1f 7572:com.sec.spp.push/u0a33}
,07-05 14:18:03.313  3506  3987 V AlarmManager:  remove PendingIntent] PendingIntent{c28a9aa: PendingIntentRecord{a11af5a com.sec.spp.push broadcastIntent}}
,07-05 14:18:03.363  4692 11748 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-05 14:18:03.363  4692 11748 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-05 14:18:03.383  4692 11748 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-05 14:18:03.383  4692 11748 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-05 14:18:03.413  4692 11748 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-05 14:18:03.413  4692 11748 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-05 14:18:03.503  4633  6937 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-05 14:18:03.543  4633  6937 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,07-05 14:18:03.543  4633  6866 E PlayLoggerImpl: Service was disconnected.  Will try caching.
,07-05 14:18:03.593  4692 11748 I ContextCompilationHandl: Recognition context unchanged for APP_NAMES en-US
07-05 14:18:03.593  4692 11748 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-05 14:18:03.633  4633  7296 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-05 14:18:03.653  4633  7296 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,07-05 14:18:03.673  4633  6935 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-05 14:18:03.693  4633  6935 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,07-05 14:18:03.713  4633  7296 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-05 14:18:03.733  4633  7296 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,07-05 14:18:03.763  4633  6935 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-05 14:18:03.773  4633  6935 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,07-05 14:18:03.773  4692 11748 I ContextCompilationHandl: Recognition context unchanged for MUSIC_NAMES en-US,
,07-05 14:18:04.003  9313 11759 I qtaguid : Tagging socket 24 with tag e4efc1ab00000000{3840917931,0} uid -1, pid: 9313, getuid(): 10028
,07-05 14:18:04.123  9313 11759 I qtaguid : Tagging socket 30 with tag e4efc1ab00000000{3840917931,0} uid -1, pid: 9313, getuid(): 10028
,07-05 14:18:04.133  9313 11759 I qtaguid : Untagging socket 24
,07-05 14:18:04.143  9313 11759 E Volley  : [862] BasicNetwork.performRequest: Unexpected response code 400 for https://api.samsungknowledge.com/knowledge-ws/v1.0/messages?lc=en&td=2016-07-05
,07-05 14:18:04.143  3506  6519 V AlarmManager:  remove PendingIntent] PendingIntent{29c1868: PendingIntentRecord{d1f2ce7 com.sec.android.app.shealth startService}}
,07-05 14:18:09.983  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 241, LCD = 0
,07-05 14:18:13.133  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:18:13.133  3506  3990 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 14:18:16.233  3506  4514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:19.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:18:19.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:18:20.053  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 241, LCD = 0
,07-05 14:18:25.753  3506  4290 E Watchdog: !@Sync 32 [07-05 14:18:25.767]
,07-05 14:18:28.563  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:18:30.123  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 241, LCD = 0
,07-05 14:18:40.173  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 241, LCD = 0
,07-05 14:18:46.283  3506  4446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:50.213  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 240, LCD = 0
,07-05 14:18:55.763  3506  4290 E Watchdog: !@Sync 33 [07-05 14:18:55.774]
,07-05 14:18:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:19:00.283  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 240, LCD = 0
,07-05 14:19:10.323  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 240, LCD = 0
,07-05 14:19:16.343  3506  4340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:19:16.343  3506  4340 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:19:16.343  3506  4340 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:19:16.343  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:16.353  3506  4340 D BatteryService: stay LED for fully charged
,07-05 14:19:16.353  3506  3506 I MotionRecognitionService: Plugged
07-05 14:19:16.353  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:19:16.353  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:19:16.353  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:19:16.353  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:19:16.353  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:19:16.353  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:19:16.353  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:19:16.363  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,07-05 14:19:16.373  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2,
,07-05 14:19:16.363  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:19:16.383  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:16.383  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:16.383  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:19:16.393  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 14:19:16.393  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:19:16.403  4676  4676 D BatteryMonitor: new battery level: 100,
,07-05 14:19:20.353  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 240, LCD = 0
,07-05 14:19:25.773  3506  4290 E Watchdog: !@Sync 34 [07-05 14:19:25.782]
,07-05 14:19:28.633  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:19:30.413  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:30), CP = 240, LCD = 0
,07-05 14:19:32.013  3506  3946 V AlarmManager: Expired Alarm result :4
,07-05 14:19:32.043  3506  3506 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
07-05 14:19:32.043  3506  3506 V AlarmManagerEXT: <AppSync3 Whitelist>
07-05 14:19:32.043  3506  3506 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-05 14:19:32.053  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:19:32.053  4072  4072 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:19:32.243 10551 11792 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:19:32.293  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:19:32.303  4355  4355 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:19:32.333  4355  4370 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:19:32.333  4355  4370 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:19:32.333  4355  4370 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:19:32.333  4355  4370 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:19:32.383  4355  6920 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:19:32.383  4355  6920 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:19:32.383  4355  6920 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:19:32.383  4355  6920 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:19:32.423 10551 11793 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:19:32.423 10551 11792 E BooksSync: Soft error
07-05 14:19:32.423 10551 11792 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:19:32.423 10551 11792 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:19:32.423 10551 11792 E BooksSync: Sync error
07-05 14:19:32.423 10551 11792 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:19:32.423 10551 11792 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:19:32.433 10551 11792 I BooksSync: Finished books sync
,07-05 14:19:32.443 10551 11794 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-05 14:19:32.443 10551 11794 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-05 14:19:32.443  3506  3582 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1041209, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:19:32.453  3506  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:19:32.463  4355  4370 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:19:32.463  4355  4370 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:19:32.463  4355  4370 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:19:32.463  4355  4370 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:19:32.503 10551 11794 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:19:32.503 10551 11794 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:19:40.443  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), CP = 240, LCD = 0
,07-05 14:19:46.393  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:50.513  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), CP = 240, LCD = 0
,07-05 14:19:55.783  3506  4290 E Watchdog: !@Sync 35 [07-05 14:19:55.788]
,07-05 14:19:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:20:00.573  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:30), CP = 240, LCD = 0
,07-05 14:20:04.423  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:20:04.423  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:20:10.613  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), CP = 240, LCD = 0
,07-05 14:20:16.453  3506  4446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:20:16.453  3506  4446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:20:16.453  3506  4446 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
,07-05 14:20:16.453  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:20:16.463  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:20:16.463  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:20:16.473  3506  3506 I MotionRecognitionService: Plugged
07-05 14:20:16.473  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:20:16.473  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:20:16.473  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:20:16.473  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:20:16.473  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:20:16.473  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:20:16.473  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:20:16.473  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:20:16.473  3506  4446 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
07-05 14:20:16.473  3506  4446 D BatteryService: stay LED for fully charged
,07-05 14:20:16.493  4676  4676 D CommonServiceConfiguration: getStringValueSetting,
,07-05 14:20:16.503  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 14:20:16.503  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:16.503  4676  4676 D BatteryMonitor: new battery level: 100,
,07-05 14:20:16.513  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 14:20:16.513  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:20:19.453  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:20:19.453  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:20:20.653  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), CP = 240, LCD = 0
,07-05 14:20:25.783  3506  4290 E Watchdog: !@Sync 36 [07-05 14:20:25.796]
,07-05 14:20:28.743  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:20:28.853  4515  4571 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 1Kb duration : 104ms lastUpdatedAfter : 145449ms
,07-05 14:20:30.713  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:30), CP = 240, LCD = 0
,07-05 14:20:40.743  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 240, LCD = 0
,07-05 14:20:46.503  3506  4514 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:20:46.503  3506  4514 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:20:46.503  3506  4514 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:20:46.513  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:20:46.513  3506  3506 I MotionRecognitionService: Plugged
07-05 14:20:46.513  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:20:46.513  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:20:46.513  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:20:46.513  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:20:46.513  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:20:46.513  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:20:46.513  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:20:46.523  3506  4514 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
07-05 14:20:46.523  3506  4514 D BatteryService: stay LED for fully charged
,07-05 14:20:46.523  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:20:46.523  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:20:46.523  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:20:46.533  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:20:46.533  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:20:46.543  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:20:46.543  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:20:46.543  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:20:46.543  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:46.783  3506  3946 V AlarmManager: Expired Alarm result :8
,07-05 14:20:50.803  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 240, LCD = 0
,07-05 14:20:55.793  3506  4290 E Watchdog: !@Sync 37 [07-05 14:20:55.804]
,07-05 14:21:00.873  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 240, LCD = 0
,07-05 14:21:10.903  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 240, LCD = 0
,07-05 14:21:16.553  3506  6505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:21:16.563  3506  6505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:21:16.563  3506  6505 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:21:16.563  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:21:16.563  3506  3506 I MotionRecognitionService: Plugged
07-05 14:21:16.563  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:21:16.563  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:21:16.573  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:21:16.573  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:21:16.573  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:21:16.573  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:21:16.573  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:21:16.573  3506  6505 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
07-05 14:21:16.573  3506  6505 D BatteryService: stay LED for fully charged
,07-05 14:21:16.583  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:21:16.583  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:16.583  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:21:16.603  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:21:16.613  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:21:16.613  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:16.613  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:21:16.623  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:21:16.623  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:21:20.963  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:21:25.803  3506  4290 E Watchdog: !@Sync 38 [07-05 14:21:25.811]
,07-05 14:21:28.953  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:21:31.033  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:21:41.063  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:21:46.613  3506  3987 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:21:46.613  3506  3987 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:21:46.613  3506  3987 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:21:46.613  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:21:46.623  3506  3506 I MotionRecognitionService: Plugged
07-05 14:21:46.623  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:21:46.623  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:21:46.623  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:21:46.623  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:21:46.623  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:21:46.623  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:21:46.623  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:21:46.633  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:21:46.633  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:21:46.633  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:46.643  3506  3987 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
07-05 14:21:46.643  3506  3987 D BatteryService: stay LED for fully charged
,07-05 14:21:46.653  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:21:46.663  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:21:46.663  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:46.663  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:21:46.673  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:21:46.673  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:21:51.113  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:21:55.813  3506  4290 E Watchdog: !@Sync 39 [07-05 14:21:55.818]
,07-05 14:22:01.193  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:22:11.243  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:22:16.663  3506  4839 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:21.313  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:22:23.263  3506  3582 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:22:23.283  3506  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/usagestats/0/daily/1467676800000.bak
,07-05 14:22:23.303  3506  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/usagestats/0/weekly/1467244800000.bak
,07-05 14:22:23.313  3506  3582 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/usagestats/0/monthly/1467072000000.bak
,07-05 14:22:25.813  3506  4290 E Watchdog: !@Sync 40 [07-05 14:22:25.826]
,07-05 14:22:26.283  3506  3928 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 14:22:26.283  3506  3928 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:22:26.293  3506  3927 D TimaService: TimaServiceHandler.handleMessage what =1,
,07-05 14:22:29.093  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:22:31.383  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:22:31.723  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 14:22:31.723  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:22:31.743  3506  3928 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-05 14:22:31.743  3506  3928 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:22:41.413  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:22:46.243  3073  3127 D Sensorhubs: readLargeContextData: 1, 1, 26, 4, 2, -107, -74, 112, 1, 1, 2, 18, 79, -117
07-05 14:22:46.243  3506  3949 D SensorHubManager: onGetSensorHubDataLocked: library(14) = 1, 1, 26, 4, 2, -107, -74, 112, 1, 1, 2, 18, 79, -117
,07-05 14:22:46.253  3506  3948 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 12, 22, 46,
,07-05 14:22:46.253  3506  3948 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 22, 46,
,07-05 14:22:46.263  3073  3073 D Sensorhubs: sendContextData: -63, 14, 12, 22, 46,
,07-05 14:22:46.263  3506  3948 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :14], AP_SLEEP
,07-05 14:22:46.273  3506  3948 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 14,
,07-05 14:22:46.273  3506  3948 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 4, 2, -107, -74, 112, 1, 1, 2, 18, 79, -117,
,07-05 14:22:46.273  3506  3948 W CAE     : parse(ActivityTrackerBatchRunner.java:236) - parse start,
,07-05 14:22:46.273  3506  3948 I CAE     : getMostActivity(ActivityTrackerBatchRunner.java:321) - size:1
,07-05 14:22:46.273  3506  3948 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER_BATCH =================
,07-05 14:22:46.283  3506  3948 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], Duration=[1200011], Count=[1], OperationMode=[2], ActivityType=[1], MostActivity=[1], TimeStamp=[1467720166000]
,07-05 14:22:46.283  3506  3951 D SContextService: updateSContext() : event = Activity Batch
,07-05 14:22:46.283  3506  3948 W CAE     : parse(ActivityTrackerBatchRunner.java:307) - parse end
,07-05 14:22:46.713  3506  3987 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:22:46.723  3506  3987 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:22:46.723  3506  3987 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:22:46.723  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:22:46.723  3506  3987 D BatteryService: stay LED for fully charged
07-05 14:22:46.723  3506  3506 I MotionRecognitionService: Plugged
07-05 14:22:46.723  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:22:46.723  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:22:46.723  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:22:46.723  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:22:46.723  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:22:46.733  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:22:46.733  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:22:46.733  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:22:46.733  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:46.743  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:22:46.753  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:22:46.753  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:22:46.753  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:22:46.763  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:22:46.763  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:46.763  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:51.453  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:22:55.823  3506  4290 E Watchdog: !@Sync 41 [07-05 14:22:55.833]
,07-05 14:22:59.993  3506  3946 V AlarmManager: Expired Alarm result :8
07-05 14:22:59.993  3506  3946 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=1249180 batch.start=1295979
,07-05 14:23:01.513  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:23:04.133  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:23:04.143  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:23:11.543  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:23:16.773  3506  4839 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:23:16.773  3506  4839 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:23:16.773  3506  4839 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:23:16.773  3506  4839 D BatteryService: stay LED for fully charged
07-05 14:23:16.773  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:16.783  3506  3506 I MotionRecognitionService: Plugged
07-05 14:23:16.783  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:23:16.783  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:23:16.783  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:23:16.783  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:23:16.783  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:23:16.783  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:23:16.783  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:23:16.783  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 14:23:16.793  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:23:16.793  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:16.793  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:16.803  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:23:16.803  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:16.803  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:23:16.803  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:23:16.813  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:19.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:23:19.213  3058  3721 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:23:21.603  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:23:25.833  3506  4290 E Watchdog: !@Sync 42 [07-05 14:23:25.840]
,07-05 14:23:29.193  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:23:29.293  4515  4571 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 89ms lastUpdatedAfter : 180436ms
,07-05 14:23:31.663  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:30), CP = 239, LCD = 0
,07-05 14:23:41.703  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:30), CP = 238, LCD = 0
,07-05 14:23:46.823  3506  6519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:23:46.823  3506  6519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:23:46.823  3506  6519 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:23:46.823  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:23:46.833  3506  3506 I MotionRecognitionService: Plugged
07-05 14:23:46.833  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:23:46.833  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:23:46.833  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:23:46.833  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:23:46.833  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:23:46.833  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:23:46.833  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:23:46.833  3506  6519 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
07-05 14:23:46.843  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:23:46.833  3506  6519 D BatteryService: stay LED for fully charged
07-05 14:23:46.843  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:23:46.853  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:23:46.873  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:23:46.883  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:23:46.883  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:46.883  4676  4676 D BatteryMonitor: new battery level: 100,
,07-05 14:23:46.883  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:23:46.883  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:23:51.763  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 279 (W:28), CP = 238, LCD = 0
,07-05 14:23:51.843  3506  3516 I art     : Background sticky concurrent mark sweep GC freed 78506(8MB) AllocSpace objects, 304(6MB) LOS objects, 29% free, 35MB/50MB, paused 4.787ms total 108.382ms
,07-05 14:23:55.833  3506  4290 E Watchdog: !@Sync 43 [07-05 14:23:55.847]
,07-05 14:24:01.833  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 279 (W:28), CP = 238, LCD = 0
,07-05 14:24:11.873  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:28), CP = 238, LCD = 0
,07-05 14:24:16.873  3506  4446 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:16.883  3506  4446 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,07-05 14:24:16.883  3506  4446 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:24:16.883  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:24:16.893  3506  3506 I MotionRecognitionService: Plugged
07-05 14:24:16.893  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:24:16.893  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:24:16.893  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:24:16.893  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:24:16.893  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:24:16.893  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:24:16.893  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:24:16.903  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:24:16.903  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:24:16.903  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:16.903  3506  4446 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
07-05 14:24:16.903  3506  4446 D BatteryService: stay LED for fully charged
,07-05 14:24:16.923  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:24:16.933  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:24:16.933  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:24:16.933  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:16.933  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:24:16.933  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:24:21.913  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:28), CP = 238, LCD = 0
,07-05 14:24:25.843  3506  4290 E Watchdog: !@Sync 44 [07-05 14:24:25.855]
,07-05 14:24:29.403  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:24:31.973  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:30), CP = 238, LCD = 0
,07-05 14:24:42.013  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), CP = 238, LCD = 0
,07-05 14:24:46.923  3506  3524 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:24:46.923  3506  3524 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:24:46.923  3506  3524 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:24:46.923  3506  3524 D BatteryService: stay LED for fully charged
07-05 14:24:46.923  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:24:46.923  3506  3506 I MotionRecognitionService: Plugged
07-05 14:24:46.923  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:24:46.923  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:24:46.923  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:24:46.923  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:24:46.923  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:24:46.923  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:24:46.923  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:24:46.933  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:24:46.933  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:24:46.933  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:46.953  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:24:46.963  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:24:46.963  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:24:46.963  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:24:46.963  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:24:46.963  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:24:52.073  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), CP = 238, LCD = 0
,07-05 14:24:55.853  3506  4290 E Watchdog: !@Sync 45 [07-05 14:24:55.862]
,07-05 14:25:02.133  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 277 (W:30), CP = 238, LCD = 0
,07-05 14:25:12.143  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), CP = 238, LCD = 0
,07-05 14:25:16.983  3506  6505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:25:16.983  3506  6505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:25:16.983  3506  6505 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:25:16.983  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:25:16.983  3506  6505 D BatteryService: stay LED for fully charged
07-05 14:25:16.993  3506  3506 I MotionRecognitionService: Plugged
07-05 14:25:16.993  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:25:16.993  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:25:16.993  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:25:16.993  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:25:16.993  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:25:16.993  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:25:16.993  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:25:17.003  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:25:17.003  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
07-05 14:25:17.003  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:17.023  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:25:17.033  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:25:17.033  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:17.043  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:25:17.043  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:25:17.043  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:25:22.173  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), CP = 238, LCD = 0
,07-05 14:25:25.853  3506  4290 E Watchdog: !@Sync 46 [07-05 14:25:25.866]
,07-05 14:25:29.523  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:25:32.233  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:30), CP = 238, LCD = 0
,07-05 14:25:42.293  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), CP = 238, LCD = 0
,07-05 14:25:47.033  3506  3987 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:25:47.043  3506  3987 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:25:47.043  3506  3987 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:25:47.043  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:25:47.053  3506  3506 I MotionRecognitionService: Plugged
07-05 14:25:47.053  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:25:47.053  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:25:47.053  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:25:47.053  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:25:47.053  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:25:47.053  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:25:47.053  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:25:47.053  3506  3987 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms
07-05 14:25:47.053  3506  3987 D BatteryService: stay LED for fully charged
,07-05 14:25:47.063  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:47.063  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:25:47.063  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:25:47.073  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:25:47.083  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:47.083  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:25:47.083  4676  4676 D BatteryMonitor: new battery level: 100
,07-05 14:25:47.093  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:25:47.093  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:52.343  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), CP = 238, LCD = 0
,07-05 14:25:55.863  3506  4290 E Watchdog: !@Sync 47 [07-05 14:25:55.873]
,07-05 14:26:02.413  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:30), CP = 238, LCD = 0
,07-05 14:26:12.463  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), CP = 238, LCD = 0
,07-05 14:26:17.093  3506  4340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:26:17.093  3506  4340 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-05 14:26:17.093  3506  4340 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-05 14:26:17.093  3506  4340 D BatteryService: stay LED for fully charged
07-05 14:26:17.093  3506  3506 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:26:17.103  3506  3506 I MotionRecognitionService: Plugged
07-05 14:26:17.103  3506  3506 E MotionRecognitionService: support TA ~
07-05 14:26:17.103  3506  3506 I MotionRecognitionService: isTAConnected | current backoffstate  = 33792
07-05 14:26:17.103  3506  3506 D MotionRecognitionService:  TA connected ,  33792
07-05 14:26:17.103  3506  3506 I MotionRecognitionService: skip setTransmitPower. 
07-05 14:26:17.103  3506  3506 D MotionRecognitionService:   cableConnection= 1
07-05 14:26:17.103  3506  3506 D MotionRecognitionService: setPowerConnected | current backoffstate  = 33792 , state =33792
07-05 14:26:17.103  3506  3506 D MotionRecognitionService: skip setTransmitPower. 
07-05 14:26:17.103  4072  4072 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:26:17.103  4072  4072 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:17.113  4072  4072 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-05 14:26:17.133  4676  4676 D CommonServiceConfiguration: getStringValueSetting
,07-05 14:26:17.133  4676  4676 D BatteryMonitor: new battery level: 100
07-05 14:26:17.143  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:26:17.143  4072  4072 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:17.143  5399  5399 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:26:17.143  5399  5709 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:26:22.523  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), CP = 238, LCD = 0
,07-05 14:26:25.873  3506  4290 E Watchdog: !@Sync 48 [07-05 14:26:25.881]
,07-05 14:26:29.643  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:26:29.733  4515  4571 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 79ms lastUpdatedAfter : 180434ms
,07-05 14:26:32.593  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 274 (W:30), CP = 238, LCD = 0
,07-05 14:26:42.643  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), CP = 238, LCD = 0
,07-05 14:26:47.143  3506  6519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:52.713  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), CP = 238, LCD = 0
,07-05 14:26:55.873  3506  4290 E Watchdog: !@Sync 49 [07-05 14:26:55.888]
,07-05 14:27:02.773  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:30), CP = 238, LCD = 0
,07-05 14:27:12.833  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), CP = 238, LCD = 0
,07-05 14:27:17.203  3506  4115 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:22.903  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:30), CP = 238, LCD = 0
,07-05 14:27:25.883  3506  4290 E Watchdog: !@Sync 50 [07-05 14:27:25.895]
,07-05 14:27:26.283  3506  3928 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 14:27:26.283  3506  3928 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:27:26.293  3506  3927 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:27:29.843  4515  4571 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:27:31.903  3506  5450 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-05 14:27:31.913  3506  5450 V MARsPolicyManager: updateSMDBValues
,07-05 14:27:31.913  3506  3611 E MARsDBManager: updateDBAll : begin --size 0
07-05 14:27:31.913  3506  3611 E MARsDBManager: updateDBAll : end
,07-05 14:27:32.953  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 14:27:32.953  3506  3928 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:27:32.963  3506  6477 D SSRM:n  : SIOP:: AP = 280, PST = 272 (W:28), CP = 237, LCD = 0
,07-05 14:27:32.963  3506  3928 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:27:32.963  3506  3928 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:27:43.003  3506  6477 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:28), CP = 238, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms),07-05 14:27:46.703 12010 12010 I FIPS_bssl: FIPS approved mode (1) | 12010 | app_process
07-05 14:27:46.713 12010 12010 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:27:46.723 12010 12010 D AndroidRuntime: CheckJNI is OFF
07-05 14:27:46.723 12010 12010 D AndroidRuntime: readGMSProperty: start
07-05 14:27:46.723 12010 12010 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:27:46.723 12010 12010 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 14:27:46.723 12010 12010 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 14:27:46.723 12010 12010 D AndroidRuntime: readGMSProperty: end
07-05 14:27:46.723 12010 12010 D AndroidRuntime: addProductProperty: start
07-05 14:27:46.783 12010 12010 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:27:46.843 12010 12010 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:27:46.863 12010 12010 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:27:46.883 12010 12010 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 14:27:46.903  3506  3987 D PackageManager: START PACKAGE DELETE: observer{19645683}
07-05 14:27:46.903  3506  3987 D PackageManager: pkg{<packageName>}
07-05 14:27:46.903  3506  3987 D PackageManager: user{0}
07-05 14:27:46.903  3506  3987 D PackageManager: caller{2000}
07-05 14:27:46.903  3506  3987 D PackageManager: flags{2}
07-05 14:27:46.903  3506  3987 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 14:27:46.903  3506  3987 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 14:27:46.903  3506  3987 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 14:27:46.903  3506  3987 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:27:46.903  3506  3987 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:27:46.903  3506  3643 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 14:27:46.903  3506  3643 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 14:27:46.903  3506  3643 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 14:27:46.903  3506  3643 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 14:27:46.903  3506  3643 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 14:27:46.903  3506  3643 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 14:27:46.903  3506  3643 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 14:27:46.903  3506  3643 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-05 14:27:46.903  3506  3643 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 14:27:46.903  3506  3643 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 14:27:46.903  3506  3588 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-05 14:27:46.903  3506  3588 I ActivityManager: Killing 10812:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 14:27:46.903  3506  3588 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-05 14:27:46.913  3506  3588 D ActivityManager: mDVFSHelper.acquire()
07-05 14:27:46.933 12027 12027 E Zygote  : v2
07-05 14:27:46.933 12027 12027 I libpersona: KNOX_SDCARD checking this for 10004
07-05 14:27:46.933 12027 12027 I libpersona: KNOX_SDCARD not a persona
07-05 14:27:46.933  3506  3588 I ActivityManager: Start proc 12027:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-05 14:27:46.933 12027 12027 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SECMOBILE_6.0.1 ver=11
07-05 14:27:46.933 12027 12027 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [1], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:27:46.933 12027 12027 E Zygote  : accessInfo : 0
07-05 14:27:46.943 12027 12027 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 14:27:46.943  3506  3643 D mjtest  : there is not file
07-05 14:27:46.943  3506  3588 I ActivityManager:   Force finishing activity ActivityRecord{e403336 u0 com.test.thalitest/.MainActivity t19}
07-05 14:27:46.963 12027 12027 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:27:46.963 12027 12027 D ActivityThread: Added TimaKeyStore provider
07-05 14:27:47.013  3045  4538 D libEGL  : eglTerminate EGLDisplay = 0x7fa619ef88
07-05 14:27:47.013  3506  4115 I WindowState: WIN DEATH: Window{187330f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 14:27:47.013  3506  3987 D GraphicsStats: Buffer count: 3
07-05 14:27:47.013  3506  4520 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@718df6b)
07-05 14:27:47.013  3045  4538 D libEGL  : eglTerminate EGLDisplay = 0x7fa619ef88
07-05 14:27:47.013  3506  4000 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:27:47.013  3506  4000 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:27:47.013  3506  4000 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:27:47.013  3045  3130 I SurfaceFlinger: id=16 Removed NainActivit (6/9)
07-05 14:27:47.023  3045  4505 I SurfaceFlinger: id=16 Removed NainActivit (-2/9)
07-05 14:27:47.023  3045  3045 D libEGL  : eglTerminate EGLDisplay = 0x7fe403c798
07-05 14:27:47.023  3506  4115 D InputDispatcher: Focus left window: 10812
07-05 14:27:47.223  3506  4113 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:27:47.333  3506  3643 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-05 14:27:47.383  3506  3643 W PackageSettings: Skipping PackageSetting{34e114b com.example.hello/10189} due to missing metadata
07-05 14:27:47.443  3506  3643 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-05 14:27:47.443  3506  3615 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 14:27:47.453  3506  3615 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-05 14:27:47.453  3506  3615 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
07-05 14:27:47.453  3506  3615 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
07-05 14:27:47.453  3506  3615 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4373)
07-05 14:27:47.453  3506  3615 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13470)
07-05 14:27:47.453  3506  3615 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:27:47.453  3506  3615 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:27:47.453  3071  3071 W keystore: ENTER clear_uid from uid 1000 for 10004
07-05 14:27:47.453  3506  3615 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:27:47.453  3506  3615 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-05 14:27:47.453  3506  3615 D SecWifiDisplayUtil: Metadata value : SecSettings2
07-05 14:27:47.453  3506  3643 I art     : Starting a blocking GC Explicit
07-05 14:27:47.453  3506  3615 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{16beac8 V.E...... R.....ID 0,0-0,0}
07-05 14:27:47.463  3506  3615 D ISSUE_DEBUG: InputChannelName : 6ebb286 Starting com.test.thalitest
07-05 14:27:47.473  3045  3045 I SurfaceFlinger: id=18 createSurf (1528x2445),1 flag=4, VSBConnecti
07-05 14:27:47.503  4432  4432 D Launcher: onRestart, Launcher: 159958831
07-05 14:27:47.533  3506  3987 V WindowStateAnimator: Finishing drawing window Window{b3bfc1b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-05 14:27:47.543  3045  3045 D libEGL  : eglInitialize EGLDisplay = 0x7fe403c668
07-05 14:27:47.613  3506  3643 I art     : Explicit concurrent mark sweep GC freed 127298(7MB) AllocSpace objects, 144(2MB) LOS objects, 31% free, 34MB/50MB, paused 1.454ms total 162.150ms
07-05 14:27:47.643  3506  3643 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-05 14:27:47.643  3506  3643 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
07-05 14:27:47.643  3506  3643 D mjtest  : there is not file
07-05 14:27:47.643  3506  3643 D PackageManager: result of delete: 1{19645683}
07-05 14:27:47.653  3506  3643 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 14:27:47.653  3506  3643 D PackageManager: userId{-1}
07-05 14:27:47.653  3506  3643 D PackageManager: andCode{true}
07-05 14:27:47.653 12010 12010 I art     : System.exit called, status: 0
07-05 14:27:47.653 12010 12010 I AndroidRuntime: VM exiting with result code 0.
07-05 14:27:47.783  3506  3588 I WindowManager: Screenshot max retries 4 of Token{d6a8821 ActivityRecord{4ea688 u0 com.samsung.android.MtpApplication/.USBConnection t18}} appWin=Window{b3bfc1b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-05 14:27:47.783  3506  3506 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
07-05 14:27:47.803  3506  6519 I ActivityManager: Killing 9545:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #31
07-05 14:27:47.813  3506  3615 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3506 uid:1000
07-05 14:27:47.813  3506  3615 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:27:47.813  4432  4432 D Launcher: onStart, Launcher: 159958831
07-05 14:27:47.813  4432  4432 D Launcher.HomeView: onStart
07-05 14:27:47.813  3045  3045 I SurfaceFlinger: id=19 createSurf (1440x2560),1 flag=404, uhalitest
07-05 14:27:47.823  3506  3615 D ViewRootImpl: #3 mView = null
07-05 14:27:47.823  3045  3130 I SurfaceFlinger: id=19 Removed uhalitest (7/10)
07-05 14:27:47.823 12027 12027 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
07-05 14:27:47.833  4432  4432 D Launcher.MenuAppsGrid: ChangeMobileKeyboard:false mCurrentOrientation:1 mRequestedOrientation:1 newConfig.orientation:1 isShown:false
07-05 14:27:47.833  3506  3588 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
07-05 14:27:47.833  3506  3643 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
07-05 14:27:47.833  3506  3643 I ActivityManager: Killing 12027:com.test.thalitest/u0a4 (adj 9): stop com.test.thalitest cause pkg removed
07-05 14:27:47.833  4432  4432 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
07-05 14:27:47.833  3506  3643 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-05 14:27:47.833  4432  4432 D ResourcesManager: For user 0 new overlays fetched Null
07-05 14:27:47.843  3506  3643 I ActivityManager:   Force finishing activity ActivityRecord{e403336 u0 com.test.thalitest/.MainActivity t19 f}
07-05 14:27:47.843  3506  3643 W ActivityManager: Duplicate finish request for ActivityRecord{e403336 u0 com.test.thalitest/.MainActivity t19 f}
07-05 14:27:47.843  4432  4432 D ApplicationPackageManager: we has com.android.calendar class. reuse it 
07-05 14:27:47.853  4432  4432 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in com.sec.android.app.launcher rsrc of package com.android.calendar
07-05 14:27:47.853 10198 12043 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
07-05 14:27:47.863 10198 12043 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest

```
